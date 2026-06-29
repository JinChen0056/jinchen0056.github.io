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

<style>
.language-switcher {
  display: flex;
  justify-content: flex-end;
  gap: 8px;
  margin: 0 0 1rem;
}

.language-switcher button {
  border: 1px solid #d5d5d5;
  background: #fff;
  color: #333;
  border-radius: 6px;
  cursor: pointer;
  font-size: 0.82rem;
  font-weight: 700;
  line-height: 1;
  padding: 8px 10px;
}

.language-switcher button.active {
  background: #333;
  border-color: #333;
  color: #fff;
}

.lang-panel[hidden] {
  display: none;
}

</style>

<div class="language-switcher" aria-label="Language switcher">
  <button type="button" class="active" data-lang-switch="en">English</button>
  <button type="button" data-lang-switch="zh">中文</button>
</div>

<div class="lang-panel lang-en" data-lang-panel="en" markdown="1">

I am a PhD student jointly affiliated with [Fudan University](https://www.fudan.edu.cn/) and the [Shanghai Innovation Institute](https://www.sii.edu.cn/), working at [OpenDriveLab](https://www.opendrivelab.com/) under the supervision of [Prof. Hongyang Li](https://lihongyang.info/).

My research interests center on **Humanoid Loco-Manipulation** and **Human Data Scaling**. Always happy to chat and exchange ideas — feel free to drop me an email.

# 🔥 News
- *2026.05*: &nbsp;🎉 **EgoHumanoid** is accepted by **RSS 2026** and fully open-sourced!
- *2026.02*: &nbsp;🎉 Joined **Tongyi Lab, Alibaba** as a Research Intern.
- *2026.02*: &nbsp;📢 Released **EgoHumanoid** on arXiv — a human-to-humanoid loco-manipulation transfer framework.
- *2026.01*: &nbsp;🎉 **WholeBodyVLA** is accepted by **ICLR 2026**!


# 🎬 Demos

<style>
.demo-grid {
  display: grid;
  grid-template-columns: repeat(2, minmax(0, 1fr));
  column-gap: 34px;
  row-gap: 30px;
  margin: 1rem auto 2rem;
  width: 90%;
  max-width: 960px;
}

.demo-item {
  display: block;
  width: 100%;
  margin: 0;
  padding: 10px;
  background: #fafafa;
  border: 1px solid #e8e8e8;
  border-radius: 8px;
  box-shadow: 0 8px 20px rgba(0, 0, 0, 0.06);
}

.demo-video {
  display: block;
  width: 100%;
  aspect-ratio: 16 / 9;
  background: #111;
  border-radius: 6px;
  border: 1px solid #ddd;
  object-fit: cover;
}

.demo-caption {
  display: block;
  flex: 0 0 100%;
  width: 100%;
  max-width: 100%;
  margin-bottom: 9px;
  color: #333;
  font-size: 1.02rem;
  font-weight: 700;
  line-height: 1.35;
  text-align: center !important;
}

.demo-caption::after {
  content: "";
  display: block;
  width: 32px;
  height: 2px;
  margin: 6px auto 0;
  background: #b9b9b9;
  border-radius: 2px;
}

@media (max-width: 640px) {
  .demo-grid {
    grid-template-columns: 1fr;
    width: 100%;
    max-width: 100%;
    row-gap: 22px;
  }

  .demo-item {
    padding: 8px;
  }
}
</style>

<div class="demo-grid">
  <figure class="demo-item">
    <figcaption class="demo-caption">Throwing Trash</figcaption>
    <video class="demo-video" controls muted playsinline preload="metadata" poster="images/demos/throw-trash.jpg">
      <source src="images/demos/throw-trash.mp4" type="video/mp4">
    </video>
  </figure>
  <figure class="demo-item">
    <figcaption class="demo-caption">Pushing Chair</figcaption>
    <video class="demo-video" controls muted playsinline preload="metadata" poster="images/demos/push-chair.jpg">
      <source src="images/demos/push-chair.mp4" type="video/mp4">
    </video>
  </figure>
  <figure class="demo-item">
    <figcaption class="demo-caption">Picking Plush Toy</figcaption>
    <video class="demo-video" controls muted playsinline preload="metadata" poster="images/demos/pick-plush.jpg">
      <source src="images/demos/pick-plush.mp4" type="video/mp4">
    </video>
  </figure>
  <figure class="demo-item">
    <figcaption class="demo-caption">Closing Laptop</figcaption>
    <video class="demo-video" controls muted playsinline preload="metadata" poster="images/demos/close-laptop.jpg">
      <source src="images/demos/close-laptop.mp4" type="video/mp4">
    </video>
  </figure>
</div>


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

*IROS 2025 Competition*, **Tech Lead**

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

</div>

<div class="lang-panel lang-zh" data-lang-panel="zh" markdown="1" hidden>

我是[复旦大学](https://www.fudan.edu.cn/)与[上海创智学院](https://www.sii.edu.cn/)联合培养博士生，目前在 [OpenDriveLab](https://www.opendrivelab.com/) 从事研究工作，导师为[李弘扬教授](https://lihongyang.info/)。

我的研究方向聚焦于**人形机器人移动操作**与**人类数据规模化**。欢迎通过邮件交流讨论。

# 🔥 最新动态
- *2026.05*: &nbsp;🎉 **EgoHumanoid** 被 **RSS 2026** 接收并完整开源。
- *2026.02*: &nbsp;🎉 加入**阿里巴巴通义实验室**担任研究实习生。
- *2026.02*: &nbsp;📢 **EgoHumanoid** 发布于 arXiv：一个基于人类第一视角演示的人形机器人移动操作迁移框架。
- *2026.01*: &nbsp;🎉 **WholeBodyVLA** 被 **ICLR 2026** 接收。


# 🎬 演示

<div class="demo-grid">
  <figure class="demo-item">
    <figcaption class="demo-caption">扔垃圾</figcaption>
    <video class="demo-video" controls muted playsinline preload="metadata" poster="images/demos/throw-trash.jpg">
      <source src="images/demos/throw-trash.mp4" type="video/mp4">
    </video>
  </figure>
  <figure class="demo-item">
    <figcaption class="demo-caption">推椅子</figcaption>
    <video class="demo-video" controls muted playsinline preload="metadata" poster="images/demos/push-chair.jpg">
      <source src="images/demos/push-chair.mp4" type="video/mp4">
    </video>
  </figure>
  <figure class="demo-item">
    <figcaption class="demo-caption">收玩偶</figcaption>
    <video class="demo-video" controls muted playsinline preload="metadata" poster="images/demos/pick-plush.jpg">
      <source src="images/demos/pick-plush.mp4" type="video/mp4">
    </video>
  </figure>
  <figure class="demo-item">
    <figcaption class="demo-caption">合上电脑</figcaption>
    <video class="demo-video" controls muted playsinline preload="metadata" poster="images/demos/close-laptop.jpg">
      <source src="images/demos/close-laptop.mp4" type="video/mp4">
    </video>
  </figure>
</div>


# 📝 代表性论文

<div class='paper-box'>
<div class='paper-box-image'><div><div class="badge">RSS 2026</div><img src='images/papers/egohumanoid.jpg' data-gif='images/papers/egohumanoid.gif' alt="EgoHumanoid" width="100%" class="lazy-gif"></div></div>
<div class='paper-box-text' markdown="1">

**[EgoHumanoid: Unlocking In-the-Wild Loco-Manipulation with Robot-Free Egocentric Demonstration](https://opendrivelab.com/EgoHumanoid/)**

Modi Shi<sup>\*</sup>, Shijia Peng<sup>\*</sup>, **Jin Chen**<sup>\*</sup>, Haoran Jiang, Yinghui Li, Di Huang, Ping Luo, Hongyang Li, Li Chen

*Robotics: Science and Systems (RSS)*, 2026

[**项目主页**](https://opendrivelab.com/EgoHumanoid/) \| [**GitHub**](https://github.com/OpenDriveLab/EgoHumanoid) \| [**arXiv**](https://arxiv.org/abs/2602.10106)

<sub><i>首个使用无机器人参与的第一视角人类视频训练，并可零样本部署到双足人形机器人上的框架。</i></sub>

</div>
</div>

<div class='paper-box'>
<div class='paper-box-image'><div><div class="badge">arXiv 2026</div><img src='images/papers/kai0.jpg' data-gif='images/papers/kai0.gif' alt="kai0" width="100%" class="lazy-gif"></div></div>
<div class='paper-box-text' markdown="1">

**[&chi;&#x2080;: Resource-Aware Robust Manipulation via Taming Distributional Inconsistencies](https://opendrivelab.com/kai0)**

Checheng Yu, Chonghao Sima, Gangcheng Jiang, Hai Zhang, Haoguang Mai, Hongyang Li, Huijie Wang, **Jin Chen**, Kaiyang Wu, Li Chen, Lirui Zhao, Modi Shi, Ping Luo, Qingwen Bu, Shijia Peng, Tianyu Li, Yibo Yuan &nbsp; <sub><i>作者按字母序排列</i></sub>

*arXiv preprint*, 2026

[**项目主页**](https://opendrivelab.com/kai0) \| [**GitHub**](https://github.com/OpenDriveLab/kai0) \| [**arXiv**](https://arxiv.org/abs/2602.09021)

<sub><i>面向双臂灵巧可变形物体操作的系统性研究与优化，支撑了首个 24 小时不间断叠衣直播。</i></sub>

</div>
</div>

<div class='paper-box'>
<div class='paper-box-image'><div><div class="badge">ICLR 2026</div><img src='images/papers/wholebodyvla.jpg' data-gif='images/papers/wholebodyvla.gif' alt="WholeBodyVLA" width="100%" class="lazy-gif"></div></div>
<div class='paper-box-text' markdown="1">

**[WholeBodyVLA: Towards Unified Latent VLA for Whole-Body Loco-Manipulation Control](https://opendrivelab.com/WholeBodyVLA/)**

Haoran Jiang<sup>\*</sup>, **Jin Chen**<sup>\*</sup>, Qingwen Bu, Li Chen, Modi Shi, Yanjie Zhang, Delong Li, Chuanzhe Suo, Chuang Wang, Zhihui Peng, Hongyang Li

*International Conference on Learning Representations (ICLR)*, 2026

[**项目主页**](https://opendrivelab.com/WholeBodyVLA/) \| [**GitHub**](https://github.com/OpenDriveLab/WholebodyVLA) \| [**arXiv**](https://arxiv.org/abs/2512.11047)

<sub><i>首个面向双足人形机器人全身移动操作控制的端到端 VLA 自主系统，并首次实现超过 1 分钟的自主移动操作。</i></sub>

</div>
</div>

<div class='paper-box'>
<div class='paper-box-image'><div><div class="badge">T-RO 2026</div><img src='images/papers/diversity.jpg' alt="diversity" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**[Is Diversity All You Need for Scalable Robotic Manipulation?](https://agibot-world.com/)**

Modi Shi<sup>\*</sup>, Li Chen<sup>\*</sup>, **Jin Chen**<sup>\*</sup>, Yuxiang Lu, Chiming Liu, Guanghui Ren, Ping Luo, Di Huang, Maoqing Yao, Hongyang Li

*IEEE Transactions on Robotics (T-RO)*, 2026

[**项目主页**](https://agibot-world.com/) \| [**GitHub**](https://github.com/OpenDriveLab/Agibot-World) \| [**arXiv**](https://arxiv.org/abs/2507.06219)

<sub><i>研究真实机器人数据多样性如何影响 VLA 基础模型性能扩展规律。</i></sub>

</div>
</div>


# 🎯 学术服务

<div class='paper-box'>
<div class='paper-box-image'><div><img src='images/papers/challenge.jpg' alt="challenge" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**[第一届 AgiBot World Challenge](https://agibot-world.com/challenge2025)**

*IROS 2025 Competition*, **技术负责人**

赛事包含 **Manipulation** 与 **World Model** 两个赛道，吸引全球 300+ 支队伍参与。负责基于 AgiBot World 平台构建真实机器人评测流程。

[**官网**](https://agibot-world.com/challenge2025)

</div>
</div>


# 💻 研究经历
- *2026.02 - 至今*, [阿里巴巴通义实验室](https://tongyi.aliyun.com/), 研究实习生。 <img src='images/logos/tongyi.svg' style='height:32px;vertical-align:middle;margin-left:6px'>
- *2025.12 - 2026.01*, [KAI（超维动力）](https://www.kinetixai.tech/), 研究实习生。 <img src='images/logos/kai.svg' style='height:20px;vertical-align:middle;margin-left:6px;filter:invert(1)'>
- *2025.05 - 2025.11*, [AgiBot（智元机器人）](https://www.agibot.com/), 研究实习生。 <img src='images/logos/agibot.png' style='height:32px;vertical-align:middle;margin-left:6px'>
- *2024.10 - 2025.04*, [上海人工智能实验室](https://www.shlab.org.cn/), 研究实习生。 <img src='images/logos/shlab.png' style='height:26px;vertical-align:middle;margin-left:6px'>
- *2023.09 - 2024.09*, [中国电信人工智能研究院](https://www.teleai.com.cn/), 研究实习生。 <img src='images/logos/teleai.png' style='height:32px;vertical-align:middle;margin-left:6px'>


# 📖 教育经历
- *2025.09 - 至今*, 博士，复旦大学与上海创智学院。
- *2022.09 - 2025.06*, 硕士，数学，西安交通大学。
- *2018.09 - 2022.06*, 学士，数学与应用数学，中国矿业大学。

</div>

<script>
function setHomepageLanguage(lang) {
  var targetLang = lang === 'zh' ? 'zh' : 'en';
  document.querySelectorAll('[data-lang-panel]').forEach(function(panel) {
    panel.hidden = panel.getAttribute('data-lang-panel') !== targetLang;
  });
  document.querySelectorAll('[data-lang-switch]').forEach(function(button) {
    button.classList.toggle('active', button.getAttribute('data-lang-switch') === targetLang);
  });
  document.documentElement.lang = targetLang === 'zh' ? 'zh-CN' : 'en';
  updateAuthorProfileLanguage(targetLang);
  try {
    window.localStorage.setItem('homepageLanguage', targetLang);
  } catch (error) {}
}

function setAuthorLinkText(selector, text) {
  document.querySelectorAll(selector).forEach(function(link) {
    var icon = link.querySelector('i');
    link.textContent = "";
    if (icon) {
      link.appendChild(icon);
      link.appendChild(document.createTextNode(" " + text));
    } else {
      link.textContent = text;
    }
  });
}

function updateAuthorProfileLanguage(lang) {
  var content = lang === 'zh' ? {
    name: "陈金 | 别名：西星",
    bio: "复旦大学与上海创智学院博士生 | OpenDriveLab at HKU",
    location: "杭州，中国",
    email: "邮箱",
    github: "GitHub",
    scholar: "谷歌学术"
  } : {
    name: "Jin Chen | Alias: Xixing",
    bio: "PhD student at Fudan University and SII | OpenDriveLab at HKU",
    location: "Hangzhou, China",
    email: "Email",
    github: "Github",
    scholar: "Google Scholar"
  };

  var authorName = document.querySelector(".author__name");
  var authorBio = document.querySelector(".author__bio");
  var authorLocationIcon = document.querySelector(".author__urls .fa-map-marker");
  if (authorName) authorName.textContent = content.name;
  if (authorBio) authorBio.textContent = content.bio;
  if (authorLocationIcon && authorLocationIcon.parentElement) {
    authorLocationIcon.parentElement.innerHTML = '<i class="fa fa-fw fa-map-marker" aria-hidden="true"></i> ' + content.location;
  }

  setAuthorLinkText('.author__urls a[href^="mailto:"]', content.email);
  setAuthorLinkText('.author__urls a[href^="https://github.com/"]', content.github);
  setAuthorLinkText('.author__urls a[href^="https://scholar.google.com/"]', content.scholar);
}

document.querySelectorAll('[data-lang-switch]').forEach(function(button) {
  button.addEventListener('click', function() {
    setHomepageLanguage(button.getAttribute('data-lang-switch'));
  });
});

try {
  setHomepageLanguage(window.localStorage.getItem('homepageLanguage') || 'en');
} catch (error) {
  setHomepageLanguage('en');
}

document.querySelectorAll('img.lazy-gif').forEach(function(img) {
  var gif = new Image();
  gif.onload = function() { img.src = gif.src; };
  gif.src = img.getAttribute('data-gif');
});
</script>
