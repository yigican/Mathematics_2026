# Exercise 7. Choosing a Method Deliberately

## Question

Do not solve all of the following systems completely. For each situation, choose the method that best uses its structure and justify your choice:

1. one system with a triangular coefficient matrix

$$
\begin{cases}
2x-y=3, \\
4y=8;
\end{cases}
$$

2. three systems $Ax=b_i$ with the same invertible matrix $A$, when $A^{-1}$ is already known;
3. one $3\times3$ system for which the inverse matrix is not given and the goal is only to find one solution vector.

For case 1, carry out the chosen method completely. For cases 2 and 3, describe the plan and indicate which part of the computation would be reusable or unnecessary. Do not judge a method by its name alone — refer to the number of right-hand sides and the structure of the matrix.

> **Why this exercise:** practices choosing a method based on the structure of the problem instead of solving another small system by two methods.

## Solution

**Case 1 — triangular coefficient matrix.** Use back-substitution because the second equation contains only $y$:

$$
4y=8\quad\Longrightarrow\quad y=2.
$$

Then $2x-y=3$ gives

$$
2x-2=3\quad\Longrightarrow\quad x=\frac52.
$$

**Check:** $2(\frac52)-2=3$ and $4(2)=8$.

**Case 2 — three systems with the same known inverse.** Use the inverse method separately on each right-hand side:

$$
x_1=A^{-1}b_1,\qquad
x_2=A^{-1}b_2,\qquad
x_3=A^{-1}b_3.
$$

The existing $A^{-1}$ is reusable. Recomputing the inverse or repeating the elimination for each right-hand side is unnecessary. Each result can be checked through $Ax_i=b_i$.

**Case 3 — one $3\times3$ system, inverse not supplied.** Use Gaussian elimination on $[A\mid b]$, followed by back-substitution if the system has a unique solution. Only one right-hand side is involved, so finding the full inverse would require extra work without providing a benefit.

**Principle:** Choose the method using the matrix structure and the number of right-hand sides, not just the name of the method.
