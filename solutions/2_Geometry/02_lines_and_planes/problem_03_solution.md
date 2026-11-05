# Exercise 3. Plane Through a Point with a Given Normal Vector

## Question

Find the equation of the plane through $P=(1,-2,3)$ and perpendicular to $n=(2,1,-1)$. Check the result by substituting the point $P$ and explain the role of the normal vector.

> **Why this exercise:** shows the basic construction of a plane from a point and a normal vector.

## Solution

Given $P=(1,-2,3)$ and the normal vector $n=(2,1,-1)$, use the point-normal equation

$$
n\cdot((x,y,z)-P)=0.
$$

Thus

$$
2(x-1)+(y+2)-(z-3)=0
\quad\Longrightarrow\quad
2x+y-z+3=0.
$$

**Check:** For $P$, the left side is $2(1)+(-2)-3+3=0$.

**Explanation:** For every point $X$ in the plane, the displacement $X-P$ lies in the plane and must be perpendicular to $n$. That is exactly what the dot-product equation expresses.
