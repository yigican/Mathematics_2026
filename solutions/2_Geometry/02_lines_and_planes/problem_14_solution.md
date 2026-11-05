# Exercise 14. Contrast: Intersection and Parallelism

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
