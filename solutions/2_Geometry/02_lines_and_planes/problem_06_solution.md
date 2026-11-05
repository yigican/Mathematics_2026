# Exercise 6. Angle Between Planes

## Question

Given

$$
\Pi_1:x+y+z=1,\qquad \Pi_2:x-y=2.
$$

First use the normal vectors to decide whether the planes are parallel. If not, compute the angle between them and explain why the normal vectors alone are enough for this calculation.

> **Why this exercise:** focuses attention on one mechanism—using normals to analyze position and angle—without also introducing the construction of the intersection line.

## Solution

The plane equations are

$$
\Pi_1:x+y+z=1,\qquad
\Pi_2:x-y=2.
$$

Their normal vectors are $n_1=(1,1,1)$ and $n_2=(1,-1,0)$.

The dot product is

$$
n_1\cdot n_2=1(1)+1(-1)+1(0)=0.
$$

Since both normals are nonzero and perpendicular, they are not parallel, and the planes meet at a right angle.

$$
\cos\theta=\frac{|n_1\cdot n_2|}{\|n_1\|\|n_2\|}=0,
\qquad\theta=90^\circ.
$$

**Explanation and check:** The angle between planes is measured using the angle between their normals (taking the acute angle). A zero dot product directly verifies the perpendicularity without constructing the intersection line.
