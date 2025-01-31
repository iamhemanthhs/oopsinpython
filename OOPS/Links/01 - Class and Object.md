

![[Pasted image 20250131214855.png]]
# Class:

A **class** is a blueprint for creating objects, defining their structure and behavior.

### Key Points:

- **Attributes**: Properties or data associated with the objects.
- **Methods**: Functions that define the behavior of the objects.

## Example: Car Class

```python
class Car:
    wheels = 4  # Class attribute (shared by all instances)
    
    def __init__(self, make, model, year):
        self.make = make  # Instance attribute
        self.model = model  # Instance attribute
        self.year = year  # Instance attribute
    
    def display_info(self):
        print(f"{self.year} {self.make} {self.model}")
```

### Breakdown:

- **`wheels`** is a class attribute.
- **`__init__`** initializes instance attributes (`make`, `model`, `year`).
- **`display_info`** displays car information.

### Creating Objects:

```python
car1 = Car("Toyota", "Corolla", 2021)
car2 = Car("Honda", "Civic", 2020)

car1.display_info()  # Output: 2021 Toyota Corolla
car2.display_info()  # Output: 2020 Honda Civic
```

---

# Object:

An **object** is an instance of a class, containing its own data and methods.

## Example:

```python
print(car1.make)  # Output: Toyota
car1.display_info()  # Output: 2021 Toyota Corolla
```

- **Accessing attributes and methods**: `car1.make`, `car1.display_info()`.


