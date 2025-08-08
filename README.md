# Cursor Minimal Template

Language-agnostic starter for new Cursor projects with shared editor hygiene and Cursor AI rules. Add language-specific tooling (TS/JS, Python, etc.) per project as needed.

## Included
- `.editorconfig`, `.gitattributes`, `.gitignore`
- `.vscode/settings.json`, `.vscode/extensions.json`
- `.cursorrules`, `.cursorignore`

## Use this template
- On GitHub: Click "Use this template" → create your new repo
- CLI: `gh repo create <name> --template <owner>/cursor-template-minimal --public`

## Add language tooling (optional per project)
- JS/TS: Prettier, ESLint, `tsconfig.json`
- Python: `pyproject.toml` (ruff/black/pytest)
- CI: GitHub Actions
- Dev env: `.devcontainer/` or Docker

## Philosophy
- Keep base minimal and portable
- Add only what the project needs
- Prefer clarity, safety, and incremental edits
