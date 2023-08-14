# Foundamentals 

## Why python

1. Python is versatile, we can build apps like data science, machine learning, web development and more
2. Strong communit, there's a package for everything
3. Easy to learn, it's like english and consice

### Variables and Data types

All the programming languages have the ability to store data information into variables to be used later for calculus or in the internal process. In python a variable is declared as next:

```python
amount = 10
amount_float = 10.50
```

If you have previous experience with other programming languages you may notice that there is not typing data for the variables, this means that python infers the data type of the `amount` variable as an `int` and `amount_float` as `float`.

## Interest calculator

Ok, so let's create our first program an interest calculator. Firstable let's understand what the program needs to do. The requirement says:
1. I want a program that prints the interest to pay by a giving amount and interest rate.
2. An interest is calculated by the next formula: f(x,t) = x + (x * t). Where x is the amount and t is the interest rate.
3. Like for example if my amount is 100 and my interest rate is 0.6 then my formula will be: f(100, 0.6) = 100 + (100*0.6)

### Hint

Python provides a function `print` to print any value in console. You just need to pass the value as parameter like the next example:
```python
print('Hello world!')
```

## Data type conversion and Strings

A common operation in programming languages is the data type conversion, python offers some functions to do that, like for example:

```python
amount = 100
amount_float = float(amount)
amount_int = int(amount_float)
print(amount_float) # 100.0
print(amount_int) # 100
```

Another data type really useful are strings. Strings can be declared using single quotation ('') or double quotation (""). Let's see some examples:

```python
name = 'Miguel'
last_name = 'Romero'
restaurant = "McDonald's"
```

You can use the operator `+` to concatenate strings in python.

```python
name = "John's"
last_name = 'Doe'
print(name + " " + last_name)
# advanced
# you can use f-strings(formatted strings)
# print(f'{name} {last_name}') 
```

Now let's take a look how to get information from the user. Similar as `print` function, python provides a function to wait for a text from the user, this function is called `input`.

```python
  text = input("What is your name?")
  print(text)
```

Great! Time for an excercise:

## Which time is it?

Build an app that gets a time as seconds and transform it into the next output:

"The time is XX hours with XX minutes and XX seconds"

Example:

Giving the input 12630
then the result is:
"The time is 3 hours with 30 minutes and 30 secods"

Requirements:

1. Ask the user time in seconds
2. Calculate the hours, minutes and seconds
3. Print them in the correct format

