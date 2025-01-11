# React Native Native Module Not Found Error

This repository demonstrates a common issue in React Native development: the "Native module not found" error. This error occurs when your app tries to use a native module (a library with native iOS or Android components) that hasn't been properly linked or configured. This example showcases the problem and provides solutions.

## Problem

The provided `RNMissingModuleBug.js` file attempts to use a native module that is missing or improperly linked. When you run this code, you'll encounter an error similar to "Native module cannot be found".

## Solution

The `RNMissingModuleSolution.js` file demonstrates the steps to fix the issue.  It shows how to properly link the native module (in this case, a hypothetical module), ensuring that it's accessible from your JavaScript code.

## Steps to Reproduce

1. Clone the repository.
2. `cd` into the project directory.
3. Run `npm install` or `yarn install`.
4. Try running the `RNMissingModuleBug.js` file; it will fail.
5. Follow the instructions in `RNMissingModuleSolution.js` to fix the error and run it.