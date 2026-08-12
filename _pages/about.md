---
layout: portfolio
permalink: /
title: ""
description: "Xingye Zhang builds reliable AI agents, reproducible evaluations, and practical data systems."
body_class: home
---

<section class="hero">
  <div class="shell hero-grid">
    <div>
      <p class="eyebrow">AI agent systems · data science</p>
      <h1>Reliable AI agents. <em>Useful</em> data systems.</h1>
      <p class="hero-lede">I’m Xingye (Austin) Zhang, a Systems Engineering M.S. student at the University of Pennsylvania. I build and evaluate tool-using LLM agents, reproducible research pipelines, and data products grounded in evidence.</p>
      <div class="hero-actions">
        <a class="button" href="{{ '/work/' | relative_url }}">View selected work <span aria-hidden="true">↗</span></a>
        <a class="button secondary" href="{{ '/resume/' | relative_url }}">Read my résumé</a>
      </div>
      <div class="signal-row" aria-label="Areas of focus">
        <div class="signal"><strong>Agent reliability</strong><span>Intervention, recovery, evaluation</span></div>
        <div class="signal"><strong>Applied data</strong><span>Geospatial, statistical, ML</span></div>
        <div class="signal"><strong>Systems thinking</strong><span>Traceable, testable workflows</span></div>
      </div>
    </div>
    <figure class="hero-portrait">
      <img src="{{ '/assets/images/xingye-hero.jpg' | relative_url }}" alt="Xingye Zhang outdoors with Molly" width="1361" height="1080">
      <figcaption class="portrait-label">Based in Philadelphia · building at the intersection of AI, evaluation, and data engineering.</figcaption>
    </figure>
  </div>
</section>

<section class="section section-tinted" id="selected-work">
  <div class="shell">
    <div class="section-head">
      <div>
        <p class="eyebrow">Selected work</p>
        <h2>Systems that can explain themselves.</h2>
      </div>
      <p>I’m interested in work where rigor matters: agents that recover from blocked actions, maps that state their uncertainty, and workflows whose decisions can be traced back to evidence.</p>
    </div>

    <div class="work-grid">
      <article class="work-card featured map-card">
        <img src="{{ '/assets/images/new-haven-map.jpg' | relative_url }}" alt="Interactive map of estimated building heights in central New Haven" width="1280" height="780">
        <div class="card-copy">
          <div class="card-kicker"><span>Geospatial case study</span><span class="card-number">01</span></div>
          <div>
            <h3>New Haven building-height spatial analysis</h3>
            <p class="card-description">A 331,423-record spatial analysis with a focused interactive preview of 16,379 central New Haven polygons.</p>
            <div class="card-meta"><span>GeoPandas</span><span>PySAL</span><span>Plotly</span><span>Quarto</span></div>
          </div>
        </div>
        <a class="card-link" href="{{ '/work/new-haven-spatial-analysis/' | relative_url }}"><span>Open New Haven spatial analysis case study</span></a>
      </article>

      <article class="work-card side light">
        <div>
          <div class="card-kicker"><span>Current research</span><span class="card-number">02</span></div>
          <h3>Reliable tool-using agents</h3>
          <p class="card-description">Evaluation design for runtime intervention, recoverable multi-step execution, leakage-aware traces, and closed-loop control.</p>
        </div>
        <div class="card-meta"><span>Python</span><span>LLM APIs</span><span>Evaluation</span></div>
        <a class="card-link" href="{{ '/work/#agent-systems' | relative_url }}"><span>Read about reliable agent systems work</span></a>
      </article>

      <article class="work-card">
        <div>
          <div class="card-kicker"><span>Open-source extension</span><span class="card-number">03</span></div>
          <h3>Evidence-governed career operations</h3>
          <p class="card-description">A human-in-the-loop workflow that separates evidence, approval, opportunity state, and irreversible submission actions.</p>
          <div class="system-visual" aria-hidden="true">
            <div class="system-node"><span>01 · Evidence</span><strong>Verified inputs</strong></div>
            <div class="system-node"><span>02 · Policy</span><strong>Explicit gates</strong></div>
            <div class="system-node"><span>03 · Action</span><strong>Human approval</strong></div>
          </div>
        </div>
        <div class="card-meta"><span>Node.js</span><span>Playwright</span><span>Workflow state</span></div>
        <a class="card-link" href="{{ '/work/#career-operations' | relative_url }}"><span>Read about the career operations project</span></a>
      </article>

      <article class="work-card">
        <div>
          <div class="card-kicker"><span>Applied statistics</span><span class="card-number">04</span></div>
          <h3>From public data to honest conclusions</h3>
          <p class="card-description">Course analyses spanning NYC rodent inspections and NBA salary prediction—including useful negative results and clearly stated limitations.</p>
        </div>
        <div class="card-meta"><span>pandas</span><span>statsmodels</span><span>scikit-learn</span></div>
        <a class="card-link" href="{{ '/work/#course-work' | relative_url }}"><span>View applied statistics projects</span></a>
      </article>
    </div>
  </div>
</section>

<section class="section">
  <div class="shell">
    <div class="section-head">
      <div>
        <p class="eyebrow">How I work</p>
        <h2>Evidence first, then action.</h2>
      </div>
      <p>Strong systems are not defined only by a model or interface. They need clear boundaries, reproducible checks, and an honest account of what the evidence supports.</p>
    </div>
    <div class="method-grid">
      <article class="method">
        <span class="method-number">01</span>
        <h3>Make the state visible</h3>
        <p>Structure inputs, decisions, and traces so a result can be inspected instead of merely trusted.</p>
      </article>
      <article class="method">
        <span class="method-number">02</span>
        <h3>Test the failure path</h3>
        <p>Evaluate blocked actions, recovery, stale data, and edge cases—not only the clean happy path.</p>
      </article>
      <article class="method">
        <span class="method-number">03</span>
        <h3>State the boundary</h3>
        <p>Separate measured outcomes from inference, archived results from reruns, and prototypes from production systems.</p>
      </article>
    </div>
  </div>
</section>

<section class="section section-tinted">
  <div class="shell">
    <div class="section-head">
      <div>
        <p class="eyebrow">Experience</p>
        <h2>Research meets engineering.</h2>
      </div>
      <p>My path combines statistics and economics with systems engineering, agent evaluation, backend development, and geospatial research.</p>
    </div>
    <div class="experience-list">
      <article class="experience-row">
        <time datetime="2026-01">2026—Present</time>
        <h3>AI Agent Systems Research Collaboration with UConn Researchers</h3>
        <p>Research and engineering for reliable tool-using agents, runtime intervention, evaluation, and closed-loop recovery.</p>
      </article>
      <article class="experience-row">
        <time datetime="2025-08">2025—Present</time>
        <h3>University of Pennsylvania</h3>
        <p>M.S. student in Systems Engineering, extending a foundation in statistics and economics into AI and systems work.</p>
      </article>
      <article class="experience-row">
        <time datetime="2024-03">2024</time>
        <h3>University of Connecticut</h3>
        <p>Research Assistant working with satellite imagery, spatial statistics, building-height data, and HPC workflows.</p>
      </article>
      <article class="experience-row">
        <time datetime="2024-05">2024</time>
        <h3>GBCS — SkyIT Services</h3>
        <p>Backend Developer Intern contributing to the delivery and release of the Voop application for a client, REST APIs, and a Firebase-to-MySQL migration.</p>
      </article>
    </div>
    <p style="margin-top: 28px;"><a class="text-link" href="{{ '/about/' | relative_url }}">More about my path <span aria-hidden="true">→</span></a></p>
  </div>
</section>

<section class="section">
  <div class="shell">
    <div class="cta-band">
      <p class="eyebrow">Let’s connect</p>
      <h2>Interested in reliable AI and useful data systems?</h2>
      <p>I’m open to conversations about agent research, applied AI, data engineering, and systems work.</p>
      <div class="hero-actions">
        <a class="button" href="mailto:azserein1016@outlook.com">Email me</a>
        <a class="button secondary" href="https://www.linkedin.com/in/az-serein" target="_blank" rel="noopener noreferrer">LinkedIn <span aria-hidden="true">↗</span></a>
      </div>
    </div>
  </div>
</section>
