# Problem 9. Definite Integral and Geometric Area

## Question

Compute

$$
\int_{-1}^{2}x\,dx.
$$

Then separately compute the areas of the parts of the graph below and above the $x$-axis and explain the difference between the definite integral and geometric area.

> **Why this problem:** it clarifies the difference between signed accumulation and area.

## Solution

By the fundamental theorem of calculus,

$$
\int_{-1}^{2}x\,dx=\left[\frac{x^2}{2}\right]_{-1}^{2}
=2-\frac12=\frac32.
$$

On $[-1,0]$, the graph is below the horizontal axis, so its geometric area is the negative of its signed integral:

$$
A_-=-\int_{-1}^{0}x\,dx=\frac12.
$$

On $[0,2]$, the area is

$$
A_+=\int_0^2x\,dx=2.
$$

The total geometric area is $1/2+2=5/2$, whereas the signed integral is $2-1/2=3/2$.

**Geometric check:** The two regions are triangles with base and height $1$ and $2$, respectively. Their areas are $1/2$ and $2$, confirming the results. The integral subtracts area below the axis, while geometric area is always nonnegative.
