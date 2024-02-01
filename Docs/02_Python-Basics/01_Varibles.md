# 1. Introduction to Variables
Let's talk a bit more about variables. In Python, a *variable* is a named location in the computer's memory that can store data. Variables allow us to assign values to names, making it easier to manipulate and work with data in our programs.

## 1.1 Variable Declaration and Assignment
To declare a variable in Python, we simply need to choose a name for the variable and use the assignment operator `=` to assign a value to it. Here's an example:

```python
name = "John"
```
In the above example, we've declared a variable named name and assigned it the value `"John"`. The value can be of any data type, which means it can store different types of information in the computer memory, for example text or numbers. We will talk more about data types later. 

## 1.2 Variable Reassignment
Once a variable has been declared, we can change its value by assigning it a new value. Here's an example:
```python
age = 25
print(age)  # Output: 25

age = 30
print(age)  # Output: 30
```
In the above example, we initially assign the value 25 to the variable age. We then reassign the value 30 to age. The variable takes on the new value, and when we print it, we see the updated value.

## 1.3 Variable Naming Rules
When choosing names for variables, there are a few rules to keep in mind:

Variable names must start with a letter or an underscore. They cannot start with a number.
Variable names are case-sensitive. For example, `age` and `Age` are considered different variables.
Variable names can contain letters, numbers, and underscores. They cannot contain spaces or special characters.
It's recommended to use descriptive names that reflect the purpose of the variable.
Python reserved keywords (e.g., `if`, `while`, `for`) cannot be used as variable names.

> ### Naming Rules at a glance:
>- Must start with a letter (a-z, A-Z) or an underscore (_)
>- Can be followed by letters, digits (0-9), or underscores (_)
>- Keywords (reserved words like `if`, `while` and `for`)  cannot be used as variable names
>  
> &nbsp;

## Excercices
Now it's time for you to get in some exercise! Head over to the [python gym](/PythonGym/) and have fun with [variables](/PythonGym/02_Python-basics/01_Variables.md) 💪