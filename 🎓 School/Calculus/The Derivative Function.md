# The Derivative Function
created: 2021-10-21 10:35

![[Pasted image 20211021103631.png]]

These lines have different slopes. That is, the [[Slope]] of the tangent line depends on which value of $x$ you start with. Another way of saying this is that the slope of the tangent line through $(x,f(x))$ is itself a function of $x$. This function is called the [[Derivative]] of $f$ and is written as $f^{'}$. We say that we have *differentiated* the function f with respect to its variable $x$ to get the function $f^{'}$. By the [[Difference quotient]] formula we say the $f$ is *differentiable* at $x$. 

If the limit doesn't exist for some particular $x$, then that value of $x$ is not in the domain of the derivative function $f^{'}$. So we say that $x$ is *not differentiable* at $x$. 

#### Cases where the limit could fail to exist
* The limit of a function could fail to exist where there is a sharp corner.
* If $x$ isn't in the domain of $f$, then you can't even plot the point $(x,f(x))$, let alone draw a tangent line there!

Can you recall the formula definition of instantaneous velocity?

![[Pasted image 20211021182913.png]]

The right hand side of the image above is the same as the definition $f^{'}(x)$ above, except with $x$ replaced by $t$! Formally, if the instantaneous velocity is given as $v(t)$ at time $t$, then $v(t)=f^{'}(t)$. If $f(x)=x^2$, what is $f^{'}(x)$?

![[Pasted image 20211021183551.png]]

This means that the slope of the tangent to the parabola $y=x^2$ at the point $(x,x^2)$ is precisely $2x$. Draw the curve and a few tangent lines to check it out:

![[Pasted image 20211021183836.png]]

The slope of the tangent at $x=-1$ does indeed look like it's about $-2$, which is consistent with the formula $f^{'}(x)=2x$. The same is true with the other tangents -- their slopes are all twice the corresponding $x$-coordinate

## References
1. 