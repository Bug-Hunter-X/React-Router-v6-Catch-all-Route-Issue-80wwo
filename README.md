# React Router v6 Catch-all Route Bug

This repository demonstrates a common issue encountered when using catch-all routes (`/*`) in React Router v6. The catch-all route is unexpectedly triggered even when other routes should match.  This example shows the problem and provides a solution.

## Problem
The problem is in `App.js`. The catch all route `/*` should only be triggered if no other route matches but it is triggered when it shouldn't be. 

## Solution
The solution is provided in `AppSolution.js` which addresses the issue by ensuring the catch-all route is placed correctly in the route hierarchy to make sure that the catch-all route only activates if no other routes match. 