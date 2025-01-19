# Stack Overflow in Recursive Factorial Function

This repository demonstrates a common error in recursive functions: stack overflow. The `foo` function calculates the factorial recursively.  For large input values of `x`, the recursion depth exceeds the call stack limit, leading to a stack overflow error.

The solution demonstrates an iterative approach to calculate the factorial, avoiding the deep recursion and thus the stack overflow problem.