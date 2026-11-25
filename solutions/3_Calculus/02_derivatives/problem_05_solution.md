# Problem 5. The Chain Rule as Working Through Layers

## Question

For

$$
f(x)=(3x^2-2x+1)^5
$$

identify the inner and outer functions, compute their derivatives, and combine the result according to the chain rule. Explain the origin of the additional factor.

> **Why this problem:** it teaches how to recognize the structure of a composition instead of memorizing the rule as a meaningless pattern.

## Solution

The inner function is $u(x)=3x^2-2x+1$, with $u'(x)=6x-2$. The outer function is $g(u)=u^5$, with $g'(u)=5u^4$.

The chain rule multiplies the derivative of the outer function at the inner value by the derivative of the inner function:

$$
f'(x)=5(3x^2-2x+1)^4(6x-2).
$$

The extra factor $6x-2$ measures how quickly the inner expression changes.

**Check:** The inner expression has its minimum at $x=1/3$, where its derivative is zero. The resulting derivative is also zero there, as expected.
