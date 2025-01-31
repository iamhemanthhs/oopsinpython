
## Constructor in OOP (Python)

A constructor is a special method that is automatically called when an object of a class is created. The constructor is typically used to initialize the attributes of the object, setting up its initial state.

In Python, the constructor method is called `__init__`. It is defined within a class and is called when an object is instantiated. The `__init__` method can take arguments, but the first argument must always be `self`, which refers to the instance of the object being created.

### Example of a Constructor in Python:

```python
class Person:
    def __init__(self, name, age):  # Constructor method
        self.name = name  # Instance attribute
        self.age = age  # Instance attribute

# Creating an object of the Person class
person1 = Person("Alice", 30)

# Accessing object attributes
print(person1.name)  # Output: Alice
print(person1.age)   # Output: 30
```

### Key Points:

- `__init__(self, ...)` is the constructor in Python.
- It is automatically invoked when you create an instance of a class.
- `self` refers to the object instance, and you can use it to set attributes of that instance.
- Constructors allow you to initialize object states when they are created.
