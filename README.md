🐍 Complete Python Programming – From Basics to Advanced


Welcome to the Complete Python Programming Repository!

This repository is designed to help students, beginners, aspiring developers and data science enthusiasts learn Python programming from the fundamentals to advanced concepts.

Each topic includes:

Easy-to-understand explanations.
Python syntax.
Practical code examples.
Expected outputs.
Real-world applications.
Important concepts and best practices.
The goal is to build strong programming fundamentals and prepare learners for careers in Data Analytics, Data Science, Machine Learning, Artificial Intelligence and Generative AI.

📚 Table of Contents
🟢 LEVEL 1 – Python Basics
Introduction to Python
Python Installation and Environment
Python Variables
Python Comments
Python Data Types
Python Numbers
Python Strings
Python Type Conversion
Python Operators
Python Input and Output
Conditional Statements
Python Loops
Python Lists
Python Tuples
Python Sets
Python Dictionaries
🟡 LEVEL 2 – Python Intermediate
Python Functions
Function Arguments
Lambda Functions
Map Function
Filter Function
Reduce Function
List Comprehension
Dictionary Comprehension
Python Modules
Python File Handling
Python Exception Handling
Python Math Module
🔴 LEVEL 3 – Python Advanced
Object-Oriented Programming
Classes and Objects
Constructors
Inheritance
Polymorphism
Encapsulation
Abstraction
Static Methods and Class Methods
Super Keyword
Shallow Copy and Deep Copy
Recursion
Iterators and Generators
Decorators
Arrays Without NumPy
🔵 LEVEL 4 – Python for Data Science
Introduction to NumPy
NumPy Arrays
NumPy Indexing and Slicing
NumPy Operations
Introduction to Pandas
Pandas Series
Pandas DataFrame
Data Selection and Filtering
Handling Missing Values
Removing Duplicates
Data Transformation
Sorting and Grouping
Matplotlib
Seaborn
🟢 LEVEL 1 – PYTHON BASICS
1. Introduction to Python
What is Python?
Python is a high-level, interpreted, general-purpose programming language known for its simple syntax and readability.

Python was created by Guido van Rossum and first released in 1991.

Python is widely used in:

Data Science
Data Analytics
Artificial Intelligence
Machine Learning
Deep Learning
Web Development
Automation
Generative AI
Natural Language Processing
Why Learn Python?
Easy to learn and understand.
Simple and readable syntax.
Large collection of libraries.
Strong community support.
Suitable for beginners and professionals.
Supports multiple programming paradigms.
First Python Program
Syntax:

print("Your message")
Example:

print("Hello World")
print("Welcome to Python Programming")
Output:

Hello World
Welcome to Python Programming
The print() function displays information on the screen.

2. Python Installation and Environment
To execute Python programs, we need to install Python and choose a development environment.

Installation
Download Python:

https://www.python.org/downloads/

Popular development environments:

VS Code
Jupyter Notebook
Google Colab
PyCharm
Spyder
Check Python Version
python --version
Install Libraries
pip install numpy
pip install pandas
pip install matplotlib
pip install seaborn
Execute Python File
python filename.py
3. Python Variables
What is a Variable?
A variable is a named memory reference used to store and access data in a Python program.

Python automatically determines the data type based on the assigned value.

Syntax
variable_name = value
Example
name = "Kamal"
age = 25
salary = 45000
percentage = 85.5

print(name)
print(age)
print(salary)
print(percentage)
Output:

Kamal
25
45000
85.5
Multiple Variable Assignment
a, b, c = 10, 20, 30

print(a)
print(b)
print(c)
Output:

10
20
30
Assigning the Same Value
a = b = c = 100

print(a, b, c)
Output:

100 100 100
Rules for Naming Variables
Variable names must begin with a letter or underscore.
Variable names cannot start with numbers.
Variable names cannot contain spaces.
Python is case-sensitive.
Reserved keywords cannot be used as variable names.
Example:

student_name = "Rahul"
Student_age = 21

print(student_name)
print(Student_age)
4. Python Comments
What are Comments?
Comments are statements written inside a program to explain the code. Python ignores comments during execution.

Single-Line Comment
Syntax:

# This is a comment
Example:

# Printing student information

name = "Kamal"
print(name)
Output:

Kamal
Multi-Line Comments
Python does not have a dedicated multi-line comment syntax. Multiple # lines are commonly used.

# This is the first comment.
# This is the second comment.
# This is the third comment.

print("Python Programming")
Output:

Python Programming
Triple-quoted strings are also commonly used for documentation strings (docstrings), but they are not technically comments.

5. Python Data Types
What are Data Types?
Data types define the kind of value stored in a variable.

Python provides several built-in data types.

Data Type	Description	Example
int	Integer numbers	100
float	Decimal numbers	10.5
complex	Complex numbers	2+3j
str	Text	"Python"
bool	True or False	True
list	Ordered, mutable collection	[1,2,3]
tuple	Ordered, immutable collection	(1,2,3)
set	Unordered collection of unique values	{1,2,3}
dict	Key-value collection	{"name":"Kamal"}
NoneType	Absence of a value	None
Example
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
Output:

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
The type() function identifies the data type of a value.

6. Python Numbers
Python supports three primary numeric types:

Integer
Float
Complex
Integer
Integer values are whole numbers without decimal points.

a = 100
b = -50

print(a)
print(b)
print(type(a))
Output:

100
-50
<class 'int'>
Float
Float values contain decimal points.

a = 10.5
b = 20.75

print(a + b)
print(type(a))
Output:

31.25
<class 'float'>
Complex
Complex numbers contain real and imaginary parts.

a = 2 + 3j

print(a)
print(a.real)
print(a.imag)
Output:

(2+3j)
2.0
3.0
Numeric Functions
a = -25

print(abs(a))
print(pow(2, 3))
print(round(10.567, 2))
print(max(10, 20, 30))
print(min(10, 20, 30))
Output:

25
8
10.57
30
10
7. Python Strings
What is a String?
A string is a sequence of characters enclosed within single, double or triple quotation marks.

Syntax
variable = "String value"
Example
name = "Python Programming"

print(name)
print(type(name))
print(len(name))
Output:

Python Programming
<class 'str'>
18
String Indexing
Indexing is used to access individual characters.

name = "PYTHON"

print(name[0])
print(name[1])
print(name[-1])
Output:

P
Y
N
String Slicing
Slicing extracts a portion of a string.

Syntax:

string[start:end:step]
Example:

name = "PYTHON PROGRAMMING"

print(name[0:6])
print(name[7:18])
print(name[::-1])
Output:

PYTHON
PROGRAMMING
GNIMMARGORP NOHTYP
Important String Methods
name = "python programming"

print(name.upper())
print(name.lower())
print(name.title())
print(name.capitalize())
print(name.replace("python", "Java"))
print(name.count("m"))
print(name.startswith("python"))
print(name.endswith("programming"))
Output:

PYTHON PROGRAMMING
python programming
Python Programming
Python programming
Java programming
2
True
True
String Formatting
name = "Kamal"
age = 25

print(f"My name is {name} and my age is {age}")
Output:

My name is Kamal and my age is 25
Important Point
Strings are immutable. This means individual characters cannot be modified directly.

8. Python Type Conversion
What is Type Conversion?
Type conversion means converting one data type into another.

Python supports two types:

Implicit Type Conversion
Explicit Type Conversion
Implicit Conversion
Python automatically converts compatible numeric types.

a = 10
b = 5.5

c = a + b

print(c)
print(type(c))
Output:

15.5
<class 'float'>
Explicit Conversion
The programmer manually converts the data type.

a = "100"

b = int(a)

print(b)
print(type(b))
Output:

100
<class 'int'>
Important Conversion Functions
int()
float()
str()
bool()
list()
tuple()
set()
dict()
Example
a = 10
b = str(a)

print(b)
print(type(b))
Output:

10
<class 'str'>
Important: Converting a string containing non-numeric text into an integer raises a ValueError.

9. Python Operators
What are Operators?
Operators are symbols or keywords used to perform operations on variables and values.

Python provides several categories of operators.

1. Arithmetic Operators
Operator	Description	Example
+	Addition	10 + 5
-	Subtraction	10 - 5
*	Multiplication	10 * 5
/	Division	10 / 5
//	Floor Division	10 // 3
%	Modulus	10 % 3
**	Exponentiation	2 ** 3
Example:

a = 10
b = 3

print(a + b)
print(a - b)
print(a * b)
print(a / b)
print(a // b)
print(a % b)
print(a ** b)
Output:

13
7
30
3.3333333333333335
3
1
1000
2. Comparison Operators
These operators compare two values and return Boolean results.

a = 10
b = 20

print(a == b)
print(a != b)
print(a > b)
print(a < b)
print(a >= b)
print(a <= b)
Output:

False
True
False
True
False
True
3. Logical Operators
Logical operators combine conditional expressions.

a = 10

print(a > 5 and a < 20)
print(a > 15 or a < 20)
print(not(a > 5))
Output:

True
True
False
4. Assignment Operators
a = 10

a += 5
print(a)

a -= 3
print(a)

a *= 2
print(a)
Output:

15
12
24
5. Membership Operators
Membership operators check whether an element exists in a collection.

name = "Python"

print("P" in name)
print("Java" not in name)
Output:

True
True
6. Identity Operators
Identity operators check whether two references point to the same object.

a = [1, 2, 3]
b = a
c = [1, 2, 3]

print(a is b)
print(a is c)
print(a == c)
Output:

True
False
True
10. Python Input and Output
Input Function
The input() function accepts information from the user.

name = input("Enter your name: ")

print("Welcome", name)
Sample Input:

Kamal
Output:

Welcome Kamal
Accepting Integer Input
a = int(input("Enter first number: "))
b = int(input("Enter second number: "))

print("Sum:", a + b)
Sample Input:

Enter first number: 10
Enter second number: 20
Output:

Sum: 30
Important Point
The input() function returns a string. Use int() or float() when numeric input is required.

11. Conditional Statements
What are Conditional Statements?
Conditional statements allow Python to execute different blocks of code depending on whether a condition is True or False.

Python supports:

if
if-else
if-elif-else
Nested if
1. If Statement
Syntax:

if condition:
    statement
Example:

age = 20

if age >= 18:
    print("Eligible to vote")
Output:

Eligible to vote
2. If-Else Statement
age = 16

if age >= 18:
    print("Eligible to vote")
else:
    print("Not eligible to vote")
Output:

Not eligible to vote
3. If-Elif-Else Statement
marks = 85

if marks >= 90:
    print("Grade A")
elif marks >= 75:
    print("Grade B")
elif marks >= 50:
    print("Grade C")
else:
    print("Fail")
Output:

Grade B
4. Nested If
age = 22
has_id = True

if age >= 18:
    if has_id:
        print("Entry allowed")
    else:
        print("ID required")
else:
    print("Entry denied")
Output:

Entry allowed
Real-World Application
Conditional statements are used in:

Login authentication.
Student grading systems.
Payment verification.
Eligibility checking.
Banking applications.
12. Python Loops
What are Loops?
Loops are used to execute a block of code repeatedly.

Python provides two primary loops:

For Loop
While Loop
1. For Loop
A for loop iterates over a sequence or iterable.

Syntax:

for variable in sequence:
    statement
Example:

for i in range(1, 6):
    print(i)
Output:

1
2
3
4
5
Understanding range()
range(start, stop, step)
Example:

for i in range(2, 11, 2):
    print(i)
Output:

2
4
6
8
10
2. While Loop
A while loop executes as long as the condition remains True.

Syntax:

while condition:
    statement
Example:

i = 1

while i <= 5:
    print(i)
    i += 1
Output:

1
2
3
4
5
3. Break Statement
The break statement terminates the loop.

for i in range(1, 6):

    if i == 4:
        break

    print(i)
Output:

1
2
3
4. Continue Statement
The continue statement skips the current iteration.

for i in range(1, 6):

    if i == 3:
        continue

    print(i)
Output:

1
2
4
5
5. Pass Statement
The pass statement acts as a placeholder.

for i in range(5):

    if i == 2:
        pass

    print(i)
Output:

0
1
2
3
4
13. Python Lists
What is a List?
A list is an ordered, mutable collection that can store multiple values of different data types.

Lists allow duplicate values.

Syntax
list_name = [value1, value2, value3]
Example
students = ["Kamal", "Rahul", "Arun"]

print(students)
print(students[0])
print(students[-1])
Output:

['Kamal', 'Rahul', 'Arun']
Kamal
Arun
List Slicing
numbers = [10, 20, 30, 40, 50]

print(numbers[0:3])
print(numbers[2:])
print(numbers[::-1])
Output:

[10, 20, 30]
[30, 40, 50]
[50, 40, 30, 20, 10]
Important List Methods
Method	Description
append()	Adds an element at the end
insert()	Adds an element at a specified position
extend()	Adds multiple elements
remove()	Removes a specified element
pop()	Removes and returns an element
sort()	Sorts the list
reverse()	Reverses the list
index()	Returns the position
count()	Counts occurrences
clear()	Removes all elements
Example
numbers = [10, 20, 30]

numbers.append(40)
print(numbers)

numbers.insert(1, 15)
print(numbers)

numbers.remove(20)
print(numbers)

numbers.sort()
print(numbers)
Output:

[10, 20, 30, 40]
[10, 15, 20, 30, 40]
[10, 15, 30, 40]
[10, 15, 30, 40]
14. Python Tuples
What is a Tuple?
A tuple is an ordered collection of elements that cannot be modified after creation.

Tuples are immutable and allow duplicate values.

Syntax
tuple_name = (value1, value2, value3)
Example
numbers = (10, 20, 30, 40)

print(numbers)
print(numbers[0])
print(numbers[-1])
Output:

(10, 20, 30, 40)
10
40
Tuple Methods
numbers = (10, 20, 10, 30, 40)

print(numbers.count(10))
print(numbers.index(30))
Output:

2
3
Tuple Unpacking
student = ("Kamal", 25, "Python")

name, age, course = student

print(name)
print(age)
print(course)
Output:

Kamal
25
Python
Important Point
A tuple containing one element requires a trailing comma.

a = (10,)

print(type(a))
Output:

<class 'tuple'>
15. Python Sets
What is a Set?
A set is an unordered collection of unique elements.

Sets automatically remove duplicate values.

Syntax
set_name = {value1, value2, value3}
Example
numbers = {10, 20, 30, 10, 20}

print(numbers)
Output:

{10, 20, 30}
Note: Set output order is not guaranteed.

Important Set Methods
numbers = {10, 20, 30}

numbers.add(40)
print(numbers)

numbers.update([50, 60])
print(numbers)

numbers.remove(20)
print(numbers)

numbers.discard(100)
print(numbers)
Set Operations
Union:

a = {1, 2, 3}
b = {3, 4, 5}

print(a.union(b))
Output:

{1, 2, 3, 4, 5}
Intersection:

print(a.intersection(b))
Output:

{3}
Difference:

print(a.difference(b))
Output:

{1, 2}
Symmetric Difference:

print(a.symmetric_difference(b))
Output:

{1, 2, 4, 5}
Real-World Application
Sets are useful for removing duplicate records, finding common customers and comparing datasets.

16. Python Dictionaries
What is a Dictionary?
A dictionary stores data in key-value pairs.

Dictionaries are mutable and preserve insertion order.

Syntax
dictionary_name = {
    "key": "value"
}
Example
student = {
    "name": "Kamal",
    "age": 25,
    "course": "Python"
}

print(student)
print(student["name"])
print(student["age"])
Output:

{'name': 'Kamal', 'age': 25, 'course': 'Python'}
Kamal
25
Accessing Values
student = {
    "name": "Rahul",
    "age": 22
}

print(student.get("name"))
print(student.get("city", "Not Available"))
Output:

Rahul
Not Available
Adding and Updating Values
student = {"name": "Kamal"}

student["age"] = 25
student["course"] = "Data Science"

print(student)
Output:

{'name': 'Kamal', 'age': 25, 'course': 'Data Science'}
Important Dictionary Methods
student = {
    "name": "Kamal",
    "age": 25,
    "course": "Python"
}

print(student.keys())
print(student.values())
print(student.items())
Output:

dict_keys(['name', 'age', 'course'])
dict_values(['Kamal', 25, 'Python'])
dict_items([('name', 'Kamal'), ('age', 25), ('course', 'Python')])
Iterating Through a Dictionary
student = {
    "name": "Kamal",
    "age": 25
}

for key, value in student.items():
    print(key, ":", value)
Output:

name : Kamal
age : 25
🟡 LEVEL 2 – PYTHON INTERMEDIATE
17. Python Functions
What is a Function?
A function is a reusable block of code designed to perform a particular task.

Functions help reduce code duplication and improve code organization.

Syntax
def function_name():
    statements

function_name()
Example Without Function
print("Welcome to Python")
print("Welcome to Python")
print("Welcome to Python")
Example With Function
def welcome():
    print("Welcome to Python")

welcome()
welcome()
welcome()
Output:

Welcome to Python
Welcome to Python
Welcome to Python
Function With Parameters
def addition(a, b):
    print(a + b)

addition(10, 20)
Output:

30
Function With Return
The return statement sends a result back to the caller.

def addition(a, b):
    return a + b

result = addition(10, 20)

print(result)
Output:

30
Returning Multiple Values
def calculation(a, b):

    addition = a + b
    multiplication = a * b

    return addition, multiplication

sum_result, product_result = calculation(10, 20)

print(sum_result)
print(product_result)
Output:

30
200
Function Calling Another Function
def is_even(number):
    return number % 2 == 0

def check_number(number):

    if is_even(number):
        return "Even Number"

    return "Odd Number"

print(check_number(10))
Output:

Even Number
18. Function Arguments
Python supports different ways of passing arguments to functions.

1. Positional Arguments
def student(name, age):
    print(name, age)

student("Kamal", 25)
Output:

Kamal 25
2. Keyword Arguments
def student(name, age):
    print(name, age)

student(age=25, name="Kamal")
Output:

Kamal 25
3. Default Arguments
def student(name, age=20):
    print(name, age)

student("Kamal")
student("Rahul", 25)
Output:

Kamal 20
Rahul 25
4. Variable-Length Arguments (*args)
*args allows a function to accept any number of positional arguments.

def addition(*numbers):

    total = 0

    for i in numbers:
        total += i

    return total

print(addition(10, 20))
print(addition(10, 20, 30, 40))
Output:

30
100
5. Keyword Variable Arguments (**kwargs)
**kwargs allows a function to accept multiple keyword arguments.

def student(**details):

    for key, value in details.items():
        print(key, value)

student(name="Kamal", age=25, course="Python")
Output:

name Kamal
age 25
course Python
19. Lambda Functions
What is a Lambda Function?
A lambda function is a small anonymous function created using the lambda keyword.

It is useful when a short function is needed without defining it using def.

Syntax
lambda arguments: expression
Example
addition = lambda a, b: a + b

print(addition(10, 20))
Output:

30
Square of a Number
square = lambda x: x ** 2

print(square(5))
Output:

25
Even or Odd
check = lambda x: "Even" if x % 2 == 0 else "Odd"

print(check(10))
print(check(7))
Output:

Even
Odd
Real-World Application
Lambda functions are often used with:

map()
filter()
sorted()
reduce()
20. Map Function
What is map()?
The map() function applies a specified function to every element of an iterable.

Syntax
map(function, iterable)
Example
numbers = [1, 2, 3, 4, 5]

def square(x):
    return x ** 2

result = map(square, numbers)

print(list(result))
Output:

[1, 4, 9, 16, 25]
Map With Lambda
numbers = [1, 2, 3, 4]

result = map(lambda x: x + 10, numbers)

print(list(result))
Output:

[11, 12, 13, 14]
Map With Multiple Iterables
a = [1, 2, 3]
b = [10, 20, 30]

result = map(lambda x, y: x + y, a, b)

print(list(result))
Output:

[11, 22, 33]
21. Filter Function
What is filter()?
The filter() function selects elements from an iterable based on a condition.

It retains elements for which the function returns True.

Syntax
filter(function, iterable)
Example
numbers = [1, 2, 3, 4, 5, 6, 7, 8]

result = filter(lambda x: x % 2 == 0, numbers)

print(list(result))
Output:

[2, 4, 6, 8]
Filtering Numbers Greater Than 5
numbers = [2, 4, 6, 8, 10, 12]

result = filter(lambda x: x > 5, numbers)

print(list(result))
Output:

[6, 8, 10, 12]
Real-World Application
Filter can be used to:

Find eligible students.
Filter customer records.
Select products by price.
Identify employees based on salary.
22. Reduce Function
What is reduce()?
The reduce() function repeatedly applies a function to the elements of an iterable and produces a single accumulated result.

It is available in the functools module.

Syntax
from functools import reduce

reduce(function, iterable)
Example: Sum of Elements
from functools import reduce

numbers = [1, 2, 3, 4, 5]

result = reduce(lambda x, y: x + y, numbers)

print(result)
Output:

15
Internal Working
1 + 2 = 3
3 + 3 = 6
6 + 4 = 10
10 + 5 = 15
Multiplication
from functools import reduce

numbers = [1, 2, 3, 4, 5]

result = reduce(lambda x, y: x * y, numbers)

print(result)
Output:

120
Finding Maximum Value
from functools import reduce

numbers = [10, 50, 20, 80, 30]

result = reduce(lambda x, y: x if x > y else y, numbers)

print(result)
Output:

80
23. List Comprehension
What is List Comprehension?
List comprehension is a concise way to create lists using an expression and an iterable.

Syntax
[expression for item in iterable]
Example
numbers = [1, 2, 3, 4, 5]

squares = [x ** 2 for x in numbers]

print(squares)
Output:

[1, 4, 9, 16, 25]
List Comprehension With Condition
numbers = [1, 2, 3, 4, 5, 6]

even = [x for x in numbers if x % 2 == 0]

print(even)
Output:

[2, 4, 6]
List Comprehension With If-Else
numbers = [1, 2, 3, 4, 5]

result = [
    "Even" if x % 2 == 0 else "Odd"
    for x in numbers
]

print(result)
Output:

['Odd', 'Even', 'Odd', 'Even', 'Odd']
24. Dictionary Comprehension
What is Dictionary Comprehension?
Dictionary comprehension is a concise way to create dictionaries using expressions and iterables.

Syntax
{key: value for item in iterable}
Example
numbers = [1, 2, 3, 4, 5]

squares = {x: x ** 2 for x in numbers}

print(squares)
Output:

{1: 1, 2: 4, 3: 9, 4: 16, 5: 25}
Dictionary Comprehension With Condition
numbers = [1, 2, 3, 4, 5, 6]

even = {
    x: x ** 2
    for x in numbers
    if x % 2 == 0
}

print(even)
Output:

{2: 4, 4: 16, 6: 36}
25. Python Modules
What is a Module?
A module is a Python file containing reusable functions, variables and classes.

Modules help organize code into separate files.

Importing a Module
import math

print(math.sqrt(25))
Output:

5.0
Importing Specific Functions
from math import sqrt

print(sqrt(36))
Output:

6.0
Importing With Alias
import math as m

print(m.factorial(5))
Output:

120
Creating a User-Defined Module
Create a file named calculator.py.

def addition(a, b):
    return a + b

def multiplication(a, b):
    return a * b
Create another file named main.py.

import calculator

print(calculator.addition(10, 20))
print(calculator.multiplication(10, 20))
Output:

30
200
26. Python File Handling
What is File Handling?
File handling is the process of creating, reading, writing, appending and managing files using Python.

Python supports several file modes.

Mode	Description
r	Read
w	Write; creates or overwrites
a	Append
x	Create a new file; fails if it exists
rb	Read binary
wb	Write binary
r+	Read and write
1. Writing a File
file = open("student.txt", "w")

file.write("Welcome to Python Programming")

file.close()
2. Reading a File
file = open("student.txt", "r")

print(file.read())

file.close()
Output:

Welcome to Python Programming
3. Appending Data
file = open("student.txt", "a")

file.write("\nWelcome to Data Science")

file.close()
4. Reading One Line
file = open("student.txt", "r")

print(file.readline())

file.close()
5. Reading All Lines
file = open("student.txt", "r")

print(file.readlines())

file.close()
6. Using With Statement
The with statement automatically manages file closure.

with open("student.txt", "w") as file:

    file.write("Python File Handling")
Reading:

with open("student.txt", "r") as file:

    data = file.read()

    print(data)
Output:

Python File Handling
Real-World Applications
Reading CSV files.
Processing JSON data.
Creating reports.
Storing application logs.
Managing datasets.
27. Python Exception Handling
What is an Exception?
An exception is an error that occurs during program execution and interrupts the normal flow of a program.

Exception handling helps us manage runtime errors without abruptly terminating the application.

Common Python Exceptions
Exception	Description
ZeroDivisionError	Division by zero
NameError	Undefined variable
ValueError	Invalid value
TypeError	Incorrect data type operation
IndexError	Invalid sequence index
KeyError	Missing dictionary key
FileNotFoundError	File does not exist
AttributeError	Missing object attribute
Example Without Exception Handling
a = 10
b = 0

print(a / b)
Output:

ZeroDivisionError: division by zero
Try and Except
Syntax:

try:
    statements

except:
    error_handling
Example:

try:
    a = 10
    b = 0

    print(a / b)

except ZeroDivisionError:
    print("Cannot divide by zero")
Output:

Cannot divide by zero
Multiple Except Blocks
try:

    number = int(input("Enter a number: "))

    result = 100 / number

    print(result)

except ValueError:
    print("Please enter a valid number")

except ZeroDivisionError:
    print("Number cannot be zero")
Finally Block
The finally block executes whether an exception occurs or not.

try:
    print("Inside try block")

except Exception:
    print("Error occurred")

finally:
    print("Program completed")
Output:

Inside try block
Program completed
Else Block
The else block executes when no exception occurs.

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
Output:

Result: 5.0
Execution completed
Raising Exceptions
age = 15

if age < 18:
    raise ValueError("Age must be 18 or above")
28. Python Math Module
What is the Math Module?
The math module provides mathematical functions and constants.

Importing Math
import math
Important Math Functions
import math

print(math.sqrt(25))
print(math.pow(2, 3))
print(math.factorial(5))
print(math.ceil(10.2))
print(math.floor(10.8))
print(math.pi)
Output:

5.0
8.0
120
11
10
3.141592653589793
Other Important Functions
Function	Description
sqrt()	Square root
pow()	Power
factorial()	Factorial
ceil()	Rounds upward
floor()	Rounds downward
log()	Natural logarithm
log10()	Base-10 logarithm
exp()	Exponential
sin()	Sine
cos()	Cosine
tan()	Tangent
🔴 LEVEL 3 – PYTHON ADVANCED
29. Object-Oriented Programming
What is OOP?
Object-Oriented Programming (OOP) is a programming paradigm based on classes and objects.

It helps organize code into reusable and structured components.

Four Main Pillars of OOP
Encapsulation
Inheritance
Polymorphism
Abstraction
Advantages of OOP
Code reusability.
Better code organization.
Easy maintenance.
Data protection.
Scalability.
30. Classes and Objects
What is a Class?
A class is a blueprint used to create objects.

What is an Object?
An object is an instance of a class.

Syntax
class ClassName:
    statements

object_name = ClassName()
Example
class Student:

    name = "Kamal"
    age = 25

student1 = Student()

print(student1.name)
print(student1.age)
Output:

Kamal
25
Creating Multiple Objects
class Student:
    pass

student1 = Student()
student2 = Student()

student1.name = "Kamal"
student2.name = "Rahul"

print(student1.name)
print(student2.name)
Output:

Kamal
Rahul
31. Constructors
What is a Constructor?
A constructor is a special method that initializes an object's attributes when the object is created.

Python uses the __init__() method for initialization.

Syntax
class ClassName:

    def __init__(self):
        statements
Example
class Student:

    def __init__(self, name, age):

        self.name = name
        self.age = age

student1 = Student("Kamal", 25)

print(student1.name)
print(student1.age)
Output:

Kamal
25
Constructor With Methods
class Rectangle:

    def __init__(self, length, breadth):

        self.length = length
        self.breadth = breadth

    def area(self):

        return self.length * self.breadth

rectangle = Rectangle(10, 5)

print(rectangle.area())
Output:

50
32. Inheritance
What is Inheritance?
Inheritance allows one class to acquire attributes and methods from another class.

The existing class is called the Parent Class or Base Class.

The new class is called the Child Class or Derived Class.

Syntax
class Parent:
    statements

class Child(Parent):
    statements
Example
class Animal:

    def sound(self):
        print("Animals make sounds")

class Dog(Animal):

    def bark(self):
        print("Dog barks")

dog = Dog()

dog.sound()
dog.bark()
Output:

Animals make sounds
Dog barks
Types of Inheritance
Single Inheritance
Multiple Inheritance
Multilevel Inheritance
Hierarchical Inheritance
Hybrid Inheritance
Multiple Inheritance
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
Output:

Gardening
Cooking
33. Polymorphism
What is Polymorphism?
Polymorphism means one interface or operation can represent different behaviors depending on the object or context.

Example: Method Overriding
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
Output:

Dog barks
Cat meows
Polymorphism Using a Common Interface
class Circle:

    def area(self):
        return 3.14 * 5 * 5

class Square:

    def area(self):
        return 10 * 10

shapes = [Circle(), Square()]

for shape in shapes:
    print(shape.area())
Output:

78.5
100
34. Encapsulation
What is Encapsulation?
Encapsulation is the concept of combining data and methods inside a class while controlling how the internal data is accessed or modified.

Python uses naming conventions for attribute visibility:

Public: name
Protected by convention: _name
Name-mangled: __name
Example
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
Output:

1500
Important: Double underscores trigger name mangling. They do not provide absolute security or strict private access.

35. Abstraction
What is Abstraction?
Abstraction means exposing essential functionality while hiding unnecessary implementation details.

Python supports abstraction through the abc module.

Example
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
Output:

Car started
Real-World Example
When using an ATM, users interact with buttons and options without needing to understand the internal banking system.

This is an example of abstraction.

36. Static Methods and Class Methods
Python supports three commonly used method types:

Instance Methods
Class Methods
Static Methods
1. Instance Method
Instance methods receive self and work with object-specific data.

class Student:

    def __init__(self, name):
        self.name = name

    def display(self):
        print(self.name)

student = Student("Kamal")

student.display()
Output:

Kamal
2. Class Method
Class methods receive cls and operate on class-level data.

class Student:

    college = "ABC College"

    @classmethod
    def display(cls):
        print(cls.college)

Student.display()
Output:

ABC College
3. Static Method
Static methods do not automatically receive self or cls.

class Calculator:

    @staticmethod
    def addition(a, b):
        return a + b

print(Calculator.addition(10, 20))
Output:

30
37. Super Keyword
What is super()?
The super() function provides access to methods from a parent class.

It is commonly used in inheritance to extend parent class behavior.

Example
class Parent:

    def display(self):
        print("Parent Class")

class Child(Parent):

    def display(self):

        super().display()

        print("Child Class")

obj = Child()

obj.display()
Output:

Parent Class
Child Class
38. Shallow Copy and Deep Copy
What is Copying?
Copying creates another object based on an existing object.

Python provides two important copying techniques:

Shallow Copy
Deep Copy
Shallow Copy
A shallow copy creates a new outer object but keeps references to nested objects.

import copy

original = [[1, 2], [3, 4]]

new_list = copy.copy(original)

new_list[0][0] = 100

print(original)
print(new_list)
Output:

[[100, 2], [3, 4]]
[[100, 2], [3, 4]]
Deep Copy
A deep copy creates a new outer object and recursively copies nested objects.

import copy

original = [[1, 2], [3, 4]]

new_list = copy.deepcopy(original)

new_list[0][0] = 100

print(original)
print(new_list)
Output:

[[1, 2], [3, 4]]
[[100, 2], [3, 4]]
Difference
Shallow Copy	Deep Copy
Creates a new outer object	Creates independent nested copies
Nested objects are shared	Nested objects are copied
Uses copy.copy()	Uses copy.deepcopy()
39. Recursion
What is Recursion?
Recursion is a programming technique in which a function calls itself to solve a problem.

A recursive function requires a base condition to stop further recursive calls.

Example: Factorial
def factorial(n):

    if n == 0 or n == 1:
        return 1

    return n * factorial(n - 1)

print(factorial(5))
Output:

120
Internal Working
factorial(5)
5 * factorial(4)
5 * 4 * factorial(3)
5 * 4 * 3 * factorial(2)
5 * 4 * 3 * 2 * factorial(1)

Result = 120
Fibonacci Using Recursion
def fibonacci(n):

    if n <= 1:
        return n

    return fibonacci(n - 1) + fibonacci(n - 2)

for i in range(7):
    print(fibonacci(i), end=" ")
Output:

0 1 1 2 3 5 8
40. Iterators and Generators
Iterators
An iterator is an object that allows sequential access to elements using next().

Example
numbers = [10, 20, 30]

iterator = iter(numbers)

print(next(iterator))
print(next(iterator))
print(next(iterator))
Output:

10
20
30
Calling next() after the last element raises StopIteration.

Generators
A generator is a special type of iterator that produces values one at a time using the yield keyword.

Syntax
def generator_name():
    yield value
Example
def numbers():

    yield 10
    yield 20
    yield 30

for i in numbers():
    print(i)
Output:

10
20
30
Generator With Range
def square_numbers(n):

    for i in range(1, n + 1):
        yield i ** 2

for value in square_numbers(5):
    print(value)
Output:

1
4
9
16
25
41. Decorators
What is a Decorator?
A decorator is a function that modifies or extends the behavior of another function without changing its original source code.

Example
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
Output:

Before function execution
Welcome to Python
After function execution
Real-World Applications
Logging
Authentication
Performance measurement
Access control
Caching
42. Arrays Without NumPy
What is an Array?
An array is a collection of elements stored in a structured sequence.

Python's built-in array module provides typed arrays.

Example
import array

numbers = array.array('i', [10, 20, 30, 40])

print(numbers)
print(numbers[0])
Output:

array('i', [10, 20, 30, 40])
10
Adding Elements
import array

numbers = array.array('i', [10, 20, 30])

numbers.append(40)

print(numbers)
Output:

array('i', [10, 20, 30, 40])
🔵 LEVEL 4 – PYTHON FOR DATA SCIENCE
43. Introduction to NumPy
What is NumPy?
NumPy stands for Numerical Python.

It is a powerful Python library used for numerical computation, scientific computing and multidimensional array operations.

NumPy is widely used in:

Data Science
Machine Learning
Deep Learning
Statistical Computing
Scientific Research
Installing NumPy
pip install numpy
Importing NumPy
import numpy as np
Why NumPy?
Efficient multidimensional arrays.
Fast mathematical operations.
Broadcasting support.
Array indexing and slicing.
Linear algebra operations.
Integration with Pandas and Machine Learning libraries.
44. NumPy Arrays
What is an ndarray?
An ndarray is the primary multidimensional array object provided by NumPy.

Creating a One-Dimensional Array
import numpy as np

arr = np.array([10, 20, 30, 40])

print(arr)
print(arr.ndim)
print(arr.shape)
print(arr.size)
Output:

[10 20 30 40]
1
(4,)
4
Creating a Two-Dimensional Array
import numpy as np

arr = np.array([
    [1, 2, 3],
    [4, 5, 6]
])

print(arr)
print(arr.ndim)
print(arr.shape)
Output:

[[1 2 3]
 [4 5 6]]
2
(2, 3)
Important Array Creation Functions
Zeros:

np.zeros((2, 3))
Output:

[[0. 0. 0.]
 [0. 0. 0.]]
Ones:

np.ones((2, 2))
Output:

[[1. 1.]
 [1. 1.]]
Arange:

np.arange(1, 10)
Output:

[1 2 3 4 5 6 7 8 9]
Identity Matrix:

np.eye(3)
Output:

[[1. 0. 0.]
 [0. 1. 0.]
 [0. 0. 1.]]
Reshape:

arr = np.arange(1, 7)

print(arr.reshape(2, 3))
Output:

[[1 2 3]
 [4 5 6]]
45. NumPy Indexing and Slicing
Array Indexing
import numpy as np

arr = np.array([10, 20, 30, 40, 50])

print(arr[0])
print(arr[2])
print(arr[-1])
Output:

10
30
50
Array Slicing
arr = np.array([10, 20, 30, 40, 50])

print(arr[1:4])
print(arr[:3])
print(arr[::-1])
Output:

[20 30 40]
[10 20 30]
[50 40 30 20 10]
Two-Dimensional Indexing
arr = np.array([
    [10, 20, 30],
    [40, 50, 60],
    [70, 80, 90]
])

print(arr[0, 1])
print(arr[2, 2])
Output:

20
90
46. NumPy Operations
Arithmetic Operations
import numpy as np

a = np.array([10, 20, 30])
b = np.array([1, 2, 3])

print(a + b)
print(a - b)
print(a * b)
print(a / b)
Output:

[11 22 33]
[ 9 18 27]
[10 40 90]
[10. 10. 10.]
Statistical Operations
arr = np.array([10, 20, 30, 40, 50])

print(np.sum(arr))
print(np.mean(arr))
print(np.median(arr))
print(np.min(arr))
print(np.max(arr))
print(np.std(arr))
Output:

150
30.0
30.0
10
50
14.142135623730951
Boolean Filtering
arr = np.array([10, 20, 30, 40, 50])

print(arr[arr > 25])
Output:

[30 40 50]
47. Introduction to Pandas
What is Pandas?
Pandas is an open-source Python library used for data manipulation, data cleaning and data analysis.

It provides two primary data structures:

Series
DataFrame
Installing Pandas
pip install pandas
Importing Pandas
import pandas as pd
Applications of Pandas
Data Cleaning
Data Transformation
Data Filtering
Data Analysis
Missing Value Handling
CSV and Excel Processing
Grouping and Aggregation
48. Pandas Series
What is a Series?
A Series is a one-dimensional labeled data structure capable of storing different types of values.

Syntax
pd.Series(data, index=None)
Example
import pandas as pd

data = [10, 20, 30, 40]

series = pd.Series(data)

print(series)
Output:

0    10
1    20
2    30
3    40
dtype: int64
Custom Index
series = pd.Series(
    [85, 90, 75],
    index=["Kamal", "Rahul", "Arun"]
)

print(series)
Output:

Kamal    85
Rahul    90
Arun     75
dtype: int64
Accessing Series Elements
print(series["Kamal"])
print(series.iloc[1])
Output:

85
90
49. Pandas DataFrame
What is a DataFrame?
A DataFrame is a two-dimensional labeled data structure consisting of rows and columns.

It is similar to a spreadsheet or database table.

Creating a DataFrame
import pandas as pd

data = {
    "Name": ["Kamal", "Rahul", "Arun"],
    "Age": [25, 22, 24],
    "Marks": [90, 85, 95]
}

df = pd.DataFrame(data)

print(df)
Output:

    Name  Age  Marks
0  Kamal   25     90
1  Rahul   22     85
2   Arun   24     95
Important DataFrame Attributes
print(df.shape)
print(df.columns)
print(df.index)
print(df.dtypes)
Important DataFrame Methods
Method	Description
head()	First five rows by default
tail()	Last five rows by default
info()	DataFrame information
describe()	Statistical summary
shape	Number of rows and columns
columns	Column names
dtypes	Data types
value_counts()	Frequency counts
Example
print(df.head(2))
print(df.describe())
50. Data Selection and Filtering
Selecting Columns
print(df["Name"])
Selecting Multiple Columns
print(df[["Name", "Marks"]])
Using loc()
loc selects data using row and column labels.

print(df.loc[0, "Name"])
Output:

Kamal
Using iloc()
iloc selects data using integer positions.

print(df.iloc[0, 1])
Output:

25
Filtering Records
result = df[df["Marks"] > 85]

print(result)
Output:

    Name  Age  Marks
0  Kamal   25     90
2   Arun   24     95
Multiple Conditions
result = df[
    (df["Age"] > 22) &
    (df["Marks"] >= 90)
]

print(result)
51. Handling Missing Values
What are Missing Values?
Missing values are records where information is unavailable or not recorded.

Pandas commonly represents missing numerical values using NaN.

Example
import pandas as pd
import numpy as np

data = {
    "Name": ["Kamal", "Rahul", "Arun"],
    "Marks": [90, np.nan, 80]
}

df = pd.DataFrame(data)

print(df)
Detecting Missing Values
print(df.isnull())
print(df.isnull().sum())
Removing Missing Values
df.dropna()
Filling Missing Values
df["Marks"] = df["Marks"].fillna(0)

print(df)
Output:

    Name  Marks
0  Kamal   90.0
1  Rahul    0.0
2   Arun   80.0
Filling With Mean
df["Marks"] = df["Marks"].fillna(df["Marks"].mean())
Important: Choose a missing-value strategy based on the meaning of the data. Replacing all missing values with zero is not always appropriate.

52. Removing Duplicates
What are Duplicate Records?
Duplicate records are repeated rows or values in a dataset.

Duplicates may affect data analysis and reporting.

Example
import pandas as pd

data = {
    "Name": ["Kamal", "Rahul", "Kamal"],
    "Age": [25, 22, 25]
}

df = pd.DataFrame(data)

print(df.duplicated())
Removing Duplicates
df = df.drop_duplicates()

print(df)
Output:

    Name  Age
0  Kamal   25
1  Rahul   22
53. Data Transformation
Data transformation means changing the structure, format or values of a dataset.

Adding a New Column
df["Result"] = ["Pass", "Pass", "Pass"]

print(df)
Renaming Columns
df = df.rename(
    columns={"Name": "Student_Name"}
)

print(df.columns)
Dropping a Column
df = df.drop("Age", axis=1)
Concatenating DataFrames
import pandas as pd

df1 = pd.DataFrame({
    "Name": ["Kamal", "Rahul"]
})

df2 = pd.DataFrame({
    "Name": ["Arun", "John"]
})

result = pd.concat([df1, df2], ignore_index=True)

print(result)
Output:

    Name
0  Kamal
1  Rahul
2   Arun
3   John
54. Sorting and Grouping
Sorting Data
The sort_values() method sorts records based on column values.

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
Output:

    Name  Marks
2   Arun     95
0  Kamal     90
1  Rahul     75
GroupBy
GroupBy divides data into groups based on one or more columns.

Example
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
Output:

Department
HR    35000.0
IT    55000.0
Name: Salary, dtype: float64
Important GroupBy Operations
df.groupby("Department")["Salary"].sum()
df.groupby("Department")["Salary"].mean()
df.groupby("Department")["Salary"].max()
df.groupby("Department")["Salary"].min()
df.groupby("Department")["Salary"].count()
55. Matplotlib
What is Matplotlib?
Matplotlib is a Python visualization library used to create charts, graphs and plots.

It helps convert numerical data into meaningful visual representations.

Installation
pip install matplotlib
Importing
import matplotlib.pyplot as plt
1. Line Plot
import matplotlib.pyplot as plt

x = [1, 2, 3, 4, 5]
y = [10, 20, 15, 30, 25]

plt.plot(x, y)

plt.title("Line Chart")
plt.xlabel("X Values")
plt.ylabel("Y Values")

plt.show()
2. Bar Chart
import matplotlib.pyplot as plt

students = ["Kamal", "Rahul", "Arun"]
marks = [90, 80, 95]

plt.bar(students, marks)

plt.title("Student Marks")
plt.xlabel("Students")
plt.ylabel("Marks")

plt.show()
3. Scatter Plot
import matplotlib.pyplot as plt

x = [10, 20, 30, 40]
y = [15, 25, 35, 45]

plt.scatter(x, y)

plt.title("Scatter Plot")

plt.show()
4. Histogram
import matplotlib.pyplot as plt

marks = [50, 60, 70, 70, 80, 90, 90, 95]

plt.hist(marks, bins=5)

plt.title("Marks Distribution")

plt.show()
5. Pie Chart
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
56. Seaborn
What is Seaborn?
Seaborn is a Python statistical data visualization library built on Matplotlib.

It provides high-level functions for creating attractive and informative statistical charts.

Installation
pip install seaborn
Importing
import seaborn as sns
import matplotlib.pyplot as plt
1. Scatter Plot
import seaborn as sns
import matplotlib.pyplot as plt

data = sns.load_dataset("tips")

sns.scatterplot(
    data=data,
    x="total_bill",
    y="tip"
)

plt.show()
2. Bar Plot
sns.barplot(
    data=data,
    x="day",
    y="total_bill"
)

plt.show()
3. Box Plot
sns.boxplot(
    data=data,
    x="day",
    y="total_bill"
)

plt.show()
4. Histogram
sns.histplot(
    data=data,
    x="total_bill",
    kde=True
)

plt.show()
5. Heatmap
import seaborn as sns
import matplotlib.pyplot as plt

data = sns.load_dataset("tips")

correlation = data.corr(numeric_only=True)

sns.heatmap(
    correlation,
    annot=True
)

plt.show()
Applications of Seaborn
Statistical visualization.
Correlation analysis.
Distribution analysis.
Outlier identification.
Exploratory Data Analysis.
🧪 PRACTICAL PYTHON PROJECTS
After completing the topics, students should practice real-world programming projects.

No.	Project	Concepts Used
1	Calculator	Variables, Operators, Functions
2	Student Marks Management	Lists, Dictionaries, Conditions
3	Number Guessing Game	Loops, Conditions
4	ATM Simulation	Functions, OOP
5	Employee Management System	Classes, Objects
6	File-Based Student Database	File Handling
7	Password Validation	Strings, Conditions
8	Data Cleaning Project	Pandas
9	Sales Data Analysis	Pandas, NumPy
10	Data Visualization Dashboard	Matplotlib, Seaborn
🎯 PYTHON INTERVIEW PREPARATION
Students should be comfortable answering the following questions:

What is Python?
What are the features of Python?
What is the difference between a list and a tuple?
What is the difference between a set and a dictionary?
What is mutable and immutable?
What is the difference between == and is?
What is type conversion?
What is the difference between break, continue and pass?
What are functions?
What are *args and **kwargs?
What is a lambda function?
What is the difference between map and filter?
What is reduce?
What is list comprehension?
What is recursion?
What is exception handling?
What is the difference between shallow copy and deep copy?
What is OOP?
What is inheritance?
What is polymorphism?
What is encapsulation?
What is abstraction?
What is a constructor?
What is the difference between static methods and class methods?
What is NumPy?
What is Pandas?
What is the difference between Series and DataFrame?
What is loc and iloc?
How do you handle missing values?
What is GroupBy in Pandas?
📌 LEARNING ROADMAP
Follow this sequence to build strong Python programming skills.

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
📖 OFFICIAL LEARNING RESOURCES
Resource	Link
Python Official Documentation	https://docs.python.org/3/
Python Official Tutorial	https://docs.python.org/3/tutorial/
Python Downloads	https://www.python.org/downloads/
NumPy Documentation	https://numpy.org/doc/
Pandas Documentation	https://pandas.pydata.org/docs/
Matplotlib Documentation	https://matplotlib.org/stable/
Seaborn Documentation	https://seaborn.pydata.org/
⭐ FINAL NOTE
Learning Python is not just about memorizing syntax. It is about understanding programming logic, solving problems and applying concepts to real-world situations.

Practice every concept. Write your own programs. Debug errors. Build projects.

Keep learning and keep building!

Happy Coding! 🐍

<p align="center"> <b>Python Programming – From Basics to Advanced</b><br> Learn • Practice • Build • Grow </p>

<p align="center"> ⭐ If you find this repository useful, consider giving it a star! </p>
