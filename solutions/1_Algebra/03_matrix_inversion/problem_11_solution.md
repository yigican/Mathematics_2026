# Exercise 11. Parameter and Invertibility

$$
A(t)=\begin{pmatrix}
1 & t \\
t & 1 \\
\end{pmatrix}.
$$

The determinant is

$$
\det A(t)=1-t^2=(1-t)(1+t).
$$

The matrix is invertible if and only if $\det A(t)\neq0$, which gives

$$
t\neq1,\qquad t\neq-1.
$$

For every allowed $t$, the $2\times2$ formula gives

$$
A(t)^{-1}=\frac{1}{1-t^2}\begin{pmatrix}
1 & -t \\
-t & 1 \\
\end{pmatrix}.
$$

**Check:** Multiplication yields

$$
A(t)A(t)^{-1}
=\frac{1}{1-t^2}
\begin{pmatrix}
1-t^2 & 0 \\
0 & 1-t^2 \\
\end{pmatrix}=I.
$$

At $t=1$ the rows are equal; at $t=-1$ they are negatives of each other. In both cases the denominator becomes zero and the inverse does not exist.
