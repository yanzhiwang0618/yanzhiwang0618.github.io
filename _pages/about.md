---
permalink: /
title: "About me"
excerpt: "About me"
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

I'm **Yanzhi Wang (王衍之)**, a third year PHD student at the [College of Engineering](https://www.coe.pku.edu.cn), [Peking University](https://www.pku.edu.cn), fortunate to be advised by [Prof. Jie Song](https://www.coe.pku.edu.cn/teaching/industrial/9972.html)([Google Scholar]()) and [Prof. Jianxiao Wang](http://bda.pku.edu.cn/info/1082/2535.htm)([Google Scholar](https://scholar.google.com/citations?user=fmmLFTUAAAAJ&hl=en&oi=ao)). My research interests include **data centric AI**, **data-driven optimization**, **energy systems** and **uncertainty estimation**. You can find my [Google Scholar](https://scholar.google.com/citations?user=ohvS_NAAAAAJ&hl=en) profile here.

**Recently, my research centers on advancing the interpretability of data science within energy systems.**  I am particularly interested in leveraging AI and data-driven methodologies to implement end-to-end optimization. My current work emphasizes enhancing the reliability and efficiency of energy systems under uncertainty through data-centric decision-making.

I am actively seeking academic exchanges for next year. You can find my CV here: [[PDF](../assets/Resumey-1.pdf)]

# 🔥 News
- *2025.2*: &nbsp;🛩️🛩️ Heading to Princeton as a VSCR this autumn!
- *2024.10*: &nbsp;🛩️🛩️ Going to Seattle for INFORMS 2024!

<span id="publications-article"></span>
# 📝 Publications (Article)

<div class='paper-box'>
  <div class='paper-box-image' style="display: flex">
    <div>
      <img src='images/Nexus_1.png' alt="sym" width="80%">
    </div>
  </div>
<div class='paper-box-text' markdown="1">

- **[Nexus]** [Bridging Prediction and Decision: Advances and Challenges in Data-Driven Optimization](https://www.cell.com/nexus/fulltext/S2950-1601(25)00004-X#editor-highlights-abstract)

  **Yanzhi Wang**, Jianxiao Wang\*, Haoran Zhang, Jie Song\* (2025)

  [[PDF](../assets/Nexus.pdf)]

- Analyzed frameworks for integrating prediction and decision-making.
- Compared advancements in multidimensional data-driven optimizations
- Addressed challenges in data input, modeling, and decision processes
- Highlighted applications in power systems, management, and control
</div>
</div>

<div class='paper-box'>
  <div class='paper-box-image' style="display: flex">
    <div>
      <img src='images/TII.png' alt="sym" width="80%">
    </div>
  </div>
<div class='paper-box-text' markdown="1">


- **[IEEE Transactions on Industrial Informatics]** [Data Purification for Improved Power Dispatch Against Renewable Uncertainty](https://ieeexplore.ieee.org/document/10924409)

  **Yanzhi Wang**, Jianxiao Wang, Jie Song\* (2025)

  [[PDF](../assets/TII.pdf)]

</div>
</div>


<div class='paper-box'>
  <div class='paper-box-image' style="display: flex">
    <div>
      <img src='images/Patterns_cover.png' alt="sym" width="40%">
      <img src='images/Patterns_GA.png' alt="sym" width="55%">
    </div>
  </div>
<div class='paper-box-text' markdown="1">

**[Patterns]**[Unveiling Value Patterns via Deep Reinforcement Learning in Heterogeneous Data Analytics (Cover of the May 2024 Issue)](https://www.cell.com/patterns/fulltext/S2666-3899(24)00073-4)

**Yanzhi Wang**, Jianxiao Wang\*, Feng Gao, Jie Song\* (2024)

[[PDF](../assets/Patterns-paper.pdf)]

- We introduce a learning-based paradigm for data valuation across scenarios.
- Our study identifies varying effects of high/low-quality data on model efficacy.
- This method explores inherent and transferable value patterns across datasets.
- Analysis reveals data value’s geographic sensitivity in nationwide power forecasts.
</div>
</div>

<div class='paper-box'>
  <div class='paper-box-image' style="display: flex">
    <div>
      <img src='images/figure_1.jpg' alt="sym" width="80%">
    </div>
  </div>
<div class='paper-box-text' markdown="1">


- **[IEEE Transactions on Industry Applications]** [Dissecting Renewable Uncertainty via Deconstructive Analysis-Based Data Valuation](https://ieeexplore.ieee.org/abstract/document/10488718)

  **Yanzhi Wang**, Jie Song\* (2024)

  [[PDF](../assets/TIA.pdf)]

</div>
</div>

- **[Management Review (In Chinese)]** [Research on the Circulation and Revenue Sharing Mechanisms of Data Elements: An Example of Integrating Meteorological Data in Wind Power Scenarios](http://123.57.61.11/jweb_glpl/CN/abstract/abstract3018.shtml), **Yanzhi Wang**, Jingsi Huang, Jianxiao Wang, Feng Gao, Jie Song\* (2024)

  [[PDF]](../assets/数据要素流通与收益分配机制...以风电场景融合气象数据为例_王衍之.pdf)

- **[Chinese Journal of Management Science (In Chinese)]** [Research on Data Value Based on Demand Forecast of Online Medical Platform](http://www.zgglkx.com/CN/10.16381/j.cnki.issn1003-207x.2022.0562), Zhao Yue, **Yanzhi Wang**, Jingsi Huang, Jie Song\*, Xuan He (2024)

  [[PDF](../assets/需求预测视角下的医疗数据价值——基于沙普利值方法_赵越.pdf)]

# 📝 Publications (Conference)

<div class='paper-box'>
  <div class='paper-box-image' style="display: flex">
    <div>
      <img src='images/IAS.png' alt="sym" width="80%">
    </div>
  </div>
<div class='paper-box-text' markdown="1">

- **[IAS 2024]** [Feature Valuation Toward Improved State Estimation for Automotive Lithium-ion Battery]()

  **Yanzhi Wang**, Jianxiao Wang*, Jie Song

  [[PDF](../assets/IAS24.pdf)]

</div>
</div>

- **[CASE 2022]** [What Drives Patients to Choose a Physician Online? A Study based on Tree Models and SHAP Values](https://ieeexplore.ieee.org/abstract/document/9926467)

  **Yanzhi Wang**, Yue Zhao, Jie Song*, Hongju Liu

  [[PDF](../assets/CASE.pdf)]

# 📝 Manuscripts under submission 

- [Data-Centric Optimization: An End-to-End Strategy for Power Systems]()

  **Yanzhi Wang**, Jianxiao Wang\*, Jie Song\* (Accepted by *Engineering*)

- [Feature Selection for Battery Lifetime Prediction using Explainable Machine Learning]()

  **Yanzhi Wang**, Jianxiao Wang\*, ..., Jie Song\* (Accepted by *IEEE Transactions on Industry Applications*)

- [Condensed Data Acquisition for Non-Intrusive Load Monitoring via Household Selection]()

   YiHang Jin, **Yanzhi Wang**, Jianxiao Wang\*, et al. (Submitted to *CSEE Jornal of Power and Energy Systems*)

# 🎖 Honors and Awards
- *2024.10* The Youth Talent Support Program of the China Association for Science and Technology (Doctoral Program) 
- *2024.09* National Scholarship
- *2024.06* Wei-Ming PhD Scholars (One of 13 recipients selected university-wide)
- *2024.05* Academic Rising Star (One of 5 recipients selected college-wide)
- *2022.01* Outstanding Undergraduate Research Award (College level)

# 📖 Educations
- *2022.09 - now*, **Ph.D. in Industrial and Systems Engineering** (*GPA=3.75*), College of Engineering, Peking University, Beijing, China.
- *2019.09 - 2022.07*, **B.E. in Economics**, National School of Development, Peking University, Beijing, China.
- *2018.09 - 2022.07*, **B.E. in Theoretical and Applied Mechanics** (*GPA=3.62*), College of Engineering, Peking University, Beijing, China.
- *2015.06 - 2018.07*, RDFZ, Beijing, China.

# 🧩 Skills
- Programming: *Python*,  *MATLAB*, *R*.
- Academic Training: *Advanced Theory of Probability*, *Advanced Operations Research*, *Optimization Methods in Machine Learning*, *Reinforcement Learning*, *Distributed Optimization*, *Design and Analysis of Algorithms*, *Carbon Neutrality and Energy Internet*, etc.
  
# 💬 Invited Talks
- *2022.04*, Physician word-of-mouth ratings in complex models, 2022 International Conference for Chinese Scholars in Industrial Engineering
  
# 💻 Internships
- *2022.07 - 2022.08*, [Beijing International Big Data Exchange](), China.
