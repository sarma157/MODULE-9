# 🧮 List Comprehension:Transpose of Matrix 

## 🎯 AIM:
To write a Python program to compute the **transpose** of a matrix using **list comprehension**.

---

## 🧠 ALGORITHM:

1. **Start**
2. Create variables `r` and `c` to represent the number of rows and columns of the matrix.
3. Get the values of `r` and `c` from the user.
4. Define a function `create(r, c)` to create the matrix by reading the elements from the user.
5. Use **list comprehension** to calculate the transpose of the matrix.
6. Print the transposed matrix.
7. **Stop**

---

## 💻 PROGRAM:
ADD CODE HERE
```
def read_matrix(r, c):
    matrix = [[0] * c for row in range(r)]
    for i in range(r):
        lines = list(map(int, input().split()))
        for j in range(c):
            matrix[i][j] = lines[j]
    return matrix
def print_matrix(M):
    print("Matrix:")
    for i in range(len(M)):
        for j in range(len(M[0])):
            print(M[i][j], end=" ")
        print()
def transpose(M):
    result = [[0] * len(M) for rows in range(len(M[0]))]
    for i in range(len(M)):
        for j in range(len(M[0])):
            result[j][i] = M[i][j]
    return result
# Input
r = int(input("Enter number of rows: "))
c = int(input("Enter number of columns: "))
M = read_matrix(r, c)
print_matrix(M)
T = transpose(M)
print("Transpose:")
print_matrix(T)
```
## OUTPUT:
<img width="537" height="340" alt="image" src="https://github.com/user-attachments/assets/feaf71c2-2bf3-4987-a920-eb37a6f2e0d3" />

## RESULT:
Thus the program executed successfully.



