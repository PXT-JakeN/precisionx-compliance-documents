---
title: "SOC 2 Trust Services Criteria – Catalog"
doc_type: "Catalog"
id: "GRS-AUD-CAT-SOC2"
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
  - ../COORDINATION_REVIEW_PLAN.md
---

## Document Control

| Field | Value |
|-------|-------|
| Title | SOC 2 Trust Services Criteria – Catalog |
| Document ID | GRS-AUD-CAT-SOC2 |
| Version | 1.0.0 |
| Status | Draft |
| Owner | GRC Analyst |
| Program Manager | Josh Mayorga, Compliance Manager |
| Approver | ISMS Manager |
| Approval Date |  |
| Effective Date |  |
| Next Review Date |  |

## Purpose

Reference list of SOC 2 Trust Services Criteria (Security, Availability, Confidentiality; Privacy optional) to support
requirement mapping.

## Criteria List

| Standard | Requirement ID | Title | Category | Primary Documents | Supporting Documents | Evidence (examples) |
|----------|-----------------|-------|----------|-------------------|----------------------|---------------------|
| SOC 2 | CC1.1 | Control Environment | Security | [P01](../../policies/Information-Security-Policy.md); [P34](../../policies/Quality-and-Document-Control-Policy.md) | [PR46](../../procedures/Management-Review-Procedure.md); [PL09](../../plans/Audit-and-Assessment-Plan.md) | Policy approvals; MR minutes; org chart. |
| SOC 2 | CC2.1 | Communication and Information | Security | [P36](../../policies/Email-and-Communications-Security-Policy.md) | [P60](../../policies/Metrics-and-Continuous-Improvement-Policy.md); [PL06](../../plans/Crisis-Communications-Plan.md) | Communications; status reports; dashboards. |
| SOC 2 | CC3.2 | Risk Assessment | Security | [P03](../../policies/Risk-Management-Policy.md) | [PR02](../../procedures/Risk-Assessment-Procedure.md); [R01](../../plans/Risk-Register.md) | Risk assessments; register; treatment decisions. |
| SOC 2 | CC6.1 | Logical Access | Security | [P08](../../policies/Identity-and-Access-Management-Policy.md); [P64](../../policies/Access-Control-Policy.md) | [PR04](../../procedures/Access-Provisioning-and-Deprovisioning-Procedure.md); [R04](../../plans/Access-Control-Matrix.md) | Access requests; RBAC; periodic reviews. |
| SOC 2 | CC6.3 | Authentication | Security | [P09](../../policies/Authentication-and-MFA-Policy.md) | [S06](../../standards/Identity-and-PAM-Standard.md) | Duo MFA configs; enrollment logs; session policies. |
| SOC 2 | CC7.2 | Monitoring and Detection | Security | [P21](../../policies/Logging-Monitoring-and-SIEM-Policy.md) | [PR20](../../procedures/Alert-Triage-and-Escalation-Procedure.md); [PR19](../../procedures/Logging-and-SIEM-Onboarding-Procedure.md) | SIEM alerts; runbooks; tuning records. |
| SOC 2 | A1.1 | Availability | Availability | [P23](../../policies/Business-Continuity-Policy.md); [P25](../../policies/Backup-and-Restore-Policy.md) | [PL05](../../plans/Disaster-Recovery-Plans.md); [S08](../../standards/Backup-and-Immutability-Standard.md) | Uptime reports; restore tests; exercise records. |
| SOC 2 | C1.1 | Confidentiality | Confidentiality | [P06](../../policies/Data-Classification-and-Handling-Policy.md) | [S12](../../standards/Data-Classification-Marking-Standard.md); [S24](../../standards/Data-Loss-Prevention-Standard.md) | Labels; DLP logs; access reviews. |

## Revision History

| Version | Date       | Author | Description |
|---------|------------|--------|-------------|
| 1.0.0   | 2025-11-05 |        | Seeded SOC 2 TSC catalog. |
| 1.1.0   | 2025-11-06 |        | Added Primary/Supporting/Evidence columns and seeded mappings. |


