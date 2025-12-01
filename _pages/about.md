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

### Hi 👋, I'm Chunyan She
[![](https://img.shields.io/badge/Research-ORCID-blue)](https://orcid.org/0000-0001-8188-938X)
[![](https://img.shields.io/badge/Research-GoogleScholar-red)](https://scholar.google.com/citations?user=1VmMLe4AAAAJ&hl=zh-CN&oi=ao)


<img align="right" alt="GIF" src="/images/code.gif" width="240" height="155" />
I am currently a Ph.D. student at the College of Artificial Intelligence, Southwest University, Chongqing, China.

- 💻 My major is **Computer Science and Technology**.
- 🔭 I’m currently working on deep learning and computer vision, in particular generative model and image enhancement. I have published some papers in the IEEE Transactions on Circuits and Systems for Video Technology (TCSVT), IEEE Transactions on Intelligent Vehicles (TIV) and Knowledge-Based Systems (KBS).

# 📖 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACMMM 2025</div><img src='/images/ACMMM-EventLLIE.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Exploring Fourier Prior and Event Collaboration for Low-Light Image Enhancement](https://dl.acm.org/doi/10.1145/3746027.3754948) \\
**Chunyan She**; Fujun Han; Chengyu Fang; Shukai Duan; Lidan Wang;

[**Paper**](https://dl.acm.org/doi/10.1145/3746027.3754948)

- In this work, we propose a two-stage decoupling framework called EventLLIE. Compared to the existing LLIE, it is aware of the fact that the frameand events carry content and structure information, respectively. Specifically, the enhancement pipeline is decoupled into two stagesconsisting of visibility restoration and structure refnement.
</div>
</div>



<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TETCI 2025</div><img src='/images/TETCI-GLCFormer.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Low-Light Image Enhancement via Global-Local Collaborative Transformer](https://ieeexplore.ieee.org/document/11150743) \\
**Chunyan She**; Fujun Han; Feng Pan; Shukai Duan; Tingwen Huang; Lidan Wang;

[**Paper**](https://ieeexplore.ieee.org/document/11150743)

- In this work, we propose a global-local collaborative transformer, an enhancer inspired by image editing experts, which exploits the collaboration between global and local adjustment to adaptively enhance low-light images with complex exposure.
</div>
</div>



<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TCSVT 2024</div><img src='/images/TCSVT-MPC-Net.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[MPC-Net: Multi-Prior Collaborative Network for Low-Light Image Enhancement](https://ieeexplore.ieee.org/document/10543170) \\
**Chunyan She**; Fujun Han; Lidan Wang; Shukai Duan; Tingwen Huang

[**Paper**](https://ieeexplore.ieee.org/document/10543170)

- MPC-Net is a multi-prior collaborative network with transformer for low-light image enhancement.
</div>
</div>



<div class='paper-box'><div class='paper-box-image'><div><div class="badge">KBS 2023</div><img src='/images/KBS-SAGAN.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[SAGAN: Deep semantic-aware generative adversarial network for unsupervised image enhancement](https://www.sciencedirect.com/science/article/pii/S0950705123008031) \\
**Chunyan She**; Tao Chen; Shukai Duan; Lidan Wang

[**Paper**](https://www.sciencedirect.com/science/article/pii/S0950705123008031)

- SAGAN adopts the pre-trained VGG model on ImageNet to extract the prior semantic information, which is organically fed into the generator to refine its feature representation, and develop an adaptive image fusion strategy working on the output layer of the generator.

</div>
</div>



<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TIV 2024</div><img src='/images/TIV-MMID-Bench.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[MMID-Bench: A Comprehensive Benchmark for Multi-domain Multi-category Intrusion Detection](https://ieeexplore.ieee.org/document/10440535) \\
Fujun Han; Peng Ye; **Chunyan She**; Shukai Duan; Lidan Wang; Derong Liu

[**Paper**](https://ieeexplore.ieee.org/document/10440535)

- In this work, we propose a comprehensive benchmark to address the aforementioned intrusion detection tasks, including multiple datasets, reasonable metrics, End-to-End framework design, and extensive evaluations.

</div>
</div>

- Wang Y, **She C**, Sun J, et al. Signal-to-noise ratio guided noise adaptive network via Dual-domain collaboration for low-light image enhancement[J]. Engineering Applications of Artificial Intelligence, 2025, 162: 112578.
- Hu H, **She C**, Wang L, et al. UCT: Uncertainty-Based Consistency Training for Domain Adaptive Human Activity Recognition[J]. Digital Signal Processing, 2025: 105209.
- Chen T, **She C**, Wang L, et al. Memristive leaky integrate-and-fire neuron and learnable straight-through estimator in spiking neural networks[J]. Cognitive Neurodynamics, 2024, 18(5): 3075-3091.
- **She C**, Zeng S, Wang Q, et al. Adaptive fuzzy C-means clustering integrated with local outlier factor[J]. Intelligent Data Analysis, 2022, 26(6): 1507-1521.
- **She C**, Zeng S. An enhanced local outlier detection using random walk on grid information graph[J]. The Journal of Supercomputing, 2022, 78(12): 14530-14547.



# 📐 Projects
1. Research Project of Southwest University. (2024-)
2. Research Project of Chongqing Normal University. (2020-2022)


# ✒️ Patents
1. Wang L, She C, Duan S. A low-light image enhancement method based on multi-prior fusion[P]. Chongqing: CN117745616A,2024-03-22.
2. Zeng S, She C, Wang S, et al. An adaptive FCM algorithm for soil image shadow detection[P]. Chongqing: CN111754501B,2021-08-27.
3. Zeng S, Wang Q, She C, et al. Shadow detection of soil image based on subtraction histogram algorithm[P]. Chongqing: CN113240619B,2022-06-21.


# 🎖 Honors and Awards
- 2024, National Scholarship
- 2019, Outstanding Graduates
- 2017, National Scholarship
- 2016, National Encouragement Scholarship





