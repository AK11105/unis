# Masters Research — Europe 2027

A curated research portfolio for AI/ML Master's programmes in Europe, built with [MkDocs Material](https://squidfunk.github.io/mkdocs-material/).

## Local Preview

```bash
pip install -r requirements.txt
mkdocs serve
```

Then open `http://127.0.0.1:8000`.

## Deployment

Pushes to `main` auto-deploy to GitHub Pages via the included workflow.

## Structure

```
docs/              → MkDocs source (advisor-facing site)
research/          → Raw research data (source of truth)
  Universities/    → Detailed per-university research files
  00_SHORTLIST.md  → Master shortlist & criteria
  01_TARGET_UNIVERSITIES.md
  02_FACULTY_MATCH.md
  ME.md            → Profile & preferences
meta/              → Process artifacts (task specs, audits, validations)
```
