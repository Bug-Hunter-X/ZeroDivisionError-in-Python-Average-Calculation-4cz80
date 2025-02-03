# Python Average Calculation with Empty List Handling

This repository demonstrates a common error in Python when calculating the average of a list of numbers: the `ZeroDivisionError`. The provided code includes a solution to address this error.

## Bug
The original code fails if an empty list is passed to the `calculate_average` function, raising a `ZeroDivisionError` because division by zero is attempted.  This is a common off-by-one error or boundary condition problem.

## Solution
The corrected code handles the case of an empty list by returning 0 in that scenario, preventing the error.