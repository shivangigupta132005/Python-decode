# Functions in Python

## What is a Function?

A function is a reusable block of code that performs a specific task. Functions help us organize code, make it more readable, and avoid repetition.

## Why Use Functions?

- **Code Reusability**: Write once, use many times
- **Modularity**: Break complex problems into smaller parts
- **Maintainability**: Easy to update and debug
- **Readability**: Makes code easier to understand

## Function Syntax

```python
def function_name(parameters):
    """Docstring explaining what the function does"""
    # Function body
    return result
```

## Basic Example

```python
def greet(name):
    """Greet a person by their name"""
    return f"Hello, {name}!"

print(greet("Alice"))  # Output: Hello, Alice!
```

## Types of Functions

### 1. **Functions with No Parameters**
```python
def say_hello():
    print("Hello!")
```

### 2. **Functions with Parameters**
```python
def add(a, b):
    return a + b
```

### 3. **Functions with Default Parameters**
```python
def greet(name="Guest"):
    return f"Hello, {name}!"
```

### 4. **Functions with Multiple Return Values**
```python
def get_coordinates():
    return 10, 20  # Returns a tuple
```

## Key Concepts

- **Parameters**: Variables in the function definition
- **Arguments**: Values passed when calling the function
- **Return Statement**: Sends a value back to the caller
- **Scope**: Variables defined inside a function are local

## Benefits of Using Functions

✓ Reduces code duplication
✓ Improves code organization
✓ Makes testing easier
✓ Increases code readability
✓ Simplifies debugging
