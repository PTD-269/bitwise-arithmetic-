# Bitwise Arithmetic Project

## Overview
The Bitwise Arithmetic Project implements basic arithmetic operations (addition, subtraction, multiplication, and division) using bitwise operations in C. This project aims to demonstrate how fundamental arithmetic can be achieved without using traditional arithmetic operators, relying instead on bit manipulation techniques.

## Features
- **Addition**: Implements addition using bitwise XOR and AND operations.
- **Subtraction**: Implements subtraction using bitwise operations to calculate the difference.
- **Multiplication**: Implements multiplication using repeated addition and bit shifting.
- **Division**: Implements division using bitwise operations to calculate the quotient.

## Project Structure
bitwise-arithmetic

├── src/                        # Source files

    ├── arithmetic.c            # Implementation of arithmetic operations

    └── main.c                  # Main entry point of the program

├── include/                     # Header files

    └── arithmetic.h            # Function declarations for arithmetic operations

├── tests/                      # Unit tests

    └── test_arithmetic.c       # Unit tests for arithmetic operations

├── Makefile
                    # Build configuration
└── README.md                   # Project description and instructions

## Header File: `arithmetic.h`
The `arithmetic.h` header file contains the function declarations for the arithmetic operations implemented in the project. It serves as an interface for the `arithmetic.c` source file.

### Function Declarations
- `int bitwise_add(int a, int b);`
  - Adds two integers using bitwise operations.
  
- `int bitwise_subtract(int a, int b);`
  - Subtracts the second integer from the first using bitwise operations.
  
- `int bitwise_multiply(int a, int b);`
  - Multiplies two integers using bitwise operations.
  
- `int bitwise_divide(int a, int b);`
  - Divides the first integer by the second using bitwise operations. Returns 0 if division by zero is attempted.

## How to Build
To compile the project, navigate to the project directory and run:
make
./bitwise-arithmetic
