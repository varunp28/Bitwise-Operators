# Bitwise-Operators
AIM:
To understand and implement Bitwise Operators in C++.

OBJECTIVE:
Understand the concept and working of bitwise operators.

Learn how to apply them to perform bit-level operations in C++.

Practice writing C++ programs using bitwise operators for tasks such as bit manipulation, masking, and shifting.

TOOLS REQUIRED:
C++ Compiler (GCC, Turbo C++, etc.)

Text Editor or IDE (Code::Blocks, VS Code, Dev C++, etc.)

THEORY:
Bitwise operators operate directly on the binary representation of integers. They are primarily used for low-level programming, such as in device drivers, embedded systems, and performance-critical code.

The main Bitwise Operators in C++ are:
& (Bitwise AND): Returns 1 only if both bits are 1.
Example: 5 & 3 results in 1 because 0101 & 0011 = 0001.

| (Bitwise OR): Returns 1 if at least one of the bits is 1.
Example: 5 | 3 results in 7 because 0101 | 0011 = 0111.

^ (Bitwise XOR): Returns 1 if the bits are different.
Example: 5 ^ 3 results in 6 because 0101 ^ 0011 = 0110.

~ (Bitwise NOT): Inverts all the bits (also called one's complement).
Example: ~5 results in -6.

<< (Left Shift): Shifts bits to the left, filling with 0 on the right.
Example: 5 << 1 results in 10 because it moves all bits one place to the left.

>> (Right Shift): Shifts bits to the right, discarding bits on the right.
Example: 5 >> 1 results in 2.
