# WANG DI - Data Science Portfolio

Public portfolio for **WANG DI (mc663385)**, CISC7204 - Data Science, University of Macau.

## Live site

https://dee663385.github.io/data-science-portfolio/

## Purpose

This repository hosts a GitHub Pages portfolio that presents:

- my data science background and technical skills;
- a detailed summary of the Semester Project;
- links to reproducible notebooks and project repositories;
- an optional Assignment 01 and Assignment 02 showcase.

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
│   ├── assignment-01.md        # Bonus showcase template (disabled by default)
│   └── assignment-02.md        # Bonus showcase template (disabled by default)
└── _submission/                # Private working drafts, excluded from the site
```

## Local preview

GitHub Pages renders the Markdown and the custom `default` layout. To check the site:

1. Edit Markdown or CSS files.
2. Commit and push to `main`.
3. Wait for GitHub Pages to rebuild.
4. Open the live site and test all links.

## Updating the bonus showcase

1. Complete and publish Assignment 01 and/or Assignment 02.
2. Set `bonus_ready: true` in `_config.yml`.
3. Fill in the four assignment URL fields.
4. Remove `published: false` from the relevant files in `assignments/`.
5. Verify every link in an incognito browser window.

## Submission drafts

Forum-post and reflection drafts are stored in `_submission/`. This folder starts with an underscore and is excluded from the generated website.
