# CLAUDE.md — Life Library

## Mission

Build a local, searchable library for saved articles, files, videos and notes, with deduplication, source links, topic organization and a weekly resurfacing digest.

## Stack

- Python CLI or small local web app
- SQLite with FTS5
- Bookmark HTML/CSV import
- Readability extraction for accessible fixtures
- SHA-256 for file deduplication

## Rules

1. The library record and original source link come before extraction.
2. Normalize URLs before deduplication; hash local files.
3. Search must explain why an item matched.
4. Summaries may use only returned library records and must link to them.
5. Do not bypass paywalls, logins or platform restrictions.
6. Do not claim a video transcript exists unless it was supplied or provided by the source.
7. Keyword search must work before semantic features are added.
8. Keep personal notes visibly separate from source text.

## Definition of done

A 25-item sample library imports without false duplicates, searches across text and notes, answers topic queries with source lists, and generates a five-item weekly digest.
