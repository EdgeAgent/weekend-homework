# CLAUDE.md — Personal Dashboard

## Mission

Build a local-first personal dashboard that creates a factual morning briefing from a calendar file/feed, a task file and a manually supplied inbox digest.

## Stack

- Python 3.11+
- FastAPI or Flask
- SQLite or a JSON snapshot
- `icalendar`
- Server-rendered HTML/CSS

## Rules

1. Build one step at a time and show the verification command for each step.
2. Use sample data until every adapter works.
3. Keep calendar, task, inbox and briefing logic in separate modules.
4. Generate facts deterministically before using any AI summary.
5. AI is optional and local through Ollama. The app must work without it.
6. Never ask for or store an email password.
7. Keep time-zone handling explicit.
8. Do not commit real personal data or credentials.

## Definition of done

The dashboard and Markdown briefing show today’s events, conflicts, top tasks, deadlines and inbox actions from the same normalized data, and both can be regenerated with one command.
