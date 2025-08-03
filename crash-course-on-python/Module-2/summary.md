# Module 2: Python Syntax, Semantics, and Conditionals
*Google IT Automation with Python Specialization*

## Overview
Module 2 introduces Python’s syntax, semantics, and the use of conditionals to create logical, decision-making programs. These concepts are foundational for building efficient DevOps scripts for automation, monitoring, and infrastructure management.

## Key Concepts

### Syntax & Semantics
- **Syntax**: Rules that define code structure (like grammar).
- **Semantics**: Meaning/logic behind the syntax.
- Errors:
  - **Syntax Errors**: Code won’t run (typos, missing punctuation).
  - **Semantic Errors**: Code runs but produces incorrect results.

### Naming Rules & Conventions
- No spaces in names; can include numbers but not as the first character.
- Use `snake_case` for variables/functions.
- Descriptive names improve readability (e.g., `server_status` instead of `ss`).

### Data Types & Conversions
- Common types: `str`, `int`, `float`, `bool`, `list`, `tuple`, `dict`, `set`.
- **Implicit conversion**: Done automatically by Python.
- **Explicit conversion**: Manual using `str()`, `int()`, `float()`.

### Type Annotations
- Provide hints about variable types for clarity and debugging.
- Example:  
  ```python
  uptime_days: int = 120
