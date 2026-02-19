# Python Project Template (Codex)

## Project Structure
```
python/
├── src/           # Source code
├── tests/         # Test files
└── pyproject.toml # Project configuration
```

## Standard Commands (uv)
- Sync: `uv sync`
- Format: `uv run ruff format .`
- Lint: `uv run ruff check . --fix`
- Test: `uv run pytest --cov=src --cov-report=xml`
- Type check: `uv run mypy src`

## Code Style
- Use Ruff for formatting and linting
- Line length: 88 characters
- Quote style: double quotes

## Developer Workflow
- Run `uv sync` once after cloning.
- Run format/lint/type/test checks before finishing a change.
- Keep source code in `src/` and tests in `tests/`.

## Recommended VS Code Extensions
- `ms-python.python`
- `ms-python.vscode-pylance`
- `charliermarsh.ruff`
- `ms-python.mypy-type-checker`
- `ryanluker.vscode-coverage-gutters`
