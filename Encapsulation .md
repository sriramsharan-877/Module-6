# 🐍 Python OOP: Encapsulation with Private Members

## 🎯 AIM

To implement **Encapsulation** in Python by defining a class `Rectangle` with **private member variables** `__length` and `__breadth`.

---

## 🧠 ALGORITHM

1. **Define the Class**:
   - Create a class `Rectangle` with two private attributes: `__length` and `__breadth`.

2. **Initialize Variables**:
   - Use the `__init__()` constructor to set initial values for `__length` and `__breadth`.

3. **Print Values**:
   - Display the private variables from within the class to demonstrate access.

4. **Instantiate the Object**:
   - Create an object of the `Rectangle` class to trigger the constructor.

---

## 💻 Program
```
# Step 1: Define the class
class Rectangle:
    
    # Step 2: Initialize variables
    def __init__(self, length, breadth):
        self.__length = length
        self.__breadth = breadth
        
        # Step 3: Print values (inside class)
        print("Length:", self.__length)
        print("Breadth:", self.__breadth)

# Step 4: Instantiate object
obj = Rectangle(10, 5)
```

## Output
```
Length: 10
Breadth: 5
```

## Result
To implement **Encapsulation** in Python by defining a class `Rectangle` with **private member variables** `__length` and `__breadth` is verified.
