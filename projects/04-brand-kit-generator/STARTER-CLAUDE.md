# CLAUDE.md — Brand Kit Generator

## Mission

Build a generator that converts a validated business brief into a structured brand kit and a polished one-page brand sheet.

## Stack

- Local web app or CLI
- JSON schema for briefs and brand kits
- HTML/CSS export with print styles
- Optional AI generation constrained by the brief

## Rules

1. Strategy comes before colours and fonts.
2. `brand-kit.json` is the source of truth; exports are generated from it.
3. Every colour needs a name, HEX value, use and contrast note.
4. Voice rules require concrete examples.
5. Never invent testimonials, awards, credentials, years in business or guarantees.
6. Label logo work as direction unless a real logo file is supplied or designed.
7. Two different businesses must produce visibly different kits.
8. Keep a human review step before calling a kit client-ready.

## Definition of done

Two fictional business briefs generate complete, distinct, structured brand kits and polished one-page HTML sheets that can be printed to PDF.
