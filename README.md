# Day-5-Number-Sign-Checker
Day 5/100 - Python Program to Check Whether a Number is Positive or Negative

# Positive, Negative, or Zero
A program to determine the sign of a user-inputted number using basic conditional statements.

## 📝 Description

This program evaluates a numerical input to classify it into one of three categories: positive, negative, or zero. It utilizes a simple `if-elif-else` control flow structure and converts the input to a floating-point number, allowing it to handle both whole numbers and decimals accurately.

---

## 🎯 Problem Statement

### Input:

* A single numerical value (can be an integer or a decimal/float).

### Output:

* A string stating: "Positive number", "Negative number", or "Zero".

### Rules:

1. The program must accept a numerical input from the user.
2. If the number is strictly greater than 0, output **"Positive number"**.
3. If the number is strictly less than 0, output **"Negative number"**.
4. If the number is exactly 0, output **"Zero"**.
5. The program should be able to handle decimal values (e.g., `3.14` or `-0.5`).

---

## 💡 Examples

### Example 1

**Input:**

```
15.5

```

**Output:**

```
Positive number

```

**Explanation:** The input `15.5` is greater than 0, so the first condition (`num > 0`) is met.

### Example 2

**Input:**

```
-7

```

**Output:**

```
Negative number

```

**Explanation:** The input `-7` is less than 0, triggering the `elif` condition (`num < 0`).

### Example 3

**Input:**

```
0

```

**Output:**

```
Zero

```

**Explanation:** The input is exactly `0`, meaning it is neither greater than nor less than 0, so it falls through to the `else` block.

---

## 🚀 How to Use

1. **Clone this repository** (or save the script)
```bash
git clone https://github.com/adiaryaz/Day-5-Number-Sign-Checker.git
cd number-sign-checker

```


2. **Run the program**:
```bash
python main.py

```


Enter a number when prompted by "Enter a number: " to see its classification.
