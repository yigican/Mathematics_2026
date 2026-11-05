# Exercise 10. Detecting Dependence

Consider

$$
A=\begin{pmatrix}
1 & 2 & 3 \\
2 & 4 & 6 \\
0 & 1 & 5 \\
\end{pmatrix}.
$$

The second row is twice the first:

$$
R_2=2R_1.
$$

**Result:** $\det A=0$, without needing a determinant expansion.

**Property:** A matrix with linearly dependent rows has determinant zero. Such a square matrix is singular and has no inverse.

**Check:** Applying $R_2\leftarrow R_2-2R_1$ produces

$$
\begin{pmatrix}
1 & 2 & 3 \\
0 & 0 & 0 \\
0 & 1 & 5 \\
\end{pmatrix}.
$$

This row replacement leaves the determinant unchanged, while the new zero row makes the determinant visibly zero.
