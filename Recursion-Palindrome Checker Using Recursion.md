# 🔁 Recursion:Palindrome Checker Using Recursion in Python

## 🎯 AIM:
To Write a Python program to find the sum of square of a first n Natural Numbers using recursion



---

## 🧠 ALGORITHM:
1. Start
2. Input a number n.
3. Define a recursive function sum_of_squares(n):
         Base case: If n == 0, return 0.
         Recursive case: Return (n * n) + sum_of_squares(n - 1).
4. Call the function with n.
5. Print the result.
6. Stop


## 💻 PROGRAM:
def sum_sq_numbers(n):
   
    if(n<=0):
       
        return 0
    
    return((n*n)+sum_sq_numbers(n-1))

n = int(input())

print('Result is',sum_sq_numbers(n))

## OUTPUT

![WhatsApp Image 2025-09-15 at 13 59 53_8c78591f](https://github.com/user-attachments/assets/d05459e0-49ec-4c1f-92e2-5000a57a07a7)


## RESULT

Thus, it verified.

