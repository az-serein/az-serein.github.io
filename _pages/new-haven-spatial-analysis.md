---
layout: portfolio
title: "New Haven Spatial Analysis"
permalink: /work/new-haven-spatial-analysis/
redirect_from:
  - /projects/New_Haven_ESDA/
  - /projects/New_Haven_Interactive_Map/
description: "A spatial-statistics and interactive-mapping case study of estimated building heights in New Haven."
nav: work
body_class: case-page
---

<header class="case-hero">
  <div class="shell">
    <p class="eyebrow">STAT 4845 · Individual case study · 2024</p>
    <h1>From 331,423 analyzed records to a focused interactive preview.</h1>
    <p class="case-intro">A New Haven case study combining exploratory spatial data analysis with a browser preview of 16,379 filtered central-city polygons.</p>
    <div class="case-actions">
      <a class="button" href="{{ '/_pages/New_Haven_Interactive_Map_Sample.html' | relative_url }}" target="_blank" rel="noopener noreferrer">Open interactive preview <span aria-hidden="true">↗</span></a>
      <a class="button secondary" href="https://doi.org/10.5281/zenodo.11156602" target="_blank" rel="noopener noreferrer">UT-GLOBUS dataset <span aria-hidden="true">↗</span></a>
    </div>
    <div class="case-meta-grid">
      <div class="case-meta"><span>Role</span><strong>Author &amp; analyst</strong></div>
      <div class="case-meta"><span>Methods</span><strong>Moran’s I · LISA · spatial lag</strong></div>
      <div class="case-meta"><span>Tools</span><strong>Python · PySAL · Plotly</strong></div>
      <div class="case-meta"><span>Context</span><strong>UConn STAT 4845</strong></div>
    </div>
  </div>
</header>

<div class="shell">
  <figure class="case-visual">
    <img src="{{ '/assets/images/new-haven-map.jpg' | relative_url }}" alt="Map of estimated building heights across central New Haven" width="1280" height="780">
    <figcaption>Preview of 16,379 filtered polygons in a fixed central New Haven extent. Data: UT-GLOBUS (CC BY 4.0). Basemap: © OpenStreetMap contributors, © CARTO.</figcaption>
  </figure>

  <section class="case-section">
    <div><p class="eyebrow">01 · Problem</p><h2>Urban-scale data, building-scale questions.</h2></div>
    <div class="case-copy">
      <p>UT-GLOBUS provides estimated building heights and urban-form attributes at a scale useful for urban modeling. For New Haven, the working data contained hundreds of thousands of building records—too many for the original self-contained browser export to remain practical.</p>
      <p>The project asked two connected questions: what spatial clustering appears in the height estimates, and how can people explore the data without downloading a 254 MB HTML file?</p>
    </div>
  </section>

  <section class="case-section">
    <div><p class="eyebrow">02 · Approach</p><h2>Statistics and interaction, side by side.</h2></div>
    <div class="case-copy">
      <p>I prepared the New Haven data, constructed K-nearest-neighbor spatial weights, evaluated global and local spatial autocorrelation, and ran a spatial-lag experiment. I also created interactive 2D building views and a rotatable 3D height visualization.</p>
      <div class="metric-grid" aria-label="Project metrics">
        <div class="metric"><strong>331,423</strong><span>building records analyzed</span></div>
        <div class="metric"><strong>0.321</strong><span>archived Global Moran’s I</span></div>
        <div class="metric"><strong>0.001</strong><span>archived permutation p-value</span></div>
      </div>
      <p class="notice">The statistical values above are archived 2024 course-project results, not a newly rerun validation. The current curated source also corrects the historical LISA display so non-significant observations are not assigned to a quadrant.</p>
    </div>
  </section>

  <section class="case-section">
    <div><p class="eyebrow">03 · Source excerpt</p><h2>A smaller, reviewable map.</h2></div>
    <div class="case-copy">
      <p>The revised builder selects a fixed central New Haven extent, keeps only presentation-relevant attributes, removes source IDs and coordinate fields from hover content, and loads Plotly from its CDN instead of embedding the entire library.</p>
      <pre class="code-block"><code>frame = gpd.read_file(source, layer="GLOBUS", bbox=CENTRAL_NEW_HAVEN)
frame = frame.loc[
    frame["height"].between(0, 100),
    ["height", "Area", "Volume", "Surface", "geometry"],
].reset_index(drop=True)
frame["map_id"] = frame.index.astype(str)
geometry = frame.set_index("map_id").geometry

figure = px.choropleth_mapbox(
    frame,
    geojson=json.loads(geometry.to_json()),
    locations="map_id",
    featureidkey="id",
    color="height",
    mapbox_style="carto-positron",
    opacity=0.72,
)</code></pre>
      <p>This excerpt communicates the selection and visualization approach without exposing local paths, raw data, or the private archival repository.</p>
    </div>
  </section>

  <section class="case-section">
    <div><p class="eyebrow">04 · Boundaries</p><h2>Estimated height is not ground truth.</h2></div>
    <div class="case-copy">
      <p>UT-GLOBUS is intended for urban modeling and should not be interpreted as surveyed building-level truth. Individual estimates may contain meaningful error, so this case study focuses on exploratory patterns and visualization rather than property-level claims.</p>
      <p>The preview retains only project-relevant attributes and does not include personal data. The official <a href="https://doi.org/10.5281/zenodo.11156602" target="_blank" rel="noopener noreferrer">UT-GLOBUS record</a> identifies Kamath et al. as the creators and licenses the dataset under <a href="https://creativecommons.org/licenses/by/4.0/" target="_blank" rel="noopener noreferrer">CC BY 4.0</a>. The upstream software repository is GPL-3.0; this site does not redistribute its source code.</p>
    </div>
  </section>
</div>

<section class="section">
  <div class="shell">
    <div class="cta-band">
      <p class="eyebrow">Explore</p>
      <h2>Open the interactive preview or return to the full project list.</h2>
      <div class="hero-actions">
        <a class="button" href="{{ '/_pages/New_Haven_Interactive_Map_Sample.html' | relative_url }}" target="_blank" rel="noopener noreferrer">Interactive preview <span aria-hidden="true">↗</span></a>
        <a class="button secondary" href="{{ '/work/' | relative_url }}">All selected work</a>
      </div>
    </div>
  </div>
</section>
