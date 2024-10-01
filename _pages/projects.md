---
layout: archive
title: ""
permalink: /projects/
author_profile: true
redirect_from:
  - /projects
---

### [Neuronal oscillations on evolving networks: Dynamics, Damage, Degeneration, Decline, Dementia and Death: A review and extension of Goreily et al. (2020)](https://github.com/shayanshafquat/PBM2/tree/main)
1. **Neurodegenerative Disease Modeling:** Recreated and extended a neural network model to simulate the progression of neurodegenerative diseases, using the Fisher-Kolmogorov-Petrovsky-Piskunov and Heterodimer models for protein spread. This deepened my expertise in modeling disease dynamics within evolving brain networks, particularly in the context of Alzheimer’s disease.
2. **Resting-State Brain Dynamics Analysis:** Applied signal processing techniques to analyze resting-state brain dynamics, focusing on the decline of cognitive functions over time. This included implementing dynamic biomarkers like Gamma range power and metastability index, enhancing my skills in using neural mass models (e.g., Wilson-Cowan) to simulate and interpret brain activity.
3. **Exploration of Hemispheric Differences and Homeostasis:** Investigated inter-hemispheric variations in disease progression and the impact of network homeostasis on cognitive decline. This work involved the use of Graph Laplacian methods and homeostatic adaptation models, advancing my understanding of how structural network changes affect neural dynamics in neurodegenerative conditions.

### Evaluating the mechanistic whole-brain model of empirical MEG data
1. **Model Reimplementation and Analysis:** Recreated Deco’s multiple-frequency brain model, utilizing techniques like bifurcation analysis, nullcline plotting, and the Euler-Maruyama method. This work enhanced my skills in simulating neural dynamics and analyzing resting-state brain activity through computational models, while also highlighting challenges in replicability and parameter sensitivity.
2. **Enhanced Model Integration and Comparison:** Extended the Stuart-Landau model with the Wilson-Cowan framework, applying signal processing techniques like band-pass filtering and envelope functional connectivity analysis. This integration demonstrated the Wilson-Cowan model’s superior alignment with empirical MEG data, particularly in handling noise and simulating frequency-specific neural behaviors, further refining my expertise in computational neuroscience.
3. **Critical Insights and Evaluation:** Conducted an evaluation of the original study, identifying key oversights in noise parameterization and model assumptions. This work emphasized the importance of refining computational models for improved accuracy and reproducibility in simulating complex brain dynamics, deepening my understanding of neuroscience and computational modeling in research.

### NREM sleep in the rodent neocortex and hippocampus reflects excitable dynamics

1. **Neural Dynamics Modeling:** Reimplemented a Wilson-Cowan-like model to simulate and analyze UP/DOWN state dynamics in the neocortex and hippocampus during NREM sleep, revealing distinct excitability regimes.
2. **Bifurcation and Stability Analysis:** Conducted bifurcation analysis and phase plane plotting to categorize neural dynamics into oscillatory, bistable, ExcitableUP, and ExcitableDOWN regimes, highlighting their stability and transition mechanisms.
3. **Quantitative Insights:** Provided quantitative analysis of state duration distributions, demonstrating how neural drive and adaptation influence the stability and dynamics of UP/DOWN states, contributing to a unified understanding of sleep-related brain activity.

### Open source, cross simulator, large scale cortical models in NeuroML  Google Summer of Code 2022 (INCF)

<img style="float: left;" src="/images/gsoc_logo.png" width="200" height="200" hspace="30">

1. Verify, improve and test the original model code in NEURON
2. Convert the published network model involving channels, cells, and connectivity developed in a simulator-specific format to NeuroML
3. Document and illustrate the baseline expected behavior of the model and share them across Open Source Brain repositories

### Reward and punishment-related changes in behavior during a 2AFC task in mice (Neuromatch Academy)

<img style="float: left;" src="/images/rrs.png" width="200" height="200" hspace="30">

1. Used [IBL datasets](data.internationalbrainlab.org) to analyse and model the decision-making (2AFC task) in mice
2. Streak distribution isn't random but rather influenced by task's difficulty, learning and motivation
3. Trained and evaluated a logistic regression model to predict the correctness of the next choice
