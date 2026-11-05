# Exercise 6. A System with a Parameter — Which Cases Actually Occur?

The augmented matrix is

$$
\begin{pmatrix}
1 & 1 & \mid & 2 \\
a & a & \mid & 4 \\
\end{pmatrix}.
$$

Apply $R_2\leftarrow R_2-aR_1$:

$$
\begin{pmatrix}
1 & 1 & \mid & 2 \\
0 & 0 & \mid & 4-2a \\
\end{pmatrix}.
$$

**Case 1: $a=2$.** The last row becomes $0=0$, so only $x+y=2$ remains. The solutions are

$$
(x,y)=(2-t,t),\qquad t\in\mathbb{R}.
$$

There are infinitely many solutions.

**Case 2: $a\neq2$.** The last row says $0=4-2a\neq0$, so there is no solution.

**Why a unique solution never occurs:** Both coefficient rows are always multiples of $(1,1)$; their rank is at most one for two unknowns. Thus there can never be two independent equations.

**Check:** The first equation forces $x+y=2$; substituting into the second requires $2a=4$, exactly the same condition $a=2$.
