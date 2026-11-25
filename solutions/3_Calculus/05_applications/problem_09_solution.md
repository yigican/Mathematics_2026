# Problem 9. Minimizing the Material Used for a Can

## Question

A closed cylinder has fixed volume $V$.

1. Write the volume constraint.
2. Eliminate one of the variables.
3. Express the surface area as a function of the radius $r$.
4. Find the relation between the height $h$ and the radius $r$ for which the material usage is minimal.

Interpret the obtained relation geometrically.

> **Why this problem:** it requires independent reduction of a problem with two variables to one objective function and control of the geometric constraint.

## Solution

Let $V>0$ be the fixed volume, $r>0$ the radius and $h>0$ the height. The volume constraint gives

$$
V=\pi r^2h,\qquad h=\frac{V}{\pi r^2}.
$$

The closed cylinder has two circular ends and a lateral surface. Substitution eliminates the height:

$$
S(r)=2\pi r^2+2\pi rh=2\pi r^2+\frac{2V}{r},\qquad r>0.
$$

Differentiating gives

$$
S'(r)=4\pi r-\frac{2V}{r^2}.
$$

The critical point satisfies $2\pi r^3=V$, so $r_*=(V/(2\pi))^{1/3}$. The height is

$$
h_*=\frac{V}{\pi r_*^2}=2r_*.
$$

**Verification:** $S''(r)=4\pi+4V/r^3>0$ throughout the domain, proving that the unique critical point is the global minimum. The surface area tends to infinity as $r$ approaches zero or infinity.

Geometrically, material usage is minimized when the height equals the diameter of the base.
