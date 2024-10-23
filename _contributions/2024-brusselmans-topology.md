---
title: "On the importance of assessing topological convergence in Bayesian phylogenetic inference"
collection: contributions
category: manuscripts
permalink: /contributions/2024-brusselmans-topology
date: 2024-10-15
venue: 'Virus Evolution'
paperurl: 'https://academic.oup.com/ve/advance-article/doi/10.1093/ve/veae081/7822753'
citation: 'Brusselmans M, Carvalho LM, Hong SL, Gao J, Matsen IV FA, Rambaut A, Lemey P, Suchard MA, <b>Dudas G</b>, Baele G, 2024. &quot;On the importance of assessing topological convergence in Bayesian phylogenetic inference&quot;. <i>Virus Evolution</i>: veae081.'
doi: 10.1093/ve/veae081
tags:
  - Ebola virus
  - methods
---

Modern phylogenetics research is often performed within a Bayesian framework, using sampling algorithms such as Markov chain Monte Carlo (MCMC) to approximate the posterior distribution. 
These algorithms require careful evaluation of the quality of the generated samples. 
Within the field of phylogenetics, one frequently adopted diagnostic approach is to evaluate the effective sample size (ESS) and to investigate trace graphs of the sampled parameters. 
A major limitation of these approaches is that they are developed for continuous parameters and therefore incompatible with a crucial parameter in these inferences: the tree topology. Several recent advancements have aimed at extending these diagnostics to topological space. 
In this reflection paper, we present two case studies – one on Ebola virus and one on HIV – illustrating how these topological diagnostics can contain information not found in standard diagnostics, and how decisions regarding which of these diagnostics to compute can impact inferences regarding MCMC convergence and mixing. 
Our results show the importance of running multiple replicate analyses and of carefully assessing topological convergence using the output of these replicate analyses. 
To this end, we illustrate different ways of assessing and visualizing the topological convergence of these replicates. 
Given the major importance of detecting convergence and mixing issues in Bayesian phylogenetic analyses, the lack of a unified approach to this problem warrants further action, especially now that additional tools are becoming available to researchers.