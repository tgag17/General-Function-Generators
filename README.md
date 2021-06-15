# General-Function-Generators

This repository was created as a part of the [QOSF Mentorship Project](https://qosf.org/qc_mentorship/)
<br>
**Mentee**: Tanya Garg
<br>
**Mentor**: Jakob Kottmann

Variational Quantum Circuits are circuits with trainable parameters. These parameters can be varied to estimate the expectation of some observable at different parameter values. Using the obtained results to determine the optimal change in the parameters, one can train quantum circuits as machine learning models to create General Function Generators.

In `General_Function_Generator_1D.ipynb`, we go through the process of creating variational objective functions by following the methods given in [ M. Schuld et al ](https://arxiv.org/pdf/2008.08605.pdf) and [A. Pérez-Salinas et al](https://arxiv.org/pdf/2102.04032.pdf)

In `General_Function_Generator_2D.ipynb`, we extend the above method to create 2D functions using the variational quantum circuits.

The work is done in [**Tequila**](https://github.com/aspuru-guzik-group/tequila) which is an Extensible Quantum Information and Learning Architecture where the main goal is to simplify and accelerate implementation of new ideas for quantum algorithms. The above tutorials can also be found in the [Tequila-Tutorials](https://github.com/aspuru-guzik-group/tequila-tutorials) repository.

