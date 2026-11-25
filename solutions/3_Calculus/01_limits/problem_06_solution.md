# Exercise 6. From a Sequence to a Function — Limit at Infinity

## Question

Compute

$$
\lim_{x\to\infty}\frac{3x^2-x+1}{5x^2+4x-2}.
$$

Compare the method with Exercise 1. Explain what changes when moving from $n$ to a real variable $x$, and what stays the same.

> **Why this exercise:** deliberately transfers a technique from sequence limits to function limits.

## Solution

Divide by $x^2$:

$$
\frac{3-1/x+1/x^2}{5+4/x-2/x^2}\to\frac35.
$$

Exactly as with Exercise 1, dominant powers determine the limit. The only difference is that $x$ ranges over real numbers rather than positive integers; $1/x\to0$ in either case.
