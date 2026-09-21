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

I am **Yuanhao Liu (刘元浩)**, a Postdoctoral Researcher at the Institute of Computing Technology, Chinese Academy of Sciences (ICT, CAS), affiliated with the National Key Laboratory of Intelligent Algorithm Security. I received my Ph.D. in Computer Science from ICT, CAS in 2026, under the supervision of Prof. Huawei Shen (沈华伟), and my B.Eng. degree in Software Engineering from Nankai University in 2020.

My research focuses on **algorithm safety and trustworthy AI**, with particular interests in **algorithmic fairness, recommender system safety, algorithm auditing, and risk assessment and governance**. I am especially interested in understanding how algorithmic risks emerge and evolve in real-world intelligent systems, and in developing methods to **measure, identify, attribute, and mitigate** these risks.

My work has been published at venues including **WWW, SIGIR, CSCW, and IJCAI**, covering topics such as fairness auditing, popularity bias, recommender system safety, and reliability of algorithmic evaluations.

Please feel free to contact me at <a href="mailto:liuyuanhao.cn@gmail.com">[liuyuanhao.cn@gmail.com](mailto:liuyuanhao.cn@gmail.com)</a> for academic discussions and collaborations.


# 🔥 News
- *2026.06*: &nbsp;🎓 Received my Ph.D. degree from the Institute of Computing Technology, Chinese Academy of Sciences.
- *2026.05: &nbsp;🎉 Paper accepted to IJCAI-ECAI 2026.
- *2025.10*: &nbsp;🎉 Paper accepted to ACM CSCW 2025.

# 📝 Publications 

<span class='anchor' id='consistency-radius'></span>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ijcai 2026</div><img src='images/ijcai2026radius.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[When Can We Trust Fairness Audits? Identifying Reliability Boundaries of Third-party Audit Conclusions]()

**Yuanhao Liu**, Qi Cao, Huawei Shen

[**appendix**](../files/ijcai2026appendix.pdf) | [**code**](https://github.com/UnitDan/fairness-audit-reliability)
- Addressed fairness fragility under distribution shifts by proposing the Consistency Radius. Proposed a convex relaxation-
based estimator enables a blind auditing paradigm, bridging static evaluation and dynamic deployment without requiring
sensitive user data.
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CSCW 2025</div><img src='images/cscw2025substantiating.jpg' alt="sym" width="100%"></div></div>
<span class='anchor' id='BUFF'></span>
<div class='paper-box-text' markdown="1">

["I Know You Are Discriminatory!": Automated Substantiating for Individual Fairness Auditing of AI Systems](https://dl.acm.org/doi/abs/10.1145/3757414)

**Yuanhao Liu**, Qi Cao, Huawei Shen, Kaike Zhang, Yunfan Wu, Xueqi Cheng

[**Code**](https://github.com/UnitDan/substantiating)
- Designed auditing techniques to evaluate individual fairness in AI systems when access to model internals and training data is restricted, and developed substantiating frameworks for fairness violations.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">The Innovation</div><img src='images/innovation2025safety.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[The rising safety concerns of deep recommender systems](https://www.sciencedirect.com/science/article/pii/S2666675825002413)

Huawei Shen, **Yuanhao Liu**, Kaike Zhang, Qi Cao, Xueqi Cheng

- Reviewed the development of recommender systems and the accompanying security issues, particularly fairness, robustness, and filter bubble problems, and outlined future research directions.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">SIGIR 2023</div><img src='images/sigir2023IPL.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Popularity debiasing from exposure to interaction in collaborative filtering](https://dl.acm.org/doi/abs/10.1145/3539618.3591947)

**Yuanhao Liu**, Qi Cao, Huawei Shen, Yunfan Wu, Shuchang Tao, Xueqi Cheng

[**Code**](https://github.com/UnitDan/IPL)
- Redefined fairness on the item side of recommendations from the perspective of click volume. The method achieved a win–win between recommendation accuracy and fairness.
- Recognized by the [WSDM 2025 Best Paper](https://dl.acm.org/doi/abs/10.1145/3701551.3703579) as a representative approach for popularity debiasing.
</div>
</div>

- [PREP: Pre-training with temporal elapse inference for popularity prediction](https://dl.acm.org/doi/abs/10.1145/3487553.3524249), Qi Cao, Huawei Shen, **Yuanhao Liu**, Jinhua Gao, Xueqi Cheng, **WWW 2022**

# 🎖 Honors and Awards
- *2024.03* Excellent Student Award from the Institute of Computing Technology, Chinese Academy of Sciences. 

# 📖 Education
- *2020.09 - 2026.06*, Ph.D. in Computer Science, Institute of Computing Technology, Chinese Academy of Sciences.
- *2016.09 - 2020.07*, B.Eng. in Software Engineering, Nankai University.

# 🎤 Talks & Presentations
- *2026.08*, IJCAI-ECAI 2026, Bremen, Germany.
- *2025.10*, CSCW 2025, Bergen, Norway.
- *2023.07*, SIGIR 2023, Taipei, Taiwan / Online.
- *2023.06*, AIS 2023, Changsha, China.

# 💼 Experience
- *2026.07 - Present*, Postdoctoral Researcher / Special Research Assistant, Institute of Computing Technology, Chinese Academy of Sciences.
