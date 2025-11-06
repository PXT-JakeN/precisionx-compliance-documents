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
| ISO 27001 | A.5.4 | Management responsibilities | [P01 Information Security Policy](../../policies/Information-Security-Policy.md) | [P34 Quality & Document Control](../../policies/Quality-and-Document-Control-Policy.md) | Policy comms, management directives. |  |
| ISO 27001 | A.5.5 | Contact with authorities | [P22 Incident Response Policy](../../policies/Incident-Response-Policy.md) | [PR13 IR Runbook – General](../../procedures/IR-Runbook-General.md) | Contact lists, notification records. |  |
| ISO 27001 | A.5.6 | Contact with special interest groups | [P01 Information Security Policy](../../policies/Information-Security-Policy.md) | [P21 Logging & SIEM](../../policies/Logging-Monitoring-and-SIEM-Policy.md) | Memberships, participation logs. |  |
| ISO 27001 | A.5.7 | Threat intelligence | [P21 Logging & SIEM](../../policies/Logging-Monitoring-and-SIEM-Policy.md) | [PR20 Alert Triage](../../procedures/Alert-Triage-and-Escalation-Procedure.md) | TI feeds, detection updates. |  |
| ISO 27001 | A.5.8 | IS in project management | [P18 Secure SDLC](../../policies/Secure-Software-Development-Policy.md) | [S10 CI/CD Security](../../standards/CI-CD-Security-Standard.md); [PR24 SAST/DAST & Code Review](../../procedures/SAST-DAST-and-Code-Review-Procedure.md) | Design reviews, security gates. |  |
| ISO 27001 | A.5.9 | Inventory of information and assets | [P05 Asset Management](../../policies/Asset-Management-Policy.md) | [R02 Asset Inventory & CMDB](../../plans/Asset-Inventory-and-CMDB.md); [PR10 Config Mgmt](../../procedures/Configuration-Management-Procedure.md) | CMDB extracts, ownership. |  |
| ISO 27001 | A.5.10 | Acceptable use of information and assets | [P07 Acceptable Use](../../policies/Acceptable-Use-Policy.md) | [P12 Endpoint Security](../../policies/Endpoint-Security-Policy.md); [S01 Workstation Baseline](../../standards/Workstation-Baseline.md) | Acknowledgements, endpoint conformance. |  |
| ISO 27001 | A.5.11 | Return of assets | [P05 Asset Management](../../policies/Asset-Management-Policy.md) | [PR06 On/Offboarding](../../procedures/Onboarding-and-Offboarding-Procedure.md) | Offboarding checklists, asset returns. |  |
| ISO 27001 | A.5.12 | Classification of information | [P06 Data Classification & Handling](../../policies/Data-Classification-and-Handling-Policy.md) | [S12 Data Classification Marking](../../standards/Data-Classification-Marking-Standard.md) | Label catalog, examples. |  |
| ISO 27001 | A.5.13 | Labelling of information | [S12 Data Classification Marking](../../standards/Data-Classification-Marking-Standard.md) | [P06 Data Classification & Handling](../../policies/Data-Classification-and-Handling-Policy.md) | Label configs, auto-labeling. |  |
| ISO 27001 | A.5.14 | Information transfer | [P06 Data Classification & Handling](../../policies/Data-Classification-and-Handling-Policy.md) | [P36 Email & Communications](../../policies/Email-and-Communications-Security-Policy.md); [P16 Cryptography](../../policies/Cryptography-and-Key-Management-Policy.md) | Transfer agreements, encryption settings. |  |
| ISO 27001 | A.5.15 | Access control | [P64 Access Control](../../policies/Access-Control-Policy.md); [P08 IAM](../../policies/Identity-and-Access-Management-Policy.md) | [S06 Identity & PAM](../../standards/Identity-and-PAM-Standard.md) | Access policy, reviews. |  |
| ISO 27001 | A.5.16 | Identity management | [P08 IAM](../../policies/Identity-and-Access-Management-Policy.md) | [S06 Identity & PAM](../../standards/Identity-and-PAM-Standard.md); [PR04 Access Provisioning](../../procedures/Access-Provisioning-and-Deprovisioning-Procedure.md) | Entra objects, JML tickets. |  |
| ISO 27001 | A.5.17 | Authentication information | [P09 Authentication & MFA](../../policies/Authentication-and-MFA-Policy.md) | [S06 Identity & PAM](../../standards/Identity-and-PAM-Standard.md) | MFA configs (Duo), reset logs. |  |
| ISO 27001 | A.5.18 | Access rights | [P64 Access Control](../../policies/Access-Control-Policy.md) | [PR04 Access Provisioning](../../procedures/Access-Provisioning-and-Deprovisioning-Procedure.md); [PR05 Privileged Elevation](../../procedures/Privileged-Access-Elevation-Procedure.md) | Access reviews, approvals. |  |
| ISO 27001 | A.5.19 | IS in supplier relationships | [P26 Supplier & Third-Party Risk](../../policies/Supplier-and-Third-Party-Risk-Management-Policy.md) | [PR30 Vendor Due Diligence](../../procedures/Vendor-Due-Diligence-and-Onboarding-Procedure.md) | DDQ results, risk tiers. |  |
| ISO 27001 | A.5.20 | IS within supplier agreements | [P26 Supplier & Third-Party Risk](../../policies/Supplier-and-Third-Party-Risk-Management-Policy.md) | [P31 Privacy & Data Protection](../../policies/Privacy-and-Data-Protection-Policy.md) | Contracts, DPA, SCCs. |  |
| ISO 27001 | A.5.21 | IS in ICT supply chain | [P26 Supplier & Third-Party Risk](../../policies/Supplier-and-Third-Party-Risk-Management-Policy.md) | [S22 Cloud Landing Zone](../../standards/Cloud-Landing-Zone-Standard.md); [S09 Secrets](../../standards/Secrets-Management-Standard.md) | Vendor monitoring, SBOMs. |  |
| ISO 27001 | A.5.22 | Supplier service monitoring/review | [PR31 Subservice Monitoring](../../procedures/Subservice-Monitoring-Procedure.md) | [P26 Supplier & Third-Party Risk](../../policies/Supplier-and-Third-Party-Risk-Management-Policy.md) | SOC reports, remediation logs. |  |
| ISO 27001 | A.5.23 | Cloud services security | [P15 Cloud Security](../../policies/Cloud-Security-Policy.md) | [S22 Cloud Landing Zone](../../standards/Cloud-Landing-Zone-Standard.md) | Account configs, guardrails. |  |
| ISO 27001 | A.5.24 | IS incident planning/prep | [P22 Incident Response](../../policies/Incident-Response-Policy.md) | [PL07 Incident Playbooks](../../plans/Incident-Playbooks.md) | IR plan, roles, call trees. |  |
| ISO 27001 | A.5.25 | Event assessment/decision | [PR20 Alert Triage](../../procedures/Alert-Triage-and-Escalation-Procedure.md) | [P21 Logging & SIEM](../../policies/Logging-Monitoring-and-SIEM-Policy.md) | Triage logs, SIEM alerts. |  |
| ISO 27001 | A.5.26 | Incident response | [P22 Incident Response](../../policies/Incident-Response-Policy.md) | [PR13/14/15/16/17 Runbooks](../../procedures/IR-Runbook-General.md) | Incident tickets, timelines. |  |
| ISO 27001 | A.5.27 | Lessons learned | [PR46 Management Review](../../procedures/Management-Review-Procedure.md) | [P60 Metrics & CI](../../policies/Metrics-and-Continuous-Improvement-Policy.md) | PIR reports, CAPA. |  |
| ISO 27001 | A.5.28 | Collection of evidence | [PR18 Forensics & Evidence](../../procedures/Forensics-and-Evidence-Handling-SOP.md) | [P32 Records Management](../../policies/Records-Management-and-Evidence-Policy.md) | Chain of custody, exports. |  |
| ISO 27001 | A.5.29 | IS during disruption | [P23 BCMS Policy](../../policies/Business-Continuity-Policy.md) | [PL11 Crisis Mgmt](../../plans/Crisis-Management-Plan.md) | Plans referencing IS constraints. |  |
| ISO 27001 | A.5.30 | ICT readiness for BC | [P24 DR Policy](../../policies/Disaster-Recovery-Policy.md) | [PL05 DR Plans](../../plans/Disaster-Recovery-Plans.md); [S07 Logging & Time Sync](../../standards/Logging-and-Time-Sync-Standard.md) | DR tests, NTP, failover drills. |  |
| ISO 27001 | A.5.31 | Legal/statutory/regulatory/contractual | [P63 Legal & Regulatory Compliance](../../policies/Legal-and-Regulatory-Compliance-Policy.md) | [P31 Privacy](../../policies/Privacy-and-Data-Protection-Policy.md); [P32 Records](../../policies/Records-Management-and-Evidence-Policy.md) | Register of obligations, attestations. |  |
| ISO 27001 | A.5.32 | Intellectual property rights | [P63 Legal & Regulatory Compliance](../../policies/Legal-and-Regulatory-Compliance-Policy.md) | [P32 Records](../../policies/Records-Management-and-Evidence-Policy.md) | IPR procedures, access controls. |  |
| ISO 27001 | A.5.33 | Protection of records | [P32 Records Management](../../policies/Records-Management-and-Evidence-Policy.md) | [P30 Data Retention & Disposal](../../policies/Data-Retention-and-Disposal-Policy.md) | Retention schedules, access logs. |  |
| ISO 27001 | A.5.34 | Privacy and protection of PII | [P31 Privacy & Data Protection](../../policies/Privacy-and-Data-Protection-Policy.md) | [S24 DLP](../../standards/Data-Loss-Prevention-Standard.md) | DPIAs, DLP incidents. |  |
| ISO 27001 | A.5.35 | Independent review of IS | [PR45 Internal Audit](../../procedures/Internal-Audit-Procedure.md) | [PL09 Audit & Assessment](../../plans/Audit-and-Assessment-Plan.md) | Audit plans, reports. |  |
| ISO 27001 | A.5.36 | Compliance with policies/rules/standards | [PR45 Internal Audit](../../procedures/Internal-Audit-Procedure.md) | [P34 Quality & Document Control](../../policies/Quality-and-Document-Control-Policy.md) | Compliance reviews, findings. |  |
| ISO 27001 | A.5.37 | Documented operating procedures | [PR10 Configuration Mgmt](../../procedures/Configuration-Management-Procedure.md) | [PR07 Change Control](../../procedures/Change-Control-Procedure.md) | SOPs, runbooks. |  |
| ISO 27001 | A.6.1 | Screening | [P48 HR Security](../../policies/HR-Security-Policy.md) | [PR06 On/Offboarding](../../procedures/Onboarding-and-Offboarding-Procedure.md) | Background checks. |  |
| ISO 27001 | A.6.2 | Terms and conditions of employment | [P48 HR Security](../../policies/HR-Security-Policy.md) | [P07 Acceptable Use](../../policies/Acceptable-Use-Policy.md) | Contract clauses, acknowledgments. |  |
| ISO 27001 | A.6.3 | IS awareness, education and training | [P33 Training & Awareness](../../policies/Training-and-Security-Awareness-Policy.md) | [PL02 Awareness Plan](../../plans/Security-Awareness-and-Phishing-Plan.md); [R13 Training Results](../../plans/Training-Attendance-and-Results.md) | Curriculum, attendance. |  |
| ISO 27001 | A.6.4 | Disciplinary process | [P48 HR Security](../../policies/HR-Security-Policy.md) | [P07 Acceptable Use](../../policies/Acceptable-Use-Policy.md) | Disciplinary records. |  |
| ISO 27001 | A.6.5 | Responsibilities after termination/change | [P48 HR Security](../../policies/HR-Security-Policy.md) | [PR06 On/Offboarding](../../procedures/Onboarding-and-Offboarding-Procedure.md) | Exit forms, NDA reaffirmation. |  |
| ISO 27001 | A.6.6 | Confidentiality or NDAs | [P31 Privacy & Data Protection](../../policies/Privacy-and-Data-Protection-Policy.md) | [P48 HR Security](../../policies/HR-Security-Policy.md) | NDA archive. |  |
| ISO 27001 | A.6.7 | Remote working | [P11 Remote Work / WFH](../../policies/Remote-Work-Security-Policy.md) | [S01 Workstation Baseline](../../standards/Workstation-Baseline.md); [P62 Remote Access](../../policies/Remote-Access-Policy.md) | VPN/MFA configs, device posture. |  |
| ISO 27001 | A.6.8 | IS event reporting | [P21 Logging & SIEM](../../policies/Logging-Monitoring-and-SIEM-Policy.md) | [T05 Incident Report Form](../../templates/Incident-Report-Form.md) | Report queue, tickets. |  |
| ISO 27001 | A.7.1 | Physical security perimeters | [S17 Facility Physical Security](../../standards/Facility-Physical-Security-Standard.md) | [P28 Physical & Environmental Security](../../policies/Physical-and-Environmental-Security-Policy.md) | Site drawings, controls. |  |
| ISO 27001 | A.7.2 | Physical entry | [S17 Facility Physical Security](../../standards/Facility-Physical-Security-Standard.md) | [PR35 Visitor Management](../../procedures/Visitor-Management-Procedure.md); [R20 Visitor Logs](../../plans/Visitor-and-Badge-Logs.md) | Badge/kiosk logs. |  |
| ISO 27001 | A.7.3 | Securing offices, rooms, facilities | [S17 Facility Physical Security](../../standards/Facility-Physical-Security-Standard.md) | [P28 Physical & Environmental Security](../../policies/Physical-and-Environmental-Security-Policy.md) | Photos, inspections. |  |
| ISO 27001 | A.7.4 | Physical security monitoring | [P52 CCTV & Surveillance](../../policies/CCTV-and-Surveillance-Policy.md) | [S17 Facility Physical Security](../../standards/Facility-Physical-Security-Standard.md) | CCTV retention, exports. |  |
| ISO 27001 | A.7.5 | Protecting against physical/env threats | [P28 Physical & Environmental Security](../../policies/Physical-and-Environmental-Security-Policy.md) | [S16 DCIM/Telemetry](../../standards/DCIM-Telemetry-Standard.md); [S19 MEP Change](../../standards/Maintenance-and-MEP-Change-Standard.md) | Alarms, thresholds. |  |
| ISO 27001 | A.7.6 | Working in secure areas | [S17 Facility Physical Security](../../standards/Facility-Physical-Security-Standard.md) | [PR34 NOC Operations Manual](../../procedures/NOC-Operations-Manual.md) | SOP adherence records. |  |
| ISO 27001 | A.7.7 | Clear desk and clear screen | [P61 Clean Desk & Clear Screen](../../policies/Clean-Desk-and-Clear-Screen-Policy.md) | [P07 Acceptable Use](../../policies/Acceptable-Use-Policy.md) | Floor walk results. |  |
| ISO 27001 | A.7.8 | Equipment siting and protection | [S17 Facility Physical Security](../../standards/Facility-Physical-Security-Standard.md) | [S02 Server Baseline](../../standards/Server-Baseline.md) | Racks, access controls. |  |
| ISO 27001 | A.7.9 | Security of assets off-premises | [P05 Asset Management](../../policies/Asset-Management-Policy.md) | [P12 Endpoint Security](../../policies/Endpoint-Security-Policy.md) | Loaner logs, MDM. |  |
| ISO 27001 | A.7.10 | Storage media | [P54 Media Handling](../../policies/Media-Handling-and-Removable-Media-Policy.md) | [PR27 Data Retention & Destruction](../../procedures/Data-Retention-and-Destruction-Procedure.md) | Disposal certificates. |  |
| ISO 27001 | A.7.11 | Supporting utilities | [S16 DCIM/Telemetry](../../standards/DCIM-Telemetry-Standard.md) | [S15 NOC Build](../../standards/NOC-Build-Standard.md) | Generator/UPS tests. |  |
| ISO 27001 | A.7.12 | Cabling security | [S17 Facility Physical Security](../../standards/Facility-Physical-Security-Standard.md) | [S04 Network Segmentation](../../standards/Network-Segmentation-Standard.md) | Cabling routes, protection. |  |
| ISO 27001 | A.7.13 | Equipment maintenance | [S19 MEP Change](../../standards/Maintenance-and-MEP-Change-Standard.md) | [PR39 MEP SOP](../../procedures/MEP-SOP.md) | Maintenance logs. |  |
| ISO 27001 | A.7.14 | Secure disposal or re-use of equipment | [P54 Media Handling](../../policies/Media-Handling-and-Removable-Media-Policy.md) | [PR27 Data Retention & Destruction](../../procedures/Data-Retention-and-Destruction-Procedure.md) | Sanitization certs. |  |
| ISO 27001 | A.8.1 | User end point devices | [S01 Workstation Baseline](../../standards/Workstation-Baseline.md); [P12 Endpoint Security](../../policies/Endpoint-Security-Policy.md) | [P13 Mobile/BYOD](../../policies/Mobile-Device-and-BYOD-Policy.md) | EDR, encryption, backups. |  |
| ISO 27001 | A.8.2 | Privileged access rights | [P10 PAM](../../policies/Privileged-Access-Management-Policy.md); [S06 Identity & PAM](../../standards/Identity-and-PAM-Standard.md) | [PR05 Privileged Elevation](../../procedures/Privileged-Access-Elevation-Procedure.md) | Duo, session recording. |  |
| ISO 27001 | A.8.3 | Information access restriction | [P64 Access Control](../../policies/Access-Control-Policy.md) | [S06 Identity & PAM](../../standards/Identity-and-PAM-Standard.md) | RBAC maps, reviews. |  |
| ISO 27001 | A.8.4 | Access to source code | [S10 CI/CD Security](../../standards/CI-CD-Security-Standard.md) | [P18 Secure SDLC](../../policies/Secure-Software-Development-Policy.md) | Repo ACLs, approvals. |  |
| ISO 27001 | A.8.5 | Secure authentication | [P09 Authentication & MFA](../../policies/Authentication-and-MFA-Policy.md) | [S06 Identity & PAM](../../standards/Identity-and-PAM-Standard.md) | MFA policies, logs. |  |
| ISO 27001 | A.8.6 | Capacity management | [P44 Capacity & Performance](../../policies/Capacity-and-Performance-Management-Policy.md) | [R18 Capacity & Availability Reports](../../plans/Capacity-and-Availability-Reports.md) | Utilization dashboards. |  |
| ISO 27001 | A.8.7 | Protection against malware | [S01 Workstation Baseline](../../standards/Workstation-Baseline.md) | [S02 Server Baseline](../../standards/Server-Baseline.md) | AV/EDR status. |  |
| ISO 27001 | A.8.8 | Management of technical vulnerabilities | [P20 Vuln & Patch Mgmt](../../policies/Vulnerability-and-Patch-Management-Policy.md) | [S23 Vulnerability Scanning](../../standards/Vulnerability-Scanning-Standard.md); [PR11 Vuln Mgmt](../../procedures/Vulnerability-Management-Procedure.md) | Scan reports, SLAs. |  |
| ISO 27001 | A.8.9 | Configuration management | [PR10 Configuration Mgmt](../../procedures/Configuration-Management-Procedure.md) | [P17 Secure Configuration](../../policies/Secure-Configuration-and-Hardening-Policy.md) | Baselines, drift reports. |  |
| ISO 27001 | A.8.10 | Information deletion | [PR27 Data Retention & Destruction](../../procedures/Data-Retention-and-Destruction-Procedure.md) | [P30 Data Retention & Disposal](../../policies/Data-Retention-and-Disposal-Policy.md) | Deletion logs, tickets. |  |
| ISO 27001 | A.8.11 | Data masking | [S11 API Security](../../standards/API-Security-Standard.md) | [P06 Data Classification](../../policies/Data-Classification-and-Handling-Policy.md); [S21 Database Security](../../standards/Database-Security-Standard.md) | Masking configs, queries. |  |
| ISO 27001 | A.8.12 | Data leakage prevention | [S24 DLP](../../standards/Data-Loss-Prevention-Standard.md) | [P06 Data Classification](../../policies/Data-Classification-and-Handling-Policy.md) | DLP alerts, policies. |  |
| ISO 27001 | A.8.13 | Information backup | [P25 Backup & Restore](../../policies/Backup-and-Restore-Policy.md) | [S08 Backup & Immutability](../../standards/Backup-and-Immutability-Standard.md); [PR21 Backup & Restore](../../procedures/Backup-and-Restore-Procedure.md) | Backup jobs, restore tests. |  |
| ISO 27001 | A.8.14 | Redundancy of processing facilities | [PL04 BCMS Strategy](../../plans/BCMS-Strategy-Plan.md) | [P44 Capacity & Performance](../../policies/Capacity-and-Performance-Management-Policy.md) | HA configs, failover tests. |  |
| ISO 27001 | A.8.15 | Logging | [P21 Logging & SIEM](../../policies/Logging-Monitoring-and-SIEM-Policy.md) | [S07 Logging & Time Sync](../../standards/Logging-and-Time-Sync-Standard.md); [PR19 SIEM Onboarding](../../procedures/Logging-and-SIEM-Onboarding-Procedure.md) | SIEM logs, retention settings, manual exports if needed. |  |
| ISO 27001 | A.8.16 | Monitoring activities | [P21 Logging & SIEM](../../policies/Logging-Monitoring-and-SIEM-Policy.md) | [PR20 Alert Triage](../../procedures/Alert-Triage-and-Escalation-Procedure.md); [PR42 Continuous Monitoring](../../procedures/Continuous-Control-Monitoring-Procedure.md) | Alerts, tuning records. |  |
| ISO 27001 | A.8.17 | Clock synchronization | [S07 Logging & Time Sync](../../standards/Logging-and-Time-Sync-Standard.md) |  | NTP configs, time skew reports. |  |
| ISO 27001 | A.8.18 | Privileged utility programs | [S06 Identity & PAM](../../standards/Identity-and-PAM-Standard.md) | [P10 PAM](../../policies/Privileged-Access-Management-Policy.md) | Allow-list, break-glass logs. |  |
| ISO 27001 | A.8.19 | Software installation on operational systems | [PR09 Release Management](../../procedures/Release-Management-Procedure.md) | [S02 Server Baseline](../../standards/Server-Baseline.md) | Change records, approvals. |  |
| ISO 27001 | A.8.20 | Networks security | [P14 Network Security](../../policies/Network-Security-Policy.md) | [S04 Network Segmentation](../../standards/Network-Segmentation-Standard.md); [S05 Firewall/WAF](../../standards/Firewall-and-WAF-Standard.md) | FW rules, baselines. |  |
| ISO 27001 | A.8.21 | Security of network services | [S05 Firewall/WAF](../../standards/Firewall-and-WAF-Standard.md) | [P14 Network Security](../../policies/Network-Security-Policy.md) | Provider SLAs, configs. |  |
| ISO 27001 | A.8.22 | Segregation of networks | [S04 Network Segmentation](../../standards/Network-Segmentation-Standard.md) | [S22 Cloud Landing Zone](../../standards/Cloud-Landing-Zone-Standard.md) | Network maps, policies. |  |
| ISO 27001 | A.8.23 | Web filtering | [S05 Firewall/WAF](../../standards/Firewall-and-WAF-Standard.md) | [P36 Email & Communications](../../policies/Email-and-Communications-Security-Policy.md); [S01 Workstation Baseline](../../standards/Workstation-Baseline.md) | URL policy, logs. |  |
| ISO 27001 | A.8.24 | Use of cryptography | [P16 Cryptography & Key Mgmt](../../policies/Cryptography-and-Key-Management-Policy.md) | [S21 Database Security](../../standards/Database-Security-Standard.md); [R06 Keys & Certs Inventory](../../plans/Keys-and-Certificates-Inventory.md) | Keystores, rotation logs. |  |
| ISO 27001 | A.8.25 | Secure development life cycle | [P18 Secure SDLC](../../policies/Secure-Software-Development-Policy.md) | [S10 CI/CD Security](../../standards/CI-CD-Security-Standard.md) | SDLC phases, sign-offs. |  |
| ISO 27001 | A.8.26 | Application security requirements | [S11 API Security](../../standards/API-Security-Standard.md) | [P18 Secure SDLC](../../policies/Secure-Software-Development-Policy.md) | Security requirements docs. |  |
| ISO 27001 | A.8.27 | Secure system architecture & engineering | [P18 Secure SDLC](../../policies/Secure-Software-Development-Policy.md) | [S03 Container/K8s Baseline](../../standards/Container-and-Kubernetes-Baseline.md) | Architecture reviews. |  |
| ISO 27001 | A.8.28 | Secure coding | [P18 Secure SDLC](../../policies/Secure-Software-Development-Policy.md) | [PR24 SAST/DAST & Code Review](../../procedures/SAST-DAST-and-Code-Review-Procedure.md) | Code review records. |  |
| ISO 27001 | A.8.29 | Security testing in dev and acceptance | [PR24 SAST/DAST & Code Review](../../procedures/SAST-DAST-and-Code-Review-Procedure.md) | [S10 CI/CD Security](../../standards/CI-CD-Security-Standard.md) | Test reports, gates. |  |
| ISO 27001 | A.8.30 | Outsourced development | [P26 Supplier & Third-Party Risk](../../policies/Supplier-and-Third-Party-Risk-Management-Policy.md) | [PR30 Vendor Due Diligence](../../procedures/Vendor-Due-Diligence-and-Onboarding-Procedure.md) | Contracts, oversight records. |  |
| ISO 27001 | A.8.31 | Separation of dev/test/prod | [S10 CI/CD Security](../../standards/CI-CD-Security-Standard.md) | [S03 Container/K8s Baseline](../../standards/Container-and-Kubernetes-Baseline.md) | Environment ACLs. |  |
| ISO 27001 | A.8.32 | Change management | [P19 Change & Release Mgmt](../../policies/Change-and-Release-Management-Policy.md) | [PR07 Change Control](../../procedures/Change-Control-Procedure.md); [PR09 Release Mgmt](../../procedures/Release-Management-Procedure.md) | Change tickets, approvals. |  |
| ISO 27001 | A.8.33 | Test information | [PR24 SAST/DAST & Code Review](../../procedures/SAST-DAST-and-Code-Review-Procedure.md) | [P31 Privacy & Data Protection](../../policies/Privacy-and-Data-Protection-Policy.md) | Synthetic/anonymized data logs. |  |
| ISO 27001 | A.8.34 | Protect systems during audit testing | [PR41 Penetration Testing](../../procedures/Penetration-Testing-Procedure.md) | [PR45 Internal Audit](../../procedures/Internal-Audit-Procedure.md) | Test plans, approvals. |  |

## Revision History

| Version | Date       | Author | Description |
|---------|------------|--------|-------------|
| 1.0.0   | 2025-11-05 |        | Seeded Annex A mappings for priority controls. |


