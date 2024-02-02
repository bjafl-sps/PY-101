# 2.1: Data types drill

## Exercise 2.2.1: Working with Integers
Create an integer variable named age and assign it your age.
Print out the variable age.
## Exercise 2.2.2: Floating Point Operations
Create two float variables named height and weight and assign them any values.
Calculate and print the Body Mass Index (BMI) using the formula BMI = weight / (height * height).
## Exercise 2.2.3: Exploring Strings
Create a string variable named greeting and assign it the value "Hello, Python learners!".
Print the length of the string stored in greeting.
> *Hint:*
>
> The built in function `len(...)` calculates the length of data like strings and lists.
## Exercise 2.2.4: Boolean Logic Basics
Create two boolean variables: python_is_fun assigned True, python_is_hard assigned False.
Print the result of the logical AND operation between these two variables.
> *Hint:*
> Use the logical operator `and`

## Exercise 2.2.5: List Operations
Create a list named fruits containing the strings "apple", "banana", and "cherry".
Add "orange" to the list, then remove "apple".
Print the updated list.

> *Hint:*
>
> `list_name.append(item)` adds *item* to the list.
> `list_name.remove(item)` removes *item* to the list.

## Exercise 2.2.6: Tuple Basics
Create a tuple named coordinates with three numbers representing X, Y, and Z positions respectively.
Print the second element of the tuple.

> *Hint:*
>
> To get the nth item of a list or a tuple, you can use `[n]` after the list, see example below.
>
> NB: the first item has index ``0`` (not 1)

```python
random_list = ['a', 'b', 'c']
second_item = random_list[2] # Value of second_item: 'b'
```

## Exercise 2.2.7: Accessing Dictionary Values
Create a dictionary named person_info with keys "name", "age", and "city" - fill it with your information.
Print the "age" value from the dictionary.

> *Hint:*
> 
> The way to retreive a item from a dictionary is very similar to retriving nth item of a list. 

## Exercise 2.2.8: Set Operations
Create a set named colors containing "red", "blue", and "green".
Add "yellow" to the set and then remove "blue".
Print the updated set.

> *Hint:*
> 
> A set and a list is very similar. How did you add and remove items from lists? 


## Exercise 2.2.9: Using Range in a Loop
Use a for loop and range() to print numbers from 1 to 10 (inclusive).


> *Hint:*
> 
> This is the basic syntax of a for loop. We will talk more about loops later. If it doesn't make sense, look at the solution and see if you can understand what's going on. 
```python
for variable_name in range(...):
    # Do stuff here
    # Note that these lines are indented
```