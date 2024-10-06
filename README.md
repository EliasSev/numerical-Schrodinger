# Time-Independent Schrödinger Equation
In this small blog (found in the Jupyter notebook and pdf), I solve the time-independent Schrödinger eqution numerically in both one and two dimensions. 
The Schrödinger equation describes wave functions in quantum dynamics, and in the 1-dimensional time-independent case it is

$$
-\frac{\hslash^2}{2m}\frac{d^2\psi}{dx^2} + V(x)\psi(x) = E\psi(x)
$$

and in two dimensions,

$$
-\frac{\hslash^2}{2m}\left(\frac{\partial^2\psi}{\partial x^2}+\frac{\partial^2\psi}{\partial y^2}\right) + V(x,y)\psi(x, y) = E\psi(x, y).
$$

Here, $\psi$ is the wave function which we want to solve for. $V$ is the potential that describes the enviroment, $E$ is the energy of the system,
$m$ is the mass and $\hslash$ is the reduced Planck constant.

In the Jupyter notebook (or pdf), I explain how to obtain a linear system by using finite differences, and then look at which libraries are best suited to solving these large linear systems.
