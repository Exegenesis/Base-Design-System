Contributing to Base Design System

Workflow

- Create small, focused branches (feat/ or fix/) per change.
- Open PRs with a concise description and a "why" section explaining the reason for the change.
- Add unit tests where applicable. Keep PRs under ~200 lines when possible.

Branch naming

- Use `feat/<short-name>` for features and `fix/<short-name>` for bug fixes.

Commit message guidance

- Start with a short scope and verb: `feat(theme): add dark theme variables`
- In the body include a "Why" paragraph explaining intent and any migration steps.

Releasing

- For now we version manually in package.json. When published, use semver.

CI

- This repo is private; CI will be added at the owner's discretion. Other projects should use GitHub Actions to run tests and linters on PRs.
