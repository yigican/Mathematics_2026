# Exercise 10. Columns of a Matrix Product

## Question

Given

$$
A=
\begin{pmatrix}
1 & 2 & 0 \\
0 & 1 & 1 \\
\end{pmatrix},\qquad B=
\begin{pmatrix}
1 & 2 \\
-1 & 0 \\
3 & 1 \\
\end{pmatrix}.
$$

Denote the columns of $B$ by $b_1,b_2$.

1. Compute $Ab_1$ and $Ab_2$.
2. Compute the matrix $AB$.
3. Compare the results and explain why the columns of $AB$ are exactly the vectors $Ab_1$ and $Ab_2$.

> **Why this exercise:** extends the interpretation of matrix-vector multiplication to a full product of two matrices instead of simply repeating another $Ax$ exercise.

---

## Solution

$$
A=\begin{pmatrix}
1 & 2 & 0 \\
0 & 1 & 1 \\
\end{pmatrix},\qquad
B=\begin{pmatrix}
1 & 2 \\
-1 & 0 \\
3 & 1 \\
\end{pmatrix}.
$$

The columns of $B$ are $b_1=(1,-1,3)^T$ and $b_2=(2,0,1)^T$. Multiplying them separately,

$$
Ab_1=\begin{pmatrix}
1-2+0 \\
0-1+3 \\
\end{pmatrix}
=\begin{pmatrix}
-1 \\
2 \\
\end{pmatrix},\qquad
Ab_2=\begin{pmatrix}
2+0+0 \\
0+0+1 \\
\end{pmatrix}
=\begin{pmatrix}
2 \\
1 \\
\end{pmatrix}.
$$

Computing the full product,

$$
AB=\begin{pmatrix}
-1 & 2 \\
2 & 1 \\
\end{pmatrix}.
$$

**Explanation and check:** The first column of $AB$ equals $Ab_1$ and the second equals $Ab_2$. In other words, $AB$ is formed by placing the vectors $Ab_1$ and $Ab_2$ side by side. This follows because each column of a matrix product is formed by applying the left matrix to the corresponding column of the right matrix.

## More Challenging Exercises
