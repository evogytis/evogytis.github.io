---
title: "On the importance of assessing topological convergence in Bayesian phylogenetic inference"
collection: contributions
category: manuscripts
permalink: /contributions/2024-brusselmans-topology
date: 2024-02-18
venue: 'arXiv'
paperurl: 'https://arxiv.org/abs/2402.11657'
citation: 'Brusselmans M, Carvalho LM, Hong SL, Gao J, Matsen IV FA, Rambaut A, Lemey P, Suchard MA, <b>Dudas G</b>, Baele G, 2024. &quot;On the importance of assessing topological convergence in Bayesian phylogenetic inference&quot;. <i>arXiv</i> 2402.11657.'
doi: 10.48550/arXiv.2402.11657
tags:
  - Ebola virus
  - methods
---

Modern phylogenetics research is often performed within a Bayesian framework, using sampling algorithms such as Markov chain Monte Carlo (MCMC) to approximate the posterior distribution. 
These algorithms require careful evaluation of the quality of the generated samples. 
Within the field of phylogenetics, one frequently adopted diagnostic approach is to evaluate the effective sample size (ESS) and to investigate trace graphs of the sampled parameters. 
A major limitation of these approaches is that they are developed for continuous parameters and therefore incompatible with a crucial parameter in these inferences: the tree topology. 
Several recent advancements have aimed at extending these diagnostics to topological space. 
In this short reflection paper, we present a case study illustrating how these topological diagnostics can contain information not found in standard diagnostics, and how decisions regarding which of these diagnostics to compute can impact inferences regarding MCMC convergence and mixing. 
Given the major importance of detecting convergence and mixing issues in Bayesian phylogenetic analyses, the lack of a unified approach to this problem warrants further action, especially now that additional tools are becoming available to researchers.