---
title: "ISO/IEC 27001:2022 Annex A – Document to Requirements Mapping"
doc_type: "Mapping"
id: "GRS-ISMS-MAP-27001-DOCS2REQ"
version: "1.0.0"
status: "Draft"
owner: "GRC Analyst"
program_manager: "Josh Mayorga, Compliance Manager"
approver: "ISMS Manager"
approval_date: ""
effective_date: ""
next_review_date: ""
classification: "Internal – Controlled"
organization: "GridSite Technology LLC and its operating subsidiaries"
related_documents:
  - ../catalogs/ISO27001-AnnexA.md
---

## Document Control

| Field | Value |
|-------|-------|
| Title | ISO/IEC 27001:2022 Annex A – Document to Requirements Mapping |
| Document ID | GRS-ISMS-MAP-27001-DOCS2REQ |
| Version | 1.0.0 |
| Status | Draft |
| Owner | GRC Analyst |
| Program Manager | Josh Mayorga, Compliance Manager |
| Approver | ISMS Manager |
| Approval Date |  |
| Effective Date |  |
| Next Review Date |  |

## Purpose

Map each GridSite document to the Annex A requirements it addresses.

## Mapping (seed)

| Document | Doc ID | Type | Standard | Requirement ID(s) | Coverage Role | Evidence (examples) | Notes |
|----------|--------|------|----------|-------------------|---------------|---------------------|-------|
| [P01 Information Security Policy](../../policies/Information-Security-Policy.md) | P01 | Policy | ISO 27001 | A.5.1, A.5.2 | Primary | Approved policy, review records. |  |
| [P34 Quality & Document Control](../../policies/Quality-and-Document-Control-Policy.md) | P34 | Policy | ISO 27001 | A.5.1 | Primary | Document control logs, versioning. |  |
| [P03 Risk Management Policy](../../policies/Risk-Management-Policy.md) | P03 | Policy | ISO 27001 | A.5.1 (support), A.5.2 (support) | Supporting | Risk register, assessments. |  |
| [P08 IAM Policy](../../policies/Identity-and-Access-Management-Policy.md) | P08 | Policy | ISO 27001 | A.5.2, A.8.2 | Primary | Access reviews, RBAC records. |  |
| [P10 PAM Policy](../../policies/Privileged-Access-Management-Policy.md) | P10 | Policy | ISO 27001 | A.8.2 | Primary | PAM approvals, session logs. |  |
| [P07 Acceptable Use](../../policies/Acceptable-Use-Policy.md) | P07 | Policy | ISO 27001 | A.5.10 | Primary | AUP acknowledgements. |  |
| [S01 Workstation Baseline](../../standards/Workstation-Baseline.md) | S01 | Standard | ISO 27001 | A.8.1 | Primary | EDR/encryption reports. |  |
| [S06 Identity & PAM Standard](../../standards/Identity-and-PAM-Standard.md) | S06 | Standard | ISO 27001 | A.8.2 | Primary | Duo enrollments, session recording. |  |
| [P21 Logging & SIEM](../../policies/Logging-Monitoring-and-SIEM-Policy.md) | P21 | Policy | ISO 27001 | A.8.15, A.8.16 | Primary | SIEM configs, alerts, manual exports. |  |
| [S07 Logging & Time Sync](../../standards/Logging-and-Time-Sync-Standard.md) | S07 | Standard | ISO 27001 | A.8.15 | Primary | NTP settings, log forwarding. |  |
| [S17 Facility Physical Security](../../standards/Facility-Physical-Security-Standard.md) | S17 | Standard | ISO 27001 | A.7.1, A.7.2 | Primary | Badge logs, CCTV coverage. |  |

## Revision History

| Version | Date       | Author | Description |
|---------|------------|--------|-------------|
| 1.0.0   | 2025-11-05 |        | Seeded document-to-requirement mappings. |


