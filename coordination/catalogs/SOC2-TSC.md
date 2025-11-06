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

## Document-to-Criteria Mapping

| Document | Doc ID | Type | Objectives (Primary) | Objectives (Supporting) |
|----------|--------|------|-----------------------|-------------------------|
| Information Security Policy | P01 | Policy | CC1.1, CC1.3 | CC1.2, CC2.3 |
| Quality & Document Control Policy | P34 | Policy | CC1.5, CC5.3 | CC2.2 |
| Management Review Procedure | PR46 | Procedure |  | CC1.2, CC4.2, CC9.2 |
| Audit & Assessment Plan | PL09 | Plan |  | CC4.1 |
| Email & Communications Security Policy | P36 | Policy | CC2.1, CC2.4 |  |
| Metrics & Continuous Improvement Policy | P60 | Policy | CC1.5, CC4.2 |  |
| Crisis Communications Plan | PL06 | Plan |  | CC2.4 |
| Risk Management Policy | P03 | Policy | CC3.1, CC3.2 | CC3.4 |
| Risk Assessment Procedure | PR02 | Procedure |  | CC3.1, CC3.2 |
| Risk Register | R01 | Register |  | CC3.1, CC3.2 |
| Fraud Prevention & Whistleblower Policy | P47 | Policy | CC3.3 |  |
| Segregation of Duties Policy | P35 | Policy | CC1.3 | CC6.5 |
| Change & Release Management Policy | P19 | Policy | CC3.4, CC8.1, CC8.2 | PI1.4 |
| Change Control Procedure | PR07 | Procedure |  | CC8.1, CC8.2 |
| Release Management Procedure | PR09 | Procedure |  | CC8.1, CC8.2, PI1.4 |
| Configuration Management Procedure | PR10 | Procedure |  | CC5.3, CC8.2 |
| Identity & Access Management Policy | P08 | Policy | CC6.1, CC6.2 |  |
| Access Control Policy | P64 | Policy | CC6.1, CC6.5 |  |
| Access Provisioning/Deprovisioning Procedure | PR04 | Procedure |  | CC6.2, CC6.4 |
| Access Control Matrix | R04 | Register |  | CC6.5 |
| Authentication & MFA Policy | P09 | Policy | CC6.3 |  |
| Identity & PAM Standard | S06 | Standard |  | CC6.1, CC6.3, CC6.5 |
| Network Security Policy | P14 | Policy | CC6.6 |  |
| Network Segmentation Standard | S04 | Standard |  | CC6.6 |
| Firewall/WAF Standard | S05 | Standard |  | CC6.6, CC7.1 |
| Facility Physical Security Standard | S17 | Standard | CC6.7 |  |
| Physical & Environmental Security Policy | P28 | Policy |  | CC6.7 |
| Data Retention & Disposal Policy | P30 | Policy | CC6.8 |  |
| Media Handling & Removable Media Policy | P54 | Policy |  | CC6.8 |
| Data Retention & Destruction Procedure | PR27 | Procedure |  | CC6.8 |
| Logging, Monitoring & SIEM Policy | P21 | Policy | CC7.1, CC7.2, CC7.4 |  |
| SIEM Onboarding Procedure | PR19 | Procedure |  | CC7.2, CC7.4 |
| Alert Triage & Escalation Procedure | PR20 | Procedure |  | CC7.1, CC7.2 |
| Incident Response Policy | P22 | Policy | CC7.3 |  |
| IR Runbook – General | PR13 | Procedure |  | CC7.3 |
| Incident Playbooks – by Scenario | PL07 | Plan |  | CC7.3 |
| Vulnerability & Patch Management Policy | P20 | Policy | CC7.5 |  |
| Vulnerability Scanning Standard | S23 | Standard |  | CC7.5 |
| Vulnerability Management Procedure | PR11 | Procedure |  | CC7.5 |
| Business Continuity Management Policy | P23 | Policy | A1.1, CC9.2 |  |
| Backup & Restore Policy | P25 | Policy | A1.1 |  |
| Disaster Recovery Plans – by System | PL05 | Plan |  | A1.1, CC9.2 |
| Backup & Immutability Standard | S08 | Standard |  | A1.1 |
| Confidentiality – Data Classification & Handling Policy | P06 | Policy | C1.1 |  |
| Data Classification Marking Standard | S12 | Standard |  | C1.1 |
| Data Loss Prevention Standard | S24 | Standard |  | C1.1 |
| Privacy & Data Protection Policy | P31 | Policy |  | C1.1 |
| Secure Software Development Policy | P18 | Policy | PI1.1 | PI1.2, PI1.3 |
| SAST/DAST & Code Review Procedure | PR24 | Procedure | PI1.1, PI1.3, PI1.4 |  |
| CI/CD Security Standard | S10 | Standard |  | PI1.1, PI1.4, CC8.2 |
| API Security Standard | S11 | Standard |  | PI1.3 |
| Workstation Baseline | S01 | Standard |  | CC5.2, CC7.1 |
| Server Baseline | S02 | Standard |  | CC5.2, CC7.1 |
| Logging & Time Sync Standard | S07 | Standard | CC5.2, CC7.4 |  |
| DCIM/Telemetry Standard | S16 | Standard |  | CC6.7, A1.1 |
| Clean Desk & Clear Screen Policy | P61 | Policy |  | CC6.7 |
| Remote Access Policy | P62 | Policy |  | CC6.1, CC6.6 |
| Security Awareness & Phishing Plan | PL02 | Plan |  | CC1.4 |
| Crisis Management Plan | PL11 | Plan |  | CC9.2 |
| Records Mgmt & Evidence Policy | P32 | Policy | CC2.2 |  |
| Training Attendance & Results | R13 | Register |  | CC1.4 |
| Internal Audit Findings & CAPA Tracker | R14 | Register |  | CC4.2 |
| Capacity & Performance Mgmt Policy | P44 | Policy |  | A1.1 |
| Capacity & Availability Reports | R18 | Register |  | A1.1 |
| Incident Report Form | T05 | Template |  | CC7.3 |
## Revision History

| Version | Date       | Author | Description |
|---------|------------|--------|-------------|
| 1.0.0   | 2025-11-05 |        | Seeded SOC 2 TSC catalog. |
| 1.1.0   | 2025-11-06 |        | Added Primary/Supporting/Evidence columns and seeded mappings. |


