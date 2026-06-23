---
name: wealth-research
description: Use when mapping public wealth, custody, portfolio, privacy, and OSS finance tooling for an Agentic Wealth OS without using private financial data.
---

# Wealth Research

Use this skill to curate public-safe sources for a private Agentic Wealth OS.

## Inputs

1. Public GitHub repos and official documentation.
2. Public catalogs in `data/repos.json`.
3. Existing selection criteria in `docs/selection-matrix.md`.

## Rules

- Treat outputs as research organization, not advice.
- Prefer active primary sources.
- Keep private positions, accounts, wallets, and strategy out of the repo.
- Mark execution-adjacent and custody-adjacent tools clearly.
- Never suggest live capital movement or wallet signing.

## Output Shape

Return:

- source
- category
- why it matters
- integration use
- execution risk
- privacy risk
- what it is not for
- next review action
