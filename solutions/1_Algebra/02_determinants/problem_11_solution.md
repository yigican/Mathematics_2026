# Exercise 11. Shortening the Calculation with Row Operations

$$
A=\begin{pmatrix}
1 & 2 & 3 \\
1 & 3 & 4 \\
1 & 4 & 6 \\
\end{pmatrix}.
$$

First subtract the top row from each of the two rows below it:

$$
R_2\leftarrow R_2-R_1,\qquad
R_3\leftarrow R_3-R_1.
$$

The resulting matrix is

$$
\begin{pmatrix}
1 & 2 & 3 \\
0 & 1 & 1 \\
0 & 2 & 3 \\
\end{pmatrix}.
$$

Now use $R_3\leftarrow R_3-2R_2$:

$$
\begin{pmatrix}
1 & 2 & 3 \\
0 & 1 & 1 \\
0 & 0 & 1 \\
\end{pmatrix}.
$$

All three operations add a multiple of one row to another row, so **none changes the determinant**. The last matrix is triangular. Hence

$$
\det A=1\cdot1\cdot1=1.
$$

**Check:** Expanding the original determinant along the first row gives $1(18-16)-2(6-4)+3(4-3)=2-4+3=1$.
