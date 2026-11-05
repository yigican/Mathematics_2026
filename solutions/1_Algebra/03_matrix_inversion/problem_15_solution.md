# Exercise 15. Two Methods for Solving the Same System

## Question

For

$$
A=
\begin{pmatrix}
2 & 1 \\
1 & 3 \\
\end{pmatrix},\qquad b=
\begin{pmatrix}
7 \\
8 \\
\end{pmatrix}
$$

solve $Ax=b$ in two ways:

1. using $A^{-1}b$,
2. using Gaussian elimination.

Compare both solutions, the number of essential steps, and state which method was simpler in this example.

> **Why this exercise:** compares two known methods and prepares the student to choose a solution method consciously.

## Solution

$$
A=\begin{pmatrix}
2 & 1 \\
1 & 3 \\
\end{pmatrix},\qquad
b=\begin{pmatrix}
7 \\
8 \\
\end{pmatrix}.
$$

**Method 1 — inverse:** Since $\det A=5$,

$$
A^{-1}=\frac15\begin{pmatrix}
3 & -1 \\
-1 & 2 \\
\end{pmatrix}.
$$

Therefore,

$$
x=A^{-1}b
=\frac15\begin{pmatrix}
3(7)-8 \\
-7+2(8) \\
\end{pmatrix}
=\begin{pmatrix}
\frac{13}{5} \\
\frac95 \\
\end{pmatrix}.
$$

**Method 2 — Gaussian elimination:** Begin with

$$
\begin{pmatrix}
2 & 1 & \mid & 7 \\
1 & 3 & \mid & 8 \\
\end{pmatrix}.
$$

Swap $R_1$ with $R_2$, then apply $R_2\leftarrow R_2-2R_1$:

$$
\begin{pmatrix}
1 & 3 & \mid & 8 \\
0 & -5 & \mid & -9 \\
\end{pmatrix}.
$$

The second row gives $x_2=9/5$. Back-substituting into $x_1+3x_2=8$ gives

$$
x_1=8-3\cdot\frac95=\frac{13}{5}.
$$

Both methods give the same vector.

**Check:**

$$
Ax=\begin{pmatrix}
2(\frac{13}{5})+\frac95 \\
\frac{13}{5}+3(\frac95) \\
\end{pmatrix}
=\begin{pmatrix}
7 \\
8 \\
\end{pmatrix}=b.
$$

**Comparison:** The inverse method requires a determinant, an inverse matrix, and a matrix-vector multiplication. Elimination uses one row swap, one row replacement, and back-substitution. For this one small system, elimination is slightly simpler; a previously computed inverse would become useful for several right-hand sides.
