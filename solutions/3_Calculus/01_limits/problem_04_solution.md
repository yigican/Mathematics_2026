# Exercise 4. Powers and Oscillation

## Question

Analyze

$$
\left(\frac23\right)^n,\qquad \left(\frac32\right)^n,\qquad (-1)^n,\qquad \frac{(-1)^n}{n}.
$$

For each sequence, describe the type of behavior and justify your answer.

> **Why this exercise:** organizes the basic types of sequence behavior and shows that oscillation does not always rule out convergence.

## Solution

Because $0<2/3<1$, $(2/3)^n\to0$. Because $3/2>1$, $(3/2)^n\to+\infty$. The sequence $(-1)^n$ alternates between $1$ and $-1$, so it has no limit. Finally,

$$
-\frac1n\le\frac{(-1)^n}{n}\le\frac1n
$$

and both bounds tend to zero; hence the oscillating final sequence converges to $0$ by the squeeze theorem.
