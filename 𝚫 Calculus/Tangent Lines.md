# Tangent Lines
created: 2021-10-21 10:05

If a point $(x,f(x))$ lies on the graph of $y=f(x)$. We want to try to draw a line through that point which is tangential to the curve. The [[_tangent line|tangent line]] doesn't have to intersect only $(x,f(x))$

![[Pasted image 20211021100846.png]]

It's possible that there's no [[_tangent line|tangent line]] through a given point on a graph. e.g the graph of $y=|x|$

![[Pasted image 20211021101208.png]]

**REM**: To specify a line, you only need to provide a point the line goes through and its [[_slope|slope]]

So far we know, the coordinates $(x,f(x))$. To find the [[_tangent line|tangent line]] of a curve using a point and it's slope, we start by picking a number $z$ which is close to $x$ (either to the left or to the right) and plot the point $(z, f(z))$ on the curve.

![[Pasted image 20211021101829.png]]

The [[_slope|slope]] of the dashed line is given as: 
$$
\frac{f(z)-f(x)}{z-x}
$$

As the point $z$ gets closer and closer to $x$, without ever actually getting to $x$, the [[_slope|slope]] of the line should get closer and closer to the slope of the tangent we're looking for. Therefore:

$$
Slope\ of\ tangent\ line\ through\ (x,f(x))=\lim_{z\rightarrow x}\frac{f(z)-f(x)}{z-x}
$$

And if you set $h=z-x$; then we see that as $z\rightarrow x$, we have  $h\rightarrow 0$. Therefore the above equation can be rewritten as:

$$
Slope\ of\ tangent\ line\ through\ (x,f(x))=\lim_{h\rightarrow 0}\frac{f(x+h)-f(x)}{h}
$$

Of course, this only makes sense if the [[Limit]] actually exists!
## References
1. 