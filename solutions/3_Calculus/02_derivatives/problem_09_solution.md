# Problem 9. A Logarithm and the Chain Rule

## Question

For

$$
f(x)=\ln(x^2+1)
$$

compute the derivative. Then determine the sign of $f'(x)$ for $x<0$, $x=0$, and $x>0$, and describe qualitatively how the function behaves around zero.

> **Why this problem:** it connects differentiation with sign analysis and the behavior of a function.

## Solution

The logarithm is defined for every real $x$ because $x^2+1>0$. Its outer derivative is $1/u$, and the inner derivative is $2x$. Hence

$$
f'(x)=\frac{2x}{x^2+1}.
$$

The denominator is strictly positive. Therefore $f'(x)<0$ for $x<0$, $f'(0)=0$, and $f'(x)>0$ for $x>0$.

The graph decreases toward zero, reaches a minimum at $(0,0)$, and increases afterward.

**Check:** Since $x^2+1\ge1$, $\ln(x^2+1)\ge0$, with equality only at zero.
