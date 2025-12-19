# API Contracts (Abstract / Public-Safe)

This page provides abstract API shapes for discussion. It intentionally omits:
- real endpoints
- secrets
- customer identifiers
- production schemas

## Example: Health
- `GET /health` → `{ status, version }`

## Example: Telemetry Summary (abstract)
- `GET /telemetry/summary?from=...&to=...` → `{ period, counts, eco_metrics }`

## Example: Mapping validation (abstract)
- `POST /mappings/validate` → `{ status, issues[], warnings[] }`
