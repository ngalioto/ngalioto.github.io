---
title: "Bayesian identification of Hamiltonian dynamics from symplectic data"
collection: publications
permalink: /publication/2020-hamiltonian
excerpt: 
date: 2020-12-14
venue: '59th IEEE Conference on Decision and Control'
paperurl: 'https://ieeexplore.ieee.org/abstract/document/9303852'
citation: 'Galioto, Nicholas, and Alex A. Gorodetsky. "Bayesian identification of Hamiltonian dynamics from symplectic data." <i>2020 59th IEEE Conference on Decision and Control (CDC)</i>. IEEE, 2020.'
---

We propose a Bayesian probabilistic formulation for system identification of Hamiltonian systems. This approach uses an approximate marginal Markov Chain Monte Carlo algorithm to directly discover a system Hamiltonian from data. Our approach improves upon existing methods in two ways: first we encode the fact that the data generating process is symplectic directly into our learning objective, and second we utilize a learning objective that simultaneously accounts for unknown parameters, model form, and measurement noise. This objective is the log marginal posterior of a probabilistic model that embeds a symplectic and reversible integrator within an uncertain dynamical system. We demonstrate that the resulting learning problem yields dynamical systems that have improved accuracy and reduced predictive uncertainty compared to existing state-of-the-art approaches. Simulation results are shown on the Hénon-Heiles Hamiltonian system.

[Download paper here](http://ngalioto.github.io/files/galioto2020hamiltonian.pdf)

Recommended BibTeX entry:
```bibtex
@INPROCEEDINGS{galioto2020hamiltonian,
  author={Galioto, Nicholas and Gorodetsky, Alex A.},
  booktitle={2020 59th IEEE Conference on Decision and Control (CDC)}, 
  title={Bayesian Identification of {H}amiltonian Dynamics from Symplectic Data}, 
  year={2020},
  volume={},
  number={},
  pages={1190-1195},
  doi={10.1109/CDC42340.2020.9303852}
}
```