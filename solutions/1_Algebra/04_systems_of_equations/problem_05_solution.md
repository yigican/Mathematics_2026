# Exercise 5. Row Echelon Form and Number of Solutions

## Question

For the augmented matrix

$$
\begin{pmatrix}
1 & 2 & -1 & \mid & 3 \\
0 & 1 & 2 & \mid & 1 \\
0 & 0 & 0 & \mid & 0 \\
\end{pmatrix}
$$

determine the number of solutions and write them in parametric form. Explain how you know how many variables may be chosen freely.

> **Why this exercise:** teaches how to read information about solutions directly from row echelon form.

## Solution

The given augmented matrix is already in row echelon form:

$$
\begin{pmatrix}
1 & 2 & -1 & \mid & 3 \\
0 & 1 & 2 & \mid & 1 \\
0 & 0 & 0 & \mid & 0 \\
\end{pmatrix}.
$$

The second row means

$$
y+2z=1,\qquad y=1-2z.
$$

The first row gives

$$
x+2y-z=3.
$$

There are pivots in the $x$- and $y$-columns but not in the $z$-column, so choose $z=t$ freely. Substitute $y=1-2t$:

$$
x=3-2(1-2t)+t=1+5t.
$$

**Answer:**

$$
(x,y,z)=(1+5t,1-2t,t),\qquad t\in\mathbb{R}.
$$

There are **infinitely many solutions** with exactly one free variable.

**Check:** In row 2, $(1-2t)+2t=1$. In row 1, $(1+5t)+2(1-2t)-t=3$. The zero row is always satisfied.
