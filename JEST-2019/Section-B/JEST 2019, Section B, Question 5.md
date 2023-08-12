~~~ad-question
collapse:none
Consider two spherical metal shells of radii $r_1$ and $r_2(r_2>r_1)$. The outer shell has a charge q and the inner shell is grounded. What is the charge on the inner shell?
~~~

 
 #### Designing an answer
![](JEST%202019,%20Section%20B,%20Question%205,%20fig%201.md)
 - The inner shell has whatever charge required to keep the potential at 0 since it is grounded.
 - We need to find the potential of the inner shell and equate it to zero 
 - Potential due to the charges $q$ and $q_2$  on the surface of inner sphere is:  
 $$V_i=V_{outside\ outer\ sphere}+V_{inside\ outer\ sphere} $$
 
 <br/>

 ```ad-solution
 collapse: none
 $$V_i=-\int_\infty^{r_2}\frac{kq}{r^2}dr-\int_\infty^{r_2}\frac{kq_2}{r^2}dr-\int_{r_2}^{r_1}\frac{kq_2}{r^2}dr$$
- Setting $V_i=0$
 $$\frac{-q}{r_2}=q_2\left(\frac{1}{r_2}+\frac{1}{r_1}-\frac{1}{r_2}\right)$$
 $$\frac{-q}{r_2}=\frac{q_2}{r_1}$$
 $$-q\frac{r_1}{r_2}={q_2}$$
 ```