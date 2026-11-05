# Exercise 11. A Parameter in a System of Three Equations

Start with

$$
\begin{cases}
x+y+z=1,\\
x+ty+z=2,\\
x+y+tz=3.
\end{cases}
$$

Subtract the first equation from the second and third, respectively. This corresponds to $R_2\leftarrow R_2-R_1$ and $R_3\leftarrow R_3-R_1$:

$$
\begin{pmatrix}
1 & 1 & 1 & \mid & 1 \\
0 & t-1 & 0 & \mid & 1 \\
0 & 0 & t-1 & \mid & 2 \\
\end{pmatrix}.
$$

**Case 1: $t\neq1$.** The two lower rows give

$$
y=\frac{1}{t-1},\qquad z=\frac{2}{t-1}.
$$

Using the first equation,

$$
x=1-\frac{1}{t-1}-\frac{2}{t-1}
=\frac{t-4}{t-1}.
$$

There is exactly one solution:

$$
(x,y,z)=\left(\frac{t-4}{t-1},\frac{1}{t-1},\frac{2}{t-1}\right).
$$

**Case 2: $t=1$.** The lower rows become $0=1$ and $0=2$, contradictions. There is no solution.

**No value gives infinitely many solutions.**

**Check:** For $t\neq1$, the first left-hand side is $1$, the second is $1+(t-1)y=2$, and the third is $1+(t-1)z=3$. This verifies all equations and explains why division by $t-1$ was permitted only in Case 1.
