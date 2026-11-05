# Exercise 3. Swapping Two Rows

## Question

For

$$
A=
\begin{pmatrix}
1 & 2 & 0 \\
0 & 3 & 1 \\
2 & 1 & 1 \\
\end{pmatrix}
$$

compute $\det A$. Then form a matrix $B$ by swapping the first and second rows of $A$.

First predict $\det B$ using a determinant property, and then verify your prediction by calculation.

> **Why this exercise:** gives a second classical calculation with a $3\times3$ determinant while teaching the precise effect of a row swap on the sign of the determinant.

## Solution

$$
A=\begin{pmatrix}
1 & 2 & 0 \\
0 & 3 & 1 \\
2 & 1 & 1 \\
\end{pmatrix}.
$$

Expand the determinant of $A$ along the first row:

$$
\begin{aligned}
\det A
&=1(3\cdot1-1\cdot1)-2(0\cdot1-1\cdot2)\\
&=2-2(-2)=6.
\end{aligned}
$$

Interchanging the first two rows gives

$$
B=\begin{pmatrix}
0 & 3 & 1 \\
1 & 2 & 0 \\
2 & 1 & 1 \\
\end{pmatrix}.
$$

**Prediction:** Swapping any two rows reverses the sign of the determinant, so $\det B=-6$.

**Verification:** Expanding along the first row of $B$,

$$
\begin{aligned}
\det B
&=0-3(1\cdot1-0\cdot2)+1(1\cdot1-2\cdot2)\\
&=-3+(1-4)=-6.
\end{aligned}
$$

Thus $\det B=-\det A$, as predicted.
