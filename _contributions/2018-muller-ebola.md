---
title: "Inferring time-dependent migration and coalescence patterns from genetic sequence and predictor data in structured populations"
collection: contributions
permalink: /contributions/2018-muller-ebola
date: 2018-06-14
venue: 'bioRxiv'
paperurl: 'https://www.biorxiv.org/content/early/2018/06/14/342329'
citation: 'Mueller NF, <b>Dudas G</b>, Stadler T, 2018. &quot;Inferring time-dependent migration and coalescence patterns from genetic sequence and predictor data in structured populations&quot;. bioRxiv: 342329.'
doi: 10.1101/342329
tags:
  - Ebola virus
  - genomic epidemiology
  - phylogeography
  - methods
---


Population dynamics can be inferred from genetic sequence data using phylodynamic methods.
These methods typically quantify the dynamics in unstructured populations or assume the parameters describing the dynamics to be constant through time in structured populations.
Inference methods allowing for structured populations and parameters to vary through time involve many parameters which have to be inferred.
Each of these parameters might be however only weakly informed by data.
Here we introduce an approach that uses so-called predictors, such as geographic distance between locations, within a generalized linear model to inform the population dynamic parameters, namely the time-varying migration rates and effective population sizes under the marginal approximation of the structured coalescent.
By using simulations, we show that we are able to reliably infer the parameters from phylogenetic trees.
We then apply this framework to a previously described Ebola virus dataset.
We infer incidence to be the strongest predictor for effective population size and geographic distance the strongest predictor for migration.
This allows us to show not only on simulated data, but also on real data, that we are able to identify reasonable predictors.
Overall, we provide a novel method that allows to identify predictors for migration rates and effective population sizes and to use these predictors to quantify migration rates and effective population sizes.
Its implementation as part of the BEAST2 software package MASCOT allows to jointly infer population dynamics within structured populations, the phylogenetic tree, and evolutionary parameters.
