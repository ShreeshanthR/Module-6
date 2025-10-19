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
class Rectangle:
    def __init__(self,length,width):
        self.length=length
        self.width=width
    def display(self):
        print(self.length)
        print(self.width)
r=Rectangle(5,3)
r.display()
```
## Output
<img width="752" height="206" alt="image" src="https://github.com/user-attachments/assets/3c1bf8ce-439f-4793-a05c-b6558f9db0ab" />

## Result
Thus, the Python program demonstrating Encapsulation was successfully executed using a class with private member variables.
