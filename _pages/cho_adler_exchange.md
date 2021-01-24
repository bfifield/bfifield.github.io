---
layout: archive
title: "Notes on Cho and Liu (2018) and Adler and Wang (2019)"
permalink: /cho_adler_exchange/
author_profile: true
---

A recent article published in Physica A by Cho and Liu (“[Sampling from complicated and unknown distributions: Monte Carlo and Markov Chain Monte Carlo methods for redistricting](https://www.sciencedirect.com/science/article/abs/pii/S0378437118304163)”) claims that the redistricting MCMC sampler introduced by Fifield, Higgins, Imai, and Tarr in "[Automated Redistricting Simulation Using Markov Chain Monte Carlo](https://imai.fas.harvard.edu/research/files/redist.pdf)" fails to randomly sample valid redistricting plans when reasonable population parity constraints are applied in a validation exercise. In a response article also published in Physica A (“[Response to Cho and Liu](https://www.sciencedirect.com/science/article/pii/S0378437118314055?via%3Dihub)”), Adler and Wang claim that Cho and Liu critically omit any discussion of methods that were available, discussed and analyzed in early and current drafts of Fifield et al. that improve the algorithm’s ability to randomly sample redistricting plans under constraints. 

Below are links to previous drafts of "[Automated Redistricting Simulation Using Markov Chain Monte Carlo](https://imai.fas.harvard.edu/research/files/redist.pdf)" (previously "A New Automated Redistricting Simulator Using Markov Chain Monte Carlo") to provide some additional clarity to the exchange. These drafts show that the methods Cho and Liu omit from their validation analysis were present in drafts of Fifield et al. dating back to 2014, and that those methods show reasonable evidence of random sampling from the target distribution across a series of population parity constraints in both validation exercises and applied examples.

* [July 2014](/files/redist-July20-2014.pdf)
* [December 2014](/files/redist-December16-2014.pdf)
* [March 2017](redist-March15-2017.pdf)

![](/files/sims.jpeg)
