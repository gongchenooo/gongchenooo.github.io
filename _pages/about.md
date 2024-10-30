---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<style>
.pubtitle{
    background: #BD666D;
    color: white;
    font-size: 13.5px;
    padding: 1px 5px 1px 5px;
    border-radius: 10px;
    float: left;
    font-weight: bold;
}
.font-bold{
    font-weight:bold;
}
</style>


{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

I am currently a 3rd-year Ph.D. student at [Shanghai Jiao Tong University (SJTU)](https://en.sjtu.edu.cn/), co-advised by [Prof. Zhenzhe Zheng](https://zhengzhenzhe220.github.io/) and [Prof. Fan Wu](https://www.cs.sjtu.edu.cn/~fwu/). 
Prior to that, I received my Bachelor degree in Computer Science from SJTU, 2022.

My research interest focuses on edge computing in mobile networks. 
Specifically, I am interested in designing *<u>efficient and effective data utilization pipelines</u>* for resource-constrained devices to support data-efficient on-device machine learning.

# 📖 Educations
- *2022.09 - Now*, Ph.D. Candidate, Department of Computer Science and Engineering, Shanghai Jiao Tong University. 
- *2018.09 - 2022.06*, IEEE Honored Class (major in computer science), Shanghai Jiao Tong University. 

<span class='anchor' id='publications'></span>

# 📝 Publications 

- <div class="pubtitle">Preprint</div> &nbsp; <b>Understanding and Optimizing Feature Extraction Latency of On-Device Machine Learning.</b> <br /> <u>Chen Gong</u>, Zhenzhe Zheng, Fan Wu, Yiliu Chen, Sheng Wang, Guihai Chen. <br /> <i>Under Review</i>. 

- <div class="pubtitle">Preprint</div> &nbsp; <b>A Two-Stage Data Selection Framework for On-Device Model Training.</b> <br /> <u>Chen Gong</u>, Zhenzhe Zheng, Fan Wu, Guihai Chen. <br /> <i>Under Review</i>. <br /> [[pdf](https://gongchenooo.github.io/assets/pdf/Preprint-Titan.pdf)] 

- <div class="pubtitle">MobiCom'24</div> &nbsp; <b>Delta: A Cloud-assisted Data Enrichment Framework for On-Device Continual Learning.</b> <br /> <u>Chen Gong</u>, Zhenzhe Zheng, Fan Wu, Guihai Chen. <br /> <i>ACM International Conference on Mobile Computing and Networking, 2024</i>. <br /> <u>CCF-A</u>, Acceptance Rate=20.8% (103/494), <u>Presentation</u> <br /> [[pdf](https://gongchenooo.github.io/assets/pdf/MobiCom24-Delta-Paper.pdf) | [code](https://github.com/gongchenooo/MobiCom24-Delta) | [slides]() | [video]()]

- <div class="pubtitle">TON'24</div> &nbsp; <b>ODE: An Online Data Selection Framework for Federated Learning in Mobile Network.</b> <br /> <u>Chen Gong</u>, Zhenzhe Zheng, Fan Wu, Yunfeng Shao, Bingshuai Li, Guihai Chen. <br /> <i>IEEE/ACM Transactions on Networking, 2024</i>. <br /> <u>CCF-A</u> <br /> [[html](https://ieeexplore.ieee.org/abstract/document/10478325) | [pdf](https://gongchenooo.github.io/assets/pdf/TON24-ODE-Paper.pdf) | [code](https://github.com/gongchenooo/WWW23-ODE)]

- <div class="pubtitle">WWW'23</div> &nbsp; <b>To Store or Not? Online Data Selection for Federated Learning with Limited Storage.</b> <br /> <u>Chen Gong</u>, Zhenzhe Zheng, Fan Wu, Yunfeng Shao, Bingshuai Li, Guihai Chen. <br /> <i>ACM International World Wide Web Conference, 2023</i>. <br /> <u>CCF-A</u>, Acceptance Rate=19.2% (365/1900), <u>Presentation</u> <br /> [[html](https://dl.acm.org/doi/abs/10.1145/3543507.3583426) | [pdf](https://gongchenooo.github.io/assets/pdf/WWW23-ODE-Paper.pdf) | [code](https://github.com/gongchenooo/WWW23-ODE) | [slides](https://gongchenooo.github.io/assets/pdf/WWW23-ODE-Slides.pdf) | [video](https://www.youtube.com/watch?v=h9feBNoxLMo)]

- <div class="pubtitle">MM'23</div> &nbsp; <b>Fine-Grained Music Plagiarism Detection: Revealing Plagiarists through Bipartite Graph Matching and a Comprehensive Large-Scale Dataset.</b> <br /> Wenxuan Liu, Tianyao He, <u>Chen Gong</u>, Ning Zhang, Hua Yang, Junchi Yan. <br /> <i>ACM International Conference on Multimedia, 2023.</i>  <br /> <u>CCF-A</u>, Acceptance Rate=24.6% (902/3669), <u>Poster</u><br /> [[html](https://dl.acm.org/doi/abs/10.1145/3581783.3611831) | [pdf](https://gongchenooo.github.io/assets/pdf/MM23-BMMDet-Paper.pdf) | [code](https://github.com/xuan301/BMMDet_MPDSet)]

- <div class="pubtitle">DASFAA'21</div> &nbsp; <b>Modeling Dynamic Social Behaviors with Time-Evolving Graphs for User Behavior Predictions.</b> <br /> Tianzi Zang, Yanmin Zhu, <u>Chen Gong</u>, Haobing Liu, Bo Li. <br /> <i>International Conference on Database Systems for Advanced Applications, 2021.</i> <br /> <u>CCF-B</u> <br /> [[html](https://link.springer.com/chapter/10.1007/978-3-030-73194-6_35)] 


# 💻 Internships
- *2021.09 - 2022.09*, Huawei - Noah’s Ark Lab, Beijing, China.  "Federated Learning on Heterogeneous Edge Devices (面向异构多终端的联邦学习技术)", **优秀结题**.
- *2024.06 - Now*, ByteDance - App Infra - Client AI, Hangzhou, China. "Optimizing Data Storage and Preprocessing on Mobile Devices (终端侧用户数据存储和加工优化)", **Work in Progress**.
