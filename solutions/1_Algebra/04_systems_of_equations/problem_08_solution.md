# Exercise 8. Two Systems with the Same Coefficient Matrix

## Question

Solve by elimination the two systems

$$
\begin{cases}
2x+y=5, \\
x-y=1,
\end{cases}
$$

$$
\begin{cases}
2x+y=1, \\
x-y=4.
\end{cases}
$$

Compare the successive elimination steps. Which part of the calculation is the same in both cases, and why?

> **Why this exercise:** shows the role of the coefficient matrix independently of the right-hand side.

## Solution

Both systems have coefficient matrix

$$
A=\begin{pmatrix}
2 & 1 \\
1 & -1 \\
\end{pmatrix}.
$$

**First system:** Start from

$$
\begin{pmatrix}
2 & 1 & \mid & 5 \\
1 & -1 & \mid & 1 \\
\end{pmatrix}.
$$

Apply $R_1\leftarrow R_1-2R_2$:

$$
\begin{pmatrix}
0 & 3 & \mid & 3 \\
1 & -1 & \mid & 1 \\
\end{pmatrix}.
$$

Thus $3y=3$, so $y=1$ and $x-y=1$ gives $x=2$.

**Second system:** The same row operation gives

$$
\begin{pmatrix}
2 & 1 & \mid & 1 \\
1 & -1 & \mid & 4 \\
\end{pmatrix}
\quad\longrightarrow\quad
\begin{pmatrix}
0 & 3 & \mid & -7 \\
1 & -1 & \mid & 4 \\
\end{pmatrix}.
$$

Therefore $y=-7/3$ and $x=4+y=5/3$.

**Checks:** For $(2,1)$, $2x+y=5$ and $x-y=1$. For $(5/3,-7/3)$, $2x+y=1$ and $x-y=4$.

**Comparison:** The coefficient transformation $(2,1)-2(1,-1)=(0,3)$ is identical in both systems. Only the right-hand sides change: $5-2(1)=3$ versus $1-2(4)=-7$. This reusable elimination is possible because both systems have the same $A$.
