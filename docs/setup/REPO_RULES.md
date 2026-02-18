# Repo Rules (tonorrow-labs)

## Branching
- Default branch: dev
- Create branches as:
  - feature/<name>
  - bugfix/<name>
  - chore/<name>

## No secrets / no real data in git
- Never commit .env, keys, credentials
- Do not commit real datasets or model artifacts
- Keep data externally (S3/MinIO/Drive/local outside repo)
- Only small sample data is allowed inside a project (optional)

## Project layout
Each project under projects/* should have:
- README.md
- pyproject.toml (or requirements.txt)
- src/ and tests/ when applicable
