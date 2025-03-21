---
title: "Likelihood-based generalization of Markov parameter estimation and multiple shooting objectives in system identification"
collection: publications
permalink: /publication/2024-likelihood
# excerpt:
date: 2024-03-24
venue: 'Physica D: Nonlinear Phenomena'
paperurl: 'https://www.sciencedirect.com/science/article/pii/S0167278924000976'
citation: 'Galioto, Nicholas, and Alex Arkady Gorodetsky. "Likelihood-based generalization of Markov parameter estimation and multiple shooting objectives in system identification." <i>Physica D: Nonlinear Phenomena</i> 462 (2024): 134146.'
---

This paper considers the problem of system identification (ID) of linear and nonlinear non-autonomous systems from noisy and sparse data. We propose and analyze an objective function derived from a Bayesian formulation for learning a hidden Markov model with stochastic dynamics. We then analyze this objective function in the context of several state-of-the-art approaches for both linear and nonlinear system ID. In the former, we analyze least squares approaches for Markov parameter estimation, and in the latter, we analyze the multiple shooting approach. We demonstrate the limitations of the optimization problems posed by these existing methods by showing that they can be seen as special cases of the proposed optimization objective under certain simplifying assumptions: conditional independence of data and zero model error. Furthermore, we observe that our proposed approach has improved smoothness and inherent regularization that make it well-suited for system ID and provide mathematical explanations for these characteristics' origins. Finally, numerical simulations demonstrate a mean squared error over 8.7 times lower compared to multiple shooting when data are noisy and/or sparse. Moreover, the proposed approach can identify accurate and generalizable models even when there are more parameters than data or when the underlying system exhibits chaotic behavior.

[Download paper here](http://ngalioto.github.io/files/galioto2024likelihood.pdf)

Recommended BibTeX entry:
```bibtex
@article{galioto2024likelihood,
  title={Likelihood-based generalization of {M}arkov parameter estimation and multiple shooting objectives in system identification},
  author={Galioto, Nicholas and Gorodetsky, Alex Arkady},
  journal={Physica D: Nonlinear Phenomena},
  volume = {462},
  pages = {134146},
  year = {2024},
  issn = {0045-7825}
}
```