# Exercise 15. Associativity of Multiplication and Different Calculation Paths

## Question

Given

$$
A=
\begin{pmatrix}
1 & 2 & 0 \\
0 & 1 & 1 \\
\end{pmatrix},\quad B=
\begin{pmatrix}
1 & 0 \\
2 & 1 \\
-1 & 3 \\
\end{pmatrix},\quad C=
\begin{pmatrix}
2 & 1 \\
0 & -1 \\
\end{pmatrix}.
$$

Compute $(AB)C$ and $A(BC)$. Compare the results and the number of intermediate operations. Explain what associativity of matrix multiplication means in this example.

> **Why this exercise:** reinforces associativity by comparing two mathematically equivalent calculation paths.

## Solution

$$
A=\begin{pmatrix}
1 & 2 & 0 \\
0 & 1 & 1 \\
\end{pmatrix},\quad
B=\begin{pmatrix}
1 & 0 \\
2 & 1 \\
-1 & 3 \\
\end{pmatrix},\quad
C=\begin{pmatrix}
2 & 1 \\
0 & -1 \\
\end{pmatrix}.
$$

**Path 1: Compute $AB$ first.**

$$
AB=\begin{pmatrix}
1+4+0 & 0+2+0 \\
0+2-1 & 0+1+3 \\
\end{pmatrix}=\begin{pmatrix}
5 & 2 \\
1 & 4 \\
\end{pmatrix}.
$$

$$
(AB)C=\begin{pmatrix}
5 & 2 \\
1 & 4 \\
\end{pmatrix}
\begin{pmatrix}
2 & 1 \\
0 & -1 \\
\end{pmatrix}
=\begin{pmatrix}
10 & 3 \\
2 & -3 \\
\end{pmatrix}.
$$

**Path 2: Compute $BC$ first.**

$$
BC=\begin{pmatrix}
1 & 0 \\
2 & 1 \\
-1 & 3 \\
\end{pmatrix}
\begin{pmatrix}
2 & 1 \\
0 & -1 \\
\end{pmatrix}
=\begin{pmatrix}
2 & 1 \\
4 & 1 \\
-2 & -4 \\
\end{pmatrix}.
$$

$$
A(BC)=\begin{pmatrix}
1 & 2 & 0 \\
0 & 1 & 1 \\
\end{pmatrix}
\begin{pmatrix}
2 & 1 \\
4 & 1 \\
-2 & -4 \\
\end{pmatrix}
=\begin{pmatrix}
10 & 3 \\
2 & -3 \\
\end{pmatrix}.
$$

**Explanation:** Both paths produce the same matrix, verifying associativity, $(AB)C=A(BC)$. We may change the **parentheses** without changing the order of the factors.

**Comparison of intermediate operations:** Counting straightforward scalar multiplications and additions for each matrix product:

| Calculation path | Scalar multiplications | Scalar additions |
|---|---:|---:|
| $AB$ then $(AB)C$ | $12+8=20$ | $8+4=12$ |
| $BC$ then $A(BC)$ | $12+12=24$ | $6+8=14$ |

In this example, computing $AB$ first requires fewer scalar operations. The general principle is that different parenthesizations can have different computational costs even when the final result is identical.
