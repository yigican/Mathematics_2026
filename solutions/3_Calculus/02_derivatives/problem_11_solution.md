# Problem 11. Derivative from the Definition

## Question

Using only

$$
f'(x)=\lim_{h\to0}\frac{f(x+h)-f(x)}h,
$$

find the derivative of $f(x)=x^2$. Compare the result with the power rule and indicate where the limit is used in the calculation.

> **Why this problem:** it shows the origin of the power rule and the direct connection between the derivative and a limit.

## Solution

Use the definition with $h\neq0$. The difference quotient simplifies by expanding the square:

$$
\frac{(x+h)^2-x^2}{h}=\frac{2xh+h^2}{h}=2x+h.
$$

Now the limit is used: as $h$ tends to zero, the remaining term $h$ tends to zero. Therefore

$$
f'(x)=\lim_{h\to0}(2x+h)=2x.
$$

**Check:** This agrees with the power rule for $x^2$. Cancellation of $h$ was performed only for nonzero $h$, before taking the limit.
