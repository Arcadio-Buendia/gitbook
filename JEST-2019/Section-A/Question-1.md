
Q. Let $$\vec r$$ be the position vector of a point on a closed contour C. What is the value of the line integral $$\oint\vec r\cdot \vec dr$$ ? 

### Understanding the Question:
  ![](JEST-2019/Section-A/Question-1,fig1.excalidraw.md)

$$\vec r$$ is the position vector for the closed contour C. 

## Designing the answer

#### Possible Methods:
 - Line integral by seperating $$\vec r$$ into it's components.[^1]
	 - There will be two variables since no obvious relation exists between x and y
-  [contour integral](../../../maths/contour%20integral.md) can be used by treating $$\vec r=f(z)$$ and invoking [cauchy's theorem](contour%20integral#Cauchy's%20Theorem)[^2]

#### Weapon of choice:
![](contour%20integral#Cauchy's%20Theorem)
	Since our position vector is [analytic](../../../maths/analytic%20function.md) inside and on the closed contour, we can use cauchy's theorem.
	
$$\oint \vec r.\vec dr$$ is of the same form as $$(i)$$.
	Therefore,
$$$$\large \boxed{\oint \vec r.\vec dr=0}$$$$


###### footnotes
[^1]: Using the property that $$\nabla \times \vec r=0\implies \oint \vec r\cdot d\vec r=0$$([Stoke's Theorem](Fundamental%20Theorems%20of%20Vector%20Analysis#Stoke's%20Theorem)) is probably a better idea.
[^2]: Does $$\vec r$$ exist in the complex plane? Is it analytic on an inside C? 








