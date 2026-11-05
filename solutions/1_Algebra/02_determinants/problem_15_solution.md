# Exercise 15. Combining Determinant Properties

## Question

Let $A$ and $B$ be invertible $2\times2$ matrices with

$$
\det A=-2,\qquad \det B=3.
$$

Without finding the entries of the matrices, compute

$$
\det\left(B^{-1}A^TB\right).
$$

State the determinant properties you use in order and explain why the factors involving $B$ eventually cancel.

> **Why this exercise:** tests the transfer of several known properties into one short problem instead of checking a single property again with numbers.

## Solution

Suppose $A$ and $B$ are invertible $2\times2$ matrices, with $\det A=-2$ and $\det B=3$.

We use, in order:

1. **Product rule:** $\det(XYZ)=\det X\,\det Y\,\det Z$.
2. **Inverse rule:** $\det(B^{-1})=1/\det B$.
3. **Transpose rule:** $\det(A^T)=\det A$.

Applying these properties,

$$
\begin{aligned}
\det(B^{-1}A^TB)
&=\det(B^{-1})\,\det(A^T)\,\det B\\
&=\frac{1}{3}\cdot(-2)\cdot3\\
&=-2.
\end{aligned}
$$

**Why the factors cancel:** $\det(B^{-1})\det B=(1/3)\cdot3=1$, leaving only $\det(A^T)=\det A=-2$.

**Check:** $B^{-1}A^TB$ is similar to $A^T$ and therefore has the same determinant. Thus the result must also equal $\det(A^T)=-2$.
