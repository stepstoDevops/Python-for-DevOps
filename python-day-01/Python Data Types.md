# Python Data Types

In Python, data types are especially important because Python uses dynamic typing, meaning you don’t have to declare a variable’s type explicitly; it’s determined by the value you assign .

## **Why Data Types Matter**

- They determine how data is stored in memory.
- They define what operations are valid for each variable.
- They help prevent errors by ensuring data is used appropriately.

## **Python's Built-in Data Types**

Python offers a variety of built-in data types, grouped into several categories:

| Category        | Data Types                                       | Example                                      |
|-----------------|--------------------------------------------------|----------------------------------------------|
| Numeric         | int, float, complex                              | `x = 5`, `y = 3.14`, `z = 2 + 3j`           |
| Sequence        | str, list, tuple, range                          | `"Hello"`, `[1,2,][3]`, `(1,2,3)`, `range(6)` |
| Mapping         | dict                                             | `{'name': 'John', 'age': 30}`               |
| Set             | set, frozenset                                   | `{1,2,3}`, `frozenset([1,[2][3])`             |
| Boolean         | bool                                             | `True`, `False`                             |
| Binary          | bytes, bytearray, memoryview                     | `b'Hello'`, `bytearray(b'Hello')`           |
| None Type       | NoneType                                         | `None`                                      |

### **Numeric Types**
- **int**: Whole numbers, e.g., `x = 10`
- **float**: Decimal numbers, e.g., `y = 10.5`
- **complex**: Complex numbers, e.g., `z = 2 + 3j`

### **Sequence Types**
- **str**: Strings of characters, e.g., `"Python"`
- **list**: Ordered, mutable collections, e.g., `[1, 2,[3]`
- **tuple**: Ordered, immutable collections, e.g., `(1, 2, 3)`
- **range**: Sequence of numbers, e.g., `range(6)`

### **Mapping Type**
- **dict**: Key-value pairs, e.g., `{'a': 1, 'b': 2}`

### **Set Types**
- **set**: Unordered, unique elements, e.g., `{1, 2, 3}`
- **frozenset**: Immutable set, e.g., `frozenset([1][2][3])`

### **Boolean Type**
- **bool**: `True` or `False`

### **Binary Types**
- **bytes**: Immutable sequences of bytes
- **bytearray**: Mutable sequences of bytes
- **memoryview**: Memory view object for binary data

### **None Type**
- **NoneType**: Represents the absence of a value, e.g., `None`

## **Dynamic Typing in Python**

Unlike statically typed languages like Java or C, where you must declare a variable’s type, Python lets you assign any value directly, and the type is set automatically. For example:

```python
x = 10        # int
y = 10.5      # float
z = "Hello"   # str
```

This makes Python flexible and beginner-friendly but requires you to be careful with type changes during runtime.

## **Checking and Setting Data Types**

- Use the `type()` function to check a variable’s type:
  ```python
  print(type(x))  # Output: 
  ```
- You can also use constructor functions to specify a type:
  ```python
  x = str("Hello")
  y = int(20)
  ```

## **Custom Data Types**

Python allows you to create your own data types using classes, enabling you to model complex data and behaviors specific to your application.

## **How Python Manages Data Types Internally**

Python manages memory for different data types using a private heap and specialized allocators for each type, ensuring efficient storage and retrieval. This is all handled automatically by the interpreter.

