# Exercise 7. A Line Relative to a Plane

## Question

For

$$
L:(x,y,z)=(1,1,0)+t(1,-1,0),\qquad \Pi:x+y+z=2,
$$

determine whether the line intersects the plane at one point, is parallel to it, or lies in it. Explain the role of the dot product of the direction vector and the normal vector.

> **Why this exercise:** builds a universal test for the relative position of a line and a plane.

## Solution

The line has point $p=(1,1,0)$ and direction $v=(1,-1,0)$. The plane $x+y+z=2$ has normal $n=(1,1,1)$.

The key dot product is

$$
n\cdot v=1-1+0=0.
$$

Thus the line direction is parallel to the plane. To distinguish a line contained in the plane from a line with no common points, test $p$:

$$
1+1+0=2.
$$

The base point lies in the plane, so **the entire line lies in the plane**.

**Check:** A general point is $(1+t,1-t,0)$, and

$$
(1+t)+(1-t)+0=2
$$

for every real $t$. Hence every point of the line satisfies the plane equation.
