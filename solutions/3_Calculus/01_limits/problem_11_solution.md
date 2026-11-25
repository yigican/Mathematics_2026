# Exercise 11. An n-th Root

## Question

Compute

$$
\lim_{n\to\infty}\sqrt[n]{5^n+2^n}.
$$

Explain which term dominates and why the transformation looks different from the case of a quotient of polynomials.

> **Why this exercise:** extends the idea of dominance to exponential expressions.

## Solution

Factor out the dominant exponential:

$$
\sqrt[n]{5^n+2^n}=5\left(1+(2/5)^n\right)^{1/n}.
$$

Since $1\le(1+(2/5)^n)^{1/n}\le2^{1/n}\to1$, the squeeze theorem gives limit $5$. Exponential dominance is extracted by factoring $5^n$ and taking an $n$th root, not dividing by a polynomial power.
