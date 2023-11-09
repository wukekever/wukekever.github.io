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


<!-- <!DOCTYPE html>
<html lang = "en">
    <head>
        <meta charset = "UTF-8">
        <meta http-equiv = "x-ua-compatible" content = "IE=edge">
        <meta name = "viewport" content= "width=device-width, initial-scale=1.0">
        <script type="module" src="https://unpkg.com/@google/model-viewer/dist/model-viewer.min.js"></script>
        
        <title>portfolio</title>

        <style>
            .box {display:flex;}
            mode-viewer {width: 800px; height: 500px; margin:0, auto}
        </style>
    </head>

    <body>
        <div class = "box">
            <div>Hey check this out</div>
            <div>
                <model-viewer camera-controls alt="Model" src="assets/3d/dog.glb">
                </model-viewer>
            </div>
        </div>
    </body> 

</html> -->


<!-- Hello, I am a PhD student at Shanghai Jiao Tong University, advised by Zheng Ma. 
I received my master's degree from Soochow University, advised by Jingrun Chen and Rui Du.  -->
My research interest includes scientific computation and deep learning. 
The deep learning frameworks now I used are JAX, TensorFlow, PyTorch, MATLAB, Julia, etc.
I am currently working on the application of deep learning in scientific computation and also interested in the application of deep learning in computer vision and natural language processing. 

<!-- In the field of AI for Science (AI4S), my collaborators and I found that a vanilla Physics-Informed Neural Network (PINN) is inadequate in capturing the intricate multiscale nature of the problem at hand. As a remedy, we put forth two groundbreaking Asymptotic-Preserving Neural Networks (APNNs) designed to effectively address the complexities of the multiscale time-dependent linear transport equations, replete with diffusive scaling and uncertainties.
Furthermore, our efforts extended to the development of APNNs, which proficiently tackle multiscale nonlinear kinetic problems, encompassing the gray radiative transfer equations (GRTEs) and Bhatnagar-Gross-Krook (BGK) equations. In addition, we delved into the realm of operator learning, where we introduced two Asymptotic-Preserving Convolutional Deep Operator Networks (APCONs) with the capability to adeptly capture the diffusive behavior inherent in the multiscale linear transport equations. -->


<!-- # 🚀 Curriculum Vitae -->


<!-- My CV can be found here: [Chinese](https://github.com/wukekever/wukekever.github.io/tree/main/pdfs/Resume_cn.pdf) and [English](https://github.com/wukekever/wukekever.github.io/tree/main/pdfs/Resume_en.pdf) -->
<!-- My CV can be found here: [English](https://github.com/wukekever/wukekever.github.io/tree/main/pdfs/Resume_en.pdf) -->


# 📝 Publications 

- [8] **Keke Wu** et al., Asymptotic-Preserving Neural Network based on Even-odd Decomposition for Multiscale Gray Radiative Transfer Equations.
- [7] Xiong-Bin Yan, **Keke Wu**, Zhi-Qin John Xu, Zheng Ma. [An Unsupervised Deep Learning Approach for the Wave Equation Inverse Problem](https://arxiv.org/abs/2311.04531). arXiv preprint arXiv:2311.04531, 2023.
- [6] **Keke Wu**, Xiong-Bin Yan, Shi Jin, and Zheng Ma. [Capturing the Diffusive Behavior of the Multiscale Linear Transport Equations by Asymptotic-Preserving Convolutional DeepONets](https://www.sciencedirect.com/science/article/pii/S0045782523006552). Computer Methods in Applied Mechanics and Engineering, 418:116531, 2024.
- [5] Shi Jin, Zheng Ma, and **Keke Wu**. [Asymptotic-Preserving Neural Networks for Multiscale Kinetic Equations](http://arxiv.org/abs/2306.15381). arXiv preprint arXiv:2306.15381, 2023. (Corresponding author)
- [4] Shi Jin, Zheng Ma, and **Keke Wu**. [Asymptotic-Preserving Neural Networks for Multiscale Time-Dependent Linear Transport Equations](https://link.springer.com/article/10.1007/s10915-023-02100-0). Journal of Scientific Computing, 94(3):57, 2023. (Corresponding author)  
- [3] **Keke Wu**, Xiangru Jian, Rui Du, Jingrun Chen, and Xiang Zhou. [Roughness Index for Loss Landscapes of Neural Network Models of Partial Differential Equations](https://arxiv.org/abs/2103.11069). Proceedings of the IEEE International Conference on Big Data, 2023.   
- [2] Liyao Lyu, **Keke Wu**, Rui Du, and Jingrun Chen. [Enforcing Exact Boundary and Initial Conditions in the Deep Mixed Residual Method](https://www.global-sci.org/intro/article_detail/csiam-am/19991.html). CSIAM Transactions on Applied Mathematics, 2(4)(2021) 748-775. (Equal contribution)
- [1] Jingrun Chen, Rui Du, and  **Keke Wu**.[A Comparison Study of Deep Galerkin Method and Deep Ritz Method for Elliptic Problems with Different Boundary Conditions](https://global-sci.org/intro/article_detail/cmr/17853.html). Communications in Mathematical Research, 36(3)(2020) 354-376. (Corresponding author)



# 📄 Selected Projects
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Comput Methods Appl Mech Eng</div><img src='images/apcons.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Capturing the Diffusive Behavior of the Multiscale Linear Transport Equations by Asymptotic-Preserving Convolutional DeepONets](http://arxiv.org/pdf/2306.15891.pdf)

**Keke Wu**, Xiong-Bin Yan, Shi Jin, Zheng Ma 

[**Project**](https://github.com/wukekever/apcons) <strong><span class='show_paper_citations' data='qVvgz3IAAAAJ:W7OEmFMy1HYC'></span></strong>
<!-- [**Project**](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=qVvgz3IAAAAJ&citation_for_view=qVvgz3IAAAAJ:W7OEmFMy1HYC) <strong><span class='show_paper_citations' data='qVvgz3IAAAAJ:W7OEmFMy1HYC'></span></strong> -->
- In this paper, we introduce two types of novel Asymptotic-Preserving Convolutional Deep Operator Networks (APCONs) designed to address the multiscale time-dependent linear transport problem. We observe that the vanilla physics-informed DeepONets with modified MLP may exhibit instability in maintaining the desired limiting macroscopic behavior. Therefore, this necessitates the utilization of an asymptotic-preserving loss function. Drawing inspiration from the heat kernel in the diffusion equation, we propose a new architecture called Convolutional Deep Operator Networks, which employ multiple local convolution operations instead of a global heat kernel, along with pooling and activation operations in each filter layer. Our APCON methods possess a parameter count that is independent of the grid size and are capable of capturing the diffusive behavior of the linear transport problem.
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Submitted</div><img src='images/apnns-bgk.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Asymptotic-Preserving Neural Networks for Multiscale Kinetic Equations](http://arxiv.org/pdf/2306.15381.pdf)

Shi Jin, Zheng Ma, **Keke Wu**

[**Project**](https://github.com/wukekever/apnns) <strong><span class='show_paper_citations' data='qVvgz3IAAAAJ:YsMSGLbcyi4C'></span></strong>
<!-- [**Project**](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=qVvgz3IAAAAJ&citation_for_view=qVvgz3IAAAAJ:YsMSGLbcyi4C) <strong><span class='show_paper_citations' data='qVvgz3IAAAAJ:YsMSGLbcyi4C'></span></strong> -->
- In this paper, we present two novel Asymptotic-Preserving Neural Networks (APNNs) for tackling multiscale time-dependent kinetic problems, encompassing the linear transport equation and Bhatnagar-Gross-Krook (BGK) equation with diffusive scaling. Our primary objective is to devise efficient and accurate APNN approaches for resolving multiscale kinetic equations. We have established a neural network based on even-odd decomposition and concluded that enforcing the initial condition for the linear transport equation with inflow boundary conditions is crucial. This APNN method based on even-odd parity relaxes the stringent conservation prerequisites while concurrently introducing an auxiliary deep neural network. Additionally, we have incorporated the conservation laws of mass,  momentum, and energy for the Boltzmann-BGK equation into the APNN framework by enforcing exact boundary conditions. This is our second contribution. The most notable finding of this study is that approximating the zeroth, first and second moments of the particle density distribution is simpler than the distribution itself. Furthermore, a compelling phenomenon in the training process is that the convergence of density is swifter than that of momentum and energy. 
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">J SCI COMPUT</div><img src='images/apnns-micro-macro.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Asymptotic-Preserving Neural Networks for Multiscale Time-Dependent Linear Transport Equations](https://arxiv.org/pdf/2111.02541.pdf)

Shi Jin, Zheng Ma, **Keke Wu**

[**Project**](https://github.com/wukekever/apnns) <strong><span class='show_paper_citations' data='qVvgz3IAAAAJ:d1gkVwhDpl0C'></span></strong>
<!-- [**Project**](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=qVvgz3IAAAAJ&citation_for_view=qVvgz3IAAAAJ:d1gkVwhDpl0C) <strong><span class='show_paper_citations' data='qVvgz3IAAAAJ:d1gkVwhDpl0C'></span></strong> -->
- In this paper we develop a neural network for the numerical simulation of time-dependent linear transport equations with diffusive scaling and uncertainties. The goal of the network is to resolve the computational challenges of curse-of-dimensionality and multiple scales of the problem. We first show that a standard Physics-Informed Neural Network (PINN) fails to capture the multiscale nature of the problem, hence justifies the need to use Asymptotic-Preserving Neural Networks (APNNs). We show that not all classical AP formulations are directly fit for the neural network approach. We construct a micro-macro decomposition based neural network, and also build in a mass conservation mechanism into the loss function, in order to capture the dynamic and multiscale nature of the solutions. 
</div>
</div>


# 💬 Presentations
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Minisymposium</div><img src='images/waseda.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[**Talk for ICIAM Minisymposium**](https://github.com/wukekever/wukekever.github.io/tree/main/pdfs/iciam2023.pdf)

**Keke Wu**

- Topic: [Analysis and Numerics on Deep Learning Based Methods for Solving PDEs](https://iciam2023.org/registered_data?id=00747)
- Abstract: Various difficult PDE problems from the science and engineering now tend to be solved by numerical methods based on deep learning. This minisymposium focuses on both analytic and numerical aspects of these new methods. The speakers will talk about their recent works on the mechanism and further improvement of variational or/and physics-informed DNN-based solvers with applications to scientific computing problems.
- Organizers: Tao Luo, Zheng Ma, Zhiping Mao

[**Paper link**](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=qVvgz3IAAAAJ&citation_for_view=qVvgz3IAAAAJ:d1gkVwhDpl0C) <strong><span class='show_paper_citations' data='qVvgz3IAAAAJ:d1gkVwhDpl0C'></span></strong>

</div>
</div>

# 📌 Life
## Skytree - Tokyo
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">2023.08.21</div><img src='images/tokyo.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
The Tokyo Skytree is an iconic landmark and communication tower located in Sumida, Tokyo. It stands as one of the tallest freestanding towers in the world, soaring to an impressive height of 634 meters. This architectural marvel was completed in 2012 and has since become a symbol of Tokyo's modern skyline and technological advancement. The tower serves multiple purposes, primarily functioning as a broadcasting tower for television and radio signals. However, it is also a major tourist attraction, offering visitors breathtaking panoramic views of Tokyo and its surroundings from its observation decks. The two main observation decks, known as the Tembo Deck and the Tembo Galleria, are located at heights of 350 meters and 450 meters respectively, providing visitors with stunning vistas of the city, including famous landmarks like Tokyo Tower and Mount Fuji on clear days.

</div>
</div>

## Tour of Ronghao Li - Suzhou
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">2023.07.29</div><img src='images/lironghao1_suzhou.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
Li Ronghao is a renowned Chinese singer, songwriter, and music producer. Born on July 11, 1985, in Guangzhou, China, he has gained widespread recognition for his exceptional musical talent and unique style. He made his debut in the Chinese music industry in 2013 with the release of his first album, "Model". This album featured a mix of pop, rock, and electronic elements, showcasing Li Ronghao's versatility as an artist. 

</div>
</div>

<!-- <div class='paper-box'><div class='paper-box-image'><div><div class="badge">2023.07.29</div><img src='images/lironghao2_suzhou.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
</div>
</div> -->

## The Bund - Shanghai
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">2023.04.09</div><img src='images/shanghai0.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
Shanghai Bund is one of Shanghai's most iconic landmarks and a symbol of the city's rich history and modernity. Situated along the western bank of the Huangpu River in the heart of Shanghai, the Bund is a waterfront promenade lined with a stunning collection of historic and modern architecture. The Bund's history dates back to the 19th century when it was a hub of international trade and finance. During this period, many European and American banks and trading houses set up their offices in the area, leaving behind a legacy of grand neo-classical and Art Deco buildings. 

</div>
</div>

<!-- <div class='paper-box'><div class='paper-box-image'><div><div class="badge">2022.01.02</div><img src='images/shanghai1.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
</div>
</div> -->

##  Zengcuo'An - Xiamen
<!-- <div class='paper-box'><div class='paper-box-image'><div><div class="badge">2023.05.02</div><img src='images/xiamen1.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
</div>
</div> -->

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">2023.05.01</div><img src='images/xiamen0.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
Zengcuo'an is a charming coastal village located in Xiamen, Fujian Province, China. This picturesque destination has gained popularity for its unique blend of traditional Chinese architecture and a vibrant, bohemian atmosphere. It is renowned for its distinctive whitewashed buildings adorned with colorful doors and windows, creating a delightful contrast against the backdrop of the azure sea. The narrow winding streets are lined with quaint cafes, boutique shops, and local seafood restaurants, making it a haven for both tourists and artists seeking inspiration. 
</div>
</div>

## The Gate of the Orient - Suzhou
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">2021.07.29</div><img src='images/suzhou0.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
The Gate of the Orient is a prominent landmark and cultural symbol located in the city of Suzhou, China. This iconic structure stands as a testament to the city's rich history and modern development. It is an architectural marvel that combines traditional Chinese design elements with contemporary aesthetics. Its design draws inspiration from classical Chinese gates and archways, featuring intricate carvings, ornate decorations, and a distinctive roofline. The gate is often adorned with vibrant red colors, which are symbolic of prosperity and good fortune in Chinese culture. Beyond its architectural beauty, it serves as a gateway to the city, welcoming visitors with open arms. 

</div>
</div>

<!-- <div class='paper-box'><div class='paper-box-image'><div><div class="badge">2020.08.21</div><img src='images/suzhou1.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
</div>
</div> -->
