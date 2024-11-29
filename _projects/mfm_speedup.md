---
layout: page
title: MFM Speedup
description: Use machine learning to accelerate a computational model (MFM) of human brains
img: assets/img/projects/pMFM_speedup/pMFM_speedup_thumbnail.png
importance: 1
category: Research Projects
related_publications: true
---

This was a research internship project at <a href="https://scholar.google.com/citations?user=BOUzsU8AAAAJ">Prof. B.T. Thomas Yeo</a>'s <a href="https://sites.google.com/view/yeolab">lab</a> at the <a href="https://nus.edu.sg/">National University of Singapore</a>. The goal of this project is to leverage machine learning and deep learning to accelerate the parameter optimization process for the mean-field model(MFM), or more precisely parametric MFM (pMFM).

The <a href="https://www.nature.com/articles/s41467-021-26704-y">pMFM</a> is a computational model of human brains that simulates brain activities through an ordinary differential equation (ODE) system to produce realistic functional MRI (fMRI) signals. The model is used to study the dynamics of brain activity and to understand how different brain regions communicate with each other.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/projects/pMFM_speedup/pMFM_Fig1A.jpg" title="Illustration of the pMFM" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Illustration of the pMFM, for more details, please refer to the original <a href="https://www.nature.com/articles/s41467-021-26704-y">paper</a>
</div>

The original pMFM's parameter optimization process utilizes Euler integration to numerically solve the ODE system, which can be computationally expensive to run. Therefore, I aim to speed up the parameter optimization process by using machine learning techniques to predict the MFM parameters' performances without the need to solve ODEs. Specifically, I performed the following tasks:

1. Generated a synthetic dataset of pMFM parameters and their corresponding performance.
2. Validated two assumptions.
3. Explored different machine learning models to predict the pMFM parameters' performances.
4. Explored various optimization techniques such as Covariance matrix adaptation evolution strategy (CMA-ES) and Gradient Descent.

In the end, I have demonstrated the feasibility of using machine learning to accelerate the pMFM parameter optimization process, achieving a speedup of **5,000x** compared to the original Euler integration method. This project has led to a paper {% cite Zeng2024DELSSOME %} that we are currently preparing for submission to _Nature Methods_. For more details of this project, please visit the [GitHub repository](https://github.com/T-Fang/pMFM_speedup/tree/main?tab=readme-ov-file).
