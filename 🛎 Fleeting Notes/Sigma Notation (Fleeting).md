Consider the sum:
$$
\frac{1}{1}+\frac{1}{4}+\frac{1}{9}+\frac{1}{16}+\frac{1}{25}+\frac{1}{36}
$$

This isn't a sum of random numbers: there's a definite pattern. Can you see it?
Here is a much more convenient way to write this sum:

$$
\sum_{j=1}^{6}\frac{1}{j^2}
$$
When reading this we say: "The sum, from $j=1$ to 6, of $1/j^2$ ". The idea is that you plug $j=1$, $j=2$,$j=3$ and so on up until $j=6$ into the expression $1/j^2$, one at a time, and then add up everything.

![[Pasted image 20211024053920.png]]

[[_Sigma]] notation is really useful when you want to vary where the sum stops (or starts). For example, consider the series:

$$
\sum_{j=1}^{n}\frac{1}{j^2}=\frac{1}{1^2}+\frac{1}{2^2}+\frac{1}{3^2}+...+\frac{1}{(n-2)^2}+\frac{1}{(n-1)^2}+\frac{1}{n^2}
$$

It looks as if there are two variables, $j$ and $n$, but in reality there is only one, which is $n$. $j$ is just a dummy variable -- It's just a temporary placeholder, called the [[_Index of summation]], that runs through the integers from 1 to $n$.