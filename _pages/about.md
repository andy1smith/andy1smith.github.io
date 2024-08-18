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

Dr. Jiahao Wang is currently a research engineer in **AI safety and governance** at Huawei Technologies Co., Ltd. He received his PhD and B.S. degrees in Computer Science from Beihang University in 2022 and 2017 respectively. He also worked as a research intern in Meituan in 2021. Supervised by Prof. [Yunhong Wang](https://scholar.google.com/citations?user=0ez7lA0AAAAJ) at [IRIP Lab](https://irip.buaa.edu.cn/), Jiahao’s major research interest during PhD was computer vision and video understanding, where he focused on how to utilize **few-shot, unsupervised** and other representation learning methods to facilitate AI **understanding human behaviors accurately and reliably.** It was also from then Jiahao has begun to pay attention to the trustworthiness and safety issues of AI. After joining Huawei, he started in-depth research in AI safety and governance, with a particular focus on **AI alignment, hallucination mitigation** and other cutting-edge areas like AI transparency and data governance.


# 🔥 News
- *2024.05*: &nbsp;🎉🎉 Our work **EvCap: Element-Aware Video Captioning** was accepted by IEEE TCSVT.
- *2022.07*: &nbsp;🎉🎉 Our unsupervised video segmentation method **PACE** was accepted by IJCAI 2024. 

# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IJCAI 2022</div><img src='images/500x300.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[PACE: Predictive and Contrastive Embedding for Unsupervised Action](https://www.ijcai.org/proceedings/2022/0198.pdf)

**Jiahao Wang**, Jie Qin, Yunhong Wang, Annan Li, **IJCAI 2022**

- We are the first to exploit both predictability and similarity information for unsupervised action segmentation. By leveraging their complementarity, we overcome the limitations of existing clustering- and prediction-based methods.
- We design a unified framework to simultaneously learn predictive and contrastive embeddings, based on which accurate action boundaries are detected.
- Extensive experiments on three challenging benchmarks demonstrate the superiority of PACE, with up to 26.9% improvements in F1-score over the state of the art.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACM MM 2021</div><img src='images/ACM MM 21.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Few-shot fine-grained action recognition via bidirectional attention and contrastive meta-learning](https://dl.acm.org/doi/10.1145/3474085.3475216)

**Jiahao Wang**, Yunhong Wang, Sheng Liu, Annan Li, **ACM MM 2021**

[**Project**](https://github.com/acewjh/FSFG) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- We propose the few-shot fine-grained action recognition problem, which is spawned from real-world demands. A novel framework is devised to accurately recognize unseen f ine-grained actions with few support samples. 
- We combine task-driven and saliency-supervised signals to capture subtle action details, simulating the top-down and bottom-up attention mechanism of human vision. 
- To generate discriminative representations for low interclass variance data, we propose contrastive meta-learning, making full use of potential contrastive pairs.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TOMM</div><img src='images/500x300.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Will You Ever Become Popular? Learning to Predict Virality of Dance Clips](https://dl.acm.org/doi/abs/10.1145/3477533)

**Jiahao Wang**, Yunhong Wang, Nina Weng, Tianrui Chai, Annan Li, Faxi Zhang, Sansi Yu, **ACM TOMM**

- We first study virality prediction from dance challenges using visual cues, which has great commercial value. To facilitate the research, we release VDV dataset, a large-scale multi-modal dance virality prediction benchmark.
- A multi-modal framework modeling both body movements and appearance dynamics is developed. For skeleton-based prediction, we devise a pyramidal skeleton graph convolutional network (PSGCN). For appearance-based prediction, relational temporal convolutional networks (RTCN) are proposed. An attentive modality fusion approach is introduced to aggregate predictions from multiple streams.
</div>
</div>


# 🎖 Honors and Awards
- *2023* Huawei Rising Star Award
- *2022* Outstanding Doctoral Graduate Award of Beihang University
- *2017* Doctoral Scholarship of Beihang University
- *2017* Outstanding Undergraduate Graduate Award of Beijing
- *2016* Meritorious Winner of MCM/ICM
- *2016* Social Work Scholarship of Beihang University
- *2016* Silver Medal of the 26th “Feng Ru Cup” Competition of Beihang University

# 📖 Educations
- *2017.09 - 2022.07*, PhD in Computer Science, Beihang University, Beijing, China (Supervised by Prof. [Yunhong Wang](https://scholar.google.com/citations?user=0ez7lA0AAAAJ) at [IRIP Lab](https://irip.buaa.edu.cn/))
- *2015.09 - 2019.06*, B.E. in Computer Science and Technology, Beihang University, Beijing, China

# 💻 Internships
- *2021.05 - 2021.10*, Visual Intelligence Center, Meituan, Beijing, China.