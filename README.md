# Simple Calculator in Python
# Professional Portfolio Project

def add(a, b):
    return a + b

def subtract(a, b):
    return a - b

def multiply(a, b):
    return a * b

def divide(a, b):
    if b == 0:
        return "Error: Cannot divide by zero"
    return a / b

print("--- Simple Calculator ---")
num1 = float(input("Enter the first number: "))
num2 = float(input("Enter the second number: "))

print(f"Sum: {add(num1, num2)}")
print(f"Difference: {subtract(num1, num2)}")
print(f"Product: {multiply(num1, num2)}")
print(f"Quotient: {divide(num1, num2)}")
