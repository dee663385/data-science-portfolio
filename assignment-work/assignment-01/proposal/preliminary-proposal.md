**Project Proposal**

Student ID：[partner ID withheld]

Name： ZhaoWei

Course code：CISC7204

Course title：data science and data visualization

Coursework item：Assignment 01: Preliminary Project Proposal - Pair

|                          |            |              |
|--------------------------|------------|--------------|
| Pair Partner Information | Student ID | Student Name |
| My Information           |  MC663385  |  Wang Di     |
| My Partner's Information |  [partner ID withheld]  |  ZhaoWei     |

**1. Project Topic Name**

**Title:** Analyzing the Drivers of Tourism Revenue in Macao: An Empirical Study Based on Visitor Volume and Spending Behavior

**Research question:** In Macao's tourism market from 2019 to the 2025, is the variation in total tourism spending driven primarily by **visitor volume (total arrivals)** or by **visitors' spending willingness (per-capita spending)**? And to what extent does hotel occupancy rate, as a control variable, explain the fluctuations in total tourism spending?

**Region and domain category:** Macao Special Administrative Region, China × Tourism & Hospitality.

**2. Project Purpose**

**a. Outcomes**: This project directly addresses the course learning outcomes — exploratory data analysis (EDA), selecting and producing the four categories of visualization plots (Comparison / Relation / Composition / Distribution), and interpreting regression models with R². It is also directly relevant to my career plan of becoming a data analyst / data scientist.

**b. Skills**: This project will help me practice the following essential skills: cleaning, merging, and aligning multiple data sources on a consistent timeline; hands-on Python programming (Pandas / Matplotlib / Seaborn / Scikit-learn); building and evaluating multiple linear regression models; and turning analytical results into a data-driven story through both writing and visualization.

**c. Knowledge**: This project will deepen my familiarity with the structure of Macao's tourism economy and its pre- and post-pandemic market shifts; the assumptions of linear regression and the meaning of R²; correlation and multicollinearity among variables; and visualization design principles (which chart type fits which analytical purpose).

**3. Project Tasks**

**Specific steps and deliverables:**

|  |  |
|----|----|
| **Step** | **Description** |
| T1 Data collection & alignment | Download 4 datasets from the Macao SAR Government Open Data Portal (all first published on 2019-06-12, with highly overlapping time spans); aggregate them to a consistent **quarterly frequency** and merge them into one master table by "year-quarter" |
| T2 Data cleaning | Handle missing values and outliers, especially the extreme values during the 2020–2022 pandemic period |
| T3 EDA & visualization | Line charts (time trends), scatter-plot matrix + heatmap (variable relationships), box plots (distribution), bar charts (year/quarter comparison) — **covering all four plot categories taught in the course** |
| T4 Regression modeling | Build a multiple linear regression model: Total Spending = β₀ + β₁(Visitor Arrivals) + β₂(Per-capita Spending) + β₃(Hotel Occupancy) + ε; compute R² and adjusted R²; plot actual vs. predicted values and residual plots |
| T5 Justification & report | Write a 1–2 paragraph justification explaining how the visualizations address the research question; compile the final report |
| T6 (Optional) | Upload one representative image that directly addresses the research question, plus a reproducible Python 3 Jupyter Notebook containing all charts and the model |

**Guides and requirements to follow:** Course Tutorial 04-02 notes (Pandas Basics), Requirements 1–7 of the Ideation page, and the five components of the Project Guideline.

**Data sources:**

|  |  |  |  |
|----|----|----|----|
| **Type** | **Variable** | **Dataset** | **Link** |
| Dependent (Y) | Total visitor spending | 03_Total Visitor Spending | \[https://data.gov.mo/Detail?id=6466a42d-cd30-40a3-9017-3e0066e6b077\] |
| Independent (X1) | Total visitor arrivals | 01_Visitor Arrivals | \[https://data.gov.mo/Detail?id=3546225a-2a34-4645-b01e-6752aed03993\] |
| Independent (X2) | Per-capita visitor spending | 02_Per-capita Visitor Spending | \[https://data.gov.mo/Detail?id=f02b334a-cc44-4433-b942-672de0fdad13\] |
| Control (X3) | Hotel occupancy rate | 04_Hotel Occupancy Rate | \[https://data.gov.mo/Detail?id=8812ecc5-e9ab-4e2f-b971-d3c16e46bd32\] |

**4. Criteria for Success**

Successful deliverables will meet the following characteristics, verified with a self-check checklist:

- **Data:** The quarterly merged table has a complete timeline (from 2019Q2), with no missing values or misalignment across the four variables;

- **Visualization:** At least the four course plot categories are used; every chart has a title, axis labels, and necessary annotations;

- **Modeling:** R² and adjusted R² are reported, with actual-vs-predicted and residual plots; the interpretation of R² explicitly ties back to the research question ("volume vs. spending");

- **Justification:** A 1–2 paragraph written argument clearly explains how the charts answer the research question;

  **Final presentation**: A consolidated dashboard-style visual (final visual) tells the complete story of the project using the data collected, analyzed, and interpreted.

  **5.** **Project Collaboration**

  **a. Expected Division of Work:**

<table style="width:87%;">
<colgroup>
<col style="width: 12%" />
<col style="width: 75%" />
</colgroup>
<tbody>
<tr>
<td>Member</td>
<td>Responsibility</td>
</tr>
<tr>
<td>Wang Di</td>
<td><p>Data collection and data cleaning</p>
<p>Exploratory Data Analysis (EDA) and visualization</p></td>
</tr>
<tr>
<td>Zhao Wei</td>
<td><p>Regression modeling and statistical analysis</p>
<p>Report writing, presentation preparation, and project integration</p></td>
</tr>
</tbody>
</table>

**b. Ground Rules:**

All members are expected to attend weekly meetings.

Tasks should be completed before agreed deadlines.

Members should actively communicate progress and difficulties.

All major decisions will be discussed and agreed upon by the team.

Project files will be shared through a common repository or cloud storage.

**c.Group Structure**

|                                        |         |
|----------------------------------------|---------|
| Role                                   | Member  |
| Project Coordinator & Progress Tracker | ZhaoWei |
| Project Scribe & Project Liaison       | WangDi  |

Due to the small team size (two members), each member will undertake more than one project role.

**6. Limitations**

The data starts in 2019, giving only about 20–24 quarterly observations, which is a small sample for regression analysis. If the R² proves unstable, the project will emphasize EDA and interpret the regression results cautiously, or switch to monthly data to increase the sample size (while accounting for seasonal fluctuations).

**7. Justification: How the Visualizations Address the Research Question**

This project uses line charts to show the time trends of visitor arrivals, total spending, per-capita spending, and occupancy rate from 2019 to 2025, revealing the structural shifts before, during, and after the pandemic — answering "what happened in the market." A scatter-plot matrix and heatmap then expose the strength of relationships among variables, answering "which factor is most closely associated with total spending." Finally, the regression model's actual-vs-predicted scatter plot (annotated with R²) quantifies each factor's explanatory power and directly answers the core research question: if the coefficient and contribution of β₁ (visitor arrivals) are significantly larger than those of β₂ (per-capita spending), we can conclude that Macao's tourism revenue still relies heavily on visitor volume rather than high per-capita consumption. These three layers of visualization progress from description to explanation, ensuring that every chart serves the research question rather than merely decorating the report.

