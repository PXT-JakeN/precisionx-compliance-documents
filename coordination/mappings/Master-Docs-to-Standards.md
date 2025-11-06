---
title: "Master Mapping – Documents to Standards and Requirements"
doc_type: "Mapping"
id: "GRS-ISMS-MAP-MASTER"
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
  - ./ISO27001-AnnexA-Docs-to-Req.md
  - ./ISO27001-AnnexA-Req-to-Docs.md
  - ./ISO22301-Req-to-Docs.md
  - ./SOC2-TSC-Req-to-Docs.md
  - ./SOC1-ICFR-Req-to-Docs.md
---

## Document Control

| Field | Value |
|-------|-------|
| Title | Master Mapping – Documents to Standards and Requirements |
| Document ID | GRS-ISMS-MAP-MASTER |
| Version | 1.0.0 |
| Status | Draft |
| Owner | GRC Analyst |
| Program Manager | Josh Mayorga, Compliance Manager |
| Approver | ISMS Manager |
| Approval Date |  |
| Effective Date |  |
| Next Review Date |  |

## Purpose

Provide a single cross-standard view listing each document with the applicable standards and requirement IDs.

## Mapping (seed)

| Document | Doc ID | Type | Applies To Standards | Requirement ID(s) | Owners | Evidence Systems | Manual Export Needed |
|----------|--------|------|-----------------------|-------------------|--------|-------------------|----------------------|
| [P01 Information Security Policy](../../policies/Information-Security-Policy.md) | P01 | Policy | ISO 27001, SOC 2 | A.5.1, A.5.2; CC1.1 | ISMS Manager | Confluence/Repo, Approvals | No |
| [P34 Quality & Document Control](../../policies/Quality-and-Document-Control-Policy.md) | P34 | Policy | ISO 27001, SOC 2 | A.5.1; CC1.1 | ISMS Manager | Repo history | No |
| [P08 IAM Policy](../../policies/Identity-and-Access-Management-Policy.md) | P08 | Policy | ISO 27001, SOC 2 | A.5.2, A.8.2; CC6.1 | Security Eng Lead | Entra ID, Access Reviews | No |
| [P09 Authentication & MFA](../../policies/Authentication-and-MFA-Policy.md) | P09 | Policy | SOC 2, ISO 27001 | CC6.3; A.8.2 (support) | Security Eng Lead | Duo, Entra ID | No |
| [P21 Logging & SIEM](../../policies/Logging-Monitoring-and-SIEM-Policy.md) | P21 | Policy | ISO 27001, SOC 2 | A.8.15, A.8.16; CC7.2 | SecOps Lead | SIEM | Yes (for non-forwarding) |
| [S07 Logging & Time Sync](../../standards/Logging-and-Time-Sync-Standard.md) | S07 | Standard | ISO 27001 | A.8.15 | SecOps Lead | NTP, SIEM | Yes (some sites) |
| [S17 Facility Physical Security](../../standards/Facility-Physical-Security-Standard.md) | S17 | Standard | ISO 27001 | A.7.1, A.7.2 | Facilities Lead | Access Control, CCTV | Yes (exports) |
| [P23 BCMS Policy](../../policies/Business-Continuity-Policy.md) | P23 | Policy | ISO 22301, SOC 2 | Clauses 5–8; A1.1 | BC/DR Lead | Exercise Records | No |
| [PL05 DR Plans](../../plans/Disaster-Recovery-Plans.md) | PL05 | Plan | ISO 22301, SOC 2 | Clause 8; A1.1 | BC/DR Lead | DR Test Logs | No |
| [SD04 ICFR – Billing & Revenue](../../plans/ICFR-Narrative-Billing-and-Revenue.md) | SD04 | Narrative | SOC 1 | ICFR-REV-01..04 | Finance Controller | ERP, Ticketing | No |

## Revision History

| Version | Date       | Author | Description |
|---------|------------|--------|-------------|
| 1.0.0   | 2025-11-05 |        | Seeded master document-to-standard mapping. |


