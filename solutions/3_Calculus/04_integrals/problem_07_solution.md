# Problem 7. Integration by Parts as Reversing the Product Rule

## Question

Compute

$$
\int xe^x\,dx.
$$

First write the product differentiation rule and, on that basis, explain the meaning of the integration-by-parts formula. Verify the result by differentiation.

> **Why this problem:** it connects a new technique with the familiar product rule.

## Solution

The product differentiation rule is $(uv)'=u'v+uv'$. Integrating both sides and rearranging yields the integration-by-parts formula

$$
\int u\,dv=uv-\int v\,du.
$$

Choose $u=x$ and $dv=e^x\,dx$ because differentiating $x$ reduces it to a constant while integrating the exponential leaves its form unchanged. Then $du=dx$ and $v=e^x$.

$$
\int xe^x\,dx=xe^x-\int e^x\,dx=(x-1)e^x+C.
$$

**Check:** By the product rule, the derivative of $(x-1)e^x+C$ is $e^x+(x-1)e^x=xe^x$.
