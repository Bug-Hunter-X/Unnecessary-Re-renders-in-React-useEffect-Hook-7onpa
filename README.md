# Unnecessary Re-renders in React useEffect Hook

This repository demonstrates a common React bug: an `useEffect` hook that runs after every render due to a missing or incorrect dependency array.  This leads to unnecessary re-renders and potential performance issues, particularly with computationally expensive operations within the effect.

The `bug.js` file showcases the problem, while `bugSolution.js` presents the corrected code.