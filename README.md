# ArrayIndexOutOfBoundsException Bug in Java

This repository demonstrates a common Java programming error: an `ArrayIndexOutOfBoundsException`. The bug is caused by an off-by-one error in a for loop, attempting to access an array element beyond its bounds.

The `bug.java` file contains the erroneous code. The `bugSolution.java` file provides the corrected version.

## How to reproduce:

1.  Clone this repository.
2.  Compile and run `bug.java` using a Java compiler (e.g., javac).
3.  Observe the `ArrayIndexOutOfBoundsException`.
4.  Compile and run `bugSolution.java` to see the corrected output.

## Learning points:

*   Always double-check loop bounds when working with arrays.
*   Be mindful of the difference between `<` and `<=` when using array indices.
*   Use exception handling (try-catch blocks) to gracefully manage potential exceptions.