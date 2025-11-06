---
title: "SOC 2 Trust Services Criteria – Requirement to Documents Mapping"
doc_type: "Mapping"
id: "GRS-AUD-MAP-SOC2-REQ2DOCS"
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
  - ../catalogs/SOC2-TSC.md
---

## Document Control

| Field | Value |
|-------|-------|
| Title | SOC 2 Trust Services Criteria – Requirement to Documents Mapping |
| Document ID | GRS-AUD-MAP-SOC2-REQ2DOCS |
| Version | 1.0.0 |
| Status | Draft |
| Owner | GRC Analyst |
| Program Manager | Josh Mayorga, Compliance Manager |
| Approver | ISMS Manager |
| Approval Date |  |
| Effective Date |  |
| Next Review Date |  |

## Purpose

Map SOC 2 TSC criteria to GridSite documents (Primary, Supporting) with evidence examples.

## Mapping (seed)

| Standard | Requirement ID | Title | Primary Documents | Supporting Documents | Evidence (examples) | Notes |
|----------|-----------------|-------|-------------------|----------------------|---------------------|-------|
| SOC 2 | CC1.1 | Control Environment | [P01 IS Policy](../../policies/Information-Security-Policy.md); [P34 Quality & Document Control](../../policies/Quality-and-Document-Control-Policy.md) | [PR46 Management Review](../../procedures/Management-Review-Procedure.md) | Policy approvals, org charts, MR minutes. |  |
| SOC 2 | CC2.1 | Communication and Information | [P36 Email & Communications](../../policies/Email-and-Communications-Security-Policy.md) | [P60 Metrics & CI](../../policies/Metrics-and-Continuous-Improvement-Policy.md) | Communications, reporting, dashboards. |  |
| SOC 2 | CC3.2 | Risk Assessment | [P03 Risk Management](../../policies/Risk-Management-Policy.md) | [PR02 Risk Assessment Procedure](../../procedures/Risk-Assessment-Procedure.md) | Risk register, heatmaps, decisions. |  |
| SOC 2 | CC6.1 | Logical Access | [P08 IAM Policy](../../policies/Identity-and-Access-Management-Policy.md); [P64 Access Control Policy](../../policies/Access-Control-Policy.md) | [PR04 Access Provisioning/Deprovisioning](../../procedures/Access-Provisioning-and-Deprovisioning-Procedure.md) | Access reviews, RBAC matrices. |  |
| SOC 2 | CC6.3 | Authentication | [P09 Authentication & MFA](../../policies/Authentication-and-MFA-Policy.md) | [S06 Identity & PAM Standard](../../standards/Identity-and-PAM-Standard.md) | MFA configs (Duo), step-up rules. |  |
| SOC 2 | CC7.2 | Monitoring and Detection | [P21 Logging & SIEM](../../policies/Logging-Monitoring-and-SIEM-Policy.md) | [PR20 Alert Triage](../../procedures/Alert-Triage-and-Escalation-Procedure.md); [PR42 Continuous Monitoring](../../procedures/Continuous-Control-Monitoring-Procedure.md) | Alerts, runbooks, tuning logs. |  |
| SOC 2 | A1.1 | Availability | [P23 BCMS Policy](../../policies/Business-Continuity-Policy.md); [P25 Backup & Restore](../../policies/Backup-and-Restore-Policy.md) | [S08 Backup & Immutability](../../standards/Backup-and-Immutability-Standard.md); [PL05 DR Plans](../../plans/Disaster-Recovery-Plans.md) | Uptime reports, restore tests. |  |
| SOC 2 | C1.1 | Confidentiality | [P06 Data Classification & Handling](../../policies/Data-Classification-and-Handling-Policy.md) | [S12 Data Classification Marking](../../standards/Data-Classification-Marking-Standard.md); [P55 Customer Data Handling](../../policies/Customer-Data-Handling-and-Confidentiality-Policy.md) | Labels, DLP logs, NDAs. |  |

## Revision History

| Version | Date       | Author | Description |
|---------|------------|--------|-------------|
| 1.0.0   | 2025-11-05 |        | Seeded SOC 2 TSC mappings. |


