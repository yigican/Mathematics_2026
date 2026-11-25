# Problem 4. A Quotient and Domain Control

## Question

For

$$
f(x)=\frac{x^2+1}{x-1}
$$

determine the domain, compute the derivative, simplify the result, and explain why the restriction $x\neq1$ remains important.

> **Why this problem:** it practices the quotient rule together with domain control.

## Solution

The denominator vanishes at $1$, so the domain is $\mathbb R\setminus\{1\}$. Using the quotient rule,

$$
f'(x)=\frac{2x(x-1)-(x^2+1)}{(x-1)^2}
=\frac{x^2-2x-1}{(x-1)^2}.
$$

The restriction $x\neq1$ remains because the original function is undefined there, as is the derivative formula.

**Check:** Polynomial division gives $f(x)=x+1+2/(x-1)$. Differentiating yields $1-2/(x-1)^2$, equivalent to the result above.
