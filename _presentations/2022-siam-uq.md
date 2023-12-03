---
title: "Bayesian learning of stochastic dynamical models for quantities of interest"
collection: presentations
type: "Conference presentation"
permalink: /talks/2022-siam-uq
venue: "Westin Peachtree Plaza"
date: 2022-04-15
location: "Atlanta, GA, USA"
---

[Minisymposium](https://meetings.siam.org/sess/dsp_programsess.cfm?SESSIONCODE=73526) presentation at [SIAM Conference on Uncertainty Quantification (UQ22)](https://www.siam.org/conferences/cm/conference/uq22).

We present a formulation for the identification of dynamical systems that is derived from probabilistic principles and accounts for three types of uncertainty present in system ID: parameter, model, and measurement. Most existing system ID methods will only consider uncertainty in the data/output of the system. In contrast, we additionally account for the uncertainty present in our dynamics/parameters by modeling the system as a stochastic process. This modeling choice can be shown to produce a regularizing term in the posterior that can counteract multi-modality and make optimization/sampling easier. Furthermore, this regularization is derived directly from the model of the system rather than from heuristic techniques such as penalizing the parameter norm. Recent algorithmic developments include parallel tempering MCMC sampling techniques that can help overcome the difficulties of sampling complicated posteriors. We present the benefits of this method for the identification of nonlinear dynamics, including chaos and PDEs. When considering high-dimensional systems, we demonstrate our method’s applicability to identifying the dynamics of a quantity of interest, which is oftentimes desirable to avoid the computational expense of full-field simulation.
