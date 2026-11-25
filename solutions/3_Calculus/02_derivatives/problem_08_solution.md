# Problem 8. Two Exponential Functions

## Question

For

$$
f(x)=e^{2x-3}+5^x
$$

compute the derivative. Explain why the factor $2$ appears in the first term and why $\ln5$ appears in the second.

> **Why this problem:** it organizes two different mechanisms that produce additional factors.

## Solution

For the first term, apply the chain rule to $e^u$ with $u=2x-3$ and $u'=2$. For the second term, use $5^x=e^{x\ln5}$.

$$
f'(x)=2e^{2x-3}+5^x\ln5.
$$

The factor $2$ comes from the derivative of the exponent $2x-3$, while $\ln5$ comes from rewriting the base-$5$ exponential as a natural exponential.

**Check:** Differentiating $e^{x\ln5}$ directly gives $(\ln5)e^{x\ln5}=(\ln5)5^x$. Both terms are positive, consistent with increasing exponentials.
