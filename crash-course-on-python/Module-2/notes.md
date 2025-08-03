# Google IT Automation with Python  
## Course 1 – Module 2: Python Syntax, Semantics & Conditionals

---

## 1. Python Syntax & Semantics

### Syntax
- Structure and rules for writing Python code.
- Includes **keywords**, **punctuation**, and **formatting**.
- Errors in syntax prevent code execution (SyntaxError).

### Semantics
- The meaning or logic behind the code.
- Even if syntax is correct, poor semantics can produce incorrect results.

> **DevOps relevance:** Clear syntax and semantics are crucial for writing automation scripts that deploy infrastructure, configure servers, or trigger CI/CD pipelines.

---

## 2. Variables, Keywords & Operators

### Variables
- Store values such as strings, numbers, lists, or objects.
- Follow **naming conventions**:
  - `snake_case` for variables/functions.
  - Cannot start with a number.
  - Avoid spaces or special symbols.

### Keywords
- Reserved words like `if`, `else`, `def`, `return`.
- Cannot be used as variable names.

### Operators
- **Arithmetic:** `+ - * / % // **`
- **Comparison:** `== != > < >= <=`
- **Logical:** `and or not`

---

## 3. Data Types & Type Conversion

### Built-in Types
- `str`, `int`, `float`, `bool`
- Use `type()` to check type.

### Type Conversion
- **Implicit:** Python converts automatically when safe.
- **Explicit:** Use `str()`, `int()`, `float()` to convert manually.

```python
room_rate = 100
tax = room_rate * 0.08
total = room_rate + tax
print("Total cost: " + str(total))
