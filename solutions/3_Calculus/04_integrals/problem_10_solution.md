# Problem 10. Definite Integral and Checking the Result

## Question

Before carrying out the exact calculation, estimate the possible range of values of the integral

$$
\int_0^2(x^2+1)\,dx,
$$

using

$$
1\le x^2+1\le5
$$

on $[0,2]$. Only then compute the integral exactly, compare the result with the earlier estimate, and explain what type of computational error such a check can detect.

> **Why this problem:** it teaches how to predict the possible range of a result and check the calculation.

## Solution

**Estimate before calculation:** The inequalities $1\le x^2+1\le5$ hold on an interval of length $2$. Integrating these bounds gives

$$
2\le\int_0^2(x^2+1)\,dx\le10.
$$

The exact integral is

$$
\int_0^2(x^2+1)\,dx
=\left[\frac{x^3}{3}+x\right]_0^2
=\frac83+2=\frac{14}{3}.
$$

**Check:** $2<14/3<10$, so the exact result lies in the predicted range. The estimate would detect, for example, a negative result caused by reversing the limits or a result greater than $10$ caused by a missing factor. It is a necessary check but not sufficient to prove that the answer is correct.
