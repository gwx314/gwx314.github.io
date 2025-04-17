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

I am a PhD student at [the College of Computer Science and Technology](http://www.en.cs.zju.edu.cn/), [Zhejiang University](https://www.zju.edu.cn/english/) (浙江大学计算机学院).

I graduated from Zhejiang University. I am now working on the Audio Research Team at Zhejiang University, under the supervision of [Prof. Zhou Zhao (赵洲)](https://person.zju.edu.cn/zhaozhou). My current research focuses on singing voice generation and spatial audio generation.

My research interests include **Singing Voice Synthesis, Music Generation, Audio Generation, and other topics related to Natural Language Processing**. I have published papers at the top international AI conference NeurIPS.

**I am actively seeking postdoctoral positions and research collaborations. Please feel free to contact me via email at guowx314@zju.edu.cn.**

# 🔥 News
- *2024.12* 🎉 1 paper is accepted by AAAI!
- *2024.09* 🎉 GTSinger is accepted by NeurIPS 2024(spotlight)!
- *2024.09* 🎉 Frieren is accepted by NeurIPS 2024!

# 📝 Publications 

## 🎙 Singing Voice Synthesis

<div class='paper-box'>
    <div class='paper-box-image'>
        <div>
            <div class="badge">NeurIPS 2024 Spotlight</div>
            <img src='../../images/gtsinger.png' alt="sym" width="100%"></div>
        </div>
        <div class='paper-box-text' markdown="1">

[GTSinger: A Global Multi-Technique Singing Corpus with Realistic Music Scores for All Singing Tasks](https://arxiv.org/abs/2409.13832) \\
Yu Zhang, Changhao Pan, **Wenxinag Guo**, et al.

[**Project**](https://gtsinger.github.io) \| [![](https://img.shields.io/github/stars/GTSinger/GTSinger?style=social&label=GTSinger+Stars)](https://github.com/GTSinger/GTSinger) [![Hugging Face](https://img.shields.io/badge/%F0%9F%A4%97%20Hugging%20Face-blue?label=Dataset)](https://huggingface.co/datasets/GTSinger/GTSinger) 

- GTSinger is a large Global, multi-Technique, free-to-use, high-quality singing corpus with realistic music scores, designed for all singing tasks.
- Our work is promoted by multiple media and forums, such as [![weixin](https://img.shields.io/badge/-WeChat@机器之心-000000?logo=wechat&logoColor=07C160)](https://mp.weixin.qq.com/s/B1Iqr-24l57f0MslzYEslA), and [![zhihu](https://img.shields.io/badge/-知乎-000000?logo=zhihu&logoColor=0084FF)](https://zhuanlan.zhihu.com/p/993933492).
</div>
</div>

## 🎼 Audio Generation 

- `NeurIPS 2024` [Frieren: Efficient Video-to-Audio Generation Network with Rectified Flow Matching](https://arxiv.org/abs/2406.00320), Yongqi Wang, **Wenxiang Guo**, et al.
- ``AAAI-2025`` [TechSinger: Technique Controllable Multilingual Singing Voice Synthesis via Flow Matching](https://arxiv.org/abs/2502.12572), **Wenxiang Guo**, Yu Zhang, Changhao Pan, et. al. 
# 🎖 Honors and Awards


# 📖 Educations
- *2023.09 - 2028.06 (Expected)*, PhD, Computer Science, College of Computer Science and Technology, Zhejiang University, Hangzhou, Zhejiang
- *2019.09 - 2023.06*, Undergraduate, Computer Science, Zhejiang University, Hangzhou, Zhejiang

# 💻 Research and Internships
- *2022.10-Now* Research Assisant in Audio Research Team at Zhejiang University <img src='../../images/zju.png' style='width: 6em;'>. Advisor: [Prof. Zhou Zhao (赵洲)](https://person.zju.edu.cn/zhaozhou).
