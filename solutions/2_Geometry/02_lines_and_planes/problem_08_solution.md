# Exercise 8. Intersection Point of a Line and a Plane

## Question

Find the intersection point of

$$
(x,y,z)=(1,0,2)+t(1,2,-1)
$$

with the plane $x+y+z=4$. Check the result by substituting it into both descriptions.

> **Why this exercise:** practices the most important computational case of the line–plane relationship.

## Solution

The line is

$$
(x,y,z)=(1,0,2)+t(1,2,-1).
$$

Therefore $x=1+t$, $y=2t$, and $z=2-t$. Substitute these expressions into $x+y+z=4$:

$$
(1+t)+2t+(2-t)=4
\quad\Longrightarrow\quad 3+2t=4
\quad\Longrightarrow\quad t=\frac12.
$$

The intersection point is

$$
Q=\left(\frac32,1,\frac32\right).
$$

**Checks:** The line at $t=1/2$ gives $(1+1/2,2(1/2),2-1/2)=Q$. The plane equation also holds because $3/2+1+3/2=4$.

There is exactly one intersection because the line direction $(1,2,-1)$ has nonzero dot product $1+2-1=2$ with the plane normal $(1,1,1)$.
