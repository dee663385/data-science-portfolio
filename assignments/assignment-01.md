---
layout: default
title: Assignment 01
description: "Tourism revenue proposal and King County house-price analysis by WANG DI."
permalink: /assignments/assignment-01/
---

<div class="page-intro">
  <p class="eyebrow">Assignment 01</p>
  <h1>Tourism Revenue Proposal and House Sales Analysis</h1>
  <p class="muted">WANG DI · mc663385 · CISC7204 - Data Science</p>
</div>

<div class="content-card" markdown="1">
## What this assignment demonstrates

Assignment 01 combines project-design work with a completed predictive analysis. The pair proposal defines a question about Macao's tourism economy and plans a reproducible data workflow. The housing analysis then demonstrates exploratory analysis, linear regression, feature engineering, regularisation, and critical evaluation of model performance.

**Repository:** [assignment-work/assignment-01](https://github.com/dee663385/data-science-portfolio/tree/main/assignment-work/assignment-01)
</div>

<section>
  <div class="section-heading">
    <p class="eyebrow">Part 1</p>
    <h2>Preliminary tourism project proposal</h2>
  </div>

  <div class="content-card" markdown="1">
### Research question

> In Macao's tourism market from 2019 to 2025, is total tourism spending driven primarily by visitor volume or by visitors' spending willingness, and to what extent does hotel occupancy rate explain fluctuations in total spending?

### My contribution

- data collection and alignment across four public datasets;
- data cleaning and preparation;
- exploratory data analysis and visualisation planning;
- visual justification connecting each chart to the research question.

This was pair work with ZhaoWei. The partner's student ID is withheld from the public repository. The proposal defines the research design; it does not claim completed regression findings.

**Sources:** Macao SAR Government Open Data Portal datasets covering arrivals, per-capita spending, total spending, and hotel occupancy.

[Read the proposal](https://github.com/dee663385/data-science-portfolio/blob/main/assignment-work/assignment-01/proposal/preliminary-proposal.md)
  </div>
</section>

<section>
  <div class="section-heading">
    <p class="eyebrow">Part 2</p>
    <h2>House Sales in King County, USA</h2>
    <p>A completed regression workflow using 21,613 property records and 22 variables.</p>
  </div>

  <div class="content-card" markdown="1">
### Results

| Model | R-squared | Evaluation scope |
|---|---:|---|
| Price ~ longitude | 0.000468 | Full dataset |
| Price ~ `sqft_living` | 0.492853 | Full dataset |
| Multiple linear regression | 0.657695 | Full dataset |
| Scaled polynomial pipeline | 0.751341 | Full dataset |
| Ridge, alpha = 0.1 | 0.647876 | Held-out test set |
| Polynomial Ridge, degree = 2 | 0.700274 | Held-out test set |

The first four scores are in-sample. The final two scores use a held-out test set and provide the more credible evidence of generalisation.

### Key findings

- Waterfront properties show more and larger high-price outliers.
- `sqft_above` is positively correlated with price (`r = 0.6056`).
- Adding relevant features substantially improves explanatory power over longitude alone.
- Polynomial features and Ridge regularisation improve held-out predictive performance in this activity.
- Predictive R-squared does not establish causal effects.
  </div>

  <figure class="project-figure">
    <img src="{{ '/assets/images/assignments/assignment-01-waterfront.png' | relative_url }}" alt="Box plot comparing house prices for waterfront and non-waterfront properties">
    <figcaption>House price distribution by waterfront status. Waterfront homes show more extreme high-price outliers.</figcaption>
  </figure>

  <figure class="project-figure">
    <img src="{{ '/assets/images/assignments/assignment-01-sqft-above.png' | relative_url }}" alt="Regression plot of above-ground square footage and house price">
    <figcaption>Above-ground living area versus price, showing a positive relationship (`r = 0.6056`).</figcaption>
  </figure>

  <div class="hero-actions">
    <a class="button" href="https://github.com/dee663385/data-science-portfolio/tree/main/assignment-work/assignment-01">Open assignment folder</a>
    <a class="button secondary" href="https://github.com/dee663385/data-science-portfolio/blob/main/assignment-work/assignment-01/notebooks/house-sales-analysis.ipynb">View notebook</a>
  </div>
</section>