# Google IT Automation with Python  
## Course 1 – Module 2: Python Syntax, Variables, Functions, and Conditionals

---

## Overview
This module builds foundational Python skills for automation by covering syntax, semantics, variables, type conversion, functions, built-in methods, comparison/logical operators, and conditionals (`if`, `elif`, `else`).  
These skills are directly applicable in DevOps for scripting, automation workflows, log analysis, and configuration management.

---

## Key Concepts

### 1. Python Syntax & Semantics
- **Syntax**: Structure and rules of writing Python code (like grammar).
- **Semantics**: The meaning/logic behind correctly written syntax.
- **Naming conventions**:
  - Use `snake_case` for variables/functions.
  - Cannot start with numbers or contain spaces.
  - Descriptive names preferred.

### 2. Variables & Data Types
- **Variables**: Store values that can change during execution.
- Common types:
  - `str` (string), `int` (integer), `float` (decimal), `bool` (True/False)
- **Type annotations**: Optional hints (`age: int = 25`)
- **Dynamic typing**: Variables can change type at runtime.
- **Duck typing**: Python checks behavior, not declared type.

### 3. Type Conversion
- **Implicit**: Python automatically converts (`int` → `float` if needed).
- **Explicit**: Manual conversion using functions like:
  - `str()` → to string
  - `int()` → to integer
  - `float()` → to float

### 4. Expressions & Operators
- Arithmetic: `+`, `-`, `*`, `/`, `//`, `%`, `**`
- Comparison: `==`, `!=`, `<`, `<=`, `>`, `>=`
- String comparisons follow Unicode order.

### 5. Functions
- Defined using `def` keyword.
- Can have parameters and return values.
- **Built-in functions**: `print()`, `type()`, `sorted()`, `max()`, `min()`
- Code reuse via functions improves maintainability and reduces duplication.

### 6. Code Style & Readability
- Follow **PEP 8** guidelines.
- Use comments `#` for clarity.
- Refactor duplicate code into reusable functions.

### 7. Comparison Operators
- Used for numeric and string evaluation.
- Return Boolean (`True`/`False`).

Example:
```python
print(10 > 5)  # True
print("apple" < "banana")  # True (alphabetical)
