# Exercise 13. Fundamental Trigonometric Limit

## Question

Using

$$
\lim_{x\to0}\frac{\sin x}{x}=1,
$$

compute

$$
\lim_{x\to0}\frac{\sin5x}{x},\qquad \lim_{x\to0}\frac{\sin2x}{\sin3x}.
$$

In each case, show how you reduce the expression to the fundamental limit.

> **Why this exercise:** teaches how to reduce new limits to one known pattern.

## Solution

Use $\sin t/t\to1$:

$$
\frac{\sin5x}{x}=5\frac{\sin5x}{5x}\to5.
$$

Likewise,

$$
\frac{\sin2x}{\sin3x}
=\frac23\frac{\sin2x/(2x)}{\sin3x/(3x)}\to\frac23.
$$

Both are reduced to the same fundamental trigonometric limit.
