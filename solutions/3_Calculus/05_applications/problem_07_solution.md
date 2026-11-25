# Problem 7. Exponential Growth

## Question

Assume the model

$$
N(t)=N_0e^{kt},\qquad k>0.
$$

1. Verify by differentiation that the model satisfies the relation $N'(t)=kN(t)$.
2. Find the population doubling time.
3. Explain why the doubling time does not depend on $N_0$.

> **Why this problem:** it shows the connection between the exponential function and a growth rate proportional to the current value, without introducing a separate technique for solving differential equations.

## Solution

For a positive initial population $N_0$, differentiating the exponential by the chain rule gives

$$
N'(t)=N_0ke^{kt}=kN(t).
$$

Let $T$ be the doubling time. The condition $N(t+T)=2N(t)$ implies

$$
N_0e^{kt}e^{kT}=2N_0e^{kt}.
$$

Cancel the positive current population to obtain $e^{kT}=2$, and therefore

$$
T=\frac{\ln2}{k}.
$$

The initial population cancels because doubling is a relative change, and the growth factor depends only on $k$ and the elapsed time.

**Check:** $N(t+T)=N(t)e^{\ln2}=2N(t)$; also $T>0$ since $k>0$.
