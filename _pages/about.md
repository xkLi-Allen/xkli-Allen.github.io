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

Currently, Xunkai Li is a third year Ph.D. student of [School of Computer Science](https://cs.bit.edu.cn) in [Beijing Institute of Technology](https://bit.edu.cn) supervised by Prof. [Rong-Hua Li](https://ronghuali.github.io/ronghuali.html). 
Prior to that, he received his B.Eng. degree in computer science department from [Shandong University](http://www.sdu.edu.cn) in June 2022. 

Since 2021, he worked with Prof. [Wentao Zhang](https://zwt233.github.io) as a research intern at the Data-centric Machine Learning (DCML) group in the [Center of Machine Learning Research](https://cmlr.pku.edu.cn/People/Faculty/5ce37bd8e3244030ae3f34e01d23e761.htm) at [Peking University (PKU)](https://www.pku.edu.cn/). 
As an active member of the team, Xunkai is the contributor of scalable graph learning system project [SGL](https://github.com/PKU-DAIR/SGL) ![GitHub Repo stars](https://img.shields.io/github/stars/PKU-DAIR/SGL?style=social) and federated graph learning system project [OpenFGL](https://github.com/xkLi-Allen/OpenFGL) ![GitHub Repo stars](https://img.shields.io/github/stars/xkLi-Allen/OpenFGL?style=social).


**Email**: cs.xunkai.li@gmail.com

**Wechat (微信)**: 18045124943

🌟 🌟 If you are interested in collaborating with me or want to have a chat, always feel free to contact me through e-mail or WeChat ：）

My research interests center on **Data-Centric Graph Intelligence**, including **Data-centric AI**, **Graph Machine Learning**, and <font color=orange>**AI4Science**</font>], with a focus on developing efficient ML solutions for structured data representation and mining. The goal of my work is to bridge the gap between theoretical advancements and practical applications in real-world industrial and scientific scenarios.

**Data-centric AI**: In recent years, the development of AI has encountered certain challenges, with many leading LLMs still being based on the Transformer architecture. Consequently, research priorities in both academia and industry are increasingly shifting from model-centric approaches to data-centric paradigms. As a result, the pivotal role of data in driving AI advancements has become more pronounced, particularly in <font color=red>Data-centric LLM Optimization</font>.

**Graph Machine Learning**: Graphs are pervasive across various domains, such as social networks (relationships), biomedicine (interactions), and recommendation systems (preferences). Graph ML, especially Graph Neural Networks (GNNs), can effectively learn from these structured data. This not only provides more effective solutions but also breaks through conventional methods, offering a novel perspective. Currently, I am particularly interested in <font color=red>Graph ML in the era of LLM</font>.

**AI4Science**: The potential of AI4Science lies in its capacity to revolutionize our understanding and transformation of the world, with profound implications across all aspects of human life. My goal is to advance the practical application of artificial intelligence in scientific domains, driving a new wave of innovation—particularly in <font color=red> Integrating Graph and LLMs into Scientific Researches</font>.

To date, I have published papers in leading international conferences on machine learning, databases, data mining, and artificial intelligence, including ICML, VLDB, ICDE, WWW, AAAI, and IJCAI. An overview of my research roadmap is as follows:

  - Data Quantity: <font color=orange>Annotation</font> [[arXiv 2025 OGA](xxx)], <font color=orange>Synthesize</font> [[arXiv 2025 GraphMaster](https://arxiv.org/abs/2504.00711)],and <font color=orange>Large-scale</font> (<font color=green>Scalability</font>) [[WWW 2024 ATP](https://arxiv.org/abs/2402.06128)] [[VLDB 2024 LightDiC](https://arxiv.org/abs/2401.11772)] [[arXiv 2025 ScaDyG](https://arxiv.org/abs/2501.16002)].

  - Data Quality: <font color=orange>Paradigm</font> (<font color=green>Directed, Hypergraph, Heterophily, and Temporal</font>) [[TKDE 2023 AHGAE](https://arxiv.org/abs/2206.08582)] [[ICDE 2024 ADPA](https://arxiv.org/abs/2312.04111)] [[WWW 2025 MAP](https://arxiv.org/abs/2501.11817)], <font color=orange>Augmentation</font> (<font color=green>Imbalance, Noise, and Out-Of-Distribution</font>) [[arXiv 2025 UltraTAG](https://arxiv.org/abs/2504.02343)] [[arXiv 2025 LLaTA](https://arxiv.org/abs/2504.02343)] [[arXiv 2025 LRW-OOD](xxx)].

  - Data Efficiency: <font color=orange>Distillation</font> (<font color=green>Coarsening, Sparsification, Condensation, and Pruning</font>) [[VLDB 2025 GEC](https://www.vldb.org/pvldb/vol17/p4760-li.pdf)] [[ICML 2025 EDEN](https://arxiv.org/abs/2505.00983)], <font color=orange>Generalization</font> (<font color=green>Graph Foundation Model</font>) [[arXiv 2025 MoT](xxx)]
  
  - Data Privacy: <font color=orange>Federated</font> [[VLDB 2023 FedGTA](https://arxiv.org/abs/2401.11755)] [[IJCAI 2024 FedTAD](http://arxiv.org/abs/2404.14061)] [[ICDE 2024 AdaFGL](https://arxiv.org/abs/2401.11750)] [[IJCAI 2025 FedGM](https://arxiv.org/abs/2505.02573)] [[VLDB 2025 OpenFGL](https://arxiv.org/abs/2408.16288)] [[arXiv 2025 FedPG](https://arxiv.org/abs/2504.09493)] [[arXiv 2025 FairFGL](https://arxiv.org/abs/2504.09963)] [[arXiv 2025 FedGKC](https://arxiv.org/abs/2501.12624)] [[arXiv 2025 FedC4](https://arxiv.org/abs/2504.14188)] [[arXiv 2025 FedGFM](xxx)] and <font color=orange>Unlearning</font> [[AAAI 2024 MEGU](https://arxiv.org/abs/2504.14188)] [[arXiv 2025 SGU](https://arxiv.org/abs/2501.11823)] [[arXiv 2025 OpenGU](https://arxiv.org/abs/2501.02728)]. 

  - Data Management: <font color=orange>Collection</font>, <font color=orange>Cleaning</font>, <font color=orange>Organization</font>, <font color=orange>Benchmark</font>

  - Data Application: <font color=orange>RAG</font>, <font color=orange>LLM Reasoning</font>, <font color=orange>Multimodal</font>, <font color=orange>Agent System</font>, and <font color=orange>AI4Science</font> (<font color=green>AI4Protein, AI4Healthcare, and AI4Social</font>)




# 🔥 News

* **2025-05**: One paper is accepted by ***ICML 2025***.
* **2025-04**: One paper is accepted by ***IJCAI 2025***.
* **2025-01**: One paper is accepted by ***TKDE 2025***.
* **2025-01**: One paper is accepted by ***WWW 2025***.
* **2025-01**: One paper is accepted by ***VLDB 2025***.
* **2024-08**: One paper is accepted by ***VLDB 2025***.
* **2024-04**: One paper is accepted by ***IJCAI 2024***.
* **2024-03**: One paper is accepted by ***ICDE 2024***.
* **2024-02**: One paper is accepted by ***VLDB 2024***.
* **2024-01**: One paper is accepted by ***WWW 2024***.
* **2023-12**: One paper is accepted by ***AAAI 2024***.
* **2023-10**: One paper is accepted by ***ICDE 2024***.
* **2023-08**: One paper is accepted by ***VLDB 2023***.




# 📝 Publications 

## First/Co-first Author
<!-- #### Conference and Journal Publications -->

\# indicates equal contribution

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICML 2025</div><img src='images/papers/eden.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

🎯<img src='https://img.shields.io/badge/ICML2025-orange'/> [Toward Data-centric Directed Graph Learning: An Entropy-driven Approach](https://arxiv.org/abs/2505.00983), **[[Code](https://github.com/xkLi-Allen/EDEN)]**

**Xunkai Li**, Zhengyu Wu, Kaichi Yu, Hongchao Qin, Guang Zeng, Rong-Hua Li, Guoren Wang

- International Conference on Machine Learning (ICML), 2025, CCF-A.

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">WWW 2025</div><img src='images/papers/map.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

🎯<img src='https://img.shields.io/badge/WWW2025-orange'/> [Toward Effective Digraph Representation Learning: A Magnetic Adaptive Propagation based Approach](https://arxiv.org/abs/2501.11817), **[[Code](https://github.com/xkLi-Allen/MAP)]**

**Xunkai Li**, Daohan Su, Zhengyu Wu, Guang Zeng, Hongchao Qin, Rong-Hua Li, Guoren Wang

- The Web Conference (WWW), 2025, CCF-A.

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">VLDB 2025</div><img src='images/papers/openfgl.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

🎯<img src='https://img.shields.io/badge/VLDB2025-orange'/> [OpenFGL: A Comprehensive Benchmark for Federated Graph Learning](https://arxiv.org/abs/2408.16288), **[[Code](https://github.com/xkLi-Allen/OpenFGL)]**

**Xunkai Li**, Yinlin Zhu, Boyang Pang, Guochen Yan, Yeyu Yan, Zening Li, Zhengyu Wu, Wentao Zhang, Rong-Hua Li, Guoren Wang

- International Conference on Very Large Data Bases (VLDB), 2025, CCF-A.

</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICDE 2024</div><img src='images/papers/adafgl.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

🎯<img src='https://img.shields.io/badge/ICDE2024-orange'/> [AdaFGL: A New Paradigm for Federated Node Classification with Topology Heterogeneity](https://arxiv.org/abs/2401.11750), **[[Code](https://github.com/xkLi-Allen/AdaFGL)]**

**Xunkai Li**, Zhenyu Wu,  Wentao Zhang, Henan Sun, Rong-Hua Li, Gouren Wang

- IEEE International Conference on Data Engineering (ICDE), 2024, CCF-A.

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">AAAI 2024</div><img src='images/papers/megu.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

🎯<img src='https://img.shields.io/badge/AAAI2024-orange'/> [Towards Effective and General Graph Unlearning via Mutual Evolution](https://arxiv.org/abs/2401.11760), **[[Code](https://github.com/xkLi-Allen/MEGU)]**

**Xunkai Li**\#, Yulin Zhao\#, Zhengyu Wu, Wentao Zhang, Rong-Hua Li, Gouren Wang

- Association for the Advancement of Artificial Intelligence (AAAI), 2024, CCF-A.
- 🎉🎉 Oral Presentation

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">WWW 2024</div><img src='images/papers/atp.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

🎯<img src='https://img.shields.io/badge/WWW2024-orange'/> [Rethinking Node-wise Propagation for Large-scale Graph Learning](https://arxiv.org/abs/2402.06128), **[[Code](https://github.com/xkLi-Allen/ATP)]**

**Xunkai Li**, Jingyuan Ma, Zhengyu Wu, Daohan Su, Wentao Zhang, Rong-Hua Li, Guoren Wang

- The Web Conference (WWW), 2024, CCF-A.
- 🎉🎉 Oral Presentation

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">VLDB 2024</div><img src='images/papers/lightdic.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

🎯<img src='https://img.shields.io/badge/VLDB2024-orange'/> [LightDiC: A Simple yet Effective Approach for Large-scale Digraph Representation Learning](https://arxiv.org/abs/2401.11772), **[[Code](https://github.com/xkLi-Allen/LightDiC)]**

**Xunkai Li**, Meihao Liao, Zhengyu Wu, Daohan Su, Wentao Zhang, Rong-Hua Li, Guoren Wang

- International Conference on Very Large Data Bases (VLDB), 2024, CCF-A.

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICDE 2024</div><img src='images/papers/adpa.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

🎯<img src='https://img.shields.io/badge/ICDE2024-orange'/> [Breaking the Entanglement of Homophily and Heterophily in Semi-supervised Node Classification](https://arxiv.org/abs/2312.04111), **[[Code](https://github.com/xkLi-Allen/AMUD-ADPA)]**

Henan Sun\#, **Xunkai Li**\#, Zhengyu Wu, Daohan Su, Rong-Hua Li, Gouren Wang

- IEEE International Conference on Data Engineering (ICDE), 2024, CCF-A.

</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">VLDB 2023</div><img src='images/papers/fedgta.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

🎯<img src='https://img.shields.io/badge/VLDB2023-orange'/> [FedGTA: Topology-aware Averaging for Federated Graph Learning](https://arxiv.org/abs/2401.11755), **[[Code](https://github.com/xkLi-Allen/FedGTA)]**

**Xunkai Li**, Zhenyu Wu, Wentao Zhang, Yinlin Zhu, Rong-Hua Li, Guoren Wang

- International Conference on Very Large Data Bases (VLDB), 2023, CCF-A.

</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">NCAA 2023</div><img src='images/papers/ehgcn.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

<img src='https://img.shields.io/badge/NCAA2023-orange'/> [Effective Hybrid Graph and Hypergraph Convolution Network for Collaborative Filtering](https://link.springer.com/article/10.1007/s00521-022-07735-y) **[[code](https://github.com/RonghuiGuo/EHGCN)]**

**Xunkai Li**\#, Ronghui Guo\#, Jianwen Chen, Youpeng Hu, Meixia Qu, Bin Jiang

- Neural Computing & Applications (NCAA) 2023, CCF-C.

</div>
</div>





## Co-author

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IJCAI 2025</div><img src='images/papers/ijcai_zhanghao.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

🎯<img src='https://img.shields.io/badge/IJCAI2025-orange'/> [Rethinking Federated Graph Learning: A Data Condensation Perspective](https://arxiv.org/abs/2505.02573), **[[Code](https://github.com/xkLi-Allen/FedGM)]**

Hao Zhang, **Xunkai Li**, Yinlin Zhu, Lianglin Hu

- International Joint Conference on Artificial Intelligence (IJCAI), 2025, CCF-A.

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TKDE 2025</div><img src='images/papers/sgl_survey.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

🎯<img src='https://img.shields.io/badge/TKDE2025-orange'/> [Acceleration Algorithms in GNNs: A Survey](https://arxiv.org/abs/2405.04114)

Lu Ma, Zeang Sheng, **Xunkai Li**, Xinyi Gao, Zhezheng Hao, Ling Yang, Wentao Zhang, Bin Cui

- IEEE Transactions on Knowledge and Data Engineering (TKDE) 2025, CCF-A.

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">VLDB 2025</div><img src='images/papers/gec.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

🎯<img src='https://img.shields.io/badge/VLDB2025-orange'/> [Topology-preserving Graph Coarsening: An Elementary Collapse-based Approach](https://www.vldb.org/pvldb/vol17/p4760-li.pdf), **[[Code](https://github.com/Shiina-Mashiro-M/GEC)]**

Yuchen Meng, Rong-Hua Li, Longlong Lin, **Xunkai Li**, Gouren Wang

- International Conference on Very Large Data Bases (VLDB), 2025, CCF-A.

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IJCAI 2024</div><img src='images/papers/fedtad.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

🎯<img src='https://img.shields.io/badge/IJCAI2024-orange'/> [FedTAD: Topology-aware Data-free Knowledge Distillation for Subgraph Federated Learning](http://arxiv.org/abs/2404.14061), **[[Code](https://github.com/xkLi-Allen/FedTAD)]**

Yinlin Zhu, **Xunkai Li**, Zhengyu Wu, Di Wu, Miao Hu, Rong-Hua Li

- International Joint Conference on Artificial Intelligence (IJCAI), 2024, CCF-A.

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TKDE 2023</div><img src='images/papers/ahgae.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

🎯<img src='https://img.shields.io/badge/TKDE2023-orange'/> [Adaptive Hypergraph Auto-Encoder for Relational Data Clustering](https://arxiv.org/abs/2206.08582) **[[code](https://github.com/RonghuiGuo/EHGCN)]**

Youpeng Hu, **Xunkai Li**, Yujie Wang, Yixuan Wu, Yining Zhao, Chenggang Yan, Jian Yin, Yue Gao

- IEEE Transactions on Knowledge and Data Engineering (TKDE) 2023, CCF-A.

</div>
</div>

🎯<img src='https://img.shields.io/badge/NN2023-orange'/> [LoyalDE: Improving The Performance of Graph Neural Networks with Loyal Node Discovery and Emphasis](https://www.sciencedirect.com/science/article/pii/S0893608023002678)

Haotong Wei, Yinlin Zhu, **Xunkai Li**, Bin Jiang

- Neural Networks (NN) 2023, CCF-B.

🎯<img src='https://img.shields.io/badge/IS2022-orange'/> [Handling Information Loss of Graph Convolutional Networks in Collaborative Filtering](https://www.sciencedirect.com/science/article/pii/S0306437922000448)

Xin Xiong, **Xunkai Li**, Youpeng Hu, Yixuan Wu, Jian Yin

- Knowledge and Information Systems (IS) 2022, CCF-B.


🎯<img src='https://img.shields.io/badge/KAIS2022-orange'/> [Graph Relation Embedding Network for Click-through Rate Prediction](https://link.springer.com/article/10.1007/s10115-022-01714-4)

Yixuan Wu, Youpeng Hu, Xin Xiong, **Xunkai Li**, Ronghui Guo, Shuiguang Deng

- Knowledge and Information Systems (KAIS) 2022, CCF-B.

<!-- # 🎖 Honors and Awards

* Academic Awards
  * **KDD 2024** Student Travel Award

* Scholarship(Selected)
  * National Scholarship (Two Times): **2020** and **2021**
  * Cao Jianyou Student Award: **2022**
  * National Scholarship for Encouragement: **2022**
  * Provincial Outstanding Graduates: **2023** -->


# 📖 Educations
- *2022.09 - 2028.06 (expected)*, Ph.D. in Computer Science, Beijing Institute of Technology (BIT)

- *2018.09 - 2022.06*, B. Eng in Computer Science, Shandong University (SDU)



# 💬 Invited Talks

- *2024.08*, Oral presentation at IJCAI 2024 about our paper: '*FedTAD: Topology-aware Data-free Knowledge Distillation for Subgraph Federated Learning*'. 
- *2024.05*, Oral presentation at WWW 2024 about our paper: '*Rethinking Node-wise Propagation for Large-scale Graph Learning*'. 
- *2024.05*, Oral presentation at ICDE 2024 about our paper: '*Breaking the Entanglement of Homophily and Heterophily in Semi-supervised Node Classification*' and '*AdaFGL: A New Paradigm for Federated Node Classification with Topology Heterogeneity*'. 
- *2024.02*, Oral presentation at AAAI 2024 about our paper: '*Towards Effective and General Graph Unlearning via Mutual Evolution*'. 



# 🧑‍💻 Service

- Conference Reviewers: 
  - ICML, ICLR, NeurIPS, KDD, WWW, AISTATS, AAAI, IJCAI
- Journal Reviewers: 
  - TKDE, TKDD, TNNLS, TBD
  

# 💻 Internships
- Research Intern
  - Company/Institution: The Hong Kong University of Science and Technology, Guangzhou.
  - Advisor: Prof. Jia Li
  - Employment period: From 3/2025 to the present
- Research Intern
  - Company/Institution: Ant Group, Alibaba, Beijing.
  - Advisor: Researcher Guang Zeng
  - Employment period: From 12/2024 to the present
- Research Intern
  - Company/Institution: Large Language Model Center, IAAR, Shanghai.
  - Advisor: Dr. Zhiyu Li
  - Employment period: From 06/2024 to the present
- Research Intern
  - Company/Institution: DCML Group, Peking University
  - Advisor: Prof. Wentao Zhang
  - Employment period: From 10/2021 to the present
- Research Intern
  - Company/Institution: iMoon Lab, Tsinghua University
  - Advisor: Prof. Yue Gao
  - Employment period: From 06/2020 to 06/2021