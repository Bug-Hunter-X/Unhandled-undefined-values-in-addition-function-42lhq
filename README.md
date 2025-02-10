# Unhandled Undefined Values in JavaScript Function

This repository demonstrates a common error in JavaScript where a function fails to handle undefined values appropriately. The `foo` function adds two numbers, but it only explicitly checks for `null` values. If either `a` or `b` is `undefined`, the addition will result in `NaN` (Not a Number), leading to unexpected behavior.

## Bug
The `bug.js` file contains the buggy code, which handles `null` but not `undefined` inputs.

## Solution
The `bugSolution.js` file demonstrates how to fix this bug by explicitly checking for both `null` and `undefined` values using the loose equality operator (`==`) or a stricter check using `typeof` operator.

## How to run

1. Clone the repository
2. Open `bug.js` and `bugSolution.js` in your preferred JavaScript environment or browser console.
3. Run the code to observe the different results.