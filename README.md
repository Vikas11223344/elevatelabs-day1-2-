# Simple Calculator

A tiny command-line calculator written in Python. It supports basic arithmetic operations: addition, subtraction, multiplication, and division. The program presents a simple menu, accepts two numeric inputs, performs the selected operation, and prints the result.

## Features
- Addition, subtraction, multiplication and division.
- Handles invalid numeric input.
- Handles division-by-zero with a clear error message.
- Simple interactive menu-driven CLI.

## Requirements
- Python 3.6+ (works with any modern Python 3.x)

## Files
- `calculator.py` — main program implementing the calculator operations and menu.

## Usage

1. Run the calculator:
```bash
python calculator.py
```

2. Follow the on-screen menu:
- Enter the number corresponding to the operation (1–4) or `5` to exit.
- Enter two numbers when prompted. Non-numeric inputs are rejected and you'll be asked again.
- Division by zero prints an error message: `Error! Division by zero.`

Example session:
```text
----- Simple Calculator -----
1. Addition (+)
2. Subtraction (-)
3. Multiplication (*)
4. Division (/)
5. Exit
-----------------------------
Enter your choice (1-5): 1
Enter first number: 3
Enter second number: 4
Result: 3.0 + 4.0 = 7.0
```

## Functions
- add(a, b) — returns a + b
- subtract(a, b) — returns a - b
- multiply(a, b) — returns a * b
- divide(a, b) — returns a / b or the string `"Error! Division by zero."` when b is 0

