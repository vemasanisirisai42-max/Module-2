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
