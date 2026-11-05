# Exercise 9. Composing Transformations

## Question

Let

$$
S=
\begin{pmatrix}
2 & 0 \\
0 & 1 \\
\end{pmatrix},\qquad R=
\begin{pmatrix}
0 & -1 \\
1 & 0 \\
\end{pmatrix}.
$$

The matrix $S$ describes nonuniform scaling, while $R$ describes a $90^\circ$ counterclockwise rotation.
For

$$
x=
\begin{pmatrix}
1 \\
2 \\
\end{pmatrix}
$$

compute $RSx$ and $SRx$. Compare the results and explain geometrically why the order of these transformations matters.

> **Why this exercise:** interprets matrix multiplication as composition of transformations.

## Solution

$$
S=\begin{pmatrix}
2 & 0 \\
0 & 1 \\
\end{pmatrix},\quad
R=\begin{pmatrix}
0 & -1 \\
1 & 0 \\
\end{pmatrix},\quad
x=\begin{pmatrix}
1 \\
2 \\
\end{pmatrix}.
$$

Matrix products act on vectors from **right to left**. Scaling first, then rotating gives

$$
Sx=\begin{pmatrix}
2 \\
2 \\
\end{pmatrix},\qquad
RSx=R\begin{pmatrix}
2 \\
2 \\
\end{pmatrix}
=\begin{pmatrix}
-2 \\
2 \\
\end{pmatrix}.
$$

Rotating first, then scaling gives

$$
Rx=\begin{pmatrix}
-2 \\
1 \\
\end{pmatrix},\qquad
SRx=S\begin{pmatrix}
-2 \\
1 \\
\end{pmatrix}
=\begin{pmatrix}
-4 \\
1 \\
\end{pmatrix}.
$$

**Geometric explanation and check:** $S$ doubles only the horizontal coordinate, whereas $R$ rotates the vector $90^\circ$ counterclockwise. After rotation, the direction that is horizontal changes. Hence $RSx\ne SRx$: the order of these two transformations matters.
