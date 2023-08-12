Q. What is the value of the integral $\int_{-\infty}^{\infty}dx\delta(x^2-\pi^2)\cos x$ ?

#### Solution:
 - Using the property ![](dirac%20delta%20function#^705fe5)
 - We have: $$\delta(x^2-\pi^2)=\frac{\delta(x+\pi)+\delta(x-\pi)}{|2\pi|}$$
 - So we get,$$\frac{1}{2\pi}\int_{-\infty}^{\infty}\delta(x-\pi)cos(x)+\delta(x+\pi)cos(x)dx$$
 - We know ![](dirac%20delta%20function#^1abb72)
 - Therefore, the solution is:$$\frac{1}{2\pi}(\cos\pi+\cos(-\pi))=\boxed{-\frac1\pi}$$