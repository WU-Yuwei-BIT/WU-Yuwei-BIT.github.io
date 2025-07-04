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
/* 原有 badge 样式（保持不变） */

/* 关键修复 */
.paper-box-image {
  position: relative;  /* 让 badge 相对于此容器定位 */
}

.paper-box-image > div {
  overflow: visible !important;  /* 防止 badge 被裁剪 */
}

/* 滚动框样式 */
.publications-scrollbox {
  max-height: 600px;
  overflow-y: auto;
  padding: 10px;
  border: 1px solid #eee;
}
</style>




{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>
# Biography
Yuwei WU received the Ph.D. degree in computer science from Beijing Institute of Technology (BIT), Beijing, China, in 2014, under the supervision of Prof Yunde JIA. He is now a Tenured Associate Professor at School of Computer Science, BIT. From August 2014 to August 2016, he was a post-doctoral research fellow at Rapid-Rich Object Search (ROSE) Lab, School of Electrical and Electronic Engineering (EEE), Nanyang Technological University (NTU), Singapore, under the supervision of Prof TAN Yap Peng and Prof Junsong Yuan. He received outstanding Ph.D. Thesis award from BIT, and Distinguished Dissertation Award Nominee from China Association for Artificial Intelligence (CAAI). 

# Research Interests
**Computer Vision**: 3D Vision, Vision Language Processing, etc.

**Machine Learning**: Riemannian Optimization, Deep Learning, etc. 

# Recruitment
I am always looking for highly motivated Master and Ph.D. students who have excellent mathematic and programming skills to work on 3D vision, vision and language modeling, and Riemannian manifold analytics. Please do not hesitate to send me your CV, if you are interested in our group. (每年计划招收博士生2-3名，硕士生2名，欢迎对计算机视觉、多媒体分析、机器学习等领域研究有兴趣的同学加入课题组：[详细招生信息](../recruitment/媒体计算与智能系统实验室招生说明V5.pdf))

# News
<div style="height: 300px; overflow-y: auto; padding: 10px; background-color: white; color: black; font-family: -apple-system,BlinkMacSystemFont,'Segoe UI',Helvetica,Arial,sans-serif; line-height: 1.8;">
- *2025.06*, &nbsp;🎉🎉 One paper is accepted by ICCV2025, congratulations to Chengtang Yao.
- *2025.05*: &nbsp;🎉🎉 One paper is accepted by IJCAI 2025, congratulations to Chuanhao LI.
- *2025.01*: &nbsp;🎉🎉 One paper is accepted by ICLR 2025, congratulations to Pengxiang LI and Zhi GAO.
- *2024.12*: &nbsp;🎉🎉 Two papers are accepted by AAAI 2025, congratulations to Chuanhao LI and Mingliang ZHAI.
- *2024.09*: &nbsp;🎉🎉 Two papers are accepted by NeurIPS 2024, and one paper is accepted by EMNLP 2024, congratulations to Chuanhao LI and Pengxiang LI.
- *2024.08*: &nbsp;🎉🎉 One paper concerning stereo mathching is accepted by IEEE T-CSVT, congratulations to Pengxiang LI.
- *2024.07*: &nbsp;🎉🎉 Two papers are accepted by ECCV2024, congratulations to Jiaxi ZENG and Chuanhao LI.
- *2023.12*: &nbsp;🎉🎉 One paper is accepted by AAAI2024, congratulations to Yangkai XUE. 
- *2023.10*: &nbsp;🎉🎉 Zhi GAO received Distinguished Dissertation Award from SIGAICHINA, congratulations!
- *2023.06*: &nbsp;🎉🎉 Three papers are accepted by ICCV2023, congratulations to Chenrui SHI, Jiaxi ZENG and Chengtang YAO.
- *2023.04*: &nbsp;🎉🎉 One paper is accepted by IJCAI2023, congratulations to Mingliang ZHAI.
- *2023.03*: &nbsp;🎉🎉 Two papers are accepted by CVPR2023, congratulations to Zhi GAO and Chuanhao LI.
- *2023.01*: &nbsp;🎉🎉 Chuanhao LI and Mingliang ZHAI received the second prize in the multi-modal technology innovation competition of the first "Xingzhi Cup" National Artificial Intelligence Innovation Application Competition.
- *2022.12*: &nbsp;🎉🎉 One paper is accepted by AAAI2023, congratulations to Che SUN.
- *2022.12*: &nbsp;🎉🎉 Che SUN successfully defended his Ph.D. thesis, congratulations Dr. SUN.
- *2022.10*: &nbsp;🎉🎉 Our "Learning to Optimize on Riemannian Manifolds" paper is accepted by T-PAMI, congratulations to Zhi GAO.
- *2022.09*: &nbsp;🎉🎉 Guangdong Provincial Key Laboratory of Machine Perception and Intelligent Computing was approved. Our team has another base in Shenzhen.
- *2022.08*: &nbsp;🎉🎉 One paper is accepted by NeurIPS2022, congratulations to Zhi GAO.
- *2022.07*: &nbsp;🎉🎉 One paper is accepted by ACM MM2022, congratulations to Che SUN.
- *2022.07*: &nbsp;🎉🎉 Chenchen JING received outstanding Ph.D. Thesis award from BIT, congratulations.
- *2022.07*: &nbsp;🎉🎉 Jindou DAI received outstanding Master Thesis award from BIT, congratulations.
- *2022.06*: &nbsp;🎉🎉 Chenchen JING successfully defended his Ph.D. thesis, congratulations Dr. JING.
- *2022.04*: &nbsp;🎉🎉 Our "Curvature-Adaptive Meta-Learning" paper is accepted by T-PAMI, congratulations to Zhi GAO.
- *2022.03*: &nbsp;🎉🎉 Two papers are accepted by CVPR2022, congratulations to Che SUN and Chenchen JING.
- *2021.12*: &nbsp;🎉🎉 Two papers are accepted by AAAI2022, congratulations to Chenchen JING and Xiaomeng FAN.
- *2021.07*: &nbsp;🎉🎉 Weichao SHEN received outstanding Ph.D. Thesis award from BIT, congratulations.
- *2021.06*: &nbsp;🎉🎉 Weichao SHEN successfully defended his Ph.D. thesis, congratulations Dr. SHEN.
- *2021.06*: &nbsp;🎉🎉 One paper is accepted by ICCV2021, congratulations to Zhi GAO.
- *2021.03*: &nbsp;🎉🎉 Two papers are accepted by CVPR2021, including one oral, congratulations to Chentang YAO and Jindou DAI.
- *2020.12*: &nbsp;🎉🎉 One paper is accepted by AAAI2021, congratulations to Xiaomeng FAN.
- *2020.07*: &nbsp;🎉🎉 Two papers are accepted by ACM MM2020, congratulations to Che SUN and Chenchen JING.
- *2020.07*: &nbsp;🎉🎉 Our paper about abnormal event detection is accepted by IEEE T-MM, congratulations to Che SUN.
- *2020.06*: &nbsp;🎉🎉 Yanmei DONG successfully defended her Ph.D. thesis, congratulations Dr. DONG!
- *2020.05*: &nbsp;🎉🎉 Our paper about face spoofing detection is accepted by IEEE T-IFS, congratulations to Chengtang YAO.
- *2020.02*: &nbsp;🎉🎉 One paper concerning SPD Riemannian optimization is accepted by CVPR2020, congratulations to Zhi GAO.
- *2019.11*: &nbsp;🎉🎉 Two papers are accepted by AAAI2020, congratulations to Zhi GAO and Chenchen JING.
- *2019.11*: &nbsp;🎉🎉 Zhi GAO’s work on the SPD Manifold is accepted by IEEE Transactions on Neural Networks and Learning Systems (T-NNLS), congratulations!
- *2019.07*: &nbsp;🎉🎉 Lidong YU received outstanding Master Thesis award from BIT, congratulations!
- *2019.06*: &nbsp;🎉🎉 Lidong YU, Lijia ZHANG, and Wenji WANG successfully defended their Master thesis, congratulations!
- *2019.06*: &nbsp;🎉🎉 Weichao SHEN’s work on 3D shape reconstruction is presented at CVPR'19 as an oral paper.
- *2019.03*: &nbsp;🎉🎉 One paper is accepted by CVPR'19 as an oral paper, congratulations to Weichao SHEN.
- *2019.02*: &nbsp;🎉🎉 Two papers are published on Patter Recognition (PR), congratulations to Xingyuan BU and Zhi GAO.
</div>
# Selected Publications 

<div class="publications-scrollbox">


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICCV 2025</div><img src='images/pipeline/ICCV25_YAO.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**Diving into the Fusion of Monocular Priors for Generalized Stereo Matching**
- Chengtang Yao, Lidong Yu, Zhidan Liu, Jiaxi Zeng, **Yuwei Wu**, Yunde Jia.
- ICCV 2025
  
  [[PDF](../paper/ICCV25_YAO.pdf)] [[Project](https://github.com/YaoChengTang/Diving-into-the-Fusion-of-Monocular-Priors-for-Generalized-Stereo-Matching)]
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IJCAI 2025</div><img src='images/pipeline/IJCAI25_Li.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**Multi-Sourced Compositional Generalization in Visual Question Answering**
- Chuanhao Li, Wenbo Ye, Zhen Li, **Yuwei Wu**, Yunde Jia.
- IJCAI 2025
  
  [[PDF](../paper/IJCAI25_Li.pdf)] [[Project](https://github.com/NeverMoreLCH/MSCG/)]
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICLR 2025</div><img src='images/pipeline/ICLR2025_GAO.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**Multi-modal Agent Tuning: Building a VLM-Driven Agent for Efficient Tool Usage**
- Zhi Gao, Bofei Zhang, Pengxiang Li, Xiaojian Ma, Tao Yuan, Yue Fan, **Yuwei Wu**, Yunde Jia, Song-Chun Zhu, and Qing Li.
- ICLR 2025
  
  [[PDF](../paper/ICLR25_GAO.pdf)] [[Project](https://mat-agent.github.io/)]
</div>
</div>



<div class='paper-box'><div class='paper-box-image'><div><div class="badge">AAAI 2025</div><img src='images/pipeline/AAAI2025_LI.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**Consistency of Compositional Generalization Across Multiple Levels**
- Chuanhao Li, Zhen Li, Chenchen Jing, Xiaomeng Fan, Wenbo Ye, **Yuwei Wu**, and Yunde Jia.
- AAAI 2025
  
  [[PDF](../paper/AAAI25_LI.pdf)] [[Project](https://github.com/NeverMoreLCH/CCG)]
</div>
</div>



<div class='paper-box'><div class='paper-box-image'><div><div class="badge">AAAI 2025</div><img src='images/pipeline/AAAI2025_ZHAI.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**World Knowledge-Enhanced Reasoning Using Instruction-Guided Interactor in Autonomous Driving**
- Mingliang Zhai, Cheng Li, Zengyuan Guo, Ningrui Yang, Xiameng Qin, Sanyuan Zhao, Junyu Han, Ji Tao, **Yuwei Wu**, and Yunde Jia.
- AAAI 2025
  
  [[PDF](../paper/AAAI25_ZHAI.pdf)] [[Project](https://github.com/zmling22/KAD)]
</div>
</div>



<div class='paper-box'><div class='paper-box-image'><div><div class="badge">NeurIPS 2024</div><img src='images/pipeline/24_NIPS_LI.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**SearchLVLMs: A Plug-and-Play Framework for Augmenting Large Vision-Language Models by Searching Up-to-Date Internet Knowledge**
- Chuanhao Li, Zhen Li, Chenchen Jing, Shuo Liu, Wenqi Shao, **Yuwei Wu**, Ping Luo, Yu Qiao, and Kaipeng Zhang.
- NeurIPS 2024
  
  [[PDF](../paper/24_NIPS_LI.pdf)] [[Project](https://nevermorelch.github.io/SearchLVLMs.github.io)]
</div>
</div>



<div class='paper-box'><div class='paper-box-image'><div><div class="badge">NeurIPS 2024</div><img src='images/pipeline/NIPS2024_PENGXIANG.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**FIRE: A Dataset for Feedback Integration and Refinement Evaluation of Multimodal Models**
- Pengxiang Li, Zhi Gao, Bofei Zhang, Tao Yuan, **Yuwei Wu**, Mehrtash Harandi, Yunde Jia, Song-Chun Zhu, and Qing Li.
- NeurIPS 2024
  
  [[PDF](../paper/TCSVT2024_LI.pdf)] [[Project](https://mm-fire.github.io/)]
</div>
</div>



<div class='paper-box'><div class='paper-box-image'><div><div class="badge">EMNLP 2024</div><img src='images/pipeline/EMNLP2024_CHUANHAO.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**In-Context Compositional Generalization for Large Vision-Language Models**
- Chuanhao Li, Chenchen Jing, Zhen Li, Mingliang Zhai, **Yuwei Wu**, and Yunde Jia.
- EMNLP 2024
  
  [[PDF](../paper/24_EMNLP_LI.pdf)]
</div>
</div>



<div class='paper-box'><div class='paper-box-image'><div><div class="badge">T-CSVT 2024</div><img src='images/pipeline/TCSVT2024_PENGXIANG.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**Inter-Scale Similarity Guided Cost Aggregation for Stereo Matching**
- Pengxiang Li, Chengtang Yao, **Yuwei Wu**, and Yunde Jia.
- T-CSVT 2024
  
  [[PDF](../paper/TCSVT2024_LI.pdf)]
</div>
</div>



<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ECCV 2024</div><img src='images/pipeline/ECCV2024_ZENG.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**Temporally Consistent Stereo Matching**
- Jiaxi Zeng, Chengtang Yao, **Yuwei Wu**, and Yunde Jia.
- ECCV 2024
  
  [[PDF](../paper/ECCV2024_JIAXI.pdf)] [[Project](https://github.com/jiaxiZeng/Temporally-Consistent-Stereo-Matching)]
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ECCV 2024</div><img src='images/pipeline/ECCV2024_LI.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**Compositional Substitutivity of Visual Reasoning for Visual Question Answering**
- Chuanhao Li, Zhen Li, Chenchen Jing, **Yuwei Wu**, Mingliang Zhai, and Yunde Jia.
- ECCV 2024 

  [[PDF](../paper/ECCV2024_CHUANHAO.pdf)] [[Project](https://github.com/NeverMoreLCH/CG-SPS)]
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">AAAI 2024</div><img src='images/pipeline/AAAI2024_Xue.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**Residual Hyperbolic Graph Convolution Networks**
- Yangkai Xue, Jindou Dai, Zhipeng Lu, **Yuwei Wu**, and Yunde Jia
- AAAI 2024 
  
  [[PDF](../paper/AAAI2024_Xue.pdf)]
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICCV 2023</div><img src='images/pipeline/ICCV2023_Chenrui.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

  **Video Anomaly Detection via Sequentially Learning Multiple Pretext Tasks**
- Chenrui Shi, Che Sun, Yunde Jia, and **Yuwei Wu**
- ICCV 2023 
  
  [[PDF](../paper/ICCV2023_Chenrui.pdf)]
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICCV 2023</div><img src='images/pipeline/ICCV2023_Zeng.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
  
**Parameterized Cost Volume for Stereo Matching**
- Jiaxi Zeng, Chengtang Yao, Lidong Yu, Yunde Jia, and **Yuwei Wu**
- ICCV 2023

  [[PDF](../paper/ICCV2023_Zeng.pdf)] [[Project](https://github.com/jiaxiZeng/Parameterized-Cost-Volume-for-Stereo-Matching)]
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICCV 2023</div><img src='images/pipeline/ICCV2023_Yao.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**Sparse Point Guided 3D Lane Detection**

- Chengtang Yao, Lidong Yu, Yunde Jia, and **Yuwei Wu**
- ICCV 2023

  [[PDF](../paper/ICCV2023_Yao.pdf)] [[Project](https://github.com/YaoChengTang/Sparse-Point-Guided-3D-Lane-Detection)]
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IJCAI 2023</div><img src='images/pipeline/IJCAI2023_Zhai.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**An Efficient Hourglass Transformer with Modality-guided Dynamic Token Merge for Document Understanding**

- Mingliang Zhai, Yulin Li, Xiameng Qin, Chen Yi, Qunyi Xie, Chengquan Zhang, Kun Yao, **Yuwei Wu**, and Yunde Jia
- IJCAI 2023

  [[PDF](../paper/IJCAI2023_Zhai.pdf)]

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2023</div><img src='images/pipeline/CVPR2023_Chuanhao.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**Exploring the Effect of Primitives for Compositional Generalization in Vision-and-Language**

- Chuanhao Li, Zhen Li, Chenchen Jing, Yunde Jia, and **Yuwei Wu**
- CVPR 2023

  [[PDF](../paper/CVPR2023_Chuanhao.pdf)] [[Project](https://github.com/NeverMoreLCH/SSL2CG)]

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2023</div><img src='images/pipeline/CVPR2023_Gao.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**Exploring Data Geometry for Continual Learning**

- Zhi Gao, Chen Xu, Feng Li, Yunde Jia, Mehrtash Harandi, and **Yuwei Wu**
- CVPR 2023
  
  [[PDF](../paper/CVPR2023_Gao.pdf)]

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">AAAI 2023</div><img src='images/pipeline/AAAI2023_Sun.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**Learning Event-Relevant Factors for Video Anomaly Detection**

- Che Sun, Chenrui Shi, Yunde Jia, and **Yuwei Wu**
- AAAI 2023
  
  [[PDF](../paper/AAAI2023_Sun.pdf)]

</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">T-PAMI 2023</div><img src='images/pipeline/TPAMI2023_Gao_Curvature-Adaptive_Meta-Learning.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**Curvature-Adaptive Meta-Learning for Fast Adaptation to Non-Euclidean Data**

- Zhi Gao, **Yuwei Wu**, Mehrtash Harandi, and Yunde Jia
- T-PAMI 2023

  [[PDF](../paper/TPAMI2023_Gao_Curvature-Adaptive-Meta-Learning.pdf)]

</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">T-PAMI 2023</div><img src='images/pipeline/TPAMI2013_Gao_Learning_to_Optimize.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**Learning to Optimize on Riemannian Manifolds**

- Zhi Gao, **Yuwei Wu**, Xiaomeng Fan, Mehrtash Harandi, and Yunde Jia
- T-PAMI 2023

  [[PDF](../paper/TPAMI2023_Gao_Learning_to_Optimize.pdf)] [[Project](https://github.com/zhigao2017/learningriemannianoptimization)]

</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">NeurIPS 2022</div><img src='images/pipeline/NeuRIPS2022_Gao.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**Hyperbolic Feature Augmentation via Distribution Estimation and Infinite Sampling on Manifolds**

- Zhi Gao, **Yuwei Wu**,Yunde Jia, and Mehrtash Harandi
- NeurIPS 2022

  [[PDF](../paper/NeuRIPS2022_Gao.pdf)] [[Project](https://github.com/zhigao2017/Hyperbolic_Feature_Augmentation)]

</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACM MM 2022</div><img src='images/pipeline/ACM_MM2022_Sun.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**Evidential Reasoning for Video Anomaly Detection**

- Che Sun, Yunde Jia, and **Yuwei Wu**
- ACM MM 2022

  [[PDF](../paper/ACM_MM2022_Sun.pdf)]

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2022</div><img src='images/pipeline/CVPR2022_Sun.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**Global-Aware Registration of Less-Overlap RGB-D Scans**

- Che Sun, Yunde Jia, Yi Guo, and **Yuwei Wu**
- CVPR 2022

  [[PDF](../paper/CVPR2022_Sun.pdf)]

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2022</div><img src='images/pipeline/CVPR2022_Jing.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**Maintaining Reasoning Consistency in Compositional Visual Question Answering**

- Chenchen Jing, Yunde Jia, **Yuwei Wu**, Xinyu Liu, and Qi Wu
- CVPR 2022

  [[PDF](../paper/CVPR2022_Jing.pdf)] [[Project](https://github.com/jingchenchen/ReasoningConsistency-VQA)]

</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">AAAI 2022</div><img src='images/pipeline/AAAI2022_Fan.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**Efficient Riemannian Meta-Optimization by Implicit Differentiation**

- Xiaomeng Fan, **Yuwei Wu**, Zhi Gao, Yunde Jia, and Mehrtash Harandi
- AAAI 2022

  [[PDF](../paper/AAAI2022_Fan.pdf)] [[Project](https://github.com/XiaomengFanmcislab/I-RMM)]

</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">AAAI 2022</div><img src='images/pipeline/AAAI2022_.Jing.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**Learning the Dynamics of Visual Relational Reasoning via Reinforced Path Routing**

- Chenchen Jing, Yunde Jia, **Yuwei Wu**, Chuanhao Li, and Qi Wu
- AAAI 2022

  [[PDF](../paper/AAAI2022_.Jing.pdf)]

</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">PR 2022</div><img src='images/pipeline/PR2022_Dai.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**Infinite-dimensional feature aggregation via a factorized bilinear model**

- Jindou Dai, **Yuwei Wu**, Zhi Gao, and Yunde Jia
- PR 2022

  [[PDF](../paper/PR2022_Dai.pdf)] 

</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">T-MM 2021</div><img src='images/pipeline/TMM2021_Sun.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**Adversarial 3D Convolutional Auto-Encoder for Abnormal Event Detection in Videos**

- Che Sun, Yunde Jia, Hao Song, and **Yuwei Wu**
- T-MM 2021

  [[PDF](../paper/TMM2021_Sun.pdf)]

</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICCV 2021</div><img src='images/pipeline/ICCV2021_Gao.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**Curvature Generation in Hyperbolic Spaces for Few-Shot Learning**

- Zhi Gao, **Yuwei Wu**, Yunde Jia, and Mehrtash Harandi
- ICCV 2021

  [[pdf](../paper/ICCV2021_Gao.pdf)] [[Project](https://github.com/zhigao2017/CurvatureGeneration_FSL)]

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2021 (Oral)</div><img src='images/pipeline/CVPR2021_Dai.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**A Hyperbolic-to-Hyperbolic Graph Convolutional Network**

- Jindou Dai, **Yuwei Wu**, Zhi Gao, and Yunde Jia
- CVPR 2021

  [[PDF](../paper/CVPR2021_Dai.pdf)]

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2021</div><img src='images/pipeline/CVPR2021_Yao.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**A Decomposition Model for Stereo Matching**

- Chengtang Yao, Yunde Jia, Huijun Di, Pengxiang Li, and **Yuwei Wu**
- CVPR 2021

  [[PDF](../paper/CVPR2021_Yao.pdf)] [[Project](https://github.com/YaoChengTang/DecNet)]

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">AAAI 2021</div><img src='images/pipeline/AAAI2021_Fan.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**Learning a Gradient-free Riemannian Optimizer on Tangent Spaces**

- Xiaomeng Fan, Zhi Gao, **Yuwei Wu**, Yunde Jia, and Mehrtash Harandi
- AAAI 2021

  [[PDF](../paper/AAAI2021_Fan.pdf)] [[Project](https://github.com/XiaomengFanmcislab/Learning-a-Gradient-free-Riemannian-Optimizer-on-Tangent-Spaces)]

</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACM MM 2020</div><img src='images/pipeline/ACM_MM2020_Sun.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**Scene-Aware Context Reasoning for Unsupervised Abnormal Event Detection in Videos**

- Che Sun, Yunde Jia, Yao Hu, and **Yuwei Wu**
- ACM MM 2020

  [[PDF](../paper/ACM_MM2020_Sun.pdf)]

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACM MM 2020</div><img src='images/pipeline/ACM_MM2020_Jing.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**Visual-Semantic Graph Matching for Visual Grounding**

- Chenchen Jing, **Yuwei Wu**, Yao Hu, Yunde Jia, and Qi Wu
- ACM MM 2020

  [[PDF](../paper/ACM_MM2020_Jing.pdf)]

</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2020</div><img src='images/pipeline/CVPR2020_Gao.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**Learning to Optimize on SPD Manifolds**

- Zhi Gao, **Yuwei Wu**, Yunde Jia, and Mehrtash Harandi
- CVPR 2020

  [[PDF](../paper/CVPR2020_Gao.pdf)] [[Project](https://github.com/zhigao2017/Learning-to-optimize-on-SPD-manifolds)]

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">AAAI 2020</div><img src='images/pipeline/AAAI2020_Gao.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**Revisiting Bilinear Pooling: A Coding Perspective**

- Zhi Gao, **Yuwei Wu**, XiaoxunZhang, Jindou Dai,Yunde Jia, and Mehrtash Harandi
- AAAI 2020

  [[PDF](../paper/AAAI2020_Gao.pdf)] [[Project](https://github.com/zhigao2017/Learning-to-optimize-on-SPD-manifolds)]

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">AAAI 2020</div><img src='images/pipeline/AAAI2020_Jing.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**Overcoming Language Priors in VQA via Decomposed Linguistic Representations**

- Chenchen Jing, **Yuwei Wu**, XiaoxunZhang, Yunde Jia, and Qi Wu
- AAAI 2020

  [[PDF](../paper/AAAI2020_Jing.pdf)]

</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">T-NNLS 2020</div><img src='images/pipeline/TNNLS2020.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**A Robust Metric for Similarity-based Classification on the SPD Manifold**

- Zhi Gao, **Yuwei Wu**, Mehrtash Harandi, and Yunde Jia
- T-NNLS 2020

  [[PDF](../paper/TNNLS2020.pdf)] [[Project](https://github.com/zhigao2017/PSSSD)]

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">T-IFS 2020</div><img src='images/pipeline/TIFS2020_Yao.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**Face Spoofing Detection Using Relativity Representation on Riemannian Manifold**

- Chengtang Yao, Yunde Jia, Huijun Di, and **Yuwei Wu**
- T-IFS 2020

  [[PDF](../paper/TIFS2020_Yao.pdf)]

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2019</div><img src='images/pipeline/CVPR2019_3D_Shape_Reconstruction_from_Images_in_the_Frequency_Domain.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">


**3D Shape Reconstruction from Images in the Frequency Domain**

- Weichao Shen, **Yuwei Wu**, and Yunde Jia
- CVPR 2019 **(Oral)**

  [[PDF](../paper/CVPR2019_3D_Shape_Reconstruction_from_Images_in_the_Frequency_Domain.pdf)]

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">T-CSVT 2019</div><img src='images/pipeline/TCSVT2019_Shen.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**Robust Distracter-Resistive Tracker via Learning A Multi-component Discriminative Dictionary**

- Weichao Shen, **Yuwei Wu**, Junsong Yuan, Ling-Yu Duan, Jian Zhang, and Yunde  Jia
- T-CSVT 2019

  [[PDF](../paper/TCSVT2019_Shen.pdf)]

</div>
</div>


<div class='paper-box'>
  <div class='paper-box-image'>
    <div>
      <div class="badge">PR 2019</div>
      <img src='images/pipeline/PR2019_Xingyuan.png' alt="sym" width="100%">
    </div>
  </div>
  <div class='paper-box-text' markdown="1">

  **Deep Convolutional Network with Locality and Sparsity Constraints Texture Classification**
  
  - Xingyuan Bu, **Yuwei Wu**, Zhi Gao, and Yunde Jia
  - PR 2019

    [[PDF](../paper/PR2019_Xingyuan.pdf)] 

  </div>
</div>

<div class='paper-box'>
  <div class='paper-box-image'>
    <div>
      <div class="badge">PR 2019</div>
      <img src='images/pipeline/PR2019_Gaozhi.png' alt="sym" width="100%">
    </div>
  </div>
  <div class='paper-box-text' markdown="1">

  **Learning a Robust Representation via a Deep Network on Symmetric Positive Definite Manifolds**
  
  - Zhi Gao, **Yuwei Wu**, Xingyuan Bu, Tan Yu, Junsong Yuan, and Yunde Jia
  - PR 2019

    [[PDF](../paper/PR2019_Gaozhi.pdf)] [[Project](https://github.com/zhigao2017/Kernel-SPD-Pooling)]

  </div>
</div>

<div class='paper-box'>
  <div class='paper-box-image'>
    <div>
      <div class="badge">T-MM 2019</div>
      <img src='images/pipeline/TMM2019_Codebook-free_Compact_Descriptor_for_Scalable_Visual_Search.png' alt="sym" width="100%">
    </div>
  </div>
  <div class='paper-box-text' markdown="1">

  **A Codebook-free Compact Descriptor via Dual Selection for Visual Search**
  
  - **Yuwei Wu**, Feng Gao, Yicheng Huang, Jie Lin, Vijay Chandrasekhar, Junsong Yuan, and Ling-Yu Duan
  - T-MM 2019

    [[PDF](../paper/TMM2019_Codebook-free_Compact_Descriptor_for_Scalable_Visual_Search.pdf)]

  </div>
</div>

<div class='paper-box'>
  <div class='paper-box-image'>
    <div>
      <div class="badge">T-MM 2019</div>
      <img src='images/pipeline/TMM2019_Temporal_Action_Localization.png' alt="sym" width="100%">
    </div>
  </div>
  <div class='paper-box-text' markdown="1">

  **Temporal Action Localization in Untrimmed Videos using Action Pattern Trees**
  
  - Hao Song, Xinxiao Wu, Bing Zhu, **Yuwei Wu**, Mei Chen, and Yunde Jia
  - T-MM 2019

    [[PDF](../paper/TMM2019_Temporal_Action_Localization.pdf)]

  </div>
</div>

<div class='paper-box'>
  <div class='paper-box-image'>
    <div>
      <div class="badge">IROS 2019</div>
      <img src='images/pipeline/IROS2019.png' alt="sym" width="100%">
    </div>
  </div>
  <div class='paper-box-text' markdown="1">

  **Person-following for Telepresence Robots Using Web Cameras**
  
  - Xianda Cheng, Yunde Jia, Jingyu Su, and **Yuwei Wu**
  - IROS 2019

    [[PDF](../paper/IROS2019.pdf)]

  </div>
</div>

<div class='paper-box'>
  <div class='paper-box-image'>
    <div>
      <div class="badge">T-IP 2018</div>
      <img src='images/pipeline/TIP2018_Minimizing_Reconstruction_Bias_Hashing.png' alt="sym" width="100%">
    </div>
  </div>
  <div class='paper-box-text' markdown="1">

  **Minimizing Reconstruction Bias Hashing via Joint Projection and Quantization**
  
  - Ling-Yu Duan, **Yuwei Wu**, Yicheng Huang, Zhe Wang, Junsong Yuan, and Wen Gao
  - T-IP 2018

    [[PDF](../paper/TIP2018_Minimizing_Reconstruction_Bias_Hashing.pdf)]

  </div>
</div>

<div class='paper-box'>
  <div class='paper-box-image'>
    <div>
      <div class="badge">T-MM 2018</div>
      <img src='images/pipeline/TMM2018_Group-Sensitive_Triplet_Embedding.png' alt="sym" width="100%">
    </div>
  </div>
  <div class='paper-box-text' markdown="1">

  **Group Sensitive Triplet Embedding for Vehicle Re-identification**
  
  - Yan Bai, Yihang Lou, Feng Gao, Shiqi Wang, **Yuwei Wu**, and Ling-Yu Duan
  - T-MM 2018

    [[PDF](../paper/TMM2018_Group-Sensitive_Triplet_Embedding.pdf)]

  </div>
</div>

<div class='paper-box'>
  <div class='paper-box-image'>
    <div>
      <div class="badge">AAAI 2018</div>
      <img src='images/pipeline/AAAI2018_Deep_Stereo_Matching_with_Explicit.png' alt="sym" width="100%">
    </div>
  </div>
  <div class='paper-box-text' markdown="1">

  **Deep Stereo Matching with Explicit Cost Aggregation Sub-Architecture**
  
  - Lidong Yu, Yucheng Wang, **Yuwei Wu**, and Yunde Jia
  - AAAI 2018

    [[PDF](../paper/AAAI2018_Deep_Stereo_Matching_with_Explicit.pdf)]

  </div>
</div>

<div class='paper-box'>
  <div class='paper-box-image'>
    <div>
      <div class="badge">T-IP 2017</div>
      <img src='images/pipeline/TIP2017_A_Hybrid_Data_Association_Framework.png' alt="sym" width="100%">
    </div>
  </div>
  <div class='paper-box-text' markdown="1">

  **A Hybrid Data Association Framework for Robust Online Multi-Object Tracking**
  
  - Min Yang, **Yuwei Wu**, and Yunde Jia
  - T-IP 2017
  
    [[PDF](../paper/TIP2017_A_Hybrid_Data_Association_Framework.pdf)]

  </div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2017</div><img src='images/pipeline/CVPR2017_HOPE_Hierarchical_Object_Prototype_Encoding.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**HOPE: Hierarchical Object Prototype Encoding for Efficient Object Instance Search in Videos**

- Tan Yu, **Yuwei Wu**, Junsong Yuan
- CVPR 2017

  [[PDF](../paper/CVPR2017_HOPE_Hierarchical_Object_Prototype_Encoding_.pdf)]

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">AAAI 2017</div><img src='images/pipeline/AAAI2017_Efficient.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**Efficient Object Instance Search Using Fuzzy Objects Matching**

- Tan Yu, **Yuwei Wu**, Sreyasee Das Bhattacharjee, Junsong Yuan
- AAAI 2017

  [[PDF](https://cse.buffalo.edu/~jsyuan/papers/2017/Efficient%20Object%20Instance%20Search%20Using%20Fuzzy%20Objects%20Matching.pdf)]

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">AAAI 2017</div><img src='images/pipeline/AAAI2017_Deep_Manifold_Learning_of_Symmetric_Positive_Definite_Matrices.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**Deep Manifold Learning of Symmetric Positive Definite Matrices with Application to Face Recognition**

- Zhen Dong, Su Jia, Chi Zhang, Mingtao Pei, **Yuwei Wu**
- AAAI 2017

  [[PDF](../paper/AAAI2017_Deep_Manifold_Learning_of_Symmetric_Positive_Definite_Matrices.pdf)]

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">T-CSVT 2016</div><img src='images/pipeline/TCSVT2016_Online_Discriminative_Tracking_With_active_example_selection.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**Online Discriminative Tracking with Active Example Selection**

- Min Yang, **Yuwei Wu**, Mingtao Pei, Bo Ma, and Yunde Jia
- T-CSVT 2016

  [[PDF](https://drive.google.com/file/d/1H1TPSrGWo-mOXqj9CwPZLvHCrd7O7_nd/view)]

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">T-IP 2015</div><img src='images/pipeline/TIP2015_Robust_Discriminative_Tracking_via_Landmark-based_Label_Propagation.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**Robust Discriminative Tracking via Landmark-based Label Propagation**

- **Yuwei Wu**, Mingtao Pei, Min Yang, Junsong Yuan, and Yunde Jia
- T-IP 2015

  [[PDF](../paper/TIP2015_Robust_Discriminative_Tracking_via_Landmark-based_Label_Propagation.pdf)]

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">T-IP 2015</div><img src='images/pipeline/TIP2015_Manifold_Kernel_Sparse_Representation_of_Symmetric_Positive-Definite_Matrices_and_Its_Applications.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**Manifold kernel Sparse Representation of Symmetric Positive Definite Matrices and Its Applications**

- **Yuwei Wu**, Yunde Jia, Peihua Li, Jian Zhang, and Junsong Yuan
- T-IP 2015

  [[PDF](../paper/TIP2015_Manifold_Kernel_Sparse_Representation_of_Symmetric_Positive-Definite_Matrices_and_Its_Applications.pdf)]

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">T-ITS 2015</div><img src='images/pipeline/TITS2015_Vehicle_Type_Classification_Using_a_Semisupervised.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**Vehicle Type Classification Using Semi-Supervised Convolutional Neural Network**

- Zhen Dong, **Yuwei Wu**, Mingtao Pei, and Yunde Jia
- T-ITS 2015

  [[PDF](../paper/TITS2015_Vehicle_Type_Classification_Using_a_Semisupervised.pdf)]

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">T-CSVT 2014</div><img src='images/pipeline/TCSVT2014_Metric_Learning_based_Structural_Appearance_model_for_robust_visual_tracking.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**Metric learning based Structural Appearance Model for Robust Visual Tracking**

- **Yuwei Wu**, Bo Ma, Min Yang, Yunde Jia, and Jian Zhang
- T-CSVT 2014

  [[PDF](https://drive.google.com/file/d/1Sgnz99TFyvrDeOyYN5FISIiMNngNlTBr/view)]

</div>
</div>


</div>
 


# Teaching

- School of CS, Beijing Institute of Technology (BIT), **Digital Image Processing**, 2020-present,  1st semester

- School of CS, Beijing Institute of Technology (BIT), **Programming Methods and Practice**, 2018-present, Summer semester


# Group

## Graduate Students






<style>
.team-members-container {
    display: grid;
    grid-template-columns: repeat(3, 1fr); /* 固定三列 */
    gap: 20px;
    margin: 0 auto;
    max-width: 1200px;
    width: 100%;
}

.team-member {
    display: flex;
    flex-direction: column;
    align-items: center;
    text-align: center;
    padding: 15px;
    box-shadow: 0 2px 5px rgba(0,0,0,0.1);
    border-radius: 8px;
    width: 100%; /* 确保占满网格单元格 */
}

.team-member-photo {
    width: 150px;
    height: 150px;
    border-radius: 50%;
    object-fit: cover;
    margin-bottom: 10px;
}

/* 响应式设计 - 小屏幕调整为2列 */
@media (max-width: 900px) {
    .team-members-container {
        grid-template-columns: repeat(2, 1fr);
    }
}

/* 响应式设计 - 更小屏幕调整为1列 */
@media (max-width: 600px) {
    .team-members-container {
        grid-template-columns: 1fr;
    }
}
</style>




<!-- 第一行 -->
<div class="team-members-container">
    <div class="team-member">
        <img src="../group/chenxu.jpg" alt="" class="team-member-photo">
        <div><strong>Xu CHEN (陈旭)</strong></div>
        <div>Ph.D. student of BIT</div>
        <div>2020--</div>
    </div>  
    <div class="team-member">
        <img src="../group/huangguichen.png" alt="" class="team-member-photo">
        <div><strong>Guichen HUANG (黄贵宸)</strong></div>
        <div>Ph.D. student of BIT</div>
        <div>2021--</div>
    </div>
    <div class="team-member">
        <img src="../group/fanxiaomeng.jpg" alt="" class="team-member-photo">
        <div><strong>Xiaomeng FAN (范啸猛)</strong></div>
        <div>Ph.D. student of BIT</div>
        <div>2022--</div>
    </div>
    <div class="team-member">
        <img src="../group/guoyi.jpg" alt="" class="team-member-photo">
        <div><strong>Yi GUO (郭一)</strong></div>
        <div>Ph.D. student of BIT</div>
        <div>2022--</div>
    </div>
    <div class="team-member">
        <img src="../group/lipengxiang.jpg" alt="" class="team-member-photo">
        <div><strong>Pengxiang LI (李朋祥)</strong></div>
        <div>Ph.D. student of BIT</div>
        <div>2023--</div>
    </div>
    <div class="team-member">
        <img src="../group/zhaimingliang.jpg" alt="" class="team-member-photo">
        <div><strong>Mingliang ZHAI (翟明亮)</strong></div>
        <div>Ph.D. student of BIT</div>
        <div>2023--</div>
    </div>
    <div class="team-member">
        <img src="../group/shichenrui.jpg" alt="" class="team-member-photo">
        <div><strong>Chenrui SHI (石辰睿)</strong></div>
        <div>Ph.D. student of BIT</div>
        <div>2023--</div>
    </div>
    <div class="team-member">
        <img src="../group/zhangxintong.jpg" alt="" class="team-member-photo">
        <div><strong>Xintong ZHANG (张欣桐)</strong></div>
        <div>Ph.D. student of BIT</div>
        <div>2024--</div>
    </div>
    <div class="team-member">
        <img src="../group/lishishen.png" alt="" class="team-member-photo">
        <div><strong>Shishen LI (李世珅)</strong></div>
        <div>Ph.D. student of BIT</div>
        <div>2024--</div>
    </div>
    <div class="team-member">
        <img src="../group/lizhen.jpg" alt="" class="team-member-photo">
        <div><strong>Zhen LI (李祯)</strong></div>
        <div>Master student of BIT</div>
        <div>2023--</div>
    </div>
     <div class="team-member">
        <img src="../group/liuzhidan.jpg" alt="" class="team-member-photo">
        <div><strong>Zhidan LIU (刘志丹)</strong></div>
        <div>Master student of BIT</div>
        <div>2023--</div>
    </div>
     <div class="team-member">
        <img src="../group/lizhaoyi.jpg" alt="" class="team-member-photo">
        <div><strong>Zhaoyi LI (李昭驿)</strong></div>
        <div>Master student of BIT</div>
        <div>2023--</div>
    </div>
     <div class="team-member">
        <img src="../group/chenquan.jpg" alt="" class="team-member-photo">
        <div><strong>Quan CHEN (陈全)</strong></div>
        <div>Master student of BIT</div>
        <div>2024--</div>
    </div>
     <div class="team-member">
        <img src="../group/wuwei.jpg" alt="" class="team-member-photo">
        <div><strong>Wei WU (吴为)</strong></div>
        <div>Master student of BIT</div>
        <div>2024--</div>
    </div>
</div>





<br>

## Previous Graduate Students

<br>


<style>
.student-scrollbox {
    height: 500px;
    overflow-y: auto;
    padding: 15px;
    border-radius: 10px;
    background-color: #f8f9fa;
    box-shadow: 0 2px 10px rgba(0,0,0,0.1);
}

.student-card {
    background-color: white;
    border-radius: 8px;
    padding: 15px;
    margin-bottom: 15px;
    box-shadow: 0 1px 3px rgba(0,0,0,0.1);
    transition: transform 0.2s;
}

.student-card:hover {
    transform: translateY(-2px);
    box-shadow: 0 4px 6px rgba(0,0,0,0.1);
}

.student-name {
    font-size: 18px;
    font-weight: bold;
    color: #2c3e50;
    margin-bottom: 5px;
}

.student-info {
    font-size: 14px;
    color: #34495e;
    line-height: 1.5;
}

.student-info strong {
    color: #2c3e50;
}

.student-scrollbox::-webkit-scrollbar {
    width: 8px;
}

.student-scrollbox::-webkit-scrollbar-thumb {
    background: #bdc3c7;
    border-radius: 4px;
}

.student-scrollbox::-webkit-scrollbar-thumb:hover {
    background: #95a5a6;
}
</style>

<div class="student-scrollbox">
    <div class="student-card">
        <div class="student-name">Peilin YU (余沛霖)</div>
        <div class="student-info">
            Master student of BIT, 2025<br>
            <strong>Now:</strong> Assistant Engineer, Institute of Software, Chinese Academy of Sciences, Beijing, China
        </div>
    </div>

    <div class="student-card">
        <div class="student-name">Yangkai XUE (薛阳凯)</div>
        <div class="student-info">
            Master student of BIT, 2025<br>
            <strong>Now:</strong> Algorithm Engineer, ByteDance, Beijing, China
        </div>
    </div>

    <div class="student-card">
        <div class="student-name">Xinyu LIU (刘新宇)</div>
        <div class="student-info">
            Master student of BIT, 2025<br>
            <strong>Now:</strong> Nanrui Group Co., Ltd, Nanjing, China
        </div>
    </div>

    <div class="student-card">
        <div class="student-name">Yuchuan MAO (毛禹川)</div>
        <div class="student-info">
            Master student of BIT, 2025<br>
            <strong>Now:</strong> Ph.D. student, Nanjing University, Nanjing, China
        </div>
    </div>

    <div class="student-card">
        <div class="student-name">Jiaxi ZENG (曾嘉禧)</div>
        <div class="student-info">
            Master student of BIT, 2025<br>
            <strong>Now:</strong> Algorithm engineer, Weride, Shenzhen, China
        </div>
    </div>

    <div class="student-card">
        <div class="student-name">Dr. Chengtang YAO (姚承唐)</div>
        <div class="student-info">
            Ph.D. student of BIT, 2025<br>
            <strong>Now:</strong> Researcher, Microsoft Research Asia, Beijing, China
        </div>
    </div>

    <div class="student-card">
        <div class="student-name">Dr. Chuanhao LI (李川皓)</div>
        <div class="student-info">
            Ph.D. student of BIT, 2025<br>
            <strong>Now:</strong> Researcher, Shanghai AI Laboratory, Shanghai, China
        </div>
    </div>

    <div class="student-card">
        <div class="student-name">Dr. Zhi GAO (高志)</div>
        <div class="student-info">
            Ph.D. student of BIT, 2023<br>
            <strong>Now:</strong> Postdoc Research Fellow, Peking University, Beijing, China
        </div>
    </div>

    <div class="student-card">
        <div class="student-name">Dr. Che SUN (孙澈)</div>
        <div class="student-info">
            Ph.D. student of BIT, 2023 (co-supervised with Prof. Yunde Jia)<br>
            <strong>Now:</strong> Postdoc Research Fellow, Tsinghua University, Beijing, China
        </div>
    </div>

    <div class="student-card">
        <div class="student-name">Dr. Chenchen JING (景宸琛)</div>
        <div class="student-info">
            Ph.D. student of BIT, 2022 (co-supervised with Prof. Yunde Jia)<br>
            <strong>Now:</strong> Postdoc Research Fellow, Zhejiang University, Hangzhou, China
        </div>
    </div>

    <div class="student-card">
        <div class="student-name">Dr. Weichao SHEN (沈伟超)</div>
        <div class="student-info">
            Ph.D. student of BIT, 2021 (co-supervised with Prof. Yunde Jia)<br>
            <strong>Now:</strong> Alibaba DAMO Academy for Discovery, Beijing, China
        </div>
    </div>

    <div class="student-card">
        <div class="student-name">Wei JIANG (姜玮)</div>
        <div class="student-info">
            Master student of BIT, 2020<br>
            <strong>Now:</strong> Alibaba, Beijing, China
        </div>
    </div>

    <div class="student-card">
        <div class="student-name">Jindou DAI (戴金豆)</div>
        <div class="student-info">
            Master student of BIT, 2022<br>
            <strong>Now:</strong> Alibaba, Beijing, China
        </div>
    </div>

    <div class="student-card">
        <div class="student-name">Jingyu SU (苏静宇)</div>
        <div class="student-info">
            Master student of BIT, 2022<br>
            <strong>Now:</strong> Putian University, Putian, China
        </div>
    </div>

    <div class="student-card">
        <div class="student-name">Xiangjun GAO (高祥君)</div>
        <div class="student-info">
            Master student of BIT, 2023<br>
            <strong>Now:</strong> Ph.D. student of HKUST, Hong Kong, China
        </div>
    </div>

    <div class="student-card">
        <div class="student-name">Tianshuo MA (马天朔)</div>
        <div class="student-info">
            Master student of BIT, 2023<br>
            <strong>Now:</strong> CASIC No.3, Beijing, China
        </div>
    </div>

    <div class="student-card">
        <div class="student-name">Zhiyu YAN (晏直誉)</div>
        <div class="student-info">
            Master student of BIT, 2024<br>
            <strong>Now:</strong> Bank of Communications Co., Ltd., Shanghai, China
        </div>
    </div>
</div>