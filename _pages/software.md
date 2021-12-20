---
layout: archive
title: "Software"
permalink: /software/
author_profile: true
---

## R Packages:

<details>
<summary><a href="http://cran.r-project.org/web/packages/redist/"><b>redist: Computational Algorithms for Redistricting Simulation</b></a> (with <a href = "https://www.christophertkenny.com">Christopher Kenny</a>, <a href = "https://corymccartan.github.io/">Cory McCartan</a>, and <a href = "https://imai.fas.harvard.edu/">Kosuke Imai</a>)</summary>
<br>
redist is a publicly available R package that enables researchers to statistically simulate congressional redistricting plans using Markov chain Monte Carlo and Sequential Monte Carlo techniques. This includes the implementation of substantive constraints in the redistricting process such as geographic compactness and population parity requirements, as well as efficient simulation methods such as simulated tempering algorithms. Tools for analysis such as inverse probability reweighting and plotting functionality are included. The package implements methods found in Fifield, Higgins, Imai, and Tarr (JCGS, 2020), "<a href = "https://imai.fas.harvard.edu/research/files/redist.pdf">Automated Redistricting Simulation Using Markov Chain Monte Carlo</a>," Fifield, Imai, Kawahara, and Kenny (SPP, 2020), “<a href = "https://imai.fas.harvard.edu/research/files/enumerate.pdf">The Essential Role of Empirical Validation in Legislative Redistricting Simulation </a>”, and McCartan and Imai, “<a href = "https://imai.fas.harvard.edu/research/files/SMCredist.pdf">Sequential Monte Carlo for Sampling Balanced and Compact Redistricting Plans</a>“. <br><br>

Type <code>install.packages("redist")</code> to install in R. Please also see the <a href = "https://github.com/alarm-redist/redist">redist GitHub page</a> for the most stable development release.<br>

</details>[![CRAN\_Status\_Badge](https://www.r-pkg.org/badges/version-last-release/redist)](https://cran.r-project.org/package=redist) ![CRAN downloads](http://cranlogs.r-pkg.org/badges/grand-total/redist)

<details>
<summary><a href = "https://cran.r-project.org/web/packages/fastLink/"><b>fastLink: Fast Probabilistic Record Linkage</b></a> (with <a href = "https://www.tedenamorado.com/">Ted Enamorado</a> and <a href = "https://imai.fas.harvard.edu/">Kosuke Imai</a>)</summary>
<br>

fastLink is a publicly available R package that enables researchers to merge two data sets using a fast implementation of the Fellegi-Sunter probabilistic record linkage model that allows for missing data and the inclusion of auxiliary information. This includes functionalities to conduct a merge of two data sets under the Fellegi-Sunter model using the Expectation-Maximization algorithm. In addition, tools for preparing, adjusting, and summarizing data merges are included. The package implements methods developed in Enamorado, Fifield, and Imai (APSR, 2019), "<a href = "https://imai.fas.harvard.edu/research/files/linkage.pdf">Using a Probabilistic Model to Assist Merging of Large-scale Administrative Records</a>."<br><br>

Type <code>install.packages("fastLink")</code> to install in R. Please also see the <a href = "https://github.com/kosukeimai/fastLink">fastLink Github page</a> for the most stable development release.<br><br>

fastLink received the 2021 Statistical Software award from the Society for Political Methodology. The award citation can be found <a href = "https://polmeth.org/news/2021-statistical-software-award">here</a>.<br><br>

The core statistical model behind fastLink has also been ported over to the Apache Spark environment, as implemented in <a href = "https://github.com/moj-analytical-services/splink">splink</a>.<br>

</details>[![CRAN Version](https://www.r-pkg.org/badges/version-last-release/fastLink)](https://CRAN.R-project.org/package=fastLink) ![CRAN downloads](http://cranlogs.r-pkg.org/badges/grand-total/fastLink)

<details>
<summary><a href = "https://cran.r-project.org/web/packages/hettx/"><b>hettx: Detecting and Measuring Treatment Effect Variation</b></a> (with <a href = "https://sites.google.com/site/pengdingpku/">Peng Ding</a>, <a href = "https://gsppi.berkeley.edu/avi-feller/">Avi Feller</a>, and <a href = "https://scholar.harvard.edu/lmiratrix/home">Luke Miratrix</a>)</summary>
<br>

hettx is a publicly available R package that implements methods developed by Ding, Feller, and Miratrix (JRSS-B, 2016)  ''<a href = "https://rss.onlinelibrary.wiley.com/doi/abs/10.1111/rssb.12124">Randomization Inference for Treatment Effect Variation</a>'',  and Ding, Feller, and Miratrix (JASA, 2019) ''<a href = "https://www.tandfonline.com/doi/abs/10.1080/01621459.2017.1407322?journalCode=uasa20">Decomposing Treatment Effect Variation</a>'',  for testing whether there is unexplained variation in treatment effects across observations. The package includes wrapper functions implementing the proposed methods, as well as helper functions for analyzing and visualizing the results of the test.<br><br>

Type <code>install.packages(“hettx”)</code> to install in R. Please also see the <a href = "https://github.com/bfifield/hettx">hettx Github Page</a> for the most stable development release.<br>

</details>[![CRAN Version](https://www.r-pkg.org/badges/version-last-release/hettx)](https://CRAN.R-project.org/package=hettx) [![](https://cranlogs.r-pkg.org/badges/grand-total/hettx)](https://cran.r-project.org/package=hettx)

<details>
<summary><a href = "https://cran.r-project.org/web/packages/redistmetrics/"><b>redistmetrics: Redistricting Metrics</b></a> (with <a href = "https://www.christophertkenny.com">Christopher Kenny</a>, <a href = "https://corymccartan.github.io/">Cory McCartan</a>, and <a href = "https://imai.fas.harvard.edu/">Kosuke Imai</a>)</summary>
<br>

redistmetrics is a publicly available R package providing reliable and flexible tools for scoring redistricting plans using common measures and metrics. These functions provide key direct access to tools useful for non-simulation analyses of redistricting plans, such as for measuring compactness or partisan fairness. Tools are designed to work with the redist package seamlessly.

Type <code>install.packages("redistmetrics")</code> to install in R. Please also see the <a href = "https://github.com/alarm-redist/redistmetrics"> redistmetrics GitHub page</a> for the most stable development release.<br>

</details>[![CRAN\_Status\_Badge](https://www.r-pkg.org/badges/version-last-release/redistmetrics)](https://cran.r-project.org/package=redistmetrics) ![CRAN downloads](http://cranlogs.r-pkg.org/badges/grand-total/redistmetrics)

## Shiny Apps:

<details>
<summary><a href = "https://randomizeauthor.shinyapps.io/shiny/"><b>randomizeAuthor</b></a> (with <a href = "https://www.yangyangzhou.com/">Yang-Yang Zhou</a> and <a href = "https://evanlieberman.org/">Evan Lieberman</a>)</summary>
<br>

randomizeAuthor is an online Shiny App utility for transparently randomizing author order for academic articles while creating a common, replicable record of the randomization. To ensure non-manipulable replicability, the app queries the random.org API for a random seed that guarantees replicability of the randomization, and it automatically sends an email record of the input names and their order along with the random seed value and its source. 

</details>
