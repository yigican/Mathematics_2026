# Exercise 13. Intersection of a Sphere and a Plane

The sphere is $x^2+y^2+z^2=25$. Substituting the plane $z=3$ gives

$$
x^2+y^2+9=25
\quad\Longrightarrow\quad
x^2+y^2=16.
$$

The intersection is a circle of radius $4$ in the plane $z=3$, centered at $(0,0,3)$.

More generally, a section by $z=c$ satisfies

$$
x^2+y^2=25-c^2.
$$

- For $|c|<5$, the section is a circle of radius $\sqrt{25-c^2}$.
- For $|c|=5$, it is one point at $(0,0,\pm5)$.
- For $|c|>5$, it is empty because the right-hand side is negative.

**Check:** $(4,0,3)$ lies in the plane and satisfies $4^2+0+3^2=25$. The maximal section at $c=0$ has radius $5$, the sphere's own radius.
