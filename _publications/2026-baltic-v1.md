---
title: "baltic: the Backronymed Adaptable Lightweight Tree vIsualisation Code"
collection: publications
category: manuscripts
permalink: /publication/2026-baltic-v1
date: 2026-09-22
venue: 'bioRxiv'
paperurl: 'https://www.biorxiv.org/content/10.64898/2026.09.20.752947v1'
localurl: 'http://evogytis.github.io/files/2026-baltic-v1-preprint.pdf'
citation: 'Potter BI, Gangavarapu K, Torres Jimenez MF, Bell SM, <b>Dudas G</b>, 2026. &quot;baltic: the Backronymed Adaptable Lightweight Tree vIsualisation Code&quot;. <i>bioRxiv</i> 2026.09.20.752947'
doi: 10.64898/2026.09.20.752947
tags:
  - methods
---

For ten years, baltic (Backronymed Adaptable Lightweight Tree vIsualization Code) has been used to make annotated phylogeny figures in molecular epidemiology, including during the West African Ebola epidemic, the Zika epidemic in the Americas, and the SARS-CoV-2 pandemic, as well as other fields. 
At its core, baltic is a Python library used for the efficient parsing, traversal, manipulation, and visualisation of phylogenetic trees. 
It is a small library with few dependencies that reads tree formats common in phylodynamic analyses and gives the user leverage to interact with a lightweight tree data structure to produce publication-ready figures with matplotlib. 
We present baltic v1.0, its first formally released and documented version. 
baltic reads and writes BEAST Nexus, Newick, and Nextstrain/Auspice JSON, and can process large BEAST posterior tree files in parallel to extract user-defined posterior statistics. 
The same objects are used for tree manipulation and for plotting in a single script. 
New to this release: a set of rooting methods (midpoint rooting, rerooting on any branch, and root-to-tip regression); support for reticulate evolution, with reassortment and recombination edges; and composite figures that combine a tree with other data, such as Müller plots, skygrid plots, tanglegrams, and plots connecting trees to maps. 
The release includes a documentation site with an API reference, tutorials, and a matplotlib-style gallery of worked examples.