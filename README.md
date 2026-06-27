# CodeAlpha_Calculator
# Basic Calculator Program (C)

A simple menu-driven calculator program written in C that performs basic arithmetic operations using switch-case statements.

## Features
- Addition, Subtraction, Multiplication, and Division
- Menu-driven interface that runs continuously until the user exits
- Input validation for invalid menu choices
- Division-by-zero handling
- Clean output formatted to 2 decimal places

## Concepts Used
- `switch` case statements
- `while` loop for menu repetition
- Conditional statements (`if-else`)
- Basic input/output functions (`scanf`, `printf`)

## How It Works
1. The program displays a menu with 5 options (Add, Subtract, Multiply, Divide, Exit).
2. The user enters a choice (1–5).
3. If the choice is between 1–4, the user is prompted to enter two numbers.
4. The corresponding arithmetic operation is performed using `switch-case`.
5. The result is displayed, and the menu appears again.
6. Choosing option 5 exits the program.

## Sample Output
----- Calculator Menu -----

Addition
Subtraction
Multiplication
Division
Exit

Enter your choice (1-5): 1

Enter two numbers: 10 5

Result: 10.00 + 5.00 = 15.00

----- Calculator Menu -----

...

Enter your choice (1-5): 5

Exiting program. Goodbye!

## How to Run
1. Compile the program:
gcc calculator.c -o calculator
2. Run the executable:
./calculator

## Author
Lokeshwari — CodeAlpha C Programming Internship
