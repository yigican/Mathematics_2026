# Exercise 1. Determinant of a 2×2 Matrix

For a $2\times2$ matrix, the determinant is $ad-bc$.

For the first matrix,

$$
\det\begin{pmatrix}
3 & -2 \\
5 & 4 \\
\end{pmatrix}
=3\cdot4-(-2)\cdot5
=12+10=22.
$$

For the second matrix,

$$
\det\begin{pmatrix}
1 & 7 \\
2 & 14 \\
\end{pmatrix}
=1\cdot14-7\cdot2
=14-14=0.
$$

**Conclusion:** Only the first matrix is invertible, because a square matrix is invertible exactly when its determinant is nonzero.

**Check:** In the second matrix, the second row is twice the first row, so the rows are dependent and its determinant must be zero. The first determinant is nonzero as directly calculated.
