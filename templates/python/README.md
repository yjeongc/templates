# Python Project Template

A modern Python project template with uv, Ruff, pytest, and mypy.

## Setup

```bash
uv sync
```

## Commands

- Format: `uv run ruff format .`
- Lint: `uv run ruff check . --fix`
- Test: `uv run pytest --cov=src --cov-report=xml`
- Type check: `uv run mypy src`

## Codex Notes

- Project agent instructions live in `AGENTS.md`.
- This template uses explicit command-based checks (no Claude hook dependency).
