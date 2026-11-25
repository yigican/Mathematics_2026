# Problem 4. Area Between Curves

## Question

Find the area of the region bounded by the graphs

$$
y=x
$$

and

$$
y=x^2.
$$

First find the intersection points and justify which function is greater on the relevant interval.

> **Why this problem:** it teaches that before integrating, one must first determine the geometry of the region and the correct order of the functions.

## Solution

Equating the curves gives $x=x^2$, or $x(x-1)=0$. Hence the intersection points are $(0,0)$ and $(1,1)$. For $0<x<1$, $x-x^2=x(1-x)>0$, so the line is the upper boundary.

The geometric area is the integral of the upper function minus the lower one:

$$
A=\int_0^1(x-x^2)\,dx
=\left[\frac{x^2}{2}-\frac{x^3}{3}\right]_0^1
=\frac16.
$$

**Check:** The difference is nonnegative and at most $1/4$ on this unit-length interval, because $x-x^2=1/4-(x-1/2)^2$. The computed area lies between zero and $1/4$, as required.
