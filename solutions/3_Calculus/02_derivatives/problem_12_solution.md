# Problem 12. Several Rules at Once

## Question

For

$$
f(x)=(x^2+1)^3e^x
$$

compute the derivative. Before calculating, write down a plan: which rule applies to the whole expression and which rule applies to one of its factors. Finally, organize the result by factoring out common factors.

> **Why this problem:** it practices the order of decisions when combining familiar differentiation rules.

## Solution

**Plan:** Apply the product rule to the whole expression, and the chain rule to the factor $(x^2+1)^3$.

Set $u=(x^2+1)^3$ and $v=e^x$. Then $u'=6x(x^2+1)^2$ and $v'=e^x$.

$$
f'(x)=6x(x^2+1)^2e^x+(x^2+1)^3e^x.
$$

Factoring out the common factors gives

$$
f'(x)=e^x(x^2+1)^2(x^2+6x+1).
$$

**Check:** Expanding the last bracket as $6x+(x^2+1)$ recovers the two product-rule terms.
