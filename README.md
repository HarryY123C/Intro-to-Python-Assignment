# Basic Calculator Program

# Ask the user to input the first number
num1 = float(input("Enter the first number: "))

# Ask the user to input the second number
num2 = float(input("Enter the second number: "))

# Ask the user to choose an operation
operation = input("Enter an operation (+, -, *, /): ")

# Perform the chosen operation
if operation == "+":
    result = num1 + num2
    print(f"{num1} + {num2} = {result}")
elif operation == "-":
    result = num1 - num2
    print(f"{num1} - {num2} = {result}")
elif operation == "*":
    result = num1 * num2
    print(f"{num1} * {num2} = {result}")
elif operation == "/":
    if num2 != 0:
        result = num1 / num2
        print(f"{num1} / {num2} = {result}")
    else:
        print("Error: Division by zero is not allowed.")
else:
    print("Invalid operation. Please enter +, -, *, or /.")


# Intro-to-Python-Assignment
creating Python programs to perform arithmetic and string, experimenting with variables, and exploring data types.
# 🧮 Basic Calculator Program (Python)

## 📘 Overview

This is a simple Python command-line calculator program that performs basic arithmetic operations: **addition**, **subtraction**, **multiplication**, and **division**.  
The user is prompted to input two numbers and an operator, and the result of the operation is displayed clearly.

---

## 🚀 Features

- Accepts two numeric inputs from the user.
- Supports the following operations:
  - Addition (`+`)
  - Subtraction (`-`)
  - Multiplication (`*`)
  - Division (`/`)
- Gracefully handles:
  - Invalid operations
  - Division by zero

---

## 📋 How to Use

### ▶️ Step-by-step Instructions:

1. Make sure you have **Python 3.x** installed on your machine.
2. Save the script as `calculator.py`.
3. Open your terminal or command prompt.
4. Navigate to the folder containing `calculator.py`.
5. Run the script:

```bash
python calculator.py
👤 Author
Ukwuoma Harrison Chiedoziem
📧 ukwuomaharri@gmail.com
📍 Abuja, Nigeria
📅 Year: 2025



