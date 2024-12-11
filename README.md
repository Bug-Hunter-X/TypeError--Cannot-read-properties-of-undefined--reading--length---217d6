# JavaScript Bug: TypeError: Cannot read properties of undefined (reading 'length')

This repository demonstrates a common JavaScript error: `TypeError: Cannot read properties of undefined (reading 'length')`.  The error occurs when attempting to access the `length` property of a variable that is undefined.

## Bug Description
The provided JavaScript function `foo` attempts to return the length of the input `x`. However, it doesn't handle the case where `x` is undefined.  This leads to the `TypeError` when the code tries to access `x.length`.

## Bug Reproduction
1. Clone this repository.
2. Run `node bug.js`.
3. Observe the `TypeError` in the console.