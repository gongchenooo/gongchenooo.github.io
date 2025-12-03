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
    border-radius: 9px;
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

I'm currently a Ph.D. student at [Shanghai Jiao Tong University (SJTU)](https://en.sjtu.edu.cn/), advised by [Prof. Zhenzhe Zheng(郑臻哲)](https://zhengzhenzhe220.github.io/) and [Prof. Fan Wu(吴帆)](https://www.cs.sjtu.edu.cn/~fwu/). 

My research interest focuses on *<u>Data-Centric Edge AI</u>*. Specifically, I have focused on optimizing data processing pipelines for on-device maching learning (e.g., efficiency of user data logging, feature computation and sample utilization).

# 📖 Educations
- *2022.09 - Now*, Ph.D. Student, School of Computer Science, Shanghai Jiao Tong University. 
- *2018.09 - 2022.06*, Computer Science (IEEE Honored Class), Shanghai Jiao Tong University.


# 📝 Publications 

## First-Author Papers

- <div class="pubtitle">ACM SIGMETRICS'26</div> &nbsp; <b>[Optimizing Storage Overhead of User Behavior Log for ML-embedded Mobile Apps](https://dl.acm.org/doi/10.1145/3771575).</b> <br /> <u><b>Chen Gong</b></u>, Yan Zhuang, Zhenzhe Zheng, Yiliu Chen, Sheng Wang, Fan Wu, Guihai Chen. <br /> <i>Proceedings of the ACM on Measurement and Analysis of Computer Systems.</i> Acceptance rate=21.4% (24/112, summer round) <br /> [[paper](https://gongchenooo.github.io/assets/pdf/SigMetrics26-AdaLog-Paper.pdf) | slides]

- <div class="pubtitle">ACM/IEEE SenSys'26</div> &nbsp; <b>Optimizing Feature Extraction for On-Device Model Inference with User Behavior Sequences.</b> <br /> <u><b>Chen Gong</b></u>, Zhenzhe Zheng, Yiliu Chen, Sheng Wang, Fan Wu, Guihai Chen. <br /> <i>ACM/IEEE International Conference on Embedded Artificial Intelligence and Sensing Systems.</i> Acceptance rate=18.6% (48/257, 1st Round). <br /> [paper | slides] 

- <div class="pubtitle">ACM KDD'25</div> &nbsp; <b>[A Two-Stage Data Selection Framework for Data-Efficient Model Training on Edge Devices](https://dl.acm.org/doi/10.1145/3711896.3736823).</b> <br /> <u><b>Chen Gong</b></u>, Rui Xing, Zhenzhe Zheng, Fan Wu. <br /> <i>Proceedings of the 31st ACM SIGKDD Conference on Knowledge Discovery and Data Mining.</i> Acceptance rate=18.3% (365/1988). <br /> [[paper](https://gongchenooo.github.io/assets/pdf/KDD25_Titan_Paper.pdf) | [slides](https://gongchenooo.github.io/assets/pdf/KDD25_Titan_Slides.pdf) | [video](https://www.youtube.com/watch?v=EUFR-620Q6A&list=PLn0nrSd4xjjaUNjqud2rogfEv-5fQK4go&index=78) | [poster](https://gongchenooo.github.io/assets/pdf/KDD25_Titan_Poster.pdf)]

- <div class="pubtitle">ACM MobiCom'24</div> &nbsp; <b>[Delta: A Cloud-assisted Data Enrichment Framework for On-Device Continual Learning](https://dl.acm.org/doi/10.1145/3636534.3690701).</b> <br /> <u><b>Chen Gong</b></u>, Zhenzhe Zheng, Fan Wu, Xiaofeng Jia, Guihai Chen. <br /> <i>Proceedings of the 30th Annual International Conference on Mobile Computing and Networking. </i> Acceptance rate=19.0% (55/288). <br /> [[paper](https://gongchenooo.github.io/assets/pdf/MobiCom24-Delta-Paper.pdf) | [slides](https://gongchenooo.github.io/assets/pdf/MobiCom24-Delta-Slides.pdf) | [code](https://github.com/gongchenooo/MobiCom24-Delta)]

- <div class="pubtitle">IEEE/ACM TON'24</div> &nbsp; <b>[ODE: An Online Data Selection Framework for Federated Learning in Mobile Network](https://ieeexplore.ieee.org/document/10478325).</b> <br /> <u><b>Chen Gong</b></u>, Zhenzhe Zheng, Fan Wu, Yunfeng Shao, Bingshuai Li, Guihai Chen. <br /> <i>IEEE/ACM Transactions on Networking, Volume:32 Issue:4.</i> <br /> [[paper](https://gongchenooo.github.io/assets/pdf/TON24-ODE-Paper.pdf) | [code](https://github.com/gongchenooo/WWW23-ODE) | [appendix](https://gongchenooo.github.io/assets/pdf/TON24-ODE-Appendix.pdf)]

- <div class="pubtitle">ACM WWW'23</div> &nbsp; <b>[To Store or Not? Online Data Selection for Federated Learning with Limited Storage](https://dl.acm.org/doi/10.1145/3543507.3583426).</b> <br /> <u><b>Chen Gong</b></u>, Zhenzhe Zheng, Fan Wu, Yunfeng Shao, Bingshuai Li, Guihai Chen. <br /> <i>Proceedings of the ACM Web Conference 2023.</i> Acceptance rate=19.2% (365/1900). <br /> [[paper](https://gongchenooo.github.io/assets/pdf/WWW23-ODE-Paper.pdf) | [slides](https://gongchenooo.github.io/assets/pdf/WWW23-ODE-Slides.pdf) | [code](https://github.com/gongchenooo/WWW23-ODE) | [video](https://www.youtube.com/watch?v=h9feBNoxLMo)]

## Other Papers

- <div class="pubtitle">ACM WWW'25</div> &nbsp; <b>[Enabling Real-Time Inference in Online Continual Learning via Device-Cloud Collaboration](https://dl.acm.org/doi/10.1145/3696410.3714796).</b> <br /> Haibo Liu, <u><b>Chen Gong</b></u>, Zhenzhe Zheng, Shengzhong Liu, Fan Wu. <br /> <i>Proceedings of the ACM on Web Conference 2025.</i> Acceptance rate=19.8% (409/2062). <br /> [[paper](https://gongchenooo.github.io/assets/pdf/WWW25_ELITE_Paper.pdf) | [poster](https://gongchenooo.github.io/assets/pdf/WWW25_ELITE_Poster.pdf)]

- <div class="pubtitle">ACM MM'23</div> &nbsp; <b>[Fine-Grained Music Plagiarism Detection: Revealing Plagiarists through Bipartite Graph Matching and a Comprehensive Large-Scale Dataset](https://dl.acm.org/doi/10.1145/3581783.3611831).</b> <br /> Wenxuan Liu, Tianyao He, <u><b>Chen Gong</b></u>, Ning Zhang, Hua Yang, Junchi Yan. <br /> <i>Proceedings of the 31st ACM International Conference on Multimedia.</i> Acceptance rate=29.3% (902/3078). <br /> [[paper](https://gongchenooo.github.io/assets/pdf/MM23-BMMDet-Paper.pdf) | [code](https://github.com/xuan301/BMMDet_MPDSet) ]

- <div class="pubtitle">DASFAA'21</div> &nbsp; <b>[Modeling Dynamic Social Behaviors with Time-Evolving Graphs for User Behavior Predictions](https://link.springer.com/chapter/10.1007/978-3-030-73194-6_35).</b> <br /> Tianzi Zang, Yanmin Zhu, <u><b>Chen Gong</b></u>, Haobing Liu, Bo Li. <br /> <i>International Conference on Database Systems for Advanced Applications.</i> <br />

# 🎖 Honors and Awards
- National Scholarship of China, Ministry of Education, 2024
- Outstanding Graduate Student, Shanghai Jiao Tong University (SJTU), 2022
- CCF Elite Collegiate Award, China Computer Federation (CCF), 2021

# 💻 Internships
- *2021.09 - 2022.09*, "Federated Learning on Heterogeneous Edge Devices (异构终端联邦学习技术)", Huawei - Noah’s Ark Lab, Beijing, China. *Excellent Completion (优秀结题)*.
- *2024.06 - 2025.06*, "Optimizing Data Storage and Feature Extraction in Mobile Apps (移动应用日志存储和特征计算优化)", ByteDance - App Infra - Client AI, Hangzhou, China. 
