---
title: "HIPSTR: highest independent posterior subtree reconstruction in TreeAnnotator X"
collection: contributions
category: manuscripts
permalink: /contributions/2025-baele-hipstr
date: 2025-09-09
venue: 'Bioinformatics'
paperurl: 'https://academic.oup.com/bioinformatics/advance-article/doi/10.1093/bioinformatics/btaf488/8250098'
citation: 'Baele G, Carvalho LM, Brusselmans M, <b>Dudas G</b>, Ji X, McCrone JT, Lemey P, Suchard M, Rambaut A, 2025. &quot;HIPSTR: highest independent posterior subtree reconstruction in TreeAnnotator X&quot;. <i>Bioinformatics</i>, btaf488.'
doi: 10.1093/bioinformatics/btaf488
tags:
  - methods
---

Summary
In Bayesian phylogenetic and phylodynamic studies it is common to summarise the posterior distribution of trees with a time-calibrated summary phylogeny. 
While the maximum clade credibility (MCC) tree is often used for this purpose, we here show that a novel summary tree method—the highest independent posterior subtree reconstruction, or HIPSTR—contains consistently higher supported clades over MCC. 
We also provide faster computational routines for estimating both summary trees in an updated version of TreeAnnotator X, an open-source software program that summarizes the information from a sample of trees and returns many helpful statistics such as individual clade credibilities contained in the summary tree.

Results
HIPSTR and MCC reconstructions on two Ebola virus and two SARS-CoV-2 data sets show that HIPSTR yields summary trees that consistently contain clades with higher support compared to MCC trees. 
The MCC trees regularly fail to include several clades with very high posterior probability ($\geq$ 95) as well as a large number of clades with moderate to high posterior probability ($\geq$ 50%), whereas HIPSTR—in particular its majority-rule extension MrHIPSTR –achieves near-perfect performance in this respect. 
HIPSTR and MrHIPSTR also exhibit favorable computational performance over MCC in TreeAnnotator X. 
Comparison to the recent CCD0-MAP algorithm yielded mixed results and requires a more in-depth investigation in follow-up studies.

Availability and implementation
TreeAnnotator X is available as part of the BEAST X (v10.5.0) software package, available at https://github.com/beast-dev/beast-mcmc/releases, and on Zenodo (DOI: https://doi.org/10.5281/zenodo.4895234).