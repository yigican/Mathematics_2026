# Exercise 4. Matrix Multiplication and Noncommutativity

## Question

For

$$
A=
\begin{pmatrix}
1 & 2 \\
0 & 1 \\
\end{pmatrix},\qquad B=
\begin{pmatrix}
2 & 0 \\
3 & 1 \\
\end{pmatrix}
$$

compute $AB$ and $BA$. Is $AB=BA$? Use this example to explain what noncommutativity of matrix multiplication means.

> **Why this exercise:** shows one of the most important differences between matrix multiplication and multiplication of numbers.

## Solution

$$
A=\begin{pmatrix}
1 & 2 \\
0 & 1 \\
\end{pmatrix},\quad
B=\begin{pmatrix}
2 & 0 \\
3 & 1 \\
\end{pmatrix}.
$$

Using row-by-column dot products:

$$
AB=\begin{pmatrix}
1\cdot2+2\cdot3 & 1\cdot0+2\cdot1 \\
0\cdot2+1\cdot3 & 0\cdot0+1\cdot1 \\
\end{pmatrix}
=\begin{pmatrix}
8 & 2 \\
3 & 1 \\
\end{pmatrix}.
$$

$$
BA=\begin{pmatrix}
2\cdot1+0\cdot0 & 2\cdot2+0\cdot1 \\
3\cdot1+1\cdot0 & 3\cdot2+1\cdot1 \\
\end{pmatrix}
=\begin{pmatrix}
2 & 4 \\
3 & 7 \\
\end{pmatrix}.
$$

**Conclusion and check:** $AB\ne BA$; for example, their $(1,1)$ entries are $8$ and $2$. Matrix multiplication is generally **noncommutative**: changing the order of two factors can change the product.
