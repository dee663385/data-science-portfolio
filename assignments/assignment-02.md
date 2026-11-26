---
layout: default
title: Assignment 02
description: "Visualisation, dashboard development, and U.S. employment recovery analysis by WANG DI."
permalink: /assignments/assignment-02/
---

<div class="page-intro">
  <p class="eyebrow">Assignment 02</p>
  <h1>Visualisation, Dashboard Development, and Employment Recovery</h1>
  <p class="muted">WANG DI · mc663385 · CISC7204 - Data Science</p>
</div>

<div class="content-card" markdown="1">
## What this assignment demonstrates

Assignment 02 combines individual visual-analysis work, an interactive dashboard, and a pair research project. It shows the full path from data acquisition and validation through exploratory charts, interactive controls, geographic visualisation, and a concise evidence-based conclusion.

**Repository:** [assignment-work/assignment-02](https://github.com/dee663385/data-science-portfolio/tree/main/assignment-work/assignment-02)
</div>

<section>
  <div class="section-heading">
    <p class="eyebrow">Featured project</p>
    <h2>U.S. nonfarm employment recovery, 2019-2023</h2>
    <p>How recovery differed across industries and states after the COVID-19 employment shock.</p>
  </div>

  <div class="content-card" markdown="1">
### Research question

> How did U.S. nonfarm payroll employment change across major industries and states between January 2019 and April 2023, and which industries and states recovered most strongly after the COVID-19 employment shock?

### Data and validation

- BLS Current Employment Statistics for national and industry series;
- BLS State and Area Employment for 51 state-level series;
- FRED `PAYEMS` as an independent check of the national total;
- 12 national series and 51 state series covering January 2019 through April 2023.

Automated checks confirmed complete series coverage, no duplicate observations, no non-positive employment values, a valid baseline, and agreement between the sector sum and FRED national total within 2.068%.

### Main findings

- National employment fell **14.7%** from January 2020 to April 2020.
- By April 2023, employment was **2.2% above** the pre-shock peak.
- Strongest sectors: Construction **+5.7%**, Professional and business services **+5.6%**, Information **+4.4%**.
- Weakest sectors: Mining and logging **-8.7%**, Other services **-1.8%**, Government **-0.7%**.
- Strongest state recoveries: Idaho, Utah, Texas, Nevada, Florida.
- Weakest state recoveries: Hawaii, Vermont, District of Columbia, Rhode Island, New York.

The project is descriptive. Payroll employment counts jobs, the series are seasonally adjusted and subject to revision, and the analysis does not identify causal policy effects.
  </div>

  <figure class="project-figure">
    <img src="{{ '/assets/images/assignments/assignment-02-employment-recovery.png' | relative_url }}" alt="Integrated chart of U.S. nonfarm employment recovery by industry and state">
    <figcaption>Integrated visual narrative combining the national employment trend, industry recovery, and state-level patterns.</figcaption>
  </figure>

  <div class="hero-actions">
    <a class="button" href="https://github.com/dee663385/data-science-portfolio/blob/main/assignment-work/assignment-02/project/analysis.ipynb">View analysis notebook</a>
    <a class="button secondary" href="https://github.com/dee663385/data-science-portfolio/blob/main/assignment-work/assignment-02/project/revised-proposal.md">Read revised proposal</a>
  </div>
</section>

<section>
  <div class="section-heading">
    <p class="eyebrow">Lab 01</p>
    <h2>Automobile sales visualisation</h2>
    <p>Twelve visual-analysis tasks using pandas, Matplotlib, Seaborn, and Folium.</p>
  </div>

  <figure class="project-figure">
    <img src="{{ '/assets/images/assignments/assignment-02-gdp-comparison.png' | relative_url }}" alt="Subplots comparing GDP during recession and non-recession periods">
    <figcaption>Recession and non-recession GDP patterns shown with coordinated line plots.</figcaption>
  </figure>

  <div class="content-card" markdown="1">
The lab covers time trends, advertising expenditure, vehicle-type comparisons, seasonality, consumer confidence, price, unemployment, pie charts, and an optional geographic map.

[View Lab 01 notebook](https://github.com/dee663385/data-science-portfolio/blob/main/assignment-work/assignment-02/labs/lab-01-visualisation/automobile-sales-visualisation.ipynb)
  </div>
</section>

<section>
  <div class="section-heading">
    <p class="eyebrow">Lab 02</p>
    <h2>Interactive Dash dashboard</h2>
    <p>Yearly and recession-period reports controlled by dropdowns and callbacks.</p>
  </div>

  <figure class="project-figure">
    <img src="{{ '/assets/images/assignments/assignment-02-dashboard.png' | relative_url }}" alt="Automobile sales Dash dashboard showing yearly statistics">
    <figcaption>Yearly report view with four coordinated Plotly charts and a conditional year selector.</figcaption>
  </figure>

  <div class="content-card" markdown="1">
### Dashboard capabilities

- report-type selector for yearly or recession statistics;
- year selector enabled only for yearly reports;
- four interactive charts per report mode;
- coordinated sales, vehicle-type, advertising, and unemployment views.

[Dashboard source](https://github.com/dee663385/data-science-portfolio/blob/main/assignment-work/assignment-02/labs/lab-02-dashboard/dashboard.py)
  </div>
</section>

<section>
  <div class="section-heading">
    <p class="eyebrow">Attribution</p>
    <h2>Collaboration and limitations</h2>
  </div>

  <div class="content-card" markdown="1">
The revised employment project was pair work with Zhaowei; the partner's student ID is withheld from the public repository. WANG DI's stated responsibilities included coordination, visualisation design, proposal preparation, and final interpretation.

Lab 01 and Lab 02 began from course-provided activity templates. The submitted answers, chart implementations, dashboard code, and written interpretation are WANG DI's work.

**Repository:** [assignment-work/assignment-02](https://github.com/dee663385/data-science-portfolio/tree/main/assignment-work/assignment-02)
  </div>
</section>