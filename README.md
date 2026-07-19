# 🐍 Python 101: Basic Programming Learning Pathway

คลังเก็บเนื้อหาและแบบฝึกหัดสำหรับการเริ่มต้นเรียนรู้ภาษา **Python** โดยเน้นการสร้างพื้นฐานด้าน **Logical Thinking**, **Programming Fundamentals** และ **Input–Process–Output (IPO)** ผ่านการใช้งาน **Jupyter Notebook**

---

## 📋 Course Overview

| Item | Description |
|------|-------------|
| **Course** | Python 101 |
| **Level** | Beginner |
| **Platform** | Jupyter Notebook / Google Colab |
| **Learning Style** | Hands-on Learning |
| **Goal** | Understand the fundamentals of Python programming using the IPO concept |

---

# 🚀 Learning Pathway

## 📅 Week 1–2 : Variables, Data Types, Input & Output

### 🎯 Learning Objectives

After completing this lesson, students will be able to:

- Understand variables and memory concepts
- Store data using variables
- Receive user input using `input()`
- Display output using `print()`
- Convert data types using Type Casting
- Design simple programs using the IPO model

---

# 📖 1. Variables

A **Variable** is a named storage location used to store data in memory.

```python
name = "Alice"
age = 20
height = 165.5
```

## Variable Naming Rules

✅ Valid

```python
student_name
_total
price1
```

❌ Invalid

```python
2name
student name
```

Python is **Case Sensitive**

```python
age
Age
AGE
```

These are **three different variables**.

### 💡 Best Practice

Use **snake_case**

```python
student_name
item_price
total_score
```

---

# 📖 2. Data Types

Everything in Python is an **Object**.

Each object has

- Identity
- Value
- Type

## Primitive Data Types

| Type | Description | Example |
|------|-------------|---------|
| `int` | Integer | `25` |
| `float` | Floating Point | `19.99` |
| `bool` | Boolean | `True` |
| `str` | String | `"Python"` |

Example

```python
x = 10
y = 2.5
status = True
name = "John"
```

Check data type

```python
type(x)
```

---

# 📖 3. Type Casting

Python provides built-in functions to convert data types.

```python
int()
float()
str()
bool()
```

Example

```python
age = "20"

age = int(age)

print(age + 5)
```

Convert number to string

```python
score = 95

print("Score = " + str(score))
```

---

# 📖 4. Input & Output

## User Input

```python
name = input("Enter your name : ")
```

> **Note:** `input()` always returns a **String**

If you need an integer

```python
age = int(input("Age : "))
```

---

## Output

Display data using

```python
print()
```

Example

```python
print("Hello Python")
```

---

# 📖 5. String Formatting

## Traditional Formatting

```python
name = "John"
age = 20

print("Name = %s" % name)
print("Age = %d" % age)
```

---

## f-String (Recommended)

```python
name = "John"
age = 20

print(f"Name = {name}")
print(f"Age = {age}")
```

### Advantages

- Easy to read
- Faster
- Modern Python standard

---

# 📖 6. IPO Concept

Programming follows three simple steps.

```text
Input
   │
   ▼
Process
   │
   ▼
Output
```

Example

```python
width = float(input("Width : "))
height = float(input("Height : "))

area = width * height

print(area)
```

### IPO Analysis

| Step | Description |
|------|-------------|
| **Input** | Width, Height |
| **Process** | Area = Width × Height |
| **Output** | Area |

---

# 🛠 Practice Exercises

## Exercise 1 — Rectangle Area

Calculate the area of a rectangle.

```text
Area = Width × Height
```

---

## Exercise 2 — Temperature Converter

Convert between

- Celsius
- Fahrenheit
- Kelvin

---

## Exercise 3 — Mass Conversion

Convert

- Stone
- Pound
- Ounce

to

```text
Kilogram
```

---

## Exercise 4 — BMI Calculator

Calculate Body Mass Index

```text
BMI = Weight / Height²
```

---

## Exercise 5 — Simple Interest

Calculate

```text
Interest = P × R × T
```

---

# 💻 Recommended Tools

## Google Colab

- No installation required
- Runs directly in a web browser
- Perfect for beginners

👉 https://colab.research.google.com

---

## Jupyter Notebook

- Local development
- Interactive programming
- Supports Markdown + Python in one notebook

👉 https://jupyter.org

---

# 🎯 Learning Outcomes

At the end of this lesson, students will be able to

- ✅ Create variables correctly
- ✅ Select appropriate data types
- ✅ Receive user input
- ✅ Display output
- ✅ Perform type conversion
- ✅ Use f-strings
- ✅ Apply the IPO concept
- ✅ Solve basic programming problems

---

# 📁 Repository Structure

```text
Python101/
│
├── README.md
│
├── Week01_Variables.ipynb
├── Week02_Input_Output.ipynb
│
├── Exercises/
│   ├── Rectangle.ipynb
│   ├── Temperature.ipynb
│   ├── MassConversion.ipynb
│   ├── BMI.ipynb
│   └── Interest.ipynb
│
├── Images/
├── Dataset/
└── Resources/
```

---

## ⭐ Course Topics

- Variables
- Data Types
- Type Casting
- Input & Output
- String Formatting
- IPO Model
- Basic Mathematical Programming
- Hands-on Exercises

---

## 📚 Recommended Environment

- Python 3.12+
- Google Colab
- Jupyter Notebook
- Visual Studio Code (Optional)

---

## 📄 License

This repository is intended for educational purposes.

---

<p align="center">

**Python 101 — Learn Python from Zero to Programming Fundamentals**

Created with ❤️ by **Pikul-CMU**

</p>


