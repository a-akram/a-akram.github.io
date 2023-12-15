---
permalink: /
title: "About"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<p style='text-align: justify;'>I am an experimental nuclear physicist with experience in statistical analysis, software development, detector development and machine learning. My research focus is to use machine learning (ML) to solve various scientific problems, hence, I explore the use of <i>Deep Learning (DL)</i>, <i>Geometric Deep Learning (GDL)</i>, <i>Probabilistic/Bayesian Machine Learning (PML)</i>, and <i>Scientific Machine Learning (SciML)</i>. Another interesting subdomain is <i>Explainable/Interpretable Machine learning (XML)</i> which addresses the explainability of the ML models.</p>

### Future Research

<p style='text-align: justify;'>In HEP, several problems need fast and reliable algorithms. Machine learning is gaining popularity to address the challenges of future experiments. I have an interest in track reconstruction, parameter estimation, jet/particle identification, uncertainty quantification (UQ), detector design optimization and solving PDEs using specialized machine learning models. For example, track reconstruction is best solved by GDL using sophisticated Graph Neural Networks (GNNs) by leveraging the topographical features of the data. Whereas for uncertainty quantification, Bayesian Neural Neworks (BNNs) from PML can give answers. For other problems, SciML may provide solutions by incorporating domain knowledge or physics constraints into machine learning models <i>e.g.</i> complex PDEs have been solved using SciML models such as Physics-informed Neural Networks (PINNs).</p>


### Current Research

<p style='text-align: justify;'>Track reconstruction is one of the crucial steps in the HEP data analysis chain after acquiring data either from the GEANT4 simulation or directly from the detector. Hence, I reconstructed particle trajectories in the Straw Tube Tracker of the <a href="https://panda.gsi.de/">PANDA Experiment at FAIR</a>. I employed machine learning models to reconstruct particle trajectories as follows:</p>

1. Track Reconstuction:

    - Data generation through GEANT4 simulation toolkit
    - Data extraction and storage using ROOT analysis framework and C++
    - Exploratory data analysis (EDA) using Python scientific stack
    - Data wrangling and preprocessing in Python using PyG
    - Prototyping deep learning models in TensorFlow
    - Model training and inference using the PyTorch ecosystem
    - Hyperparameter tuning with RayTune, and experiment tracking using W&B
    - Track formation using Unsupervised clustering techniques such as DBScan, and Connected-Components
    - Model deployment on on-premise OpenStack cloud infrastructure, Docker containers with Ansible, TensorFlow Serving, Flask API, etc 

2. Pyhton-C++ Interfacing

    - Interface between Python and C++ environments using tools like UpRoot, PandaRoot


Moreover, I have performed physics analysis to reconstruct hyperons under realistic vacuum conditions in the PANDA experiment.

### Past Research
<p style='text-align: justify;'>In the past, my main focus was on gas detectors, especially multi-gap resistive plate chambers (MRPCs). I characterised the MRPCs for the time-of-flight wall of the <a href="https://www.cbm.gsi.de/">CBM Experiment at FAIR</a>. I also extended the firmware for high-speed data transmission through the LVDS link on the Altera Stratix-V FPGA.</p>