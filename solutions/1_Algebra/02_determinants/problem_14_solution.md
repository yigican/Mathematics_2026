# Exercise 14. A System of Equations and the Determinant

$$
A=\begin{pmatrix}
1 & 2 \\
k & 4 \\
\end{pmatrix}.
$$

The determinant is

$$
\det A=1\cdot4-2k=4-2k.
$$

The system $Ax=b$ has exactly one solution for **every** right-hand side $b$ precisely when $A$ is invertible:

$$
4-2k\neq0\quad\Longleftrightarrow\quad k\neq2.
$$

When $k=2$, the coefficient matrix has proportional rows:

$$
A=\begin{pmatrix}
1 & 2 \\
2 & 4 \\
\end{pmatrix}.
$$

**Infinitely many solutions:** Choose

$$
b=\begin{pmatrix}
1 \\
2 \\
\end{pmatrix}.
$$

The two equations are $x_1+2x_2=1$ and $2x_1+4x_2=2$. They are the same condition, so the solutions are

$$
x_1=1-2s,\qquad x_2=s,\qquad s\in\mathbb{R}.
$$

**No solution:** Choose instead

$$
b=\begin{pmatrix}
1 \\
0 \\
\end{pmatrix}.
$$

The equations $x_1+2x_2=1$ and $2x_1+4x_2=0$ are inconsistent: twice the first left-hand side equals the second, but $2\neq0$ on the right.

**Check:** Both examples have the same singular coefficient matrix with $\det A=0$. The consistency of $b$ determines whether infinitely many or no solutions occur.
