# React useEffect Cleanup Issue

This repository demonstrates a common React issue where the cleanup function in a `useEffect` hook is not called when expected. This can lead to memory leaks or unexpected behavior if the effect has side effects like subscriptions or timers.

## Bug

The `bug.js` file shows a component where the useEffect cleanup function is not called correctly. The component renders a simple counter and logs the count to the console.  The issue lies in when and how often the cleanup function is run.