# Simple Python Calculator

This is a simple command-line calculator application written in Python. It allows users to perform basic arithmetic operations: addition, subtraction, multiplication, and division.

## Features

*   **Addition (+):** Adds two numbers.
*   **Subtraction (-):** Subtracts the second number from the first.
*   **Multiplication (*):** Multiplies two numbers.
*   **Division (/):** Divides the first number by the second. Includes error handling for division by zero.
*   **Input Validation:** Catches non-numeric inputs for numbers.
*   **Continuous Calculation:** Allows performing multiple calculations until the user chooses to exit.

## How to Run

1.  **Save the code:** Save the provided Python code as a `.py` file (e.g., `calculator.py`).

2.  **Run from terminal:** Open your terminal or command prompt, navigate to the directory where you saved the file, and run the script using Python:
    ```bash
    python calculator.py
    ```

3.  **Follow the prompts:** The application will guide you through entering numbers and selecting an operator.

## Example Usage

```
Welcome to the simple calculator!
Enter first number: 8
Enter second number: 9
Enter operator (+, -, *, /): +
Result: 17.0
Do you want to perform another calculation? (yes/no): yes
Enter first number: 10
Enter second number: 0
Enter operator (+, -, *, /): /
Result: Error: Division by zero is not allowed. Please enter a non-zero second number.
Do you want to perform another calculation? (yes/no): no
Thank you for using the calculator. Goodbye!
```

## Project Structure

-   `calculator.py`: Contains the main calculator logic and execution flow.

```
