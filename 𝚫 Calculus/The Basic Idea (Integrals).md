# The Basic Idea
Created: 25-10-2021 11:44

> ### **Abstract:**

Given a function $f$ and an interval $[a,b]$.  Take the graph of $y=f(x)$, and consider the region between the curve, the $x$-axis, and the two vertical line $x=a$ and $x=b$:

![[Pasted image 20211025115504.png]]
For now, we'll just call the two points $a$ and $b$, "units". So the area under the curve would be measured in "square units". The shaded region above, in square units is:
$$
\int_{a}^{b}f(x)\ dx
$$

This is a [[_definite integral|definite integral]]. You would read it out loud as "the integral from a to b of $f(x)$ with respect to $x$". The expression $f(x)$ is called the [[_integrand|integrand]], and tells you what the curved part looks like. $a$ and $b$ are called the [[_limits of integration|limits of integration]] (not to be confused with regular old limits!) or the [[_endpoints of integration|endpoints of integration]]. $dx$ tells us that $x$ is the variable on the horizontal axis. $x$ is a dummy variable -- you can change it to any other letter, provided that you change it everywhere. 

What if the function dips below the $x$-axis? The situation could look something like this:
![[Pasted image 20211025134436.png]]

If all the curve $y=f(x)$ between $x=a$ and $x=b$ actually lies below the $x$-axis, then the [[_integral|integral]] must be negative.

![[Pasted image 20211025135019.png]]

## Some easy examples
Now, let's look at a few simple examples of definite integrals. First consider:
$$
\int_{0}^{1}x\ dx\ \ \ \ \ and\ \ \ \ \ \int_{0}^{2}x\ dx
$$
In both cases, the [[_integrand|integrand]] is $x$. In the first case, the area is from $x=0$ to $x=1$, while the second case goes from $x=0$ to $x=2$. So we are looking for two areas.
![[Pasted image 20211025135957.png]]
These areas are easy to find: since both are right angle triangles, the areas of each can be found using $\frac{1}{2}bh$:
$$
\int_{0}^{1}x\ dx=\frac{1}{2}\ \ \ \ \ and\ \ \ \ \int_{0}^{2}x\ dx=2
$$

Suppose that a car starts at rest, then [[_acceleration|accelerates]] at a constant rate of 1 yard per second squared $y/s^2$; its speed (in yards per second) will be given by $v(t)=t$. So how fast does the car go in one second? How about two seconds?
$$
displacement=\int_{0}^{1}v(t)\ dt=\int_{0}^{1}t\ dt=\frac{1}{2}
$$


## References
1. 
![[Recording 20211203162055.webm]]
