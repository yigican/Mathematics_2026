# Exercise 7. Choosing a Method Deliberately

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
