---
layout: page-fullwidth
title: "Research"
meta_title: ""
subheadline: ""
teaser: ""
permalink: "/research/"
header:
    # image_fullwidth: "genvis-dna-bg_optimized_v1a.png"
---

<div data-magellan-expedition="fixed">
  <ul class="sub-nav">
    <li data-magellan-arrival="Overview"><a href="#Overview">Overview</a></li>
    <li data-magellan-arrival="IPOC"><a href="#IPOC">Image Perception and Observer Computation</a></li>
    <li data-magellan-arrival="Precision_medicine"><a href="#Precision_medicine">Precision medicine</a></li>
  </ul>
</div>

<h2 data-magellan-destination="Overview">Overview</h2>
<a name="Overview"></a>

overview





<h2 data-magellan-destination="IPOC">Image Perception and Observer Computation</h2>
<a name="IPOC"></a>

{% include project
  title="Supervised Learning for Approximating the Bayesian Ideal Observer and the Hotelling Observer"

  description="When optimizing imaging systems for signal detection tasks (e.g., detection of a tumor), it has been advocated to use the performance of the Bayesian Ideal Observer (IO) as a figure-of-merit (FOM). In this way, the imaging system can be optimized in such a way that the amount of task-specific information in the measurement data is maximized. The IO for a binary signal detection task implements a test statistic given by the likelihood ratio and maximizes the area under the receiver operating characteris- tic (ROC) curve. The IO has also been employed to assess the efficiency of human observers on signal detection tasks. The IO test statistic is generally a non-linear function of the image data and, except in some special cases, cannot be determined analytically. When the IO is intractable, the Hotelling Observer (HO) can be employed to optimize imaging systems for signal detection tasks. However, implementation of the HO is also not without challenges. Specifically, it requires the estimation and inversion of a covariance matrix that can be enormous. In this work, supervised learning-based methods that employ artificial neural networks for approximating the IO test statistic are explored systematically for binary signal detection tasks in which the observer acts on 2D image data. For the special case of the HO, an alternative supervised learning methodology is proposed that employs single-layer neural networks (SLNNs) for learning the Hotelling template without the need for explicitly estimating and inverting covariance matrices."

  team="Weimin Zhou"

  image="/assets/img/research/IO-HO-learning.png"

  citation=
<a href="https://ieeexplore.ieee.org/abstract/document/8691467">{{ "Zhou et al. 2019. IEEE Transactions on Medical Imaging. 38(10):2456–2468." }}</a><br>

%}

{% include project
  title="Ideal Observer Computation by Use of Markov-Chain Monte Carlo with Generative Adversarial Networks"

  description="Extensive."

  team="Weimin Zhou"

%}




<h2 data-magellan-destination="Precision_medicine">Reconstruction</h2>
<a name="Precision_medicine"></a>

{% include project
  title="Genome analysis of relapsed adult ALL case reveals personalized therapeutic strategy"

  description="Extensive."

  team="Jason Walker"

%}


