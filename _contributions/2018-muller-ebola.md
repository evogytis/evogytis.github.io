---
title: "Inferring time-dependent migration and coalescence patterns from genetic sequence and predictor data in structured populations"
collection: contributions
category: manuscripts
permalink: /contributions/2018-muller-ebola
date: 2019-08-14
venue: 'Virus Evolution'
paperurl: 'https://academic.oup.com/ve/article/5/2/vez030/5549805'
citation: 'Müller NF, <b>Dudas G</b>, Stadler T, 2019. &quot;Inferring time-dependent migration and coalescence patterns from genetic sequence and predictor data in structured populations&quot;. <i>Virus Evolution</i> 5(2): vez030.'
doi: 10.1093/ve/vez030
tags:
  - Ebola virus
  - genomic epidemiology
  - phylogeography
  - methods
---


Population dynamics can be inferred from genetic sequence data by using phylodynamic methods.
These methods typically quantify the dynamics in unstructured populations or assume migration rates and effective population sizes to be constant through time in structured populations.
When considering rates to vary through time in structured populations, the number of parameters to infer increases rapidly and the available data might not be sufficient to inform these.
Additionally, it is often of interest to know what predicts these parameters rather than knowing the parameters themselves.
Here, we introduce a method to  infer the predictors for time-varying migration rates and effective population sizes by using a generalized linear model (GLM) approach under the marginal approximation of the structured coalescent.
Using simulations, we show that our approach is able to reliably infer the model parameters and its predictors from phylogenetic trees.
Furthermore, when simulating trees under the structured coalescent, we show that our new approach outperforms the discrete trait GLM model.
We then apply our framework to a previously described Ebola virus dataset, where we infer the parameters and its predictors from genome sequences while accounting for phylogenetic uncertainty.
We infer weekly cases to be the strongest predictor for effective population size and geographic distance the strongest predictor for migration.
This approach is implemented as part of the BEAST2 package MASCOT, which allows us to jointly infer population dynamics, i.e. the parameters and predictors, within structured populations, the phylogenetic tree, and evolutionary parameters.
