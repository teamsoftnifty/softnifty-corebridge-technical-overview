# Security Model (High-Level)

CoreBridge is designed for regulated environments. This document outlines the security posture at a high level.

## Principles
- **Least privilege** for access controls
- **Fail closed** on validation and policy checks
- **Auditability**: immutable logs and traceable transaction lifecycle events
- **Separation of duties**: design-time configuration vs runtime execution

## What is intentionally omitted
To protect operational security and IP, this public document does not include:
- implementation details of AML/fraud thresholds
- encryption key management specifics
- internal endpoints, network topology, or routing priorities
