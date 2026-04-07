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

I am Qian Shao (邵谦), a Ph.D. student in the College of Computer Science and Technology, Zhejiang University. I am interested in machine learning and its applications in healthcare. I work closely with [Qiyuan Chen](https://qychen2001.github.io/), [Zepeng Li](https://lzzppp.github.io/) and [Jiahe Chen](https://jiahechen2002.github.io/).

# 📝 Publications 

<span style="color:blue">(*: Equal contribution; $\dagger$: Corresponding author(s))</span>

## 2026

* [CoLA: Co-Calibrated Logit Adjustment for Long-Tailed Semi-Supervised Learning](https://openreview.net/pdf?id=pI9n8wAR80); **Qian Shao**, Q Chen, J Chen, Z Li, Q Tang, H Xu$^\dagger$, J Wu$^\dagger$. **ICLR 2026, \[CCF A, TH-CPL A\]**.

* [DREAM: Distribution-aware Re-sampling with Equiangular Alignment Mechanism for Long-Tailed Semi-Supervised Learning](); **Qian Shao**$^\*$, J Chen$^\*$, Q Chen, Q Tang, J Chen, H Xu, J Kang$^\dagger$, J Wu$^\dagger$.  **ICME 2026 (Spotlight), \[CCF B\]**.

* [Learning What Matters: Dynamic Dimension Selection and Aggregation for Interpretable Vision-Language Reward Modeling](); Q Chen, H Huang, J Chen, **Qian Shao**, J Chen, H Xu, R Hua, R Chuan, J Wu. **ACL 2026, \[CCF A, TH-CPL A\]**.


## 2025

* **\[EMNLP'25\]** [Icon$^2$: Aligning Large Language Models Using Self-Synthetic Preference Data via Inherent Regulation](https://openreview.net/pdf?id=C5nZzUzYkz); Q Chen$^\*$, H Huang$^\*$, **Qian Shao**, J Chen, J Chen, H Xu, R Hua, R Chuan$^\dagger$, J Wu$^\dagger$.

## 2024

* **\[IEEE MedAI'24\]** [Joint Explicit and Implicit Cross-Modal Interaction Network for Anterior Chamber Inflammation Diagnosis](https://ieeexplore.ieee.org/abstract/document/10803521); **Qian Shao**$^\*$, Y Dai$^\*$, H Ying$^\dagger$, K Xu, J Wang, W Chi$^\dagger$, J Wu.

* **\[KDD Workshop-AIDSH'24\]** [Comprehensive Subset Selection for CT Volume Compression to Improve Pulmonary Disease Screening Efficiency](https://openreview.net/pdf?id=JLyiMGQoqZ); **Qian Shao**$^\*$, K Zhang$^\*$, B Du, Z Li, Y Wu, Q Chen, J Wu$^\dagger$, J Chen$^\dagger$.

* **\[MICCAI'24 (Oral)\]** [TeleOR: Real-time Telemedicine System for Full-Scene Operating Room](https://link.springer.com/content/pdf/10.1007/978-3-031-72089-5_59.pdf); Y Wu$^\*$, K Hu$^\*$, **Qian Shao**, J Chen$^\dagger$, D Chen, J Wu$^\dagger$.

* **\[NeurIPS'24\]** [Enhancing Semi-Supervised Learning via Representative and Diverse Sample Selection](https://proceedings.neurips.cc/paper_files/paper/2024/file/c959bb2cb164d37569a17fa67494d69a-Paper-Conference.pdf); **Qian Shao**$^\*$, J Kang$^\*$, Q Chen$^\*$, Z Li, H Xu, Y Cao, J Liang$^\dagger$, J Wu$^\dagger$.

## 2021

* **\[Mathematical Biosciences and Engineering, 2021\]** [Deep learning and radiomics analysis for prediction of placenta invasion based on T2WI](http://www.aimspress.com/aimspress-data/mbe/2021/5/PDF/mbe-18-05-310.pdf); **Qian Shao**$^\*$, R Xuan$^\*$, Y Wang$^\dagger$, J Xu, M Ouyang, C Yin, W Jin$^\dagger$.

* **\[Mathematical Biosciences and Engineering, 2021\]** [Development of a nomograph integrating radiomics and deep features based on MRI to predict the prognosis of high grade Gliomas](https://www.aimspress.com/aimspress-data/mbe/2021/6/PDF/mbe-18-06-401.pdf); Y Wang, **Qian Shao**$^\dagger$, S Luo, R Fu.

## Pre-Print

* **\[arXiv'26\]** [MM-DADM: Multimodal Drug-Aware Diffusion Model for Virtual Clinical Trials](https://arxiv.org/abs/2502.07297); **Qian Shao**$^\*$, B Du$^\*$, Z Li, Q Chen, J Chen, H Xu, J Sun, J Wu$^\dagger$, J Chen$^\dagger$.

* **\[arXiv'26\]** [Towards Clinical Practice in CT-Based Pulmonary Disease Screening: An Efficient and Reliable Framework](https://arxiv.org/pdf/2412.01525); **Qian Shao**$^\*$, B Du$^\*$, Y Wu, Z Li, Q Chen, Q Tang, J Wu, J Chen$^\dagger$, H Xu$^\dagger$.

* **\[arXiv'25\]** [CC-GSEO-Bench: A Content-Centric Benchmark for Measuring Source Influence in Generative Search Engines](https://arxiv.org/pdf/2509.05607); Q Chen$^\*$, J Chen$^\*$, H Huang$^\*$, **Qian Shao**, J Chen, R Hua, H Xu, R Wu, C Ren$^\dagger$, J Wu$^\dagger$.

* **\[arXiv'25\]** [Curing Semantic Drift: A Dynamic Approach to Grounding Generation in LVLMs](https://arxiv.org/pdf/2506.21509); J Chen, J He, Q Chen, **Qian Shao**, J Ying, H Xu, J Chen, J Zheng$^\dagger$, J Wu$^\dagger$.

<!-- ## Under Review

* **\[Science Bulletin, 2026\]** [Deep learning-enabled objective quantification of anterior chamber inflammation on multi-device AS-OCT images: a multicenter diagnostic study](); Y Dai$^*$, **Qian Shao**$^*$, K Xu, Q Chen, Y Wang, L Jiang, G Zhu, Y Sun, M Lu, K Zeng, J Liu, P Zeng, X Yao, X Hu, Y Cheng, L Su, X Guo, D Lin, N Gong, L Chen, J Wu, L Niu, H Ying, W Chi$^\dagger$.

* **\[ACL'26\]** [D-GSEO-Bench: Embedding-Based, Deterministic Measurement of Source Influence in Generative Search Engines](); Q Chen, H Huang, J Chen, **Qian Shao**, J Chen, H Xu, R Hua, R Chuan, J Wu.

* **\[ECCV'26\]** [Geometric Gradient Rectification for Safe Open-Set Semi-Supervised Learning](); J Chen$^*$, **Qian Shao**$^*$, Q Chen, J He, J Chen, H Xu, J Wu. -->



# 🎖 Awards

- *2025.12*, Academic Excellence First-Class Scholarship for Graduate Students, College of Computer Science $\&$ Technology, Zhejiang University

- *2019.12*, Sencond Prize in "HUAWEI Cup" The 16th China Post-Graduate Mathematical Contest in Modeling (Top 15%)

# 📖 Educations
- *2022.09 - 2026.03 (expected)*, Ph.D. in Computer Science and Technology, College of Computer Science and Technology, Zhejiang University

- *2019.09 - 2022.06*, M.Eng. in Computer Technology, Faculty of Electrical Engineering and Computer Science, Ningbo University

- *2014.09 - 2018.06*, B.Eng. in Computer Science and Technology, Faculty of Electrical Engineering and Computer Science, Ningbo University


# 💬 Talks
None yet.