# Python Functions

## What is a Function?

A function is a block of reusable code that performs a specific task. Functions help to organize programs, avoid repetition, and improve readability.

---

## Defining a Function

Use the `def` keyword followed by the function name and parentheses `()`:

def greet():
print("Hello, World!")

---

## Calling a Function

Use the function name followed by parentheses:
greet() # Output: Hello, World!



---

## Function Parameters and Arguments

Functions can take inputs called **parameters** and you pass **arguments** when calling them.

def greet(name):
print("Hello, " + name + "!")

greet("Alice") # Output: Hello, Alice!



---

## Default Parameters

You can specify default values for parameters:

def greet(name="User"):
print("Hello, " + name + "!")

greet() # Output: Hello, User!
greet("Bob") # Output: Hello, Bob!



---

## Return Statement

Functions can return values using the `return` keyword.

def add(a, b):
return a + b

result = add(5, 3)
print(result) # Output: 8



---

## Variable Scope

- **Local variables:** Defined inside a function and accessible only within it.
- **Global variables:** Defined outside functions, accessible globally.

Example:

x = 10 # global

def func():
x = 5 # local
print(x)

func() # Prints 5
print(x) # Prints 10



---

## Lambda Functions (Anonymous Functions)

Short, unnamed functions:
square = lambda x: x * x
print(square(4)) # Output: 16



---

## Summary

- Functions make code reusable and modular.
- Define functions using `def` and call by name.
- Functions can accept parameters and return values.
- Understand local and global scope.
- Lambda functions provide concise function expressions.

---

Next chapter will cover Python collections such as lists, tuples, dictionaries, and sets.




