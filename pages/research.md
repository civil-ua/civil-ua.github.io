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
    <li data-magellan-arrival="MIG"><a href="#MIG">AI for Medical Image Generation</a></li>
    <li data-magellan-arrival="OC"><a href="#OC">AI for Observer Computation</a></li>
    <li data-magellan-arrival="VS"><a href="#VS">Visual Search</a></li>
    <li data-magellan-arrival="CI"><a href="#CI">Task-Informed Computational Imaging</a></li>
  </ul>
</div>

<h2 data-magellan-destination="Overview">Overview</h2>
<a name="Overview"></a>
The Intelligent Imaging and Computational Vision (IICV) Lab focuses on imaging science, visual perception, and AI/machine learning. The research goals of the IICV Lab are to promote AI-powered imaging science and vision science to improve biomedical image quality and to increase the theoretical and practical understanding of image interpretation of humans and machines. Achieving these goals can lead to reduced diagnostic errors and improved health outcomes. Some questions that we are particularly interested in include: (1) How can deep learning be effectively used for conducting virtual imaging trials that permit the automated simulation and analysis of imaging systems in silico? (2) What eye movements optimize decisions in target detection and localization tasks in medical images? (3) How can image reconstruction/processing algorithms be designed such that the observer performance for task of interest is optimized? To systematically address these questions, our lab utilizes principles of imaging science and vision science and combines a variety of tools, including machine learning, numerical observers, eye tracking, computational modeling, and behavioral psychophysics.
<img src="/assets/img/research/research-overview.png">


<h2 data-magellan-destination="MIG"> AI for Medical Image Generation</h2>
<a name="MIG"></a>
Modern medical imaging systems produce images through the imaging chain that consists of complicated hardware and sophisticated computational methods. However, because of the great number of system parameters that can affect image quality, the large variety in objects to be imaged, and ethical limitations, it is often impractical to assess imaging systems via clinical imaging trials. This can hinder the development of emerging imaging technologies. Due to these reasons, there has been growing interest in virtual imaging trials (VITs) that can emulate the clinical imaging process and permit the interpretation and analysis of medical images in silico. Moreover, because it is often expensive to acquire large amount of experimental medical imaging data, generation of realistic "fake" medical images can be useful for a wide range of diagnostic applications. 

{% include project
  title="Advanced-AmbientGAN for establishing stochastic object models"

  description="To objectively assess new medical imaging technologies via computer-simulations, it is important to account for the variability in the ensemble of objects to be imaged. This source of variability can be described by stochastic object models (SOMs). It is generally desirable to establish SOMs from experimental imaging measurements acquired by use of a well-characterized imaging system, but this task has remained challenging. A generative adversarial network (GAN)-based method that employs AmbientGANs with modern progressive or multiresolution training approaches is proposed. The progressive growing of GANs (ProGANs) and style-based GANs (StyGANs) are modified for use in establishing AmbientGANs with high-dimensional medical imaging measurements. The resulting models are referred to as progressive growing AmbientGANs (ProAmGANs) and style-AmbientGANs (StyAmGANs). Both visual examinations and quantitative analyses, including task-specific validations using the Hotelling observer, demonstrated that the proposed AmbientGAN method holds promise to establish realistic SOMs from imaging measurements."
 
image="/assets/img/research/AmGAN.png"

  citation="Zhou et al. 2022. Journal of Medical Imaging. 9(1):1-22."
  
  web="https://www.spiedigitallibrary.org/journals/journal-of-medical-imaging/volume-9/issue-1/015503/Learning-stochastic-object-models-from-medical-imaging-measurements-by-use/10.1117/1.JMI.9.1.015503.full"

team="Weimin Zhou"

%}

{% include project
  title="Unsupervised Generation of Pseudo Normal PET from MRI with Diffusion Model for Epileptic Focus Localization"

  description="Fluorodeoxyglucose Positron Emission Tomography (FDG PET) has emerged as a crucial tool in identifying the epileptic focus, especially in cases where Magnetic Resonance Imaging (MRI) yields indeterminate results. The efficacy of FDG PET assessments, however, is contingent upon the selection of an appropriate reference control group. Challenges arise when such a group is either unavailable or exhibits demographic disparities. Yaakub et al. have previously introduced a technique utilizing pix2pixGAN for the conversion of MRI images to PET images, employing paired MRI and FDG PET scans from healthy individuals. This method enabled the generation of synthetic normal FDG PET images from patient MRIs, thereby improving the accuracy of lesion detection. Despite its potential, this approach requires an extensive dataset of high-quality, paired MRI and PET images from healthy control subjects. In the current study, we propose an innovative technique that leverages recent developments in diffusion models. This method is capable of performing MRI to PET image translation in an unsupervised manner. Our findings indicate that this novel approach surpasses existing benchmark methods in terms of precision in localizing the epileptic focus."
 

  citation="To be appeared in SPIE Medical Imaging 2024."
  
  web="https://spie.org/MI24/conferencedetails/clinical-biomedical-imaging?enableBackToBrowse=true#_=_"

team="Wentao Chen, Xichen Xu, Weimin Zhou"
%}


{% include project
  title="Ambient-Conditional GAN"

  description="In this work, we propose a new cGAN architecture, Ambient-cGAN, for performing medical image-to-image translation tasks by use of noisy measurement data. Moreover, we employ the Pix2Pix in the proposed Ambient-cGAN architecture and the resulting model is referred to as Ambient-Pix2PixGAN. Numerical studies that consider a task of translating MRI to PET images is conducted. Both traditional image quality metrics and task-based image quality metrics are employed to assess the proposed Ambient-cGAN. It is demonstrated that our proposed Ambient-cGAN can be trained on noisy measurement data to produce high-quality translated images. Moreover, we proposed Ambient-CycleGAN for performing unpaired image-to-image translations taks that can be employed to establish realistic and controlable SOMs by integrating computational modeling and imaging measurement data."
 

  citation="To be appeared in SPIE Medical Imaging 2024."
  
  web="https://spie.org/MI24/conferencedetails/medical-image-perception?enableBackToBrowse=true"

  team="Wentao Chen, Xichen Xu, Weimin Zhou"
%}



<h2 data-magellan-destination="OC">AI for Observer Computation</h2>
<a name="OC"></a>
When optimizing imaging systems for signal detection tasks (e.g., detection of a tumor), it has been advocated to use the performance of the Bayesian Ideal Observer (IO) as a figure-of-merit (FOM). In this way, the imaging system can be optimized in such a way that the amount of task-specific information in the measurement data is maximized. The IO for a binary signal detection task implements a test statistic given by the likelihood ratio and maximizes the area under the receiver operating characteristic (ROC) curve. The IO has also been employed to assess the efficiency of human observers on signal detection tasks. The IO test statistic is generally a non-linear function of the image data and, except in some special cases, cannot be determined analytically. When the IO is intractable, the Hotelling Observer (HO) can be employed to optimize imaging systems for signal detection tasks. However, implementation of the HO is also not without challenges. Specifically, it requires the estimation and inversion of a covariance matrix that can be enormous. 
{% include project
  title="Supervised Learning for Approximating the Bayesian Ideal Observer and the Hotelling Observer"

  description="In this work, supervised learning-based methods that employ artificial neural networks for approximating the IO test statistic are explored systematically for binary signal detection tasks in which the observer acts on 2D image data. For the special case of the HO, an alternative supervised learning methodology is proposed that employs single-layer neural networks (SLNNs) for learning the Hotelling template without the need for explicitly estimating and inverting covariance matrices. Moreover, we proposed a supervised learning approach for approximating the IO for joint detection localization tasks that maximizes the area under the localization ROC (LROC) curve."

  image="/assets/img/research/IO-HO-learning.png"

  citation="Zhou et al. 2019. IEEE Transactions on Medical Imaging. 38(10):2456–2468."
  
  web="https://ieeexplore.ieee.org/abstract/document/8691467"

  citation2="Zhou et al. 2020. IEEE Transactions on Medical Imaging. 39(12):3992–4000."

  web2="https://ieeexplore.ieee.org/abstract/document/9139307"

  team="Weimin Zhou"

%}

{% include project
  title="Ideal Observer Computation by Use of Markov-Chain Monte Carlo with Generative Adversarial Networks"

  description=" A sampling-based method that employs Markov-chain Monte Carlo (MCMC) techniques was previously proposed to estimate the IO performance. However, current applications of MCMC methods for IO approximation have been limited to a small number of situations where the considered distribution of to-be-imaged objects can be described by a relatively simple stochastic object model (SOM). As such, there remains an important need to extend the domain of applicability of MCMC methods to address a large variety of scenarios where IO-based assessments are needed but the associated SOMs have not been available. In this study, a novel MCMC method that employs a generative adversarial network (GAN)-based SOM, referred to as MCMC-GAN, is described and evaluated. The MCMC-GAN method was quantitatively validated by use of test-cases for which reference solutions were available. The results demonstrate that the MCMC-GAN method can extend the domain of applicability of MCMC methods for conducting IO analyses of medical imaging systems."

  image="/assets/img/research/mcmc_gan.jpg"

  citation="Zhou et al. 2023. IEEE Transactions on Medical Imaging. 42(12):3715–3724."

  web="https://ieeexplore.ieee.org/document/10216380"

  team="Weimin Zhou"

%}


<h2 data-magellan-destination="VS">Visual Search</h2>
<a name="VS"></a>
Humans process visual information with varying resolution, known as foveated visual systems, and explore images by orienting through eye movements the high-resolution fovea to points of interest. Visual inspection of medical images is a critical component of diagnostic process and there is a long tradition of studying eye movement strategies deployed by radiologists in visual search. What eye movements optimize decisions in tasks such as target detection and localization?
{% include project
  title="Deep Q-learning for approximating the Bayesian ideal searcher"

  description="Researchers have previously developed a Bayesian ideal searcher (IS) that optimizes search strategies for simple Gaussian noise backgrounds. However, the computation of the IS can be intractable when considering more realistic and complex backgrounds such as medical images. In this study, we investigate the ability of a reinforcement learning method that employs Q-network to approximate the IS. We demonstrate that the search strategy corresponding to the Q-network is consistent with the IS search strategy. The findings show the potential of the reinforcement learning with Q-network approach to estimate optimal eye movement planning with real anatomical backgrounds."

  image="/assets/img/research/Qnet.png"

  citation="Zhou et al. 2022. Proc. SPIE 12035, Medical Imaging."

   web="https://www.spiedigitallibrary.org/conference-proceedings-of-spie/12035/0000/A-deep-Q-learning-method-for-optimizing-visual-search-strategies/10.1117/12.2613133.full"

  team="Weimin Zhou"
%}

{% include project
  title="Optimal visual search strategy with inter-saccade response correlations"
  
description="In 2005, Najemnik & Geisler proposed the Bayesian Ideal searcher (IS) that takes into account the foveated properties of human visual and employs the optimal fixation selection strategy to maximize visual search performance. In addition, they proposed a computationally simpler model, entropy limit minimization (ELM), that approximates the IS searcher. One limitation of these models is that they were developed with the assumption that the visual system’s internal responses across fixations are statistically independent. This assumption will not hold for search tasks such as in 2D medical images for which the external noise and anatomical noise results in correlations in internal responses across saccadic fixations (inter-saccade response correlations). In this work, we present image-computable foveated IS and ELM models that accommodate inter-saccade response correlations. We demonstrate that for static images, the optimal searchers that account for the inter-saccade correlations (i.e., IS-COR and ELM-COR) significantly outperform the traditional methods that ignore such correlations."

  image="/assets/img/research/visual_search.jpg"

  citation="Zhou et al. 2023. Proc. SPIE 12467, Medical Imaging."

  web="https://www.spiedigitallibrary.org/conference-proceedings-of-spie/12467/1246705/Optimal-visual-search-strategy-with-inter-saccade-response-correlations/10.1117/12.2655817.full"

  team="Weimin Zhou"
%}


<h2 data-magellan-destination="CI">Task-Informed Computational Imaging</h2>
<a name="CI"></a>
Morden medical imaging systems rely on sophisticated image reconstruction and processing algorithms to produce high-quality images. It is important to develop image reconstruction/processing methods that can form clinically-useful images from under-sampled and noisy measurement data. Such methods, for example, can reduce the radiation exposure to the patients in X-ray/nuclear imaging and accelerate data-acquisition in MRI. When under-sampled or noisy data are acquired, the image reconstruction problem becomes ill-posed and it is important to utilize prior knowledge of the sought-after object property to provide regularization. Advanced AI methods have been applied to achieve many successes for establishing generative models and inference models in imaging applications. We endeavor to investigate AI methods to solve ill-posed inverse problems for producing diagnostically accurate high-quality images.

{% include project
  title="Task-Aware Medical Image Denoising"

  description="Medical imaging systems often produce images that are contaminated by noise. Deep neural network (DNN)-based image denoising methods have been proposed for use with medical images, and traditional image quality measures have been employed to evaluate such methods. However, studies showed that denoising networks can result in a loss of task-relevant information in the images. To address this issue, a task-aware denoising autoencoder (DAE) was developed that can effectively extract task-specific information from noisy image data and subsequently form clean images. It was also demonstrated that the encoder of the proposed task-aware DAE can be used as efficient channels for approximating the Hotelling observer (HO). In addition, a foveated channelized HO that models human visual system was employed to assess the denoised images, and the corresponding signal detectability was significantly improved."

  image="/assets/img/research/DAE.png"

  citation="Zhou. 2023. Proc. SPIE 12467, Medical Imaging."

   web="https://www.spiedigitallibrary.org/conference-proceedings-of-spie/12467/1246716/Task-aware-denoising-autoencoders-for-establishing-efficient-channels/10.1117/12.2654465.full"

  team="Weimin Zhou"
%}








