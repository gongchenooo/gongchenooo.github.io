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

I am currently a 3rd-year Ph.D. candidate at [Shanghai Jiao Tong University (SJTU)](https://en.sjtu.edu.cn/), supervised by [Prof. Zhenzhe Zheng](https://zhengzhenzhe220.github.io/) and [Prof. Fan Wu](https://www.cs.sjtu.edu.cn/~fwu/). 
Before that, I received my Bachelor degree in Computer Science from SJTU, 2022.

My research interest focuses on on-device machine learning system. 
Specifically, I am interested in designing efficient and effective data utilization/processing systems for resource-constrained devices to support data-efficient on-device learning.

# 📖 Educations
- *2022.09 - Now*, Ph.D. Candidate, Department of Computer Science and Engineering, Shanghai Jiao Tong University. 
- *2018.09 - 2022.06*, IEEE Honored Class (major in computer science), Shanghai Jiao Tong University. 

<span class='anchor' id='publications'></span>

# 📝 Publications 

- <div class="pubtitle">Preprint</div> &nbsp; <b>A Two-Stage Data Selection Framework for On-Device Model Training.</b> <br /> <b>Chen Gong</b>, Zhenzhe Zheng, Fan Wu, Guihai Chen. <br /> <i>Under Review</i>. <br /> [PDF] --<font size=2>An effective & efficient data selection pipeline for on-device ML.</font>

- <div class="pubtitle">MobiCom'24</div> &nbsp; <b>Delta: A Cloud-assisted Data Enrichment Framework for On-Device Continual Learning.</b> <br /> <b>Chen Gong</b>, Zhenzhe Zheng, Fan Wu, Guihai Chen. <br /> <i>International Conference on Mobile Computing and Networking (MobiCom)</i>, 2024. <font color="DarkRed"> Acceptance=20.8%.</font> <font color="DarkRed">[CCF-A]</font> <br /> [<a href="https://github.com/gongchenooo/gongchenooo.github.io/blob/main/images/MobiCom24_Delta.pdf" target="_blank">PDF</a> | [Code](https://github.com/gongchenooo/MobiCom24-Delta)] --<font size=2>A private & efficient data enrichment framework for on-device continual ML.</font>

- <div class="pubtitle">TON'24</div> &nbsp; <b>[ODE: An Online Data Selection Framework for Federated Learning in Mobile Network](https://ieeexplore.ieee.org/abstract/document/10478325).</b> <br /> <b>Chen Gong</b>, Zhenzhe Zheng, Fan Wu, Yunfeng Shao, Bingshuai Li, Guihai Chen. <br /> <i>IEEE/ACM Transactions on Networking (ToN)</i>, 2024. <font color="DarkRed">[CCF-A]</font> <br /> [[PDF](https://github.com/gongchenooo/gongchenooo.github.io/blob/main/TON24-DataSelection4FL.pdf) | [Code](https://github.com/gongchenooo/WWW23-ODE)]

- <div class="pubtitle">WWW'23</div> &nbsp; <b>[To Store or Not? Online Data Selection for Federated Learning with Limited Storage](https://dl.acm.org/doi/abs/10.1145/3543507.3583426).</b> <br /> <b>Chen Gong</b>, Zhenzhe Zheng, Fan Wu, Yunfeng Shao, Bingshuai Li, Guihai Chen. <br /> <i>ACM Web Conference (WWW), System Track</i>, 2023. <font color="DarkRed">Acceptance=19.2%.</font> <font color="DarkRed">[CCF-A]</font> <br /> [[PDF](https://github.com/gongchenooo/gongchenooo.github.io/blob/main/WWW23-ODE.pdf) | [Slides](https://github.com/gongchenooo/gongchenooo.github.io/blob/main/images/WWW23-ODE-7min.pdf) | [Video](https://www.youtube.com/watch?v=h9feBNoxLMo) | [Code](https://github.com/gongchenooo/WWW23-ODE)] -- <font size=2>A collaborative data selection system for multiple devices in FL.</font>

- <div class="pubtitle">MM'23</div> &nbsp; <b>[Fine-Grained Music Plagiarism Detection: Revealing Plagiarists through Bipartite Graph Matching and a Comprehensive Large-Scale Dataset](https://dl.acm.org/doi/abs/10.1145/3581783.3611831).</b> <br /> Wenxuan Liu, Tianyao He, <b>Chen Gong</b>, Ning Zhang, Hua Yang, Junchi Yan. <br /> <i>ACM International Conference on Multimedia (MM)</i>, 2023. <font color="DarkRed"> Acceptance=29.3%.</font> <font color="DarkRed">[CCF-A]</font> <br /> [[PDF](https://dl.acm.org/doi/abs/10.1145/3581783.3611831) | [Code](https://github.com/xuan301/BMMDet_MPDSet)] -- <font size=2>A bipartite graph matching algorithm for music plagisrism detection.</font>

- <div class="pubtitle">DASFAA'21</div> &nbsp; <b>[Modeling Dynamic Social Behaviors with Time-Evolving Graphs for User Behavior Predictions](https://link.springer.com/chapter/10.1007/978-3-030-73194-6_35).</b> <br /> Tianzi Zang, Yanmin Zhu, <b>Chen Gong</b>, Haobing Liu, Bo Li. <br /> <i>International Conference on Database Systems for Advanced Applications (DASFAA)</i>, 2021. <font color="DarkRed">[CCF-B]</font> <br /> [[PDF](https://link.springer.com/chapter/10.1007/978-3-030-73194-6_35)] 


# 💻 Internships
- *2021.09 - 2022.09*, Huawei Noah’s Ark Lab, Beijing, China.  "面向异构多终端的联邦学习技术", 优秀结题.
- *2024.06 - Now*, ByteDance - App Infra - Client AI, Hangzhou, China. "移动端用户特征构建加速"
