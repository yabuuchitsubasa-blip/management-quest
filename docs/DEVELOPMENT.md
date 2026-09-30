# Development Guide

## Team size
Designed for 3–4 contributors working in parallel.

## Suggested ownership
- Lead / Integration: Dashboard, architecture, final merge
- Frontend: Member Detail, HP Gauge, shared UI
- AI / Logic: Future HP, AI Analysis, Management Action
- Demo / UX: Recovery, mock data, transitions, demo polish

## Branch strategy
- main: stable demo
- feature/<scope>: feature work
- fix/<scope>: bug fixes

## Pull requests
- No direct feature pushes to main.
- One logical change per PR.
- Prefer small PRs.
- At least one teammate reviews shared-model or cross-cutting changes.

## Commit prefixes
- feat:
- fix:
- ui:
- refactor:
- docs:
- chore:
