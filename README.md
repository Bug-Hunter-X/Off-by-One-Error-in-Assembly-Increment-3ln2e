# Off-by-One Error in Assembly Increment

This repository demonstrates a common off-by-one error in assembly language programming.  The error arises from incorrect ordering of operations when attempting to increment a memory-resident variable.

## Bug Description
The provided `bug.asm` file contains an assembly code snippet that aims to increment a value at a specific memory location. Due to the incorrect order of operations (incrementing before reading), the result is incorrect.

## Bug Solution
The `bugSolution.asm` file presents the corrected code, where the value is read from memory, incremented, and then written back to the memory location.