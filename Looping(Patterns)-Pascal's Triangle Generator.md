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
from math import comb

n = int(input())
for i in range(n):
    print(' ' * (n - i - 1), end='')
    for j in range(i + 1):
        print(comb(i, j), end=' ')
    print()
```
## Sample Output
<img width="299" height="230" alt="{B5382F23-C9A1-4609-BB99-10B4DF4B906A}" src="https://github.com/user-attachments/assets/7667fb7e-5415-408f-baba-2e514623991f" />

