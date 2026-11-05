# Exercise 6. Parameter and Invertibility

## Question

For

$$
A(t)=
\begin{pmatrix}
t & 1 \\
2 & t \\
\end{pmatrix}
$$

find all values of $t$ for which the matrix is not invertible. Explain how your answer is related to the determinant being zero.

> **Why this exercise:** shows how the determinant can be used to study a family of matrices depending on a parameter.

## Solution

$$
A(t)=\begin{pmatrix}
t & 1 \\
2 & t \\
\end{pmatrix}.
$$

For a $2\times2$ matrix, the determinant is the product of the main diagonal entries minus the other diagonal product:

$$
\det A(t)=t\cdot t-1\cdot2=t^2-2.
$$

A square matrix is not invertible exactly when its determinant equals zero:

$$
\begin{aligned}
t^2-2&=0\\
t^2&=2\\
t&=\pm\sqrt{2}.
\end{aligned}
$$

**Answer:** $A(t)$ is noninvertible for $t=\sqrt{2}$ and $t=-\sqrt{2}$. For every other real $t$, it is invertible.

**Check:** Substituting either exceptional value into $t^2-2$ gives zero. Also, when $t^2=2$, the second row is $(2/t)$ times the first row, so the rows are dependent.
