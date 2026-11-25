# Problem 2. Powers, Roots, and the Domain

## Question

For

$$
f(x)=2\sqrt{x}-\frac{3}{x^2}+x^{3/2}
$$

1. rewrite the function using powers,
2. determine the domain,
3. compute the derivative,
4. compare the domain of the function with the domain of its derivative.

> **Why this problem:** it teaches how to rewrite different forms so that the power rule can be applied and how to keep track of the domain.

## Solution

The power form is $f(x)=2x^{1/2}-3x^{-2}+x^{3/2}$. The square root requires $x\ge0$, and the denominator excludes zero. Thus the domain is $(0,\infty)$.

By the power rule,

$$
f'(x)=x^{-1/2}+6x^{-3}+\frac32x^{1/2}.
$$

Equivalently, $f'(x)=1/\sqrt{x}+6/x^3+(3/2)\sqrt{x}$. The derivative exists for every positive $x$, so its domain is also $(0,\infty)$.

**Check:** The exponent of each term decreases by one and its coefficient is multiplied by its original exponent; in particular $(-3)(-2)=6$.
