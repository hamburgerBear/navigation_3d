# Contributing

## Branching

- Base new work on `develop`.
- Prefer topic branches instead of working directly on `develop`.
- Name branches as `<type>/<short-kebab-description>`.
- Allowed branch types: `feature`, `fix`, `docs`, `refactor`, `test`, `chore`, `release`.
- Examples:
  - `feature/bootstrap-engineering-foundation`
  - `fix/world-model-bounds-check`
  - `docs/add-planning-workflow`
- Merge stable release-ready work into `main`.

## Commits

Use Conventional Commits:

- `feat:`
- `fix:`
- `docs:`
- `refactor:`
- `test:`
- `chore:`

Examples:

- `feat: add traversability scoring interface`
- `fix: handle empty terrain patch in planner`

## Pull Requests

- Keep pull requests focused.
- Describe the motivation, technical approach, and validation.
- Link to related plan or spec documents when the change affects architecture.
- Avoid mixing refactors with feature delivery unless required.

## Validation

Before opening a pull request, run the smallest relevant checks available for the change:

- formatting
- static checks
- build
- tests
