---
layout: default
title: Home
---

<style>
/* 简单做个“顶部导航条” */
.topnav {
  position: sticky;
  top: 0;
  background: white;
  padding: 10px 0;
  border-bottom: 1px solid #eee;
  z-index: 999;
}
.topnav a { margin-right: 16px; text-decoration: none; }
.section { padding-top: 60px; margin-top: -60px; } /* 防止 sticky 遮住标题 */
.profile { display: flex; gap: 24px; align-items: flex-start; margin-top: 16px; }
.avatar { width: 160px; height: 160px; border-radius: 50%; object-fit: cover; border: 1px solid #eee; }
.card { border: 1px solid #eee; border-radius: 12px; padding: 16px; }
</style>

<div class="topnav">
  <a href="#home">Home</a>
  <a href="#about">About</a>
  <a href="#publications">Publications</a>
  <a href="#projects">Projects</a>
  <a href="#education">Education</a>
  <a href="#cv">CV</a>
</div>

<div id="home" class="section"></div>

# Ziwen Kan

<div class="profile">
  <div>
    <!-- 头像：把头像上传到 assets/img/avatar.jpg -->
    <img class="avatar" src="assets/img/avatar.jpg" alt="avatar">
    <div style="margin-top:12px;">
      <div><b>Ph.D. student</b>, Computer Science</div>
      <div style="color:#666;">Orlando, FL</div>
      <div style="margin-top:10px;">
        <a href="mailto:YOUR_EMAIL">Email</a> ·
        <a href="https://github.com/ziwenkan">GitHub</a> ·
        <a href="YOUR_SCHOLAR_LINK">Google Scholar</a> ·
        <a href="YOUR_LINKEDIN_LINK">LinkedIn</a>
      </div>
    </div>
  </div>

  <div class="card" style="flex:1;">
    <h2 style="margin-top:0;">Research Interests</h2>
    <ul>
      <li>Multimodal time series modeling</li>
      <li>Diffusion-based conditional generation / imputation</li>
      <li>Representation alignment</li>
    </ul>
    <p style="color:#666;margin-bottom:0;">
      (Add a 2–3 sentence summary here.)
    </p>
  </div>
</div>

---

<div id="about" class="section"></div>

## About

Write 5–8 sentences about you (current position, research focus, what you are looking for).

---

<div id="publications" class="section"></div>

## Publications

### Preprints / Under Review
- **TRACE: Temporal Representation Alignment and Conditional Estimation**. *(under review)*

### Conference Papers
- Add your paper here.


---

<div id="projects" class="section"></div>

## Projects

- **Resume / Cover Letter Generation Bot (Ollama + FastAPI + Streamlit)**  
  Local deployment + RAG + user-facing UI.

- **TRACE Codebase Packaging & Benchmarking**  
  Cross-site integration and AI-READI benchmarking.

---

<div id="education" class="section"></div>

## Education

/* - **University of Central Florida** — Ph.D. in Computer Science (incoming / in progress) */
/* - **UC Davis** — (your degree) */

---

<div id="cv" class="section"></div>

## CV

- Download: **[CV PDF](assets/cv.pdf)**

(Upload `cv.pdf` to `assets/cv.pdf`.)
