## Variables & Assignments
Creating a Variable: Simply assign a value to a variable name.

```python
x = 10
name = "Alice"

# Multiple Assignments: Assign multiple variables at once.
a, b, c = 5, 3.2, "Hello"
```

## Basic Operations
Arithmetic: Addition (+), Subtraction (-), Multiplication (*), Division (/), Modulus (%), Exponentiation (**), Floor Division (//).

```python
sum = 7 + 3  # 10
difference = 7 - 3  # 4
product = 7 * 3  # 21
quotient = 7 / 3  # 2.333...
remainder = 7 % 3  # 1
```

Comparison: Equal to (==), Not equal to (!=), Greater than (>), Less than (<), Greater than or equal to (>=), Less than or equal to (<=).

```python
7 == 3  # False
7 != 3  # True
7 > 3   # True
```
List Operations
Creating a List: List are created using square brackets.

fruits = ["apple", "banana", "cherry"]
Accessing List Items: Items in a list are indexed starting from 0.

first_fruit = fruits[0]  # "apple"
Adding Items: Items can be added using the append() method.

fruits.append("orange")
Removing Items: Items can be removed using the remove() method.

fruits.remove("banana")
Logic Control Structures
If Statement:

if age < 18:
    print("Minor")
elif age == 18:
    print("Just turned 18")
else:
    print("Adult")
For Loop: Iterating over a sequence.

for fruit in fruits:
    print(fruit)
While Loop: Executing as long as a condition is true.

count = 5
while count > 0:
    print(count)
    count -= 1
Functions
Defining a Function:

def greet(name):
    return f"Hello, {name}!"
Calling a Function:

message = greet("Alice")
print(message)
Built-in Functions
print(): Display output.

len(): Return the length of an object.

int(), float(), str(): Convert to the respective type.

input(): Read a string from standard input.

range(): Generate a sequence of numbers.

print("Hello, World!")
number_of_fruits = len(fruits)
age = int(input("Enter your age: "))
This cheat sheet covers the very basics to get started with Python programming. As you progress, you'll encounter more complex data types, advanced functions, and Python's extensive standard libraries.