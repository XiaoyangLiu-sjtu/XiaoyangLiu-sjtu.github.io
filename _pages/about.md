---
permalink: /
title: "Xiaoyang Liu"
description: "Xiaoyang Liu is a PhD candidate at Shanghai Jiao Tong University working on large language models, post-training, Lean, and formal verification."
excerpt: "Research in agentic systems, data synthesis, and model evaluation for large language models and formal verification."
author_profile: false
redirect_from:
  - /about/
  - /about.html
---

<section class="profile-hero" id="about" aria-labelledby="profile-title">
  <div class="profile-hero__content">
    <h1 id="profile-title">Xiaoyang Liu</h1>
    <nav class="profile-links" aria-label="Profile links">
      <a href="mailto:xiaoyang.liu@sjtu.edu.cn"><i class="fas fa-envelope" aria-hidden="true"></i>Email</a>
      <a href="https://scholar.google.com/citations?user=BKTfL-gAAAAJ" target="_blank" rel="noopener noreferrer"><i class="fas fa-graduation-cap" aria-hidden="true"></i>Google Scholar</a>
      <a href="https://github.com/XiaoyangLiu-sjtu" target="_blank" rel="noopener noreferrer"><i class="fab fa-github" aria-hidden="true"></i>GitHub</a>
    </nav>
    <p class="profile-hero__statement">I am a third-year PhD candidate advised by <a href="https://math.sjtu.edu.cn/Default/teachershow/tags/MDAwMDAwMDAwMLKIet0" target="_blank" rel="noopener noreferrer">Prof. Tao Luo</a> at <a href="https://math.sjtu.edu.cn/Default/index/" target="_blank" rel="noopener noreferrer">School of Mathematical Sciences</a>, <a href="https://www.sjtu.edu.cn/" target="_blank" rel="noopener noreferrer">Shanghai Jiao Tong University (SJTU)</a>.</p>
    <p class="availability">Since July 2026, I have been working as a Post-Training Research Intern at the Wizard Intelligence Learning Lab (WILL).</p>
  </div>
  <figure class="profile-hero__portrait">
    <img src="/images/profile-photo-square.jpg" alt="Portrait of Xiaoyang Liu" width="1000" height="1000">
  </figure>
</section>

<section class="home-section research-section" id="research" aria-labelledby="research-title">
  <div class="section-heading">
    <h2 id="research-title">Research</h2>
  </div>
  <div class="section-content">
    <p class="research-keywords">LLM · Lean · Post-Training · AI4Math</p>
    <p class="section-lead">I work on large language models and post-training, with a focus on agentic systems, data synthesis, and model evaluation. My research connects LLMs with Lean to advance automated theorem proving and mathematical formalization.</p>
    <div class="research-areas">
      <article>
        <h3>Agentic Systems</h3>
        <p>Developing LLM-based agentic systems for theorem proving and mathematical formalization, with the goal of supporting mathematical research through reliable automation.</p>
      </article>
      <article>
        <h3>Data Synthesis</h3>
        <p>Synthesizing high-quality training data and fine-tuning LLMs through expert iteration in <strong>ATLAS</strong>, and neuro-symbolic data generation and curriculum learning in <strong>DSR</strong>.</p>
      </article>
      <article>
        <h3>Model Evaluation</h3>
        <p>Developing semantic and structural evaluation with <strong>ASSESS</strong>, actionable error diagnosis and correction with <strong>FormalRx</strong>, and adversarial specification testing with <strong>VeriScale</strong>.</p>
      </article>
    </div>
  </div>
</section>

<section class="home-section" id="publications" aria-labelledby="publications-title">
  <div class="section-heading">
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
        <p class="publication__links"><a href="https://icml.cc/virtual/2026/82615" target="_blank" rel="noopener noreferrer">Official</a><a href="https://arxiv.org/abs/2605.22368v1" target="_blank" rel="noopener noreferrer">arXiv</a><a href="https://github.com/XiaoyangLiu-sjtu/VeriScale" target="_blank" rel="noopener noreferrer">GitHub</a></p>
      </div>
    </article>

    <article class="publication">
      <div class="publication__body">
        <p class="publication__venue">ICML 2026</p>
        <h3><a href="https://arxiv.org/abs/2604.19000" target="_blank" rel="noopener noreferrer">Decompose, Structure, and Repair: A Neuro-Symbolic Framework for Autoformalization via Operator Trees</a></h3>
        <p class="publication__authors"><strong>Xiaoyang Liu</strong>, Zineng Dong, Yifan Bai, Yantao Li, Yuntian Liu, Tao Luo<sup>†</sup></p>
        <p class="publication__summary">A neuro-symbolic framework that structures autoformalization with operator trees and repairs failed Lean outputs.</p>
        <p class="publication__links"><a href="https://icml.cc/virtual/2026/poster/62990" target="_blank" rel="noopener noreferrer">Official</a><a href="https://arxiv.org/abs/2604.19000" target="_blank" rel="noopener noreferrer">arXiv</a><a href="https://github.com/XiaoyangLiu-sjtu/DSR" target="_blank" rel="noopener noreferrer">GitHub</a></p>
      </div>
    </article>

    <article class="publication">
      <div class="publication__body">
        <p class="publication__venue">ICML 2026</p>
        <h3><a href="https://arxiv.org/abs/2607.04655" target="_blank" rel="noopener noreferrer">FormalRx: Rectify and eXamine Semantic Failures in Autoformalization</a></h3>
        <p class="publication__authors">Haocheng Wang<sup>*</sup>, Baiyu Huang<sup>*</sup>, Yingjia Wan<sup>*</sup>, Xiao Zhu, <strong>Xiaoyang Liu</strong>, Yinya Huang<sup>†</sup>, Zhijiang Guo<sup>†</sup></p>
        <p class="publication__summary">A framework for detecting, examining, and rectifying semantic failures in autoformalized statements.</p>
        <p class="publication__links"><a href="https://proceedings.mlr.press/v306/wang26cg.html" target="_blank" rel="noopener noreferrer">Official</a><a href="https://arxiv.org/abs/2607.04655" target="_blank" rel="noopener noreferrer">arXiv</a><a href="https://huggingface.co/collections/LARK-Lab/formalrx" target="_blank" rel="noopener noreferrer">HuggingFace</a></p>
      </div>
    </article>

    <article class="publication">
      <div class="publication__body">
        <p class="publication__venue">ICLR 2026</p>
        <h3><a href="https://arxiv.org/abs/2509.22246" target="_blank" rel="noopener noreferrer">ASSESS: A Semantic and Structural Evaluation Framework for Statement Similarity</a></h3>
        <p class="publication__authors"><strong>Xiaoyang Liu<sup>*</sup></strong>, Tao Zhu<sup>*</sup>, Zineng Dong, Yuntian Liu, Qingfeng Guo, Zhaoxuan Liu, Yu Chen, Tao Luo<sup>†</sup></p>
        <p class="publication__summary">An evaluation framework that combines semantic and structural signals to compare formal statements.</p>
        <p class="publication__links"><a href="https://iclr.cc/virtual/2026/poster/10008659" target="_blank" rel="noopener noreferrer">Official</a><a href="https://arxiv.org/abs/2509.22246" target="_blank" rel="noopener noreferrer">arXiv</a><a href="https://github.com/XiaoyangLiu-sjtu/ASSESS" target="_blank" rel="noopener noreferrer">GitHub</a></p>
      </div>
    </article>

    <article class="publication">
      <div class="publication__body">
        <p class="publication__venue">NeurIPS 2025</p>
        <h3><a href="https://arxiv.org/abs/2502.05567" target="_blank" rel="noopener noreferrer">ATLAS: Autoformalizing Theorems through Lifting, Augmentation, and Synthesis of Data</a></h3>
        <p class="publication__authors"><strong>Xiaoyang Liu</strong>, Kangjie Bao, Jiashuo Zhang, Yunqi Liu, Yu Chen, Yuntian Liu, Yang Jiao<sup>†</sup>, Tao Luo<sup>†</sup></p>
        <p class="publication__summary">A data-centric approach to theorem autoformalization through lifting, augmentation, and synthesis.</p>
        <p class="publication__links"><a href="https://proceedings.neurips.cc/paper_files/paper/2025/hash/5159aaee380391c366b27994ed225e4f-Abstract-Conference.html" target="_blank" rel="noopener noreferrer">Official</a><a href="https://arxiv.org/abs/2502.05567" target="_blank" rel="noopener noreferrer">arXiv</a><a href="https://github.com/XiaoyangLiu-sjtu/ATLAS" target="_blank" rel="noopener noreferrer">GitHub</a></p>
      </div>
    </article>

    <article class="publication">
      <div class="publication__body">
        <p class="publication__venue">ICML 2025 · AI4Math Workshop</p>
        <h3><a href="https://arxiv.org/abs/2507.07399" target="_blank" rel="noopener noreferrer">Generalized Tree Edit Distance (GTED): A Faithful Evaluation Metric for Statement Autoformalization</a></h3>
        <p class="publication__authors">Yuntian Liu<sup>*</sup>, Tao Zhu<sup>*</sup>, <strong>Xiaoyang Liu<sup>*</sup></strong>, Yu Chen, Zhaoxuan Liu, Qingfeng Guo, Jiashuo Zhang, Kangjie Bao, Tao Luo<sup>†</sup></p>
        <p class="publication__summary">A tree-edit-distance metric designed to evaluate the structure and meaning of autoformalized statements.</p>
        <p class="publication__links"><a href="https://icml.cc/virtual/2025/52459" target="_blank" rel="noopener noreferrer">Official</a><a href="https://arxiv.org/abs/2507.07399" target="_blank" rel="noopener noreferrer">arXiv</a><a href="https://github.com/XiaoyangLiu-sjtu/GTED" target="_blank" rel="noopener noreferrer">GitHub</a></p>
      </div>
    </article>
  </div>
</section>

<footer class="home-footer">
  <p class="home-footer__statement">Last updated: October 2026</p>
  <a href="mailto:xiaoyang.liu@sjtu.edu.cn">xiaoyang.liu@sjtu.edu.cn</a>
  <p class="home-footer__meta">Xiaoyang Liu · Shanghai, China</p>
</footer>
