# Exercise 9. Area and the Determinant

$$
u=\begin{pmatrix}
3 \\
1 \\
\end{pmatrix},\qquad
v=\begin{pmatrix}
1 \\
4 \\
\end{pmatrix}.
$$

The area of the parallelogram spanned by two planar vectors is the absolute value of the determinant of the matrix with those vectors as columns:

$$
\begin{aligned}
\mathrm{Area}
&=\left|\det\begin{pmatrix}
3 & 1 \\
1 & 4 \\
\end{pmatrix}\right|\\
&=|3\cdot4-1\cdot1|\\
&=|11|=11.
\end{aligned}
$$

Reversing the column order gives

$$
\det\begin{pmatrix}
1 & 3 \\
4 & 1 \\
\end{pmatrix}
=1\cdot1-3\cdot4=-11.
$$

**Explanation and check:** Swapping columns reverses the sign of a determinant, reflecting the opposite orientation. The geometric area does not depend on orientation: $|-11|=|11|=11$ square units.
