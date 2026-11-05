# Exercise 7. Using Properties Instead of Recomputing

## Question

Suppose that for a $3\times3$ matrix, $\det A=-4$. Compute

$$
\det(2A),\qquad \det(A^T),\qquad \det(A^2),\qquad \det(-A).
$$

Justify each answer using the appropriate property.

> **Why this exercise:** teaches how to use determinant properties instead of repeating a full calculation.

## Solution

Suppose $A$ is a $3\times3$ matrix and $\det A=-4$.

**Scalar multiplication:** For an $n\times n$ matrix, $\det(cA)=c^n\det A$. Therefore,

$$
\det(2A)=2^3(-4)=-32.
$$

**Transpose:** Transposition does not change the determinant:

$$
\det(A^T)=\det A=-4.
$$

**Matrix power:** The determinant is multiplicative:

$$
\det(A^2)=\det(A)\det(A)=(-4)^2=16.
$$

**Negation:** Since the matrix has three rows,

$$
\det(-A)=(-1)^3\det A=(-1)(-4)=4.
$$

**Check:** Multiplying every one of the three rows by $-1$ changes the determinant's sign three times, confirming $\det(-A)=4$. Likewise, multiplying all three rows by $2$ multiplies the determinant by $8$, confirming $-32$.
