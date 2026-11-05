# Exercise 4. Infinitely Many Solutions

## Question

Solve

$$
\begin{cases}
x+y+z=2, \\
2x+2y+2z=4, \\
x-y+z=0.
\end{cases}
$$

Give the solution in parametric form, identify a free variable, and for one chosen parameter value check that the resulting point really satisfies the system.

> **Why this exercise:** shows the case of multiple solutions and teaches a simple parametric description.

## Solution

Begin with the augmented matrix:

$$
\begin{pmatrix}
1 & 1 & 1 & \mid & 2 \\
2 & 2 & 2 & \mid & 4 \\
1 & -1 & 1 & \mid & 0 \\
\end{pmatrix}.
$$

Apply $R_2\leftarrow R_2-2R_1$ and $R_3\leftarrow R_3-R_1$:

$$
\begin{pmatrix}
1 & 1 & 1 & \mid & 2 \\
0 & 0 & 0 & \mid & 0 \\
0 & -2 & 0 & \mid & -2 \\
\end{pmatrix}.
$$

Thus $y=1$, while the first equation becomes $x+z=1$. The variable $z$ is free. Let $z=t$.

$$
(x,y,z)=(1-t,1,t),\qquad t\in\mathbb{R}.
$$

**Why infinitely many:** There are only two independent equations for three unknowns, leaving one free parameter.

**Check:** Choose $t=0$, giving $(x,y,z)=(1,1,0)$. Then the three original left-hand sides equal $2$, $4$, and $0$, respectively, matching the right-hand sides. In fact substituting $(1-t,1,t)$ works for every real $t$.
