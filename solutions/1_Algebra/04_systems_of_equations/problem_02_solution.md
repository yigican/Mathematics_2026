# Exercise 2. Gaussian Elimination — One Solution

Start from the augmented matrix:

$$
\begin{pmatrix}
1 & 1 & 1 & \mid & 6 \\
2 & -1 & 1 & \mid & 3 \\
1 & 2 & -1 & \mid & 2 \\
\end{pmatrix}.
$$

Apply $R_2\leftarrow R_2-2R_1$ and $R_3\leftarrow R_3-R_1$:

$$
\begin{pmatrix}
1 & 1 & 1 & \mid & 6 \\
0 & -3 & -1 & \mid & -9 \\
0 & 1 & -2 & \mid & -4 \\
\end{pmatrix}.
$$

Interchange $R_2$ and $R_3$, then apply $R_3\leftarrow R_3+3R_2$:

$$
\begin{pmatrix}
1 & 1 & 1 & \mid & 6 \\
0 & 1 & -2 & \mid & -4 \\
0 & 0 & -7 & \mid & -21 \\
\end{pmatrix}.
$$

Back-substitution gives $z=3$, $y-2(3)=-4$ so $y=2$, and $x+2+3=6$ so $x=1$.

$$
(x,y,z)=(1,2,3).
$$

**Check in all original equations:**

$$
1+2+3=6,\qquad
2(1)-2+3=3,\qquad
1+2(2)-3=2.
$$

Each equation holds. All three variables have pivots, so the solution is unique.
