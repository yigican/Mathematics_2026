# Exercise 6. Solving a System Using the Inverse

## Question

Solve

$$
Ax=b,
$$

where

$$
A=
\begin{pmatrix}
2 & 1 \\
1 & 3 \\
\end{pmatrix},\qquad b=
\begin{pmatrix}
5 \\
7 \\
\end{pmatrix},
$$

using $x=A^{-1}b$. Then substitute the resulting vector back into the equation and check the result.

> **Why this exercise:** shows the connection between inverse matrices and solving a linear system.

## Solution

$$
A=\begin{pmatrix}
2 & 1 \\
1 & 3 \\
\end{pmatrix},\qquad
b=\begin{pmatrix}
5 \\
7 \\
\end{pmatrix}.
$$

Since $\det A=2\cdot3-1=5\neq0$, the matrix is invertible and the system has the unique solution $x=A^{-1}b$. For a $2\times2$ matrix, the inverse is obtained by interchanging the diagonal entries, negating the off-diagonal entries, and dividing by the determinant:

$$
A^{-1}=\frac15\begin{pmatrix}
3 & -1 \\
-1 & 2 \\
\end{pmatrix}.
$$

Multiply by $b$:

$$
x=A^{-1}b
=\frac15\begin{pmatrix}
3(5)-7 \\
-5+2(7) \\
\end{pmatrix}
=\begin{pmatrix}
\frac85 \\
\frac95 \\
\end{pmatrix}.
$$

**Check:** Substitute into the original equation:

$$
Ax=\begin{pmatrix}
2(\frac85)+\frac95 \\
\frac85+3(\frac95) \\
\end{pmatrix}
=\begin{pmatrix}
\frac{25}{5} \\
\frac{35}{5} \\
\end{pmatrix}
=b.
$$
