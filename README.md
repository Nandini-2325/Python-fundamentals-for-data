# Python-fundamentals-for-data
# 🐍 Python Practice Exercises  

This repository contains a collection of **Python exercises** I completed as part of my learning journey.  
The exercises focus on problem-solving, arithmetic operations, and applying formulas to real-world scenarios.  

---

## 📘 What I Learned  

By the end of these exercises, I was able to:  
- 🔢 **Extract digits from numbers** using floor division (`//`) and modulus (`%`) to sum or reverse digits  
- 📐 **Measure and calculate areas and distances** by applying appropriate mathematical formulas  
- 🌡️ **Accept user input and convert temperature units** accurately between Celsius, Fahrenheit, etc.  
- 🖥️ **Report results clearly** using formatted Python output (`print` with f-strings)  
- 🛠️ **Troubleshoot simple arithmetic operations** in Python independently  

---

## 🛠️ Concepts Covered  

- Variables & Data Types  
- Arithmetic Operators (`+`, `-`, `*`, `/`, `//`, `%`, `**`)  
- User Input with `input()`  
- Type Conversion (`int()`, `float()`)  
- Formatted Strings (f-strings)  
- Basic Problem-Solving in Python  

---

## 🚀 Example Snippets  

## 1️⃣ Greeting with Name and Age  

**Task:**  
Ask the visitor for their name and age, then print a friendly greeting.  

```python
name = input("Enter your name: ")
age = int(input("Enter your age: "))
print("Hello", name + ",", "Welcome to the community centre!", 
      "At", str(age) + ",", "you're eligible for our young adults programme."
output:
Enter your name: Sarah
Enter your age: 25
Hello Sarah, Welcome to the community centre! At 25, you're eligible for our young adults programme.




Task: Ask the customer for the length and width of their kitchen in meters. Calculate the total area and total cost (£12 per m²).

l = float(input("Enter length of the kitchen: "))
w = float(input("Enter width of Kitchen: "))
area = l * w
total_cost = area * 12
print(f"To tile a kitchen of {l}m x {w}m, you will need {area:.2f} square meters of tiles.")
print(f"The total cost will be £{total_cost:.2f}")
<img width="941" height="72" alt="image" src="https://github.com/user-attachments/assets/65998cf0-05ed-4f45-bd4c-fb8a5b5032cd" />

Task: Convert temperature from Celsius to Fahrenheit.

a = float(input("Enter temperature for today (Celsius): "))
F = (9/5 * a) + 32
print(f"Today's temperature of {a}°C is equal to {F}°F")
<img width="511" height="52" alt="image" src="https://github.com/user-attachments/assets/90f0a652-d312-4725-8663-1d841cf72547" />

Version A: Miles → Kilometres

d = float(input("Enter distance in miles: "))
km = d * 1.60934
print(f"{d} miles in km is {km:.2f}")
<img width="228" height="53" alt="image" src="https://github.com/user-attachments/assets/b2913df9-9707-476a-a038-c5f3a96c47bd" />


Version B: Kilometres → Miles

d = float(input("Enter distance in km: "))
m = d / 1.60934
print(f"{d} km in miles is {m:.2f}")
<img width="411" height="52" alt="image" src="https://github.com/user-attachments/assets/19752a8f-7549-461f-8570-ad8fe05f1509" />

Task: Ask the user to enter a 3-digit number, extract digits, and add them together.

num = int(input("Enter a 3-digit number: "))
hundreds = num // 100
tens = (num // 10) % 10
units = num % 10
lucky_number = hundreds + tens + units
print("Your lucky number is", lucky_number)
<img width="306" height="56" alt="image" src="https://github.com/user-attachments/assets/0a755691-161a-47bb-a541-ab1bf75383b8" />

Task: Ask the user to enter a 4-digit number, then reverse it using floor division and modulus.

num = int(input("Enter a 4-digit number: "))
thousands = num // 1000
hundreds = (num // 100) % 10
tens = (num // 10) % 10
units = num % 10
secret_code = str(units) + str(tens) + str(hundreds) + str(thousands)
print("Your secret code is", secret_code)
<img width="456" height="50" alt="image" src="https://github.com/user-attachments/assets/8187fd29-9a95-45b1-acba-1026f8527f00" />

