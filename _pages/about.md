---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

<div style="margin-bottom: 30px;">
  <h1 style="font-size: 2.5em; margin-bottom: 10px;">Ze Chen</h1>
  <p style="font-size: 1.2em; color: #555;">Researcher in Computer Vision</p>
</div>

I am a self-motivated and ambitious student at Communication University of China, focused on computer vision research. I am committed to producing high-quality work. I am currently an undergraduate student at School of Information and Communication Engineering and a member of MIPG (Multimedia Intelligent Processing Group).

# 🔥 News
- *2024.12*: &nbsp;🎉🎉 Our paper "Exploring Kolmogorov-Arnold networks for realistic image sharpness assessment" has been accepted by ICASSP 2025!

# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICASSP 2025</div><img src='images/kan_iqa.png' alt="KAN for Image Quality Assessment" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Exploring Kolmogorov-Arnold networks for realistic image sharpness assessment](https://ieeexplore.ieee.org/abstract/document/10890447)

Shaode Yu, ***Ze Chen***, Zhimu Yang, Jiacheng Gu, Bizu Feng, Qiurui Sun*

[Paper](https://ieeexplore.ieee.org/abstract/document/10890447) | [Code](https://github.com/CUC-Chen/KAN4IQA) <strong><span class='show_paper_citations' data='10890447'></span></strong>
- This paper is the first to apply Kolmogorov-Arnold Networks (KANs) to image quality assessment
- We introduce a novel Taylor series-based KAN (TaylorKAN) that models complex nonlinear relationships between image features and quality scores
- Extensive experiments on four databases (BID2011, CID2013, CLIVE, and KonIQ-10k) demonstrate that KANs outperform traditional methods
</div>
</div>

# 🧠 Research Interests

## Deep Generative Models
With the advancement of deep generative models, my research focus has shifted from U-Net based models to those built on DiT (Diffusion Transformer) architectures. I am committed to exploring token interactions in DiT and developing video generation techniques that align with real-world physical principles.

## Large Language Models
I am interested in exploring the current level of perception and understanding of the real world exhibited by Multimodal Large Language Models (MLLMs). At the same time, I am considering more rational and effective approaches to LoRA fine-tuning, particularly to enable personalized customization of these models.

## Probabilistic Modeling
Recently, flow matching has brought fresh ideas to generative modeling. My focus splits into two: advancing probabilistic modeling methods like DDPM and DDIM, which rely on the mathematics of SDEs and ODEs that I'm fascinated by, and designing novel model architectures by turning my brainstorm into real outcomes.

# 📖 Education
- *2023.09 - Present*, **Undergraduate Studies**, B.Eng. in Artificial Intelligence, Communication University of China
- *2020.09 - 2023.06*, **High School Education**, Shanghai Shixi High School

# 💻 Research Experience
- *2024.09 - Present*, **Research Intern**, Multimedia Intelligent Processing Group (MIPG), State Key Laboratory of Media Convergence and Communication, Communication University of China
- *2021.07 - 2023.01*, **Research Intern**, State Key Laboratory of Advanced Optical Communication Systems and Networks, Shanghai Jiao Tong University

---

<div style="text-align: center; color: #666; font-size: 0.9em; margin-top: 50px;">
Last updated: April 2025
</div>
