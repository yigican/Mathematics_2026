# Exercise 12. Exponential Function Limit

## Question

Compute

$$
\lim_{x\to0}(1+3x)^{1/x}.
$$

Connect the result with the limit from Exercise 5 and show the appropriate transformation.

> **Why this exercise:** teaches how to recognize the classical pattern after a transformation.

## Solution

Let $u=3x$. Then

$$
(1+3x)^{1/x}=\left((1+u)^{1/u}\right)^3\to e^3
$$

as $x\to0$ through values for which $1+3x>0$. This uses the standard exponential limit $\lim_{u\to0}(1+u)^{1/u}=e$, the continuous-variable analogue of Exercise 5.
