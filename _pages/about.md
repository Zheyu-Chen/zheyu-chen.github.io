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

Hello, my name is Zheyu Chen. Currently, I am a Research Assistant at ASTAPLE Lab of The Hong Kong Polytechnic University, working under the supervision of Prof. Haibo Hu. I recently completed my Master's degree in Electronic and Information Engineering at the same university's Faculty of Electrical and Electronic Engineering. Prior to this, I earned dual Bachelor's degrees through a joint program between University College Dublin (UCD) and Beijing University of Technology (BJUT), graduating with First-Class Honours from UCD and an Honours degree from BJUT in Software Engineering.
My primary research interests lie in data mining, particularly in the field of recommender systems. Specifically, I focus on cutting-edge topics such as multimodal recommendation and group-based recommendation.

[//]: # ([中文版链接]&#40;about_zh.md&#41;)

[//]: # (I have published more than 5 papers at the top international AI conferences with total <a href='https://scholar.google.com/citations?user=Tj6-6lYAAAAJ'>google scholar citations <strong><span id='total_cit'>20+</span></strong></a>.)

# 📝 Publications





<div class='paper-box'><div class='paper-box-image'><div><div class="badge">SIGIR 25</div><img src='images/WeightedGCL.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
[Squeeze and Excitation: A Weighted Graph Contrastive Learning for Collaborative Filtering]()





**<u>Zheyu Chen</u>**, Jinfeng Xu, Yutong Wei, Ziyue Peng,

Paper <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>

- A critical problem in existing GCL-based models is the irrational allocation of feature attention. This problem limits the model's ability to effectively leverage crucial features, resulting in suboptimal performance. To address this, we propose a Weighted Graph Contrastive Learning framework (WeightedGCL). <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>

</div>
</div>





<div class='paper-box'><div class='paper-box-image'><div><div class="badge">SIGIR 25</div><img src='images/COHESION.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
[COHESION: Composite Graph Convolutional Network with Dual-Stage Fusion for Multimodal Recommendation]()





Jinfeng Xu, **<u>Zheyu Chen</u>**, Wei Wang, Xiping Hu, Sang-Wook Kim, Edith Ngai,

Paper <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>

- Modality fusion and representation learning were considered as two independent processes in previous work. In this paper, we reveal that these two processes are complementary and can support each other. Specifically, powerful representation learning enhances modality fusion, while effective fusion improves representation quality. Stemming from these two processes, we introduce a **CO**mposite grapH convolutional n**E**twork with dual-stage fu**SION** for the multimodal recommendation, named COHESION. <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>

</div>
</div>





<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICASSP 25</div><img src='images/RedNnD.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
[Don't Lose Yourself: Boosting Multimodal Recommendation via Reducing Node-neighbor Discrepancy in Graph Convolutional Network](https://ieeexplore.ieee.org/abstract/document/10887910)





**<u>Zheyu Chen</u>**, Jinfeng Xu, Haibo Hu,

[**Paper**](RedNnD.pdf) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>

- To address the over-smoothing problem, we propose a novel model that retains the personalized information of ego nodes during feature aggregation by Reducing Node-neighbor Discrepancy (RedN^nD). [**[Code]**](https://github.com/Zheyu-Chen/RedNnD) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>

</div>
</div>







<div class='paper-box'><div class='paper-box-image'><div><div class="badge">AAAI 25</div><img src='images/MENTOR.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
[MENTOR: Multi-level Self-supervised Learning for Multimodal Recommendation](https://arxiv.org/abs/2402.19407)




Jinfeng Xu, **<u>Zheyu Chen</u>**, Shuo Yang, Jinze Li, Hewei Wang, Edith C-H Ngai,

[**Paper**](MENTOR.pdf) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>

- To this end, we propose a Multi-level sElf-supervised learNing for mulTimOdal Recommendation (MENTOR) method to address the label sparsity problem and the modality alignment problem. [**[Code]**](https://github.com/Jinfeng-Xu/MENTOR) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>

</div>
</div>



<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CIKM 24</div><img src='images/AlignGroup.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
[AlignGroup: Learning and Aligning Group Consensus with Member Preferences for Group Recommendation](https://dl.acm.org/doi/abs/10.1145/3627673.3679697)


Jinfeng Xu, **<u>Zheyu Chen</u>**, Jinze Li, Shuo Yang, Hewei Wang, Edith C. H. Ngai,

[**Paper**](AlignGroup.pdf) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>

- Group activities are important behaviors in human society, providing personalized recommendations for groups is referred to as the group recommendation task. [**[Code]**](https://github.com/Jinfeng-Xu/AlignGroup) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>

</div>
</div>



<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TCE 24</div><img src='images/PTMCF.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
[Improving Consumer Experience With Pre-Purify Temporal-Decay Memory-Based Collaborative Filtering Recommendation for Graduate School Application](https://ieeexplore.ieee.org/abstract/document/10552423)


Jinfeng Xu, **<u>Zheyu Chen</u>**, Zixiao Ma, Jiyi Liu, Edith C. H. Ngai,

[**Paper**](PTMCF.pdf) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>

- The Internet is booming with information, and it has become especially difficult for consumers to sift through the information. Recommendation systems can effectively enhance the consumer experience. <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>

</div>
</div>








- [A Review of Gray-scale Image Recoloring Methods With Neural Network Based Model](Recoloring.pdf), Yuyang Wang, Tianli Ren, Zhuoyi Zhang, **<u>Zheyu Chen</u>**, Jinfeng Xu, Zixiao Ma, Pai Zhu, Mingjia Zhang, **ICIVC 22**



# 📝 Preprint

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">arXiv</div><img src='images/FourierKAN-GCF.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
[FourierKAN-GCF: Fourier Kolmogorov-Arnold Network -- An Effective and Efficient Feature Transformation for Graph Collaborative Filtering](https://arxiv.org/abs/2406.01034)



Jinfeng Xu, **Zheyu Chen**, Jinze Li, Shuo Yang, Wei Wang, Xiping Hu, Edith C-H Ngai,

[**Paper**](FourierKAN-GCF.pdf) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>

- Graph Collaborative Filtering (GCF) has achieved state-of-the-art performance for recommendation tasks. <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>

</div>
</div>



# 📑 Academic Services

- 2025 IEEE International Conference on Acoustics, Speech, and Signal Processing *(ICASSP 2025)*
- 2025 IEEE International Joint Conference on Neural Networks *(IJCNN 2025)*

# 🎓 Educations
- *2025.04 - 2025.08*, Hong Kong Polytechnic University. **Research Assistant** at *ASTAPLE Lab*
- *2023.09 - 2025.03*, Hong Kong Polytechnic University. **Master of Science** Major in *Electronic and Information Engineering* 
- *2019.09 - 2023.07*, Beijing University of Technology & University College Dublin. **Bachelor of Science** Major in *Software Engineering*