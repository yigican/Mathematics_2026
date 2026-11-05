# Exercise 5. Matrix Times Vector

$$
A=\begin{pmatrix}
2 & -1 \\
1 & 3 \\
\end{pmatrix},\qquad
x=\begin{pmatrix}
4 \\
2 \\
\end{pmatrix}.
$$

$$
Ax=\begin{pmatrix}
2\cdot4+(-1)\cdot2 \\
1\cdot4+3\cdot2 \\
\end{pmatrix}
=\begin{pmatrix}
6 \\
10 \\
\end{pmatrix}.
$$

The columns of $A$ are

$$
a_1=\begin{pmatrix}
2 \\
1 \\
\end{pmatrix},\qquad a_2=\begin{pmatrix}
-1 \\
3 \\
\end{pmatrix}.
$$

Therefore,

$$
Ax=4a_1+2a_2
=4\begin{pmatrix}
2 \\
1 \\
\end{pmatrix}+2\begin{pmatrix}
-1 \\
3 \\
\end{pmatrix}
=\begin{pmatrix}
8 \\
4 \\
\end{pmatrix}+\begin{pmatrix}
-2 \\
6 \\
\end{pmatrix}
=\begin{pmatrix}
6 \\
10 \\
\end{pmatrix}.
$$

**Check:** The row-by-column method and the linear-combination method give the same vector.
