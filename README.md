# React Router Dom v6 Catch All Route Not Working

This repository demonstrates a common issue encountered when using the catch-all route (`/*`) in React Router Dom v6.  The catch-all route, intended to handle any unmatched paths, may not work as expected if not placed correctly in the `Routes` component. This example showcases the problem and its solution.

## Problem
The provided `bug.js` demonstrates an implementation where the catch-all route (`/*`) doesn't function as intended.  Despite its position, other routes take precedence, making the catch-all ineffective.

## Solution
The `bugSolution.js` file offers a corrected implementation.  The solution involves carefully placing the catch-all route after other specific routes to ensure that it only catches paths not matched by prior routes.