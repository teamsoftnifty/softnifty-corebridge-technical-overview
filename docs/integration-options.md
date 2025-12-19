# 🔌 Integration Options (Public)

This page describes public-safe ways CoreBridge can integrate with existing banking environments, without exposing sensitive implementation details.

---

## Integration principles
- non-disruptive modernisation
- deterministic runtime execution driven by approved configs
- security-by-design and auditability
- incremental onboarding to reduce risk

---

## Typical integration touchpoints (conceptual)

### CBS connectivity
- APIs (REST/HTTPS) where available
- file-based exchanges (e.g., SFTP) where appropriate
- message middleware (queues/brokers) for async processing
- adapters for normalisation into canonical formats

### Payment rails connectivity
- outbound adapters aligned to required network formats (public-safe)
- protocol handlers (implementation-dependent)

### IAM integration
- role-based access control
- SSO alignment where applicable (implementation-dependent)

### Observability & reporting
- dashboards for operational and ESG/ECO views
- exports to BI tools (public-safe)

---

## Onboarding approach (recommended)
1. discovery → 2. design-time config → 3. validation sandbox → 4. pilot → 5. scale

---

## Intentionally omitted
- endpoint details
- customer/vendor-specific connector specifics
- routing priorities and thresholds
