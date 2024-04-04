TITLE: CodTech IT Solutions Internship
TASK DOCUMENTATION:Java program for simple calculator with advance features
INTERN INFORMATION:
NAME: Thaduri Ravi Teja
ID: ICOD5519



# Calculator Program Documentation

## Introduction
This documentation provides an overview of the Java calculator program. The program implements basic and advanced mathematical operations
such as addition, subtraction, multiplication, division, exponentiation, and the option to quit.This program is designed to provide a 
simple yet functional calculator that performs basic arithmetic operations and includes some advanced features such as exponentiation and
the option to quit. Whether you're a beginner learning Java programming or an experienced developer looking for a basic calculator
implementation, this documentation will guide you through the program's features, usage, and code structure.

## Table of Contents
1. [Overview](#overview)
2. [Features](#features)
3. [Usage](#usage)
4. [Code Explanation](#code-explanation)
5. [Examples](#examples)
6. [Conclusion](#conclusion)

## Overview
The Java calculator program is designed to perform various mathematical operations based on user input. It provides a simple command-line
interface for users to choose an operation and input the required numbers.

## Features
- Addition
- Subtraction
- Multiplication
- Division (handling division by zero)
- Exponentiation
- Quit option
- Input validation for numeric inputs

## Usage
To use the calculator program:
1. Compile the Calculator.java file using a Java compiler.
2. Run the compiled program using the Java Virtual Machine (JVM).

Upon execution, the program will display a menu with operation choices. Enter the corresponding number for the operation you wish to
perform. Follow the on-screen instructions to input numbers when prompted.

### User Interaction:
- Choose an operation by entering the corresponding number from the menu.
- Follow the prompts to input numbers for calculations.
- View the result of each operation displayed by the program.
- Choose the "Quit" option to exit the program.

### Input Format:
- For addition, subtraction, multiplication, and division, enter numeric values when prompted.
- For exponentiation, enter the base and exponent as numeric values when prompted.

### Output Format:
- The program will display the result of each operation in a clear and formatted manner.
- In case of division by zero, an error message will be displayed, and the program will handle the error gracefully.

## Code Explanation
### Main Method (main)
- Initializes a Scanner object for user input.
- Displays the main menu and prompts the user for a choice.
- Uses a do-while loop to repeatedly process user input until the user chooses to quit.
- Calls specific methods based on the user's choice.

### Operations Methods
- performAddition: Takes two numbers as input and performs addition.
- performSubtraction: Takes two numbers as input and performs subtraction.
- performMultiplication: Takes two numbers as input and performs multiplication.
- performDivision: Takes two numbers as input and performs division, handling division by zero.
- performExponentiation: Takes two numbers as input and performs exponentiation.

### Input Validation
- Ensures numeric inputs are valid using Scanner methods like nextInt() and nextDouble().
- Checks for division by zero in the performDivision method.

## Examples
### Addition

Choose an operation:
1. Addition
2. Subtraction
3. Multiplication
4. Division
5. Exponentiation
6. Quit
Enter your choice: 1
Enter the first number: 10
Enter the second number: 5
Result: 15.0


### Division (Division by Zero Error)

Choose an operation:
1. Addition
2. Subtraction
3. Multiplication
4. Division
5. Exponentiation
6. Quit
Enter your choice: 4
Enter the numerator: 20
Enter the denominator: 0
Error: Division by zero is not allowed.


## Conclusion
The Java calculator program provides a user-friendly interface for performing basic and advanced mathematical operations. It demonstrates 
fundamental Java programming concepts such as user input handling, method invocation, and conditional statements. The program can be 
extended with additional functionalities and error handling as needed.
