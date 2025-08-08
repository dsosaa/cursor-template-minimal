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

## Documentation Integration
The optional `docs/` directory provides templates for:
- `project-overview.md` - High-level goals and scope
- `architecture.md` - System design and patterns
- `technical-decisions.md` - Key technical choices
- `tasks.md` - Current priorities and backlog

Reference these in Cursor using `@docs/filename.md` for AI context.

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

## Cross-Platform Compatibility
This template works with:
- **Cursor** - Uses `.cursorrules` and `.cursorignore`
- **VS Code** - Respects `.vscode/` settings
- **Windsurf** - Compatible with rule formats
- **GitHub Copilot** - Works with editor settings

## Philosophy
- Keep base minimal and portable
- Add only what the project needs  
- Prefer clarity, safety, and incremental edits
- Document decisions for better AI context
