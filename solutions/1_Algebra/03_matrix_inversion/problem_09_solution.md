# Exercise 9. Matrix Equation

## Question

Given

$$
A=
\begin{pmatrix}
1 & 2 \\
0 & 1 \\
\end{pmatrix},\qquad B=
\begin{pmatrix}
3 & 1 \\
2 & 4 \\
\end{pmatrix}.
$$

Solve the equation $AX=B$ for $X$. Before calculating, decide on which side of the equation $A^{-1}$ must be used. Then check the result by computing $AX$.

> **Why this exercise:** teaches that order matters in matrix equations and must guide the solution.

## Solution

$$
A=\begin{pmatrix}
1 & 2 \\
0 & 1 \\
\end{pmatrix},\qquad
B=\begin{pmatrix}
3 & 1 \\
2 & 4 \\
\end{pmatrix}.
$$

In $AX=B$, the unknown matrix is multiplied by $A$ on the **left**. Therefore multiply both sides on the left by $A^{-1}$:

$$
A^{-1}AX=A^{-1}B,\qquad X=A^{-1}B.
$$

Here

$$
A^{-1}=\begin{pmatrix}
1 & -2 \\
0 & 1 \\
\end{pmatrix}.
$$

Thus

$$
X=\begin{pmatrix}
1 & -2 \\
0 & 1 \\
\end{pmatrix}
\begin{pmatrix}
3 & 1 \\
2 & 4 \\
\end{pmatrix}
=\begin{pmatrix}
-1 & -7 \\
2 & 4 \\
\end{pmatrix}.
$$

**Check:**

$$
AX=\begin{pmatrix}
1 & 2 \\
0 & 1 \\
\end{pmatrix}
\begin{pmatrix}
-1 & -7 \\
2 & 4 \\
\end{pmatrix}
=\begin{pmatrix}
3 & 1 \\
2 & 4 \\
\end{pmatrix}=B.
$$
