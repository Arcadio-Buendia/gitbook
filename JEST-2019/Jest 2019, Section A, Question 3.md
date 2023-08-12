### Consider the function $f(x,y)=|x|-i|y|$. In which domain of the complex plane is it analytic?

#### Understanding the Question:
##### Complex Plane
![](complex%20plane.excalidraw.md)

#####
We want to know the quadrant for which the given function is [analytic](../../../maths/analytic%20function.md).

#### Designing an answer
- We could check if the derivative of the above function exists in each quadrant by using limits.
- But ![Cauchy](analytic%20function#Cauchy%20Reimann%20Condition) provides an easier way.
#### Solution
 - $u=|x|$
 - $v=- |y|$
![](modulus%20graph.excalidraw.md)

Quadrant|$\frac{\partial u}{\partial x}$|$\frac{\partial v}{\partial x}$
-------|--------------------------------|------------------------------
I|1| -1
II| -1 | -1
III| -1 | 1
IV| 1 | 1

The second condition of CR equation is always satisfied at 0.

Therefore the function is analytic at $\boxed{\large second \ and\ third\ quadrant}$