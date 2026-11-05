# Exercise 5. Row Operations

## Question

For

$$
A=
\begin{pmatrix}
1 & 2 & 3 \\
2 & 1 & 0 \\
-1 & 4 & 2 \\
\end{pmatrix}
$$

find $\det A$ by simplifying the matrix with row operations. At each step, indicate whether and how the determinant changes.

> **Why this exercise:** connects determinants with row operations and requires conscious tracking of every step.

## Solution

$$
A=\begin{pmatrix}
1 & 2 & 3 \\
2 & 1 & 0 \\
-1 & 4 & 2 \\
\end{pmatrix}.
$$

Use row replacements to create zeros below the first pivot:

$$
R_2\leftarrow R_2-2R_1,\qquad
R_3\leftarrow R_3+R_1.
$$

Both operations have the form $R_i\leftarrow R_i+cR_j$ and therefore **do not change** the determinant. The resulting matrix is

$$
\begin{pmatrix}
1 & 2 & 3 \\
0 & -3 & -6 \\
0 & 6 & 5 \\
\end{pmatrix}.
$$

Expanding along the first column,

$$
\begin{aligned}
\det A
&=1\det\begin{pmatrix}
-3 & -6 \\
6 & 5 \\
\end{pmatrix}\\
&=(-3)\cdot5-(-6)\cdot6\\
&=-15+36=21.
\end{aligned}
$$

**Check:** Direct expansion of the original matrix along its first row gives

$$
\det A=1(2)-2(4)+3(9)=2-8+27=21.
$$

The direct calculation confirms the result obtained by row operations.
