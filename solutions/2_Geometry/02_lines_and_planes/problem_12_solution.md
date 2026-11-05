# Exercise 12. Intersection Line of Two Planes

The planes are

$$
x+y+z=3,\qquad x-y+z=1.
$$

Subtracting the second equation from the first gives $2y=2$, so $y=1$. Then $x+z=2$. Choose $z=t$ and obtain

$$
(x,y,z)=(2-t,1,t)=(2,1,0)+t(-1,0,1).
$$

This is a parametric equation of the intersection line, with direction $v=(-1,0,1)$.

**Second method — cross product:** The plane normals are $n_1=(1,1,1)$ and $n_2=(1,-1,1)$. Their cross product is

$$
n_1\times n_2=(2,0,-2)=-2(-1,0,1).
$$

It is parallel to $v$, as expected: the intersection line must be perpendicular to both plane normals.

**Check:** For a general point $(2-t,1,t)$, the first equation gives $(2-t)+1+t=3$, and the second gives $(2-t)-1+t=1$.
