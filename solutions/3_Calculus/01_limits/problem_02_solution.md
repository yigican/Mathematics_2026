# Exercise 2. Different Growth Rates

## Question

Compute

$$
\lim_{n\to\infty}\frac{3n+1}{n^2+4},\qquad \lim_{n\to\infty}\frac{2n^3-n}{5n^2+1}.
$$

Compare the two cases and formulate a general observation about the degrees of the polynomials in the numerator and denominator.

> **Why this exercise:** teaches how to compare growth rates and recognize qualitatively different cases.

## Solution

For the first ratio, divide by $n^2$:

$$
\frac{3/n+1/n^2}{1+4/n^2}\to0.
$$

For the second, divide by $n^2$:

$$
\frac{2n-1/n}{5+1/n^2}\to+\infty.
$$

A lower-degree numerator gives limit zero, equal degrees give the ratio of leading coefficients, and a higher-degree numerator grows in magnitude (with sign determined by the leading terms).
