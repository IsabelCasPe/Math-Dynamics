# Math-Dynamics
A collection of visualizations exploring the behavior of dynamic systems, chaotic attractors, and financial models, implemented in Python with Matplotlib and SciPy.  inspired by fractal aesthetics and mathematical harmony. Authored by Ana Isabel Castillo, PhD in Applied Mathematics. 

# ⚡ Tesla 3D Electromagnetic Field – Visual Tribute

> “Yesterday (07/07/25), the YouTube algorithm gifted me with a revealing interview about the genius Nikola Tesla.  
> I was captivated… and ideas flowed like electricity in the air.  
> Thus, this tribute was born: a creative spark that ignited, echoing Tesla’s vision that lit up the world.  
> His boldness inspired me to transform energy and frequency into visual art.”  
> — **Isabel  – Math Dynamics✨**

## 🎥 Project
This is a 3D simulator inspired by Nikola Tesla’s revolutionary ideas, capturing pulsating electromagnetic fields with zeta-shaped rays rising and falling like cones, evoking his genius in alternating current and wireless energy transmission. Created with Python and Matplotlib, the project blends science and visual art, featuring a vortex spiral and a subtle base tremor to reflect Tesla’s creative instability.

🎬 Watch the animation:  [Tesla 3D Animation](campo_eletromagnetico_tesla_3d_vibes.mp4)  
-![Tesla 3D Animation](campo_eletromagnetico_tesla.gif)
 
📄 Presentation PDF: [`NikolaTesla.pdf`](NikolaTesla.pdf)  
© 2025 – Original project by Ana Isabel C. – Math Dynamics  
All rights reserved. Sharing only with proper credits. 
# Site: https://github.com/IsabelCasPe/Math-Dynamics.git

# Math-Dynamics: Quantum Sphere Dynamics & Numerical Calculus
For my birthday on July 4, 2025, I present the **Quantum Flower of Life**: a 3D visualization with 1156 Spectral grid points, blooming petals, radiant white stars, and the root \( x \approx 0.9166 \) from Chapter 2. Loki, my cat, throws shade at the haters! ;) Explore the chaos and beauty of *Finance Math*!

## Chapter 2: Roots of Functions
This section solves root-finding problems from Chapter 2 of Prof. Castilho's lecture notes, with Python implementations and visualizations.
  - [Ex. 2.8](sincos_root.png)
- **Python Codes**:
  - `birthday_quantum_flower_v9.py`
- **Video**: [Quantum Flower of Life v9](birthday_quantum_flower_v9.mp4) – Updated animation with enhanced dynamics.
- **Presentation**: [Quantum Flower of Life](flordavida.pdf) – LaTeX slides detailing the mathematical formulation.

## Birthday Celebration: Quantum Flower of Life
The **Quantum Flower of Life** is a 3D visualization celebrating my birthday and resilience in the chaotic world of *Finance Math*. Key features:
- **Surface**: Defined by \( z = g \cdot p \cdot \sin(6\theta) \cos(3r) \), with organic growth \( g = \min(1.5, t/50) \cdot e^{-0.5 r^2} \) and pulsing petals \( p = 1.2 + 0.7 \sin(t/20) \).
- **Root**: Solution to \( \sin(\cos(\sqrt{3}x)) = 0 \), with \( x \approx 0.9166 \), visualized as a pulsating *goldlove* point.
- **Stars**: 50 white stars , with dynamic size and transparency, pulsing.
- **Base**: Oscillating 3D base (*Sábana Gaussiana*) in *cosmicgray* , defined by \( z = 0.1 \sin(2\pi (x + y)/5 - t/20) \).
- **Connection to QFE**: Inspired by the Anderson model and nonlinear dynamics in financial chaos (e.g., GOLL4.SA).

The LaTeX presentation ([flordavida.pdf](flordavida.pdf)) provides a rigorous mathematical foundation.

## Acknowledgments
- To Loki, for throwing shade at the haters © Ana Isabel Castillo & Loki, 2025
- To the *Math-Dynamics* community for the vibrant support!

# Schrödinger 3D – Math-Dynamics 🎥✨

Interactive and artistic visualization of the 3D Schrödinger equation with a quasi-periodic potential, inspired by just 10 minutes of a lecture.
This project blends science, art, and aesthetic sensitivity into a single dynamic flow.

🔸 Included Files
🎞️ schrodinger_3dv29.mp4: Full animation of a golden quantum particle dancing through the 3D quantum field. [schrodinger_3dv29.mp4](schrodinger_3dv29.mp4)
- ![Schrodinger 3D](schrodinger_3D.gif)

📄 Schrodinger3D2A.pdf: LaTeX Beamer presentation describing the simulation and its mathematical–visual connections. [Schrodinger3D2A.pdf](Schrodinger3D2A.pdf)

#Sphere Dynamics 
- ![Sphere Dynamics](sphere_dynamics_ladrilhos.gif)
  
## Oscillatory Systems
### Sine and Cosine Oscillations
Visualization of harmonic functions \(\sin(x+t)\) and \(\cos(x+t)\), demonstrating periodic motion.  
- **Specifications**: 10,000 points; Matplotlib animation.  
- **Visualization**: ![sincos_animation.gif](sincos_animation.gif)  
- **Description**: Parametric oscillations in two dimensions.

### Lissajous Curves
Parametric oscillations generating Lissajous curves, forming harmonic patterns.  
- **Specifications**: Frequencies `a=3`, `b=2`, phase `phi=π/2`; 10,000 points; Matplotlib animation.  
- **Visualization**: ![lissajous_dancers.gif](lissajous_dancers.gif)  
- **Description**: Trajectories defined by \(x = \sin(a t + \phi)\), \(y = \sin(b t)\).

### Heart-Shaped Parametric Dynamics
Curves forming heart-shaped orbits, inspired by parametric equations.  
- **Specifications**: Parametric equations with 10,000 points; Matplotlib animation.  
- **Visualization**: ![hearts_salsa_cosmica.gif](hearts_salsa_cosmica.gif)  
- **Description**: Oscillatory patterns evoking dynamic harmony.

### Duffing Oscillator
Nonlinear oscillator exhibiting complex behavior, visualized as a sea wave.  
- **Specifications**: Parameters for chaotic regime; Matplotlib animation.  
- **Visualization**: ![duffing_sea_wave.gif](duffing_sea_wave.gif)  
- **Description**: Solutions to the Duffing equation with nonlinear restoring force.

## Chaotic Systems
### Logistic Map
Visualization of the logistic map, transitioning from periodicity to chaos.  
- **Specifications**: Parameter \(r\) varying across grid; Matplotlib animation.  
- **Visualization**: ![chaos_animation_grid.gif](chaos_animation_grid.gif)  
- **Description**: Discrete iterations \(x_{n+1} = r x_n (1 - x_n)\).

### Lorenz Attractor
Trajectories of the Lorenz system, a continuous chaotic attractor with spiral dynamics.  
- **Specifications**: Parameters \(\sigma=10\), \(\rho=28\), \(\beta=8/3\); 10,000 points; `odeint` integration.  
- **Code**: [lorenz.py](lorenz.py)  
- **Visualization**: ![lorenz.gif](lorenz.gif)  
- **Description**: System defined by \(\dot{x} = \sigma(y-x)\), \(\dot{y} = x(\rho-z)-y\), \(\dot{z} = xy-\beta z\).

### Lorenz Particles
Two particles evolving within the Lorenz attractor, highlighting chaotic divergence.  
- **Specifications**: Initial conditions offset by 0.01; Matplotlib animation.  
- **Visualization**: ![lorenz_particles.gif](lorenz_particles.gif)  
- **Description**: Sensitivity to initial conditions in chaotic systems.

### Hénon Map
Discrete chaotic system generating dense orbits in a confined region.  
- **Specifications**: `a=1.4`, `b=0.3`; 10,000 points; Matplotlib scatter plot.  
- **Visualization**: ![henon_salsa_galactica.gif](henon_salsa_galactica.gif)  
- **Description**: Iterations \(x_{n+1} = 1 - a x_n^2 + y_n\), \(y_{n+1} = b x_n\).

- **Hénon Map 3D**: Fractal chaos with two trajectories.
  - **GIF**: ![henon_salsa_fractal.gif](henon_salsa_fractal.gif)
  - **Video**: [henon_salsa_fractal.mp4](henon_salsa_fractal.mp4)
  - **Documentation**: [Henon2.pdf](Henon2.pdf)
  - **Code**: [henon_salsa_fractal.py](henon_salsa_fractal.py)

### Rössler Attractor
Continuous chaotic system with dense spiral trajectories.  
- **Specifications**: `a=0.2`, `b=0.2`, `c=7.0`; 20,000 points; `odeint` integration.  
- **Visualization**: ![rossler.gif](rossler.gif), ![rossler_2_spiral.gif](rossler_2_spiral.gif)
- **Documentation**: [Rossler1.pdf](Rossler1.pdf)
- **Description**: System defined by \(\dot{x} = -y-z\), \(\dot{y} = x + a y\), \(\dot{z} = b + z(x-c)\).

### Quasiperiodic Toro
Three-dimensional quasiperiodic flow on a torus, exhibiting non-repeating orbits.  
- **Specifications**: Incommensurate frequencies; Matplotlib 3D animation.  
- **Visualization**: ![quasiperiodic_salsa_celeste.gif](quasiperiodic_salsa_celeste.gif)  
- **Documentation**: [quaseperiodicotoro.pdf](quaseperiodicotoro.pdf)  
- **Description**: Trajectories on a toroidal manifold.

- **Double Pendulum**: Chaotic dynamics simulation.
- **GIF**: ![pendulo.gif](pendulo.gif)
- **Documentation**: [Penduloduplo.pdf](Penduloduplo.pdf)
- **Code**: [pendulo_duplo.py](PenduloDuplo/pendulo_duplo.py)

## Financial Models
### Black-Scholes Model
Visualization of call option pricing under the Black-Scholes model with varying volatility \(\sigma\).  
- **Specifications**: Matplotlib animation with dynamic \(\sigma\).  
- **Visualization**: ![black_scholes_animation.gif](black_scholes_animation.gif)  
- **Description**: Solution to the Black-Scholes PDE for option pricing.

### Black-Scholes Interactive
Interactive visualization of Black-Scholes pricing with adjustable volatility.  
- **Specifications**: Slider for \(\sigma\); Matplotlib interactive plot.  
- **Visualization**: ![black_scholes_interactive.gif](black_scholes_interactive.gif)  
- **Description**: Dynamic exploration of option pricing.

### Heston Model
Stochastic volatility model simulating price and volatility dynamics.  
- **Specifications**: Monte Carlo simulation; Matplotlib animation.  
- **Visualization**: ![heston_dynamics.gif](heston_dynamics.gif)  
- **Description**: Coupled stochastic differential equations for asset price and variance.

## Transform Methods
### Fourier Transform
Decomposition of signals into frequency components via the Fourier transform.  
- **Specifications**: Matplotlib animation of frequency summation.  
- **Visualization**: ![fourier_animation_fixed_v2.gif](fourier_animation_fixed_v2.gif)  
- **Description**: Representation of signals as sums of sinusoids.

### Laplace Transform
Visualization of exponential decay in the \(s\)-domain, applied to control and finance.  
- **Specifications**: Matplotlib animation of transform dynamics.  
- **Visualization**: ![laplace_animation_fixed.gif](laplace_animation_fixed.gif)  
- **Description**: Transform mapping time-domain signals to the complex plane.

## Fractal Systems
### Julia Set
Animation of the Julia set, exploring complex dynamics in the complex plane.  
- **Specifications**: Iterations in complex plane; Matplotlib animation.  
- **Visualization**: ![julia_infinite.gif](julia_infinite.gif)
- **Documentation**: [JuliaDynamics.pdf](JuliaDynamics.pdf) 
- **Description**: Fractal boundaries defined by \(z_{n+1} = z_n^2 + c\).

## Numerical Methods
### Euler Method
Visualization of numerical solutions using the Euler method for differential equations.  
- **Specifications**: Matplotlib animation of iterative steps.  
- **Visualization**: ![euler_final_dance.gif](euler_final_dance.gif)  
- **Description**: Approximation of ODE solutions via discrete steps.

## Optimal Control
### Linear Quadratic Regulator (LQR)
Optimal control visualization for a dynamic system, minimizing a quadratic cost.  
- **Specifications**: Matplotlib animation of state trajectories.  
- **Visualization**: ![loki_vs_rival_com_equacao.gif](loki_vs_rival_com_equacao.gif)
- **Documentation**: [LQRLoki.pdf](LQRLoki.pdf) 
- **Description**: Control law derived from Riccati equation solutions.

## Usage
- View GIFs for looped animations directly in the browser.
- Source codes and additional documentation available upon request for academic purposes.
- Visualizations are implemented in Python with Matplotlib and SciPy.

## License
© Ana Isabel Castillo, Math-Dynamics. Licensed under [CC BY-NC-ND 4.0](LICENSE.md).

## Contributions
Suggestions for new dynamic systems or visualization techniques are welcome. Contact the author for collaboration or additional materials.

#MathDynamics #SistemasDinâmicos #ChaosTheory
