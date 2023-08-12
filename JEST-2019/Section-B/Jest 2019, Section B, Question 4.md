```ad-question
collapse:none
White light of intensity $I_0$ is incident normally one filter plate of thickness d. The plate has a wavelength dependent absorption coefficient $a(\lambda)=a_o\left(1-\frac{\lambda}{\lambda_0}\right)$ per unit length. The band pass edge of the filter is defined as the wavelength at which the intensity, after passing through the filter is $I=\frac{I_0}{\rho},a_o,\lambda_o$ and $\rho$ are constants. the reflection coefficient of the plate may be assumed to be independent of $\lambda$. Which one of the following statements is true about the bandwidth of the filter?
a) The bandwidth is linearly dependent on $\lambda_0$
b) The bandwidth is independent of the plate thickness d
c) The bandwidth is linearly dependent on $a_0$
a) The bandwidth is dependent on $\frac{a_o}{d}$
```

#### Understanding the question
 - **Absorption coefficient**: The change in intensity per unit length is proportional to the intensity, the absorption coefficient is the coeficient of proportionality. $$\frac{dI}{dx}=-aI$$
 - **Band pass edge:** The quantity that defines the boundaries of the wavelengths that pass. The filter will allow a ray to pass if it's intensity is greater than the band pass edge.
 ```ad-note
 title: Diagram in Hindsight
 ![[Jest 2019, Section B, Question 4, fig 1]]
 
 ```
#### Designing an Answer
 - The relation between intensity and wavelength is to be found out
 - The value(s) of wavelength for which intensity is $I_o/\rho$ is to be found
 - The difference between these wavelengths is the bandwidth of the filter.
 
 ```ad-solution
 -  **Intensity-absorbtion coefficient relation:**
 $$\frac{dI}{I}=-\alpha dx$$
 For the intensity of light after passing the block,
 $$\int_{I_o}^I\frac{dI}{I}=-\int_0^d \alpha dx$$
 $$ln\left(\frac{I}{I_o}\right)=-\alpha d$$
 $$I=I_oe^{-\alpha d}$$
 - **For value of wavelength for which intensity is $I_o/\rho$**
$$\frac{I_o}{\rho}=I_oe^{-\alpha d}$$
 $$ln\left(\frac{1}{\rho}\right)=-\alpha d$$
 $$ln\left(\frac{1}{\rho}\right)=-\alpha_o\left(1-\frac{\lambda}{\lambda_o}\right) d$$
 $$\lambda =\lambda_o+\frac{\lambda_o}{\alpha_o d}ln\left(\frac{1}{\rho}\right)$$
 - Since we have only one value of $\lambda$, the bandwidth will be the difference between this wavelength and the peak.
 - **The bandwidth**
    $$\lambda-\lambda_o=\frac{\lambda_o}{\alpha_o d}ln\left(\frac{1}{\rho}\right)$$ 
	$$\boxed{\therefore\text{The bandwidth is linearly dependent on } \lambda_o}$$
 ```