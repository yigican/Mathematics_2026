# Exercise 10. Projection of a Point onto a Plane

## Question

Find the orthogonal projection of $P=(2,1,3)$ onto the plane $x+y+z=3$, and then find the reflection of $P$ across this plane. Check that the midpoint of the segment joining the point and its reflection lies on the plane.

> **Why this exercise:** combines the normal, intersection, and distance into the construction of a projection and reflection.

## Solution

The plane $x+y+z=3$ has normal $n=(1,1,1)$ and $d=3$. For $P=(2,1,3)$,

$$
n\cdot P-d=(2+1+3)-3=3,\qquad n\cdot n=3.
$$

The orthogonal projection is

$$
Q=P-\frac{n\cdot P-d}{n\cdot n}\,n
=(2,1,3)-(1,1,1)=(1,0,2).
$$

The reflection is obtained by continuing the same perpendicular distance across the plane:

$$
P'=P-2\frac{n\cdot P-d}{n\cdot n}\,n
=(2,1,3)-2(1,1,1)=(0,-1,1).
$$

**Checks:** $Q$ lies on the plane because $1+0+2=3$. The midpoint is

$$
\frac{P+P'}2=\frac{(2,1,3)+(0,-1,1)}2=(1,0,2)=Q.
$$

Also $P-Q=(1,1,1)$ is parallel to the plane normal, verifying that the projection and reflection are orthogonal.
