# Exercise 3. A Square Root and Removing an Indeterminate Form

## Question

Compute

$$
\lim_{n\to\infty}\left(\sqrt{n^2+5n}-n\right).
$$

Use the conjugate expression and explain why this transformation removes the difficulty.

> **Why this exercise:** introduces conjugation as a deliberate technique for removing an indeterminate form.

## Solution

Multiply by the conjugate:

$$
\sqrt{n^2+5n}-n=\frac{5n}{\sqrt{n^2+5n}+n}
=\frac5{\sqrt{1+5/n}+1}\to\frac52.
$$

Rationalization changes an indeterminate difference of large quantities into a quotient with a finite nonzero denominator.
