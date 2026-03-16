# 🐍 Python Programming Project

## 📌 Overview
This project was completed as part of a **Data Technician Bootcamp** and focuses on learning the fundamentals of **Python programming**. The exercises demonstrate how Python can be used to build logical programs, perform calculations, and interact with users through simple console-based applications.

Throughout the project, core programming concepts were applied to solve practical problems and build small interactive programs such as number calculations, logic challenges, and user-input driven applications.

---

## 🎯 Project Objective

The objective of this project was to develop fundamental programming skills including:

- Writing structured Python programs
- Handling user input and output
- Building logical workflows
- Performing calculations and data processing

These skills provide the **foundation for more advanced programming, data analysis, and automation tasks**.

---

## 🛠️ Skills Demonstrated

- 🧮 Using **variables** to store and manipulate data
- 💬 Using **print()** to display information to users
- ⌨️ Using **input()** to collect user input
- 🔄 **Type casting** (converting data types such as strings to integers)
- ⚖️ Using **if / elif / else statements** for decision making
- 🔁 Implementing **for loops** to iterate through sequences
- 🔄 Using **while loops** for repeated program execution
- 🧠 Building program logic and solving computational problems

---

## 💻 Core Python Concepts

### Variables
Variables were used to store values and make programs dynamic.

```python
name = "Alex"
age = 25
```

---

### User Interaction with `print()` and `input()`

Programs interact with users by requesting input and displaying results.

```python
name = input("Enter your name: ")
print("Hello", name)
```

This allows programs to **collect user data and respond dynamically**.

---

### Type Casting

User input is typically stored as text, so type casting is needed for calculations.

```python
num1 = int(input("Enter first number: "))
num2 = int(input("Enter second number: "))

total = num1 + num2
print("The sum is:", total)
```

---

### Conditional Statements (`if`)

Conditional logic enables programs to make decisions.

```python
number = int(input("Enter a number: "))

if number % 2 == 0:
    print("The number is even")
else:
    print("The number is odd")
```

---

### Loops

Loops are used to repeat tasks efficiently.

#### For Loop

```python
for i in range(1, 11):
    print(i)
```

#### While Loop

```python
count = 1

while count <= 5:
    print(count)
    count += 1
```

---

## 🔢 Example Program: FizzBuzz

One of the exercises involved solving the classic **FizzBuzz programming challenge**, which demonstrates loops and conditional logic.

```python
for i in range(1, 101):

    if i % 3 == 0 and i % 5 == 0:
        print("fizzbuzz")

    elif i % 3 == 0:
        print("fizz")

    elif i % 5 == 0:
        print("buzz")

    else:
        print(i)
```

This exercise demonstrates how Python can combine **loops and conditional statements to implement logical rules**.

---

## 📊 Example Programs Created

The project includes several small Python programs such as:

- Printing **Hello World**
- Calculating the **sum of numbers**
- Converting **temperature units**
- Checking if a number is **even or odd**
- Finding **maximum and minimum values in lists**
- Checking if a number is **positive, negative, or zero**
- Creating logic-based challenges like **FizzBuzz**
- Building simple **user-interactive programs**

These exercises help develop **problem-solving skills and programming logic**.

---

## 🧰 Tools Used

- 🐍 **Python**
- 📓 **Google Colab**
- 💻 **Jupyter-style notebooks**

---

