# Exercise 3. Inconsistent System

## Question

Solve or show that the system is inconsistent:

$$
\begin{cases}
x+2y=3, \\
2x+4y=7.
\end{cases}
$$

Show how the contradiction appears in the matrix after elimination and interpret it in terms of equations.

> **Why this exercise:** teaches how to recognize that a system has no solution without guessing.

## Solution

The augmented matrix of the two equations is

$$
\begin{pmatrix}
1 & 2 & \mid & 3 \\
2 & 4 & \mid & 7 \\
\end{pmatrix}.
$$

Apply $R_2\leftarrow R_2-2R_1$:

$$
\begin{pmatrix}
1 & 2 & \mid & 3 \\
0 & 0 & \mid & 1 \\
\end{pmatrix}.
$$

The last row means $0x+0y=1$, or $0=1$, which is impossible.

**Conclusion:** There is **no solution**; the system is inconsistent.

**Independent check:** The left-hand side of the second original equation is twice that of the first, but its right-hand side is $7$ rather than $2\cdot3=6$. Therefore no pair $(x,y)$ can satisfy both equations.
