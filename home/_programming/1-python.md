---
layout: article
title: Basic Guide To Learning Python
permalink: /programming/python
key: Python
cover: assets/images/tutorial covers/python.PNG
tags: 
- Programming
- Code
- Python
sidebar:
    nav: python
---

## Introduction

Python is known for its simplicity, readability, and flexibility, making it a great choice for beginners and experienced programmers alike. It has a large standard library and supports a wide range of third-party libraries and frameworks, making it easy to build powerful and complex applications. Overall, Python is a great choice for beginners and experienced programmers alike, and is well-suited for a wide range of tasks.

---

There are many reasons why Python is a great language to learn, and  including the following:

1. Python is easy to learn and use. It has a simple syntax and uses indentation to denote blocks of code, making it easy to read and understand.

2. Python is versatile. It can be used for a wide range of tasks, including web development, data analysis, scientific computing, and automation.

3. Python has a large and active community. There are many resources available online, including tutorials, documentation, and forums, which make it easy to find help and support when you need it.

4. Python has a large standard library and supports third-party libraries and frameworks. This makes it easy to build complex applications and get things done quickly.

Python is an interpreted language, which means that you don't need to compile your code before running it. You can simply type your code into a text editor and run it using the Python interpreter. 

Python uses indentation to denote blocks of code. This means that you need to be consistent with your indentation in order for your code to work correctly. In Python, you can use the `#` symbol to add comments to your code. Anything following the `#` symbol on a line is ignored by the interpreter. 

Python has a number of built-in data types, including integers, floating-point numbers, and strings. You can use these data types to store and manipulate data in your code. Python also has a number of built-in functions, such as `print()`, which you can use to output data to the console. 

Python uses variables to store and manipulate data. To create a variable, you simply need to give it a name and assign a value to it using the `=` operator.Python has a number of control structures, such as `if` statements and `for` loops, which you can use to control the flow of your program.

## Getting Started

To get started with Python, you will need to have a Python interpreter installed on your computer. You can download the latest version of Python from the official Python website (https://www.python.org/downloads/). 

Once you have Python installed, you can start writing and running Python code in a few different ways:

- You can use a text editor to write your code and then run it using the Python interpreter from the command line.

- You can use an integrated development environment (IDE) to write and run your code. IDEs are specialized software programs that provide a more feature-rich environment for writing and debugging code. Some popular IDEs for Python include PyCharm, Visual Studio Code, and Eclipse. *(Visual Studio Code is a popular IDE which we recommend*

- You can also use online platforms, such as repl.it, to write and run Python code directly in your web browser without having to install anything on your computer.

Once you have a way to write and run Python code, you can start learning the language by working through our tutorials or exercises/courses online. There are many resources available to help you learn Python, hopefully the resources here suit your learning!

## Lesson Guide

The Python lessons start with some simple basics to understand how to use code to perform tasks. This will build knowledge to write simple code to solve problems and work with simple data.

Exploring the standard library to begin with, will allow to branch into working with other libraries and frameworks to extend the capabilities of the language to build more complex and powerful applications!

- [Basics](#basics)
- [Looping Techniques](#looping-techniques)
- [Lists](#lists)
- [Functions](#functions)
- [Data Structures](#data-structures)
- [Modules](#modules)
- [Classes](#classes)

## Basics

Here we demonstrate how to use the `print()` function to output data to the console, how to use variables to store and manipulate data, how to use the `input()` function to get input from the user, and how to use an `if` statement to control the flow of the program based on a condition.

### Basic Example

```py
# This program prints "Hello, World!" to the console

# This is a comment. Anything following the # symbol on a line is ignored by the interpreter.

# Use the print() function to output a string to the console
print("Hello, World!")

# You can use variables to store and manipulate data
message = "Hello, World!"
print(message)

# You can use the + operator to concatenate strings
greeting = "Hello"
name = "Alice"
print(greeting + ", " + name + "!")

# You can use the input() function to get input from the user
name = input("What is your name? ")
print("Hello, " + name + "!")

# You can use if statements to control the flow of your program
age = int(input("What is your age? "))
if age >= 18:
  print("You are an adult.")
else:
  print("You are a minor.")
```

Using `if` statements within loops are explored in [Looping Techniques](#looping-techniques)

### Numbers

In Python, there are two types of numbers: integers and floating-point numbers.

An integer is a whole number, such as `1`, `42`, or `-7`. You can perform arithmetic operations with integers, such as addition, subtraction, multiplication, and division.

A floating-point number is a number with a decimal point, such as `3.14` or `-0.01`. You can also perform arithmetic operations with floating-point numbers.

Here are some examples of how to use numbers in Python:

```py
# Assign an integer to a variable
x = 42

# Assign a floating-point number to a variable
y = 3.14

# Perform arithmetic operations with variables
z = x + y  # 45.14
a = x * y  # 132.48
b = x / y  # 13.31
c = x - y  # 38.86
```

**Basic Number Example**

Here wi will demonstrate how to use `for` loops and `while` loops to repeat blocks for code. In this example we use the `range` function to create a sequence of numbers and use `break` and `continue` statements to control the loop logic.

Loops are explored in further detail in [Looping Techniques](#looping-techniques)

```py
# This program demonstrates how to use loops

# You can use a for loop to iterate over a sequence of items
for number in [1, 2, 3, 4, 5]:
  print(number)

# You can use a while loop to repeat a block of code as long as a condition is true
count = 0
while count < 5:
  print(count)
  count += 1

# You can use the range() function to generate a sequence of numbers
for number in range(5):
  print(number)

# You can also specify a start and end value for the range() function
for number in range(1, 5):
  print(number)

# You can use the break and continue statements to control the flow of a loop
for number in range(10):
  if number % 2 == 0:
    continue
  print(number)
  if number == 7:
    break
```

### Strings

In Python, a string is a sequence of characters, such as `"Hello, world!"` or `"abc123"`. You can use single or double quotes to define a string. You should pick one and keep consistent with your code.

You can use the `len()` function to get the length of a string, and you can use square brackets (`[]`) to access individual characters in a string.

Here are some examples of how to use strings in Python:

```py
# Assign a string to a variable
x = "Hello, world!"

# Get the length of a string
y = len(x)  # 13

# Access individual characters in a string
z = x[0]  # 'H'
a = x[-1]  # '!'

# Concatenate strings
b = x + " My name is Python."  # "Hello, world! My name is Python."

# Replace a portion of a string
c = x[:5] + "Python"  # "Hello Python, world!"

# Convert a string to uppercase or lowercase
d = x.upper()  # "HELLO, WORLD!"
e = x.lower()  # "hello, world!"

```

## Looping Techniques

Loops are an important feature in programming languages as they allow for a block of code to be repeated multiple times.

Their an essential tool for repeating tasks and making your code more efficient, and also means less writing for you!

Their commonly used for situations, such as:

- Iterating over a sequence of items

- Repeating a task until a certain condition is met

- Performing an action for a set number of times

- Processing data

### For Loops

A `for` loop iterates over a sequence of items, such as a list or a string. You can define a `for` loop using the `for` keyword, followed by a variable name, the `in` keyword, and the sequence. The code block within the `for` loop is indented. 

*To indent code you can use the `tab` key in most IDEs and some also can automatically indent for you!*

```py
# Define a list
x = [1, 2, 3, 4, 5]

# Iterate over the list with a for loop
for item in x:
  print(item)  # 1 2 3 4 5

```

You can also use the `range()` function to generate a sequence of numbers and iterate over it with a `for` loop. The `range()` function takes three arguments: a start number, an end number, and a step size.

```py
# Iterate over a range of numbers with a for loop
for i in range(1, 6, 1):
  print(i)  # 1 2 3 4 5

# Iterate over a range of numbers with a for loop, using a step size of 2
for i in range(1, 6, 2):
  print(i)  # 1 3 5

```

You can use the `enumerate()` function to iterate over a sequence and get the index and value of each item.

```py
# Define a list
x = ['apple', 'banana', 'cherry']

# Iterate over the list with the enumerate function
for i, item in enumerate(x):
  print(f"{i}: {item}")  # 0: apple 1: banana 2: cherry

```

### While Loops

A `while` loop executes a code block as long as a condition is true. You can define a `while` loop using the `while` keyword, followed by the condition. 

```py
# Define a variable
x = 0

# Iterate with a while loop
while x < 5:
  print(x)  # 0 1 2 3 4
  x += 1

```

You can use the `break` keyword to exit a loop prematurely, and you can use the `continue` keyword to skip the rest of the current iteration and move on to the next one.

```py
# Define a variable
x = 0

# Iterate with a while loop and use the break keyword
while True:
  print(x)  # 0 1 2 3 4
  x += 1
  if x >= 5:
    break

# Define a list
x = [1, 2, 3, 4, 5]

# Iterate over the list with a for loop and use the continue keyword
for item in x:
  if item % 2 == 0:
    continue
  print(item)  # 1 3 5

```

## Lists

In Python, a list is an ordered collection of items. You can define a list using square brackets (`[]`) and separating items with commas.

You can access items in a list using square brackets (`[]`) and an index number. The index numbers start at `0` for the first item, `1` for the second item, and so on. You can also use negative index numbers, with `-1` referring to the last item, `-2` referring to the second-to-last item, and so on.

You can use the `len()` function to get the length of a list, and you can use the `append()` method to add items to a list.

Here are some examples of how to use lists in Python:

```py
# Define a list
x = [1, 2, 3, 4, 5]

# Access items in a list
y = x[0]  # 1
z = x[-1]  # 5

# Get the length of a list
a = len(x)  # 5

# Add items to a list
x.append(6)  # [1, 2, 3, 4, 5, 6]

# Modify items in a list
x[0] = 0  # [0, 2, 3, 4, 5, 6]

# Remove items from a list
del x[2]  # [0, 2, 4, 5, 6]

```

## Functions

In Python, a function is a block of code that performs a specific task. You can define a function using the `def` keyword, followed by the function name and a set of parentheses that may contain parameters. The code block within the function is indented.

You can call a function by using its name followed by a set of parentheses that may contain arguments.

Here is an example of how to define and call a function in Python:

```py
# Define a function that takes two arguments and returns their sum
def add(x, y):
  return x + y

# Call the function and print the result
result = add(2, 3)  # 5
print(result)

```

You can also define default values for parameters, which means that the parameter will take on that default value if no argument is provided when the function is called.

```py
# Define a function that takes two arguments and returns their sum, with a default value for the second argument
def add(x, y=0):
  return x + y

# Call the function with one argument
result = add(2)  # 2
print(result)

# Call the function with two arguments
result = add(2, 3)  # 5
print(result)

```

## Data Structures

In Python, there are several built-in data structures that you can use to store and organize data.

### Tuples

A tuple is an immutable sequence type, meaning that you cannot modify the items in a tuple once it has been created. You can define a tuple using parentheses (`()`) and separating items with commas.

```py
# Define a tuple
x = (1, 2, 3)

# Access items in a tuple
y = x[0]  # 1

# Get the length of a tuple
z = len(x)  # 3

```

### Lists

A list is an ordered collection of items that is mutable, meaning that you can modify the items in a list once it has been created. You can define a list using square brackets (`[]`) and separating items with commas. Lists can contain items of different types, such as integers, floating-point numbers, strings, and even other lists.

```py
# Define a list
x = [1, 2, 3]

# Access items in a list
y = x[0]  # 1

# Get the length of a list
z = len(x)  # 3

# Add items to a list
x.append(4)  # [1, 2, 3, 4]

# Modify items in a list
x[0] = 0  # [0, 2, 3, 4]

# Remove items from a list
del x[2]  # [0, 2, 4]

```

### Dictionaries

A dictionary is a collection of key-value pairs, where the keys are unique within the dictionary. You can define a dictionary using curly braces (`{}`) and separating key-value pairs with commas.

```py
# Define a dictionary
x = {'name': 'Alice', 'age': 30, 'city': 'New York'}

# Access values in a dictionary
y = x['name']  # 'Alice'

# Add a key-value pair to a dictionary
x['country'] = 'United States'  # {'name': 'Alice', 'age': 30, 'city': 'New York', 'country': 'United States'}

# Modify a value in a dictionary
x['age'] = 31  # {'name': 'Alice', 'age': 31, 'city': 'New York', 'country': 'United States'}

# Remove a key-value pair from a dictionary
del x['country']  # {'name': 'Alice', 'age': 31, 'city': 'New York'}

```

### Sets

A set is an unordered collection of unique items. You can define a set using curly braces (`{}`) and separating items with commas.

```py
# Define a set
x = {1, 2, 3}

# Check if an item is in a set
y = 1 in x  # True

# Add an item to a set
x.add(4)  # {1, 2, 3, 4}

# Remove an item from a set
x.remove(3)  # {1, 2, 4}

```

## Modules

In Python, a module is a file containing Python code that you can reuse in your own programs. You can import a module using the `import` keyword, followed by the module name.

```py
# Import the math module
import math

# Use the pi constant from the math module
x = math.pi  # 3.141592653589793

# Use the sqrt function from the math module
y = math.sqrt(4)  # 2.0

```

You can also import specific items from a module using the `from` keyword and the `import` keyword, followed by the module name and a list of items separated by commas.

```py
# Import the pi constant and the sqrt function from the math module
from math import pi, sqrt

# Use the pi constant
x = pi  # 3.141592653589793

# Use the sqrt function
y = sqrt(4)  # 2.0

```

## Classes

In Python, a class is a template for creating objects. An object is an instance of a class, and it contains the attributes and behaviors defined by the class.

You can define a class using the `class` keyword, followed by the class name and a set of parentheses that may contain a base class. The code block within the class is indented.

```py
# Define a class
class Person:
  def __init__(self, name, age):
    self.name = name
    self.age = age
  
  def greet(self):
    print(f"Hello, my name is {self.name} and I am {self.age} years old.")

# Create an object of the Person class
person = Person("Alice", 30)

# Access the attributes of the object
print(person.name)  # "Alice"
print(person.age)  # 30

# Call the greet method of the object
person.greet()  # "Hello, my name is Alice and I am 30 years old."

```

You can also define class inheritance, where a subclass inherits attributes and behaviors from a base class. The subclass can override or extend the attributes and behaviors of the base class.

```py
# Define a base class
class Animal:
  def __init__(self, species, sound):
    self.species = species
    self.sound = sound
  
  def make_sound(self):
    print(self.sound)

# Define a subclass that inherits from the Animal base class
class Dog(Animal):
  def __init__(self, breed, name, sound):
    super().__init__("Dog", sound)
    self.breed = breed
    self.name = name

# Create an object of the Dog subclass
dog = Dog("Labrador", "Buddy", "Woof woof!")

# Access the attributes and behaviors of the object
print(dog.species)  # "Dog"
print(dog.sound)  # "Woof woof!"
print(dog.breed)  # "Labrador"
print(dog.name)  # "Buddy"
dog.make_sound()  # "Woof woof!"

```