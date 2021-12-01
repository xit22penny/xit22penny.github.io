---
title: "StoCast: Stochastic Disease Forecasting With Progression Uncertainty"
collection: publications
permalink: /publication/2021-stocast
excerpt: '<b>Xian Teng</b>, Sen Pei and Yu-Ru Lin (2021). &quot;StoCast: Stochastic Disease Forecasting With Progression Uncertainty.&quot; <i>IEEE Journal of Biomedical and Health Informatics</i>. vol. 25, no. 3, pp. 850-861, March 2021. ([link](https://ieeexplore.ieee.org/document/9132696), [pdf](/files/pdf/research/2021-stocast.pdf), [github](https://github.com/picsolab/StoCast))'
date: 2021-03-01
venue: 'IEEE Journal of Biomedical and Health Informatics'
# citation: '<b>Xian Teng</b>, Sen Pei and Yu-Ru Lin (2021). &quot;StoCast: Stochastic Disease Forecasting With Progression Uncertainty.&quot; <i>IEEE Journal of Biomedical and Health Informatics</i>. vol. 25, no. 3, pp. 850-861, March 2021. doi: 10.1109/JBHI.2020.3006719.'
---



## Abstract

 Forecasting patients' disease progressions with rich longitudinal clinical data has drawn much attention in recent years due to its impactful application in healthcare and the medical field. Researchers have tackled this problem by leveraging traditional machine learning, statistical techniques and deep learning based models. However, existing methods suffer from either deterministic internal structures or over-simplified stochastic components, failing to deal with complex uncertain scenarios such as progression uncertainty (i.e., multiple possible trajectories) and data uncertainty (i.e., imprecise observations and misdiagnosis). To overcome these major uncertainty issues, we propose a novel deep generative model, Stochastic Disease Forecasting Model (STOCAST), along with an associated neural network architecture STOCASTNET, that can be trained efficiently via stochastic optimization techniques. Our STOCAST model uses internal stochastic components to deal with departures of observed data from patients' true health states, and more importantly, is able to produce a comprehensive estimate of future disease progression trajectories. Based on two public datasets related to Alzheimer's disease and Parkinson's disease, we demonstrate how our STOCAST model achieves robust and superior performance than deterministic baseline approaches, and conveys richer information that can potentially assist doctors to make decisions with greater confidence in a complex uncertain scenario.