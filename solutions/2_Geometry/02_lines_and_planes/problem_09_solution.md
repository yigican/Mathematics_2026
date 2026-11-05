# Exercise 9. Distances

## Question

Compute:

1. the distance from $P=(2,3)$ to the line $3x+4y-10=0$,
2. the distance from $Q=(2,-1,3)$ to the plane $2x-2y+z-4=0$.

Compare the two formulas and explain their common connection with the normal direction.

> **Why this exercise:** organizes two similar formulas through one geometric idea.

## Solution

**Point to a line.** For a line $ax+by+c=0$ and point $(x_0,y_0)$, distance is the absolute signed normal component divided by the normal length:

$$
d=\frac{|ax_0+by_0+c|}{\sqrt{a^2+b^2}}.
$$

For $P=(2,3)$ and $3x+4y-10=0$,

$$
d(P,L)=\frac{|3(2)+4(3)-10|}{\sqrt{3^2+4^2}}
=\frac{8}{5}.
$$

**Point to a plane.** For $ax+by+cz+d=0$, divide the absolute equation value by $\sqrt{a^2+b^2+c^2}$. For $Q=(2,-1,3)$ and $2x-2y+z-4=0$,

$$
d(Q,\Pi)=\frac{|2(2)-2(-1)+3-4|}{\sqrt{2^2+(-2)^2+1^2}}
=\frac53.
$$

**Explanation and check:** The normals are $(3,4)$ and $(2,-2,1)$, of lengths $5$ and $3$. Each numerator is the amount by which the point fails to satisfy the equation. Dividing by normal length converts this to perpendicular Euclidean distance.
