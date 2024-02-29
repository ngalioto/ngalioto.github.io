---
title: "Bayesian system ID: optimal management of parameter, model, and measurement uncertainty"
collection: publications
permalink: /publication/2020-bayesian
# excerpt: 
date: 2020-09-07
venue: 'Nonlinear Dynamics'
paperurl: 'https://link.springer.com/article/10.1007/s11071-020-05925-8'
citation: 'Nicholas Galioto and Alex Arkady Gorodetsky. Bayesian system ID: optimal management of parameter, model, and measurement uncertainty. <i>Nonlinear Dynamics</i>, 102(1):241-267, 2020.'
---

System identification of dynamical systems is often posed as a least squares minimization problem. The aim of these optimization problems is typically to learn either propagators or the underlying vector fields from trajectories of data. In this paper, we study a first principles derivation of appropriate objective formulations for system identification based on probabilistic principles. We compare the resulting inference objective to those used by emerging data-driven methods based on dynamic mode decomposition (DMD) and system identification of nonlinear dynamics (SINDy). We show that these and related least squares formulations are specific cases of a more general objective function. We also show that the more general objective function yields more robust and reliable recovery in the presence of sparse data and noisy measurements. We attribute this success to an explicit accounting of imperfect model forms, parameter uncertainty, and measurement uncertainty. We study the computational complexity of an approximate marginal Markov Chain Monte Carlo method to solve the resulting inference problem and numerically compare our results on a number of canonical systems: linear pendulum, nonlinear pendulum, the Van der Pol oscillator, the Lorenz system, and a reaction–diffusion system. The results of these comparisons show that in cases where DMD and SINDy excel, the Bayesian approach performs equally well, and in cases where DMD and SINDy fail to produce reasonable results, the Bayesian approach remains robust and can still deliver reliable results.

[Download paper here](http://ngalioto.github.io/files/galioto2020bayesian.pdf)

Recommended BibTeX entry:
```bibtex
@article{galioto2020bayesian,
  title={Bayesian system {ID}: optimal management of parameter, model, and measurement uncertainty},
  author={Galioto, Nicholas and Gorodetsky, Alex Arkady},
  journal={Nonlinear Dynamics},
  volume={102},
  number={1},
  pages={241--267},
  year={2020},
  publisher={Springer}
}
```