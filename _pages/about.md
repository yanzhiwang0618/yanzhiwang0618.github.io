---
permalink: /
title: "About me"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<style>
  body, h1, h2, h3, h4, h5, h6, p, div, span, li, a, table, .page__content {
    font-family: "Times New Roman", "Times", serif !important;
  }

  /* 2. 增加 # 标题的间距 */
  h1 {
    margin-top: 80px !important;    /* 这里控制标题与上一段内容的距离 (数值越大距离越大) */
    margin-bottom: 10px !important; /* 这里控制标题与下方正文的距离 */
    padding-bottom: 10px !important; /* 可选：给标题下方加一点点内部留白 */
    border-bottom: 1px solid #eaeaea; /* 可选：加一条淡淡的分割线，看着更整齐 */
  }

  /* 4. 增大左侧头像 [新增部分] */
  .author__avatar img {
    /* 默认模版通常限制在 150px 左右。修改下面的数值来调整大小。*/
    max-width: 280px !important;  /* 尝试设置为 220px，如果觉得不够大可以改成 250px 等 */
    width: 100% !important;       /* 确保图片宽度撑满容器 */
    height: auto !important;      /* 保持图片比例不变 */
  }
  
</style>

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

I'm **Yanzhi Wang (王衍之)**, a third year PHD student at the [College of Engineering](https://www.coe.pku.edu.cn), [Peking University](https://www.pku.edu.cn), fortunate to be advised by [Prof. Jie Song](https://www.coe.pku.edu.cn/teaching/industrial/9972.html)([Google Scholar]()) and [Prof. Jianxiao Wang](http://bda.pku.edu.cn/info/1082/2535.htm)([Google Scholar](https://scholar.google.com/citations?user=fmmLFTUAAAAJ&hl=en&oi=ao)). 
Prior to this, I received my Bachelor's degrees in Science and Economics from Peking University.
My research interests include **data centric AI**, **data-driven optimization**, **energy systems** and **uncertainty estimation**. You can find my [Google Scholar](https://scholar.google.com/citations?user=ohvS_NAAAAAJ&hl=en) profile here.

**Recently, my research centers on advancing the interpretability of data science within energy systems.**  I am particularly interested in leveraging AI and data-driven methodologies to implement end-to-end optimization. My current work emphasizes enhancing the reliability and efficiency of energy systems under uncertainty through data-centric decision-making.

You can find my CV here: [[PDF](../assets/Resumey-1.pdf)]

<span id="publications-article"></span>
# Publications (Article)

<div class='paper-box'>
  <div class='paper-box-image' style="display: flex">
    <div>
      <img src='images/ENG.png' alt="sym" width="80%">
    </div>
  </div>
<div class='paper-box-text' markdown="1">

- **[Engineering]** [Data-Centric Optimization: An End-to-End Strategy for Power Systems](https://www.sciencedirect.com/science/article/pii/S2095809925006095)

  **Yanzhi Wang**, Jianxiao Wang\*, Jie Song\* (2025)

  [[PDF](../assets/ENG.pdf)]

- Proposed DCOpt, a framework valuing features by their economic impact in end-to-end optimization.
- Developed a rolling-horizon algorithm that reduces decision costs by 8.9% in OOD scenarios.
- Demonstrated that curating high-value features outperforms increasing data quantity using ISO-NE data.
</div>
</div>

<div class='paper-box'>
  <div class='paper-box-image' style="display: flex">
    <div>
      <img src='images/TIA_2025.png' alt="sym" width="80%">
    </div>
  </div>
<div class='paper-box-text' markdown="1">

- **[IEEE Transactions on Industry Applications]** [Feature Selection for Battery Lifetime Prediction using Explainable Machine Learning](https://ieeexplore.ieee.org/abstract/document/11194100)

  **Yanzhi Wang**, Jianxiao Wang\*, Xi Chen, Yishen Wang, Jie Song (2025)

  [[PDF](../assets/TIA2025.pdf)]

</div>
</div>

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

- **[Patterns]**[Unveiling Value Patterns via Deep Reinforcement Learning in Heterogeneous Data Analytics (Cover of the May 2024 Issue)](https://www.cell.com/patterns/fulltext/S2666-3899(24)00073-4)

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

# Publications (Conference)

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

# Manuscripts under submission 

- [AI-Powered Data Valuation for Robust Financial Modelling]()

   **Yanzhi Wang**, Jianxiao Wang, Yaqin Hu, Jie Song, Xiaofei Zhao. (In Submission)

- [Condensed Data Acquisition for Non-Intrusive Load Monitoring via Household Selection]()

   YiHang Jin, **Yanzhi Wang**, Jianxiao Wang\*, et al. (Under Review in *CSEE Jornal of Power and Energy Systems*)

<span id="-honors-and-awards"></span>
# Honors and Awards
- *2025.09* National Scholarship
- *2025.05* Presidential Scholarship (Peking University)
- *2024.10* The Youth Talent Support Program of the China Association for Science and Technology (Doctoral Program) 
- *2024.09* National Scholarship
- *2024.06* Wei-Ming PhD Scholars (One of 13 recipients selected university-wide)
- *2024.05* Academic Rising Star (One of 5 recipients selected college-wide)
- *2022.01* Outstanding Undergraduate Research Award (College level)

<span id="-skills"></span>
# Skills
- Programming: *Python*,  *MATLAB*, *R*.
- Academic Training: *Advanced Theory of Probability*, *Advanced Operations Research*, *Optimization Methods in Machine Learning*, *Reinforcement Learning*, *Distributed Optimization*, *Design and Analysis of Algorithms*, *Carbon Neutrality and Energy Internet*, etc.

