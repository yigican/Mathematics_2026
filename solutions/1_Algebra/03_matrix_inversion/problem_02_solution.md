# Exercise 2. Formula for a 2×2 Matrix

$$
A=\begin{pmatrix}
3 & 2 \\
5 & 4 \\
\end{pmatrix}.
$$

For a nonsingular $2\times2$ matrix, interchange the diagonal entries, negate the off-diagonal entries, and divide by the determinant:

$$
\det A=3\cdot4-2\cdot5=2\neq0.
$$

Therefore,

$$
A^{-1}=\frac{1}{2}
\begin{pmatrix}
4 & -2 \\
-5 & 3 \\
\end{pmatrix}
=\begin{pmatrix}
2 & -1 \\
-\frac52 & \frac32 \\
\end{pmatrix}.
$$

**Check:** Multiplying by the original matrix gives

$$
AA^{-1}=
\begin{pmatrix}
3 & 2 \\
5 & 4 \\
\end{pmatrix}
\begin{pmatrix}
2 & -1 \\
-\frac52 & \frac32 \\
\end{pmatrix}
=\begin{pmatrix}
6-5 & -3+3 \\
10-10 & -5+6 \\
\end{pmatrix}=I.
$$
