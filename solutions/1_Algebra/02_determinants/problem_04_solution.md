# Exercise 4. Triangular Matrix

## Question

Without expanding the determinant, compute

$$
\det
\begin{pmatrix}
2 & 4 & 1 \\
0 & -3 & 5 \\
0 & 0 & 7 \\
\end{pmatrix}.
$$

State the rule for an arbitrary triangular matrix and explain it using this example.

> **Why this exercise:** reinforces an important property of triangular matrices.

## Solution

The given matrix is upper triangular:

$$
T=\begin{pmatrix}
2 & 4 & 1 \\
0 & -3 & 5 \\
0 & 0 & 7 \\
\end{pmatrix}.
$$

The determinant of a triangular matrix equals the product of its diagonal entries. Therefore, without expansion,

$$
\det T=2\cdot(-3)\cdot7=-42.
$$

**General rule:** For any upper or lower triangular $n\times n$ matrix $T$,

$$
\det T=t_{11}t_{22}\cdots t_{nn}.
$$

**Check:** In the usual determinant expansion, every product except the main-diagonal product contains an entry below the diagonal, which is zero here. Thus only $2(-3)7=-42$ remains.
