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

Exploring secure and trustworthy AI, from deepfake detection to robust large language models.

Based in Qingdao, China. 3nd-year Ph.D., School of Cyber Science and Technology at Shandong University.

**Research Interests:**
- **Trustworthy Machine Learning**: Researching safety, robustness, and privacy across generative models and LLM agents.
- **Deepfake Forensics**: Building attacks and defenses for facial forgery detection in practical pipelines.
- **Secure LLM Systems**: Designing evaluation frameworks that expose risk interactions and support safer deployments.


<span class='anchor' id='Education'></span>

# 📖 Education
- *2023.09 - Present*, Ph.D. Student, School of Cyber Science and Technology, Shandong University, Qingdao, China.  
  Advisor: [**Xiaoyun Wang**](https://www.ias.tsinghua.edu.cn/en/info/1059/1173.htm)
- *2020.09 - 2023.06*, Master's Degree, Shandong University (Thesis on robustness research for deepfake detection).  
  Advisor: [**Shanqing Guo**](https://scholar.google.com/citations?user=zsoQa0cAAAAJ&hl=en)


<span class='anchor' id='News'></span>

# 🔥 News
- *2025.11*: &nbsp;🎉 Featured by MIT Technology Review China - Media coverage of our latest LLM defense study.
- *2025.10*: &nbsp;📄 Preprint: From Defender to Devil? - Investigating unintended risk interactions introduced by LLM defenses.
- *2025.09*: &nbsp;🎉 ErrorTrace accepted at NeurIPS 2025 (spotlight) - Black-box traceability based on model family error space.
- *2025.09*: &nbsp;🤝 Industry collaboration launched - Joint research project on LLM security testing and risk assessment with Topsec.
- *2025.08*: &nbsp;📄 Preprint: Safe-Control - Safety patch for mitigating unsafe content in text-to-image generation models.
- *2025.08*: &nbsp;🎉 DCMI accepted at CCS 2025 - Differential calibration membership inference against RAG.
- *2025.03*: &nbsp;🎉 Fuzz-testing meets LLM-based agents accepted at IEEE S&P 2025 - Automated framework for jailbreaking text-to-image generation models.
- *2024.11*: &nbsp;🏆 Outstanding master's thesis - Recognized for thesis on robustness research for deepfake detection. 


# 🎖 Honors and Awards
- *2024.11* Outstanding master's thesis - Recognized for thesis on robustness research for deepfake detection.


# 👔 Academic Services
- *2025*, Reviewer for **IEEE Transactions on Information Forensics and Security (TIFS)**


<span class='anchor' id='Publications'></span>

# 📝 Publications 

## 2025

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">arXiv 2025</div><img src='images/crossriskeval.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[From Defender to Devil? Unintended Risk Interactions Induced by LLM Defenses](https://arxiv.org/abs/2510.07968)

**Xiangtao Meng**, Tianshuo Cong, Li Wang, Wenyu Chen, Zheng Li✉, Shanqing Guo✉, Xiaoyun Wang✉

**arXiv** · LLM Safety Risk Analysis

[**Paper**](https://arxiv.org/abs/2510.12345)
- Investigating unintended risk interactions introduced by LLM defenses.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">NeurIPS 2025</div><img src='images/errortrace.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[ErrorTrace: A Black-Box Traceability Mechanism Based on Model Family Error Space](https://neurips.cc/virtual/2025/loc/san-diego/poster/120038)

Chuanchao Zang, **Xiangtao Meng**, Wenyu Chen, Tianshuo Cong, Zha Yaxing, Dong Qi, Zheng Li, Shanqing Guo

**NeurIPS (Spotlight)** · Model Provenance

[**Link**](https://neurips.cc/Conferences/2025)
- Black-box traceability based on model family error space.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">arXiv 2025</div><img src='images/safepatch.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Safe-Control: A Safety Patch for Mitigating Unsafe Content in Text-to-Image Generation Models](https://arxiv.org/abs/2508.21099)

**Xiangtao Meng**, Yingkai Dong, Ning Yu, Li Wang, Zheng Li✉, Shanqing Guo✉

**arXiv** · T2I Safety Defense

[**Paper**](https://arxiv.org/abs/2508.21099)
- Safety patch for mitigating unsafe content in text-to-image generation models.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CCS 2025</div><img src='images/dcmi.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[DCMI: A Differential Calibration Membership Inference Attack Against Retrieval-Augmented Generation](https://arxiv.org/abs/2509.06026)

Xinyu, **Xiangtao Meng✉**, Yingkai Dong, Zheng Li✉, Shanqing Guo✉

**CCS** · RAG Security

[**Paper**](https://arxiv.org/abs/2509.06026)
- Differential calibration membership inference against RAG.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IEEE S&P 2025</div><img src='images/fuzz.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Fuzz-testing meets LLM-based agents: An automated and efficient framework for jailbreaking text-to-image generation models](https://arxiv.org/abs/2408.00523)

Yingkai Dong, **Xiangtao Meng**, Ning Yu, Li Wang, Zheng Li✉, Shanqing Guo✉

**IEEE S&P** · Adversarial Testing

[**Paper**](https://arxiv.org/abs/2408.00523)
- Automated framework for jailbreaking text-to-image generation models.
</div>
</div>

## 2024

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IEEE S&P 2024</div><img src='images/ava.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[AVA: Inconspicuous Attribute Variation-based Adversarial Attack bypassing DeepFake Detection](https://arxiv.org/abs/2312.08675)

**Xiangtao Meng**, Li Wang, Shanqing Guo✉, Lei Ju, Qingchuan Zhao

**IEEE S&P** · Deepfake Attack

[**Paper**](https://arxiv.org/abs/2312.08675) [**Code**](https://github.com/AnonymousUserA/AVA)
- Inconspicuous attribute variation-based adversarial attack bypassing deepfake detection.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACM TOPS</div><img src='images/deepfaker.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[DEEPFAKER: A Unified Evaluation Platform for Facial Deepfake and Detection Models](https://dl.acm.org/doi/10.1145/3634914)

Li Wang, **Xiangtao Meng**, Dan Li, Xuhong Zhang, Shouling Ji, Shanqing Guo✉

**ACM TOPS** · Benchmark CCF B

[**Paper**](https://dl.acm.org/doi/10.1145/3634914)
- A unified evaluation platform for facial deepfake and detection models.
</div>
</div>
