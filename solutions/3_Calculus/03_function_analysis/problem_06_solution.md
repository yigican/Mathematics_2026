# Problem 6. A Logarithmic Function

## Question

Analyze the domain, zero, and monotonicity of

$$
f(x)=\ln x-x+1.
$$

Explain why the analysis must begin with the domain.

> **Why this problem:** it reinforces the role of the domain and derivative in the analysis of a logarithmic function.

## Solution

The logarithm requires $x>0$. This domain must be established first because the derivative and the zero search are meaningful only where the original function exists.

$$
f'(x)=\frac1x-1=\frac{1-x}{x}.
$$

The derivative is positive on $(0,1)$ and negative on $(1,\infty)$. Thus the function increases to its global maximum at $x=1$ and decreases afterward. Since $f(1)=\ln1-1+1=0$, the maximum is zero and the only zero is $x=1$.

**Check:** $f''(x)=-1/x^2<0$ on the entire domain, confirming strict concavity and the uniqueness of the maximum. Also $\lim_{x\to0^+}f(x)=-\infty$ and $\lim_{x\to\infty}f(x)=-\infty$.
