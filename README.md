# MongoDB $inc Operator Error: Using String Instead of Number

This repository demonstrates a common error when using the `$inc` operator in MongoDB updates: providing a string value instead of a number.

The `bug.js` file contains code that attempts to increment a field with a string value. This will lead to an error.

The `bugSolution.js` file provides the corrected version, showing the correct usage of `$inc` with a numeric value.

## How to reproduce

1.  Clone this repository.
2.  Make sure you have MongoDB installed and running.
3.  Run the `bug.js` script. It will produce an error.
4.  Run the `bugSolution.js` script. It will successfully update the document.