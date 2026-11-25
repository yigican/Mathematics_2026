# Problem 3. The Product Rule — Why Is It Needed?

## Question

For

$$
f(x)=(x^2+1)e^x
$$

compute the derivative. Then compare the correct result with the incorrect idea

$$
f'(x)\stackrel{?}{=}(2x)e^x
$$

and explain which term is missing.

> **Why this problem:** it teaches the product rule by analyzing a common mistake.

## Solution

Both factors depend on $x$, so the product rule $(uv)'=u'v+uv'$ is needed. For $u=x^2+1$ and $v=e^x$, their derivatives are $2x$ and $e^x$.

$$
f'(x)=2xe^x+(x^2+1)e^x=e^x(x+1)^2.
$$

The proposed expression omits the term $(x^2+1)e^x$, which comes from differentiating the exponential factor.

**Check:** At zero the correct derivative equals $1$, whereas the proposed expression equals $0$. The definition gives $\lim_{h\to0}((1+h^2)e^h-1)/h=1$ as well.
