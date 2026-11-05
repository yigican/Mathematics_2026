# Exercise 15. Complete Classification of a Line Relative to a Plane

## Question

Let

$$
L:p+tv,\qquad \Pi:n\cdot x=d.
$$

State the conditions distinguishing the three cases: one intersection point, parallel with no common points, and the line contained in the plane. Then illustrate each case with your own simple numerical example.

> **Why this exercise:** requires formulating a general mathematical criterion instead of carrying out one isolated calculation.

## Solution

Let the line be $L:p+tv$, with $v\neq0$, and the plane be $\Pi:n\cdot x=d$, with $n\neq0$.

Substitute the line into the plane:

$$
n\cdot(p+tv)=d
\quad\Longleftrightarrow\quad
t(n\cdot v)=d-n\cdot p.
$$

This equation gives all three cases:

1. **Exactly one intersection:** $n\cdot v\neq0$. Then $t=(d-n\cdot p)/(n\cdot v)$.
2. **Parallel, no common points:** $n\cdot v=0$ and $n\cdot p\neq d$.
3. **Line contained in the plane:** $n\cdot v=0$ and $n\cdot p=d$.

**Examples:** Use the plane $z=0$, so $n=(0,0,1)$ and $d=0$.

- One intersection: $p=(0,0,1)$ and $v=(0,0,-1)$. The line reaches $(0,0,0)$ at $t=1$.
- Parallel and separate: $p=(0,0,1)$ and $v=(1,0,0)$. Every point has $z=1$.
- Contained: $p=(0,0,0)$ and $v=(1,0,0)$. Every point has $z=0$.

**Check:** The respective values of $(n\cdot v,n\cdot p)$ are $(-1,1)$, $(0,1)$, and $(0,0)$. They satisfy exactly the three criteria above.
