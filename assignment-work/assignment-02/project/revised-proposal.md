**U.S. Nonfarm Employment Recovery\
by Industry and State, 2019-2023**

**Project Proposal**

Prepared by: Wang Di (mc663385) and Zhaowei ([partner ID withheld])

Course: CISC7204

Class: F \| Pair: 04

Date: 24 October 2026

# **1. Project Title and Research Question**

**Project title:** *The Uneven Recovery of U.S. Nonfarm Employment: Industry and State Patterns, 2019-2023*

**Research question:** *How did U.S. nonfarm payroll employment change across major industries and states between January 2019 and April 2023, and which industries and states recovered most strongly after the COVID-19 employment shock?*

# **2. Region and Domain Category**

**Region:** United States, including the national total and state-level comparisons across all 50 states and the District of Columbia where complete data are available.

**Domain category:** Labor economics and macroeconomic employment, with emphasis on nonfarm payroll employment, industry composition, and regional labor-market recovery.

**Measure and period:** Monthly seasonally adjusted nonfarm payroll employment from January 2019 through April 2023, the latest common complete month available in the selected BLS and FRED series.

# **3. Project Purpose**

**Outcomes:** This project applies the course data-visualization workflow to a real labor-market issue. It will show how public data can be acquired, cleaned, analyzed, and presented as a clear evidence-based story. The project also supports my development in data analytics, public policy, and economic research.

**Skills:** The project will develop skills in data acquisition, validation, time-series preprocessing, exploratory analysis, visual design, and written interpretation. Python 3, pandas, matplotlib, seaborn, and folium will be used to compare national, industry, and state patterns.

**Knowledge:** The project will improve my understanding of nonfarm payroll employment, seasonal adjustment, percentage changes, baseline indexing, industry composition, and state-level labor-market differences. It will also strengthen my ability to separate descriptive evidence from unsupported causal claims.

# **4. Data Sources and Scope**

The analysis will use official public data from the following sources:

1.  **BLS Current Employment Statistics:** [<u>https://www.bls.gov/ces/data/home.htm</u>](https://www.bls.gov/ces/data/home.htm) - national total and major-industry payroll employment.

2.  **BLS State and Area Employment:** [<u>https://www.bls.gov/sae/data/home.htm</u>](https://www.bls.gov/sae/data/home.htm) - monthly nonfarm employment by state.

3.  **FRED All Employees, Total Nonfarm (PAYEMS):** [<u>https://fred.stlouisfed.org/series/PAYEMS</u>](https://fred.stlouisfed.org/series/PAYEMS) - independent cross-check for the national total.

# **5. Project Tasks**

**1. Define the scope and baseline.** Fix the 2019-2023 period, select major industries with complete monthly coverage, use seasonally adjusted series, and set January 2019 as the index baseline.

**2. Acquire and document the data.** Download the BLS and FRED series and record series identifiers, units, adjustment methods, retrieval dates, and source links.

**3. Clean and validate the data.** Parse dates, standardize industry and state labels, check missing values and duplicates, verify units, and confirm a common month range.

**4. Analyze employment change.** Calculate total trends, the COVID-19 peak-to-trough decline, recovery timing, percentage changes, and January 2019 = 100 indices.

**5. Build the visual narrative.** Create a national trend line, indexed industry lines, an industry-change bar chart, and a state-level choropleth map.

**6. Interpret the findings.** Explain the industry and state patterns, answer the research question, and discuss measurement limitations.

**7. Assemble the submission.** Complete the proposal and optional Python 3 notebook, check all figures and links, and prepare the final submission.

# **6. Deliverables and Planned Visualization**

The submission will include this proposal, at least two public dataset links, one final visualization, and a one-to-two-paragraph visual justification. An optional Python 3 Jupyter Notebook will document the complete analysis.

The final visual will combine a national employment trend line, an indexed industry comparison, an industry-change bar chart, and a state-level choropleth map. These views will show when the employment shock occurred, which industries recovered most strongly, and whether recovery differed across states.

The visual will answer the research question by connecting the national pattern with industry and geographic comparisons. It will provide descriptive evidence while clearly stating that payroll employment measures jobs rather than individual workers and does not by itself establish causal effects.

# **7. Criteria for Success**

- **Question alignment:** Every chart and interpretation directly addresses the stated research question and the 2019-2023 comparison.

- **Source quality:** At least two credible public dataset links are provided, with source, unit, adjustment method, and retrieval date documented.

- **Analytical accuracy:** Peak-to-trough changes, percentage changes, and index values are calculated correctly using a consistent period.

- **Visual clarity:** Titles, axis labels, units, legends, annotations, and comparable scales make the figures readable without the code.

- **Interpretation:** Findings distinguish patterns from causal claims and acknowledge payroll-job measurement, data revisions, seasonal adjustment, and missing-data limits.

- **Submission completeness:** All required sections, links, the final visual, and the visual justification are included.

# **8. Collaboration**

This is a pair project completed by Class F, Pair 04. The work is divided into complementary roles, while both members share responsibility for checking the analysis and approving the final submission.

- **Project Coordinator, Visualization Lead, and Instructor Liaison - Wang Di:** coordinates the timeline, communicates with the instructor, designs the integrated visualization, and prepares the proposal and final interpretation.

- **Data Lead, Project Scribe, and Progress Tracker - Zhaowei:** maintains the data-source log, prepares and validates the national and state datasets, documents analytical decisions, and tracks deadlines.

- **Shared responsibilities - both members:** review calculations and charts, interpret the findings, verify links, and approve the final submission.

Both members will use a shared project folder, document all data transformations, hold a weekly progress check, review each other's work, and resolve disagreements by checking the data or consulting the instructor.

# **References**

1\. U.S. Bureau of Labor Statistics. (n.d.). *Current Employment Statistics.* Retrieved October 24, 2026, from [<u>https://www.bls.gov/ces/data/home.htm</u>](https://www.bls.gov/ces/data/home.htm)

2\. U.S. Bureau of Labor Statistics. (n.d.). *State and Area Employment, Hours, and Earnings.* Retrieved October 24, 2026, from [<u>https://www.bls.gov/sae/data/home.htm</u>](https://www.bls.gov/sae/data/home.htm)

3\. Federal Reserve Bank of St. Louis. (n.d.). *All Employees, Total Nonfarm \[PAYEMS\]. FRED.* Retrieved October 24, 2026, from [<u>https://fred.stlouisfed.org/series/PAYEMS</u>](https://fred.stlouisfed.org/series/PAYEMS)

