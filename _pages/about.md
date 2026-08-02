---
permalink: /
title: "Xiaoyang Liu"
description: "Xiaoyang Liu is a PhD student at Shanghai Jiao Tong University working on autoformalization, AI for mathematics, and verifiable code generation."
excerpt: "Research in large language models, formal verification, and AI for mathematics."
author_profile: false
redirect_from:
  - /about/
  - /about.html
---

<section class="profile-hero" id="about" aria-labelledby="profile-title">
  <div class="profile-hero__content">
    <h1 id="profile-title">Xiaoyang Liu <span lang="zh-CN">刘晓洋</span></h1>
    <nav class="profile-links" aria-label="Profile links">
      <a href="mailto:xiaoyang.liu@sjtu.edu.cn"><i class="fas fa-envelope" aria-hidden="true"></i>Email</a>
      <a href="https://scholar.google.com/citations?user=BKTfL-gAAAAJ" target="_blank" rel="noopener noreferrer"><i class="fas fa-graduation-cap" aria-hidden="true"></i>Google Scholar</a>
      <a href="https://github.com/XiaoyangLiu-sjtu" target="_blank" rel="noopener noreferrer"><i class="fab fa-github" aria-hidden="true"></i>GitHub</a>
    </nav>
    <p class="profile-hero__statement">I am a second-year PhD candidate advised by <a href="https://math.sjtu.edu.cn/Default/teachershow/tags/MDAwMDAwMDAwMLKIet0" target="_blank" rel="noopener noreferrer">Prof. Tao Luo</a> at <a href="https://math.sjtu.edu.cn/Default/index/" target="_blank" rel="noopener noreferrer">School of Mathematical Sciences</a>, <a href="https://www.sjtu.edu.cn/" target="_blank" rel="noopener noreferrer">Shanghai Jiao Tong University (SJTU)</a>.</p>
    <p class="availability">I have started an internship at the Wizard Intelligence Learning Lab (WILL) as a post-training researcher.</p>
  </div>
  <figure class="profile-hero__portrait">
    <img src="/images/profile-photo.jpg" alt="Portrait of Xiaoyang Liu" width="2122" height="2484">
  </figure>
</section>

<section class="home-section research-section" id="research" aria-labelledby="research-title">
  <div class="section-heading">
    <p class="section-index">01</p>
    <h2 id="research-title">Research</h2>
  </div>
  <div class="section-content">
    <p class="research-keywords">LLMs · Lean · AI4Math · Verifiable Code Generation</p>
    <p class="section-lead">I develop verifiable AI systems that bridge informal reasoning and formal verification. My research addresses the core challenges of trustworthy reasoning through scalable autoformalization, faithful evaluation and diagnosis, and rigorous adversarial testing.</p>
    <div class="research-areas">
      <article>
        <h3>Autoformalization</h3>
        <p>Bootstrapping autoformalization through scalable data synthesis in <strong>ATLAS</strong> and structural operator-tree refinement in <strong>DSR</strong>.</p>
      </article>
      <article>
        <h3>Evaluation &amp; Diagnosis</h3>
        <p>Building faithful structural-semantic metrics with <strong>ASSESS</strong> and white-box diagnostic models with <strong>FormalRx</strong>.</p>
      </article>
      <article>
        <h3>Specification Testing</h3>
        <p>Scaling adversarial test suites with <strong>VeriScale</strong> to rigorously assess the soundness and completeness of formal specifications.</p>
      </article>
    </div>
  </div>
</section>

<section class="home-section" id="publications" aria-labelledby="publications-title">
  <div class="section-heading">
    <p class="section-index">02</p>
    <h2 id="publications-title">Publications</h2>
  </div>
  <div class="section-content">
    <p class="publication-note"><strong>*</strong> Equal contribution. <strong>†</strong> Corresponding author.</p>

    <article class="publication">
      <div class="publication__body">
        <p class="publication__venue">ICML 2026 · AI4Math Workshop</p>
        <h3><a href="https://arxiv.org/abs/2605.22368v1" target="_blank" rel="noopener noreferrer">VeriScale: Adversarial Test-Suite Scaling for Verifiable Code Generation</a></h3>
        <p class="publication__authors">Yifan Bai<sup>*</sup>, <strong>Xiaoyang Liu<sup>*</sup></strong>, Zihao Mou, Guihong Wang, Jian Yu, Shuhan Xie, Yantao Li, Yangyu Zhang, Jingwei Liang<sup>†</sup>, Tao Luo<sup>†</sup></p>
        <p class="publication__summary">An adversarial framework that expands and reduces test suites to expose unsound or incomplete formal specifications in verifiable code generation.</p>
        <p class="publication__links"><a href="https://arxiv.org/pdf/2605.22368v1" target="_blank" rel="noopener noreferrer">PDF</a><a href="https://arxiv.org/abs/2605.22368v1" target="_blank" rel="noopener noreferrer">arXiv</a><a href="https://github.com/XiaoyangLiu-sjtu/VeriScale" target="_blank" rel="noopener noreferrer">GitHub</a></p>
      </div>
    </article>

    <article class="publication">
      <div class="publication__body">
        <p class="publication__venue">ICML 2026</p>
        <h3><a href="https://arxiv.org/abs/2604.19000" target="_blank" rel="noopener noreferrer">Decompose, Structure, and Repair: A Neuro-Symbolic Framework for Autoformalization via Operator Trees</a></h3>
        <p class="publication__authors"><strong>Xiaoyang Liu</strong>, Zineng Dong, Yifan Bai, Yantao Li, Yuntian Liu, Tao Luo<sup>†</sup></p>
        <p class="publication__summary">A neuro-symbolic framework that structures autoformalization with operator trees and repairs failed Lean outputs.</p>
        <p class="publication__links"><a href="https://arxiv.org/pdf/2604.19000" target="_blank" rel="noopener noreferrer">PDF</a><a href="https://arxiv.org/abs/2604.19000" target="_blank" rel="noopener noreferrer">arXiv</a><a href="https://github.com/XiaoyangLiu-sjtu/DSR" target="_blank" rel="noopener noreferrer">GitHub</a></p>
      </div>
    </article>

    <article class="publication">
      <div class="publication__body">
        <p class="publication__venue">ICML 2026</p>
        <h3><a href="https://arxiv.org/abs/2607.04655" target="_blank" rel="noopener noreferrer">FormalRx: Rectify and eXamine Semantic Failures in Autoformalization</a></h3>
        <p class="publication__authors">Haocheng Wang<sup>*</sup>, Baiyu Huang<sup>*</sup>, Yingjia Wan<sup>*</sup>, Xiao Zhu, <strong>Xiaoyang Liu</strong>, Yinya Huang<sup>†</sup>, Zhijiang Guo<sup>†</sup></p>
        <p class="publication__summary">A framework for detecting, examining, and rectifying semantic failures in autoformalized statements.</p>
        <p class="publication__links"><a href="https://arxiv.org/pdf/2607.04655" target="_blank" rel="noopener noreferrer">PDF</a><a href="https://arxiv.org/abs/2607.04655" target="_blank" rel="noopener noreferrer">arXiv</a></p>
      </div>
    </article>

    <article class="publication">
      <div class="publication__body">
        <p class="publication__venue">ICLR 2026</p>
        <h3><a href="https://arxiv.org/abs/2509.22246" target="_blank" rel="noopener noreferrer">ASSESS: A Semantic and Structural Evaluation Framework for Statement Similarity</a></h3>
        <p class="publication__authors"><strong>Xiaoyang Liu<sup>*</sup></strong>, Tao Zhu<sup>*</sup>, Zineng Dong, Yuntian Liu, Qingfeng Guo, Zhaoxuan Liu, Yu Chen, Tao Luo<sup>†</sup></p>
        <p class="publication__summary">An evaluation framework that combines semantic and structural signals to compare formal statements.</p>
        <p class="publication__links"><a href="https://arxiv.org/pdf/2509.22246" target="_blank" rel="noopener noreferrer">PDF</a><a href="https://arxiv.org/abs/2509.22246" target="_blank" rel="noopener noreferrer">arXiv</a><a href="https://github.com/XiaoyangLiu-sjtu/ASSESS" target="_blank" rel="noopener noreferrer">GitHub</a></p>
      </div>
    </article>

    <article class="publication">
      <div class="publication__body">
        <p class="publication__venue">NeurIPS 2025</p>
        <h3><a href="https://arxiv.org/abs/2502.05567" target="_blank" rel="noopener noreferrer">ATLAS: Autoformalizing Theorems through Lifting, Augmentation, and Synthesis of Data</a></h3>
        <p class="publication__authors"><strong>Xiaoyang Liu</strong>, Kangjie Bao, Jiashuo Zhang, Yunqi Liu, Yu Chen, Yuntian Liu, Yang Jiao<sup>†</sup>, Tao Luo<sup>†</sup></p>
        <p class="publication__summary">A data-centric approach to theorem autoformalization through lifting, augmentation, and synthesis.</p>
        <p class="publication__links"><a href="https://arxiv.org/pdf/2502.05567" target="_blank" rel="noopener noreferrer">PDF</a><a href="https://arxiv.org/abs/2502.05567" target="_blank" rel="noopener noreferrer">arXiv</a><a href="https://github.com/XiaoyangLiu-sjtu/ATLAS" target="_blank" rel="noopener noreferrer">GitHub</a></p>
      </div>
    </article>

    <article class="publication">
      <div class="publication__body">
        <p class="publication__venue">ICML 2025 · AI4Math Workshop</p>
        <h3><a href="https://arxiv.org/abs/2507.07399" target="_blank" rel="noopener noreferrer">Generalized Tree Edit Distance (GTED): A Faithful Evaluation Metric for Statement Autoformalization</a></h3>
        <p class="publication__authors">Yuntian Liu<sup>*</sup>, Tao Zhu<sup>*</sup>, <strong>Xiaoyang Liu<sup>*</sup></strong>, Yu Chen, Zhaoxuan Liu, Qingfeng Guo, Jiashuo Zhang, Kangjie Bao, Tao Luo<sup>†</sup></p>
        <p class="publication__summary">A tree-edit-distance metric designed to evaluate the structure and meaning of autoformalized statements.</p>
        <p class="publication__links"><a href="https://arxiv.org/pdf/2507.07399" target="_blank" rel="noopener noreferrer">PDF</a><a href="https://arxiv.org/abs/2507.07399" target="_blank" rel="noopener noreferrer">arXiv</a><a href="https://github.com/XiaoyangLiu-sjtu/GTED" target="_blank" rel="noopener noreferrer">GitHub</a></p>
      </div>
    </article>
  </div>
</section>

<div class="biography-grid">
  <section class="home-section home-section--compact" id="talks" aria-labelledby="talks-title">
    <div class="section-heading">
      <p class="section-index">03</p>
      <h2 id="talks-title">Invited Talks</h2>
    </div>
    <div class="section-content">
      <ol class="timeline-list">
        <li><time datetime="2026-07">Jul 2026</time><p>AI4Math Workshop, Zhejiang University<br><span>Hangzhou, China</span></p></li>
        <li><time datetime="2025-08">Aug 2025</time><p>CSML, Shanghai Jiao Tong University<br><span>Shanghai, China</span></p></li>
        <li><time datetime="2025-07">Jul 2025</time><p>AI4Math Workshop, Shanghai Jiao Tong University<br><span>Shanghai, China</span></p></li>
      </ol>
    </div>
  </section>

  <section class="home-section home-section--compact" id="education" aria-labelledby="education-title">
    <div class="section-heading">
      <p class="section-index">04</p>
      <h2 id="education-title">Education</h2>
    </div>
    <div class="section-content">
      <ol class="timeline-list timeline-list--education">
        <li><time>2024–2028</time><p><strong>PhD, Applied Mathematics</strong><br><span>Shanghai Jiao Tong University</span></p></li>
        <li><time>2023–2024</time><p><strong>MS, Data-Driven Modeling</strong><br><span>Hong Kong University of Science and Technology</span></p></li>
        <li><time>2019–2023</time><p><strong>BS, Information and Computing Science</strong><br><span>Jinan University</span></p></li>
      </ol>
    </div>
  </section>
</div>

<footer class="home-footer">
  <p class="home-footer__statement">Interested in reliable AI for mathematical reasoning and code generation?</p>
  <a href="mailto:xiaoyang.liu@sjtu.edu.cn">xiaoyang.liu@sjtu.edu.cn</a>
  <p class="home-footer__meta">Xiaoyang Liu · Shanghai, China</p>
</footer>
