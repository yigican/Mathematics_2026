# Exercise 8. Inverse of a Transformation

## Question

The matrix

$$
S=
\begin{pmatrix}
2 & 0 \\
0 & \frac12 \\
\end{pmatrix}
$$

describes a scaling of the plane. Find $S^{-1}$ and explain geometrically what the inverse transformation does. Check the action of the pair $S,S^{-1}$ on one simple vector.

> **Why this exercise:** gives the inverse the interpretation of undoing a transformation.

## Solution

$$
S=\begin{pmatrix}
2 & 0 \\
0 & \frac12 \\
\end{pmatrix}.
$$

The transformation doubles the horizontal coordinate and halves the vertical coordinate. Its inverse must halve the horizontal coordinate and double the vertical coordinate:

$$
S^{-1}=\begin{pmatrix}
\frac12 & 0 \\
0 & 2 \\
\end{pmatrix}.
$$

**Algebraic check:**

$$
S^{-1}S=
\begin{pmatrix}
\frac12\cdot2 & 0 \\
0 & 2\cdot\frac12 \\
\end{pmatrix}=I.
$$

**Check on a vector:** Take

$$
x=\begin{pmatrix}
3 \\
2 \\
\end{pmatrix}.
$$

Then

$$
Sx=\begin{pmatrix}
6 \\
1 \\
\end{pmatrix},\qquad
S^{-1}(Sx)=\begin{pmatrix}
3 \\
2 \\
\end{pmatrix}=x.
$$

The inverse reverses the original scaling.
