---
title: "Bayesian identification of nonseparable Hamiltonians with multiplicative noise using deep learning and reduced-order modeling"
collection: publications
permalink: /publication/2024-hamiltonian
excerpt:
date: 2024-10-01
venue: 'Computer Methods in Applied Mechanics and Engineering'
paperurl: 'https://www.sciencedirect.com/science/article/pii/S004578252400450X'
citation: 'Galioto, Nicholas, et al. "Bayesian identification of nonseparable Hamiltonians with multiplicative noise using deep learning and reduced-order modeling." <i>Computer Methods in Applied Mechanics and Engineering</i> 430 (2024): 117194.'
---

This paper presents a structure-preserving Bayesian approach for learning nonseparable Hamiltonian systems using stochastic dynamic models allowing for statistically-dependent, vector-valued additive and multiplicative measurement noise. The approach is comprised of three main facets. First, we derive a Gaussian filter for a statistically-dependent, vector-valued, additive and multiplicative noise model that is needed to evaluate the likelihood within the Bayesian posterior. Second, we develop a novel algorithm for cost-effective application of Bayesian system identification to high-dimensional systems. Third, we demonstrate how structure-preserving methods can be incorporated into the proposed framework, using nonseparable Hamiltonians as an illustrative system class. We assess the method's performance based on the forecasting accuracy of a model estimated from single-trajectory data. We compare the Bayesian method to a state-of-the-art machine learning method on a canonical nonseparable Hamiltonian model and a chaotic double pendulum model with small, noisy training datasets. The results show that using the Bayesian posterior as a training objective can yield upwards of 724 times improvement in Hamiltonian mean squared error using training data with up to 10% multiplicative noise compared to a standard training objective. Lastly, we demonstrate the utility of the novel algorithm for parameter estimation of a 64-dimensional model of the spatially-discretized nonlinear Schrödinger equation with data corrupted by up to 20% multiplicative noise.

[Download paper here](http://ngalioto.github.io/files/galioto2024hamiltonian.pdf)

Recommended BibTeX entry:
```bibtex
@article{galioto2024bayesian,
  title={Bayesian identification of nonseparable {H}amiltonians with multiplicative noise using deep learning and reduced-order modeling},
  author={Galioto, Nicholas and Sharma, Harsh and Kramer, Boris and Gorodetsky, Alex Arkady},
  journal={Computer Methods in Applied Mechanics and Engineering},
  volume = {430},
  pages = {117194},
  year = {2024},
  issn = {0045-7825}
}
```