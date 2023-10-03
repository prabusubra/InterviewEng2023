
1. React Virtual DOM
2. React Profiler
3. Error boundery
     - static getDerivedStateFromError - update the state with error, so that component will render fallback component.
     - componentDidCatch - can log error message.
5. React Lifecycle
6. React Context --> Communication channel, doesn't bother about data organization.
7. controlled (component is controlled by parent component props) vs uncontrolled Component 
8. lazy loading --> React.lazy() and React.Suspense fallback={<div>Loading...</div>}
9. Performance Optimization
    - use shouldComponentUpdate.
    - Not mutate state or props, use spread operator and provide new object everytime.
    - avoid accesing dom directly.
10. 
   
