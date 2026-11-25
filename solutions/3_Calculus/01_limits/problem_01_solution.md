# Exercise 1. Dominant Terms in a Sequence

## Question

Compute

$$
\lim_{n\to\infty}\frac{4n^2-3n+1}{2n^2+5n-7}.
$$

Explain why the highest-degree terms determine the result.

> **Why this exercise:** introduces the idea of a dominant term and teaches how to simplify the behavior of expressions for large arguments.

## Solution

Divide numerator and denominator by $n^2$:

$$
\lim_{n\to\infty}\frac{4-3/n+1/n^2}{2+5/n-7/n^2}=\frac42=2.
$$

The lower powers vanish after division by the highest power. The denominator tends to $2\neq0$, justifying the quotient limit.
