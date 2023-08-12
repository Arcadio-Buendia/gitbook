A hoop of diameter D is pivoted at the topmost piont on the circumference as shown in the figure. The acceleration due to gravity g is acting downwards. What is the time period of small oscillations in the plane of the hoop?

![[hoop ona point]]
#### Designing an answer
 - Due to symmetry, the centre of mass of the circle is at it's centre
 - It can be then treated as a pendulum with string length $\frac{D}{2}$
![](pendulum.md)
 Using the [lagrangian formulation](../../../physics/classical%20mech/lagrangian%20mechanics.md):
 $$\frac{\partial}{\partial t}\frac{\partial T}{\partial \dot x}=\frac{\partial U}{\partial x}$$
 $$ml^2\ddot\theta=mgl\sin\theta$$
 $$\ddot\theta=\frac{g}{l}\sin\theta$$
 For small angles, $\sin\theta\approx\theta$
 Here, angular frequency $$\omega=\sqrt{\frac{g}{l}}$$
 Therefore, the time period is: $$T=2\pi\sqrt{\frac{D}{2g}}$$
 - Once, we get the time period of oscillation of the corresponding penduleum, the moment of inertia can replace the mass of the penduleum
```ad-solution
collapse:
Since, there is no mass dependent component in the time period, the time period of oscillation of the hoop is: 
$$T=2\pi\sqrt{\frac{D}{2g}}$$
```