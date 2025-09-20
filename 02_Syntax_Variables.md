# Python Syntax and Variables

## Python Syntax Basics

- Python is an **interpreted** language executed line-by-line.
- It uses **indentation (spaces or tabs)** to define blocks of code instead of braces `{}` like other languages.
- Indentation level is important; inconsistent indentation causes errors.
- Python statements usually end at the newline; no need for semicolons.
- Comments start with `#` for single-line comments.
- Multi-line comments can use triple quotes `''' comment '''` or `""" comment """`.

### Example:
if 5 > 2:
print("Five is greater than two")



---

## Variables in Python

- Variables are **containers** for storing data values.
- You do **not** need to declare variable types explicitly (Python is dynamically typed).
- Variable names must start with a letter or underscore `_` and can contain letters, digits, and underscores.
- Variable names are **case-sensitive** (`var` and `Var` are different).
- Avoid using Python **reserved keywords** as variable names (like `if`, `for`, `break`).

### Creating Variables and Assigning Values

name = "Alice" # string
age = 21 # integer
height = 5.7 # float
is_student = True # boolean

Printing variables
print(name)
print(age)


---

## Common Python Data Types

| Data Type | Description               | Example           |
|-----------|---------------------------|-------------------|
| `int`     | Integer numbers           | `age = 21`        |
| `float`   | Decimal/floating-point    | `height = 5.7`    |
| `str`     | Text string               | `name = "Alice"`  |
| `bool`    | Boolean (True/False)      | `is_student = True`|

---

## Naming Conventions for Variables

- Use meaningful names: `total_score`, `user_age`.
- Use lowercase letters and underscores (`snake_case`) for readability.
- Avoid single-character names except in small loops or temp variables.

---

## Multiple Assignment

Python supports assigning multiple variables in one line:

x, y, z = 5, 10, 15
print(x, y, z) # Output: 5 10 15



---

## Change Variable Value

Variables can be reassigned anytime with a new value or data type:

age = 21
age = 22 # Reassigned
print(age) # Output: 22





---

## Summary

- Python syntax is simple and uses **indentation** instead of braces.
- Variables hold data and do not require explicit declaration.
- Variable names must follow naming rules and conventions.
- Python supports multiple data types and dynamic typing.

In the next chapter, we will explore **Python data types** in more detail with operators and expressions.



