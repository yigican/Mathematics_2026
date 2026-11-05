# Exercise 3. When Does the Inverse Not Exist?

## Question

For

$$
A=
\begin{pmatrix}
2 & 4 \\
1 & 2 \\
\end{pmatrix}
$$

explain in two ways why $A^{-1}$ does not exist: using the determinant and using dependence between the rows.

> **Why this exercise:** connects two signs of noninvertibility instead of treating them as unrelated facts.

## Solution

$$
A=\begin{pmatrix}
2 & 4 \\
1 & 2 \\
\end{pmatrix}.
$$

**First method — determinant:**

$$
\det A=2\cdot2-4\cdot1=0.
$$

A square matrix has an inverse if and only if its determinant is nonzero. Hence $A^{-1}$ does not exist.

**Second method — dependent rows:** The first row $(2,4)$ is twice the second row $(1,2)$. Thus the rows are linearly dependent.

**Check:** The row operation $R_1\leftarrow R_1-2R_2$ creates a zero row:

$$
\begin{pmatrix}
0 & 0 \\
1 & 2 \\
\end{pmatrix}.
$$

This transformation preserves the determinant and confirms that it is zero. Both arguments give the same conclusion: $A$ is singular.
