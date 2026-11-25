# Problem 5. An Exponential Function with a Maximum

## Question

Analyze the monotonicity and extrema of

$$
f(x)=xe^{-x}.
$$

Also examine the behavior as $x\to\infty$ and explain how the limit affects the shape of the graph on the right-hand side.

> **Why this problem:** it combines the derivative with a limit in the description of the global behavior of a function.

## Solution

Use the product rule:

$$
f'(x)=e^{-x}-xe^{-x}=e^{-x}(1-x).
$$

The exponential is positive. Thus $f$ increases on $(-\infty,1)$ and decreases on $(1,\infty)$. Its unique global maximum occurs at $x=1$, with $f(1)=1/e$.

For the right-end behavior,

$$
\lim_{x\to\infty}xe^{-x}
=\lim_{x\to\infty}\frac{x}{e^x}=0.
$$

The last limit follows, for example, from l'Hôpital's rule. For positive $x$, the function remains positive, so after its maximum it approaches the horizontal asymptote $y=0$ from above. At the left end $xe^{-x}\to-\infty$.

**Check:** $f''(x)=e^{-x}(x-2)$, so $f''(1)=-1/e<0$, consistent with a maximum.
