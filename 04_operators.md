# Python Operators and Expressions

## What are Operators?

Operators are special symbols or keywords that perform operations on one or more operands (variables or values) in Python.

## Types of Operators

1. **Arithmetic Operators:** Perform mathematical calculations  
   | Operator | Description      | Example         |
   |----------|------------------|-----------------|
   | `+`      | Addition         | `5 + 3 = 8`     |
   | `-`      | Subtraction      | `5 - 3 = 2`     |
   | `*`      | Multiplication   | `5 * 3 = 15`    |
   | `/`      | Division (float) | `5 / 2 = 2.5`   |
   | `//`     | Floor Division   | `5 // 2 = 2`    |
   | `%`      | Modulus (remainder) | `5 % 2 = 1`  |
   | `**`     | Exponentiation   | `2 ** 3 = 8`    |

2. **Comparison Operators:** Compare two values and return Boolean result  
   | Operator | Description         | Example          |
   |----------|---------------------|------------------|
   | `==`     | Equal to            | `5 == 5` is True |
   | `!=`     | Not equal to        | `5 != 3` is True |
   | `>`      | Greater than        | `5 > 3` is True  |
   | `<`      | Less than           | `5 < 3` is False |
   | `>=`     | Greater than or equal to| `5 >= 5` is True |
   | `<=`     | Less than or equal to | `5 <= 3` is False |

3. **Logical Operators:** Combine Boolean expressions  
   | Operator | Description       | Example                |
   |----------|-------------------|------------------------|
   | `and`    | Logical AND       | `True and False` is False |
   | `or`     | Logical OR        | `True or False` is True |
   | `not`    | Logical NOT       | `not True` is False    |

4. **Assignment Operators:** Assign values to variables  
   | Operator | Example               | Meaning               |
   |----------|-----------------------|-----------------------|
   | `=`      | `x = 5`               | Assign 5 to x         |
   | `+=`     | `x += 3` equivalent to `x = x + 3` |
   | `-=`     | `x -= 2` equivalent to `x = x - 2` |
   | `*=`     | `x *= 4` equivalent to `x = x * 4` |
   | `/=`     | `x /= 2` equivalent to `x = x / 2` |

---

## Expressions

- An **expression** is a combination of values, variables, and operators that can be evaluated to produce a result.
- Example:
x = 5
y = 3
z = x * 2 + y - 1
print(z) # Output: 12


- Expressions follow **operator precedence** rules (PEMDAS):
1. Parentheses
2. Exponentiation (`**`)
3. Multiplication, Division, Floor Division, Modulus
4. Addition and Subtraction

---

## Type Conversion in Expressions

- Python automatically converts data types when needed (implicit conversion)
- You can also convert types explicitly using functions:
- `int()`, `float()`, `str()`, `bool()`

Example:
x = 5 # int
y = 2.5 # float
z = x + y # float, result 7.5

int_z = int(z) # convert to int -> 7
str_z = str(z) # convert to string -> "7.5"



---

## Summary

- Operators perform operations such as arithmetic, comparison, logical operations, and assignment.
- Expressions are evaluated following operator precedence.
- Python allows both implicit and explicit data type conversions within expressions.

---

Next, we will explore control flow statements like conditionals and loops in Python.

