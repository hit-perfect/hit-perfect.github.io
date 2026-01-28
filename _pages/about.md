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

<!-- I am now conducting ra work in <img src="images/UST.png" alt="HKUST(gz) Logo" style="height:1.25em; vertical-align:middle;">Hong Kong University of Science and Technology (Guangzhou), following <a href='https://www.yingcong.me/'>Chen Yingcong（陈颖聪）</a>

As a primary learner in the field of AI, I am now engaged in the research direction of video generation, and intend to make further research in the direction of controllable video generation.

I studied in the School of Computer Science and Technology of Harbin Institute of Technology<img src="images/HIT-大蓝.png" alt="HIT-Logo" style="height:1.8em; vertical-align:middle;"> as an undergraduate. I will get my bachelor's degree in Computer Science and technology in July this year(I hope so, this is a damn story). My undergraduate advisor was <a href='https://homepage.hit.edu.cn/liushaohui'>Liu Shaohui（刘绍辉）.</a>

After that, I will be enrolled as a mphil student in hkust in the fall of 2025. under the guidance of <a href='https://www.yingcong.me/'>Chen Yingcong（陈颖聪）</a>, I will continue to study in the field of generation, and I hope to obtain deeper atabilities. -->

I am currently an M.Phil. student in the AI Thrust at <img src="images/UST.png" alt="HKUST(gz) Logo" style="height:1.25em; vertical-align:middle;">HKUST(GZ). My supervisor is <a href='https://www.yingcong.me/'>Prof. Yingcong Chen</a>, a super nice mentor.

Before that, I received my Bachelor’s degree in Computer Science and Technology from the School of Computer Science and Technology, <img src="images/HIT-大蓝.png" alt="HIT-Logo" style="height:2em; vertical-align:middle;">Harbin Institute of Technology, under the supervision of <a href='https://homepage.hit.edu.cn/liushaohui'>Prof. Shaohui Liu</a>, who has been tremendously supportive.

At present, I am working closely with <a href='https://wileewang.github.io/'>Luozhou Wang</a> and <a href='https://dbbpaul.github.io/'>Guibao Shen</a>, both of whom are very kind and supportive. My current research focuses on controllable generation, and I aim to make rapid progress and contributions in this area.

😍😍😍Please feel free to contact with me via *duyihua0130@gmail.com*😍😍😍

<!-- My research interest includes neural machine translation and computer vision. I have published more than 100 papers at the top international AI conferences with total <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'>google scholar citations <strong><span id='total_cit'>260000+</span></strong></a> (You can also use google scholar badge <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>). -->


# 🔥 News
- *2026.01*: &nbsp;🔥 We Release the [Project Page](https://github.com/hit-perfect/Awesome-Video-World-Models), [Paper](https://arxiv.org/abs/2601.17067) of our Video-World-Models survey.
- *2025.12*: &nbsp;🎉 StereoPilot was reported by [JiQiZhiXin](https://mp.weixin.qq.com/s/uQ9ygMrFVujnkbZbObKHqA).
- *2025.12*: &nbsp;❤️ We Release [Project Page](https://hit-perfect.github.io/StereoPilot/), [Code](https://github.com/KlingTeam/StereoPilot), [Paper](https://arxiv.org/abs/2512.16915) of StereoPilot.
- *2025.12*: &nbsp;❤️ We Release [Project Page](https://hit-perfect.github.io/VideoMemory/), [Paper](https://arxiv.org/abs/2601.03655) of VideoMemory.
- *2025.12*: &nbsp;🏎️ See you at the 2026 Formula 1 Chinese Grand Prix in Shanghai!!!
- *2025.03*: &nbsp;🎉 One paper on IQA led by senior Li Yu was accepted by ICME. 

# 📝 Publications

*denotes equal contribution, <sup>†</sup> denotes corresponding author

<!-- 第一个 -->
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Arxiv 2025</div><img src='images/StereoPilot/parallel_vs_converged.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[StereoPilot: Learning Unified and Efficient Stereo Conversion via Generative Priors](https://arxiv.org/abs/2512.16915)

Guibao Shen<sup>*</sup>, **Yihua Du**<sup>*</sup>, Wenhang Ge<sup>*</sup>, Jing He, Chirui Chang, Donghao Zhou, Zhen Yang, Luozhou Wang, Xin Tao, Ying-Cong Chen<sup>†</sup>

<span class="link-block">
<span class="icon"><i class="fas fa-home"></i></span>
<a href="https://hit-perfect.github.io/StereoPilot/" class="external-link button is-normal is-rounded is-dark" target="_blank">
<!-- <span class="icon"><i class="fas fa-home"></i></span> -->
<span>Project Page</span>
</a>
</span> | <span class="link-block">
<span class="icon"><i class="fab fa-github"></i></span>
<a href="https://github.com/KlingTeam/StereoPilot" class="external-link button is-normal is-rounded is-dark" target="_blank">
<span>Code</span>
</a>
</span> | <span class="link-block">
<span class="icon">🤗</span>
<a href="https://huggingface.co/papers/2512.16915" class="external-link button is-normal is-rounded is-dark" target="_blank">
<span>Daily Paper</span>
</a>
</span> | <span class="link-block">
<span class="icon">📰</span>
<a href="https://mp.weixin.qq.com/s/uQ9ygMrFVujnkbZbObKHqA" class="external-link button is-normal is-rounded is-dark" target="_blank">
<span>机器之心</span>
</a>
</span> | <span class="link-block">
<span class="icon"><i class="ai ai-arxiv"></i></span>
<a href="https://arxiv.org/abs/2512.16915" class="external-link button is-normal is-rounded is-dark" target="_blank">
<span>arXiv</span>
</a>
<!-- </span> -->

- Converting a 5-second monocular video into a stereoscopic video takes only 11 seconds. Built both parallel and converged 3D dataset.
<!-- - This is the workshop activity done at nus. It was the first time that I finished and deployed artificial intelligence algorithms and combined them with hardware. -->
</div>
</div>


<!-- 第二个 -->
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Arxiv 2026</div><img src='images/VideoMemory/Teaser.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[VideoMemory: Toward Consistent Video Generation via Memory Integration](https://arxiv.org/abs/2601.03655)

Jinsong Zhou<sup>*</sup>, **Yihua Du**<sup>*</sup>, Xinli Xu<sup>*</sup>, Luozhou Wang, Zijie Zhuang, Yehang Zhang, Shuaibo Li, Xiaojun Hu, Bolan Su, Ying-Cong Chen<sup>†</sup>

<span class="link-block">
<span class="icon"><i class="fas fa-home"></i></span>
<a href="https://hit-perfect.github.io/VideoMemory/" class="external-link button is-normal is-rounded is-dark" target="_blank">
<!-- <span class="icon"><i class="fas fa-home"></i></span> -->
<span>Project Page</span>
</a>
</span> | <span class="link-block">
<span class="icon"><i class="ai ai-arxiv"></i></span>
<a href="https://arxiv.org/abs/2601.03655" class="external-link button is-normal is-rounded is-dark" target="_blank">
<span>arXiv</span>
</a>
<!-- </span> | <span class="link-block">
<span class="icon"><i class="fab fa-github"></i></span>
<a href="https://github.com/KlingTeam/StereoPilot" class="external-link button is-normal is-rounded is-dark" target="_blank">
<span>Code</span>
</a> -->
<!-- </span> | <span class="link-block">
<span class="icon">🤗</span>
<a href="https://huggingface.co/papers/2512.16915" class="external-link button is-normal is-rounded is-dark" target="_blank">
<span>Daily Paper</span>
</a>
</span> | <span class="link-block">
<span class="icon">📰</span>
<a href="https://mp.weixin.qq.com/s/uQ9ygMrFVujnkbZbObKHqA" class="external-link button is-normal is-rounded is-dark" target="_blank">
<span>机器之心</span>
</a> -->
<!-- </span> -->

- Propose an entity-centric, dynamic memory bank framework that enables coherent long-form, multi-shot narrative video generation by retrieving and updating character/prop/background states to preserve identity across temporal gaps.
<!-- - This is the workshop activity done at nus. It was the first time that I finished and deployed artificial intelligence algorithms and combined them with hardware. -->
</div>
</div>

<!-- Survey -->
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Arxiv 2026</div><img src='images/VideoWorldModel/VideoWorldModel_codepage.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[A Mechanistic View on Video Generation as World Models: State and Dynamics](https://arxiv.org/abs/2601.17067)

Luozhou Wang<sup>*</sup>, Zhifei Chen<sup>*</sup>, **Yihua Du**, Dongyu Yan, Wenhang Ge, Guibao Shen, Xinli Xu, Leyi Wu, Man Chen, Tianshuo Xu, Peiran Ren, Xin Tao, Pengfei Wan, Ying-Cong Chen<sup>†</sup>

<span class="link-block">
<span class="icon"><i class="fab fa-github"></i></span>
<a href="https://github.com/hit-perfect/Awesome-Video-World-Models" class="external-link button is-normal is-rounded is-dark" target="_blank">
<span>Code</span>
</a>
</span> | <span class="link-block">
<span class="icon">🤗</span>
<a href="https://huggingface.co/papers/2601.17067" class="external-link button is-normal is-rounded is-dark" target="_blank">
<span>Daily Paper</span>
</a>
</span> | <span class="link-block">
<span class="icon"><i class="ai ai-arxiv"></i></span>
<a href="https://arxiv.org/abs/2601.17067" class="external-link button is-normal is-rounded is-dark" target="_blank">
<span>arXiv</span>
</a>
<!-- </span> | <span class="link-block">
<span class="icon">📰</span>
<a href="https://mp.weixin.qq.com/s/uQ9ygMrFVujnkbZbObKHqA" class="external-link button is-normal is-rounded is-dark" target="_blank">
<span>机器之心</span>
</a> -->
<!-- </span> -->

- Bridge this divide: (1) Taxonomy: Unifying Implicit Context vs. Explicit Latent Compression (2) Evolution: Shifting benchmarks from "Visual Fidelity" to "Physical Persistence" and Causality.
<!-- - This is the workshop activity done at nus. It was the first time that I finished and deployed artificial intelligence algorithms and combined them with hardware. -->
</div>
</div>


<!-- 第二个 -->
<!-- <div class='paper-box'><div class='paper-box-image'><div><div class="badge">NUS Summer workshop 2023</div><img src='images/NUS_summer_workshop.png' alt="sym" width="100%" style="max-height: 300px; object-fit: contain;"></div></div>
<div class='paper-box-text' markdown="1">

[HaHa_go!helps you fight negative emotions](https://hit-perfect.github.io)

**Yihua Du**<sup>*</sup>, Yixuan Ding<sup>*</sup>, Youxin Zhu<sup>*</sup>, Ruoyan Luo<sup>*</sup>

<!-- [**Project**](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=DhtAFkwAAAAJ&citation_for_view=DhtAFkwAAAAJ:ALROH1vI_8AC) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong> -->
<!-- - This is the workshop activity done at nus. It was the first time that I finished and deployed artificial intelligence algorithms and combined them with hardware.
</div>
</div> -->

<!-- 第三个 -->
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Undergraduate Project</div><img src='images/bishe.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Liveness detection method based on multi-angle forensics](https://hit-perfect.github.io)

**Yihua Du**, Puchao Zhou, Yu Li, Shaohui Liu

<!-- [**Project**](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=DhtAFkwAAAAJ&citation_for_view=DhtAFkwAAAAJ:ALROH1vI_8AC) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong> -->
- This work is completed under the guidance of my undergraduate graduation supervisor and the laboratory senior. 
- Won the excellent innovation comprehensive graduation design
</div>
</div>

<!-- - [There is no Publications now, I hope this day will coming soon~~~](https://hit-perfect.github.io) **CVPR 2026** -->

# 🎖 Honors and Awards
- *2025.06* Liveness detection method based on multi-angle forensics. **Excellent and innovative comprehensive graduation design（卓越创新综合设计奖【哈尔滨工业大学本科生院颁发】）**
<!-- - *2024.11* HKUST RBM Postgraduate Scholarship. **240000 RMB**.  -->
- *2024.11* HKUST(GZ) RBM Postgraduate Scholarship. 
- *2024.11* The Sixth Global Campus Artificial Intelligence Algorithm Elite Competition. **The accuracy was second in the whole list and won the second prize in the nation（国家二等奖准确率榜单第二）**
- *2024.09* Virtual authoring Communication Community based on Diffusion Model. **National Innovation and Entrepreneurship（国家级大创）**
<!-- - *2024.04* The 17th National College Students Software Innovation Competition. **Second prize in Northeast Regional Competition（东北赛区前 20 名）**.   -->
<!-- - *2023.07* American College Student Mathematical Modeling Competition. **H Prize(美赛)**. -->
- *2022,2023* Excellent student of the school **（校优秀学生）**
- *2022.09* HIT third-class name Scholarship **（三等人民奖学金）**

# 📖 Educations
- *2021.08 - 2025.09*, <img src="images/HIT-大蓝.png" alt="HIT-Logo" style="height:2.15em; vertical-align:middle;"> Bachelor, Harbin Institute of Technology, Harbin. 
- *2023.07 - 2023.08*, <img src="images/nus-logo.jpg" alt="nus-Logo" style="height:1.7em; vertical-align:middle;"> Summer Camp student([Workshop](../images/NUS_summer_workshop.png)), National University of Singapore, Singapore. 
- *2025.09 - (now)*, <img src="images/hkust-logo.png" alt="hkust-Logo" style="height:1.7em; vertical-align:middle;"> M.Phil., Hong Kong University of Science and Technology (Guangzhou), Guangzhou.

# 💻 Internships
- *2026.01 - now*, [Tencent](https://join.qq.com/about.html)<img src="images/tencent_logo.png" alt="Tencent-Logo" style="height:0.8em; vertical-align:middle;">, IEG, Computer Vision, Shenzhen.
- *2025.02 - 2025.08*, [ENVISION Lab, HKUST(GZ)](https://envision-research.hkust-gz.edu.cn)<img src="images/hkust-logo.png" alt="hkust-Logo" style="height:1.7em; vertical-align:middle;">, Research Assistant, Guangzhou.
- *2024.03 - 2024.07*, [Meituan](https://www.meituan.com)<img src="images/meituan.png" alt="meituan-Logo" style="height:1.2em; vertical-align:middle;">, Algorithm strategy, Beijing.

<!-- # 💬 Invited Talks
- *2025.04*, Sorry, I'm just a little trash at the moment.  -->
<!-- - *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/) -->

<!-- # 💻 Internships
- *2019.05 - 2020.02*, [Lorem](https://github.com/), China. -->

# 📄 My Resume
<!-- - [English Resume / 英文简历](../images/Yihua_Du_CV.pdf) | [Chinese Resume / 中文简历](../images/杜壹华_20251216.pdf)  -->
- [English Resume](../images/CV/Yihua_Du_CV.pdf) / [中文简历](../images/CV/杜壹华_20251216.pdf).


# 🍭 Habits

- 🏸 Badminton is my absolute favorite! No matter what, I'll be there if you invite me to play!
- 🎮 I'm also a passionate CS:GO/CS2 enthusiast. [**Click here to watch my perfect moments!**](../cs2_highlights.html)

---

<p style="text-align: center; color: #888; font-size: 0.9em; margin-top: 2em;">
Last Updated: January 22 2026
</p>
