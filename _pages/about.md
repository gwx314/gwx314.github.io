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

I graduated from Zhejiang University. I am now working on the Audio Research Team at Zhejiang University, under the supervision of [Prof. Zhou Zhao (赵洲)](https://person.zju.edu.cn/zhaozhou) and [Prof. Fei Wu (吴飞)](https://person.zju.edu.cn/wufei). My current research focuses on singing voice generation and spatial audio generation.

My research interests include **Singing Voice Synthesis, Music Generation, Audio Generation, and other topics related to Natural Language Processing**. I have published papers at the top international AI conference NeurIPS.

**I am actively seeking postdoctoral positions and research collaborations. Please feel free to contact me via email at guowx314@zju.edu.cn.**

# 🔥 News
- *2025.07* 🎉 2 paper are accepted by ACM-MM 2025!
- *2025.05* 🎉 2 paper are accepted by ACL 2025!
- *2024.12* 🎉 1 paper is accepted by AAAI 2025!
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

- `AAAI 2025` [TechSinger: Technique Controllable Multilingual Singing Voice Synthesis via Flow Matching](https://arxiv.org/abs/2502.12572), **Wenxiang Guo**, Yu Zhang, Changhao Pan, et al. \| [**Project**](https://tech-singer.github.io/) \| [![](https://img.shields.io/github/stars/gwx314/TechSinger?style=social&label=TechSinger+Stars)](https://github.com/gwx314/TechSinger)

- `ACL 2025` [STARS: A Unified Framework for Singing Transcription, Alignment, and Refined Style Annotation](https://arxiv.org/abs/2507.06670), **Wenxiang Guo**, Yu Zhang, Changhao Pan, et al. ｜ [**Project**](https://demo-stars.github.io/) \| [![](https://img.shields.io/github/stars/gwx314/STARS?style=social&label=STARS+Stars)](https://github.com/gwx314/STARS)

- `ACL 2025` [TCSinger 2: Customizable Multilingual Zero-shot Singing Voice Synthesis](https://arxiv.org/abs/2505.14910), Yu Zhang, **Wenxiang Guo**, Changhao Pan, et al.

## 🎼 Audio Generation 

- `NeurIPS 2024` [Frieren: Efficient Video-to-Audio Generation Network with Rectified Flow Matching](https://arxiv.org/abs/2406.00320), Yongqi Wang, **Wenxiang Guo**, et al.

- `ACMMM 2025` [ISDrama: Immersive Spatial Drama Generation through Multimodal Prompting](https://arxiv.org/abs/2504.20630), Yu Zhang, **Wenxiang Guo**, Changhao Pan, et al.

- ``ACMMM 2025`` [A Multimodal Evaluation Framework for Spatial Audio Playback Systems: From Localization to Listener Preference](), Changhao Pan, **Wenxiang Guo**, Yu Zhang, et al. 

# 📖 Educations
- *2023.09 - 2028.06 (Expected)*, PhD, Computer Science, College of Computer Science and Technology, Zhejiang University, Hangzhou, Zhejiang
- *2019.09 - 2023.06*, Undergraduate, Computer Science, Zhejiang University, Hangzhou, Zhejiang

# 💻 Research and Internships
- *2022.10-Now* Research Assisant in Audio Research Team at Zhejiang University <img src='../../images/zju.png' style='width: 6em;'>. Advisor: [Prof. Zhou Zhao (赵洲)](https://person.zju.edu.cn/zhaozhou).
