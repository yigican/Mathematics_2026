# Problem 6. Average Value of a Function

## Question

Compute the average value of the function

$$
f(x)=x^2
$$

on the interval $[0,3]$.

Find a point $c\in[0,3]$ for which $f(c)$ is equal to this average value, and interpret the result geometrically.

> **Why this problem:** it gives the integral the interpretation of an average value and connects the numerical result with a level of the function on the graph.

## Solution

The average value is the integral divided by the length of the interval:

$$
f_{\mathrm{avg}}=\frac13\int_0^3x^2\,dx
=\frac13\left[\frac{x^3}{3}\right]_0^3=3.
$$

The condition $f(c)=3$ means $c^2=3$. The only solution in $[0,3]$ is $c=\sqrt3$.

Geometrically, the horizontal line $y=3$ meets the graph at $(\sqrt3,3)$ and forms a rectangle of width $3$ and height $3$ with the same area as the region under the curve.

**Check:** Both areas equal $9$ and $f(\sqrt3)=3$.
