# 🔁 Types of Recursion: Head Recursion in Python

## 🎯 AIM:
Write a Python program to display all the token numbers of n outpatients issued in the reception counter based on first come first serve.(Use head recursion)
## 🧠 ALGORITHM:

Start
1. Read the number of outpatients n.
2. Define a recursive function display_tokens(i, n): Base case: If i > n, return. Recursive case (head recursion): First call display_tokens(i + 1, n) Then print token number i.
3. Call display_tokens(1, n).
4, Stop

## 💻 PROGRAM:

def fun(n):

if (n > 0):
  
    fun(n - 1)
  
    print(n, end=" ")
x = int(input())

fun(x)

## OUTPUT
<img width="1087" height="271" alt="489425112-6df55403-1454-461a-bd9a-6fe36418b522" src="https://github.com/user-attachments/assets/30cad188-2c7f-49cd-80f6-71a3b532505c" />

## RESULT
Thus, the program is excuted and verified.
