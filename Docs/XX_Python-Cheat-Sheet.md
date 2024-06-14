## Variables & Assignments
Creating a Variable: Simply assign a value to a variable name.

```python
x = 10
name = "Alice"

# Multiple Assignments: Assign multiple variables at once.
a, b, c = 5, 3.2, "Hello"
```

## Basic Operations
### Arithmetic: 
Addition (+), Subtraction (-), Multiplication (*), Division (/), Modulus (%), Exponentiation (**), Floor Division (//).

```python
sum = 7 + 3  # 10
difference = 7 - 3  # 4
product = 7 * 3  # 21
quotient = 7 / 3  # 2.333...
remainder = 7 % 3  # 1
```

### Comparison: 
Equal to (==), Not equal to (!=), Greater than (>), Less than (<), Greater than or equal to (>=), Less than or equal to (<=).

```python
7 == 3  # False
7 != 3  # True
7 > 3   # True
```
## List Operations
### Creating a List: 
List are created using square brackets.

```python
fruits = ["apple", "banana", "cherry"]
```
### Accessing List Items: 
Items in a list are indexed starting from 0.

```python
first_fruit = fruits[0]  # "apple"
```
### Adding Items: 
Items can be added using the append() method.

```python
fruits.append("orange")
```
### Removing Items: 
Items can be removed using the remove() method.

```python
fruits.remove("banana")
```
## Logic Control Structures
### If Statement:

```python
if age < 18:
    print("Minor")
elif age == 18:
    print("Just turned 18")
else:
    print("Adult")
```
### For Loop: 
Iterating over a sequence.

```python
for fruit in fruits:
    print(fruit)
```
### While Loop: 
Executing as long as a condition is true.

```python
count = 5
while count > 0:
    print(count)
    count -= 1
```
## Functions
### Defining a Function:

```python
def greet(name):
    return f"Hello, {name}!"
```
### Calling a Function:

```python
message = greet("Alice")
print(message)
```
## Built-in Functions
```python
print(var) # Print data to console, in this case the value of variable var.

len(var) # Return the length of an object, in this case var.

# Type conversion
int(var) # Convert var to int.
float(var) # Convert var to float.
str(var) # Convert var to string.

s = input('prompt') # Read a string from standard input, store in variable s. Optional: prints a prompt to the console first.

range(...) # Generate a sequence of numbers.
range(5) # Example sequence: 0,1,2,3,4
range(2, 10, 2) # Example sequence: 2,4,6,8
```

# Bonus: Example program using a few basic control structures and functions
```python
print("Hello, You!")
f_name = input("Enter first name: ")
s_name = input("Enter surname: ")
age = int(input("Enter your age: "))
len_fname = len(f_name)
len_sname = len(s_name)

print(f"Hi Mr. {s_name}!")
print(f"{age} years old, eh? That's a fine age!")

short_name = s_name if len_fname > len_sname else f_name
print("I'm gonna call you", end=" ")
if (len_fname != len_sname):
    name = short_name.capitalize()
    print(f"{name}. I'm lazy, and it's your shortest name ...")
else:
    print("...")
    print("I usually call people by their shortest name, but your names are the same length!")
    print("I'm too lazy to figure out what to call you, so you have to decide ...")
    nickname = input("What should I call you? ")
    n_prompts = 0
    while (len(nickname) > len(short_name)):
        n_prompts += 1
        if (n_prompts > 4):
            print("f**k you! I don't have time for this cr*p!")
            response = input(f"I'll just call you {f_name}, write ok to accept: ")
            if (response == "ok"):
                nickname = f_name
                break
            else:
                print("I give up! Nice not knowing you !!")
                exit(1)
        if (n_prompts > 3):
            print("My patience is running out!!")
            nickname = input("One last chance - what should I call you? ")
        else:
            nickname = input("Come on! That's longer than your real names! Give me a shorter nickname! ")
    name = nickname.capitalize()
    
print(f"Okay then Mr. {age}-years old. You'll be known as", end=" ")
name_chars = ""
for c in name:
    name_chars += c.upper() + "-"
print(name_chars.strip("- "))
print(f"Nice meeting you {name}! Now I need a nap...")
```
