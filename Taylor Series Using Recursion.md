# 📐 Taylor Series Using Recursion in Python

## 🎯 AIM:
To write a Python program to evaluate a **Taylor Series** using **recursion**, where values of `x` and `n` are taken from the user.

## 🧠 ALGORITHM:

1. **Start**
2. Create variables `x` and `n`
3. Get values for `x` and `n` from the user
4. Define a recursive function `series(x, n)`
   - **Base case:** If `n == 0`, return 1
   - **Recursive case:** Return `x**n / n + series(x, n-1)`
5. Print the result
6. **Stop**

## 💻 PROGRAM:

def fun(x,n):

if(n==0):
  
    return 1 

else:
  
    return ((2**n)*(x**n)+fun(x,n-1))
x=int(input())

n=int(input())

print(fun(x,n))

## OUTPUT
<img width="840" height="297" alt="489429394-975f483c-2108-4463-8870-d0ecc67ac182" src="https://github.com/user-attachments/assets/d76d8842-8f60-4b7b-8ba9-51439aa870fd" />


## RESULT
Thus, the program is excuted and verified
