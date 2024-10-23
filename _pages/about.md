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
Specifically, I am interested in designing *efficient and effective data utilization pipelines* for resource-constrained devices to support data-efficient on-device machine learning.

# 📖 Educations
- *2022.09 - Now*, Ph.D. Candidate, Department of Computer Science and Engineering, Shanghai Jiao Tong University. 
- *2018.09 - 2022.06*, IEEE Honored Class (major in computer science), Shanghai Jiao Tong University. 

<span class='anchor' id='publications'></span>

# 📝 Publications 

- <div class="pubtitle">Preprint</div> &nbsp; <b>Understanding and Optimizing Feature Extraction Latency of On-Device Machine Learning .</b> <br /> <b>Chen Gong</b>, Zhenzhe Zheng, Fan Wu, Yiliu Chen, Sheng Wang, Guihai Chen. <br /> <i>Under Review</i>. 

- <div class="pubtitle">Preprint</div> &nbsp; <b>A Two-Stage Data Selection Framework for On-Device Model Training.</b> <br /> <b>Chen Gong</b>, Zhenzhe Zheng, Fan Wu, Guihai Chen. <br /> <i>Under Review</i>. <br /> [[Pdf](https://gongchenooo.github.io/assets/pdf/Preprint-Titan.pdf)] 

- <div class="pubtitle">MobiCom'24</div> &nbsp; <b>Delta: A Cloud-assisted Data Enrichment Framework for On-Device Continual Learning.</b> <br /> <b>Chen Gong</b>, Zhenzhe Zheng, Fan Wu, Guihai Chen. <br /> <i>ACM International Conference on Mobile Computing and Networking, 2024 (ACM MobiCom)</i>. <br /> <u>CCF-A</u>, Acceptance Rate=20.8% (103/494), <u>Presentation</u> <br /> [[Pdf](https://gongchenooo.github.io/assets/pdf/MobiCom24-Delta-Paper.pdf) | [Code](https://github.com/gongchenooo/MobiCom24-Delta) | [Slides]() | [Video]()]

- <div class="pubtitle">TON'24</div> &nbsp; <b>[ODE: An Online Data Selection Framework for Federated Learning in Mobile Network](https://ieeexplore.ieee.org/abstract/document/10478325).</b> <br /> <b>Chen Gong</b>, Zhenzhe Zheng, Fan Wu, Yunfeng Shao, Bingshuai Li, Guihai Chen. <br /> <i>IEEE/ACM Transactions on Networking, 2024 (IEEE/ACM TON)</i>. <br /> <u>CCF-A</u> <br /> [[Pdf](https://gongchenooo.github.io/assets/pdf/TON24-ODE-Paper.pdf) | [Code](https://github.com/gongchenooo/WWW23-ODE)]

- <div class="pubtitle">WWW'23</div> &nbsp; <b>[To Store or Not? Online Data Selection for Federated Learning with Limited Storage](https://dl.acm.org/doi/abs/10.1145/3543507.3583426).</b> <br /> <b>Chen Gong</b>, Zhenzhe Zheng, Fan Wu, Yunfeng Shao, Bingshuai Li, Guihai Chen. <br /> <i>ACM International World Wide Web Conference, System Track, 2023 (ACM WWW)</i>. <br /> <u>CCF-A</u>, Acceptance Rate=19.2% (365/1900), <u>Presentation</u> <br /> [[Pdf](https://gongchenooo.github.io/assets/pdf/WWW23-ODE-Paper.pdf) | [Code](https://github.com/gongchenooo/WWW23-ODE) | [Slides](https://gongchenooo.github.io/assets/pdf/WWW23-ODE-Slides.pdf) | [Video](https://www.youtube.com/watch?v=h9feBNoxLMo)]

- <div class="pubtitle">MM'23</div> &nbsp; <b>[Fine-Grained Music Plagiarism Detection: Revealing Plagiarists through Bipartite Graph Matching and a Comprehensive Large-Scale Dataset](https://dl.acm.org/doi/abs/10.1145/3581783.3611831).</b> <br /> Wenxuan Liu, Tianyao He, <b>Chen Gong</b>, Ning Zhang, Hua Yang, Junchi Yan. <br /> <i>ACM International Conference on Multimedia, 2023. (ACM MM)</i>  <br /> <u>CCF-A</u>, Acceptance Rate=24.6% (902/3669), <u>Poster</u><br /> [[Pdf](https://gongchenooo.github.io/assets/pdf/MM23-BMMDet-Paper.pdf) | [Code](https://github.com/xuan301/BMMDet_MPDSet)]

- <div class="pubtitle">DASFAA'21</div> &nbsp; <b>[Modeling Dynamic Social Behaviors with Time-Evolving Graphs for User Behavior Predictions](https://link.springer.com/chapter/10.1007/978-3-030-73194-6_35).</b> <br /> Tianzi Zang, Yanmin Zhu, <b>Chen Gong</b>, Haobing Liu, Bo Li. <br /> <i>International Conference on Database Systems for Advanced Applications, 2021. (DASFAA)</i> <br /> <u>CCF-B</u> <br /> [[Pdf](https://link.springer.com/chapter/10.1007/978-3-030-73194-6_35)] 


# 💻 Internships
- *2021.09 - 2022.09*, Huawei - Noah’s Ark Lab, Beijing, China.  "面向异构多终端的联邦学习技术", **优秀结题**.
- *2024.06 - Now*, ByteDance - App Infra - Client AI, Hangzhou, China. "移动端用户特征构建加速", ***Work in Progress*.
