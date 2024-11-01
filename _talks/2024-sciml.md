---
title: "Discovery of cellular reprogramming methodology through single-cell foundation models"
collection: talks
type: "Seminar talk"
permalink: /talks/2024-sciml
venue: "Walter E. Lay Auto Lab"
date: 2024-11-01
location: "Ann Arbor, MI, USA"
---

Presentation at the [Frontiers of Scientific Machine Learning Lecture Series](https://events.umich.edu/event/127729). The slides can be found [here](../files/2024-sciml-slides.pdf), and a recording of the presentation [here](https://www.youtube.com/@FSMLSeminarsatUMich).

Cell reprogramming, the transformation of a cell from one cell type to another through the introduction of exogenous transcription factors (TFs), is a rapidly developing research area that could lead to groundbreaking therapeutic technologies in areas such as tissue regeneration, disease modeling, and personalized medicine. However, there still exist many challenges obstructing its practical viability. Discovering which TFs induce reprogramming requires a combinatorial search, and testing a single
candidate set of TFs experimentally can cost tens of thousands of dollars and take multiple months. Moreover, even when an effective set of TFs is known, cell conversion efficiency lies only around 5%.

Faced with these challenges, researchers have developed computational surrogate models to rapidly explore the TF search space at a fraction of the cost of wet lab experimentation. Unfortunately, these models have seen limited success in practice due to the difficulty of capturing the complex gene-gene interactions within the cell, most of which are still not well-understood. With the recent high-profile rise of transformer-based foundation models for natural language, researchers are now turning to the transformer to push past current performance limitations in a wide range of digital biology tasks, including cell reprogramming. Of particular interest in these models is the attention mechanism, which is potentially well-suited for capturing long-range gene-gene interactions at a higher fidelity than previously possible. In this talk, I will describe how the transformer architecture has been adapted for cellular biology and analyze the utility of one such model, Geneformer, in identifying TFs for cell reprogramming. Specifically, I will present the results of an in silico perturbation experiment for reprogramming fibroblast cells to hematopoietic stem cells and compare the outcomes to experimental results found in the literature. I will conclude the talk with a discussion of the drawbacks and limitations of the Geneformer model and provide an assessment of what will be needed in the future for digital biology to fully reap the benefits of large-scale foundation models.