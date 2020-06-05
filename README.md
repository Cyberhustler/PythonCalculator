# PythonCalculator
Ryan and Yashens Calculator with mod verification!
 - version 0.0.0.1
  _ Success atlast...(DEXTER VOICE)
    - This calculator via python checks for the 4 basic constructs and then generates a fail safe for the 0 divisioning erranoues section 
    that users try to mess calculators with! TRY IT!
# Simple calculator

def add(x, y):
    return x + y


# Function subtract
def minus(x, y):
    return x - y


# Function divide
def divide(x, y):
    return x / y


# Function multiply
def multiply(x, y):
    return x * y


# Variable First Number
iNum1 = float(input("Enter your 1st Number: "))
# Operator Input
simple_calculator = input("Enter Operator: ")
# Variable Second Number
iNum2 = float(input("Enter your 2nd Number: "))

if simple_calculator == '+':
    print(iNum1, "+", iNum2, "=", add(iNum1, iNum2))
elif simple_calculator == '-':
    print(iNum1, "-", iNum2, "=", minus(iNum1, iNum2))
elif simple_calculator == '*':
    print(iNum1, "*", iNum2, "=", multiply(iNum1, iNum2))
elif simple_calculator == '/':
    if iNum2 == 0:
        print("Cannot divide by error.")
    else:
        print(iNum1 / iNum2)
