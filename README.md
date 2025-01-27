# React Router Dom Unexpected Behavior
This repository demonstrates an uncommon bug encountered while using React Router Dom v6 with nested routes and route parameters.  The issue manifests as unexpected rendering behavior, including infinite redirects and incorrect page transitions.  The solution outlines how to resolve this, focusing on proper route definition and parameter handling.

## Bug Description
The provided code shows a seemingly straightforward nested routing structure using React Router Dom. However, under certain conditions, especially with dynamic segments, the routes may not render as anticipated leading to errors in navigation.

## Reproduction
Clone the repository and run `npm install`. Then, run `npm start`. Navigate through the different routes to observe the unexpected behavior.  The issue becomes more apparent when interacting with nested routes and route parameters.

## Solution
The solution implements the changes needed to fix the inconsistent route behavior. These changes address the issues of route parameter handling in nested routes. See the comments within the `bugSolution.js` file for details.