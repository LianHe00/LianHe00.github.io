---
permalink: /
title: "Lian He"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% include base_path %}

<div class="about-home" markdown="1">

I received my bachelor's degree in Computer Science and Technology from the School of Computer Science, Beijing Institute of Technology (BIT). Currently, I am a Ph.D. student in the combined master's–doctoral program at BIT, advised by **Prof. Gangyi Ding**. I am also conducting research at the Beijing Zhongguancun Academy, under the supervision of **Prof. Liqiang Nie** and **Prof. Meng Liu**. 

My research interests lie in embodied AI, affordance perception and spatial intelligence. Welcome for discussion and collaboration, feel free to drop me an email.

<h2 id="education">📖 Education</h2>

<ul class="education-list" markdown="0">
  <li>
    <div class="education-item__header">
      <span class="education-item__dates">2024.09 - Present</span>
      <span class="education-item__sep">|</span>
      <strong class="education-item__degree">Combined M.S.–Ph.D. in computer science and technology</strong>
    </div>
    <span class="education-item__org">Beijing Zhongguancun Academy</span>
  </li>
  <li>
    <div class="education-item__header">
      <span class="education-item__dates">2022.09 - Present</span>
      <span class="education-item__sep">|</span>
      <img class="education-item__logo" src="{{ base_path }}/images/logo.svg" alt="Beijing Institute of Technology" width="22" height="22" />
      <strong class="education-item__degree">Combined M.S.–Ph.D. in computer science and technology</strong>
    </div>
    <span class="education-item__org">School of Computer Science, Beijing Institute of Technology</span>
  </li>
  <li>
    <div class="education-item__header">
      <span class="education-item__dates">2018.09 - 2022.06</span>
      <span class="education-item__sep">|</span>
      <img class="education-item__logo" src="{{ base_path }}/images/logo.svg" alt="Beijing Institute of Technology" width="22" height="22" />
      <strong class="education-item__degree">B.S. in computer science and technology</strong>
    </div>
    <span class="education-item__org">School of Computer Science, Beijing Institute of Technology</span>
  </li>
</ul>

<h2 id="selected-projects">🚀 Selected Projects</h2>

<ul class="project-cards" markdown="0">
  <li class="project-card">
    <div class="project-card__media">
      <img src="{{ base_path }}/images/projects/Olympic.gif" alt="the Beijing 2022 Olympic Winter Games demo" loading="lazy" onerror="this.onerror=null;this.src='{{ base_path }}/images/projects/placeholder.svg';" />
    </div>
    <div class="project-card__body">
      <h3 class="project-card__title">Integrated Simulation System for Creation, Choreography and Performance of Beijing 2022 Olympic and Paralympic Winter Games</h3>
      <p class="project-card__desc">It builds an integrated full-process simulation system for the whole stage production process. Developed with Unreal Engine.</p>
    </div>
  </li>
  <li class="project-card">
    <div class="project-card__media">
      <img src="{{ base_path }}/images/projects/sanxingdui.gif" alt="Fantastic Journey to Sanxingdui demo" loading="lazy" onerror="this.onerror=null;this.src='{{ base_path }}/images/projects/placeholder.svg';" />
    </div>
    <div class="project-card__body">
      <h3 class="project-card__title">Fantastic Journey to Sanxingdui</h3>
      <p class="project-card__desc">The first immersive cloud interactive space enables instant travel back to the ancient Shu Kingdom 3,000 years ago for anytime, anywhere exploration. Developed with Unreal Engine.</p>
    </div>
  </li>
</ul>

<!-- Selected Projects 调用方式：在 _pages/about.md 的 project-cards 列表中复制 project-card 结构；左侧动图放在 images/projects/ 目录（支持 .gif）；替换 project-card__title 与 project-card__desc 即可 -->

<h2 id="publications">📝 Selected Publications</h2>

<ul class="pub-cards" markdown="0">
  <li class="pub-card">
    <div class="pub-card__media">
      <img src="{{ base_path }}/images/publications/tas3d-affordance.jpg" alt="Task-Aware 3D Affordance Segmentation" loading="lazy" onerror="this.onerror=null;this.src='{{ base_path }}/images/publications/placeholder.svg';" />
    </div>
    <div class="pub-card__body">
      <h3 class="pub-card__title">Task-Aware 3D Affordance Segmentation via 2D Guidance and Geometric Refinement</h3>
      <p class="pub-card__venue"><a href="https://arxiv.org/pdf/2511.11702" target="_blank" rel="noopener noreferrer">AAAI 2026</a></p>
      <p class="pub-card__authors"><strong>Lian He</strong>, Meng Liu, Qilang Ye, Yu Zhou, Xiang Deng, Gangyi Ding</p>
      <div class="pub-card__actions">
        <a class="pub-card__btn" href="https://arxiv.org/pdf/2511.11702" target="_blank" rel="noopener noreferrer">Paper</a>
        <a class="pub-card__btn" href="https://github.com/LianHe00/TASA-main" target="_blank" rel="noopener noreferrer">Code</a>
      </div>
    </div>
  </li>
  <li class="pub-card">
    <div class="pub-card__media">
      <img src="{{ base_path }}/images/publications/sugar.jpg" alt="SUGAR: Learning Skeleton Representation" loading="lazy" onerror="this.onerror=null;this.src='{{ base_path }}/images/publications/placeholder.svg';" />
    </div>
    <div class="pub-card__body">
      <h3 class="pub-card__title">SUGAR: Learning Skeleton Representation with Visual-Motion Knowledge for Action Recognition</h3>
      <p class="pub-card__venue"><a href="https://arxiv.org/pdf/2511.10091" target="_blank" rel="noopener noreferrer">AAAI 2026</a></p>
      <p class="pub-card__authors">Qilang Ye, Yu Zhou, <strong>Lian He</strong>, Jie Zhang, Xuanming Guo, Jiayu Zhang, Mingkui Tan, Weicheng Xie, Yue Sun, Tao Tan, Xiaochen Yuan, Ghada Khoriba, Zitong Yu</p>
      <div class="pub-card__actions">
        <a class="pub-card__btn" href="https://arxiv.org/pdf/2511.10091" target="_blank" rel="noopener noreferrer">Paper</a>
      </div>
    </div>
  </li>
  <li class="pub-card">
    <div class="pub-card__media">
      <img src="{{ base_path }}/images/publications/collective-mechanical-props.jpg" alt="Collective Mechanical Props Performance Behavior" loading="lazy" onerror="this.onerror=null;this.src='{{ base_path }}/images/publications/placeholder.svg';" />
    </div>
    <div class="pub-card__body">
      <h3 class="pub-card__title">Research on Modeling and Simulation of Collective Mechanical Props Performance Behavior</h3>
      <p class="pub-card__venue"><a href="https://dc-china-simulation.researchcommons.org/cgi/viewcontent.cgi?article=4491&amp;context=journal" target="_blank" rel="noopener noreferrer">China Simulation 2025</a></p>
      <p class="pub-card__authors"><strong>Lian He</strong>, Kexiang Huang, Dapeng Yan, Ruida Tang, Gangyi Ding</p>
      <div class="pub-card__actions">
        <a class="pub-card__btn" href="https://dc-china-simulation.researchcommons.org/cgi/viewcontent.cgi?article=4491&amp;context=journal" target="_blank" rel="noopener noreferrer">Paper</a>
      </div>
    </div>
  </li>
  <li class="pub-card">
    <div class="pub-card__media">
      <img src="{{ base_path }}/images/publications/social-force-varying-scenes.jpg" alt="Deep Learning Improved Social Force Model" loading="lazy" onerror="this.onerror=null;this.src='{{ base_path }}/images/publications/placeholder.svg';" />
    </div>
    <div class="pub-card__body">
      <h3 class="pub-card__title">Deep Learning Improved Social Force Model to Simulate Crowd in Varying Scenes</h3>
      <p class="pub-card__venue"><a href="https://ieeexplore.ieee.org/abstract/document/10548157/" target="_blank" rel="noopener noreferrer">ICAACE 2024</a></p>
      <p class="pub-card__authors">Dapeng Yan, Chongzhi Bai, <strong>Lian He</strong>, Gangyi Ding</p>
      <div class="pub-card__actions">
        <a class="pub-card__btn" href="https://ieeexplore.ieee.org/abstract/document/10548157/" target="_blank" rel="noopener noreferrer">Paper</a>
      </div>
    </div>
  </li>
  <li class="pub-card">
    <div class="pub-card__media">
      <img src="{{ base_path }}/images/publications/crowd-dynamics-mdpi.jpg" alt="Enhanced crowd dynamics simulation" loading="lazy" onerror="this.onerror=null;this.src='{{ base_path }}/images/publications/placeholder.svg';" />
    </div>
    <div class="pub-card__body">
      <h3 class="pub-card__title">Enhanced crowd dynamics simulation with deep learning and improved social force model</h3>
      <p class="pub-card__venue"><a href="https://www.mdpi.com/2079-9292/13/5/934" target="_blank" rel="noopener noreferrer">Electronics 2024</a></p>
      <p class="pub-card__authors">Dapeng Yan, Gangyi Ding, Kexiang Huang, Chongzhi Bai, <strong>Lian He</strong>, Longfei Zhang</p>
      <div class="pub-card__actions">
        <a class="pub-card__btn" href="https://www.mdpi.com/2079-9292/13/5/934" target="_blank" rel="noopener noreferrer">Paper</a>
      </div>
    </div>
  </li>
</ul>

<!-- Publications 调用方式：在 _pages/about.md 的 pub-cards 列表中复制 pub-card 结构；替换图片路径、标题、venue 链接、作者、摘要与 Paper/Code 按钮链接；缩略图放在 images/publications/ 目录下 -->

<h2 id="honors">🏆 Honors & Awards</h2>

**Grants**

* Young Talent Support Program for Doctoral Students, 2026, CAST. (**中国科协青年人才托举工程博士生专项计划**)
* China International College Students' Innovation Competition 2023, the silver medal.
* The 18th  "Challenge Cup" National College Student Curricular Academic Science and Technology Works Competition, the third prize.
* Participation Certificate in GUINNESS WORLD RECORDS.


**Scholarships**

* 2022-2023: Master's Academic Scholarship
* 2024-2025: Doctoral Academic Scholarship

</div>

