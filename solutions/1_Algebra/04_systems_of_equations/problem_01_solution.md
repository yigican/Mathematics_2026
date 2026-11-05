# Exercise 1. From a System to a Matrix

## Question

Write the system

$$
\begin{cases}
2x-y+z=4, \\
x+3y-2z=1, \\
3x+y+z=7.
\end{cases}
$$

in the form $Ax=b$.
Identify the coefficient matrix, the vector of unknowns, and the right-hand side vector. Explain how each row of the matrix corresponds to one equation.

> **Why this exercise:** teaches how to move between a system of equations and matrix notation.

## Solution

The system is

$$
\begin{cases}
2x-y+z=4,\\
x+3y-2z=1,\\
3x+y+z=7.
\end{cases}
$$

The coefficient matrix, unknown vector, and right-hand side are

$$
A=\begin{pmatrix}
2 & -1 & 1 \\
1 & 3 & -2 \\
3 & 1 & 1 \\
\end{pmatrix},\qquad
x=\begin{pmatrix}
x \\
y \\
z \\
\end{pmatrix},\qquad
b=\begin{pmatrix}
4 \\
1 \\
7 \\
\end{pmatrix}.
$$

Thus the compact matrix form is $Ax=b$.

**Explanation:** Each row of $A$ contains the coefficients of the corresponding equation, in the fixed order $x,y,z$. For example, the second row $(1,3,-2)$ represents $x+3y-2z$.

**Check:** Matrix-vector multiplication expands to

$$
Ax=\begin{pmatrix}
2x-y+z \\
x+3y-2z \\
3x+y+z \\
\end{pmatrix}=b,
$$

which reproduces all three original equations.
