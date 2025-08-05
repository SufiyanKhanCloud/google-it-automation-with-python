
# 📘 Module 3 Notes — Google IT Automation with Python

## Using Python to Interact with the Operating System

---

## 🔁 1. While Loops

* A `while` loop executes a block of code **repeatedly as long as a given condition is true**.
* The condition is **evaluated before** each iteration.
* It's essential to update the variable involved in the condition to avoid infinite loops.

### 📌 Example:

```python
x = 0
while x < 5:
    print("Not there yet, x=" + str(x))
    x = x + 1
print("x=" + str(x))
```

---

## 🔂 2. Infinite Loops

* If the condition in a `while` loop never becomes `False`, the loop will run forever.
* Always make sure to update the variable involved in the condition.

### 📌 Example:

```python
while True:
    print("Looping endlessly")
```

> Use `Ctrl + C` to stop execution in such cases.

---

## 📛 3. Break and Continue

* **`break`**: Immediately exits the current loop.
* **`continue`**: Skips the current iteration and continues with the next.

### 📌 Example:

```python
for x in range(10):
    if x % 2 == 0:
        continue
    print(x)
```

> Prints only odd numbers.

---

## 🔁 4. For Loops

* Used to iterate over a sequence (like a list, tuple, or string).

### 📌 Example:

```python
for letter in "Python":
    print(letter)
```

---

## 📏 5. Ranges and Iterables

* `range()` generates a sequence of numbers.

### Syntax:

```python
range(start, stop, step)
```

### 📌 Example:

```python
for i in range(1, 10, 2):
    print(i)
```

---

## ⛓️ 6. Nested Loops

* A loop inside another loop.
* Useful for working with 2D structures like matrices.

### 📌 Example:

```python
for x in range(1, 3):
    for y in range(3, 0, -1):
        print(x, y)
```

---

## 🧰 7. Practice Problem: Descending Sequences

### 📌 Function Example:

```python
def sequence(high, low):
    for x in range(high, low - 1, -1):
        print(x)
    for x in range(high, low - 1, -1):
        print(x)
```

---

## 🔗 8. Combining Loops and Conditionals

* You can combine `for` or `while` loops with `if`, `break`, and `continue` to build complex logic.

---

## 📊 9. Recap

* Use `while` for unknown iteration counts, `for` for definite sequences.
* Don't forget to **avoid infinite loops**.
* Use `break`/`continue` for control.
* Practice by creating small programs!
