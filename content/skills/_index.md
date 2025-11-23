---
title: "Skills"
date: 2025-01-01
---

# <span style="color:#2558b3; font-weight:bold;">Skills</span>

A snapshot of my technical, analytical, linguistic, and professional skills, built through research, teaching, collaborative projects, and community work.

<style>
/* Container */
.skills-container {
  margin-top: 1.5rem;
}

/* Tabs */
.skills-tabs {
  display: flex;
  flex-wrap: wrap;
  gap: 0.5rem;
  margin-bottom: 1rem;
}

/* Hide radio buttons */
.skills-tabs input[type="radio"] {
  display: none;
}

/* Tab labels */
.skills-tabs label {
  padding: 0.3rem 0.8rem;
  border-radius: 999px;
  border: 1px solid #2558b3;
  cursor: pointer;
  font-size: 0.9rem;
  white-space: nowrap;
}

/* Default tab label style */
.skills-tabs label {
  background-color: #ffffff;
  color: #2558b3;
}

/* Active tab styles */
#tab-all:checked ~ label[for="tab-all"],
#tab-tech:checked ~ label[for="tab-tech"],
#tab-lang:checked ~ label[for="tab-lang"],
#tab-prof:checked ~ label[for="tab-prof"] {
  background-color: #2558b3;
  color: #ffffff;
}

/* Skill sections */
.skills-section {
  display: none;
  margin-top: 0.5rem;
}

/* Show section when tab selected */
#tab-all:checked ~ .skills-content #skills-all,
#tab-tech:checked ~ .skills-content #skills-tech,
#tab-lang:checked ~ .skills-content #skills-lang,
#tab-prof:checked ~ .skills-content #skills-prof {
  display: block;
}

/* Skill chips */
.skill-chip {
  display: inline-block;
  margin: 0.18rem 0.28rem;
  padding: 0.18rem 0.6rem;
  border-radius: 999px;
  border: 1px solid #ddd;
  font-size: 0.85rem;
}

/* Section headings inside skills */
.skills-subheading {
  font-weight: 600;
  margin-top: 0.6rem;
  margin-bottom: 0.3rem;
}
</style>

<div class="skills-container">

<div class="skills-tabs">
  <!-- Tabs as radios -->
  <input type="radio" id="tab-all"  name="skills-tab" checked>
  <label for="tab-all">All</label>

  <input type="radio" id="tab-tech" name="skills-tab">
  <label for="tab-tech">Technical</label>

  <input type="radio" id="tab-lang" name="skills-tab">
  <label for="tab-lang">Languages</label>

  <input type="radio" id="tab-prof" name="skills-tab">
  <label for="tab-prof">Professional</label>

  <!-- Content wrapper -->
  <div class="skills-content">
    <!-- ALL SKILLS -->
    <div id="skills-all" class="skills-section">
      <div class="skills-subheading">Programming & Data Science</div>
      <span class="skill-chip">Python</span>
      <span class="skill-chip">R</span>
      <span class="skill-chip">C</span>
      <span class="skill-chip">RStudio</span>
      <span class="skill-chip">Stata</span>
      <span class="skill-chip">PowerBI</span>
      <span class="skill-chip">Excel</span>
      <span class="skill-chip">LaTeX</span>
      <span class="skill-chip">Git</span>
      <span class="skill-chip">GitHub</span>
      <div class="skills-subheading">Geospatial & Visualization</div>
      <span class="skill-chip">GIS</span>
      <span class="skill-chip">QGIS</span>
      <span class="skill-chip">Geospatial Analysis</span>
      <span class="skill-chip">Geospatial Visualization</span>
      <span class="skill-chip">ggplot2</span>
      <span class="skill-chip">RMarkdown / Quarto</span>
      <div class="skills-subheading">Machine Learning & Quantitative Methods</div>
      <span class="skill-chip">Supervised ML</span>
      <span class="skill-chip">Unsupervised ML</span>
      <span class="skill-chip">Econometrics</span>
      <span class="skill-chip">Time Series & Panel Data (applied)</span>
      <span class="skill-chip">Text & Sentiment Analysis</span>
      <div class="skills-subheading">Web, Tools & Creative</div>
      <span class="skill-chip">Hugo</span>
      <span class="skill-chip">GitHub Pages</span>
      <span class="skill-chip">Markdown</span>
      <span class="skill-chip">Visual Studio Code</span>
      <span class="skill-chip">Adobe Photoshop</span>
      <span class="skill-chip">Google Suite</span>
      <div class="skills-subheading">Education, Research & Projects</div>
      <span class="skill-chip">University Teaching (1000–2000 level)</span>
      <span class="skill-chip">Curriculum & Material Design</span>
      <span class="skill-chip">Field Research & Community Work</span>
      <span class="skill-chip">Accessibility & Inclusive Pedagogy</span>
      <span class="skill-chip">Theatre & Public Speaking</span>
      <span class="skill-chip">Sustainable Design Projects (EV Charging, Piezoelectric Floor)</span>
    </div>
    <!-- TECHNICAL ONLY -->
    <div id="skills-tech" class="skills-section">
      <div class="skills-subheading">Programming & Development</div>
      <span class="skill-chip">Python</span>
      <span class="skill-chip">R</span>
      <span class="skill-chip">C</span>
      <span class="skill-chip">RStudio</span>
      <span class="skill-chip">Visual Studio Code</span>
      <span class="skill-chip">Git</span>
      <span class="skill-chip">GitHub</span>
      <div class="skills-subheading">Data Science & Statistics</div>
      <span class="skill-chip">Stata</span>
      <span class="skill-chip">Excel</span>
      <span class="skill-chip">PowerBI</span>
      <span class="skill-chip">Econometrics</span>
      <span class="skill-chip">Regression & Causal Inference (applied)</span>
      <div class="skills-subheading">Machine Learning & Text</div>
      <span class="skill-chip">Supervised & Unsupervised ML</span>
      <span class="skill-chip">Model Evaluation</span>
      <span class="skill-chip">Text Mining</span>
      <span class="skill-chip">Sentiment Analysis</span>
      <span class="skill-chip">Web Scraping</span>
      <div class="skills-subheading">Geospatial & Visualization</div>
      <span class="skill-chip">GIS</span>
      <span class="skill-chip">QGIS</span>
      <span class="skill-chip">Geospatial Analysis</span>
      <span class="skill-chip">Geospatial Visualization</span>
      <span class="skill-chip">ggplot2</span>
      <span class="skill-chip">RMarkdown / Quarto</span>
      <div class="skills-subheading">Tools & Infrastructure</div>
      <span class="skill-chip">LaTeX</span>
      <span class="skill-chip">Hugo</span>
      <span class="skill-chip">GitHub Pages</span>
      <span class="skill-chip">Google Suite</span>
      <span class="skill-chip">Markdown</span>
      <span class="skill-chip">Adobe Photoshop</span>
    </div>
    <!-- LANGUAGES -->
    <div id="skills-lang" class="skills-section">
      <div class="skills-subheading">Languages</div>
      <span class="skill-chip">English — Native / Professional</span>
      <span class="skill-chip">Hindi — Native / Professional</span>
      <span class="skill-chip">French — DELF B1 (Alliance Française)</span>
      <span class="skill-chip">German — Fit in Deutsch 1</span>
    </div>
    <!-- PROFESSIONAL / INTERPERSONAL -->
    <div id="skills-prof" class="skills-section">
      <div class="skills-subheading">Teaching & Mentorship</div>
      <span class="skill-chip">University Teaching (1000–2000 level)</span>
      <span class="skill-chip">Teaching Fellows & TA roles</span>
      <span class="skill-chip">Curriculum & Content Design</span>
      <span class="skill-chip">Research Supervision</span>
      <span class="skill-chip">Workshop Facilitation</span>
      <div class="skills-subheading">Communication & Collaboration</div>
      <span class="skill-chip">Public Speaking</span>
      <span class="skill-chip">Theatre Performance</span>
      <span class="skill-chip">Interdisciplinary Collaboration</span>
      <span class="skill-chip">Community & Field Engagement</span>
      div class="skills-subheading">Education & Social Impact</div>
      <span class="skill-chip">Accessibility Advocacy</span>
      <span class="skill-chip">Inclusive Pedagogy</span>
      <span class="skill-chip">Social Service & Education Field Work</span>
      <span class="skill-chip">Creative Pedagogy (Theatre, Storytelling, Comics)</span>
      <div class="skills-subheading">Projects & Innovation</div>
      <span class="skill-chip">Sustainable Design (EV Charging Infrastructure)</span>
      <span class="skill-chip">Piezoelectric Dance Floor Prototype</span>
      <span class="skill-chip">Digital Humanities & Partition Research</span>
      <span class="skill-chip">AI Art, Law & Technology Projects</span>
    </div>

  </div> <!-- end skills-content -->
</div> <!-- end skills-tabs -->
</div> <!-- end skills-container -->
