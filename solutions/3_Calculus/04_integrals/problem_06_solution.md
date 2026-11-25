# Problem 6. When Does a Logarithm Appear from an Integral?

## Question

Compute

$$
\int\frac{2x}{x^2+5}\,dx.
$$

Identify the denominator as a candidate for substitution, compare the numerator with its derivative, and explain the source of the logarithm in the result.

> **Why this problem:** it teaches how to recognize the structure “derivative of the denominator over the denominator.”

## Solution

The denominator suggests substitution because its derivative equals the numerator. Set $u=x^2+5$, so $du=2x\,dx$. Since $u\ge5$, the transformed integral is

$$
\int\frac{du}{u}=\ln u+C.
$$

The logarithm appears because the derivative of $\ln u$ is $1/u$ for positive $u$. Substituting back gives

$$
\int\frac{2x}{x^2+5}\,dx=\ln(x^2+5)+C.
$$

The domain is all real $x$.

**Check:** Differentiating the result by the chain rule gives $2x/(x^2+5)$, exactly the integrand.
