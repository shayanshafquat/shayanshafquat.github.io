---
layout: archive
title: ""
permalink: /projects/
author_profile: true
redirect_from:
  - /projects
---

# Recent Industry Projects

## RAG-Based Research Platform
**October - December 2024**

Built a modular RAG platform with OpenAI/Llama integration for research applications. Implemented CI/CD workflows with GitHub Actions and external web & document retrieval capabilities.

**Key Features:**
- Modular architecture supporting multiple LLM providers (OpenAI, Llama, local models)
- External web scraping and document retrieval capabilities
- CI/CD pipeline with automated testing and deployment
- RESTful API with FastAPI backend
- Vector database integration for efficient similarity search

**Technologies**: Python, LangChain, LlamaIndex, OpenAI API, GitHub Actions, FastAPI, Docker

## Traffic Light Optimization (OLA Research)
**2021**

Developed SUMO-based Deep Q-learning simulation for traffic optimization. Achieved 18.3% reduction in wait times through intelligent traffic signal coordination.

**Key Features:**
- Deep Q-learning implementation for traffic signal optimization
- SUMO traffic simulation environment integration
- Real-time traffic flow analysis and prediction
- Multi-intersection coordination algorithms
- Performance metrics and visualization tools

**Technologies**: Python, SUMO, Deep Q-Learning, Traffic Simulation, NumPy, Matplotlib

## LLM Security & Testing Framework (Enkrypt AI)
**September 2023**

Developed comprehensive security testing framework for LLM systems, including malicious file detection and prompt injection defense mechanisms.

**Key Features:**
- Automated malicious file scanner with ML-based detection
- Prompt injection attack simulation and defense testing
- RAGAS integration for LLM pipeline evaluation
- GuardRails implementation for robust security
- Comprehensive security assessment reporting

**Technologies**: Python, RAGAS, NeMoGuardRails, GuardRails, LLM Security, RAG Systems

---

# Academic & Research Projects

### [Neuronal oscillations on evolving networks: Dynamics, Damage, Degeneration, Decline, Dementia and Death: A review and extension of Goreily et al. (2020)](https://github.com/shayanshafquat/PBM2/tree/main) [[PDF Report]](../files/PBM_2.pdf)
1. **Neurodegenerative Disease Modeling:** Recreated and extended a neural network model to simulate the progression of neurodegenerative diseases, using the Fisher-Kolmogorov-Petrovsky-Piskunov and Heterodimer models for protein spread. This deepened my expertise in modeling disease dynamics within evolving brain networks, particularly in the context of Alzheimer’s disease.
2. **Resting-State Brain Dynamics Analysis:** Applied signal processing techniques to analyze resting-state brain dynamics, focusing on the decline of cognitive functions over time. This included implementing dynamic biomarkers like Gamma range power and metastability index, enhancing my skills in using neural mass models (e.g., Wilson-Cowan) to simulate and interpret brain activity.
3. **Exploration of Hemispheric Differences and Homeostasis:** Investigated inter-hemispheric variations in disease progression and the impact of network homeostasis on cognitive decline. This work involved the use of Graph Laplacian methods and homeostatic adaptation models, advancing my understanding of how structural network changes affect neural dynamics in neurodegenerative conditions.

### [Evaluating the mechanistic whole-brain model of empirical MEG data](https://github.com/shayanshafquat/whole-brain-meg-model-evaluation/tree/master) [[PDF Report]](../files/pbm_1.pdf)
1. **Model Reimplementation and Analysis:** Recreated Deco’s multiple-frequency brain model, utilizing techniques like bifurcation analysis, nullcline plotting, and the Euler-Maruyama method. This work enhanced my skills in simulating neural dynamics and analyzing resting-state brain activity through computational models, while also highlighting challenges in replicability and parameter sensitivity.
2. **Enhanced Model Integration and Comparison:** Extended the Stuart-Landau model with the Wilson-Cowan framework, applying signal processing techniques like band-pass filtering and envelope functional connectivity analysis. This integration demonstrated the Wilson-Cowan model’s superior alignment with empirical MEG data, particularly in handling noise and simulating frequency-specific neural behaviors, further refining my expertise in computational neuroscience.
3. **Critical Insights and Evaluation:** Conducted an evaluation of the original study, identifying key oversights in noise parameterization and model assumptions. This work emphasized the importance of refining computational models for improved accuracy and reproducibility in simulating complex brain dynamics, deepening my understanding of neuroscience and computational modeling in research.

### [Master's Dissertation: Stochastic Models in Patch Foraging](https://github.com/shayanshafquat/exploration_in_foraging/tree/main)
**May - September 2024 | Grade: Distinction**

Simulated foraging behaviors using resource depletion models and evaluated stochastic action selection algorithms in human patch-foraging tasks. Applied MVT predictions and epsilon-greedy algorithms for optimal foraging strategies.

**Key Contributions:**
- Implemented resource depletion models for patch foraging simulation
- Evaluated epsilon-greedy algorithms against MVT theoretical predictions
- Developed stochastic action selection framework for human decision-making
- Applied computational neuroscience principles to behavioral economics

**Technologies**: Python, NumPy, SciPy, Matplotlib, Jupyter, Computational Neuroscience

## Machine Learning in Science Coursework
**2024**

### CNN Optimization for Autonomous Driving
Developed and optimized CNN architectures for autonomous driving applications, focusing on real-time performance and accuracy.

**Key Features:**
- CNN architecture optimization for edge deployment
- Real-time inference optimization techniques
- TensorFlow Lite model conversion and deployment
- Performance benchmarking and model comparison

**Technologies**: Python, TensorFlow, CNN, TensorFlow Lite, Edge Computing

### 2D Drone Navigation with Reinforcement Learning
Implemented reinforcement learning algorithms for 2D drone navigation in complex environments.

**Key Features:**
- Q-learning and Deep Q-learning implementations
- Environment simulation and reward function design
- Policy optimization for navigation efficiency
- Real-time decision-making algorithms

**Technologies**: Python, PyTorch, Reinforcement Learning, Q-Learning, Deep Q-Learning

---

### [NREM sleep in the rodent neocortex and hippocampus reflects excitable dynamics](https://github.com/shayanshafquat/nrem-sleep-excitable-dynamics/tree/main) [[Poster]](../files/poster_pbm.pdf)

1. **Neural Dynamics Modeling:** Reimplemented a Wilson-Cowan-like model to simulate and analyze UP/DOWN state dynamics in the neocortex and hippocampus during NREM sleep, revealing distinct excitability regimes.
2. **Bifurcation and Stability Analysis:** Conducted bifurcation analysis and phase plane plotting to categorize neural dynamics into oscillatory, bistable, ExcitableUP, and ExcitableDOWN regimes, highlighting their stability and transition mechanisms.
3. **Quantitative Insights:** Provided quantitative analysis of state duration distributions, demonstrating how neural drive and adaptation influence the stability and dynamics of UP/DOWN states, contributing to a unified understanding of sleep-related brain activity.

### [Open Source Brain: Cross-Simulator Cortical Models](https://github.com/OpenSourceBrain/BahlEtAl2012_ReducedL5PyrCell)
**Google Summer of Code 2022 | INCF Organization**

<img style="float: left;" src="/images/gsoc_logo.png" width="200" height="200" hspace="30">

**Project Overview:**
Developed cross-simulator compatibility for large-scale cortical models, enabling neuroscience research across different simulation platforms.

**Key Contributions:**
1. **Model Verification**: Improved and tested original model code in NEURON simulator
2. **NeuroML Conversion**: Converted simulator-specific models to NeuroML format for cross-platform compatibility
3. **Documentation**: Created comprehensive documentation and baseline behavior illustrations
4. **Repository Management**: Organized and shared models across Open Source Brain repositories

**Technologies**: Python, NEURON, NeuroML, Git, Documentation, Model Validation

**Impact**: Enhanced accessibility of computational neuroscience models for researchers worldwide

### [Decision-Making in Mice: 2AFC Task Analysis](https://data.internationalbrainlab.org)
**Neuromatch Academy 2022 | International Brain Lab**

<img style="float: left;" src="/images/rrs.png" width="200" height="200" hspace="30">

**Project Overview:**
Analyzed decision-making patterns in mice using International Brain Lab datasets to understand the role of reward, punishment, and learning in behavioral choices.

**Key Findings:**
1. **Streak Analysis**: Demonstrated that streak distribution is non-random and influenced by task difficulty, learning progression, and motivation levels
2. **Behavioral Modeling**: Developed logistic regression model to predict next choice correctness with 75% accuracy
3. **Learning Patterns**: Identified distinct learning phases and their impact on decision-making strategies

**Methodologies:**
- Statistical analysis of behavioral data
- Machine learning model development and validation
- Data visualization and pattern recognition
- Cross-validation and model evaluation

**Technologies**: Python, Pandas, Scikit-learn, Matplotlib, Statistical Analysis, Machine Learning

**Impact**: Contributed to understanding of animal learning and decision-making processes

---

## Additional Research Projects

### [Neurodegenerative Disease Modeling](https://github.com/shayanshafquat/PBM2/tree/main)
**2024 | Computational Neuroscience Research**

**Project Overview:**
Extended neural network models to simulate neurodegenerative disease progression using Fisher-Kolmogorov-Petrovsky-Piskunov and Heterodimer models.

**Key Contributions:**
- Implemented protein spread models for Alzheimer's disease simulation
- Applied Graph Laplacian methods for network analysis
- Developed dynamic biomarkers for cognitive decline tracking
- Created homeostatic adaptation models for disease progression

**Technologies**: Python, NumPy, SciPy, Network Analysis, Computational Neuroscience

### [Whole-Brain MEG Model Evaluation](https://github.com/shayanshafquat/whole-brain-meg-model-evaluation/tree/master)
**2023 | Brain Dynamics Research**

**Project Overview:**
Evaluated and enhanced Deco's multiple-frequency brain model for empirical MEG data analysis and resting-state brain dynamics simulation.

**Key Contributions:**
- Reimplemented and validated original brain model
- Enhanced Stuart-Landau model with Wilson-Cowan framework
- Applied signal processing techniques for neural activity analysis
- Identified critical model assumptions and parameter sensitivity issues

**Technologies**: Python, Signal Processing, Bifurcation Analysis, Computational Neuroscience

---

## Competition & Hackathon Projects

### LSTM Model for Data Analytics Competition
**2018 | Inter Hall Data Analytics Competition | Gold Medal**

**Project Overview:**
Developed an LSTM-based model that won the gold medal in the Inter Hall Data Analytics Competition at IIT Kharagpur.

**Key Features:**
- LSTM architecture for time series prediction
- Feature engineering and data preprocessing
- Model optimization and hyperparameter tuning
- Performance evaluation and validation

**Technologies**: Python, LSTM, TensorFlow, Data Preprocessing, Time Series Analysis

### Football Team Leadership
**2017, 2019 | Inter Hall Sports Competition | Gold Medal**

**Project Overview:**
Led football teams to consecutive gold medals in 2017 and 2019 Inter Hall Sports Competitions at IIT Kharagpur.

**Key Contributions:**
- Team strategy development and tactical planning
- Player coordination and skill development
- Performance analysis and improvement strategies
- Leadership and team management

**Impact**: Demonstrated leadership skills and ability to work effectively in team environments
