# Unhandled Modulo Operator and Missing Input Validation

This repository demonstrates a common JavaScript coding error:  failure to handle all possible operators or input types in a function.

The `operate` function handles basic arithmetic but omits the modulo operator (`%`) and doesn't validate input types.  This can lead to unexpected behavior or errors.

The `bug.js` file contains the buggy code. The `bugSolution.js` file provides a corrected version.

## How to Reproduce

1. Clone this repository.
2. Run `bug.js`.
3. Observe the error when using the modulo operator or non-numeric inputs.  

## Solution

The solution includes thorough input validation and handling of the modulo operator.  It also addresses potential issues with non-numeric inputs.