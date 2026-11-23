# 🐍 Complete Python Programming – From Basics to Advanced

\<p align="center">
&#x20; \<img src="[https://img.shields.io/badge/Python-Programming-blue?style=for-the-badge&logo=python&logoColor=white](https://img.shields.io/badge/Python-Programming-blue?style=for-the-badge\&logo=python\&logoColor=white)" />
&#x20; \<img src="[https://img.shields.io/badge/Level-Beginner%20to%20Advanced-success?style=for-the-badge](https://img.shields.io/badge/Level-Beginner%20to%20Advanced-success?style=for-the-badge)" />
&#x20; \<img src="[https://img.shields.io/badge/Domain-Data%20Science-orange?style=for-the-badge](https://img.shields.io/badge/Domain-Data%20Science-orange?style=for-the-badge)" />
&#x20; \<img src="[https://img.shields.io/badge/Status-Learning%20Resource-purple?style=for-the-badge](https://img.shields.io/badge/Status-Learning%20Resource-purple?style=for-the-badge)" />
\</p>

Welcome to the **Complete Python Programming Repository!**

This repository is designed to help students, beginners, aspiring developers and data science enthusiasts learn Python programming from the fundamentals to advanced concepts.

Each topic includes:

- Easy-to-understand explanations.
- Python syntax.
- Practical code examples.
- Expected outputs.
- Real-world applications.
- Important concepts and best practices.

The goal is to build strong programming fundamentals and prepare learners for careers in Data Analytics, Data Science, Machine Learning, Artificial Intelligence and Generative AI.

---

# 📚 Table of Contents

## 🟢 LEVEL 1 – Python Basics

1. [Introduction to Python](#1-introduction-to-python)
2. [Python Installation and Environment](#2-python-installation-and-environment)
3. [Python Variables](#3-python-variables)
4. [Python Comments](#4-python-comments)
5. [Python Data Types](#5-python-data-types)
6. [Python Numbers](#6-python-numbers)
7. [Python Strings](#7-python-strings)
8. [Python Type Conversion](#8-python-type-conversion)
9. [Python Operators](#9-python-operators)
10. [Python Input and Output](#10-python-input-and-output)
11. [Conditional Statements](#11-conditional-statements)
12. [Python Loops](#12-python-loops)
13. [Python Lists](#13-python-lists)
14. [Python Tuples](#14-python-tuples)
15. [Python Sets](#15-python-sets)
16. [Python Dictionaries](#16-python-dictionaries)

## 🟡 LEVEL 2 – Python Intermediate

17. [Python Functions](#17-python-functions)
18. [Function Arguments](#18-function-arguments)
19. [Lambda Functions](#19-lambda-functions)
20. [Map Function](#20-map-function)
21. [Filter Function](#21-filter-function)
22. [Reduce Function](#22-reduce-function)
23. [List Comprehension](#23-list-comprehension)
24. [Dictionary Comprehension](#24-dictionary-comprehension)
25. [Python Modules](#25-python-modules)
26. [Python File Handling](#26-python-file-handling)
27. [Python Exception Handling](#27-python-exception-handling)
28. [Python Math Module](#28-python-math-module)

## 🔴 LEVEL 3 – Python Advanced

29. [Object-Oriented Programming](#29-object-oriented-programming)
30. [Classes and Objects](#30-classes-and-objects)
31. [Constructors](#31-constructors)
32. [Inheritance](#32-inheritance)
33. [Polymorphism](#33-polymorphism)
34. [Encapsulation](#34-encapsulation)
35. [Abstraction](#35-abstraction)
36. [Static Methods and Class Methods](#36-static-methods-and-class-methods)
37. [Super Keyword](#37-super-keyword)
38. [Shallow Copy and Deep Copy](#38-shallow-copy-and-deep-copy)
39. [Recursion](#39-recursion)
40. [Iterators and Generators](#40-iterators-and-generators)
41. [Decorators](#41-decorators)
42. [Arrays Without NumPy](#42-arrays-without-numpy)

## 🔵 LEVEL 4 – Python for Data Science

43. [Introduction to NumPy](#43-introduction-to-numpy)
44. [NumPy Arrays](#44-numpy-arrays)
45. [NumPy Indexing and Slicing](#45-numpy-indexing-and-slicing)
46. [NumPy Operations](#46-numpy-operations)
47. [Introduction to Pandas](#47-introduction-to-pandas)
48. [Pandas Series](#48-pandas-series)
49. [Pandas DataFrame](#49-pandas-dataframe)
50. [Data Selection and Filtering](#50-data-selection-and-filtering)
51. [Handling Missing Values](#51-handling-missing-values)
52. [Removing Duplicates](#52-removing-duplicates)
53. [Data Transformation](#53-data-transformation)
54. [Sorting and Grouping](#54-sorting-and-grouping)
55. [Matplotlib](#55-matplotlib)
56. [Seaborn](#56-seaborn)

---

# 🟢 LEVEL 1 – PYTHON BASICS

# 1. Introduction to Python

## What is Python?

Python is a high-level, interpreted, general-purpose programming language known for its simple syntax and readability.

Python was created by **Guido van Rossum** and first released in 1991.

Python is widely used in:

- Data Science
- Data Analytics
- Artificial Intelligence
- Machine Learning
- Deep Learning
- Web Development
- Automation
- Generative AI
- Natural Language Processing

### Why Learn Python?

1. Easy to learn and understand.
2. Simple and readable syntax.
3. Large collection of libraries.
4. Strong community support.
5. Suitable for beginners and professionals.
6. Supports multiple programming paradigms.

### First Python Program

**Syntax:**

```python
print("Your message")
```

**Example:**

```python
print("Hello World")
print("Welcome to Python Programming")
```

**Output:**

```text
Hello World
Welcome to Python Programming
```

The `print()` function displays information on the screen.

---

# 2. Python Installation and Environment

To execute Python programs, we need to install Python and choose a development environment.

### Installation

Download Python:

[https://www.python.org/downloads/](https://www.python.org/downloads/)

Popular development environments:

- VS Code
- Jupyter Notebook
- Google Colab
- PyCharm
- Spyder

### Check Python Version

```bash
python --version
```

### Install Libraries

```bash
pip install numpy
pip install pandas
pip install matplotlib
pip install seaborn
```

### Execute Python File

```bash
python filename.py
```

---

# 3. Python Variables

## What is a Variable?

A variable is a named memory reference used to store and access data in a Python program.

Python automatically determines the data type based on the assigned value.

### Syntax

```python
variable_name = value
```

### Example

```python
name = "Kamal"
age = 25
salary = 45000
percentage = 85.5

print(name)
print(age)
print(salary)
print(percentage)
```

**Output:**

```text
Kamal
25
45000
85.5
```

### Multiple Variable Assignment

```python
a, b, c = 10, 20, 30

print(a)
print(b)
print(c)
```

**Output:**

```text
10
20
30
```

### Assigning the Same Value

```python
a = b = c = 100

print(a, b, c)
```

**Output:**

```text
100 100 100
```

### Rules for Naming Variables

1. Variable names must begin with a letter or underscore.
2. Variable names cannot start with numbers.
3. Variable names cannot contain spaces.
4. Python is case-sensitive.
5. Reserved keywords cannot be used as variable names.

**Example:**

```python
student_name = "Rahul"
Student_age = 21

print(student_name)
print(Student_age)
```

---

# 4. Python Comments

## What are Comments?

Comments are statements written inside a program to explain the code. Python ignores comments during execution.

### Single-Line Comment

**Syntax:**

```python
# This is a comment
```

**Example:**

```python
# Printing student information

name = "Kamal"
print(name)
```

**Output:**

```text
Kamal
```

### Multi-Line Comments

Python does not have a dedicated multi-line comment syntax. Multiple `#` lines are commonly used.

```python
# This is the first comment.
# This is the second comment.
# This is the third comment.

print("Python Programming")
```

**Output:**

```text
Python Programming
```

Triple-quoted strings are also commonly used for documentation strings (docstrings), but they are not technically comments.

---

# 5. Python Data Types

## What are Data Types?

Data types define the kind of value stored in a variable.

Python provides several built-in data types.

| Data Type | Description                           | Example          |
| --------- | ------------------------------------- | ---------------- |
| int       | Integer numbers                       | 100              |
| float     | Decimal numbers                       | 10.5             |
| complex   | Complex numbers                       | 2+3j             |
| str       | Text                                  | "Python"         |
| bool      | True or False                         | True             |
| list      | Ordered, mutable collection           | [1,2,3]          |
| tuple     | Ordered, immutable collection         | (1,2,3)          |
| set       | Unordered collection of unique values | {1,2,3}          |
| dict      | Key-value collection                  | {"name":"Kamal"} |
| NoneType  | Absence of a value                    | None             |

### Example

```python
a = 100
b = 10.5
c = 2 + 3j
d = "Python"
e = True
f = [10, 20, 30]
g = (10, 20, 30)
h = {10, 20, 30}
i = {"name": "Kamal"}
j = None

print(type(a))
print(type(b))
print(type(c))
print(type(d))
print(type(e))
print(type(f))
print(type(g))
print(type(h))
print(type(i))
print(type(j))
```

**Output:**

```text
<class 'int'>
<class 'float'>
<class 'complex'>
<class 'str'>
<class 'bool'>
<class 'list'>
<class 'tuple'>
<class 'set'>
<class 'dict'>
<class 'NoneType'>
```

The `type()` function identifies the data type of a value.

---

# 6. Python Numbers

Python supports three primary numeric types:

1. Integer
2. Float
3. Complex

### Integer

Integer values are whole numbers without decimal points.

```python
a = 100
b = -50

print(a)
print(b)
print(type(a))
```

**Output:**

```text
100
-50
<class 'int'>
```

### Float

Float values contain decimal points.

```python
a = 10.5
b = 20.75

print(a + b)
print(type(a))
```

**Output:**

```text
31.25
<class 'float'>
```

### Complex

Complex numbers contain real and imaginary parts.

```python
a = 2 + 3j

print(a)
print(a.real)
print(a.imag)
```

**Output:**

```text
(2+3j)
2.0
3.0
```

### Numeric Functions

```python
a = -25

print(abs(a))
print(pow(2, 3))
print(round(10.567, 2))
print(max(10, 20, 30))
print(min(10, 20, 30))
```

**Output:**

```text
25
8
10.57
30
10
```

---

# 7. Python Strings

## What is a String?

A string is a sequence of characters enclosed within single, double or triple quotation marks.

### Syntax

```python
variable = "String value"
```

### Example

```python
name = "Python Programming"

print(name)
print(type(name))
print(len(name))
```

**Output:**

```text
Python Programming
<class 'str'>
18
```

### String Indexing

Indexing is used to access individual characters.

```python
name = "PYTHON"

print(name[0])
print(name[1])
print(name[-1])
```

**Output:**

```text
P
Y
N
```

### String Slicing

Slicing extracts a portion of a string.

**Syntax:**

```python
string[start:end:step]
```

**Example:**

```python
name = "PYTHON PROGRAMMING"

print(name[0:6])
print(name[7:18])
print(name[::-1])
```

**Output:**

```text
PYTHON
PROGRAMMING
GNIMMARGORP NOHTYP
```

### Important String Methods

```python
name = "python programming"

print(name.upper())
print(name.lower())
print(name.title())
print(name.capitalize())
print(name.replace("python", "Java"))
print(name.count("m"))
print(name.startswith("python"))
print(name.endswith("programming"))
```

**Output:**

```text
PYTHON PROGRAMMING
python programming
Python Programming
Python programming
Java programming
2
True
True
```

### String Formatting

```python
name = "Kamal"
age = 25

print(f"My name is {name} and my age is {age}")
```

**Output:**

```text
My name is Kamal and my age is 25
```

### Important Point

Strings are immutable. This means individual characters cannot be modified directly.

---

# 8. Python Type Conversion

## What is Type Conversion?

Type conversion means converting one data type into another.

Python supports two types:

1. Implicit Type Conversion
2. Explicit Type Conversion

### Implicit Conversion

Python automatically converts compatible numeric types.

```python
a = 10
b = 5.5

c = a + b

print(c)
print(type(c))
```

**Output:**

```text
15.5
<class 'float'>
```

### Explicit Conversion

The programmer manually converts the data type.

```python
a = "100"

b = int(a)

print(b)
print(type(b))
```

**Output:**

```text
100
<class 'int'>
```

### Important Conversion Functions

```python
int()
float()
str()
bool()
list()
tuple()
set()
dict()
```

### Example

```python
a = 10
b = str(a)

print(b)
print(type(b))
```

**Output:**

```text
10
<class 'str'>
```

**Important:** Converting a string containing non-numeric text into an integer raises a `ValueError`.

---

# 9. Python Operators

## What are Operators?

Operators are symbols or keywords used to perform operations on variables and values.

Python provides several categories of operators.

### 1. Arithmetic Operators

| Operator | Description    | Example  |
| -------- | -------------- | -------- |
| +        | Addition       | 10 + 5   |
| -        | Subtraction    | 10 - 5   |
| \*       | Multiplication | 10 \* 5  |
| /        | Division       | 10 / 5   |
| //       | Floor Division | 10 // 3  |
| %        | Modulus        | 10 % 3   |
| \*\*     | Exponentiation | 2 \*\* 3 |

**Example:**

```python
a = 10
b = 3

print(a + b)
print(a - b)
print(a * b)
print(a / b)
print(a // b)
print(a % b)
print(a ** b)
```

**Output:**

```text
13
7
30
3.3333333333333335
3
1
1000
```

### 2. Comparison Operators

These operators compare two values and return Boolean results.

```python
a = 10
b = 20

print(a == b)
print(a != b)
print(a > b)
print(a < b)
print(a >= b)
print(a <= b)
```

**Output:**

```text
False
True
False
True
False
True
```

### 3. Logical Operators

Logical operators combine conditional expressions.

```python
a = 10

print(a > 5 and a < 20)
print(a > 15 or a < 20)
print(not(a > 5))
```

**Output:**

```text
True
True
False
```

### 4. Assignment Operators

```python
a = 10

a += 5
print(a)

a -= 3
print(a)

a *= 2
print(a)
```

**Output:**

```text
15
12
24
```

### 5. Membership Operators

Membership operators check whether an element exists in a collection.

```python
name = "Python"

print("P" in name)
print("Java" not in name)
```

**Output:**

```text
True
True
```

### 6. Identity Operators

Identity operators check whether two references point to the same object.

```python
a = [1, 2, 3]
b = a
c = [1, 2, 3]

print(a is b)
print(a is c)
print(a == c)
```

**Output:**

```text
True
False
True
```

---

# 10. Python Input and Output

## Input Function

The `input()` function accepts information from the user.

```python
name = input("Enter your name: ")

print("Welcome", name)
```

**Sample Input:**

```text
Kamal
```

**Output:**

```text
Welcome Kamal
```

### Accepting Integer Input

```python
a = int(input("Enter first number: "))
b = int(input("Enter second number: "))

print("Sum:", a + b)
```

**Sample Input:**

```text
Enter first number: 10
Enter second number: 20
```

**Output:**

```text
Sum: 30
```

### Important Point

The `input()` function returns a string. Use `int()` or `float()` when numeric input is required.

---

# 11. Conditional Statements

## What are Conditional Statements?

Conditional statements allow Python to execute different blocks of code depending on whether a condition is True or False.

Python supports:

- if
- if-else
- if-elif-else
- Nested if

### 1. If Statement

**Syntax:**

```python
if condition:
    statement
```

**Example:**

```python
age = 20

if age >= 18:
    print("Eligible to vote")
```

**Output:**

```text
Eligible to vote
```

### 2. If-Else Statement

```python
age = 16

if age >= 18:
    print("Eligible to vote")
else:
    print("Not eligible to vote")
```

**Output:**

```text
Not eligible to vote
```

### 3. If-Elif-Else Statement

```python
marks = 85

if marks >= 90:
    print("Grade A")
elif marks >= 75:
    print("Grade B")
elif marks >= 50:
    print("Grade C")
else:
    print("Fail")
```

**Output:**

```text
Grade B
```

### 4. Nested If

```python
age = 22
has_id = True

if age >= 18:
    if has_id:
        print("Entry allowed")
    else:
        print("ID required")
else:
    print("Entry denied")
```

**Output:**

```text
Entry allowed
```

### Real-World Application

Conditional statements are used in:

- Login authentication.
- Student grading systems.
- Payment verification.
- Eligibility checking.
- Banking applications.

---

# 12. Python Loops

## What are Loops?

Loops are used to execute a block of code repeatedly.

Python provides two primary loops:

1. For Loop
2. While Loop

### 1. For Loop

A for loop iterates over a sequence or iterable.

**Syntax:**

```python
for variable in sequence:
    statement
```

**Example:**

```python
for i in range(1, 6):
    print(i)
```

**Output:**

```text
1
2
3
4
5
```

### Understanding range()

```python
range(start, stop, step)
```

Example:

```python
for i in range(2, 11, 2):
    print(i)
```

**Output:**

```text
2
4
6
8
10
```

### 2. While Loop

A while loop executes as long as the condition remains True.

**Syntax:**

```python
while condition:
    statement
```

**Example:**

```python
i = 1

while i <= 5:
    print(i)
    i += 1
```

**Output:**

```text
1
2
3
4
5
```

### 3. Break Statement

The `break` statement terminates the loop.

```python
for i in range(1, 6):

    if i == 4:
        break

    print(i)
```

**Output:**

```text
1
2
3
```

### 4. Continue Statement

The `continue` statement skips the current iteration.

```python
for i in range(1, 6):

    if i == 3:
        continue

    print(i)
```

**Output:**

```text
1
2
4
5
```

### 5. Pass Statement

The `pass` statement acts as a placeholder.

```python
for i in range(5):

    if i == 2:
        pass

    print(i)
```

**Output:**

```text
0
1
2
3
4
```

---

# 13. Python Lists

## What is a List?

A list is an ordered, mutable collection that can store multiple values of different data types.

Lists allow duplicate values.

### Syntax

```python
list_name = [value1, value2, value3]
```

### Example

```python
students = ["Kamal", "Rahul", "Arun"]

print(students)
print(students[0])
print(students[-1])
```

**Output:**

```text
['Kamal', 'Rahul', 'Arun']
Kamal
Arun
```

### List Slicing

```python
numbers = [10, 20, 30, 40, 50]

print(numbers[0:3])
print(numbers[2:])
print(numbers[::-1])
```

**Output:**

```text
[10, 20, 30]
[30, 40, 50]
[50, 40, 30, 20, 10]
```

### Important List Methods

| Method    | Description                             |
| --------- | --------------------------------------- |
| append()  | Adds an element at the end              |
| insert()  | Adds an element at a specified position |
| extend()  | Adds multiple elements                  |
| remove()  | Removes a specified element             |
| pop()     | Removes and returns an element          |
| sort()    | Sorts the list                          |
| reverse() | Reverses the list                       |
| index()   | Returns the position                    |
| count()   | Counts occurrences                      |
| clear()   | Removes all elements                    |

### Example

```python
numbers = [10, 20, 30]

numbers.append(40)
print(numbers)

numbers.insert(1, 15)
print(numbers)

numbers.remove(20)
print(numbers)

numbers.sort()
print(numbers)
```

**Output:**

```text
[10, 20, 30, 40]
[10, 15, 20, 30, 40]
[10, 15, 30, 40]
[10, 15, 30, 40]
```

---

# 14. Python Tuples

## What is a Tuple?

A tuple is an ordered collection of elements that cannot be modified after creation.

Tuples are immutable and allow duplicate values.

### Syntax

```python
tuple_name = (value1, value2, value3)
```

### Example

```python
numbers = (10, 20, 30, 40)

print(numbers)
print(numbers[0])
print(numbers[-1])
```

**Output:**

```text
(10, 20, 30, 40)
10
40
```

### Tuple Methods

```python
numbers = (10, 20, 10, 30, 40)

print(numbers.count(10))
print(numbers.index(30))
```

**Output:**

```text
2
3
```

### Tuple Unpacking

```python
student = ("Kamal", 25, "Python")

name, age, course = student

print(name)
print(age)
print(course)
```

**Output:**

```text
Kamal
25
Python
```

### Important Point

A tuple containing one element requires a trailing comma.

```python
a = (10,)

print(type(a))
```

**Output:**

```text
<class 'tuple'>
```

---

# 15. Python Sets

## What is a Set?

A set is an unordered collection of unique elements.

Sets automatically remove duplicate values.

### Syntax

```python
set_name = {value1, value2, value3}
```

### Example

```python
numbers = {10, 20, 30, 10, 20}

print(numbers)
```

**Output:**

```text
{10, 20, 30}
```

Note: Set output order is not guaranteed.

### Important Set Methods

```python
numbers = {10, 20, 30}

numbers.add(40)
print(numbers)

numbers.update([50, 60])
print(numbers)

numbers.remove(20)
print(numbers)

numbers.discard(100)
print(numbers)
```

### Set Operations

**Union:**

```python
a = {1, 2, 3}
b = {3, 4, 5}

print(a.union(b))
```

Output:

```text
{1, 2, 3, 4, 5}
```

**Intersection:**

```python
print(a.intersection(b))
```

Output:

```text
{3}
```

**Difference:**

```python
print(a.difference(b))
```

Output:

```text
{1, 2}
```

**Symmetric Difference:**

```python
print(a.symmetric_difference(b))
```

Output:

```text
{1, 2, 4, 5}
```

### Real-World Application

Sets are useful for removing duplicate records, finding common customers and comparing datasets.

---

# 16. Python Dictionaries

## What is a Dictionary?

A dictionary stores data in key-value pairs.

Dictionaries are mutable and preserve insertion order.

### Syntax

```python
dictionary_name = {
    "key": "value"
}
```

### Example

```python
student = {
    "name": "Kamal",
    "age": 25,
    "course": "Python"
}

print(student)
print(student["name"])
print(student["age"])
```

**Output:**

```text
{'name': 'Kamal', 'age': 25, 'course': 'Python'}
Kamal
25
```

### Accessing Values

```python
student = {
    "name": "Rahul",
    "age": 22
}

print(student.get("name"))
print(student.get("city", "Not Available"))
```

**Output:**

```text
Rahul
Not Available
```

### Adding and Updating Values

```python
student = {"name": "Kamal"}

student["age"] = 25
student["course"] = "Data Science"

print(student)
```

**Output:**

```text
{'name': 'Kamal', 'age': 25, 'course': 'Data Science'}
```

### Important Dictionary Methods

```python
student = {
    "name": "Kamal",
    "age": 25,
    "course": "Python"
}

print(student.keys())
print(student.values())
print(student.items())
```

**Output:**

```text
dict_keys(['name', 'age', 'course'])
dict_values(['Kamal', 25, 'Python'])
dict_items([('name', 'Kamal'), ('age', 25), ('course', 'Python')])
```

### Iterating Through a Dictionary

```python
student = {
    "name": "Kamal",
    "age": 25
}

for key, value in student.items():
    print(key, ":", value)
```

**Output:**

```text
name : Kamal
age : 25
```

---

# 🟡 LEVEL 2 – PYTHON INTERMEDIATE

# 17. Python Functions

## What is a Function?

A function is a reusable block of code designed to perform a particular task.

Functions help reduce code duplication and improve code organization.

### Syntax

```python
def function_name():
    statements

function_name()
```

### Example Without Function

```python
print("Welcome to Python")
print("Welcome to Python")
print("Welcome to Python")
```

### Example With Function

```python
def welcome():
    print("Welcome to Python")

welcome()
welcome()
welcome()
```

**Output:**

```text
Welcome to Python
Welcome to Python
Welcome to Python
```

### Function With Parameters

```python
def addition(a, b):
    print(a + b)

addition(10, 20)
```

**Output:**

```text
30
```

### Function With Return

The `return` statement sends a result back to the caller.

```python
def addition(a, b):
    return a + b

result = addition(10, 20)

print(result)
```

**Output:**

```text
30
```

### Returning Multiple Values

```python
def calculation(a, b):

    addition = a + b
    multiplication = a * b

    return addition, multiplication

sum_result, product_result = calculation(10, 20)

print(sum_result)
print(product_result)
```

**Output:**

```text
30
200
```

### Function Calling Another Function

```python
def is_even(number):
    return number % 2 == 0

def check_number(number):

    if is_even(number):
        return "Even Number"

    return "Odd Number"

print(check_number(10))
```

**Output:**

```text
Even Number
```

---

# 18. Function Arguments

Python supports different ways of passing arguments to functions.

### 1. Positional Arguments

```python
def student(name, age):
    print(name, age)

student("Kamal", 25)
```

Output:

```text
Kamal 25
```

### 2. Keyword Arguments

```python
def student(name, age):
    print(name, age)

student(age=25, name="Kamal")
```

Output:

```text
Kamal 25
```

### 3. Default Arguments

```python
def student(name, age=20):
    print(name, age)

student("Kamal")
student("Rahul", 25)
```

Output:

```text
Kamal 20
Rahul 25
```

### 4. Variable-Length Arguments (\*args)

`*args` allows a function to accept any number of positional arguments.

```python
def addition(*numbers):

    total = 0

    for i in numbers:
        total += i

    return total

print(addition(10, 20))
print(addition(10, 20, 30, 40))
```

Output:

```text
30
100
```

### 5. Keyword Variable Arguments (\*\*kwargs)

`**kwargs` allows a function to accept multiple keyword arguments.

```python
def student(**details):

    for key, value in details.items():
        print(key, value)

student(name="Kamal", age=25, course="Python")
```

Output:

```text
name Kamal
age 25
course Python
```

---

# 19. Lambda Functions

## What is a Lambda Function?

A lambda function is a small anonymous function created using the `lambda` keyword.

It is useful when a short function is needed without defining it using `def`.

### Syntax

```python
lambda arguments: expression
```

### Example

```python
addition = lambda a, b: a + b

print(addition(10, 20))
```

**Output:**

```text
30
```

### Square of a Number

```python
square = lambda x: x ** 2

print(square(5))
```

**Output:**

```text
25
```

### Even or Odd

```python
check = lambda x: "Even" if x % 2 == 0 else "Odd"

print(check(10))
print(check(7))
```

**Output:**

```text
Even
Odd
```

### Real-World Application

Lambda functions are often used with:

- map()
- filter()
- sorted()
- reduce()

---

# 20. Map Function

## What is map()?

The `map()` function applies a specified function to every element of an iterable.

### Syntax

```python
map(function, iterable)
```

### Example

```python
numbers = [1, 2, 3, 4, 5]

def square(x):
    return x ** 2

result = map(square, numbers)

print(list(result))
```

**Output:**

```text
[1, 4, 9, 16, 25]
```

### Map With Lambda

```python
numbers = [1, 2, 3, 4]

result = map(lambda x: x + 10, numbers)

print(list(result))
```

**Output:**

```text
[11, 12, 13, 14]
```

### Map With Multiple Iterables

```python
a = [1, 2, 3]
b = [10, 20, 30]

result = map(lambda x, y: x + y, a, b)

print(list(result))
```

**Output:**

```text
[11, 22, 33]
```

---

# 21. Filter Function

## What is filter()?

The `filter()` function selects elements from an iterable based on a condition.

It retains elements for which the function returns True.

### Syntax

```python
filter(function, iterable)
```

### Example

```python
numbers = [1, 2, 3, 4, 5, 6, 7, 8]

result = filter(lambda x: x % 2 == 0, numbers)

print(list(result))
```

**Output:**

```text
[2, 4, 6, 8]
```

### Filtering Numbers Greater Than 5

```python
numbers = [2, 4, 6, 8, 10, 12]

result = filter(lambda x: x > 5, numbers)

print(list(result))
```

**Output:**

```text
[6, 8, 10, 12]
```

### Real-World Application

Filter can be used to:

- Find eligible students.
- Filter customer records.
- Select products by price.
- Identify employees based on salary.

---

# 22. Reduce Function

## What is reduce()?

The `reduce()` function repeatedly applies a function to the elements of an iterable and produces a single accumulated result.

It is available in the `functools` module.

### Syntax

```python
from functools import reduce

reduce(function, iterable)
```

### Example: Sum of Elements

```python
from functools import reduce

numbers = [1, 2, 3, 4, 5]

result = reduce(lambda x, y: x + y, numbers)

print(result)
```

**Output:**

```text
15
```

### Internal Working

```text
1 + 2 = 3
3 + 3 = 6
6 + 4 = 10
10 + 5 = 15
```

### Multiplication

```python
from functools import reduce

numbers = [1, 2, 3, 4, 5]

result = reduce(lambda x, y: x * y, numbers)

print(result)
```

**Output:**

```text
120
```

### Finding Maximum Value

```python
from functools import reduce

numbers = [10, 50, 20, 80, 30]

result = reduce(lambda x, y: x if x > y else y, numbers)

print(result)
```

**Output:**

```text
80
```

---

# 23. List Comprehension

## What is List Comprehension?

List comprehension is a concise way to create lists using an expression and an iterable.

### Syntax

```python
[expression for item in iterable]
```

### Example

```python
numbers = [1, 2, 3, 4, 5]

squares = [x ** 2 for x in numbers]

print(squares)
```

**Output:**

```text
[1, 4, 9, 16, 25]
```

### List Comprehension With Condition

```python
numbers = [1, 2, 3, 4, 5, 6]

even = [x for x in numbers if x % 2 == 0]

print(even)
```

**Output:**

```text
[2, 4, 6]
```

### List Comprehension With If-Else

```python
numbers = [1, 2, 3, 4, 5]

result = [
    "Even" if x % 2 == 0 else "Odd"
    for x in numbers
]

print(result)
```

**Output:**

```text
['Odd', 'Even', 'Odd', 'Even', 'Odd']
```

---

# 24. Dictionary Comprehension

## What is Dictionary Comprehension?

Dictionary comprehension is a concise way to create dictionaries using expressions and iterables.

### Syntax

```python
{key: value for item in iterable}
```

### Example

```python
numbers = [1, 2, 3, 4, 5]

squares = {x: x ** 2 for x in numbers}

print(squares)
```

**Output:**

```text
{1: 1, 2: 4, 3: 9, 4: 16, 5: 25}
```

### Dictionary Comprehension With Condition

```python
numbers = [1, 2, 3, 4, 5, 6]

even = {
    x: x ** 2
    for x in numbers
    if x % 2 == 0
}

print(even)
```

**Output:**

```text
{2: 4, 4: 16, 6: 36}
```

---

# 25. Python Modules

## What is a Module?

A module is a Python file containing reusable functions, variables and classes.

Modules help organize code into separate files.

### Importing a Module

```python
import math

print(math.sqrt(25))
```

**Output:**

```text
5.0
```

### Importing Specific Functions

```python
from math import sqrt

print(sqrt(36))
```

**Output:**

```text
6.0
```

### Importing With Alias

```python
import math as m

print(m.factorial(5))
```

**Output:**

```text
120
```

### Creating a User-Defined Module

Create a file named `calculator.py`.

```python
def addition(a, b):
    return a + b

def multiplication(a, b):
    return a * b
```

Create another file named `main.py`.

```python
import calculator

print(calculator.addition(10, 20))
print(calculator.multiplication(10, 20))
```

**Output:**

```text
30
200
```

---

# 26. Python File Handling

## What is File Handling?

File handling is the process of creating, reading, writing, appending and managing files using Python.

Python supports several file modes.

| Mode | Description                           |
| ---- | ------------------------------------- |
| r    | Read                                  |
| w    | Write; creates or overwrites          |
| a    | Append                                |
| x    | Create a new file; fails if it exists |
| rb   | Read binary                           |
| wb   | Write binary                          |
| r+   | Read and write                        |

### 1. Writing a File

```python
file = open("student.txt", "w")

file.write("Welcome to Python Programming")

file.close()
```

### 2. Reading a File

```python
file = open("student.txt", "r")

print(file.read())

file.close()
```

**Output:**

```text
Welcome to Python Programming
```

### 3. Appending Data

```python
file = open("student.txt", "a")

file.write("\nWelcome to Data Science")

file.close()
```

### 4. Reading One Line

```python
file = open("student.txt", "r")

print(file.readline())

file.close()
```

### 5. Reading All Lines

```python
file = open("student.txt", "r")

print(file.readlines())

file.close()
```

### 6. Using With Statement

The `with` statement automatically manages file closure.

```python
with open("student.txt", "w") as file:

    file.write("Python File Handling")
```

Reading:

```python
with open("student.txt", "r") as file:

    data = file.read()

    print(data)
```

**Output:**

```text
Python File Handling
```

### Real-World Applications

- Reading CSV files.
- Processing JSON data.
- Creating reports.
- Storing application logs.
- Managing datasets.

---

# 27. Python Exception Handling

## What is an Exception?

An exception is an error that occurs during program execution and interrupts the normal flow of a program.

Exception handling helps us manage runtime errors without abruptly terminating the application.

### Common Python Exceptions

| Exception         | Description                   |
| ----------------- | ----------------------------- |
| ZeroDivisionError | Division by zero              |
| NameError         | Undefined variable            |
| ValueError        | Invalid value                 |
| TypeError         | Incorrect data type operation |
| IndexError        | Invalid sequence index        |
| KeyError          | Missing dictionary key        |
| FileNotFoundError | File does not exist           |
| AttributeError    | Missing object attribute      |

### Example Without Exception Handling

```python
a = 10
b = 0

print(a / b)
```

**Output:**

```text
ZeroDivisionError: division by zero
```

### Try and Except

**Syntax:**

```python
try:
    statements

except:
    error_handling
```

**Example:**

```python
try:
    a = 10
    b = 0

    print(a / b)

except ZeroDivisionError:
    print("Cannot divide by zero")
```

**Output:**

```text
Cannot divide by zero
```

### Multiple Except Blocks

```python
try:

    number = int(input("Enter a number: "))

    result = 100 / number

    print(result)

except ValueError:
    print("Please enter a valid number")

except ZeroDivisionError:
    print("Number cannot be zero")
```

### Finally Block

The `finally` block executes whether an exception occurs or not.

```python
try:
    print("Inside try block")

except Exception:
    print("Error occurred")

finally:
    print("Program completed")
```

**Output:**

```text
Inside try block
Program completed
```

### Else Block

The `else` block executes when no exception occurs.

```python
try:
    a = 10
    b = 2

    result = a / b

except ZeroDivisionError:
    print("Division error")

else:
    print("Result:", result)

finally:
    print("Execution completed")
```

**Output:**

```text
Result: 5.0
Execution completed
```

### Raising Exceptions

```python
age = 15

if age < 18:
    raise ValueError("Age must be 18 or above")
```

---

# 28. Python Math Module

## What is the Math Module?

The math module provides mathematical functions and constants.

### Importing Math

```python
import math
```

### Important Math Functions

```python
import math

print(math.sqrt(25))
print(math.pow(2, 3))
print(math.factorial(5))
print(math.ceil(10.2))
print(math.floor(10.8))
print(math.pi)
```

**Output:**

```text
5.0
8.0
120
11
10
3.141592653589793
```

### Other Important Functions

| Function    | Description       |
| ----------- | ----------------- |
| sqrt()      | Square root       |
| pow()       | Power             |
| factorial() | Factorial         |
| ceil()      | Rounds upward     |
| floor()     | Rounds downward   |
| log()       | Natural logarithm |
| log10()     | Base-10 logarithm |
| exp()       | Exponential       |
| sin()       | Sine              |
| cos()       | Cosine            |
| tan()       | Tangent           |

---

# 🔴 LEVEL 3 – PYTHON ADVANCED

# 29. Object-Oriented Programming

## What is OOP?

Object-Oriented Programming (OOP) is a programming paradigm based on classes and objects.

It helps organize code into reusable and structured components.

### Four Main Pillars of OOP

1. Encapsulation
2. Inheritance
3. Polymorphism
4. Abstraction

### Advantages of OOP

- Code reusability.
- Better code organization.
- Easy maintenance.
- Data protection.
- Scalability.

---

# 30. Classes and Objects

## What is a Class?

A class is a blueprint used to create objects.

## What is an Object?

An object is an instance of a class.

### Syntax

```python
class ClassName:
    statements

object_name = ClassName()
```

### Example

```python
class Student:

    name = "Kamal"
    age = 25

student1 = Student()

print(student1.name)
print(student1.age)
```

**Output:**

```text
Kamal
25
```

### Creating Multiple Objects

```python
class Student:
    pass

student1 = Student()
student2 = Student()

student1.name = "Kamal"
student2.name = "Rahul"

print(student1.name)
print(student2.name)
```

**Output:**

```text
Kamal
Rahul
```

---

# 31. Constructors

## What is a Constructor?

A constructor is a special method that initializes an object's attributes when the object is created.

Python uses the `__init__()` method for initialization.

### Syntax

```python
class ClassName:

    def __init__(self):
        statements
```

### Example

```python
class Student:

    def __init__(self, name, age):

        self.name = name
        self.age = age

student1 = Student("Kamal", 25)

print(student1.name)
print(student1.age)
```

**Output:**

```text
Kamal
25
```

### Constructor With Methods

```python
class Rectangle:

    def __init__(self, length, breadth):

        self.length = length
        self.breadth = breadth

    def area(self):

        return self.length * self.breadth

rectangle = Rectangle(10, 5)

print(rectangle.area())
```

**Output:**

```text
50
```

---

# 32. Inheritance

## What is Inheritance?

Inheritance allows one class to acquire attributes and methods from another class.

The existing class is called the Parent Class or Base Class.

The new class is called the Child Class or Derived Class.

### Syntax

```python
class Parent:
    statements

class Child(Parent):
    statements
```

### Example

```python
class Animal:

    def sound(self):
        print("Animals make sounds")

class Dog(Animal):

    def bark(self):
        print("Dog barks")

dog = Dog()

dog.sound()
dog.bark()
```

**Output:**

```text
Animals make sounds
Dog barks
```

### Types of Inheritance

1. Single Inheritance
2. Multiple Inheritance
3. Multilevel Inheritance
4. Hierarchical Inheritance
5. Hybrid Inheritance

### Multiple Inheritance

```python
class Father:

    def father_skill(self):
        print("Gardening")

class Mother:

    def mother_skill(self):
        print("Cooking")

class Child(Father, Mother):
    pass

child = Child()

child.father_skill()
child.mother_skill()
```

**Output:**

```text
Gardening
Cooking
```

---

# 33. Polymorphism

## What is Polymorphism?

Polymorphism means one interface or operation can represent different behaviors depending on the object or context.

### Example: Method Overriding

```python
class Animal:

    def sound(self):
        print("Animal makes sound")

class Dog(Animal):

    def sound(self):
        print("Dog barks")

class Cat(Animal):

    def sound(self):
        print("Cat meows")

dog = Dog()
cat = Cat()

dog.sound()
cat.sound()
```

**Output:**

```text
Dog barks
Cat meows
```

### Polymorphism Using a Common Interface

```python
class Circle:

    def area(self):
        return 3.14 * 5 * 5

class Square:

    def area(self):
        return 10 * 10

shapes = [Circle(), Square()]

for shape in shapes:
    print(shape.area())
```

**Output:**

```text
78.5
100
```

---

# 34. Encapsulation

## What is Encapsulation?

Encapsulation is the concept of combining data and methods inside a class while controlling how the internal data is accessed or modified.

Python uses naming conventions for attribute visibility:

- Public: `name`
- Protected by convention: `_name`
- Name-mangled: `__name`

### Example

```python
class BankAccount:

    def __init__(self, balance):

        self.__balance = balance

    def deposit(self, amount):

        self.__balance += amount

    def get_balance(self):

        return self.__balance

account = BankAccount(1000)

account.deposit(500)

print(account.get_balance())
```

**Output:**

```text
1500
```

**Important:** Double underscores trigger name mangling. They do not provide absolute security or strict private access.

---

# 35. Abstraction

## What is Abstraction?

Abstraction means exposing essential functionality while hiding unnecessary implementation details.

Python supports abstraction through the `abc` module.

### Example

```python
from abc import ABC, abstractmethod

class Vehicle(ABC):

    @abstractmethod
    def start(self):
        pass

class Car(Vehicle):

    def start(self):
        print("Car started")

car = Car()

car.start()
```

**Output:**

```text
Car started
```

### Real-World Example

When using an ATM, users interact with buttons and options without needing to understand the internal banking system.

This is an example of abstraction.

---

# 36. Static Methods and Class Methods

Python supports three commonly used method types:

1. Instance Methods
2. Class Methods
3. Static Methods

### 1. Instance Method

Instance methods receive `self` and work with object-specific data.

```python
class Student:

    def __init__(self, name):
        self.name = name

    def display(self):
        print(self.name)

student = Student("Kamal")

student.display()
```

Output:

```text
Kamal
```

### 2. Class Method

Class methods receive `cls` and operate on class-level data.

```python
class Student:

    college = "ABC College"

    @classmethod
    def display(cls):
        print(cls.college)

Student.display()
```

Output:

```text
ABC College
```

### 3. Static Method

Static methods do not automatically receive `self` or `cls`.

```python
class Calculator:

    @staticmethod
    def addition(a, b):
        return a + b

print(Calculator.addition(10, 20))
```

Output:

```text
30
```

---

# 37. Super Keyword

## What is super()?

The `super()` function provides access to methods from a parent class.

It is commonly used in inheritance to extend parent class behavior.

### Example

```python
class Parent:

    def display(self):
        print("Parent Class")

class Child(Parent):

    def display(self):

        super().display()

        print("Child Class")

obj = Child()

obj.display()
```

**Output:**

```text
Parent Class
Child Class
```

---

# 38. Shallow Copy and Deep Copy

## What is Copying?

Copying creates another object based on an existing object.

Python provides two important copying techniques:

1. Shallow Copy
2. Deep Copy

### Shallow Copy

A shallow copy creates a new outer object but keeps references to nested objects.

```python
import copy

original = [[1, 2], [3, 4]]

new_list = copy.copy(original)

new_list[0][0] = 100

print(original)
print(new_list)
```

**Output:**

```text
[[100, 2], [3, 4]]
[[100, 2], [3, 4]]
```

### Deep Copy

A deep copy creates a new outer object and recursively copies nested objects.

```python
import copy

original = [[1, 2], [3, 4]]

new_list = copy.deepcopy(original)

new_list[0][0] = 100

print(original)
print(new_list)
```

**Output:**

```text
[[1, 2], [3, 4]]
[[100, 2], [3, 4]]
```

### Difference

| Shallow Copy               | Deep Copy                         |
| -------------------------- | --------------------------------- |
| Creates a new outer object | Creates independent nested copies |
| Nested objects are shared  | Nested objects are copied         |
| Uses `copy.copy()`         | Uses `copy.deepcopy()`            |

---

# 39. Recursion

## What is Recursion?

Recursion is a programming technique in which a function calls itself to solve a problem.

A recursive function requires a base condition to stop further recursive calls.

### Example: Factorial

```python
def factorial(n):

    if n == 0 or n == 1:
        return 1

    return n * factorial(n - 1)

print(factorial(5))
```

**Output:**

```text
120
```

### Internal Working

```text
factorial(5)
5 * factorial(4)
5 * 4 * factorial(3)
5 * 4 * 3 * factorial(2)
5 * 4 * 3 * 2 * factorial(1)

Result = 120
```

### Fibonacci Using Recursion

```python
def fibonacci(n):

    if n <= 1:
        return n

    return fibonacci(n - 1) + fibonacci(n - 2)

for i in range(7):
    print(fibonacci(i), end=" ")
```

**Output:**

```text
0 1 1 2 3 5 8
```

---

# 40. Iterators and Generators

## Iterators

An iterator is an object that allows sequential access to elements using `next()`.

### Example

```python
numbers = [10, 20, 30]

iterator = iter(numbers)

print(next(iterator))
print(next(iterator))
print(next(iterator))
```

**Output:**

```text
10
20
30
```

Calling `next()` after the last element raises `StopIteration`.

## Generators

A generator is a special type of iterator that produces values one at a time using the `yield` keyword.

### Syntax

```python
def generator_name():
    yield value
```

### Example

```python
def numbers():

    yield 10
    yield 20
    yield 30

for i in numbers():
    print(i)
```

**Output:**

```text
10
20
30
```

### Generator With Range

```python
def square_numbers(n):

    for i in range(1, n + 1):
        yield i ** 2

for value in square_numbers(5):
    print(value)
```

**Output:**

```text
1
4
9
16
25
```

---

# 41. Decorators

## What is a Decorator?

A decorator is a function that modifies or extends the behavior of another function without changing its original source code.

### Example

```python
def my_decorator(func):

    def wrapper():

        print("Before function execution")

        func()

        print("After function execution")

    return wrapper

@my_decorator
def welcome():

    print("Welcome to Python")

welcome()
```

**Output:**

```text
Before function execution
Welcome to Python
After function execution
```

### Real-World Applications

- Logging
- Authentication
- Performance measurement
- Access control
- Caching

---

# 42. Arrays Without NumPy

## What is an Array?

An array is a collection of elements stored in a structured sequence.

Python's built-in `array` module provides typed arrays.

### Example

```python
import array

numbers = array.array('i', [10, 20, 30, 40])

print(numbers)
print(numbers[0])
```

**Output:**

```text
array('i', [10, 20, 30, 40])
10
```

### Adding Elements

```python
import array

numbers = array.array('i', [10, 20, 30])

numbers.append(40)

print(numbers)
```

**Output:**

```text
array('i', [10, 20, 30, 40])
```

---

# 🔵 LEVEL 4 – PYTHON FOR DATA SCIENCE

# 43. Introduction to NumPy

## What is NumPy?

NumPy stands for Numerical Python.

It is a powerful Python library used for numerical computation, scientific computing and multidimensional array operations.

NumPy is widely used in:

- Data Science
- Machine Learning
- Deep Learning
- Statistical Computing
- Scientific Research

### Installing NumPy

```bash
pip install numpy
```

### Importing NumPy

```python
import numpy as np
```

### Why NumPy?

1. Efficient multidimensional arrays.
2. Fast mathematical operations.
3. Broadcasting support.
4. Array indexing and slicing.
5. Linear algebra operations.
6. Integration with Pandas and Machine Learning libraries.

---

# 44. NumPy Arrays

## What is an ndarray?

An ndarray is the primary multidimensional array object provided by NumPy.

### Creating a One-Dimensional Array

```python
import numpy as np

arr = np.array([10, 20, 30, 40])

print(arr)
print(arr.ndim)
print(arr.shape)
print(arr.size)
```

**Output:**

```text
[10 20 30 40]
1
(4,)
4
```

### Creating a Two-Dimensional Array

```python
import numpy as np

arr = np.array([
    [1, 2, 3],
    [4, 5, 6]
])

print(arr)
print(arr.ndim)
print(arr.shape)
```

**Output:**

```text
[[1 2 3]
 [4 5 6]]
2
(2, 3)
```

### Important Array Creation Functions

**Zeros:**

```python
np.zeros((2, 3))
```

Output:

```text
[[0. 0. 0.]
 [0. 0. 0.]]
```

**Ones:**

```python
np.ones((2, 2))
```

Output:

```text
[[1. 1.]
 [1. 1.]]
```

**Arange:**

```python
np.arange(1, 10)
```

Output:

```text
[1 2 3 4 5 6 7 8 9]
```

**Identity Matrix:**

```python
np.eye(3)
```

Output:

```text
[[1. 0. 0.]
 [0. 1. 0.]
 [0. 0. 1.]]
```

**Reshape:**

```python
arr = np.arange(1, 7)

print(arr.reshape(2, 3))
```

Output:

```text
[[1 2 3]
 [4 5 6]]
```

---

# 45. NumPy Indexing and Slicing

## Array Indexing

```python
import numpy as np

arr = np.array([10, 20, 30, 40, 50])

print(arr[0])
print(arr[2])
print(arr[-1])
```

**Output:**

```text
10
30
50
```

## Array Slicing

```python
arr = np.array([10, 20, 30, 40, 50])

print(arr[1:4])
print(arr[:3])
print(arr[::-1])
```

**Output:**

```text
[20 30 40]
[10 20 30]
[50 40 30 20 10]
```

## Two-Dimensional Indexing

```python
arr = np.array([
    [10, 20, 30],
    [40, 50, 60],
    [70, 80, 90]
])

print(arr[0, 1])
print(arr[2, 2])
```

**Output:**

```text
20
90
```

---

# 46. NumPy Operations

### Arithmetic Operations

```python
import numpy as np

a = np.array([10, 20, 30])
b = np.array([1, 2, 3])

print(a + b)
print(a - b)
print(a * b)
print(a / b)
```

**Output:**

```text
[11 22 33]
[ 9 18 27]
[10 40 90]
[10. 10. 10.]
```

### Statistical Operations

```python
arr = np.array([10, 20, 30, 40, 50])

print(np.sum(arr))
print(np.mean(arr))
print(np.median(arr))
print(np.min(arr))
print(np.max(arr))
print(np.std(arr))
```

**Output:**

```text
150
30.0
30.0
10
50
14.142135623730951
```

### Boolean Filtering

```python
arr = np.array([10, 20, 30, 40, 50])

print(arr[arr > 25])
```

**Output:**

```text
[30 40 50]
```

---

# 47. Introduction to Pandas

## What is Pandas?

Pandas is an open-source Python library used for data manipulation, data cleaning and data analysis.

It provides two primary data structures:

1. Series
2. DataFrame

### Installing Pandas

```bash
pip install pandas
```

### Importing Pandas

```python
import pandas as pd
```

### Applications of Pandas

- Data Cleaning
- Data Transformation
- Data Filtering
- Data Analysis
- Missing Value Handling
- CSV and Excel Processing
- Grouping and Aggregation

---

# 48. Pandas Series

## What is a Series?

A Series is a one-dimensional labeled data structure capable of storing different types of values.

### Syntax

```python
pd.Series(data, index=None)
```

### Example

```python
import pandas as pd

data = [10, 20, 30, 40]

series = pd.Series(data)

print(series)
```

**Output:**

```text
0    10
1    20
2    30
3    40
dtype: int64
```

### Custom Index

```python
series = pd.Series(
    [85, 90, 75],
    index=["Kamal", "Rahul", "Arun"]
)

print(series)
```

**Output:**

```text
Kamal    85
Rahul    90
Arun     75
dtype: int64
```

### Accessing Series Elements

```python
print(series["Kamal"])
print(series.iloc[1])
```

**Output:**

```text
85
90
```

---

# 49. Pandas DataFrame

## What is a DataFrame?

A DataFrame is a two-dimensional labeled data structure consisting of rows and columns.

It is similar to a spreadsheet or database table.

### Creating a DataFrame

```python
import pandas as pd

data = {
    "Name": ["Kamal", "Rahul", "Arun"],
    "Age": [25, 22, 24],
    "Marks": [90, 85, 95]
}

df = pd.DataFrame(data)

print(df)
```

**Output:**

```text
    Name  Age  Marks
0  Kamal   25     90
1  Rahul   22     85
2   Arun   24     95
```

### Important DataFrame Attributes

```python
print(df.shape)
print(df.columns)
print(df.index)
print(df.dtypes)
```

### Important DataFrame Methods

| Method         | Description                |
| -------------- | -------------------------- |
| head()         | First five rows by default |
| tail()         | Last five rows by default  |
| info()         | DataFrame information      |
| describe()     | Statistical summary        |
| shape          | Number of rows and columns |
| columns        | Column names               |
| dtypes         | Data types                 |
| value_counts() | Frequency counts           |

### Example

```python
print(df.head(2))
print(df.describe())
```

---

# 50. Data Selection and Filtering

## Selecting Columns

```python
print(df["Name"])
```

## Selecting Multiple Columns

```python
print(df[["Name", "Marks"]])
```

## Using loc()

`loc` selects data using row and column labels.

```python
print(df.loc[0, "Name"])
```

Output:

```text
Kamal
```

## Using iloc()

`iloc` selects data using integer positions.

```python
print(df.iloc[0, 1])
```

Output:

```text
25
```

## Filtering Records

```python
result = df[df["Marks"] > 85]

print(result)
```

**Output:**

```text
    Name  Age  Marks
0  Kamal   25     90
2   Arun   24     95
```

## Multiple Conditions

```python
result = df[
    (df["Age"] > 22) &
    (df["Marks"] >= 90)
]

print(result)
```

---

# 51. Handling Missing Values

## What are Missing Values?

Missing values are records where information is unavailable or not recorded.

Pandas commonly represents missing numerical values using `NaN`.

### Example

```python
import pandas as pd
import numpy as np

data = {
    "Name": ["Kamal", "Rahul", "Arun"],
    "Marks": [90, np.nan, 80]
}

df = pd.DataFrame(data)

print(df)
```

### Detecting Missing Values

```python
print(df.isnull())
print(df.isnull().sum())
```

### Removing Missing Values

```python
df.dropna()
```

### Filling Missing Values

```python
df["Marks"] = df["Marks"].fillna(0)

print(df)
```

**Output:**

```text
    Name  Marks
0  Kamal   90.0
1  Rahul    0.0
2   Arun   80.0
```

### Filling With Mean

```python
df["Marks"] = df["Marks"].fillna(df["Marks"].mean())
```

**Important:** Choose a missing-value strategy based on the meaning of the data. Replacing all missing values with zero is not always appropriate.

---

# 52. Removing Duplicates

## What are Duplicate Records?

Duplicate records are repeated rows or values in a dataset.

Duplicates may affect data analysis and reporting.

### Example

```python
import pandas as pd

data = {
    "Name": ["Kamal", "Rahul", "Kamal"],
    "Age": [25, 22, 25]
}

df = pd.DataFrame(data)

print(df.duplicated())
```

### Removing Duplicates

```python
df = df.drop_duplicates()

print(df)
```

**Output:**

```text
    Name  Age
0  Kamal   25
1  Rahul   22
```

---

# 53. Data Transformation

Data transformation means changing the structure, format or values of a dataset.

### Adding a New Column

```python
df["Result"] = ["Pass", "Pass", "Pass"]

print(df)
```

### Renaming Columns

```python
df = df.rename(
    columns={"Name": "Student_Name"}
)

print(df.columns)
```

### Dropping a Column

```python
df = df.drop("Age", axis=1)
```

### Concatenating DataFrames

```python
import pandas as pd

df1 = pd.DataFrame({
    "Name": ["Kamal", "Rahul"]
})

df2 = pd.DataFrame({
    "Name": ["Arun", "John"]
})

result = pd.concat([df1, df2], ignore_index=True)

print(result)
```

**Output:**

```text
    Name
0  Kamal
1  Rahul
2   Arun
3   John
```

---

# 54. Sorting and Grouping

## Sorting Data

The `sort_values()` method sorts records based on column values.

```python
import pandas as pd

data = {
    "Name": ["Kamal", "Rahul", "Arun"],
    "Marks": [90, 75, 95]
}

df = pd.DataFrame(data)

result = df.sort_values(
    by="Marks",
    ascending=False
)

print(result)
```

**Output:**

```text
    Name  Marks
2   Arun     95
0  Kamal     90
1  Rahul     75
```

## GroupBy

GroupBy divides data into groups based on one or more columns.

### Example

```python
import pandas as pd

data = {
    "Department": [
        "IT", "HR", "IT", "HR"
    ],
    "Salary": [
        50000, 30000, 60000, 40000
    ]
}

df = pd.DataFrame(data)

result = df.groupby("Department")["Salary"].mean()

print(result)
```

**Output:**

```text
Department
HR    35000.0
IT    55000.0
Name: Salary, dtype: float64
```

### Important GroupBy Operations

```python
df.groupby("Department")["Salary"].sum()
df.groupby("Department")["Salary"].mean()
df.groupby("Department")["Salary"].max()
df.groupby("Department")["Salary"].min()
df.groupby("Department")["Salary"].count()
```

---

# 55. Matplotlib

## What is Matplotlib?

Matplotlib is a Python visualization library used to create charts, graphs and plots.

It helps convert numerical data into meaningful visual representations.

### Installation

```bash
pip install matplotlib
```

### Importing

```python
import matplotlib.pyplot as plt
```

### 1. Line Plot

```python
import matplotlib.pyplot as plt

x = [1, 2, 3, 4, 5]
y = [10, 20, 15, 30, 25]

plt.plot(x, y)

plt.title("Line Chart")
plt.xlabel("X Values")
plt.ylabel("Y Values")

plt.show()
```

### 2. Bar Chart

```python
import matplotlib.pyplot as plt

students = ["Kamal", "Rahul", "Arun"]
marks = [90, 80, 95]

plt.bar(students, marks)

plt.title("Student Marks")
plt.xlabel("Students")
plt.ylabel("Marks")

plt.show()
```

### 3. Scatter Plot

```python
import matplotlib.pyplot as plt

x = [10, 20, 30, 40]
y = [15, 25, 35, 45]

plt.scatter(x, y)

plt.title("Scatter Plot")

plt.show()
```

### 4. Histogram

```python
import matplotlib.pyplot as plt

marks = [50, 60, 70, 70, 80, 90, 90, 95]

plt.hist(marks, bins=5)

plt.title("Marks Distribution")

plt.show()
```

### 5. Pie Chart

```python
import matplotlib.pyplot as plt

labels = ["Python", "Java", "SQL"]
values = [50, 30, 20]

plt.pie(
    values,
    labels=labels,
    autopct="%1.1f%%"
)

plt.title("Programming Language Preferences")

plt.show()
```

---

# 56. Seaborn

## What is Seaborn?

Seaborn is a Python statistical data visualization library built on Matplotlib.

It provides high-level functions for creating attractive and informative statistical charts.

### Installation

```bash
pip install seaborn
```

### Importing

```python
import seaborn as sns
import matplotlib.pyplot as plt
```

### 1. Scatter Plot

```python
import seaborn as sns
import matplotlib.pyplot as plt

data = sns.load_dataset("tips")

sns.scatterplot(
    data=data,
    x="total_bill",
    y="tip"
)

plt.show()
```

### 2. Bar Plot

```python
sns.barplot(
    data=data,
    x="day",
    y="total_bill"
)

plt.show()
```

### 3. Box Plot

```python
sns.boxplot(
    data=data,
    x="day",
    y="total_bill"
)

plt.show()
```

### 4. Histogram

```python
sns.histplot(
    data=data,
    x="total_bill",
    kde=True
)

plt.show()
```

### 5. Heatmap

```python
import seaborn as sns
import matplotlib.pyplot as plt

data = sns.load_dataset("tips")

correlation = data.corr(numeric_only=True)

sns.heatmap(
    correlation,
    annot=True
)

plt.show()
```

### Applications of Seaborn

- Statistical visualization.
- Correlation analysis.
- Distribution analysis.
- Outlier identification.
- Exploratory Data Analysis.

---

# 🧪 PRACTICAL PYTHON PROJECTS

After completing the topics, students should practice real-world programming projects.

| No. | Project                      | Concepts Used                   |
| --- | ---------------------------- | ------------------------------- |
| 1   | Calculator                   | Variables, Operators, Functions |
| 2   | Student Marks Management     | Lists, Dictionaries, Conditions |
| 3   | Number Guessing Game         | Loops, Conditions               |
| 4   | ATM Simulation               | Functions, OOP                  |
| 5   | Employee Management System   | Classes, Objects                |
| 6   | File-Based Student Database  | File Handling                   |
| 7   | Password Validation          | Strings, Conditions             |
| 8   | Data Cleaning Project        | Pandas                          |
| 9   | Sales Data Analysis          | Pandas, NumPy                   |
| 10  | Data Visualization Dashboard | Matplotlib, Seaborn             |

---

# 🎯 PYTHON INTERVIEW PREPARATION

Students should be comfortable answering the following questions:

1. What is Python?
2. What are the features of Python?
3. What is the difference between a list and a tuple?
4. What is the difference between a set and a dictionary?
5. What is mutable and immutable?
6. What is the difference between `==` and `is`?
7. What is type conversion?
8. What is the difference between `break`, `continue` and `pass`?
9. What are functions?
10. What are `*args` and `**kwargs`?
11. What is a lambda function?
12. What is the difference between map and filter?
13. What is reduce?
14. What is list comprehension?
15. What is recursion?
16. What is exception handling?
17. What is the difference between shallow copy and deep copy?
18. What is OOP?
19. What is inheritance?
20. What is polymorphism?
21. What is encapsulation?
22. What is abstraction?
23. What is a constructor?
24. What is the difference between static methods and class methods?
25. What is NumPy?
26. What is Pandas?
27. What is the difference between Series and DataFrame?
28. What is `loc` and `iloc`?
29. How do you handle missing values?
30. What is GroupBy in Pandas?

---

# 📌 LEARNING ROADMAP

Follow this sequence to build strong Python programming skills.

```text
Python Fundamentals
       |
       v
Variables and Data Types
       |
       v
Operators and Conditions
       |
       v
Loops and Collections
       |
       v
Functions and Comprehensions
       |
       v
File Handling and Exceptions
       |
       v
Object-Oriented Programming
       |
       v
Advanced Python Concepts
       |
       v
NumPy
       |
       v
Pandas
       |
       v
Matplotlib and Seaborn
       |
       v
Real-World Data Science Projects
```

---

# 📖 OFFICIAL LEARNING RESOURCES

| Resource                      | Link                                                                       |
| ----------------------------- | -------------------------------------------------------------------------- |
| Python Official Documentation | [https://docs.python.org/3/](https://docs.python.org/3/)                   |
| Python Official Tutorial      | [https://docs.python.org/3/tutorial/](https://docs.python.org/3/tutorial/) |
| Python Downloads              | [https://www.python.org/downloads/](https://www.python.org/downloads/)     |
| NumPy Documentation           | [https://numpy.org/doc/](https://numpy.org/doc/)                           |
| Pandas Documentation          | [https://pandas.pydata.org/docs/](https://pandas.pydata.org/docs/)         |
| Matplotlib Documentation      | [https://matplotlib.org/stable/](https://matplotlib.org/stable/)           |
| Seaborn Documentation         | [https://seaborn.pydata.org/](https://seaborn.pydata.org/)                 |

---

# ⭐ FINAL NOTE

Learning Python is not just about memorizing syntax. It is about understanding programming logic, solving problems and applying concepts to real-world situations.

**Practice every concept. Write your own programs. Debug errors. Build projects.**

Keep learning and keep building!

Happy Coding! 🐍

---

\<p align="center">   \<b>Python Programming – From Basics to Advanced\</b>\<br>   Learn • Practice • Build • Grow \</p>

\<p align="center">   ⭐ If you find this repository useful, consider giving it a star! \</p>
