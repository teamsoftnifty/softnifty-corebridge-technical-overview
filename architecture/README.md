# 🏗️ Architecture

This folder contains high-level architecture artefacts for **Softnifty AI‑Eco CoreBridge**.

## What this diagram represents
CoreBridge is structured as a modular middleware with three logical layers:

1. **Design‑Time (Configuration & Intelligence)**
   - CoreBridge UI / Admin Console
   - AI Mapping Studio (mapping proposals + validation)
   - Mapping Repository (versioned configurations)
   - Rule & Policy Manager (routing, controls)
   - ESG/ECO Dashboard (visibility into metrics)

2. **Runtime Engine (Deterministic Transaction Processing)**
   - Protocol handling + normalisation/validation
   - Mapping execution using published configs
   - Business logic and policy enforcement
   - Security & trust controls (high level)
   - CoreRouter for routing decisions
   - ECO runtime telemetry capture

3. **Telemetry / Audit / Storage**
   - Transaction logs and audit trails
   - ESG metrics store and aggregation
   - BI/reporting surfaces

## Files
- `Architectural_Design_v01.pdf` — primary architecture diagram (public-safe version).

## Publishing rules
Only include diagrams that are:
- free from internal endpoints, credentials, or customer identifiers
- high-level enough to be public
- aligned with the docs in `/docs/`
