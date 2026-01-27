---
permalink: /
title: "Welcome to Tieyuan Chen's Homepage"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<style>
/* 全局样式优化 */
.research-tag {
    background-color: #f3f6f9;
    color: #0d6efd;
    border: 1px solid #dce4ec;
    border-radius: 4px;
    padding: 2px 8px;
    font-size: 0.9em;
    font-weight: 500;
    margin-right: 5px;
    display: inline-block;
}

.pub-card {
    display: flex;
    flex-wrap: wrap;
    gap: 20px;
    margin-bottom: 30px;
    padding-bottom: 20px;
    border-bottom: 1px solid #eee;
}

.pub-img {
    flex: 0 0 220px; /* 固定图片宽度 */
    width: 220px;
}

.pub-img img {
    width: 100%;
    border-radius: 8px;
    box-shadow: 0 4px 6px rgba(0,0,0,0.1);
    transition: transform 0.2s;
}

.pub-img img:hover {
    transform: scale(1.02);
}

.pub-content {
    flex: 1;
    min-width: 300px;
}

.pub-title {
    font-weight: bold;
    font-size: 1.1em;
    color: #333;
    margin-bottom: 5px;
}

.pub-venue {
    color: #c0392b; /* 会议名称颜色 */
    font-weight: bold;
    font-style: italic;
    margin-bottom: 5px;
    display: block;
}

.pub-authors {
    color: #555;
    font-size: 0.95em;
    margin-bottom: 8px;
    line-height: 1.5;
}

.pub-links {
    margin-top: 8px;
}

/* 移动端适配 */
@media (max-width: 768px) {
    .pub-card { display: block; }
    .pub-img { width: 100%; margin-bottom: 15px; }
}
</style>

Hello! I am **Tieyuan Chen (陈铁元)**. 

I am currently a second-year Ph.D. student (2023-present) at [Shanghai Jiao Tong University (SJTU)](https://en.sjtu.edu.cn/), affiliated with [SEIEE](https://english.seiee.sjtu.edu.cn/), under the supervision of Prof. [Weiyao Lin](https://weiyaolin.github.io/). 

Previously, I obtained my Bachelor's degree from [Sichuan University](https://en.scu.edu.cn/) (2019-2023), [CEIE](https://eie.scu.edu.cn/eneieen/), where I ranked **1st/29**. I am also a Research Intern at **Beijing Zhongguancun Academy** and **Alibaba AntGroup**.

**Research Interests:**
<div style="margin-top: 5px;">
<span class="research-tag">Video Understanding</span>
<span class="research-tag">LLMs & MLLMs</span>
<span class="research-tag">Video Reasoning</span>
</div>

<br>
If you are interested in my research or potential collaborations, please feel free to [contact me](mailto:tieyuanchen@sjtu.edu.cn).

---

## 🥇 Honors and Awards

*   **2021**: China National Scholarship (**Top 1%**)
*   **2022**: China National Scholarship (**Top 1%**)
*   **2022**: Sichuan University Comprehensive Special Scholarship (**Top 1‰**)
*   **2022**: Sichuan University Hundred Excellent Student (**Top 2‰**)
*   **2023**: Sichuan Province Outstanding Graduate (**Top 3%**)

---

## 📃 First Author Publications

<!-- Paper 1: NeurIPS 2024 -->
<div class="pub-card">
  <div class="pub-img">
    <img src="main_mecd.png" alt="MECD">
  </div>
  <div class="pub-content">
    <div class="pub-title">MECD: Unlocking Multi-Event Causal Discovery in Video Reasoning</div>
    <span class="pub-venue">NeurIPS 2024 (Spotlight, Top 2.4%)</span>
    <div class="pub-authors">
      <strong>Tieyuan Chen</strong>, Huabin Liu, Tianyao He, Yihang Chen, Chaofan Gan, Xiao Ma, Cheng Zhong, Yang Zhang, Yingxue Wang, Hui Lin, Weiyao Lin
    </div>
    <div class="pub-links">
      <a href="https://github.com/tychen-SJTU/MECD-Benchmark"><img src="https://img.shields.io/badge/-Github-black?logo=github" alt="github"></a>
      <a href="https://arxiv.org/abs/2409.17647"><img src="https://img.shields.io/badge/Arxiv-2409.17647-b31b1b.svg?logo=arXiv" alt="arxiv"></a>
    </div>
  </div>
</div>

<!-- Paper 2: ICLR 2026 -->
<div class="pub-card">
  <div class="pub-img">
    <img src="main_dnd.png" alt="DND">
  </div>
  <div class="pub-content">
    <div class="pub-title">DND: Boosting Large Language Models with Dynamic Nested Depth</div>
    <span class="pub-venue">ICLR 2026</span>
    <div class="pub-authors">
      <strong>Tieyuan Chen</strong>, Xiaodong Chen, Haoxing Chen, Zhenzhong Lan, Weiyao Lin, Jianguo Li
    </div>
    <div class="pub-links">
      <a href="https://arxiv.org/abs/2510.11001"><img src="https://img.shields.io/badge/Arxiv-2510.11001-b31b1b.svg?logo=arXiv" alt="arxiv"></a>
    </div>
  </div>
</div>

<!-- Paper 3: T-PAMI -->
<div class="pub-card">
  <div class="pub-img">
    <img src="main_mecd2.png" alt="MECD+">
  </div>
  <div class="pub-content">
    <div class="pub-title">MECD+: Unlocking Event-Level Causal Graph Discovery for Video Reasoning</div>
    <span class="pub-venue">IEEE Transactions on Pattern Analysis and Machine Intelligence (T-PAMI)</span>
    <div class="pub-authors">
      <strong>Tieyuan Chen</strong>, Huabin Liu, Yi Wang, Yihang Chen, Tianyao He, Chaofan Gan, Huanyu He, Weiyao Lin
    </div>
    <div class="pub-links">
      <a href="https://github.com/tychen-SJTU/MECD-Benchmark"><img src="https://img.shields.io/badge/-Github-black?logo=github" alt="github"></a>
      <a href="https://arxiv.org/abs/2501.07227"><img src="https://img.shields.io/badge/Arxiv-2501.07227-b31b1b.svg?logo=arXiv" alt="arxiv"></a>
    </div>
  </div>
</div>

<!-- Paper 4: T-CSVT -->
<div class="pub-card">
  <div class="pub-img">
    <img src="main_csta.png" alt="CSTA">
  </div>
  <div class="pub-content">
    <div class="pub-title">CSTA: Spatial-Temporal Causal Adaptive Learning for Exemplar-Free Video Class-Incremental Learning</div>
    <span class="pub-venue">IEEE Transactions on Circuits and Systems for Video Technology (T-CSVT)</span>
    <div class="pub-authors">
      <strong>Tieyuan Chen</strong>, Huabin Liu, Chern Hong Lim, John See, Xing Gao, Junhui Hou, Weiyao Lin
    </div>
    <div class="pub-links">
      <a href="https://github.com/tychen-SJTU/CSTA"><img src="https://img.shields.io/badge/-Github-black?logo=github" alt="github"></a>
      <a href="https://arxiv.org/abs/2501.07236"><img src="https://img.shields.io/badge/Arxiv-2501.07236-b31b1b.svg?logo=arXiv" alt="arxiv"></a>
    </div>
  </div>
</div>

---

## 📊 Academic Service

**Conference Reviewer**
*   **2026**: ICLR, CVPR, ECCV, ICML, ICME
*   **2025**: ICLR, CVPR, ICCV, NeurIPS, AAAI, ICME, PRCV

**Journal Reviewer**
*   Journal of Visual Communication and Image Representation (JVCI)
*   Signal Processing: Image Communication (SPIC)