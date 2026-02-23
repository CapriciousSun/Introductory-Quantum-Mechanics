20260208155424

Tags: 

A quantum harmonic oscillator is way of modeling the energy states of a particle, where every level is a linear change from the other. 

## Formalism
Given the base [[The Schrödinger Equation|Schrödinger equation]], some simplification could be done to the constants in it. Have some $y = \sqrt{ \frac{m\omega}{\hbar} }x$ and $\tilde{E} = \frac{2E}{\hbar \omega}$. The new form of the Schrödinger equation is $$\frac{d^{2}\psi}{dy^{2}} - y^{2}\psi = -\tilde{E}\psi$$
which is actually a [[The Infinite Potential Well#The Gaussian|Gaussian]], so the solution solution for the state is $$\psi(y) = e^{-y^{2}/2}$$
where the first and second derivatives are $\psi' = -y\psi$ and $\psi'' = y^{2}\psi - \psi$, where the rescaled energy is $\tilde{E} = 1$. 
#### Normalization
Given the above Gaussian solution, the normalized state would be $$\psi(y) = h(y)e^{-y^{2}/2}$$
where the first and second derivatives are $\psi' = (h' - hy)e^{-y^{2}/2}$ and $\psi'' = (h'' - 2h'y + hy^{2} - h)e^{-y^{2}/2}$. When it is plugged back into the Schrödinger equation above, it becomes $$\frac{d^{2}h}{dy^{2}} - 2y\frac{dh}{dy} + (\tilde{E} - 1)h = 0$$
The general solution of $h(y)$ is the sum $$h(y) = \sum_{p = 0}^{\infty} a_{p}y^{p}$$

___
# References
