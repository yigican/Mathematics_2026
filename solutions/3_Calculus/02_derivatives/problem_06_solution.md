# Problem 6. Product Rule and Trigonometry

## Question

For

$$
f(x)=x\sin x+\cos x
$$

compute the derivative and simplify the result. Then compute $f'(0)$ and interpret the direction of the tangent line at that point.

> **Why this problem:** it combines the product rule with trigonometric derivatives and geometric interpretation.

## Solution

Apply the product rule to $x\sin x$ and differentiate the remaining cosine term:

$$
f'(x)=\sin x+x\cos x-\sin x=x\cos x.
$$

At $x=0$, $f'(0)=0$. Since $f(0)=1$, the tangent is the horizontal line $y=1$.

**Check:** The two sine terms cancel exactly. In a neighborhood of zero, $\cos x>0$, so the derivative changes from negative to positive, consistent with a horizontal tangent at a local minimum.
