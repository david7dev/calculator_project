# 🧮 Calculator

A simple interactive command-line calculator built in Python, featuring a retro ASCII art logo.

## Features

- Basic arithmetic operations: addition, subtraction, multiplication and division
- Accumulated calculation mode — continue operating on the previous result
- ASCII art interface displayed on startup
- Option to start a new calculation or chain operations seamlessly

## Project Structure

```
.
├── art.py            # ASCII art logo
└── calculator_main.py  # Main calculator logic
```

## Requirements

- Python 3.x
- No external dependencies

## How to Run

```bash
python calculator_main.py
```

## Usage

1. Enter the first number when prompted.
2. Choose an operation (`+`, `-`, `*`, `/`).
3. Enter the second number.
4. View the result.
5. Type `y` to continue calculating with the current result, or `n` to restart.

## Example

```
Type the first number: 10
+
-
*
/
Choose an operation: +
Type the second number: 5
10.0 + 5.0 = 15.0
Type 'y' to continue calculating with 15.0, or type 'n' to start a new calculation.
```
