# Functions in Python: Modulo Calculator

## 🎯 Aim
To write a Python program that defines a function which accepts two values and returns their **modulo** using the `%` operator.

## 🧠 Algorithm
1. Define a function called `result` that takes two arguments `a` and `b`.
2. Inside the function, compute the modulo using `a % b`.
3. Print the result of the modulo operation.
4. Get two integer inputs from the user.
5. Call the `result` function with the user-provided values.

## 🧾 Program
```
# Function to calculate modulo
def result(a, b):
    mod = a % b
    print("Modulo of", a, "and", b, "is:", mod)

# Taking user input
a = int(input("Enter first number: "))
b = int(input("Enter second number: "))

# Calling the function
result(a, b)
```

## Output
<img width="336" height="114" alt="7" src="https://github.com/user-attachments/assets/12a6ac5c-862b-468d-a75f-3b771c2a850a" />

## Result
Thus the program has been successfully executed
