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

I am an MPhil student at the [Hong Kong University of Science and Technology (Guangzhou)](https://www.hkust-gz.edu.cn/), advised by Prof. [Hui Xiong (熊辉)](IEEE, ACM, CCF Fellow)(https://facultyprofiles.hkust-gz.edu.cn/faculty-personal-page/XIONG-Hui/huixiong). 

My research focuses on **Multimodal Large Language Models (MLLMs)** and **Computer Vision**, with particular interest in table understanding, visual question answering, and document intelligence. I am passionate about building AI systems that can reason across text, images, and structured data.

# 🔥 News
- *2026.04*: &nbsp;🎉🎉 Our paper is accepted by acl 2026!
- *2026.04*: &nbsp;🎉🎉 Our paper [TableVision](https://arxiv.org/abs/2604.03660) is now on arXiv!
- *2026.02*: &nbsp;🎉🎉 Our paper [VideoAfford](https://arxiv.org/abs/2602.09638) is now on arXiv!

# 📝 Publications 

<!-- 
  使用方式：
  <div class='paper-box'>...</div> 用于重点论文（带图）
  - [Title](link), Authors, **Venue Year** 用于普通列表论文
-->

*(\* indicates equal contribution)*

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">arXiv 2026</div><img src='images/tablevision.png' alt="TableVision" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[**TableVision: A Large-Scale Benchmark for Spatially Grounded Reasoning over Complex Hierarchical Tables**](https://arxiv.org/abs/2604.03660)

**Xiaoyu Chen**, Lu Dai, Hanqing Wang, Zhuoyu Li, Wenbin Dai, Yanzong Zheng, Zhenggang Xia, Junyong Lin, Hui Xiong

[**arXiv**](https://arxiv.org/abs/2604.03660)
- Introduces TableVision, a large-scale trajectory-aware benchmark with 6,799 reasoning trajectories for spatially grounded reasoning over complex hierarchical tables, identifying the "Perceptual Overload" bottleneck in MLLMs.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">arXiv 2026</div><img src='images/videoafford.png' alt="VideoAfford" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[**VideoAfford: Grounding 3D Affordance from Human-Object-Interaction Videos via Multimodal Large Language Model**](https://arxiv.org/abs/2602.09638)

Hanqing Wang, Mingyu Liu, **Xiaoyu Chen**, Chengwei Ma, Yiming Zhong, Wenti Yin, Yuhao Liu, Zhiqing Cui, Jiahao Yuan, Lu Dai, Zhiyuan Ma, Hui Xiong

[**arXiv**](https://arxiv.org/abs/2602.09638)
- Collects VIDA, a 38K HOI video dataset covering 16 affordance types and 38 object categories; proposes VideoAfford to enable MLLMs with fine-grained 3D affordance grounding via latent action encoding and spatial-aware loss.
</div>
</div>

- [**Graph Attention and Layer Refinement Integrated LightGCN for Enhanced Recommender System**](https://ieeexplore.ieee.org/document/11021789), **Xiaoyu Chen**, et al., *IEEE*

# 📖 Educations
- *2025.09 - Present*, M.Phil., [Information Hub](https://www.hkust-gz.edu.cn/academics/hubs-and-thrust-areas/information-hub/), Hong Kong University of Science and Technology (Guangzhou). Advised by Prof. [Hui Xiong](https://facultyprofiles.hkust-gz.edu.cn/faculty-personal-page/XIONG-Hui/huixiong).
- *2021.09 - 2025.07*, B.Eng. in Computer Science and Technology, School of Information Science and Engineering, [Lanzhou University](https://www.lzu.edu.cn/).
