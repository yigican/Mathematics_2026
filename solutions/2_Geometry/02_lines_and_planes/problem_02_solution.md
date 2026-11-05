# Exercise 2. A Line in Space

## Question

Given

$$
L:(x,y,z)=(2,-1,3)+t(1,2,-2).
$$

State a point on the line and its direction vector, check whether $P=(4,3,-1)$ lies on $L$, and find the point corresponding to $t=-1$.

> **Why this exercise:** reinforces the interpretation of parametric form as “point + direction.”

## Solution

The line is

$$
L:(x,y,z)=(2,-1,3)+t(1,2,-2).
$$

Its base point is $(2,-1,3)$ (when $t=0$), and its direction vector is $(1,2,-2)$.

To test $P=(4,3,-1)$, use the first coordinate: $2+t=4$ gives $t=2$. The other coordinates at this value are

$$
-1+2(2)=3,\qquad 3-2(2)=-1.
$$

Both agree, so $P$ lies on $L$.

At $t=-1$, the point is

$$
(2,-1,3)-(1,2,-2)=(1,-3,5).
$$

**Check:** Substituting $t=-1$ into each coordinate gives $(1,-3,5)$, while the single parameter $t=2$ consistently reproduces all three coordinates of $P$.
