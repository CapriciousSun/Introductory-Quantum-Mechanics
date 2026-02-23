20260207184725

Tags: 

A free particle, as the name suggest, is a particle is is absent of a potential.

## Formalism
Since a free particle doesn't have a potential, the [[The Schrödinger Equation#Time Independence|time-independent Schrödinger equation]] has the form $$-\frac{\hbar^{2}}{2m}\frac{d^{2}\psi}{dx^{2}} = E\psi$$
Given that this is now a differential equation, the solution, which is the [[State|state]], has the form $$\psi(x) = e^{ikx}$$
where $k \in \mathbb{R}$. It's impossible for $k \in \mathbb{C}$ physically, since it would cause the state to diverge exponentially as $x$ approaches infinity. It should be noted, however, that the above wavefunction is not normalizable. 

## Eigenstates
#### Energy
The energy eigenvalue solution of a real number $k$ is $$E = \frac{\hbar^{2}k^{2}}{2m}$$
#### Momentum
Given that classically a free particle has energy $E = \frac{p^{2}}{2m}$, quantum mechanically $p = \hbar k$. The wavefunction could be viewed as a sum of a sine and cosine function describing some complex wavefunction where the wavelength $\lambda$ is $\frac{2\pi}{|k|}$. Given that, the momentum is $$|p| = \frac{2\pi \hbar}{\lambda}$$

## Particle on a Circle
Given that the base solution of a free particle is not normalizable, a fix will be to place a particle on a circular path. The resulting wavefunction will be $$\psi(x) = \psi(x + 2\pi R) \implies e^{ikx} = e^{ik(x + 2\pi R)}$$
where $R$ is the radius of a circle. The normalized wavefunction would be $$\psi(x) = \frac{e^{ikx}}{\sqrt{ 2\pi R }}$$
where $k = \frac{n}{R}$ for some $k \in \mathbb{Z}$. Since the wavefunction would only be physically realizable for certain values, the wavefunction, and by extension all values related to it, are quantized. For example, momentum is described as $$p = \hbar k = \frac{\hbar n}{R}$$
and energy is described as $$E = \frac{\hbar^{2}k^{2}}{2m} = \frac{\hbar^{2}n^{2}}{2mR^{2}}$$
___
# References
