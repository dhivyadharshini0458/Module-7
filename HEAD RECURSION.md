# 🔁 Types of Recursion: Head Recursion in Python

## 🎯 AIM:
To write a Python program to demonstrate **Head Recursion** by finding and printing the sequence based on the sum of all digits (even or odd adjusted input).

## 🧠 ALGORITHM:

1. **Start**
2. Define a recursive function `fun(n)`
3. In the function:
   - Create a recursive call at the **beginning** (Head Recursion)
   - Print the result after the recursive call
4. Take input from the user
5. If input is odd, convert it to the next even number
6. Call the recursive function
7. **Stop**

## 💻 PROGRAM:
```
def fun(n):
    if n == 0:
        return
    fun(n - 2)
    print(n, end=' ')
num = int(input())
if num % 2 != 0:
    num -= 1
print()
fun(num)
```

## OUTPUT
<img width="563" height="145" alt="Screenshot 2026-03-28 073702" src="https://github.com/user-attachments/assets/c70b7d41-7234-46a6-8f33-391b2006cb71" />

## RESULT
Thus, the Python program to demonstrate Head Recursion is executed successfully.
