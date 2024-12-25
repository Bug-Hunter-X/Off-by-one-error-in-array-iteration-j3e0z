# Off-by-one Error in Array Iteration

This repository demonstrates a common off-by-one error in Java when iterating over an array.  The error results in an `ArrayIndexOutOfBoundsException`.

## Bug Description

The `bug.java` file contains a `for` loop that iterates one element past the end of the array, leading to an index out of bounds error.

## Solution

The `bugSolution.java` file provides the corrected code. The loop condition is changed to `< array.length` to prevent the error.

## How to Run

1. Clone the repository.
2. Compile and run the `bug.java` file to observe the exception.
3. Compile and run the `bugSolution.java` file to see the corrected output.