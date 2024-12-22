# C Bug: Array Out-of-Bounds Access

This repository demonstrates a common error in C programming: accessing memory beyond the bounds of an array. This can lead to undefined behavior, making debugging difficult.

## Bug Description
The `bug.c` file contains code that attempts to write to an array element beyond its allocated size. This causes undefined behavior, which might result in a crash, unexpected data corruption, or seemingly random results.

## Solution
The `bugSolution.c` file provides a corrected version of the code that avoids out-of-bounds access by ensuring that array indices remain within the valid range (0 to 4 in this case).