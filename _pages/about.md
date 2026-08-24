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

I received my Ph.D. in Computer Science from the <a href="http://www.cs.zju.edu.cn/">College of Computer Science and Technology</a> at <a href="https://www.zju.edu.cn/">Zhejiang University</a> in June 2026, under the supervision of Prof. <a href="http://yangy.org/">Yang Yang</a>. I also received my Bachelor's degree in Software Engineering from Zhejiang University.

During my Ph.D., my research primarily focused on graph data mining and large-scale graph neural networks. I published several papers at leading international AI conferences, including ICML, NeurIPS, and ICLR. <a href="https://scholar.google.com/citations?user=FT8SBIkAAAAJ"><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a> My work received the <a href="https://aaai-23.aaai.org/wp-content/uploads/2023/02/AAAI-23-Paper-Awards-1.pdf">Distinguished Paper Award</a> at AAAI 2023, and I was also the youngest-ever winner of the WAIC Youth Outstanding Paper Nomination Award. I enjoy exploring frontier research problems from novel and unconventional perspectives.

After completing my Ph.D., I founded <a href="https://demos.ispark.world/">ISpark</a> with a group of like-minded partners. At ISpark, we focus on next-generation AI digital content creation, spanning AI video and dynamic 3D worlds. We are developing the ISpark Fusion Model for more flexible and accessible video generation, while exploring foundational representations and models for dynamic 3D content.

If you are interested in what we do, please feel free to contact me at <a href="mailto:luckytiger@ispark.world">luckytiger@ispark.world</a>.

# 🔥 News
- *2026.07*: &nbsp;🎉🎉 I founded ISpark with a group of amazing partners. A brand-new chapter begins!
- *2026.06*: &nbsp;🎉🎉 I received my Ph.D. in Computer Science from Zhejiang University. Many thanks to Prof. Yang Yang for his guidance and support!

# 🎖 Honors and Awards
- AAAI 2023 Distinguished Paper Award (Rank 1st)
- WAIC 2023 Youth Outstanding Paper Nomination Award (Youngest-Ever Winner)
- Chinese Institute of Electronics 2024 Outstanding Ph.D. Award
- AI Time 2023 Top 10 Academic Presentations of the Year

# 📝 Publications
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IJCAI 2026</div><img src='images/UniSAGE.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**UniSAGE: Unifying Static and Dynamic Attributes with Hyper-Structure**
\[[Paper](https://arxiv.org/abs/2607.14102), [Code](https://github.com/zjunet/UniSAGE)\]

**Taoran Fang**, Yan Deng, Chunping Wang, Yang Wang, Lei Chen, Yang Yang

We seamlessly integrate dynamic and static representations, enabling them to collaborate effectively while preserving their distinct characteristics.

</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICLR 2025</div><img src='images/KAA.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**KAA: Kolmogorov-Arnold Attention for Enhancing Attentive Graph Neural Networks**
\[[Paper](https://arxiv.org/abs/2501.13456), [Code](https://github.com/zjunet/KAA)\]

**Taoran Fang**, Tianhong Gao, Chunping Wang, Yihao Shang, Wei Chow, Lei Chen, Yang Yang

We unify the scoring functions of existing attentive GNNs and compare the theoretical expressive ability between KAN-based attention and MLP-based attention.

<!-- [Deep Residual Learning for Image Recognition](https://openaccess.thecvf.com/content_cvpr_2016/papers/He_Deep_Residual_Learning_CVPR_2016_paper.pdf) -->


<!-- [**Project**](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=DhtAFkwAAAAJ&citation_for_view=DhtAFkwAAAAJ:ALROH1vI_8AC) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  -->
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICML 2024</div><img src='images/GraphTCM.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**Exploring Correlations of Self-supervised Tasks for Graphs**
\[[Paper](https://arxiv.org/abs/2405.04245), [Code](https://github.com/zjunet/GraphTCM)\]

**Taoran Fang**, Wei Zhou, Yifei Sun, Kaiqiao Han, Lvbin Ma, Yang Yang

We propose a framework to unify the self-supervised tasks for pre-trained GNNs, and analyze the correlations between these tasks.

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">NeurIPS 2023</div><img src='images/GPF.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**Universal Prompt Tuning for Graph Neural Networks**
\[[Paper](https://arxiv.org/abs/2209.15240), [Code](https://github.com/zjunet/GPF)\]

**Taoran Fang**, Yunchao Zhang, Yang Yang, Chunping Wang, Lei Chen

We unify all forms of prompt tuning on graphs and propose a Graph Prompt Tuning method with theoretical guarantees of effectiveness.

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">AAAI 2023 (Distinguished Paper)</div><img src='images/DropMessage.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**Dropmessage: Unifying Random Dropping for Graph Neural Networks**
\[[Paper](https://arxiv.org/abs/2204.10037), [Code](https://github.com/zjunet/DropMessage)\]

**Taoran Fang**, Zhiqing Xiao, Chunping Wang, Jiarong Xu, Xuan Yang, Yang Yang

Our proposed DropMessage unifies random dropping methods on graphs, and it alleviates over-smoothing, over-fitting and non-robustness issues on GNN models.

</div>
</div>

<!-- - [Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet](https://github.com), A, B, C, **CVPR 2020** -->



# 📖 Educations

- *2021.09 - 2026.06*, Ph.D. in Computer Science and Technology, Zhejiang University, Hangzhou, Zhejiang.
- *2017.09 - 2021.06*, Bachelor in Software Engineering, Zhejiang University, Hangzhou, Zhejiang.
- *2014.09 - 2017.06*, Hangzhou No.2 High School, Hangzhou, Zhejiang.

<!-- - *2019.06 - 2022.04 (now)*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2015.09 - 2019.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  -->

# 💬 Invited Talks

- *2023.02*, Invited talk for the distinguished paper. \[[Video](https://www.bilibili.com/video/BV1GR4y1v7E8/?spm_id_from=333.337.search-card.all.click&vd_source=5edc8a1c662d1ebbae05ea71bbf93cf1)\] 
- *2023.10*, Report on graph pre-training. \[[Video](https://www.bilibili.com/video/BV1LN4y1k7Ze/?spm_id_from=333.1387.search.video_card.click&vd_source=5edc8a1c662d1ebbae05ea71bbf93cf1)\] 
- *2024.6*, Report on GraphTCM. \[[Video](https://www.bilibili.com/video/BV1sx4y1b7ST/?spm_id_from=333.1387.search.video_card.click&vd_source=5edc8a1c662d1ebbae05ea71bbf93cf1)\] 


<!-- - *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/) -->

# 💻 Internships
- *2020.03 - 2020.11*, Designing and developing [Volcano Engine](https://www.volcengine.com/), Bytedance.

<br><br>
<footer>
  <p>&copy; Taoran(Terry) Fang. Homepage style from <a href="https://github.com/RayeRen/acad-homepage.github.io/tree/main">AcadHomepage</a>.</p>
</footer>
<br><br>
