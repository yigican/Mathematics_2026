# Exercise 12. Finding Inverses Without Starting from Scratch

## Question

It is known that

$$
A^{-1}=
\begin{pmatrix}
2 & -1 \\
-3 & 2 \\
\end{pmatrix}.
$$

Without finding $A$, compute $(3A)^{-1}$, $(A^T)^{-1}$, and $(A^2)^{-1}$. Justify each result using the appropriate property.

> **Why this exercise:** teaches how to use inverse properties instead of carrying out unnecessary full calculations.

## Solution

It is known that

$$
A^{-1}=\begin{pmatrix}
2 & -1 \\
-3 & 2 \\
\end{pmatrix}.
$$

**Scalar multiple:** For a nonzero scalar $c$, $(cA)^{-1}=c^{-1}A^{-1}$. Hence

$$
(3A)^{-1}=\frac13\begin{pmatrix}
2 & -1 \\
-3 & 2 \\
\end{pmatrix}
=\begin{pmatrix}
\frac23 & -\frac13 \\
-1 & \frac23 \\
\end{pmatrix}.
$$

**Transpose:** $(A^T)^{-1}=(A^{-1})^T$. Therefore

$$
(A^T)^{-1}=\begin{pmatrix}
2 & -3 \\
-1 & 2 \\
\end{pmatrix}.
$$

**Square:** $(A^2)^{-1}=A^{-1}A^{-1}$. Multiplication gives

$$
(A^2)^{-1}
=\begin{pmatrix}
2 & -1 \\
-3 & 2 \\
\end{pmatrix}
\begin{pmatrix}
2 & -1 \\
-3 & 2 \\
\end{pmatrix}
=\begin{pmatrix}
7 & -4 \\
-12 & 7 \\
\end{pmatrix}.
$$

**Checks:** $(3A)(\frac13A^{-1})=I$, $A^T(A^{-1})^T=(A^{-1}A)^T=I$, and $A^2(A^{-1})^2=I$. These identities verify the results without calculating $A$.
