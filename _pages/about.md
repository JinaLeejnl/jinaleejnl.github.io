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

I am currently a Ph.D. student at the Gaoling School of Artificial Intelligence (GSAI), Renmin University of China, advised by [Prof. Chongxuan Li](https://zhenxuan00.github.io/). I am expected to receive my Ph.D. degree in 2029. Before that, I received my B.S. degree from Southeast University (SEU) in 2024, where I was advised by [Prof. Yuheng Jia](https://jyh-learning.github.io/).

My current research interests span LLM pre-training, large language diffusion models, and efficient LLM inference.

# 🔥 News
- *Apr 2026*: &nbsp;🎉🎉 Paper “[AlignX](https://arxiv.org/abs/2503.15463)” accepted to ACL 2026 Main.
- *Jan 2026*: &nbsp;🎉🎉 Paper “[ReFusion](https://arxiv.org/abs/2512.13586)” accepted to ICLR 2026.

# 📝 Publications 

<div class='paper-box' style="width: 100%; max-width: none; display: grid; grid-template-columns: 30% minmax(0, 1fr); column-gap: 2rem; align-items: center; box-sizing: border-box;">
  <div class='paper-box-image' style="width: 100%; max-width: none;">
    <div>
      <div class="badge">ICLR 2026</div>
      <img src='https://raw.githubusercontent.com/ML-GSAI/ReFusion/main/images/refusion_visualization.gif'
           alt="ReFusion"
           style="width: 100%; height: auto; display: block;">
    </div>
  </div>

  <div class='paper-box-text' markdown="1" style="width: 100%; max-width: none; min-width: 0;">

[**ReFusion: A Diffusion Large Language Model with Parallel Autoregressive Decoding**](https://arxiv.org/abs/2512.13586) <img src='https://img.shields.io/github/stars/ML-GSAI/ReFusion.svg?style=social&label=Star' alt="GitHub stars">

**Jia-Nan Li**, Jian Guan, Wei Wu, Chongxuan Li

- **Full KV Cache Reuse:** The first MDM with full KV cache reuse for every decoded token.
- **Stronger and Faster:** 34% average performance gain over LLaDA/Dream with over 18× higher decoding throughput, and 2.33× faster than Qwen3-8B on average.

<div style="display: inline">
    <a href="https://arxiv.org/abs/2512.13586"><strong>[paper]</strong></a>
    <a href="https://github.com/ML-GSAI/ReFusion"><strong>[code]</strong></a>
    <a href="https://huggingface.co/GSAI-ML/ReFusion"><strong>[model]</strong></a>
</div>

  </div>
</div>

<ul>
  <li>
    <strong> 2D-TPE: Two-Dimensional Positional Encoding Enhances Table Understanding for Large Language Models. WWW 2025. </strong>
    <div style="display: inline">
        <a href="https://arxiv.org/abs/2409.19700"> <strong>[paper]</strong></a>
        <a href="https://github.com/JinaLeejnl/2D-TPE"> <strong>[code]</strong></a>
    </div>
    <div><i><strong>Jia-Nan Li</strong>, Jian Guan, Wei Wu, Zhengtao Yu, Rui Yan. </i></div>
  </li>
  
  <li>
    <strong> StreamingDialogue: Prolonged Dialogue Learning via Long Context Compression with Minimal Losses. NeurIPS 2024. </strong>
    <div style="display: inline">
        <a href="https://www.proceedings.com/079017-2733.html"> <strong>[paper]</strong></a>
        <a href="https://github.com/JinaLeejnl/StreamingDialogue"> <strong>[code]</strong></a>
    </div>
    <div><i><strong>Jia-Nan Li</strong>, Quan Tu, Cunli Mao, Zhengtao Yu, Ji-Rong Wen, Rui Yan. </i></div>
  </li>

  <li>
   <strong> From 1,000,000 Users to Every User: Scaling Up Personalized Preference for User-level Alignment. ACL 2026 main. </strong>
    <div style="display: inline">
        <a href="https://arxiv.org/abs/2503.15463"> <strong>[paper]</strong></a>
        <a href="https://github.com/JinaLeejnl/AlignX"> <strong>[code]</strong></a>
        <a href="https://huggingface.co/datasets/JinaLeejnl/AlignX"> <strong>[dataset]</strong></a>
    </div>
    <div><i><strong>Jia-Nan Li</strong>, Jian Guan, Songhao Wu, Wei Wu, Rui Yan. </i></div>
  </li>  

  <li>
   <strong> A Survey on Personalized Alignment—The Missing Piece for Large Language Models in Real-World Applications. ACL 2025 Findings. </strong>
    <div style="display: inline">
        <a href="https://aclanthology.org/2025.findings-acl.277/"> <strong>[paper]</strong></a>
    </div>
    <div><i>Jian Guan*, Junfei Wu*, <strong>Jia-Nan Li*</strong>, Chuanqi Cheng*, Wei Wu.</i></div>
  </li>  

  <li>
   <strong> Extended Inductive Reasoning for Personalized Preference Inference from Behavioral Signals. Preprint. </strong>
    <div style="display: inline">
        <a href="https://arxiv.org/abs/2505.18071"> <strong>[paper]</strong></a>
        <a href="https://github.com/AntResearchNLP/AlignXplore"> <strong>[code]</strong></a>
        <a href="https://huggingface.co/JinaLeejnl/AlignXplore-7B-Streaming"> <strong>[model]</strong></a>
    </div>
    <div><i><strong>Jia-Nan Li</strong>, Jian Guan, Wei Wu, Rui Yan. </i></div>
  </li>  
  
</ul>

<!--
# 🎖 Honors and Awards
- *2021.10* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.09* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 

# 📖 Educations
- *2019.06 - 2022.04 (now)*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2015.09 - 2019.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 

# 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/)
-->

# 💻 Internships
- *2025.10 - Present*, Diffusion LLM (dLLM) Pre-training Team, Ant Group.
- *2024.03 - 2025.09*, Research Intern, Natural Language Processing Lab, Ant Group. Mentor: [Wei Wu](https://sites.google.com/view/wei-wu-homepage/home).
