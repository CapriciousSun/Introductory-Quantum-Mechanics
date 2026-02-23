20260114162739

Tags: 

In its simplest form, a state describes how a single particle is behaving. 
## Formalism
Classically, a particle is described by its position and velocity. Quantum mechanically, it is determined by some [[Wavefunction|wavefunction]] $\psi(x, t)$. The probability density of a particle occupying some point $x$ at time $t$ is given by 
$$P(x, t) = |\psi(x, t)|^{2}$$
which is known as Born's rule. 
#### Time-Independence
As long as the state at some time $t_{0}$ is known, it is possible to know how the state will behave for all other times. 

## Normalization
Normalization involves taking a wavefunction, and scaling it such that the total probability of finding a particle is 1.
$$\int d^{3}x P(x, t) = \int d^{3}x|\psi(x, t)|^{2} = 1$$
Wavefunctions that could be scaled are normalizable, or physically realizable. A wavefunction that is normalizable follows the following rule
$$\int d^{3}x |\Psi(x, t)|^{2} = N < \infty$$
#### Phase
The phase of an wavefunction carries some complex value, such that $$\psi(x, t) \equiv e^{i\alpha} \psi(x, t)$$
for any constant $\alpha \in \mathbb{R}$. Such a phase could be viewed like the following equivalence relation $$\psi(x, t) \equiv \lambda \psi(x, t)$$
for any non-zero constant $\lambda \in \mathbb{C}$.  

## Superposition
If $\psi(x, t)$ and $\phi(x, t)$ are both valid quantum states, then any linear combination of $\alpha \psi(x, t) + \beta \phi(x, t)$ for any non-zero constants $a, b \in \mathbb{C}$ is also a valid quantum state. 

## Hilbert Space
Quantum mechanics exists within the Hilbert space, denoted by $\mathcal{H}$, is a vector space over complex numbers with a complete inner product. The wavefunction $\psi$ in a Hilbert space is a vector represented in Dirac notation, where $\ket{\psi} \in \mathcal{H}$. The superposition of two wavefunctions is given by $\ket{\psi}, \ket{\varphi} \in \mathcal{H}$ is represented as $\ket{\psi} + \ket{\varphi} \in \mathcal{H}$. Since a Hilbert space is over complex numbers, $\alpha \ket{\psi} \in \mathcal{H}$ as long as $\alpha \in \mathbb{C}$. Any wavefunction multiplied by 0 gets the zero element $\ket{0}$, which is the ground state of the wavefunction. The basis for the Hilbert space could be some vector where $\ket{1} = (1, 0, \dots, 0)$, $\ket{2} = (0, 1, \dots, 0)$, and so on. The general vector could be written as $$\ket{\psi} = \sum_{n = 1}^{N} \psi_{n}\ket{n} $$For an infinite vector space, $$\ket{\psi} = \sum_{n = 1}^{\infty} \psi_{n}\ket{n} $$
#### Inner Product
The inner product of a complex vector space like a quantum state is expressed as $$\braket{ \psi | \varphi } = \sum_{n = 1}^{N}\psi_{n}^{*}\varphi_{n}$$with condition $\braket{ \psi | \varphi } \geq 0$. This also works for linear combinations of multiple states, where $\braket{ \psi\ |\ \alpha \phi_{1} + \phi_{2} } = \alpha \braket{ \psi | \phi_{1} } + \braket{ \psi | \phi_{2} }$, or in the case of the first argument, anti-linear combination as $\braket{ \alpha \psi_{1} + \psi_{2}\ |\ \phi } = \alpha^{*}\braket{ \psi_{1}\ |\ \phi } + \braket{ \psi_{2}\ |\ \phi }$. The anti-linear property also means $\braket{ \psi\ |\ \phi }^{*} = \braket{ \phi\ |\ \psi }$. Given that the 
___
# References
[[Tong - Quantum Mechanics]]
