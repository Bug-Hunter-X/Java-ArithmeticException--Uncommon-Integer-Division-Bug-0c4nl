# Java ArithmeticException: Uncommon Integer Division Bug

This repository demonstrates a common yet easily overlooked error in Java: the `ArithmeticException` that occurs when performing integer division by zero.  The code in `UncommonBug.java` contains this error, which results in a runtime exception. The solution in `UncommonBugSolution.java` shows how to prevent the error using a simple conditional check.

## How to run:

1. Clone this repository.
2. Compile the `UncommonBug.java` file using a Java compiler (javac UncommonBug.java).
3. Run the compiled code (java UncommonBug) to observe the ArithmeticException.
4. Compile and run `UncommonBugSolution.java` (javac UncommonBugSolution.java && java UncommonBugSolution) to see the corrected version.