<span class='anchor' id='about-me'></span>

<style>
:root {
  --primary: #1f4e79;
  --primary-light: #eaf2f8;
  --text-main: #1f2933;
  --text-muted: #5f6c7b;
  --card-bg: #ffffff;
  --border: #e5e7eb;
  --shadow: 0 8px 24px rgba(15, 23, 42, 0.08);
  --radius: 18px;
}

.hero-card {
  display: flex;
  align-items: center;
  gap: 32px;
  padding: 34px;
  margin: 24px 0 34px 0;
  border-radius: var(--radius);
  background: linear-gradient(135deg, #f8fbff 0%, #eef6fb 48%, #ffffff 100%);
  border: 1px solid var(--border);
  box-shadow: var(--shadow);
  flex-wrap: wrap;
}

.hero-text {
  flex: 1;
  min-width: 280px;
}

.hero-text h1 {
  margin-top: 0;
  margin-bottom: 8px;
  font-size: 2.2rem;
  color: var(--text-main);
}

.hero-subtitle {
  font-size: 1.05rem;
  color: var(--primary);
  font-weight: 600;
  margin-bottom: 16px;
}

.hero-description {
  color: var(--text-muted);
  line-height: 1.75;
  font-size: 0.98rem;
}

.hero-photo {
  flex: 0 0 210px;
  text-align: center;
}

.hero-photo img {
  width: 205px;
  height: 205px;
  object-fit: cover;
  border-radius: 50%;
  border: 6px solid #ffffff;
  box-shadow: 0 10px 28px rgba(31, 78, 121, 0.18);
}

.hero-links {
  margin-top: 18px;
  display: flex;
  gap: 10px;
  flex-wrap: wrap;
}

.btn {
  display: inline-block;
  padding: 8px 15px;
  border-radius: 999px;
  text-decoration: none;
  font-size: 0.9rem;
  font-weight: 600;
  border: 1px solid var(--primary);
}

.btn-primary {
  background: var(--primary);
  color: white !important;
}

.btn-outline {
  color: var(--primary) !important;
  background: white;
}

.section-title {
  margin-top: 42px;
  margin-bottom: 18px;
  padding-bottom: 8px;
  border-bottom: 2px solid var(--primary-light);
  color: var(--text-main);
}

.tag-container {
  display: flex;
  flex-wrap: wrap;
  gap: 10px;
  margin: 14px 0 8px 0;
}

.research-tag {
  padding: 8px 13px;
  border-radius: 999px;
  background: var(--primary-light);
  color: var(--primary);
  font-size: 0.9rem;
  font-weight: 600;
}

.news-box {
  padding: 22px 26px;
  border-radius: var(--radius);
  background: #ffffff;
  border: 1px solid var(--border);
  box-shadow: var(--shadow);
}

.news-box ul {
  margin-bottom: 0;
}

.paper-card {
  display: grid;
  grid-template-columns: 260px 1fr;
  gap: 24px;
  align-items: stretch;
  padding: 22px;
  margin: 22px 0;
  border-radius: var(--radius);
  background: var(--card-bg);
  border: 1px solid var(--border);
  box-shadow: var(--shadow);
}

.paper-image {
  position: relative;
  overflow: hidden;
  border-radius: 14px;
  background: #f3f6f8;
  min-height: 160px;
}

.paper-image img {
  width: 100%;
  height: 100%;
  min-height: 160px;
  object-fit: cover;
  display: block;
}

.badge {
  position: absolute;
  top: 12px;
  left: 12px;
  padding: 5px 11px;
  border-radius: 999px;
  background: rgba(31, 78, 121, 0.92);
  color: white;
  font-size: 0.78rem;
  font-weight: 700;
  z-index: 2;
}

.paper-content h3 {
  margin-top: 0;
  margin-bottom: 8px;
  color: var(--text-main);
  line-height: 1.35;
}

.paper-authors {
  color: var(--text-muted);
  margin-bottom: 8px;
  line-height: 1.55;
}

.paper-journal {
  color: var(--primary);
  font-weight: 600;
  margin-bottom: 12px;
}

.paper-summary {
  color: var(--text-muted);
  line-height: 1.7;
  margin-bottom: 14px;
}

.paper-links {
  display: flex;
  gap: 10px;
  flex-wrap: wrap;
}

.project-grid {
  display: grid;
  grid-template-columns: 1fr;
  gap: 18px;
}

.project-card {
  padding: 24px 26px;
  border-radius: var(--radius);
  background: #ffffff;
  border: 1px solid var(--border);
  box-shadow: var(--shadow);
}

.project-card h3 {
  margin-top: 0;
  margin-bottom: 6px;
  color: var(--text-main);
}

.project-meta {
  color: var(--primary);
  font-weight: 600;
  font-size: 0.92rem;
  margin-bottom: 12px;
}

.project-card p {
  color: var(--text-muted);
  line-height: 1.75;
}

.two-column {
  display: grid;
  grid-template-columns: 1fr 1fr;
  gap: 22px;
}

.info-card {
  padding: 22px 24px;
  border-radius: var(--radius);
  background: #ffffff;
  border: 1px solid var(--border);
  box-shadow: var(--shadow);
}

.info-card h3 {
  margin-top: 0;
  color: var(--text-main);
}

.info-card p,
.info-card li {
  color: var(--text-muted);
  line-height: 1.7;
}

@media (max-width: 760px) {
  .hero-card {
    padding: 24px;
  }

  .hero-photo {
    margin: 0 auto;
  }

  .paper-card {
    grid-template-columns: 1fr;
  }

  .two-column {
    grid-template-columns: 1fr;
  }
}
</style>

<div class="hero-card">

<div class="hero-text" markdown="1">

# Huaixiang Li

<div class="hero-subtitle">
Undergraduate Student in Chemical Engineering and Technology
</div>

<div class="hero-description" markdown="1">

I am an undergraduate student in **Chemical Engineering and Technology** at  
[Kunming University of Science and Technology](https://www.kmust.edu.cn).

My research focuses on **heterogeneous catalysis**, especially **propane dehydrogenation**, **Ni-based non-precious metal catalysts**, **defect engineering**, and **structure–activity relationships**. I am interested in understanding how active-site structure, support defects, electronic regulation, and metal–support interactions affect catalytic activity, selectivity, and stability under high-temperature reaction conditions.

</div>

<div class="hero-links">
<a class="btn btn-primary" href="files/CV.pdf">Curriculum Vitae</a>
<a class="btn btn-outline" href="mailto:huaixianglee@gmail.com">Email</a>
<a class="btn btn-outline" href="#publications">Publications</a>
</div>

</div>

<div class="hero-photo">
<img src="images/profile.jpg" alt="Huaixiang Li">
</div>

</div>

---

<h2 class="section-title">Research Interests</h2>

<div class="tag-container">
<span class="research-tag">Propane Dehydrogenation</span>
<span class="research-tag">Ni-based Catalysts</span>
<span class="research-tag">Defect Engineering</span>
<span class="research-tag">Metal–Support Interactions</span>
<span class="research-tag">Structure–Activity Relationships</span>
<span class="research-tag">In-situ DRIFTS</span>
<span class="research-tag">CO₂ Valorization</span>
<span class="research-tag">Reverse Water–Gas Shift</span>
</div>

---

<h2 class="section-title">News</h2>

<div class="news-box" markdown="1">

- **2026** — Recognized as Provincial “Five Merits” Student  
- **2025** — First-author manuscript on boron-regulated Ni-based catalysts for PDH under peer review  
- **2025** — Co-authored work on Gaδ⁺–H active sites for RWGS accepted by *Chemical Engineering Journal*  
- **2025.04** — Project on defect-engineered catalysts for PDH supported by the Yunnan Provincial University Students’ Innovation and Entrepreneurship Fund  
- **2025.01** — Ongoing research on Ni-based catalysts for propane dehydrogenation  
- **2024.11** — Started systematic research training in heterogeneous catalysis  

</div>

---

<h2 class="section-title" id="publications">Publications</h2>

<div class="paper-card">

<div class="paper-image">
<div class="badge">In Peer Review</div>
<img src="images/pdh-b-ni-defect.png" alt="Boron-regulated Ni-based catalysts for PDH">
</div>

<div class="paper-content" markdown="1">

### Stabilizing Ni²⁺ Sites via Boron-Induced Structural Modulation for Propane Dehydrogenation

<div class="paper-authors">
<strong>Huaixiang Li</strong>, T. Zhang, Z. Tao, Y. Ling, S. Zhong, H. Wang, Y. Li, H. He, and Y. Luo
</div>

<div class="paper-journal">
<em>Catalysis Science & Technology</em>, 2025. In peer review.
</div>

<div class="paper-summary">
This work focuses on boron-modified Ni-based catalysts for propane dehydrogenation. We investigate how boron-induced structural modulation stabilizes highly dispersed Ni²⁺ species, regulates the electronic and geometric environment of Ni active sites, and suppresses carbon deposition under high-temperature PDH conditions.
</div>

<div class="paper-links">
<a class="btn btn-outline" href="#defect-controlled-metal-oxide-catalysts-for-propane-dehydrogenation">Project</a>
</div>

</div>

</div>

<div class="paper-card">

<div class="paper-image">
<div class="badge">Accepted</div>
<img src="images/rwgs-ga-h.png" alt="Ga-H active sites for RWGS">
</div>

<div class="paper-content" markdown="1">

### Gaδ⁺–H Active Sites-Driven Reverse Water–Gas Shift Reaction with High CO Selectivity

<div class="paper-authors">
Z. Tao, <strong>Huaixiang Li</strong>, H. He, Z. Huang, J. Liang, J. Dong, X. Cao, and Y. Luo
</div>

<div class="paper-journal">
<em>Chemical Engineering Journal</em>, 2025. Accepted.
</div>

<div class="paper-summary">
This work identifies Gaδ⁺–H species as key active sites for the reverse water–gas shift reaction over Ga/Al₂O₃ catalysts. My contribution mainly focused on in-situ DRIFTS analysis and mechanistic interpretation of dynamic surface intermediate evolution under reaction atmospheres.
</div>

<div class="paper-links">
<a class="btn btn-primary" href="DOI_OR_JOURNAL_LINK_HERE">Paper</a>
<a class="btn btn-outline" href="files/rwgs-ga-h-cej.pdf">PDF</a>
</div>

</div>

</div>

---

<h2 class="section-title">Research Experience</h2>

<div class="project-grid">

<div class="project-card" id="defect-controlled-metal-oxide-catalysts-for-propane-dehydrogenation" markdown="1">

### Defect-Controlled Metal Oxide Catalysts for Propane Dehydrogenation

<div class="project-meta">
Student Researcher | Supervisor: Prof. Hedong He | Apr. 2025 – Present
</div>

This project focuses on the design of high-performance non-precious metal catalysts for propane dehydrogenation. I investigate how defect engineering, support acidity modulation, and boron-induced structural regulation influence the dispersion, valence state, and stability of Ni active sites.

My work includes catalyst synthesis, catalytic performance evaluation, structural characterization, and mechanism analysis. I have used techniques including **XRD, XPS, H₂-TPR, Raman, UV–Vis, EPR, O₂-TPO, NH₃-TPD, and in-situ DRIFTS** to study catalyst structure, oxygen vacancies, metal valence states, carbon deposition behavior, and reaction mechanisms.

</div>

<div class="project-card" markdown="1">

### Ga/Al₂O₃ Catalysts for Reverse Water–Gas Shift Reaction

<div class="project-meta">
Research Contributor
</div>

In this project, I contributed to the mechanistic investigation of Ga-based catalysts for CO₂ hydrogenation to CO. My work focused on in-situ DRIFTS analysis, especially the identification of dynamic surface species under H₂ and CO₂-containing atmospheres.

The study revealed that Gaδ⁺–H species can be generated under hydrogen atmosphere and consumed during CO₂ activation, providing mechanistic evidence for the role of Ga–H species in highly selective RWGS catalysis.

</div>

<div class="project-card" markdown="1">

### Functional Materials for Water Purification

<div class="project-meta">
Core Member | Supervisor: Prof. Hedong He | Sept. 2024 – Present
</div>

This project explores the transformation of industrial waste into functional water purification materials. I participated in material preparation, performance testing, and structure–property analysis, gaining broader experience in functional material design and characterization.

</div>

</div>

---

<h2 class="section-title">Education</h2>

<div class="info-card" markdown="1">

### Kunming University of Science and Technology

**B.E. in Chemical Engineering and Technology, Honors Program**  
*Sept. 2023 – Jul. 2027 expected*

Relevant coursework includes Physical Chemistry, Organic Chemistry, Inorganic and Analytical Chemistry, Principles of Chemical Engineering, Chemical Engineering Thermodynamics, Chemical Process Modeling, Industrial Catalysis, and Instrumental Analysis.

</div>

---

<h2 class="section-title">Honors and Awards</h2>

<div class="two-column">

<div class="info-card" markdown="1">

### Major Awards

- **2026** — Provincial “Five Merits” Student  
- **2024** — National Scholarship  
- **2024** — He Dong Scholarship, KUST  
- **2025** — First-Class Scholarship, KUST  
- **2026** — Second-Class Scholarship, KUST  

</div>

<div class="info-card" markdown="1">

### Competitions and Honors

- **2025** — Third Prize, National University Students’ Chemical Engineering Experiment Competition, Southwest China Division  
- **2025** — Third Prize, Yunnan Provincial University Students’ Energy Conservation & Emission Reduction Competition  
- **2024** — Third Prize, Contemporary Undergraduate Mathematical Contest in Modeling, Yunnan Provincial Division  
- **2023–2026** — Multiple university-level scholarships and academic honors  

</div>

</div>

---

<h2 class="section-title">Skills</h2>

<div class="two-column">

<div class="info-card" markdown="1">

### Experimental Skills

**Catalyst synthesis and testing**  
Impregnation, ion exchange, co-precipitation, catalyst activity evaluation

**Characterization**  
XRD, XPS, H₂-TPR, NH₃-TPD, O₂-TPO, Raman, UV–Vis, EPR, in-situ DRIFTS

</div>

<div class="info-card" markdown="1">

### Research and Analysis

**Mechanistic analysis**  
Structure–activity relationship analysis, coke deposition analysis, surface intermediate identification, active-site evolution

**Modeling and visualization**  
Diamond, Cinema 4D

**Languages**  
Chinese, English

</div>

</div>

---

<h2 class="section-title">Professional Experience</h2>

<div class="project-grid">

<div class="project-card" markdown="1">

### Beijing Academy of Artificial Intelligence

<div class="project-meta">
Data Annotator | Mar. 2025 – Present
</div>

I contribute to scientific literature and patent data annotation for AI-for-science projects. My work includes proofreading automatic annotation results, identifying errors in entity recognition and relationship extraction, and providing structured feedback to improve data quality.

</div>

<div class="project-card" markdown="1">

### Online Tutoring Initiative

<div class="project-meta">
Founder & Tutor | Jan. 2025 – Present
</div>

I independently manage an online tutoring initiative in mathematics and physics, including curriculum design, student communication, scheduling, and personalized learning support.

</div>

</div>

---

<h2 class="section-title">Contact</h2>

<div class="info-card" markdown="1">

Email: [huaixianglee@gmail.com](mailto:huaixianglee@gmail.com)

I welcome discussions on heterogeneous catalysis, propane dehydrogenation, CO₂ valorization, catalyst characterization, and related research topics.

</div>

<!-- 
==========================
需要你补充或替换的内容
==========================

1. 请准备一张正式头像，并命名为：
   images/profile.jpg

2. 请准备一张你的 PDH 一作论文/项目图，建议使用 B–Ni–Defect 协同机制示意图，并命名为：
   images/pdh-b-ni-defect.png

3. 请准备一张 RWGS 论文图，建议使用 Gaδ⁺–H active sites 或 DRIFTS 机制图，并命名为：
   images/rwgs-ga-h.png

4. 如果 RWGS 论文已经有 DOI，请把下面这一行：
   href="DOI_OR_JOURNAL_LINK_HERE"
   替换成真实 DOI 链接，例如：
   href="https://doi.org/xxxxx"

5. 如果你想让 PDF 可以点击下载，请把论文 PDF 放到：
   files/rwgs-ga-h-cej.pdf

6. 如果你的 PDH 一作论文接收后，可以把 “In Peer Review” 改成 “Accepted” 或 “Published”，并添加：
   <a class="btn btn-primary" href="你的DOI链接">Paper</a>
   <a class="btn btn-outline" href="files/pdh-b-ni-defect.pdf">PDF</a>

7. 如果你不想放 Professional Experience，可以删除整个 Professional Experience 部分。
   但我建议保留，因为它能体现你除了科研外还有数据标注和教学经历。

8. 如果你的 GitHub Pages 模板不支持 <style>，可以把 <style> 和 </style> 中间的内容剪切到：
   assets/css/custom.css
   然后在模板中引入该 CSS 文件。
-->
```
