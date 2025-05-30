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

I am currently a 3rd-year Ph.D. student at [Shanghai Jiao Tong University (SJTU)](https://en.sjtu.edu.cn/), co-advised by [Prof. Zhenzhe Zheng(郑臻哲)](https://zhengzhenzhe220.github.io/) and [Prof. Fan Wu(吴帆)](https://www.cs.sjtu.edu.cn/~fwu/). 

My research interest focuses on *Mobile/Edge Computing*. Specifically, I am interested in building *<u>efficient data preparation pipelines</u>* for machine learning on mobile/edge devices, including data logging, feature extraction, sample selection, model training/inference optimization.

# 📖 Educations
- *2022.09 - Now*, Ph.D. Student, Department of Computer Science and Engineering, Shanghai Jiao Tong University. 
- *2018.09 - 2022.06*, Computer Science (IEEE Honored Class), Shanghai Jiao Tong University. 

<span class='anchor' id='publications'></span>

# 📝 Publications 

## 2025

- <div class="pubtitle">ACM SIGKDD'25</div> &nbsp; <b>[A Two-Stage Data Selection Framework for Data-Efficient Model Training on Edge Devices]().</b> <br /> <u><b>Chen Gong</b></u>, Rui Xing, Zhenzhe Zheng, Fan Wu. <br /> <i>Proceedings of the 31st ACM SIGKDD International Conference on Knowledge Discovery & Data Mining (KDD'25).</i> <br /><b><font color="#BD666D">CCF-A</font>.</b> Acceptance rate = 18.4% (365/1988).  <br /> [[paper](https://gongchenooo.github.io/assets/pdf/KDD25_Titan_Paper.pdf) | [slides]()]

- <div class="pubtitle">ACM WWW'25</div> &nbsp; <b>[Enabling Real-Time Inference in Online Continual Learning via Device-Cloud Collaboration](https://dl.acm.org/doi/10.1145/3696410.3714796).</b> <br /> Haibo Liu, <u><b>Chen Gong</b></u>, Zhenzhe Zheng, Shengzhong Liu, Fan Wu. <br /> <i>Proceedings of the ACM Web Conference 2025 (WWW'25).</i> <br /><b><font color="#BD666D">CCF-A.</font></b> Acceptance rate = 19.8% (409/2062).<br /> [[paper](https://gongchenooo.github.io/assets/pdf/WWW25_ELITE_Paper.pdf) | [poster](https://gongchenooo.github.io/assets/pdf/WWW25_ELITE_Poster.pdf)]

## 2024
- <div class="pubtitle">ACM MobiCom'24</div> &nbsp; <b>[Delta: A Cloud-assisted Data Enrichment Framework for On-Device Continual Learning](https://dl.acm.org/doi/10.1145/3636534.3690701).</b> <br /> <u><b>Chen Gong</b></u>, Zhenzhe Zheng, Fan Wu, Xiaofeng Jia, Guihai Chen. <br /> <i>The 30th Annual International Conference on Mobile Computing and Networking (ACM MobiCom'24).</i> <br /> <b><font color="#BD666D">CCF-A.</font></b> Acceptance rate = 19.0% (55/288, winter round). <br /> [[paper](https://gongchenooo.github.io/assets/pdf/MobiCom24-Delta-Paper.pdf) | [code](https://github.com/gongchenooo/MobiCom24-Delta) | [slides](https://gongchenooo.github.io/assets/pdf/MobiCom24-Delta-Slides.pdf) | [full version](https://gongchenooo.github.io/assets/pdf/MobiCom_Delta_fullversion.pdf)]

- <div class="pubtitle">IEEE/ACM TON'24</div> &nbsp; <b>[ODE: An Online Data Selection Framework for Federated Learning in Mobile Network](https://ieeexplore.ieee.org/document/10478325).</b> <br /> <u><b>Chen Gong</b></u>, Zhenzhe Zheng, Fan Wu, Yunfeng Shao, Bingshuai Li, Guihai Chen. <br /> <i>IEEE/ACM Transactions on Networking (TON), VOL. 32, NO. 4, August 2024.</i> <br /> <b><font color="#BD666D">CCF-A.</font></b> <br /> [[paper](https://gongchenooo.github.io/assets/pdf/TON24-ODE-Paper.pdf) | [code](https://github.com/gongchenooo/WWW23-ODE) | [appendix](https://gongchenooo.github.io/assets/pdf/TON24-ODE-Appendix.pdf)]

## 2023
- <div class="pubtitle">ACM WWW'23</div> &nbsp; <b>[To Store or Not? Online Data Selection for Federated Learning with Limited Storage](https://dl.acm.org/doi/10.1145/3543507.3583426).</b> <br /> <u><b>Chen Gong</b></u>, Zhenzhe Zheng, Fan Wu, Yunfeng Shao, Bingshuai Li, Guihai Chen. <br /> <i>Proceedings of the ACM Web Conference 2023 (WWW'23).</i> <br /> <b><font color="#BD666D">CCF-A.</font></b> Acceptance rate = 19.2% (365/1900). <br /> [[paper](https://gongchenooo.github.io/assets/pdf/WWW23-ODE-Paper.pdf) | [code](https://github.com/gongchenooo/WWW23-ODE) | [slides](https://gongchenooo.github.io/assets/pdf/WWW23-ODE-Slides.pdf) | [video](https://www.youtube.com/watch?v=h9feBNoxLMo)]

- <div class="pubtitle">ACM MM'23</div> &nbsp; <b>[Fine-Grained Music Plagiarism Detection: Revealing Plagiarists through Bipartite Graph Matching and a Comprehensive Large-Scale Dataset](https://dl.acm.org/doi/10.1145/3581783.3611831).</b> <br /> Wenxuan Liu, Tianyao He, <u><b>Chen Gong</b></u>, Ning Zhang, Hua Yang, Junchi Yan. <br /> <i>Proceedings of the 31st ACM International Conference on Multimedia (MM'23).</i> <br /><b><font color="#BD666D">CCF-A.</font></b> Acceptance rate = 29.3% (902/3078). <br /> [[paper](https://gongchenooo.github.io/assets/pdf/MM23-BMMDet-Paper.pdf) | [code](https://github.com/xuan301/BMMDet_MPDSet) ]

- <div class="pubtitle">DASFAA'21</div> &nbsp; <b>[Modeling Dynamic Social Behaviors with Time-Evolving Graphs for User Behavior Predictions](https://link.springer.com/chapter/10.1007/978-3-030-73194-6_35).</b> <br /> Tianzi Zang, Yanmin Zhu, <u><b>Chen Gong</b></u>, Haobing Liu, Bo Li. <br /> <i>International Conference on Database Systems for Advanced Applications (DASFAA).</i> <br /><b><font color="#BD666D">CCF-B</font>.</b> <br /> [[paper](https://link.springer.com/chapter/10.1007/978-3-030-73194-6_35)] 

# 🎖 Honors and Awards
- National Scholarship of China, Ministry of Education, 2024
- Outstanding Graduate Student, Shanghai Jiao Tong University (SJTU), 2022
- CCF Elite Collegiate Award, China Computer Federation (CCF), 2021

# 💻 Internships
- *2021.09 - 2022.09*, "Federated Learning on Heterogeneous Edge Devices (异构多终端联邦学习技术)", Huawei - Noah’s Ark Lab, Beijing, China. *Excellent Completion (优秀结题)*.
- *2024.06 - Now*, "Optimizing User Data Storage and Feature Extraction in Mobile Apps (移动应用用户数据存储、处理系统优化)", ByteDance - App Infra - Client AI, Hangzhou, China. *Work in Progress*.
