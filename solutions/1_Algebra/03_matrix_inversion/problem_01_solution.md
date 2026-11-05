# Exercise 1. Definition of the Inverse

Given

$$
A=\begin{pmatrix}
2 & 1 \\
1 & 1 \\
\end{pmatrix},\qquad
B=\begin{pmatrix}
1 & -1 \\
-1 & 2 \\
\end{pmatrix}.
$$

Multiply in both orders:

$$
AB=\begin{pmatrix}
2(1)+1(-1) & 2(-1)+1(2) \\
1(1)+1(-1) & 1(-1)+1(2) \\
\end{pmatrix}
=\begin{pmatrix}
1 & 0 \\
0 & 1 \\
\end{pmatrix}=I.
$$

$$
BA=\begin{pmatrix}
1(2)+(-1)(1) & 1(1)+(-1)(1) \\
(-1)(2)+2(1) & (-1)(1)+2(1) \\
\end{pmatrix}
=\begin{pmatrix}
1 & 0 \\
0 & 1 \\
\end{pmatrix}=I.
$$

**Conclusion:** $B=A^{-1}$. By definition, the inverse of a square matrix $A$ is a matrix $B$ satisfying both $AB=I$ and $BA=I$. The two direct products verify the claim without any inverse formula.
