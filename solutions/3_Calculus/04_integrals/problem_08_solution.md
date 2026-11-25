# Problem 8. Choosing the Factors in Integration by Parts

## Question

Compute

$$
\int x\cos x\,dx.
$$

Before calculating, justify why it is convenient to differentiate $x$ and integrate $\cos x$, rather than the other way around.

> **Why this problem:** it teaches that integration by parts requires a deliberate choice of factors.

## Solution

Choose $u=x$ and $dv=\cos x\,dx$. Differentiating $x$ gives the constant $1$, while integrating cosine gives the familiar sine function. The opposite choice would introduce $x^2/2$ multiplied by a trigonometric derivative, making the integral more complicated.

With $du=dx$ and $v=\sin x$, integration by parts gives

$$
\int x\cos x\,dx=x\sin x-\int\sin x\,dx
=x\sin x+\cos x+C.
$$

**Check:** Differentiating yields $\sin x+x\cos x-\sin x=x\cos x$.
