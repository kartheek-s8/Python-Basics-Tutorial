# Python Control Statements

## What are Control Statements?

Control statements allow you to control the flow of execution of your program based on conditions or repetitions.

---

## Conditional Statements (If-Else)

These statements let your program make decisions.

### Syntax:
if condition:
# code block if condition is True
elif another_condition:
# code block if another_condition is True
else:
# code block if none above is True


### Example:

age = 18
if age >= 18:
print("You are an adult.")
else:
print("You are a minor.")



---

## Comparison Operators Used in Conditions

| Operator | Description          |
|----------|----------------------|
| `==`     | Equal to             |
| `!=`     | Not equal to         |
| `>`      | Greater than         |
| `<`      | Less than            |
| `>=`     | Greater than or equal to |
| `<=`     | Less than or equal to |

---

## Logical Operators in Conditions

- `and`: Both conditions must be True  
- `or`: At least one condition is True  
- `not`: Negates the condition

### Example:

age = 20
has_ID = True

if age >= 18 and has_ID:
print("Allowed entry")
else:
print("Entry denied")



---

## Looping Statements

Loops execute a block of code multiple times.

---

### While Loop

Repeatedly executes the code as long as the condition is True

count = 0
while count < 5:
print(count)
count += 1



---

### For Loop

Executes code for each item in a sequence (like list or range)

for i in range(5):
print(i)



---

### Break and Continue Statements

- `break` exits the loop immediately
- `continue` skips the current iteration and continues with the next

### Example:

for i in range(10):
if i == 5:
break # stop the loop
if i % 2 == 0:
continue # skip even numbers
print(i)



---

## Summary

- Use **if-elif-else** for conditional execution
- Use **while** and **for** loops for repetition
- Use **logical operators** to form complex conditions
- Use **break** and **continue** to control loop flow

---

Next chapter covers **Functions** - how to reuse code efficiently and organize programs.



