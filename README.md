# Built-in Functions -Binary Conversion Using Built-in Functions in Python

## 🎯 Aim
To write a Python program to convert the number **16** into its **binary representation** using built-in Python functions.

## 🧠 Algorithm
1. Assign the value `16` to a variable `a`.
2. Use the built-in `bin()` function to convert the number to binary.
3. Print the result.

## 🧾 Program
```
a = 16
binary_representation = bin(a)
print(binary_representation)
```
## Output
<img width="1920" height="1080" alt="Screenshot (13)" src="https://github.com/user-attachments/assets/83049731-f911-4747-a667-1444041f64bb" />


## Result
Thus to write a Python program to convert the number 16 into its binary representation using built-in Python functions has been executed sucessfully.

# Functions in Python: Modulo Calculator

## 🎯 Aim
To write a Python program that defines a function which accepts two values and returns their modulo using the % operator.

## 🧠 Algorithm
Define a function called result that takes two arguments a and b.
Inside the function, compute the modulo using a % b.
Print the result of the modulo operation.
Get two integer inputs from the user.
Call the result function with the user-provided values.

## 🧾 Program
```
def result(a, b):
    print(a % b)

a = int(input("Enter the first number: "))
b = int(input("Enter the second number: "))
result(a, b)
```

## Output
<img width="1920" height="1080" alt="Screenshot (14)" src="https://github.com/user-attachments/assets/f8a72337-3c61-4e45-bb9c-48cb5a993a66" />

## Result
Thus To write a Python program that defines a function which accepts two values and returns their modulo using the % operator has been executed sucessfully.

# Lambda Function in Python: Addition of Two Numbers

## 🎯 Aim
To write a Python program that defines a lambda function which takes two arguments a and b, and returns their sum.

## 🧠 Algorithm
Get two integer inputs from the user.
Use a lambda function to define a function f that returns a + b.
Call the function with the user inputs and print the result.

## 🧾 Program
```
a = int(input("Enter the first number: "))
b = int(input("Enter the second number: "))

f = lambda a, b: a + b
result = f(a, b)

print("Sum:", result)
```
## Output
<img width="1920" height="1080" alt="Screenshot (15)" src="https://github.com/user-attachments/assets/49aafd6b-59c2-4a3a-b369-a829cc4833cd" />

## Result
Thus To write a Python program that defines a lambda function which takes two arguments a and b, and returns their sum has been executed sucessfully.

# Looping(Patterns)-Pascal's Triangle Generator in Python
This project demonstrates a simple Python program to generate Pascal’s Triangle, where the number of rows is provided by the user.

## 🎯 Aim
To write a Python program that generates Pascal's Triangle using numbers. The number of rows is accepted from the user.

## 🧠 Algorithm
Start the program.
Input the number of rows from the user.
Loop from 0 to the number of rows.
For each row:
Print appropriate spaces to shape the triangle.
Compute values using the formula:
[ C(n, k) = \frac{n!}{k!(n-k)!} ]
Print all rows of Pascal’s Triangle.
End the program.

## 🧪 Program
```
import math

rows = int(input("Enter the number of rows: "))

for n in range(rows):
    # Print leading spaces to shape the triangle
    print(' ' * (rows - n), end='')
    for k in range(n + 1):
        # Compute the binomial coefficient using factorials
        val = math.factorial(n) // (math.factorial(k) * math.factorial(n - k))
        print(val, end=' ')
    print()
```
## Output
<img width="1920" height="1080" alt="Screenshot (16)" src="https://github.com/user-attachments/assets/915f37cd-5646-4982-a99b-77684c005e1d" />

## Result
Thus To write a Python program that generates Pascal's Triangle using numbers. The number of rows is accepted from the user has been executed sucessfully.

# Loops in Python: Palindrome Number Checker

## 🎯 Aim
To write a Python program that checks whether a given number is a palindrome using loops.

## 🧠 Algorithm
Get input from the user and assign it to a variable num.
Assign the value of num to a temporary variable temp.
Initialize a variable rev to 0 (used to store the reversed number).
Use a while loop to reverse the digits:
While temp > 0:
rev = (10 * rev) + temp % 10
temp = temp // 10
After the loop, compare rev with num:
If equal, print that the number is a palindrome.
Else, print that it is not a palindrome.

## 🧾 Program
```
num = int(input("Enter a number: "))
temp = num
rev = 0

while temp > 0:
    rev = (10 * rev) + (temp % 10)
    temp = temp // 10

if rev == num:
    print(f"{num} is a palindrome.")
else:
    print(f"{num} is not a palindrome.")
```
## Output
<img width="1920" height="1080" alt="Screenshot (17)" src="https://github.com/user-attachments/assets/6d90fd58-1c93-4f8e-bc48-3cb11af9c757" />

## Result
Thus To write a Python program that checks whether a given number is a palindrome using loops has been executed sucessfully.
