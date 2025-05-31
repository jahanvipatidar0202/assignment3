# assignment3
## task1 and task2
Task1 is a simple Python script that calculates the factorial of a number entered by the user using a recursive function. task2  Python script prompts the user to enter a number and then performs several mathematical operations using Python's built-in math module:
Square root
Natural logarithm
Sine (in radians)
## Features
## task1
1.Prompts the user to enter a number.
2.Calculates the factorial of the number using recursion.
3.Displays the result in a readable format.
## task2
1.Prompts the user to enter a number.
2.Performs several mathematical operation using pythons's built-in math madule .
3.Display the result in readable format.
## code task 1
n = int(input("Enter a number : "))
def factorial(n):
    if n<2:
        return 1
    else:
        return n*(factorial(n-1))
result = factorial(n)
print(f"factorial of {n} is : {result}")
## code task2 
from math import *
n = int(input("Enter a number : "))
print(f"Square root is : {(sqrt(n))}")
print(f"logarithm  : {(log(n))}")
print(f"sine : {(sin(n))}")
        

