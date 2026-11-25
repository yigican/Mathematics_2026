# Problem 4. A Function with Two Vertical Asymptotes

## Question

Analyze

$$
f(x)=\frac1{x^2-1}.
$$

Determine the domain, asymptotes, sign, and monotonicity on the intervals of the domain. Explain why each interval must be analyzed separately.

> **Why this problem:** it practices the analysis of a function on several disjoint intervals.

## Solution

The domain is $\mathbb R\setminus\{-1,1\}$. The denominator vanishes at both excluded points, giving vertical asymptotes $x=-1$ and $x=1$. The one-sided limits are

$$
\lim_{x\to-1^-}f(x)=+\infty,\quad
\lim_{x\to-1^+}f(x)=-\infty,
$$

$$
\lim_{x\to1^-}f(x)=-\infty,\quad
\lim_{x\to1^+}f(x)=+\infty.
$$

As $x\to\pm\infty$, the function tends to zero from above, so $y=0$ is a horizontal asymptote. The numerator is always positive, hence $f(x)>0$ for $|x|>1$ and $f(x)<0$ for $|x|<1$; there are no zeros.

$$
f'(x)=-\frac{2x}{(x^2-1)^2}.
$$

The derivative has the opposite sign to $x$. The function increases on $(-\infty,-1)$ and $(-1,0)$ and decreases on $(0,1)$ and $(1,\infty)$. There is a local maximum at $(0,-1)$.

**Check:** At $x=-2,-1/2,1/2,2$, the derivative signs are $+,+,-,-$. The intervals cannot be joined across the asymptotes because the function is not defined at either boundary.
