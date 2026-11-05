# Exercise 9. A System from a Sum Condition

The conditions are

$$
x+y=10,\qquad 2x+5y=32.
$$

From the first equation, $x=10-y$. Substitute this into the second:

$$
2(10-y)+5y=32
\quad\Longrightarrow\quad
20+3y=32
\quad\Longrightarrow\quad y=4.
$$

Then $x=10-4=6$.

**Answer:** $(x,y)=(6,4)$.

**Check:** $6+4=10$ and $2(6)+5(4)=12+20=32$.

**Geometric explanation:** The equations represent two lines with different slopes. Equivalently, their coefficient determinant is

$$
\det\begin{pmatrix}
1 & 1 \\
2 & 5 \\
\end{pmatrix}=5-2=3\neq0.
$$

Thus the lines meet at exactly one point.
