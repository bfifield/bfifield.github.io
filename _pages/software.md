---
layout: archive
title: "Software"
permalink: /software/
author_profile: true
---

## R Packages:

<details>
<summary><a href="http://cran.r-project.org/web/packages/redist/"><b>redist: Computational Algorithms for Redistricting Simulation</b></a> (with <a href = "https://scholar.harvard.edu/christopherkenny/home">Christopher T. Kenny</a>, <a href = "https://corymccartan.github.io/">Cory McCartan</a>, Alexander Tarr, and <a href = "https://imai.fas.harvard.edu/">Kosuke Imai</a></summary>

redist is a publicly available R package that enables researchers to statistically simulate congressional redistricting plans using Markov chain Monte Carlo and Sequential Monte Carlo techniques. This includes the implementation of substantive constraints in the redistricting process such as geographic compactness and population parity requirements, as well as efficient simulation methods such as simulated tempering algorithms. Tools for analysis such as inverse probability reweighting and plotting functionality are included. The package implements methods found in Fifield, Higgins, Imai, and Tarr (JCGS, 2020), "<a href = "https://imai.fas.harvard.edu/research/files/redist.pdf">Automated Redistricting Simulation Using Markov Chain Monte Carlo</a>," Fifield, Imai, Kawahara, and Kenny (SPP, 2020), “<a href = "https://imai.fas.harvard.edu/research/files/enumerate.pdf">The Essential Role of Empirical Validation in Legislative Redistricting Simulation </a>”, and McCartan and Imai, “<a href = "https://imai.fas.harvard.edu/research/files/SMCredist.pdf">Sequential Monte Carlo for Sampling Balanced and Compact Redistricting Plans</a>“. 

Type <tt>install.packages("redist")</tt> to install in R. Please also see the <a href = "https://github.com/redistricting/redist">redist GitHub page</a> for the most stable development release.

</details>

[**fastLink: Fast Probabilistic Record Linkage**](https://cran.r-project.org/web/packages/fastLink/) (with [Ted Enamorado](https://www.tedenamorado.com/) and [Kosuke Imai](https://imai.fas.harvard.edu/))

fastLink is a publicly available R package that enables researchers to merge two data sets using a fast implementation of the Fellegi-Sunter probabilistic record linkage model that allows for missing data and the inclusion of auxiliary information. This includes functionalities to conduct a merge of two data sets under the Fellegi-Sunter model using the Expectation-Maximization algorithm. In addition, tools for preparing, adjusting, and summarizing data merges are included. The package implements methods developed in Enamorado, Fifield, and Imai (APSR, 2019), "[Using a Probabilistic Model to Assist Merging of Large-scale Administrative Records](https://imai.fas.harvard.edu/research/files/linkage.pdf)."

Type `install.packages("fastLink")` to install in R. Please also see the [fastLink Github page](https://github.com/kosukeimai/fastLink) for the most stable development release.

[**hettx: Detecting and Measuring Treatment Effect Variation**](https://cran.r-project.org/web/packages/hettx/) (with [Peng Ding](https://sites.google.com/site/pengdingpku/), [Avi Feller](https://gsppi.berkeley.edu/avi-feller/), and [Luke Miratrix](https://scholar.harvard.edu/lmiratrix/home))

hettx is a publicly available R package that implements methods developed by Ding, Feller, and Miratrix (JRSS-B, 2016)  ''[Randomization Inference for Treatment Effect Variation](https://rss.onlinelibrary.wiley.com/doi/abs/10.1111/rssb.12124)'',  and Ding, Feller, and Miratrix (JASA, 2019) ''[Decomposing Treatment Effect Variation](https://www.tandfonline.com/doi/abs/10.1080/01621459.2017.1407322?journalCode=uasa20)'',  for testing whether there is unexplained variation in treatment effects across observations. The package includes wrapper functions implementing the proposed methods, as well as helper functions for analyzing and visualizing the results of the test.

Type `install.packages(“hettx”)` to install in R. Please also see the [hettx Github Page](https://github.com/bfifield/hettx) for the most stable development release.

## Shiny Apps:

[**randomizeAuthor**](https://randomizeauthor.shinyapps.io/shiny/) (with [Yang-Yang Zhou](https://www.yangyangzhou.com/) and [Evan Lieberman](https://evanlieberman.org/))

randomizeAuthor is an online Shiny App utility for transparently randomizing author order for academic articles while creating a common, replicable record of the randomization. To ensure non-manipulable replicability, the app queries the random.org API for a random seed that guarantees replicability of the randomization, and it automatically sends an email record of the input names and their order along with the random seed value and its source. 
