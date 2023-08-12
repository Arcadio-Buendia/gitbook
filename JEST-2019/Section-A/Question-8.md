Q. Consider a diatomic molecule with an infinite number of equally spaced non-degenerate energy levels. The spacing between any two adjacent levels is $$\epsilon$$ and the ground state energy is zero. What is the single particle partition function Z?

#### Understanding the Question
 - ![](maxwell-boltzmann%20energy%20distribution#^partition-function)
 - Non-degenerate means that $$g_i=1\ \ \ \forall\  i$$ 
 - Our $$E_i$$ are of the form $$0,\epsilon,2\epsilon,etc.$$
#### Designing the Answer
 - We need to take the sum as prescribed by the above formula
#### Solution
$$$$Z=e^{-0/KT}+e^{-\epsilon/KT}+e^{-2\epsilon/KT}...$$$$
 - Observation: It is a geometric series with infinite elements. Moreover, the ratio of successive terms is lesser than 1. So the series converges as: ![](sequences%20and%20series#^85e479)
 - Taking $$a=r=e^{-\large{\epsilon}/KT}$$
   $$$$\boxed{ Z=\frac{1}{1-e^{-\large{\epsilon}/kT}}}$$$$