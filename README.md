# tomorrow-labs

A personal innovation lab for building and experimenting with:
- Software Engineering
- Machine Learning
- AI/LLM Systems
- Data Engineering & Automation
- Prototypes and research-grade experiments

## Repo Structure
This is a monorepo that hosts multiple independent projects.

- `projects/` — all runnable projects (software, ml, ai)
- `shared/` — reusable libraries/utilities shared across projects
- `docs/` — notes, architecture, setup guides
- `templates/` — starter templates for new projects

## Conventions
- Default branch: `dev`
- Work happens on `feature/*` branches and is merged via PR into `dev`
- Data and secrets are never committed (use `.env` and external storage)

## Goals
Build practical, reusable systems and continuously learn by shipping real projects.
