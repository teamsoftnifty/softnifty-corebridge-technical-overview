# Architecture Notes (Public)

This document explains the architecture diagram in `/architecture/Architectural_Design_v01.pdf`.

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
