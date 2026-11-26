# WANG DI - Data Science Portfolio

Public portfolio for **WANG DI (mc663385)**, CISC7204 - Data Science, University of Macau.

## Live site

https://dee663385.github.io/data-science-portfolio/

## Purpose

This repository hosts a GitHub Pages portfolio that presents:

- my data science background and technical skills;
- a detailed summary of the Semester Project;
- links to reproducible notebooks and project repositories;
- Assignment 01 and Assignment 02 showcases with project evidence and figures.

## Site structure

```text
.
├── _config.yml                 # Site details and controlled feature flags
├── _layouts/default.html       # Shared page layout
├── assets/css/style.css        # Portfolio styling
├── index.md                    # Portfolio home page
├── projects/
│   └── geospatial-z-cities.md  # Semester Project summary
├── assignments/
│   ├── assignment-01.md        # Portfolio showcase page
│   └── assignment-02.md        # Portfolio showcase page
├── assignment-work/
│   ├── assignment-01/          # Notebooks, proposal, data, and figures
│   └── assignment-02/          # Project, labs, data, results, and screenshots
└── _submission/                # Private working drafts, excluded from the site
```

## Local preview

GitHub Pages renders the Markdown and the custom `default` layout. To check the site:

1. Edit Markdown or CSS files.
2. Commit and push to `main`.
3. Wait for GitHub Pages to rebuild.
4. Open the live site and test all links.

## Updating the assignment showcases

1. Update the selected showcase page in `assignments/` and its source files in `assignment-work/`.
2. Confirm the repository URLs in `_config.yml`.
3. Test every figure and external link in an incognito browser window.
4. Commit and push to `main`.
5. Verify the generated page under `/assignments/`.

## Submission drafts

Forum-post and reflection drafts are stored in `_submission/`. This folder starts with an underscore and is excluded from the generated website.
