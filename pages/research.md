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
    <li data-magellan-arrival="IGAI"><a href="#IGAI">Image Generative AI</a></li>
  </ul>
</div>

<h2 data-magellan-destination="Overview">Overview</h2>
<a name="Overview"></a>

{% include project
overview


image="/assets/img/research/research-overview.png"

%}

<h2 data-magellan-destination="IPOC">Image Perception and Observer Computation</h2>
<a name="IPOC"></a>

{% include project
  title="Supervised Learning for Approximating the Bayesian Ideal Observer and the Hotelling Observer"

  description="When optimizing imaging systems for signal detection tasks (e.g., detection of a tumor), it has been advocated to use the performance of the Bayesian Ideal Observer (IO) as a figure-of-merit (FOM). In this way, the imaging system can be optimized in such a way that the amount of task-specific information in the measurement data is maximized. The IO for a binary signal detection task implements a test statistic given by the likelihood ratio and maximizes the area under the receiver operating characteristic (ROC) curve. The IO has also been employed to assess the efficiency of human observers on signal detection tasks. The IO test statistic is generally a non-linear function of the image data and, except in some special cases, cannot be determined analytically. When the IO is intractable, the Hotelling Observer (HO) can be employed to optimize imaging systems for signal detection tasks. However, implementation of the HO is also not without challenges. Specifically, it requires the estimation and inversion of a covariance matrix that can be enormous. In this work, supervised learning-based methods that employ artificial neural networks for approximating the IO test statistic are explored systematically for binary signal detection tasks in which the observer acts on 2D image data. For the special case of the HO, an alternative supervised learning methodology is proposed that employs single-layer neural networks (SLNNs) for learning the Hotelling template without the need for explicitly estimating and inverting covariance matrices. Moreover, we proposed a supervised learning approach for approximating the IO for joint detection localization tasks that maximizes the area under the localization ROC (LROC) curve."

  image="/assets/img/research/IO-HO-learning.png"

  citation="Zhou et al. 2019. IEEE Transactions on Medical Imaging. 38(10):2456–2468."
  
  web="https://ieeexplore.ieee.org/abstract/document/8691467"

  citation2="Zhou et al. 2020. IEEE Transactions on Medical Imaging. 39(12):3992–4000."

  web2="https://ieeexplore.ieee.org/abstract/document/9139307"

  team="Weimin Zhou"

%}

{% include project
  title="Ideal Observer Computation by Use of Markov-Chain Monte Carlo with Generative Adversarial Networks"

  description="The performance of the Bayesian Ideal Observer (IO) sets an upper limit among all observers, numerical or human, and has been advocated for use as a figure-of-merit (FOM) for eval- uating and optimizing medical imaging systems. However, the IO test statistic corresponds to the likelihood ratio that is intractable to compute in the majority of cases. A sampling- based method that employs Markov-chain Monte Carlo (MCMC) techniques was previously proposed to estimate the IO performance. However, current applications of MCMC methods for IO approximation have been limited to a small number of situations where the considered distribution of to-be-imaged objects can be described by a relatively simple stochastic object model (SOM). As such, there remains an important need to extend the domain of applicability of MCMC methods to address a large variety of scenarios where IO-based assessments are needed but the associated SOMs have not been available. In this study, a novel MCMC method that employs a generative adversarial network (GAN)-based SOM, referred to as MCMC-GAN, is described and evaluated. The MCMC-GAN method was quantitatively validated by use of test-cases for which reference solutions were available. The results demonstrate that the MCMC-GAN method can extend the domain of applicability of MCMC methods for conducting IO analyses of medical imaging systems."

  image="/assets/img/research/mcmc_gan.jpg"

  citation="Zhou et al. 2023. IEEE Transactions on Medical Imaging. 42(12):3715–3724."

  web="https://ieeexplore.ieee.org/document/10216380"

  team="Weimin Zhou"

%}


{% include project
  title="Visual Search"

  description="Humans process visual information with varying resolution, known as foveated visual systems, and explore images by orienting through eye movements the high-resolution fovea to points of interest. Visual inspection of medical images is a critical component of diagnostic process and there is a long tradition of studying eye movement strategies deployed by radiologists in visual search. What eye movements optimize decisions in tasks such as target detection and localization? Researchers have previously developed a Bayesian ideal searcher (IS) that optimizes search strategies for simple Gaussian noise backgrounds. However, the computation of the IS can be intractable when considering more realistic and complex backgrounds such as medical images. To address this limitation, a reinforcement learning method that employs Q-network to approximate the IS for 2D images was developed. Moreover, an image-computable foveated optimal search models that accom- modate inter-saccade response correlations that would arise from influences of external image variability in static 2D images was developed."

  image="/assets/img/research/visual_search.jpg"

  citation="Proc. SPIE 12035, Medical Imaging 2022."

  web="https://www.spiedigitallibrary.org/conference-proceedings-of-spie/12035/0000/A-deep-Q-learning-method-for-optimizing-visual-search-strategies/10.1117/12.2613133.full"

  citation2="Proc. SPIE 12467, Medical Imaging 2023."

  web2="https://www.spiedigitallibrary.org/conference-proceedings-of-spie/12467/1246705/Optimal-visual-search-strategy-with-inter-saccade-response-correlations/10.1117/12.2655817.full"

  team="Weimin Zhou"

%}



<h2 data-magellan-destination="IGAI">Image Generative AI</h2>
<a name="IGAI"></a>

{% include project
  title="Advanced-AmbientGAN for establishing stochastic object models"

  description="Extensive."

  

%}


