# Problem 10. A Cable Through Water and Land

## Question

Point $A$ lies on one bank of a river of width $100$ m, and point $B$ lies on the other bank, $500$ m along the bank from the point directly opposite $A$.

The cost per meter of cable underwater is twice the cost per meter of cable on land.

Build a cost function depending on the point where the cable comes out of the water, determine the domain, and find the solution that minimizes the cost.

> **Why this problem:** it checks whether the student can independently translate a spatial description and two different costs into a single function to be optimized.

## Solution

Let $O$ be the point directly opposite $A$ on the other bank, and choose the exit point $P$ between $O$ and $B$. Let $x=OP$ in meters. An exit outside the segment cannot be optimal because moving it to the nearer endpoint reduces the land distance and does not increase the underwater distance. Thus $0\le x\le500$.

The underwater length is $\sqrt{10000+x^2}$ and land length is $500-x$. If $c>0$ is the cost per meter on land, the total cost is

$$
C(x)=c(2\sqrt{10000+x^2}+500-x).
$$

Its derivative is

$$
C'(x)=c\left(\frac{2x}{\sqrt{10000+x^2}}-1\right).
$$

Setting it equal to zero gives $2x=\sqrt{10000+x^2}$. Both sides are nonnegative, so squaring gives $3x^2=10000$, hence

$$
x_*=\frac{100}{\sqrt3}\approx57.74.
$$

**Verification:** $C''(x)=20000c/(10000+x^2)^{3/2}>0$, so this interior critical point is the global minimum. Its cost divided by $c$ is $500+100\sqrt3\approx673.21$, below the endpoint costs $700$ and $2\sqrt{260000}\approx1019.80$.

The cable should emerge approximately $57.74$ m toward $B$ from $O$. Its underwater length is approximately $115.47$ m, and its land length $442.26$ m.
