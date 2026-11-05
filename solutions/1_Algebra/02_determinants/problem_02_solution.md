# Exercise 2. Determinant of a 3×3 Matrix

$$
A=\begin{pmatrix}
1 & 2 & -1 \\
0 & 3 & 4 \\
2 & 1 & 5 \\
\end{pmatrix}.
$$

For a $3\times3$ matrix, Sarrus' rule adds the three downward diagonal products and subtracts the three upward diagonal products:

$$
\begin{aligned}
\det A
&=(1\cdot3\cdot5)+(2\cdot4\cdot2)+((-1)\cdot0\cdot1)\\
&\quad-((-1)\cdot3\cdot2)-(1\cdot4\cdot1)-(2\cdot0\cdot5)\\
&=15+16+0-(-6)-4-0\\
&=33.
\end{aligned}
$$

**Check using a determinant property:** Replacing $R_3$ by $R_3-2R_1$ does not change the determinant:

$$
\det A=\det\begin{pmatrix}
1 & 2 & -1 \\
0 & 3 & 4 \\
0 & -3 & 7 \\
\end{pmatrix}.
$$

Expanding along the first column yields

$$
\det A=1\bigl(3\cdot7-4(-3)\bigr)=21+12=33.
$$

Both methods agree.
