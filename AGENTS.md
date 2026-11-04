# AGENTS.md

Instructions for automation agents (Claude Code, Codex and similar) working in this repository.

## Repository

- **Name:** `orangeelefant/portfolio`
- **Purpose:** Public portfolio of the sites Webraketen builds and runs, published by GitHub Pages.
- **Live:** https://orangeelefant.github.io/portfolio/

## Rules

- Read `CLAUDE.md` and `TODO.md` before changing anything.
- Push directly to `main`. One logical change per commit.
- Never commit credentials. Reference secrets through environment variables.
- Every existing link to a client site keeps its URL and anchor text. The Webraketen backlink engine counts them.
- Public copy is Swedish unless the file is already in English.
- Add a line under `## [Unreleased]` in `CHANGELOG.md` for every change to content or configuration.
- The "Fler sajter" table in `README.md` is extended by the backlink engine.
