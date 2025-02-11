# React Infinite Loop Bug
This repository demonstrates a common error in React involving an infinite loop caused by improper usage of the `useEffect` hook.  The `bug.js` file contains the buggy code, and `bugSolution.js` provides a corrected version.

**Bug Description:**
The `useEffect` hook is used incorrectly to update state.  This leads to an infinite loop because the component re-renders continuously.

**Solution:**
The solution uses the functional update pattern for setting state to correct the infinite loop.