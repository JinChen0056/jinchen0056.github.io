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

I am a PhD student jointly affiliated with [Fudan University](https://www.fudan.edu.cn/) and the [Shanghai Innovation Institute](https://www.sii.edu.cn/), working at [OpenDriveLab](https://www.opendrivelab.com/) under the supervision of [Prof. Hongyang Li](https://lihongyang.info/).

My research interests center on **Humanoid Loco-Manipulation** and **Human Data Scaling**. Always happy to chat and exchange ideas — feel free to drop me an email.


# 🔥 News
- *2026.05*: &nbsp;🎉 **EgoHumanoid** is accepted by **RSS 2026** and fully open-sourced!
- *2026.02*: &nbsp;🎉 Joined **Tongyi Lab, Alibaba** as a Research Intern.
- *2026.02*: &nbsp;📢 Released **EgoHumanoid** on arXiv — a human-to-humanoid loco-manipulation transfer framework.
- *2026.01*: &nbsp;🎉 **WholeBodyVLA** is accepted by **ICLR 2026**!


# 📝 Selected Publications

<div class='paper-box'>
<div class='paper-box-image'><div><div class="badge">RSS 2026</div><img src='images/papers/egohumanoid.jpg' data-gif='images/papers/egohumanoid.gif' alt="sym" width="100%" class="lazy-gif"></div></div>
<div class='paper-box-text' markdown="1">

**[EgoHumanoid: Unlocking In-the-Wild Loco-Manipulation with Robot-Free Egocentric Demonstration](https://opendrivelab.com/EgoHumanoid/)**

Modi Shi<sup>\*</sup>, Shijia Peng<sup>\*</sup>, **Jin Chen**<sup>\*</sup>, Haoran Jiang, Yinghui Li, Di Huang, Ping Luo, Hongyang Li, Li Chen

*Robotics: Science and Systems (RSS)*, 2026

[**Project**](https://opendrivelab.com/EgoHumanoid/) \| [**GitHub**](https://github.com/OpenDriveLab/EgoHumanoid) \| [**arXiv**](https://arxiv.org/abs/2602.10106)

<sub><i>The first framework that trains on robot-free egocentric human videos and zero-shot deploys on bipedal humanoid robots.</i></sub>

</div>
</div>

<div class='paper-box'>
<div class='paper-box-image'><div><div class="badge">arXiv 2026</div><img src='images/papers/kai0.jpg' data-gif='images/papers/kai0.gif' alt="sym" width="100%" class="lazy-gif"></div></div>
<div class='paper-box-text' markdown="1">

**[&chi;&#x2080;: Resource-Aware Robust Manipulation via Taming Distributional Inconsistencies](https://opendrivelab.com/kai0)**

Checheng Yu, Chonghao Sima, Gangcheng Jiang, Hai Zhang, Haoguang Mai, Hongyang Li, Huijie Wang, **Jin Chen**, Kaiyang Wu, Li Chen, Lirui Zhao, Modi Shi, Ping Luo, Qingwen Bu, Shijia Peng, Tianyu Li, Yibo Yuan &nbsp; <sub><i>(authors listed alphabetically)</i></sub>

*arXiv preprint*, 2026

[**Project**](https://opendrivelab.com/kai0) \| [**GitHub**](https://github.com/OpenDriveLab/kai0) \| [**arXiv**](https://arxiv.org/abs/2602.09021)

<sub><i>A systematic study and optimization of dual-arm dexterous deformable-object manipulation; powered the first 24-hour non-stop laundry-folding livestream.</i></sub>

</div>
</div>

<div class='paper-box'>
<div class='paper-box-image'><div><div class="badge">ICLR 2026</div><img src='images/papers/wholebodyvla.jpg' data-gif='images/papers/wholebodyvla.gif' alt="sym" width="100%" class="lazy-gif"></div></div>
<div class='paper-box-text' markdown="1">

**[WholeBodyVLA: Towards Unified Latent VLA for Whole-Body Loco-Manipulation Control](https://opendrivelab.com/WholeBodyVLA/)**

Haoran Jiang<sup>\*</sup>, **Jin Chen**<sup>\*</sup>, Qingwen Bu, Li Chen, Modi Shi, Yanjie Zhang, Delong Li, Chuanzhe Suo, Chuang Wang, Zhihui Peng, Hongyang Li

*International Conference on Learning Representations (ICLR)*, 2026

[**Project**](https://opendrivelab.com/WholeBodyVLA/) \| [**GitHub**](https://github.com/OpenDriveLab/WholebodyVLA) \| [**arXiv**](https://arxiv.org/abs/2512.11047)

<sub><i>The first end-to-end VLA autonomy stack for bipedal humanoids, and the first to sustain over 1 minute of autonomous loco-manipulation on a bipedal humanoid.</i></sub>

</div>
</div>

<div class='paper-box'>
<div class='paper-box-image'><div><div class="badge">T-RO 2026</div><img src='images/papers/diversity.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**[Is Diversity All You Need for Scalable Robotic Manipulation?](https://agibot-world.com/)**

Modi Shi<sup>\*</sup>, Li Chen<sup>\*</sup>, **Jin Chen**<sup>\*</sup>, Yuxiang Lu, Chiming Liu, Guanghui Ren, Ping Luo, Di Huang, Maoqing Yao, Hongyang Li

*IEEE Transactions on Robotics (T-RO)*, 2026

[**Project**](https://agibot-world.com/) \| [**GitHub**](https://github.com/OpenDriveLab/Agibot-World) \| [**arXiv**](https://arxiv.org/abs/2507.06219)

<sub><i>A scaling-law study of how VLA foundation model performance scales with real-robot data diversity.</i></sub>

</div>
</div>


# 🎯 Academic Services

<div class='paper-box'>
<div class='paper-box-image'><div><img src='images/papers/challenge.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**[The 1st AgiBot World Challenge](https://agibot-world.com/challenge2025)**

*IROS 2025 Competition*, Tech Lead

Two tracks — **Manipulation** and **World Model** — attracting 300+ teams worldwide. Built on the AgiBot World platform with real-robot evaluation pipelines.

[**Website**](https://agibot-world.com/challenge2025)

</div>
</div>


# 💻 Research Experience
- *2026.02 - Present*, [Tongyi Lab, Alibaba (通义实验室)](https://tongyi.aliyun.com/), Research Intern. <img src='images/logos/tongyi.svg' style='height:32px;vertical-align:middle;margin-left:6px'>
- *2025.12 - 2026.01*, [KAI (超维动力)](https://www.kinetixai.tech/), Research Intern. <img src='images/logos/kai.svg' style='height:20px;vertical-align:middle;margin-left:6px;filter:invert(1)'>
- *2025.05 - 2025.11*, [AgiBot (智元机器人)](https://www.agibot.com/), Research Intern. <img src='images/logos/agibot.png' style='height:32px;vertical-align:middle;margin-left:6px'>
- *2024.10 - 2025.04*, [Shanghai AI Laboratory (上海人工智能实验室)](https://www.shlab.org.cn/), Research Intern. <img src='images/logos/shlab.png' style='height:26px;vertical-align:middle;margin-left:6px'>
- *2023.09 - 2024.09*, [TeleAI (中国电信人工智能研究院)](https://www.teleai.com.cn/), Research Intern. <img src='images/logos/teleai.png' style='height:32px;vertical-align:middle;margin-left:6px'>


# 📖 Educations
- *2025.09 - Present*, Ph.D., Fudan University and Shanghai Innovation Institute.
- *2022.09 - 2025.06*, M.S. in Mathematics, Xi'an Jiaotong University.
- *2018.09 - 2022.06*, B.S. in Mathematics and Applied Mathematics, China University of Mining and Technology.

<script>
document.querySelectorAll('img.lazy-gif').forEach(function(img) {
  var gif = new Image();
  gif.onload = function() { img.src = gif.src; };
  gif.src = img.getAttribute('data-gif');
});
</script>
