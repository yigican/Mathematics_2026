# Exercise 8. Row Operations and Their Reversibility

## Question

For

$$
A=
\begin{pmatrix}
1 & 2 & -1 \\
2 & 4 & 1 \\
-1 & 1 & 3 \\
\end{pmatrix}
$$

perform, in order:

1. $R_2\leftarrow R_2-2R_1$,
2. $R_3\leftarrow R_3+R_1$,
3. interchange $R_2$ and $R_3$.

Write the matrix after each step. Then, for each of the three operations, state an operation that reverses it.

> **Why this exercise:** prepares for elimination by showing that row operations are controlled and reversible transformations of a matrix.

## Solution

Start with

$$
A=\begin{pmatrix}
1 & 2 & -1 \\
2 & 4 & 1 \\
-1 & 1 & 3 \\
\end{pmatrix}.
$$

**Step 1:** $R_2\leftarrow R_2-2R_1$, where $(2,4,1)-2(1,2,-1)=(0,0,3)$:

$$
A_1=\begin{pmatrix}
1 & 2 & -1 \\
0 & 0 & 3 \\
-1 & 1 & 3 \\
\end{pmatrix}.
$$

**Step 2:** $R_3\leftarrow R_3+R_1$, where $(-1,1,3)+(1,2,-1)=(0,3,2)$:

$$
A_2=\begin{pmatrix}
1 & 2 & -1 \\
0 & 0 & 3 \\
0 & 3 & 2 \\
\end{pmatrix}.
$$

**Step 3:** Swap $R_2$ and $R_3$:

$$
A_3=\begin{pmatrix}
1 & 2 & -1 \\
0 & 3 & 2 \\
0 & 0 & 3 \\
\end{pmatrix}.
$$

Each elementary row operation has an inverse:

1. The inverse of $R_2\leftarrow R_2-2R_1$ is $R_2\leftarrow R_2+2R_1$.
2. The inverse of $R_3\leftarrow R_3+R_1$ is $R_3\leftarrow R_3-R_1$.
3. The inverse of swapping $R_2$ and $R_3$ is swapping those same rows again.

**Check:** Starting from $A_3$, first undo step 3, then step 2, then step 1. This restores the initial rows $(1,2,-1)$, $(2,4,1)$, and $(-1,1,3)$.
