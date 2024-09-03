---
title: 'Welcome to behind the scenes'
date: 2018-01-16
permalink: /posts/2018/01/greetings/
tags:
  - MERS coronavirus
---

I've decided to launch my website with a short "behind the scenes" look at the most recent paper on MERS-CoV, which has recently been published in eLife.


Motivation
----

The goal of the [mers-structure](https://github.com/blab/mers-structure) project was to understand the epidemiology of MERS-CoV epidemiology.
It began through a combination of a [strong argument about MERS-CoV epidemiology](http://epidemic.bio.ed.ac.uk/MERS-CoV_camel_source), contentious findings by other groups (from both [case-based](http://www.pnas.org/content/113/32/9081.short) and [sequence-based](https://www.nature.com/articles/srep25049) studies), wanting to learn [BEAST2](https://www.beast2.org/) (specifically Tim Vaughan's [structured coalescent implementation](http://tgvaughan.github.io/MultiTypeTree/)), and seeing a publication niche that wasn't occupied.
The timing could have been ever so [slightly better](https://www.nature.com/articles/emi201789), but when we started a sufficiently large number of MERS-CoV genomes sequenced from camels were already available on GenBank.


Progress
----

Like many other projects I've worked on, this MERS study went through a number of research digressions, bursts of activity, and periods of inactivity.
It started towards the end of 2016 summer and took well over a year from starting to publishing.
During 2016 I was helping out with a [review on Ebola virus evolution](https://www.nature.com/articles/nature19790) still finishing up the big [Ebola study](https://www.nature.com/articles/nature22040), and got involved with the [Zika in Florida study](https://www.nature.com/articles/nature22400), so not exactly wasting my time.
In addition, structured coalescent models mix [sloooooooow](https://academic.oup.com/bioinformatics/article/30/16/2272/2748160#83418423), so I usually ended up setting up runs that would take weeks and going away to work on something else.
I still think that the slow approach to doing projects is the way to go (with some exceptions), because it allows to flesh out ideas, cover your bases, and get the project to a point where you're happy with it.
My [influenza B study](https://academic.oup.com/mbe/article/32/1/162/2925578) took a similarly long period of time and is still one of my favourite projects.


Reviews
----

We submitted the MERS-CoV manuscript to eLife in early September 2017 instead of August because of my uncanny ability to disappear to Lithuania for holidays when I'm most needed.
Reviews took a while, but were with us by mid-October and were very positive.
Erik Volz and Cristophe Fraser were two of the three reviewers and suggested a number of improvements which we were actually happy (rather than reluctant) to implement.
Thanks to reviewer comments we ended up with extra figures of MERS-CoV trees reconstructed with the classic CTMC approach and structured coalescent with enforced equal deme sizes (neatly demonstrating where our inference power was coming from), as well as using different statistics in our ABC-like approach for R0 inference.


What I've learned
----

One of the most valuable things I've adopted during this project are [IPython cell and line magics](http://ipython.readthedocs.io/en/stable/interactive/magics.html) available in [Jupyter notebooks](http://jupyter.org/).
The ability to call other programs from inside the notebook environment adds another layer of reproducibility, much like [XMLs do for BEAST](http://science.sciencemag.org/content/353/6300/658.1).
Sure beats my previous approach of keeping a text editor open with commands I use frequently.

Structured coalescent and its approximations are very promising approaches to phylogenetic inference for specific problems and data situations.
I'm aware of at least one promising approach under development in [Tanja Stadler](https://www.bsse.ethz.ch/cevo/the-group/people/head.html)'s group.
Another indirect advantage of having to work with multitype trees (phylogenies with single-child nodes) during this project is that [baltic](https://github.com/blab/baltic) had to be [modified](https://github.com/blab/baltic/commit/c49686aa44ffea9a0e570e1793ff64e2551f7c6a#diff-6b8ebfe329fc93b57cc385a8d31e2acf) to deal with the different data structure.

Especially where inference is involved someone else will probably have done and done it better.
Largely because of my more evolutionary rather than epidemiological background I wasn't aware (enough) of packages like [PhyDyn](https://github.com/mrc-ide/PhyDyn) which we could have used from the start to do R0 inference properly rather than via the rather clunky ABC-like Monte Carlo approach.

[Julia](https://julialang.org/) might actually be as fast as advertised (under some conditions).
I've previously expressed [skepticism about Julia's speed](https://twitter.com/evogytis/status/477879696940859392) and wouldn't be surprised if my python kung fu isn't up to scratch when it comes to hardcore heavy-lifting NumPy-based computing, but the [simulation code I wrote in Julia](https://github.com/blab/mers-structure/blob/master/scripts/MERS.2_epi.ipynb) was both easy to write and ran pretty fast.
