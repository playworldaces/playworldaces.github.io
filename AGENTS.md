# Contributor guide

## Content boundary

- Publish game information only when it exists in the approved documentation cache.
- Never publish internal tools, scripts, API details, private data, tactical experiments, model output, or inferred engine behavior.
- Keep deployed output dependency-free: static HTML and CSS only.

## System design

| Concept | Location |
| --- | --- |
| Homepage and category index | `site/index.html:1` |
| Static wiki articles | `site/articles/*.html:1` |
| Shared visual system and responsive layout | `site/assets/styles.css:1` |
| GitHub Pages deployment | `.github/workflows/pages.yml:1` |
| Content and preview policy | `README.md:1` |
