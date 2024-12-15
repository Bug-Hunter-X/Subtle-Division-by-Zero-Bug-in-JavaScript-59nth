# Subtle Division by Zero Bug in JavaScript

This repository demonstrates a subtle bug in JavaScript related to division by zero.  The code appears to handle the case of zero inputs, but it fails in a less obvious scenario due to type coercion.

## Bug Description

The `myFunction` function is designed to divide `a` by `b`, returning 0 if either `a` or `b` is 0.  However, it doesn't correctly handle cases where implicit type conversion leads to a division by zero.

## How to Reproduce

1. Clone the repository.
2. Run `bug.js`.
3. Observe the unexpected behavior when certain inputs are provided (e.g., a string that evaluates to 0).