# DAO Governance Radar Architecture

## Purpose

Decision intelligence layer for proposals, delegate blocs, vote risk, and execution monitoring.

## Runtime loop

1. **Observe** — collect domain signals: quorum_gap_pct, delegate_concentration, treasury_impact_usd, execution_delay_days, sentiment_shift.
2. **Orient** — map the active scenario to specialist agent responsibilities.
3. **Decide** — score severity, confidence, and operator urgency.
4. **Act** — emit next actions that a human operator can verify.
5. **Reflect** — attach trace IDs and deterministic evidence for review.

## Components

- `backend/swarm.py` — pure Python reasoning core, safe for CI and static demos.
- `backend/app.py` — FastAPI wrapper for product integration.
- `cli.py` — terminal demo path for reviewers.
- `index.html` — front-facing dashboard surface.

## Agent responsibilities

- `Proposal Summarizer`: owns one part of the analysis loop.
- `Delegate Bloc Mapper`: owns one part of the analysis loop.
- `Quorum Forecaster`: owns one part of the analysis loop.
- `Execution Risk Reviewer`: owns one part of the analysis loop.
- `Comms Brief Writer`: owns one part of the analysis loop.

## Production extension points

- Replace deterministic signals with live connectors.
- Persist reports in Postgres or SQLite.
- Add auth and organization workspaces.
- Add export hooks for Slack, Discord, Telegram, or email.
