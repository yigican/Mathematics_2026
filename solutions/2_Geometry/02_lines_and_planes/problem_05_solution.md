# Exercise 5. Relative Position of Two Lines

## Question

Analyze the position of

$$
L_1:(x,y,z)=(1,1,0)+t(1,2,1),
$$

$$
L_2:(x,y,z)=(2,0,1)+s(0,1,-1).
$$

If they intersect, give the intersection point. If not, determine whether they are parallel or skew. Justify the classification.

> **Why this exercise:** teaches how to distinguish qualitatively different relationships between lines in space.

## Solution

The lines are

$$
L_1=(1,1,0)+t(1,2,1),\qquad
L_2=(2,0,1)+s(0,1,-1).
$$

At an intersection, corresponding coordinates would satisfy

$$
1+t=2,\qquad 1+2t=s,\qquad t=1-s.
$$

The first equation gives $t=1$, and the second then gives $s=3$. But the third would require $1=1-3=-2$, a contradiction. Thus the lines do not meet.

Their directions $(1,2,1)$ and $(0,1,-1)$ are not scalar multiples: the first coordinates are $1$ and $0$. Therefore they are not parallel.

**Conclusion:** The two lines are **skew** (nonparallel and nonintersecting in three-dimensional space).

**Check:** The candidate parameters $t=1,s=3$ give points $(2,3,1)$ and $(2,3,-2)$, which differ in the $z$-coordinate.
