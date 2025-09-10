---
title: Calculator CLI
date: 2025-09-06
description: An updated version of my Python calculator with colored output for better user experience.
tags: [Python, Calculator, CLI, ANSI Colors]
---

## Description

A basic command-line calculator implemented in Python that performs arithmetic operations with colored output for enhanced user experience.

## Features

- Supports addition, subtraction, division, multiplication, squaring, and square root operations.
- User-friendly menu interface with numbered options.
- Color-coded output for results (green) and error messages (red) using ANSI escape codes.
- Error handling for invalid inputs and division by zero.
- Option to exit the program gracefully.

## Requirements

- Python 3.x
- The `math` module (included in Python's standard library)
- A terminal that supports ANSI color codes for colored output (most modern terminals support this)

## Usage

1. Clone or download the repository.
2. Navigate to the project directory.
3. Run the script using:
   ```bash
   python main.py
   ```
4. Follow the on-screen prompts to:
   - Select an operation by entering its corresponding number (1-7).
   - Enter one or two numbers as required by the chosen operation.
   - View the result (displayed in green) or exit the program.

## Example

```
Options:
1. Add
2. Subtract
3. Divide
4. Multiply
5. Squared
6. Square Root
7. Exit
Enter option number: 1
Enter first number: 5
Enter second number: 3

Result: 8.0
```

_Note_: The result will appear in green in a compatible terminal.

## Error Handling

- **Invalid Input**: If a non-numeric value is entered, the program displays "Please enter a number." in red and prompts again.
- **Keyboard Interrupt**: Pressing `Ctrl+C` will display "Program stopped by user." in red and exit gracefully.
