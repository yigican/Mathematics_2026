# Exercise 13. Closest Point on a Plane

## Question

Find the point on the plane $x+2y+2z=4$ closest to $P=(3,0,0)$. Give the distance and check that the segment joining the two points is perpendicular to the plane.

> **Why this exercise:** combines projection, distance, and the normal direction in one problem.

## Solution

The plane $x+2y+2z=4$ has normal $n=(1,2,2)$, with $\|n\|^2=1+4+4=9$. For $P=(3,0,0)$,

$$
n\cdot P-4=3-4=-1.
$$

The perpendicular projection onto the plane is

$$
\begin{aligned}
Q&=P-\frac{n\cdot P-4}{\|n\|^2}\,n\\
&=(3,0,0)+\frac19(1,2,2)\\
&=\left(\frac{28}{9},\frac29,\frac29\right).
\end{aligned}
$$

The shortest distance is

$$
d(P,\Pi)=\frac{|n\cdot P-4|}{\|n\|}=\frac13.
$$

**Checks:** $Q$ lies on the plane since $28/9+2(2/9)+2(2/9)=4$. Moreover,

$$
Q-P=\frac19(1,2,2)=\frac19n,
$$

so the segment $PQ$ is perpendicular to the plane. Its length is $(1/9)\|n\|=1/3$.
