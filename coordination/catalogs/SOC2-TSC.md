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
| SOC 2 | CC1.2 | Board Oversight | Security | [P01](../../policies/Information-Security-Policy.md) | [PR46](../../procedures/Management-Review-Procedure.md) | Governance records; management review inputs/outputs. |
| SOC 2 | CC1.3 | Structure, Authority, and Responsibility | Security | [P01](../../policies/Information-Security-Policy.md) | [P35](../../policies/Segregation-of-Duties-Policy.md) | Org charts; role definitions; SoD matrices. |
| SOC 2 | CC1.4 | Commitment to Competence | Security | [P33](../../policies/Training-and-Security-Awareness-Policy.md) | [PL02](../../plans/Security-Awareness-and-Phishing-Plan.md); [R13](../../plans/Training-Attendance-and-Results.md) | Training curricula; attendance records. |
| SOC 2 | CC1.5 | Accountability | Security | [P34](../../policies/Quality-and-Document-Control-Policy.md) | [P60](../../policies/Metrics-and-Continuous-Improvement-Policy.md) | Assigned owners; KPI reviews. |
| SOC 2 | CC2.1 | Communication and Information | Security | [P36](../../policies/Email-and-Communications-Security-Policy.md) | [P60](../../policies/Metrics-and-Continuous-Improvement-Policy.md); [PL06](../../plans/Crisis-Communications-Plan.md) | Communications; dashboards. |
| SOC 2 | CC2.2 | Quality of Information | Security | [P32](../../policies/Records-Management-and-Evidence-Policy.md) | [P34](../../policies/Quality-and-Document-Control-Policy.md) | Source integrity; version control; review logs. |
| SOC 2 | CC2.3 | Internal Communication of Responsibilities | Security | [P01](../../policies/Information-Security-Policy.md) | [P08](../../policies/Identity-and-Access-Management-Policy.md) | Role communications; onboarding packs. |
| SOC 2 | CC2.4 | External Communication | Security | [P36](../../policies/Email-and-Communications-Security-Policy.md) | [PL06](../../plans/Crisis-Communications-Plan.md) | External notices; press logs. |
| SOC 2 | CC3.1 | Risk Identification | Security | [P03](../../policies/Risk-Management-Policy.md) | [PR02](../../procedures/Risk-Assessment-Procedure.md); [R01](../../plans/Risk-Register.md) | Risk inventory; assessments. |
| SOC 2 | CC3.2 | Risk Assessment | Security | [P03](../../policies/Risk-Management-Policy.md) | [PR02](../../procedures/Risk-Assessment-Procedure.md) | Risk analysis; treatment plans. |
| SOC 2 | CC3.3 | Fraud Risk | Security | [P47](../../policies/Fraud-Prevention-and-Whistleblower-Policy.md) | [P35](../../policies/Segregation-of-Duties-Policy.md) | Hotline logs; investigations; SoD. |
| SOC 2 | CC3.4 | Significant Changes | Security | [P19](../../policies/Change-and-Release-Management-Policy.md) | [PR07](../../procedures/Change-Control-Procedure.md) | Change impact assessments; approvals. |
| SOC 2 | CC4.1 | Monitoring Activities | Security | [PR45](../../procedures/Internal-Audit-Procedure.md) | [P60](../../policies/Metrics-and-Continuous-Improvement-Policy.md) | IA plans; KPI reviews. |
| SOC 2 | CC4.2 | Remediation of Deficiencies | Security | [R14](../../plans/Internal-Audit-Findings-and-CAPA-Tracker.md) | [PR46](../../procedures/Management-Review-Procedure.md) | CAPA logs; follow-ups. |
| SOC 2 | CC5.1 | Control Activities Selection and Development | Security | [P17](../../policies/Secure-Configuration-and-Hardening-Policy.md) | [P64](../../policies/Access-Control-Policy.md) | Baselines; procedures. |
| SOC 2 | CC5.2 | General Control Activities over Technology | Security | [S07](../../standards/Logging-and-Time-Sync-Standard.md); [S02](../../standards/Server-Baseline.md) | [S01](../../standards/Workstation-Baseline.md) | NTP configs; baseline evidence. |
| SOC 2 | CC5.3 | Deployment through Policies and Procedures | Security | [P34](../../policies/Quality-and-Document-Control-Policy.md) | [PR10](../../procedures/Configuration-Management-Procedure.md) | Documented SOPs; approvals. |
| SOC 2 | CC6.1 | Logical Access | Security | [P08](../../policies/Identity-and-Access-Management-Policy.md); [P64](../../policies/Access-Control-Policy.md) | [PR04](../../procedures/Access-Provisioning-and-Deprovisioning-Procedure.md); [R04](../../plans/Access-Control-Matrix.md) | Access requests; RBAC; reviews. |
| SOC 2 | CC6.2 | Registration and Authorization | Security | [P08](../../policies/Identity-and-Access-Management-Policy.md) | [PR04](../../procedures/Access-Provisioning-and-Deprovisioning-Procedure.md) | JML tickets; approvals. |
| SOC 2 | CC6.3 | Authentication | Security | [P09](../../policies/Authentication-and-MFA-Policy.md) | [S06](../../standards/Identity-and-PAM-Standard.md) | Duo configs; session controls. |
| SOC 2 | CC6.4 | Revocation | Security | [PR04](../../procedures/Access-Provisioning-and-Deprovisioning-Procedure.md) | [R05](../../plans/Privileged-Accounts-Register.md) | Deprovision logs; disable evidence. |
| SOC 2 | CC6.5 | Logical Access Restrictions | Security | [P64](../../policies/Access-Control-Policy.md) | [S06](../../standards/Identity-and-PAM-Standard.md) | RBAC matrices; SoD checks. |
| SOC 2 | CC6.6 | Network Security | Security | [P14](../../policies/Network-Security-Policy.md) | [S04](../../standards/Network-Segmentation-Standard.md); [S05](../../standards/Firewall-and-WAF-Standard.md) | FW rules; segmentation. |
| SOC 2 | CC6.7 | Physical Access | Security | [S17](../../standards/Facility-Physical-Security-Standard.md) | [P28](../../policies/Physical-and-Environmental-Security-Policy.md) | Badge logs; kiosk exports. |
| SOC 2 | CC6.8 | Confidential Information Disposal | Security | [P30](../../policies/Data-Retention-and-Disposal-Policy.md); [P54](../../policies/Media-Handling-and-Removable-Media-Policy.md) | [PR27](../../procedures/Data-Retention-and-Destruction-Procedure.md) | Disposal certs; wipe logs. |
| SOC 2 | CC7.1 | System Operations | Security | [P21](../../policies/Logging-Monitoring-and-SIEM-Policy.md) | [PR20](../../procedures/Alert-Triage-and-Escalation-Procedure.md) | Ops logs; runbooks. |
| SOC 2 | CC7.2 | Monitoring and Detection | Security | [P21](../../policies/Logging-Monitoring-and-SIEM-Policy.md) | [PR19](../../procedures/Logging-and-SIEM-Onboarding-Procedure.md) | SIEM alerts; tuning. |
| SOC 2 | CC7.3 | Incident Response | Security | [P22](../../policies/Incident-Response-Policy.md) | [PR13](../../procedures/IR-Runbook-General.md); [PL07](../../plans/Incident-Playbooks.md) | Incident timelines; PIRs. |
| SOC 2 | CC7.4 | Logging of Security Events | Security | [P21](../../policies/Logging-Monitoring-and-SIEM-Policy.md) | [S07](../../standards/Logging-and-Time-Sync-Standard.md) | Log retention; time sync. |
| SOC 2 | CC7.5 | Vulnerability and Threat Management | Security | [P20](../../policies/Vulnerability-and-Patch-Management-Policy.md) | [S23](../../standards/Vulnerability-Scanning-Standard.md); [PR11](../../procedures/Vulnerability-Management-Procedure.md) | Scan results; remediation SLAs. |
| SOC 2 | CC8.1 | Change Management | Security | [P19](../../policies/Change-and-Release-Management-Policy.md) | [PR07](../../procedures/Change-Control-Procedure.md); [PR09](../../procedures/Release-Management-Procedure.md) | Change tickets; approvals; testing. |
| SOC 2 | CC8.2 | Change Authorization and Testing | Security | [P19](../../policies/Change-and-Release-Management-Policy.md) | [PR09](../../procedures/Release-Management-Procedure.md); [PR10](../../procedures/Configuration-Management-Procedure.md) | UAT; rollback; peer reviews. |
| SOC 2 | CC9.1 | Risk Mitigation | Security | [P26](../../policies/Supplier-and-Third-Party-Risk-Management-Policy.md) | [PR31](../../procedures/Subservice-Monitoring-Procedure.md); [P27](../../policies/Subservice-Organization-Oversight-Policy.md) | Vendor SOC reports; remediation trackers. |
| SOC 2 | CC9.2 | Business Disruption and Contingency Planning | Security | [P23](../../policies/Business-Continuity-Policy.md) | [PL05](../../plans/Disaster-Recovery-Plans.md); [PR23](../../procedures/Tabletop-Exercise-Procedure.md) | BC/DR exercises; results. |
| SOC 2 | A1.1 | Availability | Availability | [P23](../../policies/Business-Continuity-Policy.md); [P25](../../policies/Backup-and-Restore-Policy.md) | [PL05](../../plans/Disaster-Recovery-Plans.md); [S08](../../standards/Backup-and-Immutability-Standard.md) | Uptime reports; restore tests. |
| SOC 2 | C1.1 | Confidentiality | Confidentiality | [P06](../../policies/Data-Classification-and-Handling-Policy.md) | [S12](../../standards/Data-Classification-Marking-Standard.md); [S24](../../standards/Data-Loss-Prevention-Standard.md) | Labels; DLP logs; access reviews. |
| SOC 2 | PI1.1 | Processing Integrity | Processing Integrity | [P18](../../policies/Secure-Software-Development-Policy.md) | [PR24](../../procedures/SAST-DAST-and-Code-Review-Procedure.md); [S10](../../standards/CI-CD-Security-Standard.md) | Test evidence; acceptance criteria. |
| SOC 2 | PI1.2 | Data Processing Completeness and Accuracy | Processing Integrity | [P18](../../policies/Secure-Software-Development-Policy.md) | [PL08](../../plans/Pen-Test-and-AppSec-Annual-Plan.md) | Test cases; reconciliations. |
| SOC 2 | PI1.3 | Input and Output Controls | Processing Integrity | [P18](../../policies/Secure-Software-Development-Policy.md) | [S11](../../standards/API-Security-Standard.md) | Input validation; output checks. |
| SOC 2 | PI1.4 | Change and Error Handling | Processing Integrity | [P19](../../policies/Change-and-Release-Management-Policy.md) | [PR09](../../procedures/Release-Management-Procedure.md) | Defect tickets; rollbacks. |

## Revision History

| Version | Date       | Author | Description |
|---------|------------|--------|-------------|
| 1.0.0   | 2025-11-05 |        | Seeded SOC 2 TSC catalog. |
| 1.1.0   | 2025-11-06 |        | Added Primary/Supporting/Evidence columns and seeded mappings. |


