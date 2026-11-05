# Exercise 6. Transpose

$$
A=\begin{pmatrix}
1 & 2 & 3 \\
4 & 5 & 6 \\
\end{pmatrix},\qquad
B=\begin{pmatrix}
1 & 0 \\
2 & 1 \\
-1 & 3 \\
\end{pmatrix}.
$$

Transposition exchanges rows and columns:

$$
A^T=\begin{pmatrix}
1 & 4 \\
2 & 5 \\
3 & 6 \\
\end{pmatrix},\qquad
B^T=\begin{pmatrix}
1 & 2 & -1 \\
0 & 1 & 3 \\
\end{pmatrix}.
$$

Multiplying the original matrices,

$$
AB=\begin{pmatrix}
1+4-3 & 0+2+9 \\
4+10-6 & 0+5+18 \\
\end{pmatrix}
=\begin{pmatrix}
2 & 11 \\
8 & 23 \\
\end{pmatrix}.
$$

Now check the transpose-of-a-product identity:

$$
(AB)^T=\begin{pmatrix}
2 & 8 \\
11 & 23 \\
\end{pmatrix},
$$

$$
B^TA^T=\begin{pmatrix}
1 & 2 & -1 \\
0 & 1 & 3 \\
\end{pmatrix}
\begin{pmatrix}
1 & 4 \\
2 & 5 \\
3 & 6 \\
\end{pmatrix}
=\begin{pmatrix}
2 & 8 \\
11 & 23 \\
\end{pmatrix}.
$$

**Conclusion:** $(AB)^T=B^TA^T$. Taking the transpose of a product reverses the order of its factors.
