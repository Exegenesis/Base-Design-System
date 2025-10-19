# @exegenesis/design-system

Shared base CSS tokens, utilities, and page templates used across Exegenesis projects.

This package exposes the compiled stylesheet at `css/base-theme.css` and includes `assets/` and `templates/` for quick scaffolding.

Usage

- Install from GitHub Packages or from the repository source.
- Include the stylesheet in your HTML:

```html
<link rel="stylesheet" href="node_modules/@exegenesis/design-system/css/base-theme.css">
```

Publishing

This repository includes a GitHub Actions workflow at `.github/workflows/publish.yml` to publish releases to the npm registry or GitHub Packages. Configure `NPM_TOKEN` or `GITHUB_TOKEN` in your repository secrets before enabling the workflow.

License: MIT
