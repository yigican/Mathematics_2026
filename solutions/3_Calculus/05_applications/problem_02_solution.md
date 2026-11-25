# Problem 2. Maximum Area of a Rectangle

## Question

A rectangle has perimeter $40$.

1. Write its area as a function of the length of one side.
2. Determine the domain of this function resulting from the geometry of the problem.
3. Find the dimensions that give the maximum area.
4. Justify that the point found actually gives a maximum.

> **Why this problem:** it teaches the complete optimization scheme: model → domain → derivative → verification and interpretation of the maximum.

## Solution

Let $x,y$ be the positive side lengths. From $2x+2y=40$, the other side is $y=20-x$. Thus the area and its geometric domain are

$$
A(x)=x(20-x)=20x-x^2,\qquad 0<x<20.
$$

Differentiation gives $A'(x)=20-2x$. It vanishes at $x=10$, is positive before that point, and negative afterward. The unique global maximum is therefore at $x=y=10$, with area $100$ square units.

**Check:** $A''(x)=-2<0$. Independently, $A(x)=100-(x-10)^2\le100$, and the square with sides $10$ satisfies the perimeter constraint.
