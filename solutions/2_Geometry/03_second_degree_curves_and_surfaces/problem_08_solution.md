# Exercise 8. Sphere

## Question

Reduce

$$
x^2+y^2+z^2-4x+2y-6z-2=0
$$

to canonical form. Find the center and radius. Give two points on the sphere and check them in the equation.

> **Why this exercise:** transfers the technique known from circles from two dimensions to three.

## Solution

Complete the squares in

$$
x^2+y^2+z^2-4x+2y-6z-2=0.
$$

$$
\begin{aligned}
(x^2-4x)+(y^2+2y)+(z^2-6z)&=2\\
(x-2)^2-4+(y+1)^2-1+(z-3)^2-9&=2\\
(x-2)^2+(y+1)^2+(z-3)^2&=16.
\end{aligned}
$$

The center is $C=(2,-1,3)$ and radius $r=4$.

Choose the points $P=(6,-1,3)$ and $Q=(2,3,3)$, each four units from the center along one coordinate direction.

**Canonical-form checks:**

$$
(6-2)^2+0+0=16,\qquad
0+(3+1)^2+0=16.
$$

**Original-form checks:**

$$
36+1+9-24-2-18-2=0,\qquad
4+9+9-8+6-18-2=0.
$$

Thus both points lie on the sphere in both forms.
