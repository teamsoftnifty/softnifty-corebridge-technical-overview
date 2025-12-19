# ✅ Compliance Scope (Public)

This page clarifies what **compliance areas CoreBridge is designed to support** at a **high level**, and what is intentionally out of scope for this public portal.

<div class="callout">
<b>Important:</b> This is an overview. Detailed control design, evidence artefacts, and environment-specific implementation details remain private and are shared under controlled access.
</div>

---

## What “compliance support” means here
CoreBridge supports regulated transaction environments by enabling:
- structured validation and policy enforcement (conceptual)
- auditability (traceability and logging)
- configurable controls and approval workflows (high-level)
- standards readiness for interoperability (including ISO 20022)

---

## Coverage areas (high-level)

### 1) Data protection and privacy
- minimisation of sensitive data exposure in logs (where applicable)
- access controls and separation of responsibilities
- secure handling of personal data (implementation-dependent)

### 2) Security and operational resilience
- authenticated administration (high-level)
- audit trails for configuration and transaction lifecycle
- operational visibility (monitoring/telemetry)
- fail-closed behaviour on validation/policy violations

### 3) Payments standards readiness
- message validation and normalisation
- mapping execution using approved configurations

### 4) ESG/ECO telemetry
- telemetry capture and aggregation to support reporting discussions

---

## What is NOT published here
- AML/fraud thresholds or rule logic
- customer identifiers or real transaction samples
- key management, detailed crypto design, network topology
- internal endpoints, routing priorities, vendor secrets
