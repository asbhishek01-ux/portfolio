# AUDIT-page.md — Session 9 Portfolio

Oct 14, 2026 · @Abhishek

Portfolio audit for Abhishek Singh Chouhan's Session 9 personal portfolio page, verifying all content claims and technical validation.

## Content Audit

| Content | True? | Evidence / What was removed |
| --- | --- | --- |
| Name: Abhishek Singh Chouhan | Yes | Real name, appears once in the `<h1>` |
| About section | Yes | Written using provided background; no invented biography |
| Prompt Engineering | Yes | Skill learned/practiced — confirmed by user |
| Artificial Intelligence & Machine Learning | Yes | Skill learned/practiced — confirmed by user |
| Exploratory Data Analysis (EDA) | Yes | Skill learned/practiced — confirmed by user |
| Machine Learning Model Development | Yes | Skill learned/practiced — confirmed by user |
| Data Visualization | Yes | Skill learned/practiced — confirmed by user |
| Student Attrition Prediction | Yes | Actual project — confirmed by user |
| NoBrokerage.com Chatbot | Yes | Actual project — confirmed by user |
| Email / Phone / Social links | N/A | Placeholder `hello@example.com` used; no real contact details invented |
| GitHub project links | N/A | No GitHub links added; none were provided to verify |

## Technical Validation

| Check | Result | Notes |
| --- | --- | --- |
| Nu HTML Checker | 0 errors | Validated; standard HTML5 elements only, no deprecated attributes |
| Narrow-width (≈375px) | Pass | `@media (max-width: 600px)` breakpoint applied; single-column layout, stacked About meta card, full-width project cards |
| HTML and CSS are separate files | Pass | `index.html` and `style.css` delivered as two distinct files |
| No inline CSS | Pass | Zero `style="…"` attributes in `index.html`; all rules in `style.css` |
| Exactly one `<h1>` | Pass | Single `<h1>Abhishek Singh Chouhan</h1>` in the hero section |

## Outstanding Items

- **GitHub links:** No repository URLs were provided. The GitHub row is marked N/A. Once you have actual working links, add them to the project cards and update this row to Verified with the URLs.
- **Contact email:** `hello@example.com` is a placeholder. Replace it with your real address before sharing the portfolio publicly.
- **Published artifact note:** The Artifact publisher requires a single self-contained HTML file; `style.css` was inlined as a `<style>` block for publication only. The source `index.html` and `style.css` remain as separate downloadable files.
