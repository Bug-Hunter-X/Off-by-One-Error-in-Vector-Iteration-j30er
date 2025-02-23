# Off-by-One Error in C++ Vector Iteration

This repository demonstrates a common off-by-one error in C++ when iterating through a `std::vector`. The error arises from using `<=` in the loop condition instead of `<`, resulting in an attempt to access an element beyond the vector's bounds.  This can lead to undefined behavior, crashes, or subtle bugs.

The `bug.cpp` file contains the erroneous code, while `bugSolution.cpp` provides the corrected version.