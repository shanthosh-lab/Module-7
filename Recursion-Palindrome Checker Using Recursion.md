# 🔁 Recursion:Palindrome Checker Using Recursion in Python

## 🎯 AIM:
To Write a Python program to find the sum of square of a first n Natural Numbers using recursion

## 🧠 ALGORITHM:
1.Start
2.Input a number n.
3. Define a recursive function sum_of_squares(n): Base case: If n == 0, return 0. Recursive case: 4'Return (n * n) + sum_of_squares(n - 1).
5Call the function with n.
6.Print the result.
7.Stop


## 💻 PROGRAM:
def sum_sq_numbers(n):

if(n<=0):
   
    return 0

return((n*n)+sum_sq_numbers(n-1))
n = int(input())

print('Result is',sum_sq_numbers(n))



## OUTPUT 
<img width="836" height="274" alt="489427976-90ae7e41-7bbb-4136-a248-35f2085c16c4" src="https://github.com/user-attachments/assets/5aab5193-da7d-4802-8263-2013f7fdc2d0" />



## RESULT
thus, the program is excuted and verified.

