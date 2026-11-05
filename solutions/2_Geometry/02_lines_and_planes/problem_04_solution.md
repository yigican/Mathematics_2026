# Exercise 4. Plane Through Three Points

Given $A=(1,0,0)$, $B=(0,1,0)$, and $C=(0,0,1)$, form two in-plane directions:

$$
\overrightarrow{AB}=(-1,1,0),\qquad
\overrightarrow{AC}=(-1,0,1).
$$

Their cross product is a normal vector:

$$
n=\overrightarrow{AB}\times\overrightarrow{AC}
=(1,1,1).
$$

Using point $A$, the plane equation is

$$
(1,1,1)\cdot(x-1,y,z)=0
\quad\Longrightarrow\quad x+y+z=1.
$$

**Checks:** Each of $A$, $B$, and $C$ has coordinate sum $1$, so all lie in the plane. Also,

$$
n\cdot\overrightarrow{AB}=-1+1=0,\qquad
n\cdot\overrightarrow{AC}=-1+1=0.
$$

These independent dot-product checks confirm that $n$ is perpendicular to both in-plane directions.
