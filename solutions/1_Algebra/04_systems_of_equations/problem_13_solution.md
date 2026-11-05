# Exercise 13. Does Every Equation Add New Information?

The system is

$$
x_1+x_2=10,\qquad
x_2+x_3=8,\qquad
x_1-x_3=2.
$$

Subtract the second equation from the first:

$$
(x_1+x_2)-(x_2+x_3)=10-8
\quad\Longrightarrow\quad x_1-x_3=2.
$$

This is exactly the third equation. Therefore it is **redundant**; only the first two equations give independent information.

Let $x_2=t$ be free. Then $x_1=10-t$ and $x_3=8-t$.

**Answer:**

$$
(x_1,x_2,x_3)=(10-t,t,8-t),\qquad t\in\mathbb{R}.
$$

There are infinitely many solutions.

**Check:** The first equation gives $(10-t)+t=10$, the second gives $t+(8-t)=8$, and the third gives $(10-t)-(8-t)=2$, for every $t$.
