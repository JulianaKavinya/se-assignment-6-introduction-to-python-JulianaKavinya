[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/WfNmjXUk)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15374624&assignment_repo_type=AssignmentRepo)
# SE-Assignment-6
 Assignment: Introduction to Python
Instructions:
Answer the following questions based on your understanding of Python programming. Provide detailed explanations and examples where appropriate.

 Questions:

1. Python Basics:
   - What is Python, and what are some of its key features that make it popular among developers? Provide examples of use cases where Python is particularly effective.

   - Python is a high-level, interpreted programming language known for its simplicity and readability. Its key features include:

1. Easy to Read and Write: Python's syntax is clear and intuitive, making it easy to learn and use.
Interpreted Language: Python code is executed line by line, which makes debugging easier.
2. Dynamically Typed: You don’t need to declare the type of variable. It is decided at runtime.
3. Extensive Standard Library: Python has a rich set of libraries and frameworks for various applications.
4. Versatility: It is used in web development, data analysis, artificial intelligence, scientific computing, and more.
5. Community Support: A large, active community contributes to a wealth of resources and libraries.

### Use Cases:

1. Web Development: Using frameworks like Django and Flask.
2. Data Analysis and Visualization: Libraries like Pandas, NumPy, and Matplotlib.
2. Machine Learning and AI: TensorFlow, Keras, and scikit-learn.
3. Scripting and Automation: Writing scripts to automate repetitive tasks.


2. Installing Python:
   - Describe the steps to install Python on your operating system (Windows, macOS, or Linux). Include how to verify the installation and set up a virtual environment.

#### Windows:

Download the Python installer from the official website.
Run the installer and check "Add Python to PATH".
Follow the installation steps.

#### macOS:

Download the Python installer from the official website.
Open the downloaded package and follow the installation steps.

#### Linux:

Open a terminal.
Run sudo apt-get update and sudo apt-get install python3.
Verify Installation:

Open a terminal or command prompt.
Type python --version or python3 --version to check the installation.

#### Setting Up a Virtual Environment:

Install virtualenv using pip install virtualenv.
Create a virtual environment using virtualenv myenv.
Activate the environment:
Windows: myenv\Scripts\activate
macOS/Linux: source myenv/bin/activate


3. Python Syntax and Semantics:
   - Write a simple Python program that prints "Hello, World!" to the console. Explain the basic syntax elements used in the program.

print("Hello, World!")
print: A built-in function that outputs text to the console.
"Hello, World!": A string literal enclosed in double quotes.


4. Data Types and Variables:
   - List and describe the basic data types in Python. Write a short script that demonstrates how to create and use variables of different data types.

1. int: Integer numbers.
2. float: Floating-point numbers.
3. str: Strings.
4. bool: Boolean values (True or False).
5. list: Ordered collection of items.
6. dict: Key-value pairs.
7. tuple: Ordered, immutable collection of items.
8. set: Unordered collection of unique items.


Script:

python
Copy code
### Integer
age = 25
print("Age:", age)

### Float
height = 5.8
print("Height:", height)

### String
name = "Juliana"
print("Name:", name)

### Boolean
is_student = True
print("Is student:", is_student)

### List
fruits = ["apple", "banana", "cherry"]
print("Fruits:", fruits)

### Dictionary
person = {"name": "Juliana", "age": 25}
print("Person:", person)

### Tuple
coordinates = (10.0, 20.0)
print("Coordinates:", coordinates)

### Set
unique_numbers = {1, 2, 3, 4, 5}
print("Unique numbers:", unique_numbers)


5. Control Structures:
   - Explain the use of conditional statements and loops in Python. Provide examples of an `if-else` statement and a `for` loop.

   age = 18
if age >= 18:
    print("You are an adult.")
else:
    print("You are a minor.")
if: Starts a conditional statement.
else: Provides an alternative block of code if the condition is not met.
Loops:

python
Copy code
# For loop
for i in range(5):
    print("Iteration:", i)

# While loop
count = 0
while count < 5:
    print("Count:", count)
    count += 1
for: Iterates over a sequence (like a list or range).
while: Repeats as long as a condition is true.


6. Functions in Python:
   - What are functions in Python, and why are they useful? Write a Python function that takes two arguments and returns their sum. Include an example of how to call this function.
   def add_numbers(a, b):
    return a + b

# Calling the function
result = add_numbers(5, 7)
print("Sum:", result)


7. Lists and Dictionaries:
   - Describe the differences between lists and dictionaries in Python. Write a script that creates a list of numbers and a dictionary with some key-value pairs, then demonstrates basic operations on both.

Lists:

Ordered collection of items.
Indexed by position.
Dictionaries:

Collection of key-value pairs.
Indexed by keys.
Script:

python
Copy code
# List of numbers
numbers = [1, 2, 3, 4, 5]
print("Numbers:", numbers)

# Adding an element
numbers.append(6)
print("Updated Numbers:", numbers)

# Dictionary with key-value pairs
student = {"name": "Juliana", "age": 25, "course": "Computer Science"}
print("Student:", student)

# Accessing a value
print("Student's Name:", student["name"])

# Updating a value
student["age"] = 26
print("Updated Student:", student)


8. Exception Handling:
   - What is exception handling in Python? Provide an example of how to use `try`, `except`, and `finally` blocks to handle errors in a Python script.

try:
    result = 10 / 0
except ZeroDivisionError:
    print("Cannot divide by zero.")
finally:
    print("This block always executes.")


9. Modules and Packages:
   - Explain the concepts of modules and packages in Python. How can you import and use a module in your script? Provide an example using the `math` module.

import math

# Using math module functions
print("Square root of 16:", math.sqrt(16))
print("Pi value:", math.pi)


10. File I/O:
    - How do you read from and write to files in Python? Write a script that reads the content of a file and prints it to the console, and another script that writes a list of strings to a file.

Reading from a file:

with open('example.txt', 'r') as file:
    content = file.read()
    print(content)


Writing to a file:

lines = ["Hello", "World", "This is a file"]

with open('output.txt', 'w') as file:
    for line in lines:
        file.write(line + "\n")



# Submission Guidelines:
- Your answers should be well-structured, concise, and to the point.
- Provide code snippets or complete scripts where applicable.
- Cite any references or sources you use in your answers.
- Submit your completed assignment by [due date].


