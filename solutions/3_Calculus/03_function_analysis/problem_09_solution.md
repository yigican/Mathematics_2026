# Problem 9. An Oblique Asymptote

## Question

Analyze the asymptotes of

$$
f(x)=\frac{x^2+1}{x-1}.
$$

Perform polynomial division and explain why the remainder term vanishes for large $|x|$.

> **Why this problem:** it teaches how to recognize an oblique asymptote and interpret the decomposition of a function.

## Solution

The domain excludes $x=1$. Polynomial division gives

$$
x^2+1=(x-1)(x+1)+2,
$$

so

$$
f(x)=x+1+\frac2{x-1}.
$$

The remainder term tends to zero as $x\to\pm\infty$ because its numerator is constant and the denominator grows in absolute value. Thus the oblique asymptote is $y=x+1$ at both ends.

At $x=1$, the remainder term tends to $-\infty$ from the left and $+\infty$ from the right. Therefore $x=1$ is a vertical asymptote. There is no horizontal asymptote because the linear part is unbounded.

**Check:** Multiplying the division identity back gives $x^2-1+2=x^2+1$. The difference from the proposed oblique asymptote is exactly $2/(x-1)$, whose limit is zero.
