# Problem 14. Continuity and Differentiability of a Piecewise Function

## Question

Investigate the behavior at $x=0$ of

$$
f(x)=
\begin{cases}
x^2,&x\ge0, \\
ax,&x<0. \\
\end{cases}
$$

For which values of $a$ is the function continuous? For which values do the one-sided derivatives exist and agree? For which value of $a$ is the function differentiable? Explain why continuity alone is not sufficient.

> **Why this problem:** it requires an organized argument and a clear distinction between two concepts.

## Solution

At zero, $f(0)=0$. The left limit is $\lim_{x\to0^-}ax=0$, and the right limit is $\lim_{x\to0^+}x^2=0$. The function is continuous for every $a\in\mathbb R$.

Using the one-sided difference quotients,

$$
f'_-(0)=\lim_{h\to0^-}\frac{ah}{h}=a,
$$

$$
f'_+(0)=\lim_{h\to0^+}\frac{h^2}{h}=0.
$$

Both one-sided derivatives exist for every real $a$, but they agree only for $a=0$. Thus differentiability at zero holds exactly when $a=0$.

**Check:** With $a=1$, the function is still continuous but the left slope is $1$ and the right slope is $0$. This illustrates why continuity alone does not imply differentiability.
