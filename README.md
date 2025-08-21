# 🧮 Matrix Operations in C++

## 🎯 Aim

To implement basic matrix operations in C++ including addition, multiplication, transpose, diagonal addition, and row comparison using arrays and loops.

---

## 📚 Theory

A **matrix** is a 2D array of numbers arranged in rows and columns.  
Matrix operations are widely used in mathematics, computer graphics, machine learning, and scientific computations.  

Key concepts:
- **Addition**: Performed by adding corresponding elements of two matrices of the same dimension.
- **Multiplication**: Rows of the first matrix multiplied with columns of the second matrix.
- **Transpose**: Flipping a matrix over its diagonal, switching rows with columns.
- **Diagonal operations**: Focused only on elements lying on the main diagonal.
- **Row comparison**: Comparing elements of specific rows for equality or magnitude.

---

## 🧮 Algorithms / Steps

### 1. **Addition of Two Matrices (`Add_2no.cpp`)**
- Input dimensions and elements of both matrices.
- Loop through rows and columns.
- Add corresponding elements: `C[i][j] = A[i][j] + B[i][j]`.
- Print result.

### 2. **Diagonal Addition (`Diagonal_Addition.cpp`)**
- Input a square matrix.
- Traverse where `i == j`.
- Sum diagonal elements.
- Print sum.

### 3. **Matrix Multiplication (`Multiplication.cpp`)**
- Input dimensions and elements of matrices A (m×n) and B (n×p).
- Initialize result matrix C (m×p) with zeros.
- Use triple nested loops:
  - `C[i][j] += A[i][k] * B[k][j]`.
- Print result.

### 4. **Matrix Transpose (`Transpose.cpp`)**
- Input matrix A (m×n).
- For each element `A[i][j]`, assign to `B[j][i]`.
- Print transpose matrix B.

### 5. **First & Second Row Comparison (`first_sec_row_comp.cpp`)**
- Input matrix.
- Extract elements of row1 and row2.
- Compare element-wise:
  - Print whether equal, greater, or smaller.
- Conclude relationship.

---

## ✅ Conclusion

This set of programs demonstrates how arrays and nested loops can be used to perform fundamental matrix operations. These operations form the base for advanced computations in engineering, graphics, and data science.

---

## 🧵 Topics Covered

- 2D Array declaration and initialization  
- Matrix traversal using nested loops  
- Matrix addition, multiplication, transpose  
- Diagonal operations  
- Row-wise comparison  
- Input/Output formatting of matrices  


