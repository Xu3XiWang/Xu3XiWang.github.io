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

Hi 👋! I’m Zhicheng Wang (王志诚), currently an Algorithm Researcher at ByteDance. My current work aims to develop general-purpose image search and question-answering systems on Douyin, as well as foundational technologies for general video understanding. In particular, I focus on MLLM-based embedding models, Video LLMs, and scalable multi-modal representation learning. Douyin multi-modal search has become one of the largest real-world application scenarios for multi-modal technologies.

Before joining ByteDance, I was a research intern at Alibaba’s Pailitao, one of the largest e-commerce visual search scenarios in China, where I explored large-scale post-training methods for MLLM-based representations in e-commerce search systems.

I received both my Master’s and Bachelor’s degrees from Huazhong University of Science and Technology, supervised by Prof. Zhiguo Cao. My academic research mainly focused on Open-World Object Localization & Counting, MLLM Representation, and Video LLM.

I’m always open to new collaborations, so please feel free to get in touch 🙋!



# 🔥 News
- *2026.02*: &nbsp;🎉🎉 we are releasing [Pailitao-VL](https://arxiv.org/pdf/2602.13704), a unified embedding and reranker for real-time multi-modal industrial search.
- *2025.11*: &nbsp;🎉🎉 we are releasing [PDF-VLM2Vec](https://arxiv.org/abs/2511.01588), a efficient training framework for MLLM embedding models.
- *2025.11*: &nbsp;🎉🎉 [IPFormer-VideoLLM](https://arxiv.org/abs/2506.21116) is accepted to **AAAI26**.
- *2025.07*: &nbsp;🎉🎉 [SRefiner](https://arxiv.org/abs/2507.04263) is accepted to **ICCV25**.
- *2025.06*: &nbsp;🎉🎉 we are releasing [IPFormer-VideoLLM](https://arxiv.org/abs/2506.21116), a Video-LLM designed for multi-scene video understanding.
- *2025.04*: &nbsp;🎉🎉 [DAM](https://www.sciencedirect.com/science/article/pii/S0031320325005801) is accepted to **Pattern Recognition**.
- *2025.03*: &nbsp;🎉🎉 [CAD-GD](https://arxiv.org/abs/2503.12460v1) is accepted to **CVPR25**.
- *2023.12*: &nbsp;🎉🎉 [CACViT](https://arxiv.org/abs/2305.04440) is accepted to **AAAI24**.

# 📝 Publications 
(\* denotes corresponding author.)
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Arixv 26.01</div><img src='images/embedding-pipeline.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**[Tech Report]**[Pailitao-VL: Unified Embedding and Reranker for Real-Time Multi-Modal Industrial Search] \\
Pailitao Team **(Core contributor)** \\
[[Paper]](https://arxiv.org/pdf/2602.13704)
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Arixv 25.09</div><img src='images/iclr26.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">


**[Arxiv 25.11]**[Explore More, Learn Better: Parallel MLLM Embeddings under Mutual Information Minimization] \\
**Zhicheng Wang**, Chen Ju, Xu Chen, Shuai Xiao, Jinsong Lan, Xiaoyong Zhu, Zhiguo Cao \\
[[Paper]](https://arxiv.org/abs/2511.01588)
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2025</div><img src='images/cvpr25.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
  
**[CVPR 2025]**[Exploring Semantic Density for Referring Expression Counting](https://arxiv.org/abs/2503.12460v1) \\
**Zhicheng Wang**, Zhiyu Pan, Liwen Xiao, Zhan Peng, Jian Cheng, Wei Jiang, Shuaiyuan Du, Zhiguo Cao \\
[[Paper]](https://arxiv.org/abs/2503.12460v1)
[[Code]](https://github.com/Xu3XiWang/CAD-GD)

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">AAAI 2024</div><img src='images/aaai24.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**[AAAI 2024]**[Vision Transformer Off-the-Shelf: A Surprising Baseline for Few-Shot Class-Agnostic Counting](https://arxiv.org/abs/2305.04440) \\
**Zhicheng Wang**, Liwen Xiao, Zhiguo Cao, Hao Lu \\
[[Paper]](https://arxiv.org/abs/2305.04440)
[[Code]](https://github.com/Xu3XiWang/CACViT-AAAI24)

</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">AAAI 2026</div><img src='images/arxiv.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
  
**[AAAI 2026]**[IPFormer-VideoLLM: Enhancing Multi-modal Video Understanding for Multi-shot Scenes](https://arxiv.org/abs/2506.21116) \\
Yujia Liang, Jile Jiao, Xuetao Feng, Zixuan Ye, Yuan Wang, **Zhicheng Wang**\* \\
[[Paper]](https://arxiv.org/abs/2506.21116)

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICCV 2025 highlight</div><img src='images/iccv25.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**[ICCV 2025 Highlight]**[SRefiner: Soft-Braid Attention for Multi-Agent Trajectory Refinement](https://arxiv.org/abs/2507.04263) \\
Liwen Xiao, Zhiyu Pan, **Zhicheng Wang**, Zhiguo Cao, Wei Li \\
[[Paper]](https://arxiv.org/abs/2507.04263)
[[Code]](https://github.com/Liwen-Xiao/SRefiner)

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">PR</div><img src='images/pr.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**[PR]**[Densely Activated Self-Attention for Semantic Segmentation](https://www.sciencedirect.com/science/article/pii/S0031320325005801) \\
Liwen Xiao, Wenze Liu, **Zhicheng Wang**, Zhiyu Pan, Yiran Wang, Zhiguo Cao, Hao Lu \\
[[Paper]](https://www.sciencedirect.com/science/article/pii/S0031320325005801) 


</div>
</div>

# 🎖 Honors and Awards
- *2026* Top Talent Program by Technology Companies (Ant Group AntStar Talent Program)
- *2025* National Scholarship (1%)
- *2024* The Lead Intelligent and Wang Yanqing Scholarship (先导智能·王燕清奖学金)，
- *2024* Weichai Power Scholarship (“潍柴动力”奖学金)
- *2023* Outstanding graduates
- *2021* Merit Student
- *2020* Outstanding Undergraduate Student (Top 1%)

# 💻 Internships
- *2026.03 - Present*, ByteDance, Data, Multimodal Search.
- *2025.02 - 2025.12*, Alibaba, Future Living Lab, Pailitao(拍立淘).
- *2024.07 - 2024.12*, Shanghai AI Lab.
- *2024.06 - 2025.02*, Worked on project “Camera Image Fusion and Reconstruction” with Huawei.
