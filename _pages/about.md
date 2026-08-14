---
permalink: /
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

<summary id="about_me"><span class="summary-heading">About Me</span></summary>

I am a second-year Ph.D. student (D2) in the [Natural Language Processing Laboratory](https://nlp.naist.jp/en/) at the [Nara Institute of Science and Technology (NAIST)](https://www.naist.jp/en/), advised by [Yusuke Sakai](https://www.yusuke1997.jp/), [Hidetaka Kamigaito](https://sites.google.com/site/hidetakakamigaito), and [Taro Watanabe](https://sites.google.com/site/tarowtnb/home).

My research lies at the intersection of natural language processing, vision-language models, and trustworthy AI. I am particularly interested in evaluating and improving multimodal and large language models across cultural, scientific, and high-stakes settings. My recent work covers LLM bias and evaluation, Chinese art understanding, tool-augmented remote sensing, and clinical AI.

You can find my latest work on [Google Scholar](https://scholar.google.com/citations?user=V5Z7HzMAAAAJ&hl=en).

---

<details id="publications" open>
  <summary><span class="summary-heading">Publications</span></summary>
  <ul>
    <li>
      <strong>CArtBench: Evaluating Vision-Language Models on Chinese Art Understanding, Interpretation, and Authenticity</strong><br>
      Xuefeng Wei, Zhixuan Wang, <u>Xuan Zhou</u>, Zhi Qu, Hongyao Li, Yusuke Sakai, Hidetaka Kamigaito, Taro Watanabe<br>
      <em>arXiv preprint arXiv:2604.11632, 2026</em><br>
      <a href="https://arxiv.org/abs/2604.11632"><img src="https://img.shields.io/badge/Paper-blue" alt="Paper"/></a>
    </li>
    <li>
      <strong>“Yuki Gets Sushi, David Gets Steak?”: Uncovering Gender and Racial Biases in LLM-Based Meal Recommendations</strong><br>
      Xuefeng Wei, <u>Xuan Zhou</u>, Yusuke Sakai, Taro Watanabe<br>
      <em>EACL 2026, Long Papers</em><br>
      <a href="https://aclanthology.org/2026.eacl-long.364/"><img src="https://img.shields.io/badge/Paper-blue" alt="Paper"/></a>
    </li>
    <li>
      <strong>A Cross-Domain Tool-Augmented Vision-Language Framework for Remote Sensing Image Understanding</strong><br>
      <u>Xuan Zhou</u>, Xuefeng Wei, Zhi Qu, Yusuke Sakai, Hidetaka Kamigaito, Taro Watanabe<br>
      <em>Remote Sensing, 18(10), 1613, 2026</em><br>
      <a href="https://doi.org/10.3390/rs18101613"><img src="https://img.shields.io/badge/Paper-blue" alt="Paper"/></a>
    </li>
    <li>
      <strong>Large Language Models Are Poor Clinical Decision-Makers: A Comprehensive Benchmark</strong><br>
      Fenglin Liu, Zheng Li, Hongjian Zhou, Qingyu Yin, Jingfeng Yang, Xianfeng Tang, Chen Luo, Ming Zeng, Haoming Jiang, Yifan Gao, Priyanka Nigam, Sreyashi Nag, Bing Yin, Yining Hua, <u>Xuan Zhou</u>, Omid Rohanian, Anshul Thakur, Lei Clifton, David A. Clifton<br>
      <em>EMNLP 2024, Main Conference, pp. 13696–13710</em><br>
      <a href="https://aclanthology.org/2024.emnlp-main.759/"><img src="https://img.shields.io/badge/Paper-blue" alt="Paper"/></a>
    </li>
    <li>
      <strong>FLDNet: A Foreground-Aware Network for Polyp Segmentation Leveraging Long-Distance Dependencies</strong><br>
      Xuefeng Wei, <u>Xuan Zhou</u><br>
      <em>ICONIP 2023</em><br>
      <a href="https://arxiv.org/abs/2309.05987"><img src="https://img.shields.io/badge/Paper-blue" alt="Paper"/></a>
    </li>
    <li>
      <strong>Feature Aggregation Network for Building Extraction from High-Resolution Remote Sensing Images</strong><br>
      <u>Xuan Zhou</u>, Xuefeng Wei<br>
      <em>PRICAI 2023</em><br>
      <a href="https://arxiv.org/abs/2309.06017"><img src="https://img.shields.io/badge/Paper-blue" alt="Paper"/></a>
    </li>
  </ul>
</details>

---

<details id="education">
  <summary><span class="summary-heading">Education</span></summary>
  <h3><a href="https://www.naist.jp/en/">Nara Institute of Science and Technology (NAIST)</a>, Japan</h3>
  <ul>
    <li>Ph.D. Student in Computer Science, 2024.10 - present</li>
    <li>Research: Computational Linguistics and Multimodal Large Language Models</li>
    <li>Supervisors: <a href="https://www.yusuke1997.jp/">Yusuke Sakai</a>, <a href="https://sites.google.com/site/hidetakakamigaito">Hidetaka Kamigaito</a>, and <a href="https://sites.google.com/site/tarowtnb/home">Taro Watanabe</a></li>
  </ul>

  <h3><a href="https://www.ip-paris.fr/en">Institut Polytechnique de Paris</a>, France</h3>
  <ul>
    <li>Master's degree in Electronic Information, 2021.10 - 2023.10</li>
  </ul>

  <h3><a href="https://www.sanxiau.edu.cn/">Chongqing Three Gorges University</a>, China</h3>
  <ul>
    <li>Bachelor's degree in Electronic Information Engineering, 2018.09 - 2020.06</li>
  </ul>
</details>

---

<details id="research_experience">
  <summary><span class="summary-heading">Research Experience</span></summary>
  <h3>Centrale Méditerranée, France</h3>
  <ul>
    <li>Research Internship, 2023.02 - 2023.08</li>
    <li>Worked on visual explanation methods and developed Sim-CAM based on Opti-CAM.</li>
  </ul>
</details>

<script>
(function () {
  function openDetailsFromHash() {
    if (!location.hash) return;
    const el = document.querySelector(location.hash);
    if (!el) return;
    let d = el.matches("details") ? el : el.closest("details");
    while (d) {
      d.open = true;
      d = d.parentElement?.closest("details");
    }
    el.scrollIntoView({ block: "start" });
  }
  window.addEventListener("DOMContentLoaded", openDetailsFromHash);
  window.addEventListener("hashchange", openDetailsFromHash);
})();
</script>
