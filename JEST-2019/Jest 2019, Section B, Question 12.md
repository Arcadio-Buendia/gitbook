```ad-question
Consider a quantum particle in a one-dimensional box of length L. The cordinates of the leftmost wall of the box is at $x=0$ and that of the rightmost wall is at $x=L$.The particle is in the ground state at $t=0$. At $t=0$, we suddenly change the length of the box to 3L by moving the right wall. What is the probability that the particle is in the ground state of the new system imemdiately after the change?
```
#### Understanding The Question
![](jest%202019,%20section%20B,%20question%2012.md)

#### Designing an Answer
 - The wave function at the ground state of when $L=0$ is a sum of other wave functions.
 - The wave functions of a particle in an infinite potential well are complete and so the set of wave functions of the latter system can represent the groundstate wave function of the earlier one.
 - One of these wave functions is the ground state of $L=3$, we need to single out the coefficient of this function from the sum.
 - Squaring the coefficient should give us the probability that the particle is in the ground state of the new system.

```ad-solution

$$\psi_{oo}=\sum_nc_n\psi_{ln}$$
where $\psi_{ln}$ is the $n^{th}$ state wave function of the later system and $\psi_{oo}$ is the ground state wave function of the old system. 
 - The value of $\psi_{ln}$ and $\psi_{oo}$ in a [[physics/quantum/potential well|potential well]] are: $$\psi_{oo}=\sqrt{\frac{2\pi}{L}}\sin\left(\frac{\pi x}{L}\right) \hspace{2cm} \psi_{ln}=\sqrt{\frac{2\pi}{3L}}\sin\left(\frac{n\pi x}{3L}\right) $$ 
  - The value of $\psi_{ln}$ at $n=1$ is of our interest.
 Since this is the [[physics/quantum/potential well#^576ba0|ground state wave function]] for the new system.
 
 - Using [[fourier series#Fourier's Trick 1| Fourier's Trick]],  
 $$C_{lo}=\int_0^L\psi_{lo}^*\psi_{oo}dx$$
 $$C_{lo}=\frac{9}{8\pi}$$
 
 $$\boxed{\text{The required probaility is: }\frac{81}{64\pi^2}}$$