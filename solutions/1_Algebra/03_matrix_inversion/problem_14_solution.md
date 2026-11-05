# Exercise 14. A Matrix That Is Its Own Inverse

Assume $A^2=I$. Then

$$
AA=I.
$$

The definition of an inverse says that $A^{-1}$ is the matrix whose product with $A$ is $I$. Since multiplying $A$ by itself gives $I$ in either order, $A$ is its own inverse:

$$
A^{-1}=A.
$$

A concrete example different from both $I$ and $-I$ is

$$
A=\begin{pmatrix}
0 & 1 \\
1 & 0 \\
\end{pmatrix}.
$$

**Check by multiplication:**

$$
A^2=\begin{pmatrix}
0 & 1 \\
1 & 0 \\
\end{pmatrix}
\begin{pmatrix}
0 & 1 \\
1 & 0 \\
\end{pmatrix}
=\begin{pmatrix}
1 & 0 \\
0 & 1 \\
\end{pmatrix}=I.
$$

Geometrically, this example exchanges the two coordinates; doing it twice returns the original vector.
