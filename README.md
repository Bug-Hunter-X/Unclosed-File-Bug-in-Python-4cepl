# Unclosed File Bug in Python

This repository demonstrates a common error in Python: forgetting to close a file after opening it.  Leaving files open can lead to resource leaks, especially when dealing with many files or large files. This example shows the problem and a solution using the `with` statement.

## Bug Description
The `bug.py` file contains a function `function_with_unclosed_file` that opens a file but doesn't explicitly close it.  This leaves the file open, potentially leading to issues.

## Solution
The `bugSolution.py` file provides a corrected version using the `with` statement. This ensures the file is automatically closed, even if exceptions occur.