---
title: "HIPSTR: highest independent posterior subtree reconstruction in TreeAnnotator X"
collection: contributions
category: manuscripts
permalink: /contributions/2024-baele-hipstr
date: 2024-12-10
venue: 'bioRxiv'
paperurl: 'https://www.biorxiv.org/content/10.1101/2024.12.08.627395v1'
citation: 'Baele G, Carvalho LM, Brusselmans M, <b>Dudas G</b>, Ji X, McCrone JT, Lemey P, Suchard M, Rambaut A, 2024. &quot;HIPSTR: highest independent posterior subtree reconstruction in TreeAnnotator X&quot;. <i>bioRxiv</i> 2024.12.08.627395.'
doi: 10.1101/2024.12.08.627395
tags:
  - methods
---


In Bayesian phylogenetic and phylodynamic studies it is common to summarise the posterior distribution of trees with a time-calibrated consensus phylogeny. 
While the maximum clade credibility (MCC) tree is often used for this purpose, we here show that a novel consensus tree method - the highest independent posterior subtree reconstruction, or HIPSTR - contains consistently higher supported clades over MCC. 
We also provide faster computational routines for estimating both consensus trees in an updated version of TreeAnnotator X, an open-source software program that summarizes the information from a sample of trees and returns many helpful statistics such as individual clade credibilities contained in the consensus tree. 
HIPSTR and MCC reconstructions on two Ebola virus and two SARS-CoV-2 data sets show that HIPSTR yields consensus trees that consistently contain clades with higher support compared to MCC trees. 
The MCC trees regularly fail to include several clades with very high posterior probability (>=0.95) as well as a large number of clades with moderate to high posterior probability (>=0.50), whereas HIPSTR achieves near-perfect performance in this respect. 
HIPSTR also exhibits favorable computational performance over MCC in TreeAnnotator X. 
Comparison to the recently developed CCD0-MAP algorithm yielded mixed results, and requires more in-depth exploration in follow-up studies. 
TreeAnnotator X -- which is part of the BEAST X (v10.5.0) software package -- is available at https://github.com/beast-dev/beast-mcmc/releases.