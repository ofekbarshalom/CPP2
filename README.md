# Matrix Operator Project

This project implements a `SquareMat` class in C++ that represents a square matrix of `double`s and supports a wide variety of operators including arithmetic, comparison, element-wise operations, and advanced matrix functionalities such as transpose and determinant.

## Files

- `SquareMat.hpp` – Class declaration
- `SquareMat.cpp` – Class implementation
- `main.cpp` – Demonstrates usage of `SquareMat`
- `test.cpp` – Unit tests using the [doctest](https://github.com/doctest/doctest) framework
- `Makefile` – Compile/test automation

## Features

The `SquareMat` class supports:
- Arithmetic operators: `+`, `-`, `*`, `/`, `%`, `^`
- Compound assignment: `+=`, `-=`, `*=`, `/=`, `%=`
- Unary: `-`, `!`, `~`
- Comparison: `==`, `!=`, `<`, `>`, `<=`, `>=`
- Pre/Post increment/decrement: `++`, `--`
- Element access: `matrix[row][col]`
- Helper functions: `sum()`, `getMinor()`

## Build and Run

### Requirements
- C++20 compiler (e.g., `g++`)
- Make
- Optional: `valgrind` for memory checks

### Compile

To build the main demo:
```bash
make Main
