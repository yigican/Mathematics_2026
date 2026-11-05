# Exercise 10. A Polynomial Through Three Points

## Question

Find a polynomial $p(x)=ax^2+bx+c$ whose graph passes through $(0,1)$, $(1,3)$, and $(2,9)$. Reduce the problem to a system of equations and check the result by substituting all three points.

> **Why this exercise:** shows that finding unknown coefficients can be reduced to solving a linear system.

## Solution

Let $p(x)=ax^2+bx+c$. The three points impose the equations

$$
\begin{cases}
c=1,\\
a+b+c=3,\\
4a+2b+c=9.
\end{cases}
$$

These are linear in the unknown coefficients $a,b,c$. Using $c=1$, the remaining equations become

$$
a+b=2,\qquad 4a+2b=8.
$$

Divide the second equation by $2$ to obtain $2a+b=4$. Subtract $a+b=2$:

$$
a=2,\qquad b=0,\qquad c=1.
$$

**Answer:**

$$
p(x)=2x^2+1.
$$

**Check at each point:**

$$
p(0)=1,\qquad p(1)=2+1=3,\qquad p(2)=2\cdot4+1=9.
$$

All three required points lie on the graph. The independent equations determine the coefficients uniquely.
