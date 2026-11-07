# CLAUDE.md — Daily Review Agent

## Mission

Build a local daily-review agent that combines task facts with a three-question reflection, stores dated Markdown reviews, and produces an evidence-based weekly pattern report.

## Stack

- Python CLI
- Markdown journal files with structured front matter or headings
- Deterministic analysis first
- Optional local summarization through Ollama

## Rules

1. Never overwrite an existing daily review.
2. Store the user’s reflection answers word-for-word.
3. Keep imported facts, user reflection and agent analysis visibly separate.
4. A weekly pattern must cite the dates that support it.
5. Do not turn one difficult day into a trend.
6. Keep the nightly flow to three questions.
7. The weekly report must work without a model.

## Definition of done

Seven sample daily reviews produce a weekly report that accurately detects repeated friction and recurring unfinished work, with dates attached.
