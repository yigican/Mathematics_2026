# Exercise 12. A Parameter Revealed by a Row Operation

## Question

For

$$
A(t)=
\begin{pmatrix}
1 & 2 & 3 \\
2 & 4 & t \\
0 & 1 & 1 \\
\end{pmatrix}
$$

find the values of $t$ for which the matrix is not invertible.

Before computing the determinant, perform the operation

$$
R_2\leftarrow R_2-2R_1
$$

and use the resulting structure. At the end, explain what special thing happens to the rows for the value of the parameter you found.

> **Why this exercise:** combines a parameter, row operations, and recognition of dependence in one short argument.

## Solution

$$
A(t)=\begin{pmatrix}
1 & 2 & 3 \\
2 & 4 & t \\
0 & 1 & 1 \\
\end{pmatrix}.
$$

Apply the specified operation $R_2\leftarrow R_2-2R_1$. Adding a multiple of one row to another leaves the determinant unchanged:

$$
\det A(t)=\det\begin{pmatrix}
1 & 2 & 3 \\
0 & 0 & t-6 \\
0 & 1 & 1 \\
\end{pmatrix}.
$$

Expand along the second row. The cofactor of the entry in position $(2,3)$ has sign $(-1)^{2+3}=-1$:

$$
\begin{aligned}
\det A(t)
&=-(t-6)\det\begin{pmatrix}
1 & 2 \\
0 & 1 \\
\end{pmatrix}\\
&=-(t-6)=6-t.
\end{aligned}
$$

A square matrix is noninvertible precisely when its determinant is zero. Thus

$$
6-t=0\quad\Longrightarrow\quad t=6.
$$

**Check and explanation:** At $t=6$, the original second row becomes $(2,4,6)=2(1,2,3)$, so two rows are dependent. Equivalently, the row operation above creates a zero row. Both facts confirm $\det A(6)=0$.
