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

<section class="home-hero">
  <p class="eyebrow">Multimodal Search · MLLM Representation · Video Understanding</p>
  <h1>Zhicheng Wang <span>王志诚</span></h1>
  <p class="hero-lead">I build large-scale multimodal systems for real-world search and question answering, with a focus on MLLM-based embeddings, Video LLMs, and scalable representation learning.</p>
  <p class="hero-links">
    <a href="#publications">Publications</a>
    <span class="sep">·</span>
    <a href="https://scholar.google.com/citations?user=d6qLT28AAAAJ">Google Scholar</a>
    <span class="sep">·</span>
    <a href="https://github.com/Xu3XiWang">GitHub</a>
    <span class="sep">·</span>
    <a href="mailto:zhicheng_wang@hust.edu.cn">Email</a>
  </p>
</section>

<section class="about-intro" markdown="1">
I am currently an Algorithm Researcher at ByteDance, where I work on general-purpose image search and question-answering systems on Douyin, as well as foundational technologies for general video understanding. My research focuses on MLLM-based embedding models, Video LLMs, and scalable multi-modal representation learning. Before joining ByteDance, I was a research intern at Alibaba Pailitao, one of the largest e-commerce visual search scenarios in China, where I explored large-scale post-training methods for MLLM-based representations in industrial search systems. I received both my Master's and Bachelor's degrees from Huazhong University of Science and Technology, supervised by Prof. Zhiguo Cao. I am always open to collaborations on multimodal retrieval, representation learning, open-world localization and counting, and video-language understanding.
</section>

# News
<div class="news-list" markdown="1">
- *2026.08* Released (Douyin Multimodal Embedding Model Technical Report)[https://arxiv.org/abs/2608.02148], an efficient and powerful MLLM embedding model that achieves SOTA performance on the [MMEBv2](https://huggingface.co/spaces/TIGER-Lab/MMEB-Leaderboard) leaderboard.
- *2026.02* Released [Pailitao-VL](https://arxiv.org/pdf/2602.13704), a unified embedding and reranker for real-time multi-modal industrial search.
- *2025.11* Released [PDF-VLM2Vec](https://arxiv.org/abs/2511.01588), an efficient training framework for MLLM embedding models.
- *2025.11* [IPFormer-VideoLLM](https://arxiv.org/abs/2506.21116) was accepted to **AAAI 2026**.
- *2025.07* [SRefiner](https://arxiv.org/abs/2507.04263) was accepted to **ICCV 2025** and selected as a **Highlight**.
- *2025.06* Released [IPFormer-VideoLLM](https://arxiv.org/abs/2506.21116), a Video LLM designed for multi-scene video understanding.
- *2025.04* [DAM](https://www.sciencedirect.com/science/article/pii/S0031320325005801) was accepted to **Pattern Recognition**.
- *2025.03* [CAD-GD](https://arxiv.org/abs/2503.12460v1) was accepted to **CVPR 2025**.
- *2023.12* [CACViT](https://arxiv.org/abs/2305.04440) was accepted to **AAAI 2024**.
</div>

# Publications
<span class='anchor' id='publications'></span>
(\* denotes corresponding author.)
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Tech Report</div><img src='images/dme-embedding-pipeline.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

<span class="venue-tag">Tech Report</span> **Douyin Multimodal Embedding Model Technical Report** \\
Douyin Search Multimodal Team **(Co-First, Core contributor)** \\
[[Paper]](https://arxiv.org/abs/2608.02148)
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Tech Report</div><img src='images/embedding-pipeline.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

<span class="venue-tag">Tech Report</span> **Pailitao-VL: Unified Embedding and Reranker for Real-Time Multi-Modal Industrial Search** \\
Pailitao Team **(Core contributor)** \\
[[Paper]](https://arxiv.org/pdf/2602.13704)
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Arxiv 25.11</div><img src='images/iclr26.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">


<span class="venue-tag">Arxiv 25.11</span> **Explore More, Learn Better: Parallel MLLM Embeddings under Mutual Information Minimization** \\
**Zhicheng Wang**, Chen Ju, Xu Chen, Shuai Xiao, Jinsong Lan, Xiaoyong Zhu, Zhiguo Cao \\
[[Paper]](https://arxiv.org/abs/2511.01588)
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2025</div><img src='images/cvpr25.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
  
<span class="venue-tag">CVPR 2025</span> [**Exploring Semantic Density for Referring Expression Counting**](https://arxiv.org/abs/2503.12460v1) \\
**Zhicheng Wang**, Zhiyu Pan, Liwen Xiao, Zhan Peng, Jian Cheng, Wei Jiang, Shuaiyuan Du, Zhiguo Cao \\
[[Paper]](https://arxiv.org/abs/2503.12460v1)
[[Code]](https://github.com/Xu3XiWang/CAD-GD)

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">AAAI 2024</div><img src='images/aaai24.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

<span class="venue-tag">AAAI 2024</span> [**Vision Transformer Off-the-Shelf: A Surprising Baseline for Few-Shot Class-Agnostic Counting**](https://arxiv.org/abs/2305.04440) \\
**Zhicheng Wang**, Liwen Xiao, Zhiguo Cao, Hao Lu \\
[[Paper]](https://arxiv.org/abs/2305.04440)
[[Code]](https://github.com/Xu3XiWang/CACViT-AAAI24)

</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">AAAI 2026</div><img src='images/arxiv.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
  
<span class="venue-tag">AAAI 2026</span> [**IPFormer-VideoLLM: Enhancing Multi-modal Video Understanding for Multi-shot Scenes**](https://arxiv.org/abs/2506.21116) \\
Yujia Liang, Jile Jiao, Xuetao Feng, Zixuan Ye, Yuan Wang, **Zhicheng Wang**\* \\
[[Paper]](https://arxiv.org/abs/2506.21116)

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICCV 2025 highlight</div><img src='images/iccv25.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

<span class="venue-tag venue-tag--highlight">ICCV 2025 Highlight</span> [**SRefiner: Soft-Braid Attention for Multi-Agent Trajectory Refinement**](https://arxiv.org/abs/2507.04263) \\
Liwen Xiao, Zhiyu Pan, **Zhicheng Wang**, Zhiguo Cao, Wei Li \\
[[Paper]](https://arxiv.org/abs/2507.04263)
[[Code]](https://github.com/Liwen-Xiao/SRefiner)

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">PR</div><img src='images/pr.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

<span class="venue-tag">PR</span> [**Densely Activated Self-Attention for Semantic Segmentation**](https://www.sciencedirect.com/science/article/pii/S0031320325005801) \\
Liwen Xiao, Wenze Liu, **Zhicheng Wang**, Zhiyu Pan, Yiran Wang, Zhiguo Cao, Hao Lu \\
[[Paper]](https://www.sciencedirect.com/science/article/pii/S0031320325005801) 


</div>
</div>

# Honors and Awards
- *2026* Top Talent Program by Technology Companies (Ant Group AntStar Talent Program)
- *2025* National Scholarship (1%)
- *2024* The Lead Intelligent and Wang Yanqing Scholarship (先导智能·王燕清奖学金)，
- *2024* Weichai Power Scholarship (“潍柴动力”奖学金)
- *2023* Outstanding graduates
- *2021* Merit Student
- *2020* Outstanding Undergraduate Student (Top 1%)

# Internships
- *2026.03 - 2026.06*, ByteDance, Data, Multimodal Search.
- *2025.02 - 2025.12*, Alibaba, Future Living Lab, Pailitao(拍立淘).
- *2024.07 - 2024.12*, Shanghai AI Lab.
- *2024.06 - 2025.02*, Worked on project “Camera Image Fusion and Reconstruction” with Huawei.
