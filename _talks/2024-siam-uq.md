---
title: "Correcting for Error in Reduced-Order Modeling Using Experimental Partial Observations and Bayesian System ID"
collection: talks
type: "Conference presentation"
permalink: /talks/2024-siam-uq
venue: "Savoia Excelsior Palace Trieste and Stazione Marittima"
date: 2024-02-28
location: "Trieste, Italy"
---

[Minisymposium](https://meetings.siam.org/sess/dsp_programsess.cfm?SESSIONCODE=78429) presentation at [SIAM Conference on Uncertainty Quantification (UQ24)](https://www.siam.org/conferences/cm/conference/uq24). The slides can be found [here](../files/2024-siam-uq-slides.pdf).

In the traditional reduced-order modeling setting, full-field data collected from simulation of a full-order model (FOM) are used to estimate a low-dimensional approximation of the FOM. In practice, however, FOMs are almost always inaccurate, uncertain, or partially unknown, which limits the level of accuracy that can be achieved by a reduced-order model (ROM). Data-driven estimation techniques can improve the FOM accuracy but are challenging for two main reasons. The first is that estimation is computationally burdensome since it usually involves many forward evaluations of an expensive FOM. The second is that the system of interest can often only be measured through noisy partial observations that introduce high uncertainty into the estimation problem. In this work, we propose a method for learning reduced-order closure models that is capable of addressing both of these challenges. Firstly, evaluation of the FOM is avoided by performing estimation in the reduced-dimensional space such that only forward evaluations of the ROM are needed. Secondly, we use a Bayesian learning framework that addresses the model uncertainty of the ROM and the measurement uncertainty of the noisy partial observations to deliver robust estimation under uncertainty. The merits of this method will be demonstrated on numerical examples of systems of partial differential equations.