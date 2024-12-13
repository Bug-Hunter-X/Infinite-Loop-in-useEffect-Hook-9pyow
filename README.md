# React useEffect Infinite Loop Bug

This repository demonstrates a common React bug involving the `useEffect` hook.  The bug occurs when a function inside the `useEffect` hook causes a state update which triggers a re-render, and the effect runs again, creating an infinite loop.