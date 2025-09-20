# Python Data Types

## What Are Data Types?

Data types define the kind of value a variable can hold in Python. They determine the operations that can be performed on the data.

Python is a **dynamically typed language**, which means you do not need to declare data types explicitly — the interpreter assigns the type automatically based on the value.

---

## Common Built-in Data Types

| Data Type | Description               | Example              |
|-----------|---------------------------|----------------------|
| `int`     | Integer numbers (whole numbers) | `x = 10`            |
| `float`   | Floating-point numbers (decimals) | `pi = 3.14`        |
| `complex` | Complex numbers (real + imaginary) | `z = 2 + 3j`      |
| `str`     | String of characters (text) | `name = "Alice"`     |
| `bool`    | Boolean values (`True` or `False`) | `flag = True`     |
| `list`    | Ordered, mutable sequence | `fruits = ["apple", "banana"]` |
| `tuple`   | Ordered, immutable sequence | `coords = (10, 20)` |
| `dict`    | Key-value pairs (mapping) | `person = {"name": "Bob", "age": 25}` |
| `set`     | Unordered collection of unique elements | `colors = {"red", "green"}` |

---

## Checking Data Type

Use the `type()` function to find the type of a variable or value:

x = 10
print(type(x)) # Output: <class 'int'>

name = "Alice"
print(type(name)) # Output: <class 'str'>



---

## Numeric Data Types

- `int`: Represents whole numbers, positive or negative, without decimal points.
- `float`: Represents real numbers with decimals.
- `complex`: Represents complex numbers with real and imaginary parts.

Examples:
a = 100 # int
b = 3.14 # float
c = 2 + 3j # complex



---

## Sequence Data Types

- `str`: Stores text as a sequence of characters.
- `list`: Mutable ordered sequence of elements.
- `tuple`: Immutable ordered sequence of elements.

Examples:
s = "Hello" # string
lst = # list
tup = (10, 20, 30) # tuple



---

## Mapping and Set Types

- `dict`: Collection of key-value pairs, useful for fast lookups.
- `set`: Unordered collection of unique elements.

Examples:
d = {"name": "Alice", "age": 21} # dictionary
colors = {"red", "green", "blue"} # set



---

## Boolean Type

Represents truth values:
flag1 = True
flag2 = False
Used in control flows and logical expressions.

---

## None Type

`None` represents the absence of a value, used to indicate "nothing" or "no value here".

x = None



---

## Summary

- Python has versatile built-in data types to handle different kinds of data.
- Data types are assigned dynamically.
- Understanding data types is essential for efficient programming and applying the right operations.

---

In the next chapter, we will learn about operators and expressions in Python.


