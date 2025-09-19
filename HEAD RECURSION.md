# 🔁 Types of Recursion: Head Recursion in Python

## 🎯 AIM:
Write a Python program to display all the token numbers of n outpatients issued in the reception counter based on first come first serve.(Use head recursion)


## 🧠 ALGORITHM:

1. Start
2. Read the number of outpatients n.
3. Define a recursive function display_tokens(i, n):
      Base case: If i > n, return.
      Recursive case (head recursion):
            First call display_tokens(i + 1, n)
            Then print token number i.
4. Call display_tokens(1, n).
5. Stop


## 💻 PROGRAM:

def fun(n):
   
    if (n > 0):
      
        fun(n - 1)
      
        print(n, end=" ")
 

x = int(input())

fun(x)

## OUTPUT

![WhatsApp Image 2025-09-15 at 13 51 03_c5321b7f](https://github.com/user-attachments/assets/92bfbdf8-a8ea-4d15-928d-10f928aaad12)

## RESULT
Thus,it verfied.
