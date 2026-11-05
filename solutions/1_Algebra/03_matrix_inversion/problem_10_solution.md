# Exercise 10. Inverse of a Diagonal Matrix

$$
D=\begin{pmatrix}
2 & 0 & 0 \\
0 & -3 & 0 \\
0 & 0 & 5 \\
\end{pmatrix},\qquad
E=\begin{pmatrix}
2 & 0 & 0 \\
0 & 0 & 0 \\
0 & 0 & 5 \\
\end{pmatrix}.
$$

A diagonal matrix is invertible precisely when every diagonal entry is nonzero. In that case, its inverse contains the reciprocals of those entries.

All diagonal entries of $D$ are nonzero, so

$$
D^{-1}=\begin{pmatrix}
\frac12 & 0 & 0 \\
0 & -\frac13 & 0 \\
0 & 0 & \frac15 \\
\end{pmatrix}.
$$

The middle diagonal entry of $E$ is zero. Therefore $\det E=2\cdot0\cdot5=0$, so $E^{-1}$ does not exist.

**Check:**

$$
DD^{-1}=\begin{pmatrix}
2(\frac12) & 0 & 0 \\
0 & (-3)(-\frac13) & 0 \\
0 & 0 & 5(\frac15) \\
\end{pmatrix}=I.
$$
