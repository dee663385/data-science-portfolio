---
layout: default
title: Home
description: "Data Science portfolio of WANG DI, CISC7204 student at the University of Macau."
permalink: /
---

<section class="hero">
  <div>
    <p class="eyebrow">CISC7204 Data Science Portfolio</p>
    <h1>Turning data into <span>clear evidence</span>.</h1>
    <p class="hero-lead">
      I am <strong>WANG DI</strong>, a Data Science student at the University of Macau.
      This portfolio documents how I frame questions, prepare data, build reproducible analyses,
      communicate findings, and reflect on the limits of evidence.
    </p>
    <div class="hero-actions">
      <a class="button" href="{{ '/projects/geospatial-z-cities/' | relative_url }}">View Semester Project</a>
      <a class="button secondary" href="{{ site.semester_project_repo }}">Open GitHub Repository</a>
    </div>
  </div>

  <aside class="hero-panel" aria-label="Portfolio summary">
    <dl>
      <div><dt>Student</dt><dd>WANG DI</dd></div>
      <div><dt>Student ID</dt><dd>mc663385</dd></div>
      <div><dt>Course</dt><dd>CISC7204 - Data Science</dd></div>
      <div><dt>GitHub</dt><dd><a href="https://github.com/{{ site.github_username }}">@{{ site.github_username }}</a></dd></div>
    </dl>
  </aside>
</section>

<section>
  <div class="section-heading">
    <p class="eyebrow">About</p>
    <h2>A portfolio built around reproducible evidence</h2>
    <p>I focus on analyses that are understandable, traceable, and honest about their limitations.</p>
  </div>

  <div class="split-grid">
    <article class="content-card">
      <h3>How I approach data science</h3>
      <p>
        I start with a focused research question, audit the available data, document cleaning decisions,
        and choose methods that suit the structure of the data. I then communicate the result with
        visualisations and plain-language interpretation rather than code alone.
      </p>
    </article>
    <article class="content-card">
      <h3>What this portfolio demonstrates</h3>
      <ul>
        <li>Python-based data preparation and analysis</li>
        <li>Geospatial visualisation with GeoPandas and Shapely</li>
        <li>Reproducible notebooks and documented repositories</li>
        <li>Clear discussion of data quality and limitations</li>
      </ul>
    </article>
  </div>
</section>

<section>
  <div class="section-heading">
    <p class="eyebrow">Skills</p>
    <h2>Technical toolkit</h2>
  </div>
  <div class="skill-grid">
    <article class="skill-card">
      <h3>Languages</h3>
      <p>Python, SQL</p>
    </article>
    <article class="skill-card">
      <h3>Analysis</h3>
      <p>pandas, NumPy, scikit-learn, GeoPandas, Shapely</p>
    </article>
    <article class="skill-card">
      <h3>Communication</h3>
      <p>Matplotlib, seaborn, Jupyter, GitHub Pages</p>
    </article>
  </div>
</section>

<section>
  <div class="section-heading">
    <p class="eyebrow">Featured work</p>
    <h2>Semester Project</h2>
  </div>

  <article class="project-card">
    <img class="project-visual" src="https://raw.githubusercontent.com/dee663385/data-science-project/main/fig1.png" alt="Dot density map of European cities beginning with the letter Z">
    <div class="project-body">
      <div class="project-meta">
        <span class="status-pill">Portfolio project</span>
        <span class="tag">Geospatial analysis</span>
        <span class="tag">Python</span>
        <span class="tag">Data quality</span>
      </div>
      <h3>European Cities Starting with the Letter "Z"</h3>
      <p>
        A geospatial investigation of how European cities beginning with the letter Z are distributed,
        with dot-density and Voronoi visualisations. The project examines filtering decisions,
        spatial sparsity, and the effect of missing population values.
      </p>
      <div class="metric-grid">
        <div class="metric"><strong>3.17M</strong><span>city records inspected</span></div>
        <div class="metric"><strong>898,604</strong><span>European records identified</span></div>
        <div class="metric"><strong>2</strong><span>spatial visualisations</span></div>
      </div>
      <div class="hero-actions">
        <a class="button" href="{{ '/projects/geospatial-z-cities/' | relative_url }}">Read project summary</a>
        <a class="button secondary" href="{{ site.semester_project_repo }}">View repository</a>
      </div>
    </div>
  </article>
</section>

{% if site.bonus_ready %}
<section>
  <div class="section-heading">
    <p class="eyebrow">Coursework</p>
    <h2>Assignment Showcase</h2>
  </div>
  <div class="split-grid">
    <article class="content-card">
      <h3>Assignment 01</h3>
      <p><a href="{{ site.assignment_01_repo }}">Repository</a>{% if site.assignment_01_live %} · <a href="{{ site.assignment_01_live }}">Live page</a>{% endif %}</p>
    </article>
    <article class="content-card">
      <h3>Assignment 02</h3>
      <p><a href="{{ site.assignment_02_repo }}">Repository</a>{% if site.assignment_02_live %} · <a href="{{ site.assignment_02_live }}">Live page</a>{% endif %}</p>
    </article>
  </div>
</section>
{% endif %}

<section>
  <div class="section-heading">
    <p class="eyebrow">Contact</p>
    <h2>Find the work and the code</h2>
  </div>
  <div class="contact-card">
    <p><strong>GitHub:</strong> <a href="https://github.com/{{ site.github_username }}">github.com/{{ site.github_username }}</a></p>
    <p><strong>Semester Project:</strong> <a href="{{ site.semester_project_repo }}">Repository and analysis notebook</a></p>
    <p class="muted">Student ID: mc663385 · CISC7204 - Data Science · University of Macau</p>
  </div>
</section>
