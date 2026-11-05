# Exercise 6. Shifted Ellipse

## Question

Reduce

$$
4x^2+9y^2-16x+18y-11=0
$$

to canonical form. Give the center and semiaxis lengths. Check that substituting the coordinates of the center into the left-hand side gives a value consistent with the form you obtained.

> **Why this exercise:** reinforces completing the square and recognizing a shift of the coordinate system.

## Solution

Complete the square in

$$
4x^2+9y^2-16x+18y-11=0.
$$

$$
\begin{aligned}
4(x^2-4x)+9(y^2+2y)&=11\\
4\bigl((x-2)^2-4\bigr)+9\bigl((y+1)^2-1\bigr)&=11\\
4(x-2)^2+9(y+1)^2&=36.
\end{aligned}
$$

Divide by $36$ to obtain canonical form:

$$
\frac{(x-2)^2}{9}+\frac{(y+1)^2}{4}=1.
$$

The center is $(2,-1)$, with horizontal semiaxis $3$ and vertical semiaxis $2$.

**Center check:** Substituting $(2,-1)$ into the **original left-hand side** gives

$$
4(4)+9(1)-16(2)+18(-1)-11=-36.
$$

This is consistent with $4(x-2)^2+9(y+1)^2-36=-36$ at the center. A center lies inside the ellipse, not on its boundary.
