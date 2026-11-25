# Problem 13. An Integral Depending on the Upper Limit

## Question

Let

$$
F(x)=\int_0^x(t^2+1)\,dt.
$$

Determine $F(x)$, compute $F'(x)$, and compare the result with the integrand. Explain in your own words why the height of the function describes the local rate of increase of the accumulated area.

> **Why this problem:** it connects differentiation and integration through the idea of accumulation.

## Solution

Integrate with respect to $t$ while keeping the upper limit variable:

$$
F(x)=\left[\frac{t^3}{3}+t\right]_0^x
=\frac{x^3}{3}+x.
$$

Differentiating gives

$$
F'(x)=x^2+1.
$$

This is precisely the integrand evaluated at the upper limit, as stated by the fundamental theorem of calculus. As the upper limit increases by a small amount $h$, the new signed area is approximately the height $x^2+1$ times $h$. Thus the height describes the local accumulation rate.

**Check:** $F(0)=0$ and, for $h\neq0$,

$$
\frac{F(x+h)-F(x)}h=x^2+xh+\frac{h^2}{3}+1.
$$

Its limit as $h\to0$ is $x^2+1$, confirming the local-rate interpretation directly.
