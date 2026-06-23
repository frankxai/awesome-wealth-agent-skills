# Selection Matrix

Score each candidate from 0 to 3 in each dimension. Prefer fewer, better entries.

| Dimension | 0 | 1 | 2 | 3 |
| --- | --- | --- | --- | --- |
| Source quality | Unknown | Public repo only | Docs plus active repo | Docs, active repo, strong community |
| Maintenance | Stale or archived | Occasional | Recently pushed | Active and mature |
| License clarity | Unknown | Restrictive | Clear but viral | Clear and integration-friendly |
| Research value | Weak | Narrow | Useful | Core substrate |
| Execution risk | Live-money focused | Execution-heavy | Can be read-only | Research/simulation first |
| Privacy posture | Extractive | Unclear | Self-hostable | Local/private-first |
| Agent fit | None | Manual only | Agent-readable | Agent-ready API or data model |

## Default Decisions

- OpenBB is the first OSS Bloomberg/data terminal seed.
- Ghostfolio and rotki are portfolio/privacy seeds, not execution engines.
- Safe is custody infrastructure research, not a license to automate signing.
- Trading and crypto bots belong in `awesome-investor-agent-skills`; this repo links them only at the architecture level.

## Risk Labels

- `research-only`: safe for public study and read-only workflows.
- `simulation`: useful for backtests or paper trading.
- `execution-adjacent`: can touch orders or wallets if misused; keep gated.
- `custody-adjacent`: can touch keys, wallets, or signing concepts; never store real secrets.
- `regulated-adjacent`: may be interpreted as financial advice; use disclaimer and human review.
