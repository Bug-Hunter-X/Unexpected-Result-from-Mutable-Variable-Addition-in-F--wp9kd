# F# Mutable Variable Bug

This repository demonstrates a subtle bug involving mutable variables in F#. The `add` function appears to correctly add two numbers, but the result is unexpected due to the way mutable variables are handled within the function's scope.

## Bug Description
The `bug.fs` file contains a function that adds two mutable variables. Despite the function seemingly performing addition, the output is not the sum of the initial values of `x` and `y`.

## Solution
The `bugSolution.fs` file offers a corrected approach. It explains the issue and demonstrates how to achieve the intended behavior using immutability or explicitly passing values to the function rather than relying on mutable variables that may be changed elsewhere in the program.