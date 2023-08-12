Q. Which one of the following vectors lie along the line of intersection of the two planes $x+3y-z=5$ and $2x-2y+4z=3$?

#### Understanding the question
 - Any two intersecting planes have a line of intersection.
 - Given four options, find the option that fits the property this line should have.
 
#### Designing an answer
 - A [vector](../../../maths/vectors.md) lying on this line must satisfy the (x,y,z) values of both the equations
 	- So we could do hit and trial for each given option to get the correct answer.
	
 - A vector lying on this plane is also perpendicular to the gradient of both planes
 	- We won't get the exact answer since we will have two equations and three variables but it must make matching options simpler.
	
 #### Solution
 - Finding gradients
 $$\nabla (x+3y-z=5)=\hat x+3\hat y-\hat z$$ 
 $$\nabla (2x-2y+4z)=2\hat x-2\hat y+4\hat z$$
 - Let a vector on the line of intersection be: $a\hat x+b\hat y+c \hat z$
 $$\implies (\hat x+3\hat y-\hat z).(a\hat x+b\hat y+c \hat z)=0$$ and
 $$\implies (2\hat x-2\hat y+4\hat z)\cdot (a\hat x+b\hat y+c \hat z)=0$$
 - We obtain:
   - $c-a=3b$
   - $3c=4b$
  
  
The only equation satisfying both conditions is (b) $\boxed {10\hat i-6\hat j-8\hat k}$
 