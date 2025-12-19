# API Contracts (Abstract / Public-Safe)

This file provides abstract API shapes for discussion and alignment. It intentionally omits:
- real endpoints
- authentication secrets
- customer identifiers
- production schemas

## Example: Health
- `GET /health` → `{ status, version }`

## Example: Telemetry Query (abstract)
- `GET /telemetry/summary?from=...&to=...` → `{ period, counts, eco_metrics }`
