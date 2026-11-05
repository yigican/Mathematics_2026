# Exercise 4. Gauss–Jordan

$$
A=\begin{pmatrix}
1 & 2 \\
3 & 5 \\
\end{pmatrix}.
$$

Start from the augmented matrix $[A\mid I]$:

$$
\begin{pmatrix}
1 & 2 & \mid & 1 & 0 \\
3 & 5 & \mid & 0 & 1 \\
\end{pmatrix}.
$$

Apply $R_2\leftarrow R_2-3R_1$:

$$
\begin{pmatrix}
1 & 2 & \mid & 1 & 0 \\
0 & -1 & \mid & -3 & 1 \\
\end{pmatrix}.
$$

Apply $R_2\leftarrow -R_2$:

$$
\begin{pmatrix}
1 & 2 & \mid & 1 & 0 \\
0 & 1 & \mid & 3 & -1 \\
\end{pmatrix}.
$$

Apply $R_1\leftarrow R_1-2R_2$:

$$
\begin{pmatrix}
1 & 0 & \mid & -5 & 2 \\
0 & 1 & \mid & 3 & -1 \\
\end{pmatrix}.
$$

Therefore,

$$
A^{-1}=\begin{pmatrix}
-5 & 2 \\
3 & -1 \\
\end{pmatrix}.
$$

**Why the method works:** The same elementary row operations that turn $A$ into $I$ turn $I$ into $A^{-1}$, because their combined effect is multiplication by $A^{-1}$ on the left.

**Check:**

$$
AA^{-1}=
\begin{pmatrix}
1(-5)+2(3) & 1(2)+2(-1) \\
3(-5)+5(3) & 3(2)+5(-1) \\
\end{pmatrix}
=I.
$$
