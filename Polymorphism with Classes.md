# # 🐍 Python OOP: Polymorphism with Classes

## 🎯 AIM

To create two specific classes — `Beans` and `Mango`. Then, create a **generic function** that can accept any object and determine its **type** (Fruit or Vegetable) and **color**, using polymorphism.

---

## 🧠 ALGORITHM

1. **Create Class `Beans`**:
   - Define `type()` method that prints `"Vegetable"`.
   - Define `color()` method that prints `"Green"`.

2. **Create Class `Mango`**:
   - Define `type()` method that prints `"Fruit"`.
   - Define `color()` method that prints `"Yellow"`.

3. **Define Generic Function `func(obj)`**:
   - Call `obj.type()` and `obj.color()` — this works with both `Beans` and `Mango` objects, showcasing **polymorphism**.

4. **Create Objects**:
   - Instantiate `Beans` and `Mango`.
   - Pass them to `func()` and execute the program.

---

## 💻 Program
```
# Step 1: Create Beans class
class Beans:
    def type(self):
        print("Vegetable")
    
    def color(self):
        print("Green")

# Step 2: Create Mango class
class Mango:
    def type(self):
        print("Fruit")
    
    def color(self):
        print("Yellow")

# Step 3: Generic function
def func(obj):
    obj.type()
    obj.color()

# Step 4: Create objects
b = Beans()
m = Mango()

# Call function with different objects
func(b)
func(m)
```

## Output
```
Vegetable
Green
Fruit
Yellow
```

## Result
Two specific classes — `Beans` and `Mango`. Then, create a **generic function** that can accept any object and determine its **type** (Fruit or Vegetable) and **color**, using polymorphism is verified.
