20260208000151

Tags: 

A particle in a potential well, as opposed to a [[Free Particle|free particle]], is only allowed to exist classically where potential is infinite. 

## Formalism
The infinite potential well has 0 potential within the well, and infinite potential otherwise $$V(x) = \begin{cases}
0 & 0 < x < L  \\
\infty & \text{otherwise}
\end{cases}$$
such that within the well, the Schrödinger equation is in the form $$-\frac{\hbar^{2}}{2m}\frac{\partial^{2}\psi}{\partial x^{2}} = E\psi$$
#### Wavefunction
The wavefunction $\psi$ has the general form $$\psi(x) = Ae^{ikx} + Be^{-ikx}$$
Given that at $x = 0$, the wavefunction doesn't exist, $B = -A$, so the wavefunction can be evaluated to $$\psi(x) = A(e^{ikx} - e^{-ikx}) = 2iA\sin(kx)$$
The factor of $2iA$ is for the normalization of the wavefunction. As the wavefunction must vanish at $x = L$, the following condition must be true $$\sin(kL) = 0 \implies k = \frac{\pi n}{L}$$
which, when placed back into the wavefunction gets $$\psi(x) = \sqrt{ \frac{2}{L} }\sin(kx)$$
#### Momentum
The momentum of the state is not well-defined, because it's in a superposition of $\hbar k$ and $-\hbar k$.

#### Energy
From the wavefunction, the energy eigenvalue must be $$E = \frac{\hbar^{2}\pi^{2}n^{2}}{2mL^{2}}$$
where $n \in \mathbb{N}$. 

## The Gaussian
Given the [[The Schrödinger Equation#Time Independence|time-independent]] solution of the state $\psi_{k}$, while it is not normalizable, taking superposition of the state could yield states that are normalizable. The general superposition of the state is $$\psi(x, t) = \int_{-\infty}^{\infty} dk A(k)\psi_{k}(x, t)$$
where $A(k)$ is the *Gaussian function*, an exponential function with a symmetrical bell curve. The base form of the Gaussian is some $f(x) = e^{-x^{2}}$, with some parametric extension $f(x) = ae^{-(x - b)^{2}/2c^{2}}$. For $A(k)$, consider the following Gaussian $$A(k) = e^{-(k - k_{0})^{2}/2\sigma + k_{0}^{2}/2\sigma}$$
where $k_{0}$ is the center of the momentum space and $2\sigma$ is the width of the wavefunction. The addition of some $e^{k_{0}^{2}/2\sigma}$ is some constant and affects the normalization of the state. The resulting wavefunction when $A(k)$ is plugged back into the state is $$\begin{gather*}
\psi(x, t) = \int_{-\infty}^{\infty} dk e^{-(k^{2} - 2kk_{0})/2\sigma + (i\hbar tk^{2})/2m + ikx} = \int_{-\infty}^{\infty} e^{-\alpha/2(k - \beta/\alpha)^{2} + \beta^{2}/2\alpha}
\end{gather*}$$
where $\alpha = \frac{1}{\sigma} + \frac{i\hbar t}{m}$ and $\beta = \frac{k_{0}}{\sigma} + ix$. By transforming it into this state, this could be solved as a Gaussian integral $$\psi(x, t) = dk e^{-\alpha( - \gamma)^{2}/2} = \sqrt{ \frac{2\pi}{\alpha} }$$

___
# References
