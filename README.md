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

## Documentation (Optional)

The `docs/` directory provides basic templates for project context:
- `project-overview.md` - Goals and scope
- `architecture.md` - System design  
- `technical-decisions.md` - Key choices
- `tasks.md` - Current priorities

Reference in Cursor: `@docs/filename.md`

## Suggested Project Structure

```
your-project/
├── .cursorrules          # AI behavior rules
├── .cursorignore         # Files to ignore
├── .vscode/              # Editor settings
├── docs/                 # Project documentation (optional)
│   ├── project-overview.md
│   ├── architecture.md
│   └── tasks.md
├── src/                  # Source code
├── tests/                # Test files
├── config/               # Configuration files
└── README.md
```

## Compatible With
Cursor, VS Code, Windsurf, GitHub Copilot

## Philosophy

- Keep base minimal and portable
- Add only what the project needs
- Prefer clarity, safety, and incremental edits
- Document decisions for better AI context
