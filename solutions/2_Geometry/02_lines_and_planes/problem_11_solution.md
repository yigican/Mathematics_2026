# Exercise 11. Plane Containing a Line and a Point

The line has base point $A=(1,0,2)$ and direction $v=(1,1,-1)$. The extra point is $P=(0,2,1)$.

Another vector lying in the required plane is

$$
w=P-A=(-1,2,-1).
$$

The directions are not proportional. Their cross product gives a normal:

$$
n=v\times w=(1,2,3).
$$

Using $A$, the plane equation is

$$
(1,2,3)\cdot(x-1,y,z-2)=0,
\qquad x+2y+3z=7.
$$

**Checks:** $P$ satisfies $0+2(2)+3(1)=7$. A general point on the line is $(1+t,t,2-t)$; substitution gives

$$
(1+t)+2t+3(2-t)=7
$$

for every $t$. The whole line, not only its base point, is contained in the plane. Also $n\cdot v=1+2-3=0$, as required for a normal.
