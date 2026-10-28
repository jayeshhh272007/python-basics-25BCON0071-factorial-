# README Claims Audit — Factorial Calculator

## 1. Program Purpose
**Claim:** The program calculates the factorial of a number entered by the user.

**Status:** Supported

**Evidence:** The program accepts an integer as input and multiplies numbers from 1 to the entered number.

## 2. User Input
**Claim:** The program takes an integer as input.

**Status:** Supported

**Evidence:** The code uses `int(input("Enter a number: "))` to accept and convert user input to an integer.

## 3. Initialization
**Claim:** The program initializes the factorial to 1.

**Status:** Supported

**Evidence:** The variable `factorial` is initialized with the value `1`.

## 4. Loop Implementation
**Claim:** The program uses a `for` loop to multiply numbers from 1 to the entered number.

**Status:** Supported

**Evidence:** The loop `for i in range(1, n + 1):` iterates through the numbers from 1 to `n`, and `factorial *= i` updates the result.

## 5. Output
**Claim:** The program prints the calculated factorial.

**Status:** Supported

**Evidence:** The statement `print("Factorial:", factorial)` displays the result.

## 6. Example Output
**Claim:** For input `5`, the output is `Factorial: 120`.

**Status:** Supported

**Evidence:** The program multiplies 1 × 2 × 3 × 4 × 5, resulting in 120.

## 7. Learning Objectives
**Claim:** The program demonstrates Python input, variables, loops, and multiplication.

**Status:** Supported

**Evidence:** The code uses `input()`, variables `n`, `factorial`, and `i`, a `for` loop, and multiplication through `factorial *= i`.

## Conclusion
All the claims reviewed above are supported by the provided `factorial.py` implementation. No unsupported claims were identified.
