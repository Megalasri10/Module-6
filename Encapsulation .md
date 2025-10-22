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
    def __init__(self, length, breadth):
        self.__length = length     
        self.__breadth = breadth
        print(f"Rectangle created with Length = {self.__length} and Breadth = {self.__breadth}")
rect = Rectangle(5, 3)
```
## Output
<img width="1576" height="475" alt="image" src="https://github.com/user-attachments/assets/2d4bb04d-f9cb-455e-8415-1d61d1a65f10" />

## Result
The code is executed successfully.
