# Problem 7. A Trigonometric Composition

## Question

For

$$
f(x)=\sin(x^2+1)
$$

compute the derivative. Explicitly identify the outer function, the inner function, and the derivative of the inner function. Finally, determine the sign of $f'(0)$.

> **Why this problem:** it reinforces the chain rule in a different type of composition.

## Solution

The outer function is $g(u)=\sin u$, so $g'(u)=\cos u$. The inner function is $u(x)=x^2+1$, with $u'(x)=2x$.

By the chain rule,

$$
f'(x)=2x\cos(x^2+1).
$$

At zero, $f'(0)=0$; it is neither positive nor negative.

**Check:** The original function is even and differentiable, so its derivative at zero must be zero.
