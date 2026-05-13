# Soc Ops Agent Instructions

## Development Checklist
Before commits or PRs:
- [ ] Lint: `uv run ruff check .`
- [ ] Test: `uv run pytest`
- [ ] Install: `uv sync` (if dependencies changed)

## Overview
Social bingo game: FastAPI backend + HTMX frontend. Players match questions for 5-in-a-row.

## Tech Stack
- Backend: FastAPI, sessions
- Frontend: HTMX, Jinja2
- Styling: Custom CSS utils (no frameworks)
- Testing: pytest
- Package: uv

## Commands
- Install: `uv sync`
- Test: `uv run pytest`
- Lint: `uv run ruff check .`
- Run: `uv run uvicorn app.main:app --reload --host 0.0.0.0 --port 8000`

## Architecture
- `app/main.py`: Routes
- `app/game_logic.py`: Bingo logic
- `app/game_service.py`: Sessions
- `app/models.py`: Models
- `app/data.py`: Questions
- `app/templates/`: HTMX views
- `app/static/css/app.css`: Utils

## Conventions
- Custom CSS utils over inline styles
- HTMX for updates, no full reloads
- Session-based games
- TDD: tests first

## Notes
- No Simple Browser; HTMX needs full browser
- Docs: [Contributing](CONTRIBUTING.md), [Workshop](workshop/)
- Agents: TDD for dev, UI Review for frontend

## Instructions
- [Frontend Design](.github/instructions/frontend-design.instructions.md)
- [CSS Utils](.github/instructions/css-utilities.instructions.md)
- [General](.github/instructions/general.instructions.md)
