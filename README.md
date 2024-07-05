# SE-Assignment-6
 Assignment: Introduction to Python
Instructions:
Answer the following questions based on your understanding of Python programming. Provide detailed explanations and examples where appropriate.

 Questions:

1. Python Basics:
   - What is Python, and what are some of its key features that make it popular among developers? Provide examples of use cases where Python is particularly effective.
   Python is a high-level, interpreted programming language known for its simplicity and readability. It supports multiple programming paradigms, including procedural, object-oriented, and functional programming.
   Key Features:

   Easy to Learn and Read: Python's syntax resembles English, making it accessible for beginners and readable for experienced developers.
   Rich Standard Library: Includes modules and packages for diverse tasks such as web development, data analysis, and machine learning.
   Cross-platform: Runs on Windows, macOS, Linux, and other platforms without modification.
   Dynamic Typing: Variables do not need explicit declaration to reserve memory space.
   Strong Community Support: Active community providing libraries, frameworks, and extensive documentation.

   Use Cases:

   Web Development: Django and Flask frameworks.
   Data Science: Pandas, NumPy, and SciPy for data analysis.
   Machine Learning: TensorFlow and PyTorch for building AI models.
   Automation: Scripting tasks and building applications with ease.

2. Installing Python:
   - Describe the steps to install Python on your operating system (Windows, macOS, or Linux). Include how to verify the installation and set up a virtual environment.
   Steps to Install Python:

   Windows:
   Download the installer from python.org.
   Run the installer, ensuring to check "Add Python to PATH" during installation.

   Verifying Installation:

   Open a terminal or command prompt and type python --version or python3 --version to verify the installation.
   Setting Up a Virtual Environment:

   Install virtualenv using pip install virtualenv.
   Create a virtual environment: virtualenv venv.
   Activate the virtual environment:
   Windows: venv\Scripts\activate

3. Python Syntax and Semantics:
   - Write a simple Python program that prints "Hello, World!" to the console. Explain the basic syntax elements used in the program.
   # Python program to print Hello, World!
   print("Hello, World!")
   Explanation:

   print() is a built-in function in Python used to print output to the console.
   "Hello, World!" is a string literal enclosed in double quotes.

4. Data Types and Variables:
   - List and describe the basic data types in Python. Write a short script that demonstrates how to create and use variables of different data types.
   Basic Data Types:

   Integer (int): Whole numbers, e.g., 42.
   Float (float): Numbers with decimal points, e.g., 3.14.
   String (str): Sequence of characters, e.g., "Hello".
   Boolean (bool): Represents truth values True or False
   # Python script demonstrating data types and variables
   num = 42         # integer variable
   pi = 3.14        # float variable
   name = "Alice"   # string variable
   is_true = True   # boolean variable

   # Print variables
   print(num, pi, name, is_true)

5. Control Structures:
   - Explain the use of conditional statements and loops in Python. Provide examples of an `if-else` statement and a `for` loop.
   Conditional statements in Python allow you to execute certain code blocks based on whether a specific condition is true or false. The syntax for an if-else statement in Python is straightforward:
   # Example of if-else statement
   num = 10

   if num > 0:
    print("Positive number")
   elif num < 0:
    print("Negative number")
   else:
    print("Zero")
   # Explanation:
   The if statement checks if num is greater than 0.
   If the condition is true (num > 0), it prints "Positive number".
   If the condition is false (num <= 0), it moves to the elif (else if) statement and checks if num is less than 0.
   If num is less than 0, it prints "Negative number".
   If neither condition (num > 0 and num < 0) is true, it executes the else block and prints "Zero".

   Loops in Python are used to repeatedly execute a block of code until a specific condition is met. The for loop is typically used when you know the number of iterations in advance or when iterating over a sequence (like a list or tuple):
   # Example of a for loop
   fruits = ["apple", "banana", "cherry"]

   for fruit in fruits:
    print(fruit)
   # Explanation:
   fruits is a list containing three strings.
   The for loop iterates over each element (fruit) in the fruits list.
   During each iteration, the current element (fruit) is assigned the value of the current item in the list.
   The loop body (indented block) prints each fruit to the console.
   In this example, the for loop iterates through each item in the fruits list and prints it. You can perform various operations within a for loop, such as calculations, condition checks, or appending to other lists.

6. Functions in Python:
   - What are functions in Python, and why are they useful? Write a Python function that takes two arguments and returns their sum. Include an example of how to call this function.
   Functions in Python are defined using the def keyword and are reusable blocks of code.

   Example Function:
   # Function to add two numbers
   def add_numbers(a, b):
    return a + b

   # Calling the function
   result = add_numbers(3, 5)
   print("Sum:", result)

7. Lists and Dictionaries:
   - Describe the differences between lists and dictionaries in Python. Write a script that creates a list of numbers and a dictionary with some key-value pairs, then demonstrates basic operations on both.
   # Lists (list):
   Ordered collection of items.
   Accessed by index.
   Dictionaries (dict):

   Key-value pairs.
   Accessed by keys.
   # Example of lists and dictionaries
   # List of numbers
   numbers = [1, 2, 3, 4, 5]

   # Dictionary of person's details
   person = {
    "name": "Alice",
    "age": 30,
    "city": "Wonderland"
   }

   # Accessing list and dictionary elements
   print("List:", numbers)
   print("Dictionary:", person)
   print("Person's name:", person["name"])

8. Exception Handling:
   - What is exception handling in Python? Provide an example of how to use `try`, `except`, and `finally` blocks to handle errors in a Python script:
   Used to handle errors gracefully in Python.
   # Example of exception handling
   try:
       num = 10 / 0
   except ZeroDivisionError as e:
       print("Error:", e)
   finally:
       print("Cleanup code here")


9. Modules and Packages:
   - Explain the concepts of modules and packages in Python. How can you import and use a module in your script? Provide an example using the `math` module:
   Modules: Python files containing definitions and statements.
   Packages: Collection of related modules.
   # Example of importing and using a module
   import math

   # Calculate square root
   num = 16
   sqrt = math.sqrt(num)
   print("Square root of", num, "is", sqrt)

10. File I/O:
    - How do you read from and write to files in Python? Write a script that reads the content of a file and prints it to the console, and another script that writes a list of strings to a file.
    # Reading from a file
   with open('example.txt', 'r') as file:
      content = file.read()
      print("File Content:")
      print(content)
   # Writing to a file
      lines = ["Line 1\n", "Line 2\n", "Line 3\n"]

   with open('output.txt', 'w') as file:
       file.writelines(lines)
      print("Data written to file successfully.")

 # Reference
 - python.org     

# Submission Guidelines:
- Your answers should be well-structured, concise, and to the point.
- Provide code snippets or complete scripts where applicable.
- Cite any references or sources you use in your answers.
- Submit your completed assignment by [due date].


