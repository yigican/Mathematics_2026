# Problem 1. Motion — from Position to Velocity

## Question

The position of a point is described by

$$
s(t)=t^3-6t^2+9t+2,\qquad t\ge0.
$$

1. Determine the velocity and acceleration.
2. Find the times at which the point stops.
3. Determine on which intervals the point moves in the positive direction of the axis and on which intervals it moves in the negative direction.

> **Why this problem:** it shows the derivative as a real rate of change and requires interpretation of the sign of the derivative in the context of motion.

## Solution

Velocity is the derivative of position, and acceleration is the derivative of velocity. The power rule gives

$$
v(t)=s'(t)=3t^2-12t+9=3(t-1)(t-3),
$$

$$
a(t)=v'(t)=6t-12.
$$

The point stops when $v(t)=0$, at $t=1$ and $t=3$. The factors have the same sign outside these roots and opposite signs between them. The point moves in the positive direction on $[0,1)$ and $(3,\infty)$, and the negative direction on $(1,3)$.

**Check:** $v(0)=9$, $v(2)=-3$, and $v(4)=9$. Also $s(1)=6$ and $s(3)=2$, consistent with backward motion between the stopping times.
