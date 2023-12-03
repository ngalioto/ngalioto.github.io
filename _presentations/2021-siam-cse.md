---
title: "Robust Bayesian inference by accounting for model error: with applications to Hamiltonian systems
models"
collection: presentations
type: "Conference presentation"
permalink: /talks/2021-siam-cse
date: 2021-03-04
location: "Virtual"
---

[Minisymposium](https://meetings.siam.org/sess/dsp_programsess.cfm?SESSIONCODE=70165) presentation at [SIAM Conference on Computational Science and Engineering (CSE21)](https://www.siam.org/conferences/cm/conference/cse21).

Central to any inference problem is the selection of an objective function. By and large, a least squares-based objective function that seeks to minimize the sum of the squared deviations of the model from the data is seen as the default choice. In this talk we show that such objectives are only optimal only for a narrow class of systems because they ignore either model error and/or measurement noise. We instead derive an optimal objective function using a probabilistic model of dynamical systems and provide a low-cost method of evaluating it. This optimal objective function is robust to noisy and/or sparse data and can outperform the most common existing methods of system identification. We then extend this result into the identification of Hamiltonian systems by equipping the objective with a structure-preserving symplectic integrator. Existing methods may use a symplectic integrator when validating their learned model but often neglect the fact that the data are generated from a symplectic process during the learning phase. We show that use of a symplectic integrator during the learning phase allows us to identify the equations of motion of a Hamiltonian system with less frequent data and with more certainty than possible otherwise.