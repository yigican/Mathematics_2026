# Problem 15. Find the Error in the Monotonicity Analysis

## Question

For the function

$$
f(x)=x^3-3x
$$

the derivative was correctly computed as

$$
f'(x)=3(x-1)(x+1).
$$

However, a student wrote the following conclusion:

> The derivative is positive between its zeros and negative outside them. Therefore, the function is decreasing on $(-\infty,-1)\cup(1,\infty)$, increasing on $(-1,1)$, has a local minimum at $x=-1$, and a local maximum at $x=1$.

1. Without differentiating again, explain why merely identifying the zeros of the derivative does not justify the stated sign chart, and find the error in the student's reasoning.
2. Construct the correct sign chart for $f'(x)$.
3. Give the correct intervals of monotonicity and the character of the extrema.
4. In each of the three intervals, choose one simple test point and show that the sign of the derivative confirms your classification.

> **Why this problem:** it teaches how to diagnose an error in a completed argument and shows that a correct derivative formula is not enough if its sign is interpreted incorrectly.

## Solution

The zeros alone identify possible sign-change locations, but do not establish the sign on the intervals. The student reversed the actual signs. Since the coefficient $3$ is positive, the product is positive when both factors have the same sign and negative when they have opposite signs.

| Interval | $x-1$ | $x+1$ | $f'(x)$ | Behavior |
|---|---|---|---|---|
| $(-\infty,-1)$ | $-$ | $-$ | $+$ | Increasing |
| $(-1,1)$ | $-$ | $+$ | $-$ | Decreasing |
| $(1,\infty)$ | $+$ | $+$ | $+$ | Increasing |

At $x=-1$, the derivative changes from positive to negative, giving a local maximum $(-1,2)$. At $x=1$, it changes from negative to positive, giving a local minimum $(1,-2)$.

**Verification using one test point per interval:**

$$
f'(-2)=3(-3)(-1)=9>0,
$$

$$
f'(0)=3(-1)(1)=-3<0,
$$

$$
f'(2)=3(1)(3)=9>0.
$$

These values confirm the corrected sign chart without differentiating again.
