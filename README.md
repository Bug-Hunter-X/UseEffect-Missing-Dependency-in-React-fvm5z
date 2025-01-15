## React useEffect Missing Dependency
This repository demonstrates a common error in React's `useEffect` hook: a missing dependency causing an infinite loop. 
The `useEffect` hook is intended to perform side effects, such as data fetching or setting timers, after a component renders. However, if the dependency array is incorrect, the effect can run unexpectedly often, resulting in unwanted behavior.
In this example, the `setInterval` function is called repeatedly, causing an infinite loop.