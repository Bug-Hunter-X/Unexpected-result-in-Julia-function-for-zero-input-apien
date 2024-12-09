# Julia Function Bug

This repository contains a Julia function with a subtle bug related to handling zero input. The function aims to square positive numbers and return the negation of negative numbers.  However, the current implementation yields unexpected output when the input is zero.

The `bug.jl` file showcases the buggy code and its behavior. The solution is demonstrated in `bugSolution.jl`.

This example highlights a common issue: overlooking edge cases when defining functions.  Always consider how your function handles extreme or boundary values.
