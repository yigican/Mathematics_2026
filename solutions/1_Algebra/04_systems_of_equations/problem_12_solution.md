# Exercise 12. Homogeneous System

$$
\begin{cases}
x+2y-z=0,\\
2x+4y-2z=0,\\
x-y+2z=0.
\end{cases}
$$

The second equation is twice the first, so it adds no new condition. Subtract the first equation from the third:

$$
(x-y+2z)-(x+2y-z)=0
\quad\Longrightarrow\quad
-3y+3z=0.
$$

Hence $y=z$. Choose the free parameter $z=t$; then $y=t$. The first equation becomes $x+2t-t=0$, so $x=-t$.

**Answer:**

$$
(x,y,z)=(-t,t,t),\qquad t\in\mathbb{R}.
$$

There are infinitely many solutions.

**Check:** For every $t$, the first equation gives $-t+2t-t=0$, the second is twice this, and the third gives $-t-t+2t=0$. Taking $t=0$ yields $(0,0,0)$, which always solves any homogeneous system because all right-hand sides are zero.
