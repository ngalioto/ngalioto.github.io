---
title: "A switching Kalman filter approach to online mitigation and correction sensor corruption for inertial navigation"
collection: publications
permalink: /publication/2024-switching
# excerpt:
date: 2024-12-10
venue: 'arXiv'
paperurl: 'https://arxiv.org/pdf/2412.06601'
citation: 'Mustaev, Artem, et al. "A switching Kalman filter approach to online mitigation and correction sensor corruption for inertial navigation." arXiv preprint arXiv:2412.06601 (2024).'
---

This paper introduces a novel approach to detect and address faulty or corrupted external sensors in the context of inertial navigation by leveraging a switching Kalman Filter combined with parameter augmentation. Instead of discarding the corrupted data, the proposed method retains and processes it, running multiple observation models simultaneously and evaluating their likelihoods to accurately identify the true state of the system. We demonstrate the effectiveness of this approach to both identify the moment that a sensor becomes faulty and to correct for the resulting sensor behavior to maintain accurate estimates. We demonstrate our approach on an application of balloon navigation in the atmosphere and shuttle reentry. The results show that our method can accurately recover the true system state even in the presence of significant sensor bias, thereby improving the robustness and reliability of state estimation systems under challenging conditions. We also provide a statistical analysis of problem settings to determine when and where our method is most accurate and where it fails.

[Download paper here](http://ngalioto.github.io/files/mustaev2024switching.pdf)

Recommended BibTeX entry:
```bibtex
@article{mustaev2024switching,
  title={A switching {K}alman filter approach to online mitigation and correction sensor corruption for inertial navigation},
  author={Mustaev, Artem and Galioto, Nicholas and Boler, Matt and Jakeman, John D and Safta, Cosmin and Gorodetsky, Alex},
  journal={arXiv preprint arXiv:2412.06601},
  year={2024}
}
```