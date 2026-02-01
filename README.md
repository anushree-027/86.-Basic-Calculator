# 86.-Basic-Calculator
def add(x, y): return x + y
def subtract(x, y): return x - y
def multiply(x, y): return x * y
def divide(x, y): return x / y

n1 = float(input("Enter first number: "))
n2 = float(input("Enter second number: "))
op = input("Enter operation (+, -, *, /): ")

if op == '+':
    print("Result:", add(n1, n2))
elif op == '-':
    print("Result:", subtract(n1, n2))
elif op == '*':
    print("Result:", multiply(n1, n2))
elif op == '/':
    print("Result:", divide(n1, n2))
else:
    print("Invalid entry")
