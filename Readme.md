# Python for AI & Machine Learning


---

## 🚀 What is Python?

Python is a powerful, high-level programming language created by **Guido van Rossum** and released in **1991**. It is widely used because of its simplicity, readability, and versatility.

### 💡 Python is commonly used for:

* Web development (server-side)
* Software development
* Artificial Intelligence & Machine Learning
* Data Analysis & Big Data
* Automation and system scripting
* Mathematics & scientific computing

---

## 🧠 What Can Python Do?

* Build server-side web applications
* Automate workflows and tasks
* Connect to databases and manage files
* Handle large datasets and perform complex mathematical operations
* Rapidly prototype ideas
* Develop production-ready applications

---

## 🌟 Why Python for AI & ML?

* Works on all major platforms (Windows, macOS, Linux, Raspberry Pi)
* Clean and English-like syntax makes it beginner-friendly
* Requires fewer lines of code compared to many other languages
* Runs on an interpreter → quick testing and prototyping
* Supports procedural, object-oriented, and functional programming styles

---

## 📘 Good to Know

* The latest major version is **Python 3** — recommended for modern development
* You can write Python in simple text editors or IDEs like:

  * **VS Code**
  * **PyCharm**
  * **Thonny**
  * **Eclipse** (with plugins)

---

## 🧩 Python Syntax vs Other Languages

Python is designed for readability.

### Key Differences:

* Uses **new lines** to complete commands instead of semicolons
* Uses **indentation** (whitespace) to define scope instead of curly braces
* Syntax is cleaner and influenced by mathematical structure

Example:

```python
def greet():
    print("Hello, Python!")
```

---

## 📈 Why Learn Python for AI & ML?

Python has become the #1 choice for machine learning because:

* Excellent libraries: **NumPy, Pandas, Scikit-learn, TensorFlow, PyTorch**
* Strong community support
* Easy to integrate with data and AI workflows

---

## 🎯 Goal of This Repository

This repository will help you learn Python step-by-step for building skills in **AI**, **ML**, and **automation**.

---

## 🖨️ Python Output / The `print()` Function

The `print()` function is used to display output on the screen. It can show text, numbers, booleans, variables, and results.

### ✔️ What is `print()`?

`print()` is a built-in Python function that outputs data to the console.

Example:

```python
print("Hello World")
```

Output:

```
Hello World
```

### 🧵 Python is Case-Sensitive

Python treats:

* `print`
* `Print`
* `PRINT`

as different. Only lowercase **print** works.

---

## 📌 Basic Usage

### 1️⃣ Printing Strings

```python
print("Hello World")
print('Hello World')
```

### 2️⃣ Printing Numbers

```python
print(7)
print(45.56)
```

### 3️⃣ Printing Boolean Values

```python
print(True)
```

---

## 📑 Printing Multiple Values

```python
print("Hello", 23.55, True)
```

Output:

```
Hello 23.55 True
```

Python separates values with **spaces** by default.

---

## 🔧 Using `sep` (Separator)

`sep` defines what separates multiple printed values.

```python
print("Hello", 23.55, True, sep='/')
```

Output:

```
Hello/23.55/True
```

---

## 🔄 Line Breaks & `end`

By default, each print ends with a newline (`
`).

```python
print('hello')
print('world')
```

### Using `end` to avoid new line

```python
print('hello', end='-')
print('world')
```

Output:

```
hello-world
```

---

## 📚 Quick Summary

| Feature         | Description      | Example                  |
| --------------- | ---------------- | ------------------------ |
| `print()`       | Displays output  | `print("Hi")`            |
| Strings         | Use '' or ""     | `print("Hello")`         |
| Numbers         | No quotes needed | `print(10)`              |
| Booleans        | True/False       | `print(True)`            |
| Multiple values | Comma-separated  | `print("A", 10)`         |
| `sep`           | Custom separator | `print("A","B",sep='-')` |
| `end`           | Custom ending    | `print("Hi",end='!')`    |

---

# Python Comments

Python comments are helpful for explaining code, making programs more readable, and disabling lines during testing.

---

## 🔹 What Are Python Comments?

Comments are lines in the code that Python **ignores** during execution. They are meant for humans to understand the code better.

### ✔ Uses of Comments

* Explain Python code
* Make code more readable
* Prevent execution of code (useful in testing)

---

## 🔹 Single-Line Comments

Single-line comments start with the `#` symbol.

### **Example:**

```python
# This is a single-line comment
print("Hello, World!")  # This comment is placed at the end of a line
```

---

## 🔹 Using Comments to Disable Code

You can comment out a line of code if you want Python to ignore it.

### **Example:**

```python
#print("This line will not run")
print("This line will run")
```

---

## 🔹 Multi-line Comments

Python does not have a dedicated multiline comment syntax. But you can use either multiple `#` symbols or triple-quoted strings.

### **Method 1: Using `#` on each line**

```python
# This is a multiline comment
# written using the hash symbol
# on each line
```

### **Method 2: Using Multiline String (Triple Quotes)**

Python ignores a string literal if it is not assigned to a variable.

```python
"""
This is a multiline comment.
Python will ignore this string because
it is not assigned to any variable.
"""

print("Program continues...")
```

---

## ✔ Summary

* Use `#` for single-line comments
* Use `#` repeatedly or triple quotes for multiline comments
* Comments help document your code and improve readability

---

# 🐍 Python Data Types

Python provides a rich set of **built‑in data types**, and understanding them is essential for writing efficient and clean code.

---

## 🔸 What Are Data Types?

In programming, a **data type** defines the type of value a variable can store. Different types support different operations.

Python automatically assigns a data type when a value is assigned to a variable.

---

## 📚 Built‑in Data Types in Python

Python has the following built‑in data types:

### **📝 Text Type**

* `str`

### **🔢 Numeric Types**

* `int`
* `float`
* `complex`

### **📦 Sequence Types**

* `list`
* `tuple`
* `range`

### **🗂️ Mapping Type**

* `dict`

### **🧺 Set Types**

* `set`
* `frozenset`

### **⚡ Boolean Type**

* `bool`

### **💾 Binary Types**

* `bytes`
* `bytearray`
* `memoryview`

### **🚫 None Type**

* `NoneType`

---

## 🔍 Getting the Data Type

Use the `type()` function to check the data type of a variable:

```python
x = 10
print(type(x))   # Output: <class 'int'>
```

---

## ✍ Setting the Data Type

Python automatically sets the data type when you assign a value:

```python
x = "Hello World"          # str
x = 20                      # int
x = 20.5                    # float
x = 1j                      # complex
x = ["apple", "banana"]    # list
x = ("apple", "banana")    # tuple
x = range(6)                # range
x = {"name": "John"}       # dict
x = {"apple", "banana"}    # set
x = frozenset({"apple", "banana"}) # frozenset
x = True                    # bool
x = b"Hello"                # bytes
x = bytearray(5)            # bytearray
x = memoryview(bytes(5))    # memoryview
x = None                    # NoneType
```

---

## 🎉 Summary

* Python supports multiple built‑in data types.
* Data types are assigned automatically when values are stored in variables.
* Use `type()` to check the type of any object.

✨ Python handles data types dynamically, making coding easier and more flexible!

# 🐍 Python Data Types Examples

This README provides examples of different Python data types using simple `print()` statements.

---

## 🔢 Integer

Integers represent whole numbers.

```python
print(8)
print(1e309)  # Range limit demonstration (1 * 10^308)
```

---

## 💠 Decimal / Float

Floats represent decimal numbers.

```python
print(7.56)
print(1.7e309)  # Range of float
```

---

## ⚡ Boolean

Boolean values represent truth values.

```python
print(True)
print(False)
```

---

## 📝 Text / String

Strings represent text.

```python
print("Hello World")
print('Hello world')
```

---

## 🔮 Complex Number

Used for scientific and mathematical calculations.

```python
print(3+5j)
```

---

## 📦 List (Similar to Array in Java)

Lists are ordered, mutable collections.

```python
print([1,2,3,5,8,4])
```

---

## 🎯 Tuple

Tuples are ordered and immutable.

```python
print((1,5,6,87,9))
```

---

## 🧺 Set

Sets are unordered collections of unique elements.

```python
print({1,2,5,8,69,14})
```

---

## 🗂️ Dictionary

Stores data in key-value pairs.

```python
print({'name':'Vishal','Roll':102,'college':'JISCE', 'marks':89.6})
```

---

## 🎉 Summary

This README demonstrates Python's most commonly used data types with simple print examples.

# 🐍✨ Python Variables, Typing & Binding — Stylish GitHub README

A clean and stylish explanation of Python **variables**, **dynamic vs static typing**, **dynamic vs static binding**, and **Pythonic declaration techniques** — with emojis and examples.

---

# 🔤📌 Python Variables

A **variable** is a name that stores a value. In Python, you simply assign a value — no type declaration needed.

### ✅ Example:

```python
name = 'Vishal singh'  # 🧑‍💻 String
print(name)

a = 4  # 🔢 Integer
print(a)

x = 34
y = 34
print(x + y)  # ➕ Addition
```

Python automatically decides the data type based on the assigned value.

---

# 🔄🆚 Static Typing vs Dynamic Typing

## 🌀 Dynamic Typing (Python)

Python determines the variable's type **at runtime**.

* No need to declare type
* Very flexible
* The type can change anytime

### ✅ Example:

```python
a = 34        # int
a = "Vishal"  # becomes string
```

## 🔒 Static Typing (Java, C++)

Type must be declared and **cannot change**.

### Example (Java):

```java
int a = 10;  // must always be integer
```

---

# 🔗 Static Binding vs Dynamic Binding

## 🔄 Dynamic Binding (Python)

Also known as **late binding**.

* Binding of variable → value happens during execution
* Variable may change type

### Example:

```python
a = 5
print(a)   # 🔢 int

a = 'vishal'
print(a)   # 🔤 string
```

## 🔂 Static Binding (Java)

Binding happens at compile-time.

### Example (Java):

```java
int a = 5;   // type fixed
```

---

# 🎨 Stylish Python Variable Declaration Techniques

Python supports clean and expressive assignment styles.

## 1️⃣ Normal Assignment

```python
a = 12
b = 12
c = 45
print(a, b, c)
```

## 2️⃣ Multiple Assignment (Pythonic 😎)

Assign different values in a single line.

```python
a, b, c = 10, 12, 13
print(a, b, c)
```

## 3️⃣ Assign Same Value to All Variables

```python
a = b = c = 12
print(a, b, c)
```

---

# ✨ Summary

✔ Python uses **dynamic typing** → variable type can change at runtime
✔ Python uses **dynamic binding** → variable binds to value during execution
✔ No type declaration required
✔ Clean & stylish assignment options make Python beginner-friendly & powerful 🐍💙

---


