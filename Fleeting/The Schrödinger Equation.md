20260207184719

Tags: 

If a wavefunction gives information about the [[State|state]] of a quantum particle, then the Schrödinger equation gives information about how a state evolves. 

## Formalism
The Schrödinger equation described by the following equation $$i\hbar \frac{\partial \psi}{\partial t} = \hat{H}\psi$$
where the [[Operator|operator]] $\hat{H}$ is a Hamiltonian, which represents the total energy of the state and $\hbar$ is the reduced Planck's constant $\frac{h}{2\pi}$. 
#### Time Independence
Solving for some base form of the Schrödinger equation involves looking at just the position first. So the wavefunction could be separated into position and time $$\psi(x, t) = e^{-i\omega t}\psi(x)$$
Given the separated wavefunction, the *time-independent Schrödinger equation* would be $$\hat{H}\psi(x) = E\psi(x)$$
where $E = \hbar \omega$ and $\omega$ is the frequency. 

## The Hamiltonian
The Hamiltonian in the Schrödinger equation is composed of the kinetic and potential energy of a state $$\hat{H} = -\frac{\hbar^{2}}{2m}\nabla^{2} + V(x)$$
where $\nabla$ is the Laplacian defined by the following partial derivatives $$\nabla^{2} = \frac{\partial^{2}}{\partial x^{2}} + \frac{\partial^{2}}{\partial y^{2}} + \frac{\partial^{2}}{\partial z^{2}}$$
Classically, energy is the sum of all potential and kinetic energy, defined like the following $$E = K + V = \frac{1}{2m}p^{2} + V(x);\ \ p = mx$$
Quantum mechanically, the same applies, except $\hat{p} = \pm i\hbar \nabla$. So the full Schrödinger equation is the following $$i\hbar \frac{\partial \psi}{\partial t} = -\frac{\hbar^{2}}{2m}\frac{\partial^{2}\psi}{\partial x^{2}} + V(x)\psi$$

## Conservation of Probability
Given that $P = |\psi|^{2}$, the change in probability over time is defined by $$\frac{\partial P}{\partial t} = \psi^{*}\frac{\partial \psi}{\partial t} + \frac{\partial \psi^{*}}{\partial t}\psi$$
where the partial derivatives are defined by $$\frac{\partial \psi}{\partial t} = -\frac{i}{\hbar}\left( -\frac{\hbar^{2}}{2m} \nabla^{2}\psi + V\psi \right),\ \ \frac{\partial \psi^{*}}{\partial t} = \frac{i}{\hbar}\left( -\frac{\hbar^{2}}{2m}\nabla^{2}\psi^{*} + V\psi^{*} \right)$$
When the partial derivatives are plugged back into the change in probability, it becomes the following $$\frac{\partial P}{\partial t} = \frac{i\hbar}{2m}\nabla(\psi^{*}\nabla \psi - \psi \nabla \psi^{*})$$
## Collapse of the Wavefunction
Given a wavefunction with two distinct positions, $\chi_{1}$ and $\chi_{2}$, a normalized wavefunction at some time $t_{0}$ would be represented as $$\psi(x, t_{0}) = \frac{1}{\sqrt{ N' }}\left( e^{-a(x - \chi_{1})^{2}} + e^{-a(x - \chi_{2})^{2}} \right)$$
which would evolve as time goes on. If measured at $\chi_{1}$ at some time $t_{+}$, then the wavefunction would collapse, turning into the following $$\psi(x, t_{+}) = \frac{1}{\sqrt{ N }}e^{-a(x - \chi_{1})}$$ 
___
# References
