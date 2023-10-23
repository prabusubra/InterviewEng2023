# InterviewEng2023

# Rumango Softwares

1. what is immutable cass in java?
2. use a stream API to find highest salaried employee?
3. Functional Interface?
4. what is dead lock and how to avoid it?
5. Executors framework?
6. what is singleton design pattern and how to break it?
7. 

# Zycus:-

1. What do you do if there is any outofmemory error happens?
2. How to analyze heap dump?
3. What is the use of immutable class?
4. How to do you header among all the controllers?
5. Transactions in spring?
6. Garbage collector in java?
7. How to break singleton design pattern?
8. Database indexes?
9. How to decide which column to be indexed?
10. What is marker interface?
11. What are different types of class loader? And it's chain of responsibility?
12. How to log a execution time after execution of list of controllers?


# EPAM round1:-
1. What is immutable class? How to break ?
2. Java spring question to count employee based on gender.
3. Hashmap internals?
4. Big o notation for hashmap?
5. Find immediate largest element  in the array?
6. What is functional interface?
7. What is predicate functional interface?
8. Anonymous function?

# EPAM round2:
* Let vs var key
* Const key can be modfiable.
* How to create immutable object in javascript
* Deep copy vs shallow copy
* What is usecallback?
* Can we replace context with redux
* Lazy loading
* @controller vs restcontroller
* Find unique character using stream.

# HDFC:-
* Micro frontend?
* Create two micro service and communicate via feign client.
* Reverse a string without using extra space?
* What is outofmemory error? Is it checked or unchecked exception?
* What is qualifier in spring?
* System diagram of current app.
* How authentication and authorisation works?
* what is second-level cache in hibernate?

# Troposheresolutions

1. What is singleton patterns. What is the use of it?
2. Restcontroller vs controller
3. What is useState and useEffect.
4. What is equivalent of componentdidunmount in functional component.
5. What is interface?
6. Private methods in interface?
7. Diff abstraction class and interface?
8. Rest api get vs post?
9. Limitation of get?
10. Query param character limit?


# HCL

1. how to not use caching in spring JPA?
2. diff Controller vs RestController?
3. what is Qualifier annotation?
4. what is deep and shallow copy?
5. how to decide whether react component has to render or not?
6. how to get previous state of react component?
7. best practises to improve react performance?
8. what is useMemo vs useCallback?
9. what is multithread in js? webworkers vs service workers?
10. setTimer function?

# Boeing

1. write a code for a class which extends interface?
2. create a code for factory design pattern?
3. diff abstract class vs interface?
4. can we have a private methods in interface?
5. write a code for incrementor/decrementor using ReactJS?
6. explain about your project structure?
7. 
 
# RoyalCyber

1. Diff class component vs functional components in reactjs.
2. What webAPI vs callstack vs eventloop
3. Lifecyle methods
4. useEffect and useState hooks
5. How redux works?
6. Given a list of names:
   List<String> list = Arrays.asList( "Alice", "Bob", "Charlie", "David", "Emily", "Frank")
   write a Java 8 program to:
     Filter out names with more than 4 letters.
     Transform the remaining names to uppercase.
     Print each transformed name.
       Ans:- list.stream().filter(data -> data.length > 4).map(data -> data.toUpperCase(Locale.US)).forEach(System.out::println);
   
8. Given an array nums containing n distinct numbers in the range [0, n], return the only number in the range that is missing from the array

# goDigit

1. write a program to find next highest number for given number in an array ?
  int[] arr = {55, 66, 77, 78, 65, 33}; for input 33, output is 55  
2. write a program to find an element using binary search ?
3. design patterns used in micro services?
4. how to handle authentication and authorization in microservice?
5. how to handle logs in microservice?
6. how to handle transaction in microservice?
7. annotation used in springboot?
8. restcontroller vs controller?
9. in springboot, how to provide ouput in both json and xml format?
10. what is deadlock and how to handle it?

# Sony
1. what is lookup annotation?
2. what is dependency injection?
3. how to create 2 different session factory?
4. what is cyclic barrier?
5. what is map and reducer?
6. what is flatmap?
7. what is sharding?
8. sql vs nosql
9. saga pattern?
10. 2phase commit?
11. count a character question?
12. CQRS?
13. 

# Random:-

1. Rest vs Restfull service.
2. Thread lifecycle states?
3. How to connect 2 different database in spring?
4. What is profiler in spring ?
5. When to use comparator vs comparable?
6. Print even and odd numbers from 2 threads? One should print even other should print odd alternatively till 10.
7. Serialization/Externalization? What is the significant of version id?
8. What is String intern?
9. diff countdown latch vs cyclic barrier vs phaser?
10. fatory design pattern vs abstract factory pattern?
11. can we have a private field in interface?
    No, All the fields are public, static and final in interface.
    Fields in interface are accessible by interface or class not using object.
    if a class implements 2 interfaces which are having same field name will have issue only if we access and use the field.
    if a class implements 2 interfaces which are having same method name will have issue, it will be solved by overriding the method in subclass.
13. 




* How to disable autoconfiguration ?
Ans:- spring.autoconfigure.exclude=org.springframework.boot.autoconfigure.security.servlet.SecurityAutoConfiguration

*  How to optimize Spring boot?
Use lazy bean initialization using @Lazy annotation.
Disable unwanted autoconfiguration.
Profile specific configuration.
Limit component scanning using @scanBasePackages annotation.

STAR Questions:-
1. Tell me about when you missed a deadline?
2. Tell me about a time you have disagreed with a  senior member of staff?


