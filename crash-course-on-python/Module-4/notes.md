# 📘 Module 4 Notes — Google IT Automation with Python

## Strings, Lists, and Dictionaries

---

## 🧵 1. Review: What is a String?

- A **string** is a sequence of characters enclosed in quotes (`""` or `''`).

### Example:

```python
name = "Sasha"
color = 'Gold'
print("Name: " + name + ", Favorite color: " + color)
# Output: Name: Sasha, Favorite color: Gold
````

---

## 2. You can multiply strings

* Multiplying a string by a number repeats it.

### Example:

```python
"example" * 3
# Output: exampleexampleexample
```

---

## 3. Length of a string

* Use `len()` to get the number of characters.

### Example:

```python
pet = "loooooooooooooooooooooooooooooooog cat"
print(len(pet))
# Output: 38
```

---

## 4. Parts of a String (Indexing)

* Strings are indexed starting at 0.
* Access individual characters with square brackets `[]`.

### Example:

```python
name = "Jaylen"
print(name[1])  # a
print(name[0])  # J
print(name[5])  # n
# print(name[6])  # Error (index out of range)
```

---

## 5. Slicing Strings

* Extract substring with `[start:end]`.
* Omitting start or end means from start or till end.

### Example:

```python
color = "Orange"
print(color[1:4])  # ran
print(color[:4])   # Oran
print(color[4:])   # ge
```

---

## 6. Looping Through Strings

* Iterate over each character using a `for` loop.

### Example:

```python
pets = "Cats & Dogs"
for char in pets:
    print(char)
```

---

## 7. String Methods

* Useful built-in string methods include:

### Examples:

```python
message = "  Hello World  "
print(message.lower())        # hello world
print(message.upper())        # HELLO WORLD
print(message.strip())        # removes whitespace
print(message.count("l"))     # 3
print(message.endswith("d"))  # True
print(message.isnumeric())    # False
print(message.isalpha())      # False
print(message.replace("World", "Python"))  # Hello Python
```

---

## 8. Formatting Strings

* Use `.format()` or f-strings to insert variables.

### Examples:

```python
name = "Sufi"
age = 22
print("My name is {}, and I am {} years old.".format(name, age))
print(f"My name is {name}, and I am {age} years old.")
```

---

## 9. Lists

* Lists are ordered, mutable collections.

### Example:

```python
fruits = ["apple", "banana", "cherry"]
print(fruits[0])  # apple
fruits[1] = "blueberry"
print(fruits)     # ['apple', 'blueberry', 'cherry']
```

* Adding and removing items:

```python
fruits.append("orange")
fruits.remove("apple")
```

---

## 10. Looping Through Lists

* Use `for` loops to iterate.

### Example:

```python
for fruit in fruits:
    print(fruit)
```

---

## 11. List Operations

* Common operations:

### Example:

```python
numbers = [1, 2, 3]
print(len(numbers))       # 3
print(2 in numbers)       # True
print(numbers + [4, 5])   # [1, 2, 3, 4, 5]
```

---

## 12. Dictionaries

* Store key-value pairs.

### Example:

```python
colors = {"red": "#FF0000", "green": "#00FF00"}
print(colors["red"])  # #FF0000

colors["blue"] = "#0000FF"
del colors["green"]
```

* Looping through dictionaries:

```python
for key, value in colors.items():
    print(key, value)
```

---

## 13. Key Points

* Strings are indexed and immutable
* Lists are ordered and mutable
* Dictionaries store key-value pairs
* Use string methods for transformation and analysis
* Use loops to iterate over sequences

---

## 📚 Resources

* [Python Strings](https://docs.python.org/3/library/stdtypes.html#string-methods)
* [Python Lists](https://docs.python.org/3/tutorial/datastructures.html#more-on-lists)
* [Python Dictionaries](https://docs.python.org/3/tutorial/datastructures.html#dictionaries)
