---
layout: portfolio
title: "Résumé"
permalink: /resume/
description: "Résumé of Xingye Zhang, Systems Engineering M.S. student working on reliable AI agents and applied data systems."
nav: resume
body_class: resume-page
---

<header class="page-hero">
  <div class="shell">
    <p class="eyebrow">Résumé</p>
    <h1>Research engineering, agent evaluation, and applied data.</h1>
    <p class="page-intro">A public-safe summary of my education, experience, and selected technical work. Phone numbers, detailed address, private research artifacts, and application records are intentionally excluded.</p>
    <div class="resume-actions">
      <a class="button" href="{{ '/files/Xingye-Zhang-Resume.pdf' | relative_url }}" target="_blank">Download PDF <span aria-hidden="true">↗</span></a>
      <a class="button secondary" href="mailto:azserein1016@outlook.com">Email me</a>
    </div>
  </div>
</header>

<section class="section compact">
  <div class="shell resume-layout">
    <aside class="resume-sidebar">
      <h2>Core toolkit</h2>
      <div class="skill-cloud">
        <span class="tag">Python</span><span class="tag">JavaScript</span><span class="tag">SQL</span><span class="tag">R</span>
        <span class="tag">LLM APIs</span><span class="tag">PyTorch</span><span class="tag">Playwright</span><span class="tag">PySpark</span>
        <span class="tag">Django REST</span><span class="tag">Express.js</span><span class="tag">MySQL</span><span class="tag">Git</span>
        <span class="tag">GeoPandas</span><span class="tag">QGIS</span><span class="tag">HPC / Slurm</span><span class="tag">Evaluation</span>
      </div>
    </aside>

    <div>
      <section class="resume-entry">
        <h2>Profile</h2>
        <p>Systems Engineering M.S. student at the University of Pennsylvania with a Statistics and Economics background. Builds practical AI systems that combine agent research, evaluation, data processing, backend engineering, and reproducible experimentation.</p>
      </section>

      <section class="resume-entry">
        <h2>Education</h2>
        <h3>University of Pennsylvania</h3>
        <p class="meta">M.S. in Systems Engineering · 2025—Present · Philadelphia, PA</p>
        <p>Coursework includes applied machine learning, optimization, big data analytics, simulation, feedback control, statistics for data science, and time-series machine learning.</p>
        <h3>University of Connecticut</h3>
        <p class="meta">B.A. in Statistics and Economics · 2020—2024 · GPA 3.88 / 4.00</p>
      </section>

      <section class="resume-entry">
        <h2>Research &amp; Experience</h2>
        <h3>AI Agent Systems Research Collaboration with UConn Researchers</h3>
        <p class="meta">Research and Engineering Contributor · January 2026—Present</p>
        <ul>
          <li>Research reliable tool-using agents, runtime intervention, recoverable execution, evaluation design, and closed-loop control.</li>
          <li>Designed evaluation for safety, task completion, structured block feedback, and post-intervention recovery; co-developed a 60-episode benchmark across five task families.</li>
          <li>Integrated online action interception, evaluated five runtime-defense conditions across 300 traces, and performed a clean-seed leakage audit.</li>
          <li>Co-developed closed-loop trace-replay evaluation across 10,933 shared states and 114 matched telecom tasks.</li>
        </ul>

        <h3>University of Connecticut, Department of Statistics</h3>
        <p class="meta">Research Assistant · March—December 2024</p>
        <ul>
          <li>Integrated satellite imagery, OpenStreetMap footprints, and UT-GLOBUS data for city- and building-scale analysis.</li>
          <li>Applied spatial statistics and geospatial visualization; built an HPC/Slurm workflow for 413 major U.S. cities.</li>
        </ul>

        <h3>GBCS — SkyIT Services</h3>
        <p class="meta">Backend Developer Intern · May—August 2024</p>
        <ul>
          <li>Collaborated with frontend and backend engineers to deliver and release the Voop application for a client.</li>
          <li>Developed, tested, optimized, and maintained REST APIs with Express.js and Django REST, using Postman for endpoint validation.</li>
          <li>Supported a Firebase-to-MySQL migration through schema refinement and consistency checks.</li>
        </ul>

        <h3>Beijing QIANSHIDU Trade Co., Ltd.</h3>
        <p class="meta">Data Analyst and Market Research Associate · January—May 2024</p>
        <ul>
          <li>Analyzed more than 1 GB of two-year business data and developed a GPT-based demand-forecasting workflow using SHAP and K-means.</li>
          <li>Produced insights that supported reallocating approximately 10% of product supply toward neighboring-country markets.</li>
          <li>Represented the company at Vision Expo 2024 in New York City.</li>
        </ul>
      </section>

      <section class="resume-entry">
        <h2>Selected Projects</h2>
        <h3>New Haven Spatial Analysis</h3>
        <p>Spatial statistics and interactive visualization over 331,423 UT-GLOBUS building records using GeoPandas, PySAL, Plotly, and Quarto.</p>
        <h3>Evidence-Governed Career Operations Agent</h3>
        <p>Policy-governed extension of Career-Ops, an open-source project by santifer, using explicit workflow state, evidence routing, approval gates, Playwright, and LaTeX.</p>
        <h3>NYC Rodent Inspection Analysis</h3>
        <p>Public-data cleaning, statistical modeling, and geospatial visualization presented to the NYC Open Data team.</p>
        <h3>NBA Salary Prediction</h3>
        <p>Feature engineering, cross-validation, Bayesian optimization, and ensembling across four machine-learning models.</p>
      </section>
    </div>
  </div>
</section>
