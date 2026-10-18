# Day 01 — Arithmetic Operations in Python

## 📌 Overview

Welcome to Day 1 of my Python Learning Journey!

Today, I learned how to perform basic arithmetic operations using Python. These operators are essential for calculations and are widely used in programming.

## 🎯 Learning Objectives

By the end of this lesson, I can:

- Perform addition and subtraction.
- Multiply and divide numbers.
- Understand floor division.
- Calculate the remainder using the modulus operator.
- Store calculation results in variables.
- Display results using the `print()` function.

## 🧮 Arithmetic Operators

| Operator | Name | Description | Example | Output |
|---|---|---|---|---:|
| `+` | Addition | Adds two numbers | `35 + 56` | `91` |
| `-` | Subtraction | Subtracts the second number from the first | `65 - 34` | `31` |
| `*` | Multiplication | Multiplies two numbers | `23 * 56` | `1288` |
| `/` | Division | Performs division and returns a float | `25 / 5` | `5.0` |
| `//` | Floor Division | Rounds the quotient down to an integer for these positive operands | `26 // 5` | `5` |
| `%` | Modulus | Returns the remainder | `26 % 5` | `1` |

## 💻 Python Code

The following program demonstrates all six arithmetic operations.

```python
# DAY 1: Arithmetic Operations

# 1. Addition
a = 35 + 56
print(a)

# 2. Subtraction
b = 65 - 34
print(b)

# 3. Multiplication
c = 23 * 56
print(c)

# 4. Division
d = 25 / 5
print(d)

# 5. Floor Division
e = 26 // 5
print(e)

# 6. Modulus (remainder)
f = 26 % 5
print(f)
```

## 📤 Expected Output

```text
91
31
1288
5.0
5
1
```

## 🔍 Understanding the Code

### 1. Variables

A variable stores a value so that it can be reused.

```python
a = 35 + 56
```

Python calculates `35 + 56` and stores the result, `91`, in the variable `a`.

### 2. The `print()` Function

```python
print(a)
```

The `print()` function displays the value stored in `a` in the terminal.

### 3. Division vs. Floor Division

```python
print(25 / 5)   # 5.0
print(26 // 5)  # 5
```

- `/` performs regular division and returns a floating-point result.
- `//` performs floor division. For positive numbers, it removes the fractional part by rounding down.

### 4. Understanding Modulus

```python
print(26 % 5)  # 1
```

When 26 is divided by 5, the quotient is 5 and the remainder is 1. Therefore, the modulus operator returns `1`.

## 🧠 Key Takeaways

- Variables store values.
- Python uses arithmetic operators to perform calculations.
- `print()` displays results.
- `/` and `//` behave differently.
- `%` returns the remainder after division.

## 🏋️ Practice Exercises

Try these exercises to improve your understanding:

1. Add `45` and `78`.
2. Subtract `25` from `100`.
3. Multiply `12` by `15`.
4. Divide `45` by `6`.
5. Find the result of `45 // 6`.
6. Find the remainder of `45 % 6`.

**Challenge:** Predict the output before running each expression.

## 📁 File Information

- **Python file:** `day1_arithmetic.py`
- **Topic:** Arithmetic Operations
- **Level:** Beginner
- **Language:** Python 3

---

*Day 1 complete — building a strong foundation, one concept at a time!* 🐍
