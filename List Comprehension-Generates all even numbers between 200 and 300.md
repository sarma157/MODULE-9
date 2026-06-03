# 🧾 List Comprehension:Generates all even numbers between 200 and 300
## 🎯 AIM:
To write a Python class-based program that generates all even numbers between 200 and 300 using **list comprehension**, and stores them in a list.

---

## 🧠 ALGORITHM:

1. **Start**
2. Create a class named `program`
3. Create variables `a`, `b`, and `c` to represent:
   - `a`: Lower limit
   - `b`: Step value
   - `c`: Upper limit
4. Initialize the values using a constructor `__init__`
5. Define a method `display()` that uses **list comprehension** to store even numbers
6. Print the resulting list of even numbers
7. **Stop**

---

## 💻 PROGRAM:
```
L=[] n=int(input())
for i in range(n):
x=int(input())
L.append(x) ODD=[x for x in L if x%2!=0]
EVEN=[x for x in L if x%2==0]
print(L) print(ODD)
print(EVEN)
```
## OUTPUT:
<img width="592" height="337" alt="image" src="https://github.com/user-attachments/assets/6532485d-2792-4dcf-b158-c84c74aa1cce" />

## RESULT:
Thus the program executed successfully.
