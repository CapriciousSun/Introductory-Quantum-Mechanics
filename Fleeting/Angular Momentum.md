20260208183828

Tags: 

Angular momentum in a particle describes the orbit around some external point. It is not [[Spin|spin]], which describes the rotation of the particle on some internal axis.

## Formalism
The angular momentum operator, $\hat{L}$ is defined as $\hat{x} \times \hat{p}$, which is expanded to $$-i\hbar \hat{x}\times \nabla$$where the components of $\hat{x}$ are the following $$\begin{gather*}
\hat{L}_{1} = -i\hbar \left( x_{2} \frac{\partial}{\partial x_{3}} - x_{3} \frac{\partial}{\partial x_{2}} \right) \\
\hat{L}_{2} = -i\hbar \left( x_{3} \frac{\partial}{\partial x_{1}} - x_{1} \frac{\partial}{\partial x_{3}} \right) \\
\hat{L}_{3} = -i\hbar \left( x_{1} \frac{\partial}{\partial x_{2}} - x_{2} \frac{\partial}{\partial x_{1}} \right) 
\end{gather*}$$or more generally $$\hat{L}_{i} = -i\hbar \epsilon_{ijk}x_{j} \frac{\partial}{\partial x_{k}}$$

## Commutation
The commutation relation between all the components of $\hat{L}$ is $$[\hat{L}_{i}, \hat{L}_{j}] = i\hbar \epsilon_{ijk}\hat{L}_{k}$$Given that this is the case, it means a particle could not have a well-defined angular momentum in all directions at once. This is proven by the following calculation $$[\hat{L}_{1}, \hat{L}_{2}]\psi = -\hbar^{2}\left( x_{2} \frac{\partial}{\partial x_{3}} - x_{3} \frac{\partial}{\partial x_{2}} \right)\left( x_{3} \frac{\partial}{\partial x_{1}} - x_{1} \frac{\partial}{\partial x_{3}} \right)\psi + \hbar^{2}\left( x_{3} \frac{\partial}{\partial x_{1}} - x_{1} \frac{\partial}{\partial x_{3}} \right)\left( x_{2} \frac{\partial}{\partial x_{3}} - x_{3} \frac{\partial}{\partial x_{2}} \right)\psi = \hbar^{2} \left( x_{1} \frac{\partial}{\partial x_{2}} - x_{2} \frac{\partial}{\partial x_{1}} \right)\psi = i\hbar \hat{L}_{3}\psi$$Due to the fact that almost all other terms cancel out, the only remaining term is for some $\hat{L}_{k}$. 
#### Magnitude
Instead of commuting with each individual direction, the relation could be evaluated for the magnitude of $\hat{L}$ instead. The magnitude is defined as $$\hat{L}^{2} = \hat{L}_{1}^{2} + L_{2}^{2} + L_{3}^{2}$$and the commutation relation of it with any $\hat{L}_{i}$ is $$[\hat{L}^{2}, \hat{L}_{i}] = 0$$The proof for this is given by the lemma $$[\hat{A}^{2}, \hat{B}] = \hat{A}[\hat{A}, \hat{B}] + [\hat{B}, \hat{A}]\hat{A}$$but applied to all values within the magnitude. So the setup is $$[\hat{L}_{1}^{2}, \hat{L}_{1}] + [\hat{L}_{2}^{2}, \hat{L}_{1}] + [\hat{L}_{3}^{2}, \hat{L}_{1}]$$and immediately the first term commutates with itself. The second term evaluates to $$[\hat{L}_{2}^{2}, \hat{L}_{1}] = \hat{L}_{2}[\hat{L}_{2}, \hat{L}_{1}] + [\hat{L}_{1}, \hat{L}_{2}]\hat{L}_{2} = -i\hbar(\hat{L}_{2}\hat{L}_{3} + \hat{L}_{3}\hat{L}_{2})$$and the third term evaluates to $$[\hat{L}_{3}^{2}, \hat{L}_{1}] = \hat{L}_{3}[\hat{L}_{3}, \hat{L}_{1}] + [\hat{L}_{1}, \hat{L}_{3}]\hat{L}_{3} = i\hbar(\hat{L}_{3}\hat{L}_{2} + \hat{L}_{2}\hat{L}_{3})$$Summed up, the total is 0. 

## Eigenfunctions

___
# References
