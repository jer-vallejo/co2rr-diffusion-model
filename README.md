# co2rr-diffusion-model

This repository is not an application: it is a step-by-step numerical study of $\ce{CO2}$ transport toward an electrode during its electrochemical reduction. Each notebook explains the procedure and the functions it uses, and already includes the resulting plots, so there is no need to run it again.

If you want to run the code yourself, install the packages listed in requirements.txt. Then you can change the parameters as you like.

## Stages

**Stage 1 — Diffusion toward the electrode.** Numerical solution of the
one-dimensional diffusion equation, showing how $\ce{CO2}$ reaches the electrode
while it is consumed at the surface. Method: explicit finite differences.

**Stage 2 — Limits and steady state.** Analysis of the characteristic
time scales of reaction and diffusion.

**Stage 3 — Linear sweep voltammetry.** The rate constant, which was
constant in the previous stages, now depends exponentially on the
overpotential, and the overpotential changes linearly in
time. With this, the problem no longer has a simple analytical solution,
so it must be solved numerically. Method: implicit finite differences.