---
title: "BCMS Strategy Plan"
doc_type: "Plan"
id: "GRS-ISMS-PLN-004"
version: "1.0.0"
status: "Draft"
owner: "BC/DR Lead"
program_manager: "Josh Mayorga, Compliance Manager"
approver: "Executive Management, GridSite Technology LLC"
approval_date: ""
effective_date: ""
next_review_date: ""
classification: "Internal – Controlled"
organization: "GridSite Technology LLC and its operating subsidiaries"
related_documents:
  - ../policies/Business-Continuity-Policy.md
  - ./BIA-Reports.md
  - ./Disaster-Recovery-Plans.md
  - ../standards/NOC-Build-Standard.md
---

## Document Control

| Field | Value |
|-------|-------|
| Title | BCMS Strategy Plan |
| Document ID | GRS-ISMS-PLN-004 |
| Version | 1.0.0 |
| Status | Draft |
| Owner | BC/DR Lead |
| Program Manager | Josh Mayorga, Compliance Manager |
| Approver | Executive Management, GridSite Technology LLC |
| Approval Date |  |
| Effective Date |  |
| Next Review Date |  |

## 1. Purpose

Translate BIA results into enterprise continuity strategies spanning people, facilities, technology, vendors, and
communications.

## 2. Strategy Principles

Cloud‑first workloads with segmentation; dual‑NOC operations with resilient AV link and surge participation; secure
tunnels to sites; prioritized wired workstations and UniFi Identity for Wi‑Fi; Duo‑protected SSH/RDP; immutable,
encrypted backups; supplier redundancy where feasible; evidence capture with manual exports as backup.

## 3. Strategy by Domain

- People: Cross‑training, role coverage, remote‑work readiness, workforce continuity (pandemic/long outage).
- Facilities: Physical security program with integrated portal/kiosk, guard terminal fallback, and audit logging.
- Technology: Multi‑AZ/region where viable, infra‑as‑code guardrails, CI/CD integrity, DLP and classification.
- Vendors: Tiering, exit strategies, alternative providers for critical services.
- Communications: Crisis comms plan, 24x7 NOC bridge, radio/SIP alerts, external stakeholder updates.

## 4. Exercising & Validation

Tabletop and technical exercises; restore tests; failovers; lessons learned feeding CAPA and strategy updates.

## 5. Governance & Review

Quarterly review in management meetings; annual refresh or after significant changes or incidents.

## 6. Revision History

| Version | Date       | Author | Description |
|---------|------------|--------|-------------|
| 1.0.0   | 2025-11-05 |        | Initial BCMS strategy plan. |


