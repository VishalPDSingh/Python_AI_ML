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
