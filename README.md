# Python Interview Questions And Answers

Most targeted up-to-date Python interview questions and answers list

## Table of Contents

1. [How do you print "Hello, World!" in Python?](#1-how-do-you-print-hello-world-in-python)
2. [How do you declare and initialize a variable in Python?](#2-how-do-you-declare-and-initialize-a-variable-in-python)
3. [How do you define a function in Python?](#3-how-do-you-define-a-function-in-python)
4. [How do you create a class in Python?](#4-how-do-you-create-a-class-in-python)
5. [How do you iterate through a list in Python?](#5-how-do-you-iterate-through-a-list-in-python)
6. [How do you handle exceptions in Python?](#6-how-do-you-handle-exceptions-in-python)
7. [How do you read from a file in Python?](#7-how-do-you-read-from-a-file-in-python)
8. [How do you write to a file in Python?](#8-how-do-you-write-to-a-file-in-python)
9. [How do you work with dictionaries in Python?](#9-how-do-you-work-with-dictionaries-in-python)
10. [How do you sort a list in Python?](#10-how-do-you-sort-a-list-in-python)
11. [How do you work with modules in Python?](#11-how-do-you-work-with-modules-in-python)
12. [How do you handle JSON data in Python?](#12-how-do-you-handle-json-data-in-python)
- [Whats more?](#whats-more)
- [Contributing](#contributing)
- [License](#license)

## 1. How do you print "Hello, World!" in Python?

Answer:

```python
print("Hello, World!")
```

## 2. How do you declare and initialize a variable in Python?

Answer:

```python
name = "John Doe"
age = 25
```

## 3. How do you define a function in Python?

Answer:

```python
def greet():
    print("Hello!")
```

## 4. How do you create a class in Python?

Answer:

```python
class MyClass:
    def __init__(self, name):
        self.name = name

    def greet(self):
        print(f"Hello, {self.name}!")
```

## 5. How do you iterate through a list in Python?

Answer:

```python
my_list = [1, 2, 3, 4, 5]

for item in my_list:
    print(item)
```

## 6. How do you handle exceptions in Python?

Answer:

```python
try:
    # Code that may raise an exception
    result = 10 / 0
except ZeroDivisionError:
    print("Cannot divide by zero!")
```

## 7. How do you read from a file in Python?

Answer:

```python
with open("file.txt", "r") as file:
    content = file.read()
    print(content)
```

## 8. How do you write to a file in Python?

Answer:

```python
with open("file.txt", "w") as file:
    file.write("Hello, World!")
```

## 9. How do you work with dictionaries in Python?

Answer:

```python
my_dict = {"name": "John", "age": 25}

# Accessing values
print(my_dict["name"])

# Iterating through key-value pairs
for key, value in my_dict.items():
    print(f"{key}: {value}")
```

## 10. How do you sort a list in Python?

Answer:

```python
my_list = [3, 1, 4, 2, 5]
sorted_list = sorted(my_list)
print(sorted_list)
```

## 11. How do you work with modules in Python?

Answer:

```python
# Importing a module
import math

# Using functions from the module
square_root = math.sqrt(25)
print(square_root)
```

## 12. How do you handle JSON data in Python?

Answer:

```python
import json

# Converting JSON to Python object
json_data = '{"name": "John", "age": 25}'
python_data = json.loads(json_data)
print(python_data)

# Converting Python object to JSON
python_data = {"name": "John", "age": 25}
json_data = json.dumps(python_data)
print(json_data)
```

## What's more?
<a href="https://interviewplus.ai/developers-and-programmers/python/questions">A comprehensive list of questions and answers</a>

## Contributing
We welcome contributions from our users to help make this resource as comprehensive and useful as possible. If you have been recently interviewed and encountered a question that is not currently covered on our website, feel free to suggest it as a new question. Your contributions will be added to our platform, and we will make sure to credit you for your contributions. We appreciate your help in making our platform a valuable tool for all job seekers.

## License
MIT License
