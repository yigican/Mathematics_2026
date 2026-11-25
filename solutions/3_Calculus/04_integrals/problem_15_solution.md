# Problem 15. Recovering a Function from Its Derivative and a Condition

## Question

The function $F$ satisfies

$$
F'(x)=2xe^{x^2}
$$

and

$$
F(0)=3.
$$

1. Recognize the method needed to find the function $F$.
2. Determine the entire family of functions with the given derivative.
3. Use the condition $F(0)=3$ to determine the correct constant.
4. Verify the final result by differentiation and substitution of $x=0$.

> **Why this problem:** it combines recognition of substitution, the meaning of the constant of integration, and an initial condition in one problem, using only mechanisms introduced earlier.

## Solution

The derivative contains the composite exponential $e^{x^2}$ together with the derivative $2x$ of its exponent. Substitution reverses this chain rule. Let $u=x^2$, so $du=2x\,dx$.

$$
F(x)=\int 2xe^{x^2}\,dx=\int e^u\,du=e^{x^2}+C.
$$

This is the full family of antiderivatives on $\mathbb R$. Apply the initial condition:

$$
F(0)=e^0+C=1+C=3,
$$

which gives $C=2$. Therefore

$$
F(x)=e^{x^2}+2.
$$

**Verification:** Differentiating gives $F'(x)=2xe^{x^2}$ and substituting zero gives $F(0)=1+2=3$. Both requirements hold.
