---
layout: page
title: WottleNFT
description: a sustainable NFT Marketplace built on the Cardano Blockchain
img: assets/img/projects/WottleNFT/WottleNFT_thumbnail.gif
importance: 2
category: Apps and Tools
---

# WottleNFT

<div class="row justify-content-center">
    <!-- <div class="d-flex justify-content-center">
        <iframe width="560" height="315" src="https://www.youtube.com/embed/8s6AXX16T6Q?si=6GXO8HVwsSTW1JGP" title="WottleNFT Promotion Video" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
    </div> -->
    <div class="col-sm mt-3 mt-md-0">
        {% include video.liquid path="https://www.youtube.com/embed/8s6AXX16T6Q?si=6GXO8HVwsSTW1JGP" title="WottleNFT Promotion Video" class="img-fluid rounded z-depth-1" controls=true autoplay=false %}
    </div>
</div>
<div class="caption">
    WottleNFT Promotion Video
</div>

Promotional Video URL: https://youtu.be/8s6AXX16T6Q

# Description

WottleNFT, a student-initiated startup, is a Cardano NFT marketplace. It serves as a platform for collectors of NFTs on the Cardano blockchain to trade their NFTs efficiently and with low transaction costs. It also boasts an easy-to-use NFT minting page, where users may mint their very own NFT on the Cardano blockchain straight from the browser.

Importantly, the core of WottleNFT’s marketplace is its focus on supporting humanitarian efforts. Every trade on the WottleNFT marketplace will contribute towards the United Nations Sustainable Development Goals (SDG) - when a user chooses to list his/her NFT on the marketplace, he/she will be prompted to select a UN SDG to support. Currently, users may choose between 3 SDGs to support: Zero Hunger, Climate Action or Quality Education. When the listed NFT is successfully sold, 1% of the transaction will be donated towards the selected UN SDG. That way, the popularity of NFTs can be harnessed to do good, in the form of raising money for meaningful causes.

## My Role

I am in charge of the **front-end development** of the WottleNFT website. Below are some of my key contributions:

1. Exchange ideas with the design team using Figma.
2. Optimize image loading and webpage navigation using Next.js
3. Search Engine Optimization with Open Graph support (Next SEO).
4. Achieve native look and feel using Ionic framework.
5. Responsive design using Tailwind.

## Our Story

Here at WottleNFT, we aim to bring out the true value behind each Cardano NFT by providing a space for the Creators to share their stories. It is also important to give back, especially with the outbreak of the Covid-19 Pandemic. That is why, WottleNFT will be aligning its business model with the United Nation Sustainable Development Goals (SDGs) to support Social Enterprises worldwide. Furthermore, we are empowering you to support them! With every transaction made on WottleNFT, you get to choose which of the UN Goal to support. For now, WottleNFT is focusing on 3 UN Goals : Zero Hunger, Climate Action and Quality Education.

## Our Focus

WottleNFT focus is to help the whole of Cardano Community better determine the appropriate prices for each NFT by creating a Cardano Marketplace that is story focused, details centric and community driven. We believe that price is only what you pay; value is what you get.

## Marketplace

WottleNFT will first focus on building an amazing marketplace. Afterwhich, we aim to integrate Cardano Smart Contracts by December. Listing is FREE\*. You just need to pay ~2₳ : 1₳ pegged to your NFT and ~1₳ for transactional Fee. Upon successful sale, we charge a 3% fee, with a minimum of 2₳ for each transaction. This fee comprises: Service Fees (1₳,2%) and Social Donations (1₳,1%). If you are a successful buyer/seller, head over to the profile section to choose one of the 3 UN Goals to support : Zero Hunger, Climate Action or Quality Education

## NFT Minter

WottleNFT wants to make Cardano NFT as easy and as accessible to everyone. As such, we have implemented a whole new in-browser experience that offers the lowest minting service fee in the market. Mint 1 Cardano NFT for 1 ADA in just under 1 Minute with our very own Nami Wallet enabled NFT-minter.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/projects/WottleNFT/WottleNFT_poster.png" title="WottleNFT Poster" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    WottleNFT Poster
</div>

a research internship project at <a href="https://scholar.google.com/citations?user=BOUzsU8AAAAJ">Prof. B.T. Thomas Yeo</a>'s <a href="https://sites.google.com/view/yeolab">lab</a> at the <a href="https://nus.edu.sg/">National University of Singapore</a>. The goal of this project is to leverage machine learning and deep learning to accelerate the parameter optimization process for the mean-field model(MFM), or more precisely parametric MFM (pMFM).

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
4. Explored various optimization techniques such as Covariance matrix adaptation evolution strategy (CMA-ES) and Gradient Descent

In the end, I have demonstrated the feasibility of using machine learning to accelerate the pMFM parameter optimization process. This project has led to a paper {% cite Zeng2024DELSSOME %} that we are currently preparing for submission to _Nature Methods_. For more details of this project, please visit the [GitHub repository](https://github.com/T-Fang/pMFM_speedup/tree/main?tab=readme-ov-file).
