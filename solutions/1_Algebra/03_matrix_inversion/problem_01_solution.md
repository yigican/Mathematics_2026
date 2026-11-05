# Exercise 1. Definition of the Inverse

## Question

For

$$
A=
\begin{pmatrix}
2 & 1 \\
1 & 1 \\
\end{pmatrix},\qquad B=
\begin{pmatrix}
1 & -1 \\
-1 & 2 \\
\end{pmatrix}
$$

check, without using a formula, whether $B=A^{-1}$. Compute $AB$ and $BA$ and relate the result to the definition of the inverse.

> **Why this exercise:** starts from the definition of the inverse through multiplication before any formulas or computational methods are introduced.

## Solution

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
