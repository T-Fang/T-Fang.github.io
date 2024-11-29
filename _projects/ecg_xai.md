---
layout: page
title: ECG XAI
description: An inherently explainable AI model that aligns predictions with clinical reasoning in electrocardiogram (ECG) diagnosis
img: assets/img/projects/ECG_XAI/ECG_XAI_thumbnail.jpg
importance: 1
category: Research Projects
related_publications: true
---

I carried out this project as my Final Year Project (undergraduate dissertation) {% cite Tian2023ECGXAI %}. The project was supervised by <a href="https://scholar.google.com/citations?user=_bza0AoAAAAJ">Prof. Brian Y. Lim</a> at the <a href="https://nus.edu.sg/">National University of Singapore</a>. The aim of this project is to develop an explainable AI (XAI) framework that aligns machine learning predictions with clinical reasoning in electrocardiogram (ECG) diagnosis, providing clinically relevant explanations to support cardiologists' decision-making.

Previous literatures on applying AI or machine learning to ECG diagnosis often focus on achieving high prediction accuracy. Although some papers do utilize some post-hoc XAI techniques to highlight parts of ECG that are most relevant to the prediction, these highlights often fail to provide insights aligned with cardiologists' clinical reasoning, which relies on identifying specific ECG patterns indicative of heart conditions.

To address this, I designed an inherently explainable AI framework that replicates cardiologists’ decision-making processes by incorporating logical rules used in ECG diagnoses. This framework retains the advantages of machine learning in detecting nuanced details while aligning its outputs with clinical reasoning. Furthermore, my framework can generate detailed diagnostic reports that explain predictions, such as pointing out relevant ECG patterns, making the results more interpretable and trustworthy for medical professionals.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/projects/ECG_XAI/ECG_XAI_example.png" title="Explanation to support prediction" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    The 12-lead ECG plot of a patient with anterior myocardial infarction (AMI). The ECG XAI model derived from the proposed framework can provide detailed explanations for its predictions, such as pointing out the ST-segment elevation in leads V1-V4, which is one of the hallmarks of AMI.
</div>

For more details, please refer to the [technical report](/assets/pdf/ECG_XAI.pdf). The code for this project is available on [GitHub](https://github.com/T-Fang/ECG_XAI).

Currently, we are adapting the framework to be more flexible, enabling it to address a wide range of prediction problems that require explanations aligned with predefined guidelines. To enhance usability, we are also developing an intuitive interface for users to design and edit their own rules and integrate them into an inherently explainable machine-learning model. This work is currently being prepared for submission to _UIST 2025_ {% cite Tian2024EditableXAI %}.
