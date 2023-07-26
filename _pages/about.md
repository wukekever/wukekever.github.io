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

My research interest includes scientific computation and deep learning.

# 📝 Publications 

## 📄 Submitted
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Commun Comput Phys</div><img src='images/apnns-bgk.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Asymptotic-Preserving Neural Networks for Multiscale Kinetic Equations](http://export.arxiv.org/pdf/2306.15381)

Shi Jin, Zheng Ma, **Keke Wu**

[**Project**](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=qVvgz3IAAAAJ&citation_for_view=qVvgz3IAAAAJ:YsMSGLbcyi4C) <strong><span class='show_paper_citations' data='qVvgz3IAAAAJ:YsMSGLbcyi4C'></span></strong>
- In this paper, we present two novel Asymptotic-Preserving Neural Networks (APNNs) for tackling multiscale time-dependent kinetic problems, encompassing the linear transport equation and Bhatnagar-Gross-Krook (BGK) equation with diffusive scaling. Our primary objective is to devise efficient and accurate APNN approaches for resolving multiscale kinetic equations. We have established a neural network based on even-odd decomposition and concluded that enforcing the initial condition for the linear transport equation with inflow boundary conditions is crucial. This APNN method based on even-odd parity relaxes the stringent conservation prerequisites while concurrently introducing an auxiliary deep neural network. Additionally, we have incorporated the conservation laws of mass,  momentum, and energy for the Boltzmann-BGK equation into the APNN framework by enforcing exact boundary conditions. This is our second contribution. The most notable finding of this study is that approximating the zeroth, first and second moments of the particle density distribution is simpler than the distribution itself. Furthermore, a compelling phenomenon in the training process is that the convergence of density is swifter than that of momentum and energy. 
</div>
</div>

- Shi Jin, Zheng Ma, and Keke Wu. Shi Jin, Zheng Ma, and Keke Wu. [Asymptotic-preserving neural networks for multiscale kinetic
equations](http://export.arxiv.org/pdf/2306.15381). arXiv preprint arXiv:2306.15381.


## 🏷️ Accepted
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">J SCI COMPUT</div><img src='images/apnns-micro-macro.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Asymptotic-Preserving Neural Networks for Multiscale Time-Dependent Linear Transport Equations](https://arxiv.org/pdf/2111.02541.pdf)

Shi Jin, Zheng Ma, **Keke Wu**

[**Project**](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=qVvgz3IAAAAJ&citation_for_view=qVvgz3IAAAAJ:d1gkVwhDpl0C) <strong><span class='show_paper_citations' data='qVvgz3IAAAAJ:d1gkVwhDpl0C'></span></strong>
- In this paper we develop a neural network for the numerical simulation of time-dependent linear transport equations with diffusive scaling and uncertainties. The goal of the network is to resolve the computational challenges of curse-of-dimensionality and multiple scales of the problem. We first show that a standard Physics-Informed Neural Network (PINN) fails to capture the multiscale nature of the problem, hence justifies the need to use Asymptotic-Preserving Neural Networks (APNNs). We show that not all classical AP formulations are directly fit for the neural network approach. We construct a micro-macro decomposition based neural network, and also build in a mass conservation mechanism into the loss function, in order to capture the dynamic and multiscale nature of the solutions. 
</div>
</div>

- Shi Jin, Zheng Ma, and Keke Wu. [Asymptotic-preserving neural networks for multiscale
time-dependent linear transport equations](https://link.springer.com/article/10.1007/s10915-023-02100-0). Journal of Scientific Computing, 94(3):57, 2023.

## 💬 Presentations
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2016</div><img src='images/500x300.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Deep Residual Learning for Image Recognition](https://openaccess.thecvf.com/content_cvpr_2016/papers/He_Deep_Residual_Learning_CVPR_2016_paper.pdf)

**Kaiming He**, Xiangyu Zhang, Shaoqing Ren, Jian Sun

[**Project**](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=DhtAFkwAAAAJ&citation_for_view=DhtAFkwAAAAJ:ALROH1vI_8AC) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
</div>
</div>

- [Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet](https://github.com), A, B, C, **CVPR 2020**

## 📌 Life
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2016</div><img src='images/500x300.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Deep Residual Learning for Image Recognition](https://openaccess.thecvf.com/content_cvpr_2016/papers/He_Deep_Residual_Learning_CVPR_2016_paper.pdf)

**Kaiming He**, Xiangyu Zhang, Shaoqing Ren, Jian Sun

[**Project**](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=DhtAFkwAAAAJ&citation_for_view=DhtAFkwAAAAJ:ALROH1vI_8AC) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
</div>
</div>

- [Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet](https://github.com), A, B, C, **CVPR 2020**
