# ActionScript 3 ReferenceError #1069: Property not found on prototype chain

This repository demonstrates a common ActionScript 3 error and its solution. The error, ReferenceError #1069, arises when a property or variable is accessed before it's been properly declared or initialized in its scope.

## The Bug

The `bug.as` file contains a function that attempts to use a variable before it's been declared or initialized leading to the ReferenceError. This can occur due to typos, logical errors, or asynchronous operations.

## The Solution

The `bugSolution.as` file presents a corrected version where the variable is explicitly declared and initialized before use, eliminating the error.  This ensures that the variable exists within the expected scope before any operations are performed on it.

## How to Reproduce

1. Compile and run `bug.as`.  Observe the ReferenceError.
2. Compile and run `bugSolution.as`. Observe the corrected output.