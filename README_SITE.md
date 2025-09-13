README — Site build workflow

- Source of truth: `docs/` (edit these Markdown files).
- Build the site locally: `pip install mkdocs-material mkdocs && mkdocs build`.
- Generated output is `site/` (now archived in the `site-archive` branch).
- To publish: CI or run `mkdocs gh-deploy` or upload the `site/` output.

Notes:
- Do not edit files under `site/` in the repository; they are generated output.
- If you need to recover the last published site, it is available in the `site-archive` branch.
