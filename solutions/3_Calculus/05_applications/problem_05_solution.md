# Problem 5. Distance from Velocity

## Question

The velocity of a car during the first five seconds is described by the function

$$
v(t)=4t+2\quad [\mathrm{m/s}].
$$

Compute the distance traveled and explain why the integral of velocity gives the change in position.

Then answer what would have to be changed in the reasoning if the velocity also took negative values.

> **Why this problem:** it connects the integral with accumulation and distinguishes displacement from the actual distance traveled.

## Solution

The velocity is positive on the entire interval $[0,5]$, so distance and displacement coincide. Since velocity is the derivative of position, the fundamental theorem of calculus gives the change in position:

$$
\int_0^5(4t+2)\,dt
=\left[2t^2+2t\right]_0^5=50+10=60.
$$

The car travels $60$ m.

**Check:** The linear velocity has endpoint values $2$ and $22$ m/s, so its average is $12$ m/s. Multiplying by $5$ seconds gives $60$ m.

If the velocity took negative values, the integral of velocity would give signed displacement. For total distance, integrate the speed, $\int_0^5|v(t)|\,dt$, splitting at sign changes if necessary.
