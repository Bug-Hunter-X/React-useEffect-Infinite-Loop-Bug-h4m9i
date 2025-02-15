# React useEffect Infinite Loop

This repository demonstrates a common React bug involving an infinite loop within a `useEffect` hook. The bug arises from setting the state within the `useEffect` using a value derived from the current state without employing functional updates.  This results in an infinite render cycle.

The `bug.js` file contains the buggy code, while `bugSolution.js` presents the corrected version. This demonstrates the proper use of functional updates to prevent this issue.

## How to Reproduce the Bug

1. Clone the repository.
2. Run `npm install` to install dependencies.
3. Run `npm start` to start the development server.
4. Observe the infinite loop in the console and the continuously incrementing counter.