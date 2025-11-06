---
title: "ISO/IEC 27001:2022 Annex A – Requirement to Documents Mapping"
doc_type: "Mapping"
id: "GRS-ISMS-MAP-27001-REQ2DOCS"
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
  - ../../policies/Information-Security-Policy.md
  - ../../policies/Quality-and-Document-Control-Policy.md
  - ../../policies/Risk-Management-Policy.md
---

## Document Control

| Field | Value |
|-------|-------|
| Title | ISO/IEC 27001:2022 Annex A – Requirement to Documents Mapping |
| Document ID | GRS-ISMS-MAP-27001-REQ2DOCS |
| Version | 1.0.0 |
| Status | Draft |
| Owner | GRC Analyst |
| Program Manager | Josh Mayorga, Compliance Manager |
| Approver | ISMS Manager |
| Approval Date |  |
| Effective Date |  |
| Next Review Date |  |

## Purpose

Map each Annex A requirement to the GridSite document set (Primary, Supporting) with example evidence.

## Mapping (seed)

| Standard | Requirement ID | Title | Primary Documents | Supporting Documents | Evidence (examples) | Notes |
|----------|-----------------|-------|-------------------|----------------------|---------------------|-------|
| ISO 27001 | A.5.1 | Policies for information security | [P01 Information Security Policy](../../policies/Information-Security-Policy.md); [P34 Quality & Document Control](../../policies/Quality-and-Document-Control-Policy.md) | [P03 Risk Management](../../policies/Risk-Management-Policy.md) | Approved policy, version history, review records. |  |
| ISO 27001 | A.5.2 | Information security roles and responsibilities | [P01 Information Security Policy](../../policies/Information-Security-Policy.md); [P08 IAM Policy](../../policies/Identity-and-Access-Management-Policy.md) | [P35 Segregation of Duties](../../policies/Segregation-of-Duties-Policy.md) | Org chart, RACI, access reviews. |  |
| ISO 27001 | A.5.3 | Segregation of duties | [P35 Segregation of Duties](../../policies/Segregation-of-Duties-Policy.md) | [P08 IAM Policy](../../policies/Identity-and-Access-Management-Policy.md); [PR05 Privileged Access Elevation](../../procedures/Privileged-Access-Elevation-Procedure.md) | SoD matrices, approvals, logs. |  |
| ISO 27001 | A.5.10 | Acceptable use of information and assets | [P07 Acceptable Use](../../policies/Acceptable-Use-Policy.md) | [P12 Endpoint Security](../../policies/Endpoint-Security-Policy.md); [S01 Workstation Baseline](../../standards/Workstation-Baseline.md) | Acknowledgements, endpoint conformance reports. |  |
| ISO 27001 | A.5.23 | Information security for use of cloud services | [P15 Cloud Security](../../policies/Cloud-Security-Policy.md) | [S22 Cloud Landing Zone](../../standards/Cloud-Landing-Zone-Standard.md); [S09 Secrets Management](../../standards/Secrets-Management-Standard.md) | Cloud account configs, IaC guardrails, vendor due diligence. |  |
| ISO 27001 | A.5.30 | ICT readiness for business continuity | [P23 BCMS Policy](../../policies/Business-Continuity-Policy.md) | [PL04 BCMS Strategy](../../plans/BCMS-Strategy-Plan.md); [PL05 DR Plans](../../plans/Disaster-Recovery-Plans.md); [PR22 DR Invocation](../../procedures/DR-Invocation-and-Recovery-Procedure.md) | Exercise records, RTO/RPO tests, DR evidence. |  |
| ISO 27001 | A.6.1 | Screening | [P48 HR Security](../../policies/HR-Security-Policy.md) | [PR06 Onboarding & Offboarding](../../procedures/Onboarding-and-Offboarding-Procedure.md) | Background checks, onboarding checklists. |  |
| ISO 27001 | A.6.3 | Termination or change of employment responsibilities | [P48 HR Security](../../policies/HR-Security-Policy.md) | [PR06 Onboarding & Offboarding](../../procedures/Onboarding-and-Offboarding-Procedure.md); [PR04 Access Provisioning/Deprovisioning](../../procedures/Access-Provisioning-and-Deprovisioning-Procedure.md) | Termination tickets, access revocation logs. |  |
| ISO 27001 | A.7.1 | Physical security perimeters | [S17 Facility Physical Security](../../standards/Facility-Physical-Security-Standard.md) | [P28 Physical & Environmental Security](../../policies/Physical-and-Environmental-Security-Policy.md) | Site diagrams, access control configs, CCTV coverage. |  |
| ISO 27001 | A.7.2 | Physical entry controls | [S17 Facility Physical Security](../../standards/Facility-Physical-Security-Standard.md) | [PR35 Visitor Management Procedure](../../procedures/Visitor-Management-Procedure.md); [R20 Visitor & Badge Logs](../../plans/Visitor-and-Badge-Logs.md) | Badge logs, kiosk exports, visitor records. |  |
| ISO 27001 | A.8.1 | User endpoint devices | [S01 Workstation Baseline](../../standards/Workstation-Baseline.md); [P12 Endpoint Security](../../policies/Endpoint-Security-Policy.md) | [P13 Mobile/BYOD](../../policies/Mobile-Device-and-BYOD-Policy.md); [S08 Backup & Immutability](../../standards/Backup-and-Immutability-Standard.md) | EDR status, encryption reports, iDrive360 success logs. |  |
| ISO 27001 | A.8.2 | Privileged access rights | [P10 PAM Policy](../../policies/Privileged-Access-Management-Policy.md); [S06 Identity & PAM Standard](../../standards/Identity-and-PAM-Standard.md) | [PR05 Privileged Access Elevation](../../procedures/Privileged-Access-Elevation-Procedure.md); [R05 Privileged Accounts Register](../../plans/Privileged-Accounts-Register.md) | PAM approvals, session records, Duo enrollments. |  |
| ISO 27001 | A.8.15 | Logging | [P21 Logging, Monitoring & SIEM](../../policies/Logging-Monitoring-and-SIEM-Policy.md); [S07 Logging & Time Sync](../../standards/Logging-and-Time-Sync-Standard.md) | [PR19 SIEM Onboarding](../../procedures/Logging-and-SIEM-Onboarding-Procedure.md); [PR20 Alert Triage](../../procedures/Alert-Triage-and-Escalation-Procedure.md) | SIEM dashboards, retention configs, manual exports where needed. |  |
| ISO 27001 | A.8.16 | Monitoring activities | [P21 Logging, Monitoring & SIEM](../../policies/Logging-Monitoring-and-SIEM-Policy.md) | [PR20 Alert Triage](../../procedures/Alert-Triage-and-Escalation-Procedure.md); [PR42 Continuous Control Monitoring](../../procedures/Continuous-Control-Monitoring-Procedure.md) | Detection rules, alert SLAs, tuning records. |  |

## Revision History

| Version | Date       | Author | Description |
|---------|------------|--------|-------------|
| 1.0.0   | 2025-11-05 |        | Seeded Annex A mappings for priority controls. |


