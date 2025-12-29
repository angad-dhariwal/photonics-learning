# photonics-learning

This repo's purpose is to document my journey in learning more about photonics, especially with MIT Electromagnetic Equation Propagation (MEEP), which is a finite-difference time-domain (FDTD) method to solve Maxwell's equations. It is very powerful and allows one to simulate many different electromagnetic phenomena.

Specifically, I use PyMeep, which is a library that allows one to run MEEP with python, which is much more familiar to me.

## my goals
- Develop proficiency in computational photonics and FDTD simulation
- Build intuition for how electromagnetic waves behave in photonic structures
- Work toward understanding advanced topics like photonic crystals, resonators, and waveguide coupling.
- Eventually contribute to research in integrated photonics


## process

I began with reviewing Maxwell's equations, getting familiar with them in all forms. I then went through a few tutorials available on the [MEEP documentation](https://meep.readthedocs.io/en/latest/Python_Tutorials/Basics/#).

After working on the straight waveguide and the bent waveguide (viewable [here](/tutorials/), with the mp4 videos [here](/tutorials/media)), I began working on how to quantitatively gather some information about the simulations. In particular, for the bent-waveguide simulation, I want to know how much power makes it around the bend (i.e. transmittance), how much is reflected (reflectance), and how much is radiated away (scattered loss).
