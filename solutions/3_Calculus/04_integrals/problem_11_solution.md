# Problem 11. Choose the Method First

## Question

For each integral, first write which method you choose and how you recognize it, and then compute:

1. $\int\sin(3x)\,dx$,
2. $\int x\ln x\,dx$,
3. $\int\frac{x}{\sqrt{x^2+1}}\,dx$.

> **Why this problem:** it tests the choice of method based on the structure of the problem.

## Solution

**1. Substitution.** The sine argument is $3x$ with constant derivative $3$. Let $u=3x$, $du=3\,dx$.

$$
\int\sin(3x)\,dx=\frac13\int\sin u\,du
=-\frac13\cos(3x)+C.
$$

Differentiation gives $\sin(3x)$.

**2. Integration by parts.** For $x>0$, differentiating $\ln x$ simplifies it to $1/x$, and integrating $x$ is straightforward. Choose $u=\ln x$, $dv=x\,dx$, so $du=dx/x$ and $v=x^2/2$.

$$
\int x\ln x\,dx=\frac{x^2}{2}\ln x-\frac12\int x\,dx
=\frac{x^2}{2}\ln x-\frac{x^2}{4}+C.
$$

Its derivative is $x\ln x+x/2-x/2=x\ln x$.

**3. Substitution.** The square root contains $x^2+1$, whose derivative is $2x$. Let $u=x^2+1$, $du=2x\,dx$.

$$
\int\frac{x}{\sqrt{x^2+1}}\,dx
=\frac12\int u^{-1/2}\,du
=\sqrt{x^2+1}+C.
$$

The domain is $\mathbb R$. Differentiating the square root gives $x/\sqrt{x^2+1}$, confirming the result.
