# Exercise 6. Solving a System Using the Inverse

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

Since $\det A=2\cdot3-1=5\neq0$, the inverse exists:

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
