# Architecture Notes (Public)

This page explains the conceptual architecture published in the `/architecture` folder.

## Layers
1. **Design-Time**
   - mapping configuration and validation
   - policy configuration and approvals

2. **Runtime**
   - deterministic processing using published configs
   - routing and status handling
   - telemetry capture

3. **Telemetry/Audit**
   - logs, audit trails, metrics storage and aggregation

## Design-time intelligence, deterministic runtime
CoreBridge uses AI primarily at **design time** to propose and validate mappings. Approved mappings are versioned and published. Runtime processing executes **deterministically** using the approved configurations to support auditability and operational safety.
