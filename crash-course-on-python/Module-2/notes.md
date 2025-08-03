# Google IT Automation with Python
## Course 1 – Module 2: Python Syntax, Semantics, and Conditionals

---

## 1. Python Syntax & Semantics

**Syntax**: The set of rules that defines the structure of Python code (like grammar in human languages).  
**Semantics**: The meaning behind that structure (logic of the code).  

**Core Syntax Elements:**
- **Variables**: Store data (strings, integers, floats, lists, dicts, tuples, objects)
- **Keywords**: Reserved words for specific purposes (`if`, `else`, `def`, `return`, etc.)
- **Operators**: Perform operations (`==`, `<`, `>`, `%`, `//`, `/`, `**`, `+`, `-`, `*`)
- **Functions**: Reusable blocks of code
- **Expressions**: Combinations of values, variables, and operators that return a result

*DevOps Relevance*: Clean syntax and correct semantics ensure scripts for automation, deployment, and monitoring run reliably without errors.

---

## 2. Naming Rules & Conventions
- No spaces in names
- May use upper/lower case, numbers (not as first character)
- Use **snake_case** for variables/functions
- Use descriptive names (e.g., `server_status` instead of `ss`)

*DevOps Relevance*: Readable variable names help when collaborating on CI/CD scripts or infrastructure-as-code templates.

---

## 3. Data Types & Conversions

**Common Data Types:**
- `str` (String)
- `int` (Integer)
- `float` (Decimal numbers)
- `bool` (True/False)
- `list`, `tuple`, `dict`, `set`

**Type Conversion:**
- **Implicit**: Python converts automatically (`int` to `float`)
- **Explicit**: Manually convert using `str()`, `int()`, `float()`

Example:
```python
area = (base * height) / 2
print("Area: " + str(area))
