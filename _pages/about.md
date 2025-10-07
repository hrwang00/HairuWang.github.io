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
# 👋 About Me

Hi, everyone! I earned my bachelor’s degree at Harbin Institute of Technology in 2023. In the same year, I joined the School of Computer Science at USTC for my master's degree. Currently, I am a third-year M.S. candidate jointly supervised by Prof. [Prof. Xike Xie](http://staff.ustc.edu.cn/~xkxie/) and [Prof. S. Kevin Zhou](https://scholar.google.com/citations?user=8eNm2GMAAAAJ&hl=en).

Please don’t hesitate to reach out for any discussion. You can contact me via Email: hrwang00@mail dot ustc dot edu dot cn. I am always open to engaging in intriguing research endeavors! 😊

# 📝 Research Interests:

My research interests include NNs' memory, Large Language Models, LLM efficiency, and RAG.

🎯 **Teaching NNs to memorize data streams & Learnable Large-Scale Data Compression.**

1. <span style="color:#002FA7;">**[ICLR 2024 Spotlight]**</span>  Mayfly: a Neural Data Structure for Graph Stream Summarization. <span>   [link](https://openreview.net/pdf?id=n7Sr8SW4bn)</span>
2. <span style="color:#002FA7;">**[TPAMI24]**</span>  Learning to Sketch: A Neural Approach to Item Frequency Estimation in Streaming Data. <span> [link](https://ieeexplore.ieee.org/abstract/document/10499867/) </span>
3. <span style="color:#002FA7;">**[ICML 2025]**</span>  Lego Sketch: A Scalable Memory-augmented Neural Network for Sketching Data Streams. <span> [link](https://openreview.net/forum?id=GPSmbdTZBm) </span>

🎯 **LLM Efficiency.**

1. <span style="color:#002FA7;">**[EMNLP 2024 Main]**</span> Pruning via Merging: Compressing LLMs via Manifold Alignment Based Layer Merging.  [link](https://arxiv.org/abs/2406.16330)
2. <span style="color:#002FA7;">**[EMNLP 2025 findings]**</span> SkewRoute: Training-Free LLM Routing for Knowledge Graph Retrieval-Augmented Generation via Score Skewness.  [link](https://arxiv.org/pdf/2505.23841)
    *We propose the first LLM routing method for KG-RAG, based on the observation of a strong correlation between query difficulty and the skewness of the RAG retrieval score distribution.*

🎯 **RAG in LLMs.**


1. <span style="color:#002FA7;">**[ACL 2025 findings]**</span> FRAG: A Flexible Modular Framework for Retrieval-Augmented Generation based on Knowledge Graphs <span> [link](https://arxiv.org/abs/2501.09957)</span>
2. <span style="color:#BEBEBE;">**[arXiv]**</span>  Path Pooling: Training-Free Structure Enhancement for Efficient Knowledge Graph Retrieval-Augmented Generation. [link](https://arxiv.org/abs/2503.05203)


# 📖 Education
- *2023.09 - 2026.06*, Master in Computer Science and Technology, University of Science and Technology of China (USTC).
- *2019.09 - 2023.06*, Bachelor in Software Engineering, Harbin Institute of Technology (HIT).
