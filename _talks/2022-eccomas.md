---
title: "Accounting for model uncertainty in the identification of partially known models"
collection: talks
type: "Conference presentation"
permalink: /talks/2022-eccomas
venue: "NOVA Spektrum"
date: 2022-06-09
location: "Oslo, Norway"
---

[Minisymposium](https://www.eccomas2022.org/frontal/ProgMS.asp?id=17) presentation at [8th European Congress on Computational Methods in Applied Sciences and Engineering (ECCOMAS)](https://www.eccomas2022.org/frontal/).

In problems of model inadequacy, where only a portion of the full model is known, we would oftentimes like to learn the unknown component of the model. Many of the existing system ID approaches consider only the discrepancy between the model output and the data (i.e., measurement uncertainty), and they neglect the effects of the uncertainty present in the unknown model itself. To address this shortcoming, we present a system ID modeling framework for dynamical systems that is able to account for the three different types of uncertainty that enter into a system ID problem: parameter, model, and measurement uncertainty.  Our approach directly accounts for model errors/uncertainties by modeling the dynamics as a stochastic process.

This modeling choice allows the uncertainty of our state estimate to inform the posterior distribution over the model parameters. Incorporating this additional information results in the posterior now assigning low probability to models that amplify the state uncertainty too quickly. This change can yield benefits over least squares estimation for any level of model expressiveness. In the case of an extremely expressive model, the least squares method will overfit the data unless additional work is performed to add regularization to the objective function. Our method doesn't require this extra step, and instead automatically penalizes the large output variance commonly produced by overfit models, even if the output matches the data closely.  On the other end where the  model form is not expressive enough to fit the data, the least squares objective struggles to properly prioritize certain models over others since they are all incapable of fitting the data. Our method, however, recognizes when it's not possible to fit all of the data and will therefore assign high probability to models that can give the best estimate over the longest period of time. Oftentimes, these models are far from the least squares optimum but are desirable models in tracking applications where data are periodically available to update the state estimate.

In this presentation, we consider a model inadequacy problem, where the model is partially known and we'd like to learn the remaining part. We compare the performance of our posterior distribution to the performance of the least squares objective on several test examples and demonstrate that our method is better able to estimate the unknown component of the model.
