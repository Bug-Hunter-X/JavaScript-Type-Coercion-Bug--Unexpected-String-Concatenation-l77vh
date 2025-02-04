# JavaScript Type Coercion Bug

This repository demonstrates a common JavaScript bug caused by type coercion.  The `foo` function is intended to add two numbers. However, due to JavaScript's dynamic typing, when a number and a string are passed, string concatenation happens instead of numerical addition.

The `bug.js` file contains the erroneous code, while `bugSolution.js` provides a corrected version using explicit type checking or conversion.