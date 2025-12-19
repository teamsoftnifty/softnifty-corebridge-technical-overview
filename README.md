# 📘 Softnifty CoreBridge — Technical Overview (Docs-Only)

> **Public repository (docs-only):** This repo contains **non-sensitive** technical documentation and artefacts for **Softnifty AI‑Eco CoreBridge** — an eco‑efficient, AI‑assisted middleware designed to connect legacy core banking systems to modern payment rails, support ISO 20022 interoperability, and produce ESG/ECO telemetry for measurable operational efficiency.

✅ **Included:** Architecture diagrams, process flows, high-level documentation, sanitised UI/UX artefacts (screenshots/wireframes).  
🚫 **Excluded:** Runtime transaction engine source code, mapping repository contents, real message samples, endpoints, keys, certificates, AML/fraud thresholds, customer data.

---

## 🧭 What’s inside

- **🏗️ `architecture/`** — platform architecture artefacts (PDFs) + explanation.
- **🔁 `process-flows/`** — end‑to‑end process diagrams (design‑time, runtime flow, ESG reporting).
- **📚 `docs/`** — product overview, architecture notes, security model (high-level), glossary.
- **🎨 `design/`** — sanitised UI/UX screenshots, wireframes, and design system notes.

---

## 🔒 Safety & Sanitisation Rules (Non‑negotiable)

Before adding any file, confirm it contains **no**:
- secrets (`.env`, tokens, keys, certificates)
- real bank payloads / transaction samples
- internal endpoints, network addresses, routing priorities
- AML/fraud rules, thresholds, or sensitive compliance logic
- customer names, institutions, or identifiable data

If in doubt, **do not publish** — keep it in the private evidence repo instead.

---

## 🗂️ Recommended folder layout

```text
softnifty-corebridge-docs/
├── architecture/
│   ├── Architectural_Design_v01.pdf
│   └── README.md
├── process-flows/
│   ├── 01_Design_Mapping_Configuration_Process_v01.pdf
│   ├── 02_Runtime_Transaction_Process_v01.pdf
│   ├── 03_ESG_Reporting_Process_v01.pdf
│   └── README.md
├── docs/
│   ├── product-overview.md
│   ├── architecture.md
│   ├── security-model.md
│   ├── esg-metrics-model.md
│   ├── api-contracts.md
│   ├── glossary.md
│   └── README.md
├── design/
│   ├── ui-screenshots/
│   ├── wireframes/
│   └── README.md
└── README.md
```

---

## 🧩 Core principles (high-level)

### ✅ Design‑time intelligence, deterministic runtime
CoreBridge uses AI primarily at **design time** to propose and validate mappings. Approved mappings are versioned and published to a repository. Live transaction processing executes **pre‑computed mappings deterministically** for auditability and operational safety.

### 🌿 ESG/ECO telemetry by design
ECO telemetry is captured as part of the transaction lifecycle and aggregated into ESG metrics for operational optimisation and reporting.

---

## 📄 Quick links
- Architecture: `architecture/`
- Process flows: `process-flows/`
- Docs: `docs/`
- UI/UX artefacts: `design/`

---

## 📌 Status
This documentation repo is maintained as a **public, non‑sensitive technical overview**. The private repository contains deeper engineering artefacts and controlled‑access evidence.
