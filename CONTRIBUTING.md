# Contributing

Contributions should improve the catalog without turning it into a noisy dump.

## Good Additions

- Active open-source projects with clear licenses or known license status.
- Public documentation, papers, or reference implementations.
- Tools that help research, privacy, custody, portfolio tracking, simulation, or governance.
- Clear notes on what a project is useful for and what it should not be used for.

## Required Entry Fields

Catalog entries in `data/repos.json` must include:

- `name`
- `url`
- `category`
- `assetClass`
- `integrationUse`
- `executionRisk`
- `privacyRisk`
- `whyIncluded`
- `notFor`
- `reviewedAt`

## Safety Rules

- No private financial details.
- No wallet material.
- No guaranteed-return language.
- No instructions to bypass human approval.
- No regulated advice.

Run:

```powershell
./scripts/validate-catalog.ps1
```
