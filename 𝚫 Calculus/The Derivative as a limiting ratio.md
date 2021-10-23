# The Derivative as a limiting ratio
created: 2021-10-21 18:48

In the [[Difference quotient]] formula, we have to evaluate the quantity $f(x+h)$. What is this quantity? Well, if $y=f(x)$, and you change $x$ into $f(x+h)$, then $f(x+h)$ is simply the new value of $y$. The amount $h$ represents how much you change $x$, so let's replace it by the quantity $\Delta x$. So, rewriting the $f^{'}(x)$ formula (or difference quotient ), with $h$ replaced with $\Delta x$:

$$
f^{'}(x)=\lim_{\Delta x \rightarrow 0}\frac{f(x +\Delta x)-f(x)}{\Delta x}
$$

Given:

![[Pasted image 20211021190002.png]]

The first equation says that $x_{new}=x+\Delta x$, so now the second equation can be transformed as follows:

![[Pasted image 20211021190059.png]]


What this means is that:

$$
f^{'}(x)=\lim_{\Delta x \rightarrow 0}\frac{\Delta y}{\Delta x}
$$

An interpretation of this is that a small change in $x$ produces approximately $f^{'}(x)$ times as much change in $y$. $f^{'}(x)$ isn't actually equal to the ratio of $\Delta y$ to $\Delta x$: it's equal to the [[Limit]] of that ratio as $\Delta x$ tends towards 0. 

Instead of writing $\Delta x$, we'd like to write $dx$, which should mean **really, really tiny change in x**, and similarly for y. Unfortunately neither $dx$ nor $dy$ really means anything by itself; nevertheless this provides the inspiration for writing the derivative in a different, more convenient way:

if $y=f(x)$, they you can write $\frac{dy}{dx}$ instead of $f^{'}(x)$.

For example, if $y=x^2$, then $\frac{dy}{dx}$. In fact, if you replace $y$ with $x^2$, you get a variety of different way of expressing the same thing:

![[Pasted image 20211021192044.png]]

## References
1. 