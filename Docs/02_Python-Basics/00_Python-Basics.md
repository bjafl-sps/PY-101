# Beginner Lesson in Python Syntax and Variables
## Python Syntax
Syntax refers to the set of rules determining how code should be written. Just as grammar shapes languages, adhering to Python's syntax ensures code is readable and executable by computers. The syntax in Python is pretty easy and readable, which makes it suitable for beginners. 

### 1. Comments
Let's start with comments! When writing code, it's useful to provide comments to human readers. This makes it easier to remember what different parts of the code is doing, and helps others reading your code to understand it. Comments are ignored by the computer during execution.

In Python comments start with the character #

```python
# This is a comment in Python
```

### 2. Statements
A statement is a single instruction that performs a specific action or task within a program. It represents the smallest standalone unit of code that the computer can execute to accomplish a particular operation.

Python statements are executed line-by-line and each statement ends with a newline character.

```python
# The following code has three statements

a = 5  # Assignment statement
b = 3 + 2  # Arithmetic expression as a statement
print(a)  # Function call statement
```
### 3. Operations
Operations in programming refer to actions or manipulations performed on data. This includes simple arithmetic operations like addition and subtraction, as well as logical operations such as comparisons (equal to, not equal to, greater than, less than). An operation can also manipulate strings or assign values to variables. Operators are the symbols or statements `+`, `-`, `len()`, and so on.

Below are some examples of basic operators in Python

```python
# Arithmetic Operations
a = 10
b = 5

addition = a + b
subtraction = a - b
multiplication = a * b
division = a / b
modulo = a % b
exponentiation = a ** b

# Comparison Operations
x = 10
y = 5

x == y  # False
x != y  # True
x > y   # True
x < y   # False
x >= y  # True
x <= y  # False

# String Operations
text1 = "Hello"
text2 = "World"

concatenation = text1 + " " + text2 # Yields "Hello World"
len(text1) # Yields 5

```
Note the difference between `=` and `==`. The first is the assign operator, which assigns a value to a variable. The latter is a comparison operator, that compares one variable or value to another. Also note that `+` can mean different things depending on the context. A `+` between two numbers will perform a mathematical addition. A `+` between to strings will join (concatenate) these strings together to a new string.

### 4. Functions
Functions contain code to perform defined operations. Using functions make your code more organized, and easier to manage. Functions also allows you to reuse by allowing the reuse a set of instructions. Don't copy-paste code you use several times, use functions instead!

In python you use the keyword `def` to define a function:
```python
# This is a simple python function:
def hi():
    print('Hello!')
```
### 4. Indentation
Python uses indentation to define blocks of code. Proper indentation is crucial for determining the scope of code blocks.

```python
if a > b:
    print("This code is indented correctly")
else:
print("This is not indented correctly")  # Incorrect indentation will result in an error
```
## Variables in Python
### 1. Variable Naming Rules
- Must start with a letter (a-z, A-Z) or an underscore (_)
- Can be followed by letters, digits (0-9), or underscores (_)
- Keywords (reserved words) cannot be used as variable names
### 2. Variable Assignment
Variables are created and assigned values using the = operator.

```python
my_var = 10  # Assigns the value 10 to the variable 'my_var'
```

### 3. Data Types
Python is dynamically typed, so you don't need to declare a variable's data type explicitly.

```python
# Examples of different data types
num = 10  # Integer
pi = 3.14  # Float
text = "Hello, Python!"  # String
is_valid = True  # Boolean

# Check the data type using the 'type()' function
print(type(num))  # Output: <class 'int'>
print(type(pi))  # Output: <class 'float'>
print(type(text))  # Output: <class 'str'>
print(type(is_valid))  # Output: <class 'bool'>
```

### 4. Variable Reassignment
Variables in Python can be reassigned to different values of any data type.

```python
my_var = 5
my_var = "Hello"  # Valid - my_var changes from an integer to a string
```
### 5. Multiple Assignment
Python allows multiple variables to be assigned values in a single line.

```python
a, b, c = 5, 10, 15  # Assigns 5 to a, 10 to b, and 15 to c
```
As a general rule it's not a good idea to assign multiple variables in a single line. This makes the code harder to read. Sometimes it's ok or useful to do so, but often its better to write a few extra lines than to compress several operations into a single line. The following rewriting og the above code will be easier to read:
```python
# Assigning each variable on a separate line makes the code easier to read:
a = 5
b = 10
c = 15
```