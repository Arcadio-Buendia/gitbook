Q. Consider the following transformation of the phase space coordinates $$(q,p)$$&rarr;$$(Q,P)$$
$$$$Q=q^a\cos bp \hspace{2cm}P=q^a\sin bp$$$$
For what values of a and b will the transformation be canonical?

#### Understanding the Question
- The question relates to [hamiltonian mechanics](../../../physics/classical%20mech/hamiltonian%20mechanics.md) where p and q are the position and momentum
- For a canonical transformation, the new coordinates $$(Q,P)$$ must satisfy [hamilton's equations](hamiltonian%20mechanics#Hamilton's%20Equation) and this be canonical
#### Designing an Answer
 - Canonical coordinates preserve ![](poisson%20brackets#Fundamental%20Poisson%20Brackets)
 - We need to find the value of a and b such that these three equations are satisfied.
#### Solution
- Our transformation only has one degree of freedom,so the first two are 0.
Now, we have,
$$$$\{p_j,q_k \}=\delta_{jk}$$$$
$$$$\implies \{P,Q\}=1$$$$
$$$$\implies \begin{vmatrix}
\frac{\partial P}{\partial p} & \frac{\partial P}{\partial q} \\
\frac{\partial Q}{\partial p} & \frac{\partial Q}{\partial q} \\
\end{vmatrix}=1
$$$$
$$$$\implies abq^{2a-1}=1$$$$
By inspection, 
$$$$\boxed{a=\frac{1}{2},b=2}$$$$