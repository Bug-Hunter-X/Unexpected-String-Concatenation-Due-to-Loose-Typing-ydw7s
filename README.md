# Unexpected String Concatenation in JavaScript

This repository demonstrates a common JavaScript bug caused by the language's loose typing system. The `foo` function is intended to add two numbers, but due to implicit type coercion, it concatenates strings if one of the inputs is a string.

## Bug

The `bug.js` file contains a function that unintentionally concatenates a number and a string. The result is unexpected and can lead to subtle errors in larger applications.

## Solution

The `bugSolution.js` file provides a corrected version of the function that explicitly checks the input types and handles them appropriately.

## How to Reproduce

1. Clone this repository.
2. Open `bug.js` and run the code in a JavaScript environment (e.g., Node.js or a browser's developer console).
3. Observe the unexpected output.
4. Open `bugSolution.js` to see the corrected version.
