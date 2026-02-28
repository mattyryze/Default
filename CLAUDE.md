# CLAUDE.md

## Project Overview

**Default** is a new repository in its initial stage. It currently contains only a README and is ready for development.

- **Repository**: mattyryze/Default
- **Primary branch**: `master`

## Repository Structure

```
.
├── CLAUDE.md        # AI assistant guide (this file)
└── README.md        # Project README
```

## Development Workflow

### Branching

- The default branch is `master`.
- Feature branches should follow the naming convention: `feature/<description>` or `claude/<description>-<id>` for AI-assisted work.
- Always branch from `master` for new work.

### Commits

- Write clear, concise commit messages describing **why** the change was made, not just what changed.
- Keep commits focused — one logical change per commit.

### Pull Requests

- PRs should target `master`.
- Include a summary of changes and any relevant test plan.

## Conventions

### Code Style

- Follow the conventions of whatever language/framework is adopted for this project.
- Prefer readability and simplicity over cleverness.
- Avoid over-engineering; solve the problem at hand without unnecessary abstractions.

### File Organization

- Keep the root directory clean — configuration files and documentation only.
- Source code should go in a dedicated directory (e.g., `src/`).
- Tests should mirror the source structure (e.g., `tests/` or colocated with source files).

## Key Guidelines for AI Assistants

1. **Read before editing** — Always read a file before making changes to it.
2. **Minimal changes** — Only modify what is necessary. Don't refactor surrounding code unless asked.
3. **No unnecessary files** — Don't create files unless they are required to complete the task.
4. **Security first** — Never commit secrets, credentials, or `.env` files.
5. **Test your changes** — If a test framework is present, run tests after making changes.
6. **Preserve existing patterns** — Match the style and conventions already in use in the codebase.
