# Exercise 14. Contrast: Intersection and Parallelism

## Question

From the point $P=(0,0,1)$, two lines are drawn with direction vectors

$$
v_1=(2,1,-1),\qquad v_2=(2,1,0).
$$

For each line, analyze its position relative to the plane $z=0$.

For the line that intersects the plane, find the intersection point. For the other line, explain how you can recognize parallelism without solving an equation.

> **Why this exercise:** compares two very similar data sets that lead to different outcomes and forces recognition of the geometric condition before calculation.

## Solution

Both lines begin at $P=(0,0,1)$, and the plane $z=0$ has normal $n=(0,0,1)$.

**First line:** Its direction is $v_1=(2,1,-1)$, so

$$
n\cdot v_1=-1\neq0.
$$

The line must meet the plane once. Its parametrization is $(2t,t,1-t)$. Requiring $z=0$ gives $t=1$ and the intersection

$$
Q=(2,1,0).
$$

**Second line:** Its direction is $v_2=(2,1,0)$, and

$$
n\cdot v_2=0.
$$

The direction is parallel to the plane, while the base point has $z=1\neq0$. Therefore this line is parallel to the plane and never meets it.

**Check:** On the first line, $(2,1,0)$ occurs at $t=1$. On the second line every point has $z=1$, so no point can satisfy $z=0$.
