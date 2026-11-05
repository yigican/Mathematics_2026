# Exercise 7. Inverse of a Product

## Question

For

$$
A=
\begin{pmatrix}
1 & 1 \\
0 & 1 \\
\end{pmatrix},\qquad B=
\begin{pmatrix}
2 & 0 \\
0 & 3 \\
\end{pmatrix}
$$

compute $(AB)^{-1}$ and $B^{-1}A^{-1}$. Check that the results are the same and explain the meaning of the reversed order.

> **Why this exercise:** reinforces the inverse-of-a-product property and requires its interpretation.

## Solution

$$
A=\begin{pmatrix}
1 & 1 \\
0 & 1 \\
\end{pmatrix},\qquad
B=\begin{pmatrix}
2 & 0 \\
0 & 3 \\
\end{pmatrix}.
$$

First calculate

$$
AB=\begin{pmatrix}
2 & 3 \\
0 & 3 \\
\end{pmatrix}.
$$

The $2\times2$ inverse formula gives

$$
(AB)^{-1}=\frac16\begin{pmatrix}
3 & -3 \\
0 & 2 \\
\end{pmatrix}
=\begin{pmatrix}
\frac12 & -\frac12 \\
0 & \frac13 \\
\end{pmatrix}.
$$

Individually,

$$
A^{-1}=\begin{pmatrix}
1 & -1 \\
0 & 1 \\
\end{pmatrix},\qquad
B^{-1}=\begin{pmatrix}
\frac12 & 0 \\
0 & \frac13 \\
\end{pmatrix}.
$$

Thus

$$
B^{-1}A^{-1}=
\begin{pmatrix}
\frac12 & 0 \\
0 & \frac13 \\
\end{pmatrix}
\begin{pmatrix}
1 & -1 \\
0 & 1 \\
\end{pmatrix}
=\begin{pmatrix}
\frac12 & -\frac12 \\
0 & \frac13 \\
\end{pmatrix}.
$$

**Check:** $(AB)(B^{-1}A^{-1})=A(BB^{-1})A^{-1}=I$. Therefore $(AB)^{-1}=B^{-1}A^{-1}$.

**Explanation:** To undo $AB$, the action of $B$ must be undone before the action of $A$, so the factor order is reversed.
