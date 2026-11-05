# Exercise 12. Recognizing a Surface from Cross-Sections

## Question

A certain surface has the following properties:
- the cross-section $z=0$ is a point,
- for $z>0$, the cross-sections $z=\mathrm{const}$ are circles with increasing radius,
- vertical cross-sections through the $Oz$ axis are parabolas.

Propose a simple equation for such a surface and justify your choice.

> **Why this exercise:** reverses the usual reasoning: from geometry to an equation.

## Solution

A simple equation satisfying all three conditions is

$$
z=x^2+y^2.
$$

**Horizontal sections:** At $z=0$, $x^2+y^2=0$, giving only $(0,0,0)$. For any fixed $z=c>0$,

$$
x^2+y^2=c,
$$

which is a circle of radius $\sqrt c$. The radius increases as $c$ increases.

**Vertical sections:** Every vertical plane through the $z$-axis can be described using a horizontal unit direction $e=(\cos\phi,\sin\phi)$ and the coordinate $s$ through $x=s\cos\phi$, $y=s\sin\phi$. Substitution gives

$$
z=s^2(\cos^2\phi+\sin^2\phi)=s^2,
$$

an upward-opening parabola.

**Conclusion and check:** This is an elliptic paraboloid opening upward. All three stated cross-section properties follow directly from its equation.
