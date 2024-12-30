# React Router v6 Nested Routes Issue

This repository demonstrates a common issue encountered when working with nested routes in React Router v6.  The problem lies in how nested routes are defined and accessed, leading to unexpected behavior where nested routes fail to render even when the parent route renders correctly.  The solution provided fixes this issue by ensuring that the nested routes are properly defined and accessible within the parent route component.

## Problem
The initial `App.js` file contains a flawed implementation of nested routes.  Despite the parent route rendering correctly, the nested routes do not render as expected.

## Solution
The `AppSolution.js` file provides a corrected implementation.  It demonstrates the correct way to define and access nested routes, ensuring proper rendering of the nested components.