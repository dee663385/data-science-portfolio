---
layout: default
title: European Cities Starting with Z
description: "Semester project in CISC7204: a geospatial analysis of European cities whose names begin with the letter Z."
permalink: /projects/geospatial-z-cities/
---

<div class="page-intro">
  <p class="eyebrow">Semester Project</p>
  <h1>European Cities Starting with the Letter "Z"</h1>
  <p class="muted">WANG DI · mc663385 · CISC7204 - Data Science</p>
</div>

<div class="content-card">
  <h2>Research question</h2>
  <p>
    How are European cities whose names start with the letter Z distributed across the continent,
    and how can spatial visualisation make that distribution easier to understand?
  </p>

  <h2>Why the question matters</h2>
  <p>
    City-name patterns are not random in a simple sense: they reflect language, history, borders,
    and settlement patterns. Restricting the analysis to one starting letter creates a manageable
    but unusual subset that makes spatial sparsity and data-quality limitations visible.
  </p>

  <h2>Data and preparation</h2>
  <ul>
    <li>The analysis uses the CISC7204 world cities population dataset.</li>
    <li>European countries are identified through an explicit country-code list.</li>
    <li>Cities beginning with Z are isolated from the European subset.</li>
    <li>Latitude and longitude are converted into point geometries using EPSG:4326.</li>
    <li>Missing population values are retained and discussed rather than silently replaced.</li>
  </ul>

  <h2>Methods</h2>
  <ol>
    <li>Load and inspect the global city dataset.</li>
    <li>Filter records to the European country subset.</li>
    <li>Extract city names beginning with Z.</li>
    <li>Build a GeoDataFrame and plot the point locations.</li>
    <li>Construct Voronoi cells clipped to a bounding envelope.</li>
    <li>Compare spatial coverage and discuss missing population values.</li>
  </ol>

  <h2>Selected visualisations</h2>
</div>

<figure class="project-figure">
  <img src="https://raw.githubusercontent.com/dee663385/data-science-project/main/fig1.png" alt="Dot density plot of European cities beginning with Z">
  <figcaption>Figure 1: Dot-density view of European cities beginning with Z.</figcaption>
</figure>

<figure class="project-figure">
  <img src="https://raw.githubusercontent.com/dee663385/data-science-project/main/fig2.png" alt="Voronoi visualisation of European cities beginning with Z">
  <figcaption>Figure 2: Voronoi cells showing the spatial coverage of the selected cities.</figcaption>
</figure>

<div class="content-card">
  <h2>Key findings</h2>
  <ul>
    <li>The dataset contains approximately 3.17 million city records.</li>
    <li>Approximately 898,604 records are classified as European in the analysis.</li>
    <li>Cities beginning with Z form a sparse subset concentrated in a limited number of countries.</li>
    <li>Large Voronoi cells indicate that many areas are far from a selected city.</li>
    <li>Missing population values limit comparisons based on city size.</li>
  </ul>

  <h2>Limitations</h2>
  <ul>
    <li>The definition of Europe depends on a hard-coded country-code list.</li>
    <li>Population fields are missing for many smaller cities.</li>
    <li>The notebook's animated filter is simulated frame by frame rather than being a true interactive dashboard.</li>
  </ul>

  <h2>Reproducibility and code</h2>
  <p>
    The repository contains the analysis notebook, visualisations, dependency list, and instructions
    for obtaining the course dataset.
  </p>
  <div class="hero-actions">
    <a class="button" href="{{ site.semester_project_repo }}">Open the project repository</a>
    <a class="button secondary" href="{{ '/' | relative_url }}">Back to portfolio</a>
  </div>
</div>
