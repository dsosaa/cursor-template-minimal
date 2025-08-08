# Project Documentation

This optional `docs/` directory provides templates for project documentation inspired by software engineering best practices.

## Quick Start
- Copy and rename templates as needed for your project
- Remove unused templates to keep things minimal
- Add language-specific docs (API specs, etc.) as your project grows

## Templates Included

### Core Project Documents
- `project-overview.md` - High-level project description and goals
- `architecture.md` - System design and component relationships  
- `technical-decisions.md` - Key technical choices and rationale

### Development Tracking
- `tasks.md` - Task backlog and progress tracking
- `decisions.md` - Decision log (lightweight ADRs)

## Usage with Cursor
Reference these docs in Cursor using `@docs/filename.md` to give AI context about your project structure, decisions, and goals.

**Example:** "Based on @docs/project-overview.md, implement the user authentication feature following the patterns in @docs/architecture.md"
