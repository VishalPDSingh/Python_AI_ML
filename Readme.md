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

# 🐍✨ Python Variable Names — Rules & Styles (With Examples)

A clean and stylish README explaining **variable naming rules** and **multi-word naming styles** in Python.

---

# 📌 Variable Names in Python

A variable can have a short name like `x`, `y` or a descriptive name like `age`, `car_name`, or `total_volume`.

## ✅ Rules for Python Variable Names

Below are the official rules you must follow:

### 🔹 1. Must start with a **letter** or **underscore** (`_`)

✔ Valid:

```python
name = "Vishal"
_age = 21
```

❌ Invalid:

```python
1name = "wrong"  # cannot start with number
```

### 🔹 2. Cannot start with a **number**

```python
99value = 10   # ❌ invalid
value99 = 10   # ✔ valid
```

### 🔹 3. Can contain **letters, numbers, and underscores** only

```python
first_name = "Vishal"   # ✔ valid
first-name = "no"       # ❌ invalid
first name = "no"       # ❌ invalid
```

### 🔹 4. Variable names are **case-sensitive**

```python
age = 22
Age = 30
AGE = 40
print(age, Age, AGE)  # all are different
```

### 🔹 5. Cannot use **Python keywords**

Examples of keywords: `class`, `while`, `for`, `return`, `lambda`, etc.

❌ Invalid:

```python
class = "test"   # cannot use keyword
```

✔ Valid alternative:

```python
class_name = "test"
```

---

# ⚠️ Remember

✔ Variable names are **case-sensitive**
✔ Use descriptive names for clean, readable code
✔ Avoid using Python keywords as variable names

---

# 🧩 Multi-Word Variable Naming Styles

When variable names have more than one word, readability becomes important.
Python supports multiple naming conventions.

---

## 🐪 Camel Case

Each word **except the first** starts with a capital letter.

### ✅ Example:

```python
myVariableName = "Vishal"
totalVolumeCount = 120
```

---

## 🏛️ Pascal Case

**Each word** starts with a capital letter.

### ✅ Example:

```python
MyVariableName = "Python"
TotalVolumeCount = 120
```

Pascal Case is usually used for **Class Names** in Python.

---

## 🐍 Snake Case (Most Common in Python)

Words are separated using an underscore `_`.

### ✅ Example:

```python
my_variable_name = "Vishal"
total_volume_count = 120
```

Snake case is the **official Python convention (PEP-8)** for variable names.

---

# 🎉 Summary

* Python variable names follow strict rules (letters, underscores, case-sensitive, no keywords).
* Multi-word names can be written using **camelCase**, **PascalCase**, or **snake_case**.
* **snake_case** is the recommended style for Python projects.

✨ This README is perfect for GitHub documentation, Python learning modules, and beginner-friendly guides!

## 🎉 Final Tips

* Pick names that are **meaningful**, not random.
* Avoid single letters except in loops.
* Follow **snake_case** for clean Python code.



# 🐍✨ Python Keywords & Identifiers — Stylish README

This README explains **Keywords**, **Identifiers**, and **Compilation vs Interpretation** in Python with emojis and clean examples. Copy & paste into your GitHub repo! 🚀

---

# 🔑 Python Keywords

Python **keywords** are special reserved words that Python uses for its syntax. You **cannot** use them as variable names.

### 🧠 Examples:

```
False   True   None
if      else   elif
for     while  break
class   def    return
try     except finally
import  from   as
```

### ❌ Wrong Usage

```python
if = 10        # ❌ ERROR: 'if' is a keyword
class = "A"    # ❌ ERROR
```

### ✔️ Correct Usage

```python
value = 10          # 👍 works
class_name = "A"    # 👍 identifier, not keyword
```

---

# 🆔 Python Identifiers

Identifiers are **names** for variables, functions, classes, modules, etc.

### 📜 Rules for Python Identifiers:

* ✔️ Must start with a **letter** or **underscore**
* ❌ Cannot start with a **number**
* ✔️ Can include **A–Z**, **a–z**, **0–9**, and **_**
* ⚠️ **Case-sensitive** (age ≠ Age ≠ AGE)
* ❌ Cannot use **keywords** as names

### ✔️ Valid Examples

```python
name = "Vishal"
_age = 21
total_1 = 450
CarName = "BMW"
```

### ❌ Invalid Examples

```python
1age = 10         # starts with number ❌
my-name = 20      # hyphen not allowed ❌
for = 50          # keyword ❌
```

---

# ⚙️ Compilation vs Interpretation

## 💻 Compilation

Compilation converts entire code → **machine (binary) code** *before* execution.

Examples: C, C++, Java

### ✔️ Pros

* Faster execution
* Errors detected before running

### Diagram

```
source_code.c → Compiler → Machine Code
```

---

## 🐍 Interpretation (Python)

Python is an **interpreted** language.

➡️ Executes code **line by line**
➡️ Stops immediately when an error occurs
➡️ Easier for debugging

### Example:

```python
print("Hello")
a = 10
b = 0
print(a / b)   # ❌ error here, interpreter stops
```

### Diagram

```
Python Code → Interpreter → Output (line-by-line)
```

---

# 🎯 Summary

| Topic                 | Description                                 |
| --------------------- | ------------------------------------------- |
| 🔑 **Keywords**       | Reserved words in Python                    |
| 🆔 **Identifiers**    | Names for variables, functions, classes     |
| 💻 **Compilation**    | Converts whole code before running          |
| 🐍 **Interpretation** | Executes line-by-line (Python follows this) |

---

# 🧑‍💻📥 Python User Input — Stylish README

Learn how to take **user input** in Python using the `input()` function, with easy examples and explanations. Perfect for beginners! 🚀🐍

---

# 📌 What Is User Input?

User input means taking data **from the user** during program execution.

Python uses the **`input()`** function to accept data from the keyboard.

```
input(prompt)
```

* `prompt` = message displayed to user
* Always returns **string** by default

---

# 📝 Basic Example

```python
name = input("Enter your name: ")
print("Hello", name)
```

### 🖥️ Output:

```
Enter your name: Vishal
Hello Vishal
```

---

# 🔢 Taking Numeric Input

`input()` always returns **string**, so convert using:

* `int()` → for integers
* `float()` → for decimals

### ▶ Integer Input

```python
age = int(input("Enter your age: "))
print("Your age is", age)
```

### ▶ Float Input

```python
marks = float(input("Enter your marks: "))
print("Marks:", marks)
```

---

# ➕ Using Input in Calculations

```python
a = int(input("Enter first number: "))
b = int(input("Enter second number: "))
print("Sum is:", a + b)
```

### 🖥️ Output

```
Enter first number: 5
Enter second number: 7
Sum is: 12
```

---

# 📤 Multiple Inputs in One Line

Python allows multiple inputs using `split()`.

```python
a, b = input("Enter two numbers: ").split()
print(a, b)
```

### 🎯 With Type Conversion

```python
a, b = map(int, input("Enter two numbers: ").split())
print(a + b)
```

---

# 🎭 Example: User Input in Real Program

```python
name = input("Enter your name: ")
age = int(input("Enter your age: "))
city = input("Enter your city: ")

print("\n--- User Details ---")
print("Name:", name)
print("Age:", age)
print("City:", city)
```

---

# 🧠 Tips

✔ `input()` always gives **string**
✔ Convert to `int` or `float` when needed
✔ Use `split()` for multiple inputs
✔ Use `map()` for converting multiple values at once

---

# 🎉 Summary Table

| Feature         | Description              | Example                  |
| --------------- | ------------------------ | ------------------------ |
| Basic input     | Takes user text          | `name = input()`         |
| Convert to int  | Numeric input            | `age = int(input())`     |
| Multiple inputs | Split values             | `a, b = input().split()` |
| Map conversion  | Convert multiple numbers | `map(int, ...)`          |

---

# 🔄✨ Python Type Conversion — Stylish README

Learn **Type Conversion**, **Implicit vs Explicit Casting**, and examples with emojis to make it fun and GitHub-ready! 🐍🚀

---

# 🔄 What is Type Conversion?

Type conversion means converting one data type into another.
Python supports:

* **Implicit Conversion** (done automatically)
* **Explicit Conversion** (done manually by programmer)

---

# 🤖 1. Implicit Type Conversion

Python automatically converts one type to another **without losing data**.
This happens when mixing different numeric types.

### 📝 Example

```python
print(45 + 63.36)
print(type(5), type(56.5))
```

### 👉 Output

```
108.36
<class 'int'> <class 'float'>
```

### 💡 Why?

Python converts `45` (int) → `45.0` (float) to avoid data loss.

---

# ❌ Invalid Implicit Conversion

Python cannot automatically convert **string to number**.

### Example (ERROR)

```python
# print(4 + 'vishal')
# print(type(4), type('vishal'))
```

This throws:

```
TypeError: unsupported operand types
```

---

# 🧑‍💻 2. Explicit Type Conversion (Type Casting)

You manually convert values using functions like:

* `int()` → convert to integer
* `float()` → convert to decimal
* `str()` → convert to string

---

# 🔢 Convert String → Integer

```python
num = int('4')
print(num)
print(type(num))
```

### Output

```
4
<class 'int'>
```

---

# ⚠️ Not Possible with Complex Numbers

You cannot convert a complex number into int.

```python
# int(3 + 5j)   # ❌ ERROR
```

This gives:

```
TypeError: can't convert complex to int
```

---

# 🔁 Convert Float → Integer

Converts by **removing decimal part**.

```python
value = int(45.6)
print(value)
```

### Output

```
45
```

---

# 🔤 Convert Number → String

```python
s = str(5)
print(s)
print(type(s))
```

### Output

```
5
<class 'str'>
```

---

# 🧠 Summary Table

| Conversion Type | Description                   | Example          |
| --------------- | ----------------------------- | ---------------- |
| Implicit        | Auto conversion (int → float) | `45 + 63.36`     |
| Explicit        | Manual conversion             | `int('4')`       |
| Float → Int     | Decimal removed               | `int(45.6)`      |
| Number → String | Number becomes text           | `str(5)`         |
| Invalid         | String + int                  | `4 + 'vishal'` ❌ |

---

# 🔥🐍 Python Literals — Stylish README with Examples

Literals are the **fixed values** used directly in Python code. This README explains all types of Python literals with clear examples and emojis. 🚀

---

# 📌 What Are Literals?

A **literal** is a raw value assigned to a variable.

Example:

```python
x = 10      # 10 is a literal
name = "Vishal"  # "Vishal" is a literal
```

Python supports:

* **Numeric Literals** (Binary, Octal, Decimal, Hexadecimal, Float, Complex)
* **String Literals**
* **Boolean Literals**
* **Special Literal (`None`)**

---

# 🔢 Numeric Literals

## ✔ Binary Literal

```python
a = 0b1010
print(a)
```

### Output:

```
10
```

## ✔ Decimal Literal (default)

```python
b = 100
```

## ✔ Octal Literal

```python
c = 0o3212
print(c)
```

## ✔ Hexadecimal Literal

```python
d = 0x12c
print(d)
```

---

# 🌊 Floating-Point Literals

```python
f1 = 12.5
f2 = 1.5e2     # 1.5 × 10² = 150
f3 = 1.4e-3    # 1.4 × 10⁻³ = 0.0014
```

---

# ⚛ Complex Literals

Complex numbers have two parts:

* **real part**
* **imaginary part** (with `j`)

```python
x = 3 + 4j
y = 45j
print(x.real)  # real part
print(x.imag)  # imaginary part
```

### Output:

```
3.0
4.0
```

---

# 📝 String Literals

Python supports multiple types of string literals:

## ✔ Single Quotes

```python
string = 'This is python'
```

## ✔ Double Quotes

```python
Strings = "Welcome"
```

## ✔ Triple Quotes (Multiline)

```python
multiple_str = """This is multiple string"""
```

## ✔ Raw String

Used to ignore escape characters (`\n`, `\t`).

```python
raw_str = r"C:\\python\\folder"
```

## ✔ Unicode String

```python
unicode = u"Hello Python"
```

---

# 🔁 Boolean Literals

`True` and `False` are boolean values.
Python treats them as **1** and **0** when used in math.

```python
a = True + 4
b = False + 56
print("a:", a)
print("b:", b)
```

### Output:

```
a: 5
b: 56
```

---

# 🟣 Special Literal — `None`

Represents **no value** or **empty value**.

```python
x = None
print(x)
```

### Output:

```
None
```

---

# 🎯 Summary Table

| Literal Type | Example   | Description         |
| ------------ | --------- | ------------------- |
| Binary       | `0b1010`  | Base-2 number       |
| Octal        | `0o3212`  | Base-8 number       |
| Hexadecimal  | `0x12c`   | Base-16 number      |
| Float        | `1.5e2`   | Scientific notation |
| Complex      | `3+4j`    | Real + imaginary    |
| String       | `'Hello'` | Text data           |
| Boolean      | `True`    | Evaluates to 1 or 0 |
| Special      | `None`    | No value            |

---





