# Built-in Functions -Binary Conversion Using Built-in Functions in Python

## 🎯 Aim
To write a Python program to convert the number **16** into its **binary representation** using built-in Python functions.

## 🧠 Algorithm
1. Assign the value `16` to a variable `a`.
2. Use the built-in `bin()` function to convert the number to binary.
3. Print the result.

## 🧾 Program
```
a=16
n=bin(a)
print(n)
```


## Output
<img width="1088" height="709" alt="image" src="https://github.com/user-attachments/assets/73229ac9-beb1-439b-9cb5-3ff9285d4c8e" />


## Result
Thus, the python program was executed successfully

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
def result(a,b):
        return a%b
try:
    a=int(input())
    b=int(input())    
    
    if b==0:
        print("a is not allowed to divide by b")
    else:
        modulo=result(a,b)
        print("modulo is",modulo)
except value:        
           print("please enter the correct value")
```

## Output
<img width="923" height="705" alt="image" src="https://github.com/user-attachments/assets/2c0572e2-ec88-4f80-94a2-00164a0f0dd4" />

## Result
Thus, the python program was executed successfully


# Lambda Function in Python: Addition of Two Numbers

## 🎯 Aim
To write a Python program that defines a **lambda function** which takes two arguments `a` and `b`, and returns their sum.

## 🧠 Algorithm
1. Get two integer inputs from the user.
2. Use a **lambda function** to define a function `f` that returns `a + b`.
3. Call the function with the user inputs and print the result.

## 🧾 Program
Add code here
```
a = int(input("Enter first number: "))
b = int(input("Enter second number: "))
f = lambda a, b: a + b
print("The sum is:", f(a, b))
```
## Output
<img width="990" height="769" alt="image" src="https://github.com/user-attachments/assets/f53bc84d-6472-4f8c-9f20-a4a688494dc3" />

## Result
Thus, the output is verified successfully

# 🔺 Looping(Patterns)-Pascal's Triangle Generator in Python

This project demonstrates a simple Python program to generate **Pascal’s Triangle**, where the number of rows is provided by the user.

---

## 🎯 Aim

To write a Python program that generates **Pascal's Triangle** using numbers. The number of rows is accepted from the user.

---

## 🧠 Algorithm

1. Start the program.
2. Input the number of rows from the user.
3. Loop from 0 to the number of rows.
4. For each row:
   - Print appropriate spaces to shape the triangle.
   - Compute values using the formula:  
     \[
     C(n, k) = \frac{n!}{k!(n-k)!}
     \]
5. Print all rows of Pascal’s Triangle.
6. End the program.

---

## 🧪 Program
```
from math import factorial
rows = int(input("Enter the number of rows: "))

for i in range(rows):
    print(" " * (rows - i), end="")

    for j in range(i + 1):
        print(factorial(i) // (factorial(j) * factorial(i - j)), end=" ")

    print()
```

## Sample Output
<img width="872" height="769" alt="image" src="https://github.com/user-attachments/assets/4d74e877-669e-4eb1-a019-67f1b9cc5eb6" />

## Result
Thus, the output is verified successfully

## Loops in Python: Palindrome Number Checker

## 🎯 Aim
To write a Python program that checks whether a given number is a **palindrome** using loops.

## 🧠 Algorithm
1. Get input from the user and assign it to a variable `num`.
2. Assign the value of `num` to a temporary variable `temp`.
3. Initialize a variable `rev` to 0 (used to store the reversed number).
4. Use a `while` loop to reverse the digits:
   - While `temp > 0`:
     - `rev = (10 * rev) + temp % 10`
     - `temp = temp // 10`
5. After the loop, compare `rev` with `num`:
   - If equal, print that the number is a palindrome.
   - Else, print that it is not a palindrome.

## 🧾 Program
```
num = int(input("Enter a number: "))
temp = num
rev = 0  
while temp > 0:
    rev = (10 * rev) + temp % 10
    temp = temp // 10
if num == rev:
    print(f"{num} is a palindrome!")
else:
    print(f"{num} is not a palindrome.")
```
## Output
<img width="713" height="702" alt="image" src="https://github.com/user-attachments/assets/0b69f879-728d-46c2-9130-6cf530a096d5" />

## Result
Thus, the output is verified successfully
