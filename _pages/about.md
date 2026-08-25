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

Based in Qingdao, China. I am a Ph.D. student at the School of Cyber Science and Technology, Shandong University.

**Research Interests:**
- **Trustworthy Machine Learning**: Researching safety, robustness, and privacy across generative models and LLM agents.
- **Deepfake Forensics**: Building attacks and defenses for facial forgery detection in practical pipelines.
- **Secure LLM Systems**: Designing evaluation frameworks that expose risk interactions and support safer deployments.


<span class='anchor' id='education'></span>

# 📖 Education
- *2023.09 - Present*, Ph.D. Student, School of Cyber Science and Technology, Shandong University, Qingdao, China.  
  - Supervisors: [**Shanqing Guo**](https://scholar.google.com/citations?user=zsoQa0cAAAAJ&hl=en) and [**Xiaoyun Wang**](https://www.ias.tsinghua.edu.cn/en/info/1059/1173.htm)
  - Co-supervisor: [**Zheng Li**](https://zhenglisec.github.io/)
- *2020.09 - 2023.06*, Master's Degree, Shandong University (Thesis on robustness research for deepfake detection).  
  - Supervisor: [**Shanqing Guo**](https://scholar.google.com/citations?user=zsoQa0cAAAAJ&hl=en)


<span class='anchor' id='news'></span>

# 🔥 News

<div class="news-list" aria-label="Latest news">
  <div class="news-item news-item--featured">
    <time class="news-date" datetime="2026-08">2026.08</time>
    <div class="news-content"><span class="news-tag news-tag--service">Service</span>I will serve on the Program Committee for <a href="https://www.usenix.org/conference/usenixsecurity27"><strong>USENIX Security '27</strong></a>.</div>
  </div>
  <div class="news-item">
    <time class="news-date" datetime="2026-04">2026.04</time>
    <div class="news-content"><span class="news-tag news-tag--publication">Publication</span>Our paper <strong>Beyond the Safety Tax</strong> was accepted to the Findings of ACL 2026.</div>
  </div>
  <div class="news-item">
    <time class="news-date" datetime="2026-03">2026.03</time>
    <div class="news-content"><span class="news-tag news-tag--preprint">Preprint</span><a href="https://arxiv.org/abs/2603.23269"><strong>Not All Tokens Are Created Equal</strong></a>: query-efficient jailbreak fuzzing for LLMs.</div>
  </div>
  <div class="news-item">
    <time class="news-date" datetime="2025-11">2025.11</time>
    <div class="news-content"><span class="news-tag news-tag--media">Media</span><a href="https://wap.mittrchina.com/news/detail/15426"><strong>MIT Technology Review China</strong></a> featured our text-to-image safety defense study.</div>
  </div>
  <div class="news-item">
    <time class="news-date" datetime="2025-10">2025.10</time>
    <div class="news-content"><span class="news-tag news-tag--preprint">Preprint</span><a href="https://arxiv.org/abs/2510.07968"><strong>From Defender to Devil?</strong></a> investigates unintended risk interactions induced by LLM defenses.</div>
  </div>
  <div class="news-item">
    <time class="news-date" datetime="2025-09">2025.09</time>
    <div class="news-content"><span class="news-tag news-tag--publication">Publication</span><strong>ErrorTrace</strong> was accepted to NeurIPS 2025 as a spotlight paper.</div>
  </div>
  <div class="news-item">
    <time class="news-date" datetime="2025-09">2025.09</time>
    <div class="news-content"><span class="news-tag news-tag--collaboration">Collaboration</span>Launched a joint project with Topsec on LLM security testing and risk assessment.</div>
  </div>
  <div class="news-item">
    <time class="news-date" datetime="2025-08">2025.08</time>
    <div class="news-content"><span class="news-tag news-tag--publication">Publication</span><strong>DCMI</strong> was accepted to ACM CCS 2025.</div>
  </div>
  <div class="news-item">
    <time class="news-date" datetime="2025-03">2025.03</time>
    <div class="news-content"><span class="news-tag news-tag--publication">Publication</span><strong>Fuzz-testing Meets LLM-based Agents</strong> was accepted to IEEE S&amp;P 2025.</div>
  </div>
  <div class="news-item">
    <time class="news-date" datetime="2024-11">2024.11</time>
    <div class="news-content"><span class="news-tag news-tag--award">Award</span>Received the Outstanding Master's Thesis award for research on robust deepfake detection.</div>
  </div>
</div>


<span class='anchor' id='honors-and-awards'></span>

# 🎖 Honors and Awards
- *2024.11* Outstanding master's thesis - Recognized for thesis on robustness research for deepfake detection.


<span class='anchor' id='academic-services'></span>

# 👔 Academic Services
- *2027*, Program Committee Member for [**USENIX Security '27**](https://www.usenix.org/conference/usenixsecurity27)
- *2025*, Reviewer for **IEEE Transactions on Information Forensics and Security (TIFS)**


<span class='anchor' id='publications'></span>

# 📝 Publications 
## 2026
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACL 2026 Findings</div><img src="{{ '/images/safepatch.png' | relative_url }}" alt="SafePatch method overview" width="100%" loading="lazy" decoding="async"></div></div>
<div class='paper-box-text' markdown="1">

[Beyond the Safety Tax: Mitigating Unsafe Text-to-Image Generation via External Safety Rectification](https://arxiv.org/abs/2508.21099)

**Xiangtao Meng**, Yingkai Dong, Ning Yu, Li Wang, Zheng Li✉, Shanqing Guo✉

**ACL 2026 Findings** · T2I Safety Defense

[**Paper**](https://arxiv.org/abs/2508.21099)
- Safety patch for mitigating unsafe content in text-to-image generation models.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">arXiv 2026</div><img src="{{ '/images/triagefuzz.png' | relative_url }}" alt="TriageFuzz method overview" width="100%" loading="lazy" decoding="async"></div></div>
<div class='paper-box-text' markdown="1">

[Not All Tokens Are Created Equal: Query-Efficient Jailbreak Fuzzing for LLMs](https://arxiv.org/abs/2603.23269)

**Wenyu Chen**\*, **Xiangtao Meng**\*, Chuanchao Zang, Li Wang, Xinyu Gao, Jianing Wang, Peng Zhan, Zheng Li, Shanqing Guo

**arXiv**

[**Paper**](https://arxiv.org/abs/2603.23269)
- Not All Tokens Are Created Equal
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">arXiv 2026</div><img src="{{ '/images/pda.png' | relative_url }}" alt="Post-hoc distribution alignment method overview" width="100%" loading="lazy" decoding="async"></div></div>
<div class='paper-box-text' markdown="1">

[Beyond Known Fakes: Generalized Detection of AI-Generated Images via Post-hoc Distribution Alignment](https://arxiv.org/abs/2502.10803)

Li Wang, Wenyu Chen, Xiangtao Meng, Zheng Li, Shanqing Guo

**arXiv**

[**Paper**](https://arxiv.org/abs/2502.10803)
- Generalized Detection of AI-Generated Images via Post-hoc Distribution Alignment
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">arXiv 2026</div><img src="https://arxiv.org/html/2607.23444v1/isolation1.png" alt="SPORE memory extraction threat model" width="100%" loading="lazy" decoding="async"></div></div>
<div class='paper-box-text' markdown="1">

[Isolated but Exposed: Persistence-Based Memory Extraction Attack on LLM Agents](https://arxiv.org/abs/2607.23444)

Xinyu Gao, Wenyu Chen, **Xiangtao Meng**, Li Wang, Chuanchao Zang, Jianing Wang, Zheng Li, Shanqing Guo

**arXiv** · LLM Agent Privacy

[**Paper**](https://arxiv.org/abs/2607.23444)
- Persistence-based memory extraction targeting tool-side data flows in LLM agents.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">arXiv 2026</div><img src="https://arxiv.org/html/2605.14514v1/method.png" alt="ConflictEval evaluation framework" width="100%" loading="lazy" decoding="async"></div></div>
<div class='paper-box-text' markdown="1">

[Defenses at Odds: Measuring and Explaining Defense Conflicts in Large Language Models](https://arxiv.org/abs/2605.14514)

**Xiangtao Meng**, Wenyu Chen, Chuanchao Zang, Xinyu Gao, Jianing Wang, Li Wang, Zheng Li, Shanqing Guo

**arXiv** · LLM Defense Conflicts

[**Paper**](https://arxiv.org/abs/2605.14514)
- Measuring, explaining, and mitigating conflicts between sequentially deployed LLM defenses.
</div>
</div>

## 2025

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">arXiv 2025</div><img src="{{ '/images/crossriskeval.png' | relative_url }}" alt="CrossRiskEval framework overview" width="100%" loading="lazy" decoding="async"></div></div>
<div class='paper-box-text' markdown="1">

[From Defender to Devil? Unintended Risk Interactions Induced by LLM Defenses](https://arxiv.org/abs/2510.07968)

**Xiangtao Meng**, Tianshuo Cong, Li Wang, Wenyu Chen, Zheng Li✉, Shanqing Guo✉, Xiaoyun Wang✉

**arXiv** · LLM Safety Risk Analysis

[**Paper**](https://arxiv.org/abs/2510.07968)
- Investigating unintended risk interactions introduced by LLM defenses.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">NeurIPS 2025</div><img src="{{ '/images/errortrace.png' | relative_url }}" alt="ErrorTrace framework overview" width="100%" loading="lazy" decoding="async"></div></div>
<div class='paper-box-text' markdown="1">

[ErrorTrace: A Black-Box Traceability Mechanism Based on Model Family Error Space](https://neurips.cc/virtual/2025/loc/san-diego/poster/120038)

Chuanchao Zang, **Xiangtao Meng**, Wenyu Chen, Tianshuo Cong, Zha Yaxing, Dong Qi, Zheng Li, Shanqing Guo

**NeurIPS (Spotlight)** · Model Provenance

[**Link**](https://neurips.cc/Conferences/2025)
- Black-box traceability based on model family error space.
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CCS 2025</div><img src="{{ '/images/dcmi.png' | relative_url }}" alt="DCMI attack overview" width="100%" loading="lazy" decoding="async"></div></div>
<div class='paper-box-text' markdown="1">

[DCMI: A Differential Calibration Membership Inference Attack Against Retrieval-Augmented Generation](https://arxiv.org/abs/2509.06026)

Xinyu Gao, **Xiangtao Meng✉**, Yingkai Dong, Zheng Li✉, Shanqing Guo✉

**CCS** · RAG Security

[**Paper**](https://arxiv.org/abs/2509.06026)
- Differential calibration membership inference against RAG.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IEEE S&amp;P 2025</div><img src="{{ '/images/fuzz.png' | relative_url }}" alt="Agent-based text-to-image jailbreak fuzzing framework" width="100%" loading="lazy" decoding="async"></div></div>
<div class='paper-box-text' markdown="1">

[Fuzz-testing meets LLM-based agents: An automated and efficient framework for jailbreaking text-to-image generation models](https://arxiv.org/abs/2408.00523)

Yingkai Dong, **Xiangtao Meng**, Ning Yu, Li Wang, Zheng Li✉, Shanqing Guo✉

**IEEE S&P** · Adversarial Testing

[**Paper**](https://arxiv.org/abs/2408.00523)
- Automated framework for jailbreaking text-to-image generation models.
</div>
</div>

## 2024

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IEEE S&amp;P 2024</div><img src="{{ '/images/ava.png' | relative_url }}" alt="AVA adversarial attack overview" width="100%" loading="lazy" decoding="async"></div></div>
<div class='paper-box-text' markdown="1">

[AVA: Inconspicuous Attribute Variation-based Adversarial Attack bypassing DeepFake Detection](https://arxiv.org/abs/2312.08675)

**Xiangtao Meng**, Li Wang, Shanqing Guo✉, Lei Ju, Qingchuan Zhao

**IEEE S&P** · Deepfake Attack

[**Paper**](https://arxiv.org/abs/2312.08675) [**Code**](https://github.com/AnonymousUserA/AVA)
- Inconspicuous attribute variation-based adversarial attack bypassing deepfake detection.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACM TOPS</div><img src="{{ '/images/deepfaker.png' | relative_url }}" alt="DeepFaker evaluation platform overview" width="100%" loading="lazy" decoding="async"></div></div>
<div class='paper-box-text' markdown="1">

[DEEPFAKER: A Unified Evaluation Platform for Facial Deepfake and Detection Models](https://dl.acm.org/doi/10.1145/3634914)

Li Wang, **Xiangtao Meng**, Dan Li, Xuhong Zhang, Shouling Ji, Shanqing Guo✉

**ACM TOPS** · Benchmark CCF B

[**Paper**](https://dl.acm.org/doi/10.1145/3634914)
- A unified evaluation platform for facial deepfake and detection models.
</div>
</div>
