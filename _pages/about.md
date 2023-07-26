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

<img class="image" src="assets/3d/dog.glb"/>

Hello, I'm a PhD student at Shanghai Jiao Tong University. My research interest includes scientific computation and deep learning. I'm currently working on the application of deep learning in scientific computation and also interested in the application of deep learning in computer vision and natural language processing. 

In the field of AI for Science (AI4S), my collaborators and I have made a noteworthy discovery. We found that a vanilla Physics-Informed Neural Network (PINN) is inadequate in capturing the intricate multiscale nature of the problem at hand. As a remedy, we put forth two groundbreaking Asymptotic-Preserving Neural Networks (APNNs) designed to effectively address the complexities of the multiscale time-dependent linear transport equations, replete with diffusive scaling and uncertainties.
Furthermore, our efforts extended to the development of APNNs, which proficiently tackle multiscale nonlinear kinetic problems, encompassing the gray radiative transfer equations (GRTEs) and Bhatnagar-Gross-Krook (BGK) equations. In addition, we delved into the realm of operator learning, where we introduced two Asymptotic-Preserving Convolutional Deep Operator Networks (APCONs) with the capability to adeptly capture the diffusive behavior inherent in the multiscale linear transport equations.


# 📝 Publications 

## 📄 Submitted
<!-- <div class='paper-box'><div class='paper-box-image'><div><div class="badge">J Comput Phys</div><img src='images/apnns-grte.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Asymptotic-Preserving Neural Network based on Even-odd Decomposition for Multiscale Gray Radiative Transfer Equations](http://arxiv.org/pdf/2306.15891.pdf)

**Keke Wu**, Xiong-bin Yan, Shi Jin, Zheng Ma 

[**Project**](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=qVvgz3IAAAAJ&citation_for_view=qVvgz3IAAAAJ:W7OEmFMy1HYC) <strong><span class='show_paper_citations' data='qVvgz3IAAAAJ:W7OEmFMy1HYC'></span></strong>
- We present a novel Asymptotic-Preserving Neural Network (APNN) approach utilizing even-odd decomposition to tackle the nonlinear gray radiative transfer equations (GRTEs). The novel AP loss demonstrates consistent stability concerning the small Knudsen number, ensuring the neural network solution uniformly converges to the macro solution. This APNN method alleviates the rigorous conservation requirements while simultaneously incorporating an auxiliary deep neural network, distinguishing it from the APNN method based on micro-macro decomposition for GRTE. Several numerical problems are examined to demonstrate the effectiveness of our proposed APNN technique.
</div>
</div>

- Keke Wu, xxx, ..., Zheng Ma. [Asymptotic-preserving convolutional deep-
onets capture the diffusive behavior of the multiscale linear transport equations](http://arxiv.org/pdf/2306.15891.pdf). arXiv preprint
arXiv:2306.15891, 2023. -->


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">J Comput Phys</div><img src='images/apcons.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Asymptotic-Preserving Convolutional DeepONets Capture the Diffusive Behavior of the Multiscale Linear Transport Equations](http://arxiv.org/pdf/2306.15891.pdf)

**Keke Wu**, Xiong-bin Yan, Shi Jin, Zheng Ma 

[**Project**](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=qVvgz3IAAAAJ&citation_for_view=qVvgz3IAAAAJ:W7OEmFMy1HYC) <strong><span class='show_paper_citations' data='qVvgz3IAAAAJ:W7OEmFMy1HYC'></span></strong>
- In this paper, we introduce two types of novel Asymptotic-Preserving Convolutional Deep Operator Networks (APCONs) designed to address the multiscale time-dependent linear transport problem. We observe that the vanilla physics-informed DeepONets with modified MLP may exhibit instability in maintaining the desired limiting macroscopic behavior. Therefore, this necessitates the utilization of an asymptotic-preserving loss function. Drawing inspiration from the heat kernel in the diffusion equation, we propose a new architecture called Convolutional Deep Operator Networks, which employ multiple local convolution operations instead of a global heat kernel, along with pooling and activation operations in each filter layer. Our APCON methods possess a parameter count that is independent of the grid size and are capable of capturing the diffusive behavior of the linear transport problem.
</div>
</div>

- Keke Wu, Xiong-bin Yan, Shi Jin, and Zheng Ma. [Asymptotic-preserving convolutional deep-
onets capture the diffusive behavior of the multiscale linear transport equations](http://arxiv.org/pdf/2306.15891.pdf). arXiv preprint
arXiv:2306.15891, 2023.


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Commun Comput Phys</div><img src='images/apnns-bgk.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Asymptotic-Preserving Neural Networks for Multiscale Kinetic Equations](http://arxiv.org/pdf/2306.15381.pdf)

Shi Jin, Zheng Ma, **Keke Wu**

[**Project**](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=qVvgz3IAAAAJ&citation_for_view=qVvgz3IAAAAJ:YsMSGLbcyi4C) <strong><span class='show_paper_citations' data='qVvgz3IAAAAJ:YsMSGLbcyi4C'></span></strong>
- In this paper, we present two novel Asymptotic-Preserving Neural Networks (APNNs) for tackling multiscale time-dependent kinetic problems, encompassing the linear transport equation and Bhatnagar-Gross-Krook (BGK) equation with diffusive scaling. Our primary objective is to devise efficient and accurate APNN approaches for resolving multiscale kinetic equations. We have established a neural network based on even-odd decomposition and concluded that enforcing the initial condition for the linear transport equation with inflow boundary conditions is crucial. This APNN method based on even-odd parity relaxes the stringent conservation prerequisites while concurrently introducing an auxiliary deep neural network. Additionally, we have incorporated the conservation laws of mass,  momentum, and energy for the Boltzmann-BGK equation into the APNN framework by enforcing exact boundary conditions. This is our second contribution. The most notable finding of this study is that approximating the zeroth, first and second moments of the particle density distribution is simpler than the distribution itself. Furthermore, a compelling phenomenon in the training process is that the convergence of density is swifter than that of momentum and energy. 
</div>
</div>

- Shi Jin, Zheng Ma, and Keke Wu. [Asymptotic-preserving neural networks for multiscale kinetic
equations](http://arxiv.org/pdf/2306.15381.pdf). arXiv preprint arXiv:2306.15381, 2023.


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

# 💬 Presentations
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2016</div><img src='images/500x300.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Deep Residual Learning for Image Recognition](https://openaccess.thecvf.com/content_cvpr_2016/papers/He_Deep_Residual_Learning_CVPR_2016_paper.pdf)

**Kaiming He**, Xiangyu Zhang, Shaoqing Ren, Jian Sun

[**Project**](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=DhtAFkwAAAAJ&citation_for_view=DhtAFkwAAAAJ:ALROH1vI_8AC) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
</div>
</div>

- [Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet](https://github.com), A, B, C, **CVPR 2020**

# 📌 Life
## Shanghai
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">2023.04.09</div><img src='images/shanghai0.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">2022.01.02</div><img src='images/shanghai1.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
</div>
</div>

## Xiamen
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">2021.05.02</div><img src='images/xiamen1.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">2023.05.01</div><img src='images/xiamen0.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
</div>
</div>

## Suzhou
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">2021.07.29</div><img src='images/suzhou0.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">2020.08.21</div><img src='images/suzhou1.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
</div>
</div>


