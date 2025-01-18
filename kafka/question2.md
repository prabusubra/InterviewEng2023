### What is the use of acks in the Producer?
 - The ***acks*** configuration in Kafka determines how much acknowledgment the Kafka broker must receive before it considers a message successfully written.
 - Configuration Options:
     - acks=0:
          - The producer does not wait for any acknowledgment from the broker.
          - The producer assumes the message is successfully written as soon as it is sent.
          - Pro: Very fast as no network round trip is required.
          - Con: High risk of message loss if the broker never receives the message.
     - acks=1: - default
          - The leader broker acknowledges the message as soon as it writes it to its local log.
          - Pro: Provides a balance between reliability and performance.
          - Con: If the leader crashes before replicating the message to followers, the message may be lost.
     - acks=all or -1 :
         - The leader broker waits for acknowledgment from all in-sync replicas (ISRs) before confirming the message.
         - Pro: Ensures maximum durability. Messages are guaranteed to persist even if the leader fails.
         - Con: Higher latency due to waiting for replication.
### Why is acks Important?
  - Controls the trade-off between performance and durability.
  - In critical systems where message loss is unacceptable, use acks=all.
  - For high-throughput scenarios where some data loss is tolerable, acks=0 or acks=1 may suffice.
