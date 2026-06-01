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

<style>
.paper-box {
  display: flex;
  align-items: flex-start;
  gap: 2rem;
  padding: 1.6rem 0;
  border-bottom: 1px solid #e6e6e6;
}

.paper-box-image {
  width: 39%;
  min-width: 260px;
}

.paper-box-image img {
  width: 100%;
  border-radius: 4px;
  box-shadow: 0 4px 14px rgba(0,0,0,0.18);
}

.paper-box-text {
  flex: 1;
  font-size: 0.98rem;
  line-height: 1.65;
}

.paper-title {
  font-size: 1.08rem;
  font-weight: 600;
}

.badge {
  display: inline-block;
  background: #0646a5;
  color: white;
  font-weight: 600;
  font-size: 0.82rem;
  padding: 0.28rem 0.75rem;
  border-radius: 2px;
  margin-bottom: 0.45rem;
}

.paper-meta {
  color: #555;
  margin-top: 0.25rem;
  margin-bottom: 0.55rem;
}

.paper-links a {
  margin-right: 0.75rem;
  font-weight: 600;
}

@media screen and (max-width: 768px) {
  .paper-box {
    flex-direction: column;
  }

  .paper-box-image {
    width: 100%;
    min-width: 0;
  }
}
</style>

<span class='anchor' id='about-me'></span>

I am **Huaixiang Li**, an undergraduate student in **Chemical Engineering** at **Kunming University of Science and Technology**. My research focuses on **heterogeneous catalysis**, with particular interests in **light alkane dehydrogenation**, **CO<sub>2</sub> conversion**, **defect-controlled metal oxide catalysts**, and **in-situ spectroscopic characterization**.

My current work centers on the rational design of non-noble metal catalysts by regulating active-site structure, surface defects, and metal–support interactions. I am especially interested in understanding how local coordination environments and electronic structures influence catalytic activity, selectivity, and long-term stability under reaction conditions.

# 🔥 News

- *2026.05*: &nbsp;Contributed to a review article on methanol as a key C1 platform molecule and its emerging applications.
- *2026.04*: &nbsp;Completed a first-author manuscript on boron-regulated Ni-based catalysts for propane dehydrogenation.
- *2025.12*: &nbsp;Participated in a mechanistic study of Ga/Al<sub>2</sub>O<sub>3</sub> catalysts for the reverse water-gas shift reaction using in-situ DRIFTS.

# 📝 Publications

<!-- 
说明：
1. TOC 图片请放到 GitHub 仓库的 /images/ 文件夹下。
2. 例如：images/ni_b_pdh_toc.png 和 images/ga_rwgs_toc.png。
3. 如果论文已有 DOI 或期刊页面，把 href="/publications/ni-b-pdh/" 改成 DOI 链接即可。
4. 如果论文暂时未上线，可以先保留内部页面链接，之后再更新为正式论文链接。
-->

<div class='paper-box'>
  <div class='paper-box-image'>
    <div>
      <div class="badge">Under Revision</div>
      <!-- TOC 图片位置：请将 Ni-B PDH 的 TOC 图放到 images/ni_b_pdh_toc.png -->
      <img src='images/ni_b_pdh_toc.png' alt="Boron-regulated Ni-based catalyst for propane dehydrogenation">
    </div>
  </div>

  <div class='paper-box-text' markdown="1">

<a class="paper-title" href="/publications/ni-b-pdh/">Boron-Regulated Ni-Based Catalysts for Stable and Selective Propane Dehydrogenation</a>

**Huaixiang Li**, Yubing Li, Hedong He, et al.

<div class="paper-meta">
Manuscript under revision
</div>

<div class="paper-links">
<a href="/publications/ni-b-pdh/">Paper Page</a>
<a href="/publications/ni-b-pdh/#toc">TOC</a>
</div>

- **Research focus:** Stabilization of highly dispersed Ni species for propane dehydrogenation.
- **Key idea:** Boron regulation modulates the electronic and geometric environment of Ni sites, helping improve propylene selectivity and suppress carbon deposition.
- **Significance:** This work provides a defect- and coordination-regulation strategy for designing stable non-noble metal catalysts under high-temperature reaction conditions.

  </div>
</div>

<div class='paper-box'>
  <div class='paper-box-image'>
    <div>
      <div class="badge">In Preparation</div>
      <!-- TOC 图片位置：请将 Ga/Al2O3 RWGS 的 TOC 图放到 images/ga_rwgs_toc.png -->
      <img src='images/ga_rwgs_toc.png' alt="Ga/Al2O3 catalyst for reverse water-gas shift reaction">
    </div>
  </div>

  <div class='paper-box-text' markdown="1">

<a class="paper-title" href="/publications/ga-rwgs/">Ga<sup>δ+</sup>–H Species Driven Reverse Water-Gas Shift Reaction over Ga/Al<sub>2</sub>O<sub>3</sub> Catalysts</a>

**Huaixiang Li**, et al.

<div class="paper-meta">
Manuscript in preparation
</div>

<div class="paper-links">
<a href="/publications/ga-rwgs/">Paper Page</a>
<a href="/publications/ga-rwgs/#toc">TOC</a>
</div>

- **Research focus:** Mechanistic investigation of Ga-based catalysts for the reverse water-gas shift reaction.
- **My contribution:** Design and analysis of in-situ DRIFTS experiments to track surface intermediates and Ga<sup>δ+</sup>–H species.
- **Significance:** The study reveals the dynamic generation and consumption of Ga<sup>δ+</sup>–H species during CO<sub>2</sub> activation, providing mechanistic insight into the high CO selectivity of Ga/Al<sub>2</sub>O<sub>3</sub> catalysts.

  </div>
</div>

# 🔬 Research Interests

- **Propane dehydrogenation:** non-noble metal catalysts, active-site isolation, coke suppression, and catalyst stability.
- **CO<sub>2</sub> conversion:** reverse water-gas shift reaction, CO<sub>2</sub> hydrogenation, and C1 chemistry.
- **Defect-controlled catalysis:** oxygen vacancies, metal–support interactions, and surface coordination regulation.
- **In-situ characterization:** in-situ DRIFTS, surface intermediate analysis, and mechanism-guided catalyst design.

# 📖 Education

- *2022.09 - Present*, **B.Eng. in Chemical Engineering**, Kunming University of Science and Technology, Kunming, China.

# 🧪 Research Skills

- **Catalyst synthesis:** supported metal catalysts, metal oxide catalysts, defect-controlled catalyst design.
- **Catalytic reactions:** propane dehydrogenation, reverse water-gas shift reaction, CO<sub>2</sub> hydrogenation.
- **Characterization:** in-situ DRIFTS, catalyst structure–performance correlation, surface intermediate analysis.
- **Scientific writing:** research manuscripts, review articles, graphical abstracts, and academic presentations.

# 📫 Contact

Please feel free to contact me for academic discussion or research collaboration in heterogeneous catalysis, light alkane dehydrogenation, CO<sub>2</sub> conversion, and in-situ spectroscopic characterization.

<!-- 
Email: your_email@example.com
Google Scholar: https://scholar.google.com/citations?user=YOUR_ID
ORCID: https://orcid.org/XXXX-XXXX-XXXX-XXXX
-->
```
