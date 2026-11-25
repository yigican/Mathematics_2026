# Problem 8. Number of Requests Handled by a Server

## Question

The rate at which requests arrive at a server during the first 5 minutes is described by the function

$$
r(t)=100+20t\quad [\mathrm{requests/min}],\qquad 0\le t\le5.
$$

1. Compute the total number of requests that arrived during this time.
2. Compute the average rate of incoming requests over this interval.
3. Compare the average rate with the values $r(0)$ and $r(5)$.

> **Why this problem:** it shows the integral as summation of a varying rate in an example directly related to computer science.

## Solution

Integrating the incoming rate over time gives the total number of requests:

$$
Q=\int_0^5(100+20t)\,dt
=\left[100t+10t^2\right]_0^5=750.
$$

The average rate is the total divided by the duration, $Q/5=150$ requests per minute. The endpoint rates are $r(0)=100$ and $r(5)=200$ requests per minute.

**Check:** The rate is linear, so the average is the midpoint of its endpoint values, $(100+200)/2=150$. Multiplying by five minutes confirms the total of $750$ requests.
