# React setInterval Memory Leak

This repository demonstrates a common error in React applications involving the `setInterval` function within the `useEffect` hook, leading to a memory leak.  The example shows how to fix this by using a cleanup function in `useEffect` to stop the interval when the component unmounts.