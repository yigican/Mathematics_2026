# Problem 3. A Box Made from Cardboard

## Question

From a $30\,\mathrm{cm}\times40\,\mathrm{cm}$ sheet, squares of side length $x$ are cut from the corners and the edges are folded up to form an open box.

Write the volume as a function of $x$, determine the physically meaningful domain, and find the value of $x$ for which the volume is greatest.

> **Why this problem:** it develops optimization modeling in a situation where the objective function is not given and must be built independently from the geometry.

## Solution

The folded box has height $x$ and base dimensions $30-2x$ and $40-2x$, all in centimeters. Its volume is

$$
V(x)=x(30-2x)(40-2x)=1200x-140x^2+4x^3.
$$

The physical domain is $0<x<15$, since all three dimensions must be positive. At the two endpoints of the closed extension, the volume is zero.

Differentiate and solve for stationary points:

$$
V'(x)=1200-280x+12x^2=4(3x^2-70x+300),
$$

$$
x=\frac{35\pm5\sqrt{13}}3.
$$

Only the smaller root $x_*=(35-5\sqrt{13})/3\approx5.6574$ cm is in the physical domain; the larger root is approximately $17.68$ cm. The derivative changes from positive to negative at $x_*$, making it the global maximum.

**Result:** The cut size is approximately $5.66$ cm; the base measures approximately $18.69$ by $28.69$ cm. The maximum volume is $(35000+13000\sqrt{13})/27\approx3032.30$ cubic centimeters.

**Check:** $V''(x_*)=24x_*-280=-40\sqrt{13}<0$. Direct substitution in the original volume formula yields the same numerical maximum.
