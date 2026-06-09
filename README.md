# 🐍 Interactive Personal Data Collector

A beginner-friendly Python project that collects personal information from users, demonstrates Python fundamentals, and displays formatted output.

## 📌 Project Objective

This project demonstrates the use of:

- `print()` function
- `input()` function
- Variables
- Data Types
- Type Casting
- Arithmetic Operators
- `type()` function
- `id()` function
- Formatted Output

## 🚀 Features

✅ Collect user information:
- Name
- Age
- Height
- Favourite Number

✅ Display:
- Data Types
- Memory Addresses
- Birth Year Calculation

✅ Demonstrate:
- Type Casting
- Arithmetic Operations

---

## 🛠️ Technologies Used

- Python 3.x

---

## 📂 Project Structure

```text
Interactive-Personal-Data-Collector/
│
├── personal_data_collector.py
├── README.md
└── screenshots/
    └── output.png
```

---

## 💻 Source Code

```python
print("Welcome to the Interactive Personal Data Collector!")

name = input("Please enter your name: ")
age = int(input("Please enter your age: "))
height = float(input("Please enter your height in meters: "))
fav_num = int(input("Please enter your favourite number: "))

print("\nThank you! Here is the information we collected:\n")

birth_year = 2023 - age

print(f"Name: {name} (Type: {type(name)}, Memory Address: {id(name)})")
print(f"Age: {age} (Type: {type(age)}, Memory Address: {id(age)})")
print(f"Height: {height} (Type: {type(height)}, Memory Address: {id(height)})")
print(f"Favourite Number: {fav_num} (Type: {type(fav_num)}, Memory Address: {id(fav_num)})")

print("\nYour birth year is approximately:")
print(birth_year)

age_float = float(age)
fav_str = str(fav_num)

print("\nType Conversion:")
print("Age converted to float =", age_float)
print("Favourite Number converted to string =", fav_str)

print("\nThank you for using the Personal Data Collector. Goodbye!")
```

---

## 📸 Sample Output

```text
Welcome to the Interactive Personal Data Collector!

Please enter your name: Alice
Please enter your age: 25
Please enter your height in meters: 1.68
Please enter your favourite number: 7

Thank you! Here is the information we collected:

Name: Alice
Age: 25
Height: 1.68
Favourite Number: 7

Your birth year is approximately:
1998
```

---

## 🎯 Learning Outcomes

After completing this project, you will understand:

- User Input Handling
- Variables and Data Types
- Type Casting
- Arithmetic Operations
- Memory Management using `id()`
- Data Type Checking using `type()`
- Formatted Output in Python

---

## 👨‍💻 Author

**Hiteshi Mehta**

B.Sc. IT Student

---

## ⭐ GitHub

If you found this project useful, give it a ⭐ on GitHub.
