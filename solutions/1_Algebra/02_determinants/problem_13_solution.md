# Exercise 13. Determinant by Elimination

$$
A=\begin{pmatrix}
1 & 2 & 3 \\
2 & 5 & 7 \\
1 & 0 & 2 \\
\end{pmatrix}.
$$

**Step 1:** Apply $R_2\leftarrow R_2-2R_1$ and $R_3\leftarrow R_3-R_1$:

$$
\begin{pmatrix}
1 & 2 & 3 \\
0 & 1 & 1 \\
0 & -2 & -1 \\
\end{pmatrix}.
$$

**Step 2:** Apply $R_3\leftarrow R_3+2R_2$:

$$
\begin{pmatrix}
1 & 2 & 3 \\
0 & 1 & 1 \\
0 & 0 & 1 \\
\end{pmatrix}.
$$

Each operation is a row replacement of the form $R_i\leftarrow R_i+cR_j$, so **the determinant stays unchanged** throughout. The final matrix is upper triangular, giving

$$
\det A=1\cdot1\cdot1=1.
$$

**Check:** Directly expanding the original matrix along the first row gives

$$
\begin{aligned}
\det A
&=1(5\cdot2-7\cdot0)-2(2\cdot2-7\cdot1)\\
&\quad+3(2\cdot0-5\cdot1)\\
&=10+6-15=1.
\end{aligned}
$$
