---
title: "ISO/IEC 27001:2022 – Annex A Control Catalog"
doc_type: "Catalog"
id: "GRS-ISMS-CAT-27001-A"
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
| Title | ISO/IEC 27001:2022 – Annex A Control Catalog |
| Document ID | GRS-ISMS-CAT-27001-A |
| Version | 1.0.0 |
| Status | Draft |
| Owner | GRC Analyst |
| Program Manager | Josh Mayorga, Compliance Manager |
| Approver | ISMS Manager |
| Approval Date |  |
| Effective Date |  |
| Next Review Date |  |

## Purpose

Reference list of Annex A controls (93 total) organized by theme to support requirement mapping.

## Control List (full)

| Standard | Requirement ID | Title | Primary Documents | Supporting Documents | Evidence (examples) | Notes |
|----------|-----------------|-------|-------------------|----------------------|---------------------|-------|
| ISO 27001 | A.5.1 | Policies for information security | [P01](../../policies/Information-Security-Policy.md); [P34](../../policies/Quality-and-Document-Control-Policy.md) | [P03](../../policies/Risk-Management-Policy.md) | Policy approvals; revision history. |  |
| ISO 27001 | A.5.2 | Information security roles and responsibilities | [P01](../../policies/Information-Security-Policy.md); [P08](../../policies/Identity-and-Access-Management-Policy.md) | [P35](../../policies/Segregation-of-Duties-Policy.md) | RACI; access review sign‑offs. |  |
| ISO 27001 | A.5.3 | Segregation of duties | [P35](../../policies/Segregation-of-Duties-Policy.md) | [P08](../../policies/Identity-and-Access-Management-Policy.md); [PR05](../../procedures/Privileged-Access-Elevation-Procedure.md) | SoD matrix; approvals. |  |
| ISO 27001 | A.5.4 | Management responsibilities | [P01](../../policies/Information-Security-Policy.md) | [P34](../../policies/Quality-and-Document-Control-Policy.md) | Comms to staff; directives. |  |
| ISO 27001 | A.5.5 | Contact with authorities | [P22](../../policies/Incident-Response-Policy.md) | [PR13](../../procedures/IR-Runbook-General.md) | Contact lists; notifications. |  |
| ISO 27001 | A.5.6 | Contact with special interest groups | [P01](../../policies/Information-Security-Policy.md) | [P21](../../policies/Logging-Monitoring-and-SIEM-Policy.md) | Membership records. |  |
| ISO 27001 | A.5.7 | Threat intelligence | [P21](../../policies/Logging-Monitoring-and-SIEM-Policy.md) | [PR20](../../procedures/Alert-Triage-and-Escalation-Procedure.md) | TI feeds; rule updates. |  |
| ISO 27001 | A.5.8 | Information security in project management | [P18](../../policies/Secure-Software-Development-Policy.md) | [S10](../../standards/CI-CD-Security-Standard.md); [PR24](../../procedures/SAST-DAST-and-Code-Review-Procedure.md) | Design reviews; gates. |  |
| ISO 27001 | A.5.9 | Inventory of information and other associated assets | [P05](../../policies/Asset-Management-Policy.md) | [R02](../../plans/Asset-Inventory-and-CMDB.md); [PR10](../../procedures/Configuration-Management-Procedure.md) | CMDB extracts; owners. |  |
| ISO 27001 | A.5.10 | Acceptable use of information and other associated assets | [P07](../../policies/Acceptable-Use-Policy.md) | [P12](../../policies/Endpoint-Security-Policy.md); [S01](../../standards/Workstation-Baseline.md) | AUP acks; conformance. |  |
| ISO 27001 | A.5.11 | Return of assets | [P05](../../policies/Asset-Management-Policy.md) | [PR06](../../procedures/Onboarding-and-Offboarding-Procedure.md) | Offboarding checklist. |  |
| ISO 27001 | A.5.12 | Classification of information | [P06](../../policies/Data-Classification-and-Handling-Policy.md) | [S12](../../standards/Data-Classification-Marking-Standard.md) | Label catalog; examples. |  |
| ISO 27001 | A.5.13 | Labelling of information | [S12](../../standards/Data-Classification-Marking-Standard.md) | [P06](../../policies/Data-Classification-and-Handling-Policy.md) | Auto‑label configs. |  |
| ISO 27001 | A.5.14 | Information transfer | [P06](../../policies/Data-Classification-and-Handling-Policy.md) | [P36](../../policies/Email-and-Communications-Security-Policy.md); [P16](../../policies/Cryptography-and-Key-Management-Policy.md) | Transfer agreements; TLS/mTLS. |  |
| ISO 27001 | A.5.15 | Access control | [P64](../../policies/Access-Control-Policy.md); [P08](../../policies/Identity-and-Access-Management-Policy.md) | [S06](../../standards/Identity-and-PAM-Standard.md) | RBAC; review logs. |  |
| ISO 27001 | A.5.16 | Identity management | [P08](../../policies/Identity-and-Access-Management-Policy.md) | [S06](../../standards/Identity-and-PAM-Standard.md); [PR04](../../procedures/Access-Provisioning-and-Deprovisioning-Procedure.md) | JML tickets; Entra logs. |  |
| ISO 27001 | A.5.17 | Authentication information | [P09](../../policies/Authentication-and-MFA-Policy.md) | [S06](../../standards/Identity-and-PAM-Standard.md) | MFA configs; resets. |  |
| ISO 27001 | A.5.18 | Access rights | [P64](../../policies/Access-Control-Policy.md) | [PR04](../../procedures/Access-Provisioning-and-Deprovisioning-Procedure.md); [PR05](../../procedures/Privileged-Access-Elevation-Procedure.md) | Access reviews; approvals. |  |
| ISO 27001 | A.5.19 | Information security in supplier relationships | [P26](../../policies/Supplier-and-Third-Party-Risk-Management-Policy.md) | [PR30](../../procedures/Vendor-Due-Diligence-and-Onboarding-Procedure.md) | DDQs; risk tiers. |  |
| ISO 27001 | A.5.20 | Addressing IS within supplier agreements | [P26](../../policies/Supplier-and-Third-Party-Risk-Management-Policy.md) | [P31](../../policies/Privacy-and-Data-Protection-Policy.md) | Contract clauses; DPA. |  |
| ISO 27001 | A.5.21 | IS in the ICT supply chain | [P26](../../policies/Supplier-and-Third-Party-Risk-Management-Policy.md) | [S22](../../standards/Cloud-Landing-Zone-Standard.md); [S09](../../standards/Secrets-Management-Standard.md) | Vendor monitoring; SBOM. |  |
| ISO 27001 | A.5.22 | Supplier service monitoring and review | [PR31](../../procedures/Subservice-Monitoring-Procedure.md) | [P26](../../policies/Supplier-and-Third-Party-Risk-Management-Policy.md) | SOC reports; trackers. |  |
| ISO 27001 | A.5.23 | Information security for use of cloud services | [P15](../../policies/Cloud-Security-Policy.md) | [S22](../../standards/Cloud-Landing-Zone-Standard.md) | Guardrails; IaC. |  |
| ISO 27001 | A.5.24 | IS incident management planning and preparation | [P22](../../policies/Incident-Response-Policy.md) | [PL07](../../plans/Incident-Playbooks.md) | IR plan; call trees. |  |
| ISO 27001 | A.5.25 | Assessment and decision on IS events | [PR20](../../procedures/Alert-Triage-and-Escalation-Procedure.md) | [P21](../../policies/Logging-Monitoring-and-SIEM-Policy.md) | Triage logs; alerts. |  |
| ISO 27001 | A.5.26 | Response to IS incidents | [P22](../../policies/Incident-Response-Policy.md) | [PR13](../../procedures/IR-Runbook-General.md); [PR14](../../procedures/IR-Runbook-Credential-Leak.md); [PR15](../../procedures/IR-Runbook-Ransomware.md); [PR16](../../procedures/IR-Runbook-DDoS-WAF.md); [PR17](../../procedures/IR-Runbook-Data-Breach.md) | Incident tickets; timelines. |  |
| ISO 27001 | A.5.27 | Learning from IS incidents | [PR46](../../procedures/Management-Review-Procedure.md) | [P60](../../policies/Metrics-and-Continuous-Improvement-Policy.md) | PIR; CAPA. |  |
| ISO 27001 | A.5.28 | Collection of evidence | [PR18](../../procedures/Forensics-and-Evidence-Handling-SOP.md) | [P32](../../policies/Records-Management-and-Evidence-Policy.md) | Chain of custody; exports. |  |
| ISO 27001 | A.5.29 | Information security during disruption | [P23](../../policies/Business-Continuity-Policy.md) | [PL11](../../plans/Crisis-Management-Plan.md) | Plans referencing IS constraints. |  |
| ISO 27001 | A.5.30 | ICT readiness for business continuity | [P24](../../policies/Disaster-Recovery-Policy.md) | [PL05](../../plans/Disaster-Recovery-Plans.md); [S07](../../standards/Logging-and-Time-Sync-Standard.md) | DR tests; NTP. |  |
| ISO 27001 | A.5.31 | Legal, statutory, regulatory and contractual requirements | [P63](../../policies/Legal-and-Regulatory-Compliance-Policy.md) | [P31](../../policies/Privacy-and-Data-Protection-Policy.md); [P32](../../policies/Records-Management-and-Evidence-Policy.md) | Obligations register. |  |
| ISO 27001 | A.5.32 | Intellectual property rights | [P63](../../policies/Legal-and-Regulatory-Compliance-Policy.md) | [P32](../../policies/Records-Management-and-Evidence-Policy.md) | IPR procedures. |  |
| ISO 27001 | A.5.33 | Protection of records | [P32](../../policies/Records-Management-and-Evidence-Policy.md) | [P30](../../policies/Data-Retention-and-Disposal-Policy.md) | Retention; access logs. |  |
| ISO 27001 | A.5.34 | Privacy and protection of PII | [P31](../../policies/Privacy-and-Data-Protection-Policy.md) | [S24](../../standards/Data-Loss-Prevention-Standard.md) | DPIAs; DLP. |  |
| ISO 27001 | A.5.35 | Independent review of information security | [PR45](../../procedures/Internal-Audit-Procedure.md) | [PL09](../../plans/Audit-and-Assessment-Plan.md) | Audit reports. |  |
| ISO 27001 | A.5.36 | Compliance with IS policies, rules and standards | [PR45](../../procedures/Internal-Audit-Procedure.md) | [P34](../../policies/Quality-and-Document-Control-Policy.md) | Review findings. |  |
| ISO 27001 | A.5.37 | Documented operating procedures | [PR10](../../procedures/Configuration-Management-Procedure.md) | [PR07](../../procedures/Change-Control-Procedure.md) | SOP repository. |  |
| ISO 27001 | A.6.1 | Screening | [P48](../../policies/HR-Security-Policy.md) | [PR06](../../procedures/Onboarding-and-Offboarding-Procedure.md) | Background checks. |  |
| ISO 27001 | A.6.2 | Terms and conditions of employment | [P48](../../policies/HR-Security-Policy.md) | [P07](../../policies/Acceptable-Use-Policy.md) | Contract clauses. |  |
| ISO 27001 | A.6.3 | IS awareness, education and training | [P33](../../policies/Training-and-Security-Awareness-Policy.md) | [PL02](../../plans/Security-Awareness-and-Phishing-Plan.md); [R13](../../plans/Training-Attendance-and-Results.md) | Attendance; curricula. |  |
| ISO 27001 | A.6.4 | Disciplinary process | [P48](../../policies/HR-Security-Policy.md) | [P07](../../policies/Acceptable-Use-Policy.md) | Disciplinary records. |  |
| ISO 27001 | A.6.5 | Responsibilities after termination or change | [P48](../../policies/HR-Security-Policy.md) | [PR06](../../procedures/Onboarding-and-Offboarding-Procedure.md) | Exit docs; NDA. |  |
| ISO 27001 | A.6.6 | Confidentiality or non-disclosure agreements | [P31](../../policies/Privacy-and-Data-Protection-Policy.md) | [P48](../../policies/HR-Security-Policy.md) | Signed NDAs. |  |
| ISO 27001 | A.6.7 | Remote working | [P11](../../policies/Remote-Work-Security-Policy.md) | [S01](../../standards/Workstation-Baseline.md); [P62](../../policies/Remote-Access-Policy.md) | Device posture; VPN. |  |
| ISO 27001 | A.6.8 | IS event reporting | [P21](../../policies/Logging-Monitoring-and-SIEM-Policy.md) | [T05](../../templates/Incident-Report-Form.md) | Tickets; reports. |  |
| ISO 27001 | A.7.1 | Physical security perimeters | [S17](../../standards/Facility-Physical-Security-Standard.md) | [P28](../../policies/Physical-and-Environmental-Security-Policy.md) | Site drawings. |  |
| ISO 27001 | A.7.2 | Physical entry | [S17](../../standards/Facility-Physical-Security-Standard.md) | [PR35](../../procedures/Visitor-Management-Procedure.md); [R20](../../plans/Visitor-and-Badge-Logs.md) | Badge/kiosk logs. |  |
| ISO 27001 | A.7.3 | Securing offices, rooms and facilities | [S17](../../standards/Facility-Physical-Security-Standard.md) | [P28](../../policies/Physical-and-Environmental-Security-Policy.md) | Inspection records. |  |
| ISO 27001 | A.7.4 | Physical security monitoring | [P52](../../policies/CCTV-and-Surveillance-Policy.md) | [S17](../../standards/Facility-Physical-Security-Standard.md) | CCTV exports. |  |
| ISO 27001 | A.7.5 | Protecting against physical and environmental threats | [P28](../../policies/Physical-and-Environmental-Security-Policy.md) | [S16](../../standards/DCIM-Telemetry-Standard.md); [S19](../../standards/Maintenance-and-MEP-Change-Standard.md) | Alarms; thresholds. |  |
| ISO 27001 | A.7.6 | Working in secure areas | [S17](../../standards/Facility-Physical-Security-Standard.md) | [PR34](../../procedures/NOC-Operations-Manual.md) | SOP adherence. |  |
| ISO 27001 | A.7.7 | Clear desk and clear screen | [P61](../../policies/Clean-Desk-and-Clear-Screen-Policy.md) | [P07](../../policies/Acceptable-Use-Policy.md) | Floor walk results. |  |
| ISO 27001 | A.7.8 | Equipment siting and protection | [S17](../../standards/Facility-Physical-Security-Standard.md) | [S02](../../standards/Server-Baseline.md) | Rack diagrams. |  |
| ISO 27001 | A.7.9 | Security of assets off-premises | [P05](../../policies/Asset-Management-Policy.md) | [P12](../../policies/Endpoint-Security-Policy.md) | MDM; loan logs. |  |
| ISO 27001 | A.7.10 | Storage media | [P54](../../policies/Media-Handling-and-Removable-Media-Policy.md) | [PR27](../../procedures/Data-Retention-and-Destruction-Procedure.md) | Disposal certs. |  |
| ISO 27001 | A.7.11 | Supporting utilities | [S16](../../standards/DCIM-Telemetry-Standard.md) | [S15](../../standards/NOC-Build-Standard.md) | UPS/Gen test logs. |  |
| ISO 27001 | A.7.12 | Cabling security | [S17](../../standards/Facility-Physical-Security-Standard.md) | [S04](../../standards/Network-Segmentation-Standard.md) | Cabling routes. |  |
| ISO 27001 | A.7.13 | Equipment maintenance | [S19](../../standards/Maintenance-and-MEP-Change-Standard.md) | [PR39](../../procedures/MEP-SOP.md) | Maintenance tickets. |  |
| ISO 27001 | A.7.14 | Secure disposal or re-use of equipment | [P54](../../policies/Media-Handling-and-Removable-Media-Policy.md) | [PR27](../../procedures/Data-Retention-and-Destruction-Procedure.md) | Sanitization records. |  |
| ISO 27001 | A.8.1 | User end point devices | [S01](../../standards/Workstation-Baseline.md); [P12](../../policies/Endpoint-Security-Policy.md) | [P13](../../policies/Mobile-Device-and-BYOD-Policy.md) | EDR; encryption; backups. |  |
| ISO 27001 | A.8.2 | Privileged access rights | [P10](../../policies/Privileged-Access-Management-Policy.md); [S06](../../standards/Identity-and-PAM-Standard.md) | [PR05](../../procedures/Privileged-Access-Elevation-Procedure.md) | Duo; session recording. |  |
| ISO 27001 | A.8.3 | Information access restriction | [P64](../../policies/Access-Control-Policy.md) | [S06](../../standards/Identity-and-PAM-Standard.md) | RBAC; reviews. |  |
| ISO 27001 | A.8.4 | Access to source code | [S10](../../standards/CI-CD-Security-Standard.md) | [P18](../../policies/Secure-Software-Development-Policy.md) | Repo ACLs; PR approvals. |  |
| ISO 27001 | A.8.5 | Secure authentication | [P09](../../policies/Authentication-and-MFA-Policy.md) | [S06](../../standards/Identity-and-PAM-Standard.md) | MFA policies; logs. |  |
| ISO 27001 | A.8.6 | Capacity management | [P44](../../policies/Capacity-and-Performance-Management-Policy.md) | [R18](../../plans/Capacity-and-Availability-Reports.md) | Utilization dashboards. |  |
| ISO 27001 | A.8.7 | Protection against malware | [S01](../../standards/Workstation-Baseline.md) | [S02](../../standards/Server-Baseline.md) | AV/EDR status. |  |
| ISO 27001 | A.8.8 | Management of technical vulnerabilities | [P20](../../policies/Vulnerability-and-Patch-Management-Policy.md) | [S23](../../standards/Vulnerability-Scanning-Standard.md); [PR11](../../procedures/Vulnerability-Management-Procedure.md) | Scan reports; SLAs. |  |
| ISO 27001 | A.8.9 | Configuration management | [PR10](../../procedures/Configuration-Management-Procedure.md) | [P17](../../policies/Secure-Configuration-and-Hardening-Policy.md) | Baselines; drift. |  |
| ISO 27001 | A.8.10 | Information deletion | [PR27](../../procedures/Data-Retention-and-Destruction-Procedure.md) | [P30](../../policies/Data-Retention-and-Disposal-Policy.md) | Deletion logs. |  |
| ISO 27001 | A.8.11 | Data masking | [S11](../../standards/API-Security-Standard.md) | [S21](../../standards/Database-Security-Standard.md); [P06](../../policies/Data-Classification-and-Handling-Policy.md) | Masking configs. |  |
| ISO 27001 | A.8.12 | Data leakage prevention | [S24](../../standards/Data-Loss-Prevention-Standard.md) | [P06](../../policies/Data-Classification-and-Handling-Policy.md) | DLP alerts. |  |
| ISO 27001 | A.8.13 | Information backup | [P25](../../policies/Backup-and-Restore-Policy.md) | [S08](../../standards/Backup-and-Immutability-Standard.md); [PR21](../../procedures/Backup-and-Restore-Procedure.md) | Backup jobs; restores. |  |
| ISO 27001 | A.8.14 | Redundancy of information processing facilities | [PL04](../../plans/BCMS-Strategy-Plan.md) | [P44](../../policies/Capacity-and-Performance-Management-Policy.md) | HA configs; tests. |  |
| ISO 27001 | A.8.15 | Logging | [P21](../../policies/Logging-Monitoring-and-SIEM-Policy.md) | [S07](../../standards/Logging-and-Time-Sync-Standard.md); [PR19](../../procedures/Logging-and-SIEM-Onboarding-Procedure.md) | SIEM logs; retention; manual exports. |  |
| ISO 27001 | A.8.16 | Monitoring activities | [P21](../../policies/Logging-Monitoring-and-SIEM-Policy.md) | [PR20](../../procedures/Alert-Triage-and-Escalation-Procedure.md); [PR42](../../procedures/Continuous-Control-Monitoring-Procedure.md) | Alerts; tuning records. |  |
| ISO 27001 | A.8.17 | Clock synchronization | [S07](../../standards/Logging-and-Time-Sync-Standard.md) |  | NTP configs; skew reports. |  |
| ISO 27001 | A.8.18 | Use of privileged utility programs | [S06](../../standards/Identity-and-PAM-Standard.md) | [P10](../../policies/Privileged-Access-Management-Policy.md) | Allow-list; logs. |  |
| ISO 27001 | A.8.19 | Installation of software on operational systems | [PR09](../../procedures/Release-Management-Procedure.md) | [S02](../../standards/Server-Baseline.md) | Change approvals. |  |
| ISO 27001 | A.8.20 | Networks security | [P14](../../policies/Network-Security-Policy.md) | [S04](../../standards/Network-Segmentation-Standard.md); [S05](../../standards/Firewall-and-WAF-Standard.md) | FW rules; configs. |  |
| ISO 27001 | A.8.21 | Security of network services | [S05](../../standards/Firewall-and-WAF-Standard.md) | [P14](../../policies/Network-Security-Policy.md) | Provider SLAs; configs. |  |
| ISO 27001 | A.8.22 | Segregation of networks | [S04](../../standards/Network-Segmentation-Standard.md) | [S22](../../standards/Cloud-Landing-Zone-Standard.md) | Segmentation diagrams. |  |
| ISO 27001 | A.8.23 | Web filtering | [S05](../../standards/Firewall-and-WAF-Standard.md) | [P36](../../policies/Email-and-Communications-Security-Policy.md); [S01](../../standards/Workstation-Baseline.md) | URL policy; logs. |  |
| ISO 27001 | A.8.24 | Use of cryptography | [P16](../../policies/Cryptography-and-Key-Management-Policy.md) | [S21](../../standards/Database-Security-Standard.md); [R06](../../plans/Keys-and-Certificates-Inventory.md) | Keystores; rotations. |  |
| ISO 27001 | A.8.25 | Secure development life cycle | [P18](../../policies/Secure-Software-Development-Policy.md) | [S10](../../standards/CI-CD-Security-Standard.md) | SDLC gates; sign‑offs. |  |
| ISO 27001 | A.8.26 | Application security requirements | [S11](../../standards/API-Security-Standard.md) | [P18](../../policies/Secure-Software-Development-Policy.md) | Requirements docs. |  |
| ISO 27001 | A.8.27 | Secure system architecture and engineering principles | [P18](../../policies/Secure-Software-Development-Policy.md) | [S03](../../standards/Container-and-Kubernetes-Baseline.md) | Architecture reviews. |  |
| ISO 27001 | A.8.28 | Secure coding | [P18](../../policies/Secure-Software-Development-Policy.md) | [PR24](../../procedures/SAST-DAST-and-Code-Review-Procedure.md) | Review records. |  |
| ISO 27001 | A.8.29 | Security testing in development and acceptance | [PR24](../../procedures/SAST-DAST-and-Code-Review-Procedure.md) | [S10](../../standards/CI-CD-Security-Standard.md) | Test reports; gates. |  |
| ISO 27001 | A.8.30 | Outsourced development | [P26](../../policies/Supplier-and-Third-Party-Risk-Management-Policy.md) | [PR30](../../procedures/Vendor-Due-Diligence-and-Onboarding-Procedure.md) | Contracts; oversight. |  |
| ISO 27001 | A.8.31 | Separation of development, test and production environments | [S10](../../standards/CI-CD-Security-Standard.md) | [S03](../../standards/Container-and-Kubernetes-Baseline.md) | Env ACLs; pipelines. |  |
| ISO 27001 | A.8.32 | Change management | [P19](../../policies/Change-and-Release-Management-Policy.md) | [PR07](../../procedures/Change-Control-Procedure.md); [PR09](../../procedures/Release-Management-Procedure.md) | Change tickets. |  |
| ISO 27001 | A.8.33 | Test information | [PR24](../../procedures/SAST-DAST-and-Code-Review-Procedure.md) | [P31](../../policies/Privacy-and-Data-Protection-Policy.md) | Synthetic/anonymized data. |  |
| ISO 27001 | A.8.34 | Protection of information systems during audit testing | [PR41](../../procedures/Penetration-Testing-Procedure.md) | [PR45](../../procedures/Internal-Audit-Procedure.md) | Test plans; approvals. |  |

Note: Control titles reflect ISO/IEC 27001:2022 Annex A wording; evidence examples illustrate typical artifacts.

## Document Index for Mapping

### Policies (P##)

| ID | Title | Path |
|----|-------|------|
| P01 | Information Security Policy (ISMS Charter) | ../../policies/Information-Security-Policy.md |
| P02 | ISMS Scope & Context Policy | ../../policies/ISMS-Scope-and-Context-Policy.md |
| P03 | Risk Management Policy | ../../policies/Risk-Management-Policy.md |
| P04 | Statement of Applicability (SoA) | ../../policies/Statement-of-Applicability.md |
| P05 | Asset Management Policy | ../../policies/Asset-Management-Policy.md |
| P06 | Data Classification & Handling Policy | ../../policies/Data-Classification-and-Handling-Policy.md |
| P07 | Acceptable Use Policy | ../../policies/Acceptable-Use-Policy.md |
| P08 | Identity & Access Management Policy | ../../policies/Identity-and-Access-Management-Policy.md |
| P09 | Authentication & MFA Policy | ../../policies/Authentication-and-MFA-Policy.md |
| P10 | Privileged Access Management Policy | ../../policies/Privileged-Access-Management-Policy.md |
| P11 | Remote Work / WFH Security Policy | ../../policies/Remote-Work-Security-Policy.md |
| P12 | Endpoint Security Policy | ../../policies/Endpoint-Security-Policy.md |
| P13 | Mobile Device & BYOD Policy | ../../policies/Mobile-Device-and-BYOD-Policy.md |
| P14 | Network Security Policy | ../../policies/Network-Security-Policy.md |
| P15 | Cloud Security Policy | ../../policies/Cloud-Security-Policy.md |
| P16 | Cryptography & Key Management Policy | ../../policies/Cryptography-and-Key-Management-Policy.md |
| P17 | Secure Configuration & Hardening Policy | ../../policies/Secure-Configuration-and-Hardening-Policy.md |
| P18 | Secure Software Development Policy | ../../policies/Secure-Software-Development-Policy.md |
| P19 | Change & Release Management Policy | ../../policies/Change-and-Release-Management-Policy.md |
| P20 | Vulnerability & Patch Management Policy | ../../policies/Vulnerability-and-Patch-Management-Policy.md |
| P21 | Logging, Monitoring & SIEM Policy | ../../policies/Logging-Monitoring-and-SIEM-Policy.md |
| P22 | Incident Response Policy | ../../policies/Incident-Response-Policy.md |
| P23 | Business Continuity Management Policy | ../../policies/Business-Continuity-Policy.md |
| P24 | Disaster Recovery Policy | ../../policies/Disaster-Recovery-Policy.md |
| P25 | Backup & Restore Policy | ../../policies/Backup-and-Restore-Policy.md |
| P26 | Supplier & Third-Party Risk Management Policy | ../../policies/Supplier-and-Third-Party-Risk-Management-Policy.md |
| P27 | Subservice Organization Oversight Policy | ../../policies/Subservice-Organization-Oversight-Policy.md |
| P28 | Physical & Environmental Security Policy | ../../policies/Physical-and-Environmental-Security-Policy.md |
| P29 | Visitor Management Policy | ../../policies/Visitor-Management-Policy.md |
| P30 | Data Retention & Disposal Policy | ../../policies/Data-Retention-and-Disposal-Policy.md |
| P31 | Privacy & Data Protection Policy | ../../policies/Privacy-and-Data-Protection-Policy.md |
| P32 | Records Management & Evidence Policy | ../../policies/Records-Management-and-Evidence-Policy.md |
| P33 | Training & Security Awareness Policy | ../../policies/Training-and-Security-Awareness-Policy.md |
| P34 | Quality & Document Control Policy | ../../policies/Quality-and-Document-Control-Policy.md |
| P35 | Segregation of Duties Policy | ../../policies/Segregation-of-Duties-Policy.md |
| P36 | Email & Communications Security Policy | ../../policies/Email-and-Communications-Security-Policy.md |
| P37 | API Security Policy | ../../policies/API-Security-Policy.md |
| P38 | Application Security Testing Policy | ../../policies/Application-Security-Testing-Policy.md |
| P39 | Penetration Testing & Red Team Policy | ../../policies/Penetration-Testing-and-Red-Team-Policy.md |
| P40 | Secrets Management Policy | ../../policies/Secrets-Management-Policy.md |
| P41 | Open-Source Software Governance Policy | ../../policies/Open-Source-Software-Governance-Policy.md |
| P42 | AI & Automation Use Policy | ../../policies/AI-and-Automation-Use-Policy.md |
| P43 | Service Continuity for SaaS Policy | ../../policies/Service-Continuity-for-SaaS-Policy.md |
| P44 | Capacity & Performance Management Policy | ../../policies/Capacity-and-Performance-Management-Policy.md |
| P45 | Financial Controls Policy (ICFR) | ../../policies/Financial-Controls-Policy.md |
| P46 | Revenue Recognition & Billing Policy | ../../policies/Revenue-Recognition-and-Billing-Policy.md |
| P47 | Fraud Prevention & Whistleblower Policy | ../../policies/Fraud-Prevention-and-Whistleblower-Policy.md |
| P48 | HR Security Policy | ../../policies/HR-Security-Policy.md |
| P49 | Health, Safety & Environment Policy | ../../policies/HSE-Policy.md |
| P50 | Facility & Franchise Compliance Policy | ../../policies/Facility-and-Franchise-Compliance-Policy.md |
| P51 | Franchise Branding & Communications Policy | ../../policies/Franchise-Branding-and-Communications-Policy.md |
| P52 | CCTV & Surveillance Policy | ../../policies/CCTV-and-Surveillance-Policy.md |
| P53 | Badge & Key/Card Control Policy | ../../policies/Badge-and-Key-Card-Control-Policy.md |
| P54 | Media Handling & Removable Media Policy | ../../policies/Media-Handling-and-Removable-Media-Policy.md |
| P55 | Customer Data Handling & Confidentiality Policy | ../../policies/Customer-Data-Handling-and-Confidentiality-Policy.md |
| P56 | Data Residency & Sovereignty Policy | ../../policies/Data-Residency-and-Sovereignty-Policy.md |
| P57 | Network Change Control Policy | ../../policies/Network-Change-Control-Policy.md |
| P58 | Incident Communications & Public Relations Policy | ../../policies/Incident-Communications-and-PR-Policy.md |
| P59 | Exception & Compensating Controls Policy | ../../policies/Exception-and-Compensating-Controls-Policy.md |
| P60 | Metrics & Continuous Improvement Policy | ../../policies/Metrics-and-Continuous-Improvement-Policy.md |
| P61 | Clean Desk & Clear Screen Policy | ../../policies/Clean-Desk-and-Clear-Screen-Policy.md |
| P62 | Remote Access Policy | ../../policies/Remote-Access-Policy.md |
| P63 | Legal & Regulatory Compliance Policy | ../../policies/Legal-and-Regulatory-Compliance-Policy.md |
| P64 | Access Control Policy | ../../policies/Access-Control-Policy.md |

### Standards & Baselines (S##)

| ID | Title | Path |
|----|-------|------|
| S01 | Workstation Baseline (Windows/macOS/Linux) | ../../standards/Workstation-Baseline.md |
| S02 | Server Baseline (Linux/Windows) | ../../standards/Server-Baseline.md |
| S03 | Container/Kubernetes Baseline | ../../standards/Container-and-Kubernetes-Baseline.md |
| S04 | Network Segmentation Standard | ../../standards/Network-Segmentation-Standard.md |
| S05 | Firewall/WAF Standard | ../../standards/Firewall-and-WAF-Standard.md |
| S06 | Identity & PAM Standard | ../../standards/Identity-and-PAM-Standard.md |
| S07 | Logging & Time Sync Standard | ../../standards/Logging-and-Time-Sync-Standard.md |
| S08 | Backup & Immutability Standard | ../../standards/Backup-and-Immutability-Standard.md |
| S09 | Secrets Management Standard | ../../standards/Secrets-Management-Standard.md |
| S10 | CI/CD Security Standard | ../../standards/CI-CD-Security-Standard.md |
| S11 | API Security Standard | ../../standards/API-Security-Standard.md |
| S12 | Data Classification Marking Standard | ../../standards/Data-Classification-Marking-Standard.md |
| S13 | Vulnerability Severity & SLA Standard | ../../standards/Vulnerability-Severity-and-SLA-Standard.md |
| S14 | SaaS Multi-Tenancy & Isolation Standard | ../../standards/SaaS-Multi-Tenancy-and-Isolation-Standard.md |
| S15 | NOC Build Standard | ../../standards/NOC-Build-Standard.md |
| S16 | DCIM/Telemetry Standard | ../../standards/DCIM-Telemetry-Standard.md |
| S17 | Facility Physical Security Standard | ../../standards/Facility-Physical-Security-Standard.md |
| S18 | EHS/LOTO Standard | ../../standards/EHS-LOTO-Standard.md |
| S19 | Maintenance & MEP Change Standard | ../../standards/Maintenance-and-MEP-Change-Standard.md |
| S20 | Franchise Technical Baseline Standard | ../../standards/Franchise-Technical-Baseline-Standard.md |
| S21 | Database Security Standard | ../../standards/Database-Security-Standard.md |
| S22 | Cloud Landing Zone Standard | ../../standards/Cloud-Landing-Zone-Standard.md |
| S23 | Vulnerability Scanning Standard | ../../standards/Vulnerability-Scanning-Standard.md |
| S24 | Data Loss Prevention (DLP) Standard | ../../standards/Data-Loss-Prevention-Standard.md |

### Procedures & Runbooks (PR##)

| ID | Title | Path |
|----|-------|------|
| PR01 | ISMS Implementation Procedure | ../../procedures/ISMS-Implementation-Procedure.md |
| PR02 | Risk Assessment Procedure | ../../procedures/Risk-Assessment-Procedure.md |
| PR03 | BIA Procedure | ../../procedures/BIA-Procedure.md |
| PR04 | Access Provisioning/Deprovisioning Procedure | ../../procedures/Access-Provisioning-and-Deprovisioning-Procedure.md |
| PR05 | Privileged Access Elevation Procedure | ../../procedures/Privileged-Access-Elevation-Procedure.md |
| PR06 | Onboarding & Offboarding Procedure | ../../procedures/Onboarding-and-Offboarding-Procedure.md |
| PR07 | Change Control Procedure | ../../procedures/Change-Control-Procedure.md |
| PR08 | Emergency Change Procedure | ../../procedures/Emergency-Change-Procedure.md |
| PR09 | Release Management Procedure | ../../procedures/Release-Management-Procedure.md |
| PR10 | Configuration Management Procedure | ../../procedures/Configuration-Management-Procedure.md |
| PR11 | Vulnerability Management Procedure | ../../procedures/Vulnerability-Management-Procedure.md |
| PR12 | Patch Management Procedure | ../../procedures/Patch-Management-Procedure.md |
| PR13 | Incident Response Runbook (General) | ../../procedures/IR-Runbook-General.md |
| PR14 | IR Runbook – Credential Leak (Cloud) | ../../procedures/IR-Runbook-Credential-Leak.md |
| PR15 | IR Runbook – Ransomware | ../../procedures/IR-Runbook-Ransomware.md |
| PR16 | IR Runbook – DDoS/WAF Evasion | ../../procedures/IR-Runbook-DDoS-WAF.md |
| PR17 | IR Runbook – Data Breach (PII/CI) | ../../procedures/IR-Runbook-Data-Breach.md |
| PR18 | Forensics & Evidence Handling SOP | ../../procedures/Forensics-and-Evidence-Handling-SOP.md |
| PR19 | Logging & SIEM Onboarding Procedure | ../../procedures/Logging-and-SIEM-Onboarding-Procedure.md |
| PR20 | Alert Triage & Escalation Procedure | ../../procedures/Alert-Triage-and-Escalation-Procedure.md |
| PR21 | Backup & Restore Procedure | ../../procedures/Backup-and-Restore-Procedure.md |
| PR22 | DR Invocation & Recovery Procedure | ../../procedures/DR-Invocation-and-Recovery-Procedure.md |
| PR23 | Tabletop Exercise Procedure | ../../procedures/Tabletop-Exercise-Procedure.md |
| PR24 | SAST/DAST & Code Review Procedure | ../../procedures/SAST-DAST-and-Code-Review-Procedure.md |
| PR25 | Secrets Rotation Procedure | ../../procedures/Secrets-Rotation-Procedure.md |
| PR26 | CI/CD Hardening Procedure | ../../procedures/CI-CD-Hardening-Procedure.md |
| PR27 | Data Retention & Destruction Procedure | ../../procedures/Data-Retention-and-Destruction-Procedure.md |
| PR28 | Customer Onboarding & Offboarding Procedure | ../../procedures/Customer-Onboarding-and-Offboarding-Procedure.md |
| PR29 | Support & Escalation Procedure | ../../procedures/Support-and-Escalation-Procedure.md |
| PR30 | Vendor Due Diligence & Onboarding Procedure | ../../procedures/Vendor-Due-Diligence-and-Onboarding-Procedure.md |
| PR31 | Subservice Monitoring Procedure | ../../procedures/Subservice-Monitoring-Procedure.md |
| PR32 | Franchise Site Onboarding Procedure | ../../procedures/Franchise-Site-Onboarding-Procedure.md |
| PR33 | Franchise Compliance Audit Procedure | ../../procedures/Franchise-Compliance-Audit-Procedure.md |
| PR34 | NOC Operations Manual | ../../procedures/NOC-Operations-Manual.md |
| PR35 | Visitor Management Procedure | ../../procedures/Visitor-Management-Procedure.md |
| PR36 | Badge Issuance & Revocation Procedure | ../../procedures/Badge-Issuance-and-Revocation-Procedure.md |
| PR37 | EHS Incident Reporting Procedure | ../../procedures/EHS-Incident-Reporting-Procedure.md |
| PR38 | LOTO Procedure | ../../procedures/LOTO-Procedure.md |
| PR39 | Maintenance Method of Procedure (MEP) SOP | ../../procedures/MEP-SOP.md |
| PR40 | CCTV Export & Review Procedure | ../../procedures/CCTV-Export-and-Review-Procedure.md |
| PR41 | Penetration Testing Procedure | ../../procedures/Penetration-Testing-Procedure.md |
| PR42 | Continuous Control Monitoring Procedure | ../../procedures/Continuous-Control-Monitoring-Procedure.md |
| PR43 | Metrics & KRIs Reporting Procedure | ../../procedures/Metrics-and-KRIs-Reporting-Procedure.md |
| PR44 | Exception & Compensating Controls Procedure | ../../procedures/Exception-and-Compensating-Controls-Procedure.md |
| PR45 | Internal Audit Procedure | ../../procedures/Internal-Audit-Procedure.md |
| PR46 | Management Review Procedure | ../../procedures/Management-Review-Procedure.md |
| PR47 | Quality Assurance Procedure | ../../procedures/Quality-Assurance-Procedure.md |
| PR48 | Revenue & Billing Controls Procedure | ../../procedures/Revenue-and-Billing-Controls-Procedure.md |
| PR49 | Financial System Access Procedure | ../../procedures/Financial-System-Access-Procedure.md |
| PR50 | Reconciliations & Exception Management Procedure | ../../procedures/Reconciliations-and-Exception-Management-Procedure.md |
| PR51 | DPIA Procedure | ../../procedures/DPIA-Procedure.md |

### Plans & Playbooks (PL##)

| ID | Title | Path |
|----|-------|------|
| PL01 | Program Plan | ../../plans/Program-Plan.md |
| PL02 | Security Awareness & Phishing Plan | ../../plans/Security-Awareness-and-Phishing-Plan.md |
| PL03 | BIA Reports – by Function | ../../plans/BIA-Reports.md |
| PL04 | BCMS Strategy Plan | ../../plans/BCMS-Strategy-Plan.md |
| PL05 | Disaster Recovery Plans – by System | ../../plans/Disaster-Recovery-Plans.md |
| PL06 | Crisis Communications Plan | ../../plans/Crisis-Communications-Plan.md |
| PL07 | Incident Playbooks – by Scenario | ../../plans/Incident-Playbooks.md |
| PL08 | Pen-Test & AppSec Annual Plan | ../../plans/Pen-Test-and-AppSec-Annual-Plan.md |
| PL09 | Audit & Assessment Plan | ../../plans/Audit-and-Assessment-Plan.md |
| PL10 | Franchise Compliance Plan | ../../plans/Franchise-Compliance-Plan.md |
| PL11 | Crisis Management Plan | ../../plans/Crisis-Management-Plan.md |
| PL12 | Workforce Continuity Plan (Pandemic/Long Outage) | ../../plans/Workforce-Continuity-Plan.md |
| SD01 | SOC System Description – GridSite Marketplace | ../../plans/SD-GridSite-Marketplace.md |
| SD02 | SOC System Description – ComputeComplete & GridColo Services | ../../plans/SD-ComputeComplete-and-GridColo.md |
| SD03 | SOC System Description – Vendor Network | ../../plans/SD-Vendor-Network.md |
| SD04 | ICFR Narrative – Billing & Revenue | ../../plans/ICFR-Narrative-Billing-and-Revenue.md |
| SD05 | Network & Data Flow Diagrams – by system | ../../plans/Network-and-Data-Flow-Diagrams.md |
| SD06 | Threat Models (STRIDE) – by system | ../../plans/Threat-Models-STRIDE.md |
| SD07 | NOC Design Package (primary/secondary) | ../../plans/NOC-Design-Package.md |
| SD08 | Franchise Standards Manual | ../../plans/Franchise-Standards-Manual.md |

### Registers, Logs & Inventories (R##)

| ID | Title | Path |
|----|-------|------|
| R01 | Risk Register | ../../plans/Risk-Register.md |
| R02 | Asset Inventory & CMDB | ../../plans/Asset-Inventory-and-CMDB.md |
| R03 | Data Inventory (Record of Processing) | ../../plans/Data-Inventory.md |
| R04 | Access Control Matrix | ../../plans/Access-Control-Matrix.md |
| R05 | Privileged Accounts Register | ../../plans/Privileged-Accounts-Register.md |
| R06 | Keys & Certificates Inventory | ../../plans/Keys-and-Certificates-Inventory.md |
| R07 | Vendor/Subservice Register | ../../plans/Vendor-and-Subservice-Register.md |
| R08 | Customer Commitments & SLAs Register | ../../plans/Customer-Commitments-and-SLAs-Register.md |
| R09 | Change Log | ../../plans/Change-Log.md |
| R10 | Incident Log | ../../plans/Incident-Log.md |
| R11 | Vulnerability Register | ../../plans/Vulnerability-Register.md |
| R12 | Patch Register | ../../plans/Patch-Register.md |
| R13 | Training Attendance & Results | ../../plans/Training-Attendance-and-Results.md |
| R14 | Internal Audit Findings & CAPA Tracker | ../../plans/Internal-Audit-Findings-and-CAPA-Tracker.md |
| R15 | BC/DR Test Records | ../../plans/BC-DR-Test-Records.md |
| R16 | Backup & Restore Test Logs | ../../plans/Backup-and-Restore-Test-Logs.md |
| R17 | Pen-Test Reports & Remediation Tracker | ../../plans/Pen-Test-Reports-and-Remediation-Tracker.md |
| R18 | Capacity & Availability Reports | ../../plans/Capacity-and-Availability-Reports.md |
| R19 | Energy & PUE Reports (facilities) | ../../plans/Energy-and-PUE-Reports.md |
| R20 | Visitor & Badge Logs (sites) | ../../plans/Visitor-and-Badge-Logs.md |
| R21 | ISMS Objectives Register | ../../plans/ISMS-Objectives-Register.md |

### Templates & Forms (T##)

| ID | Title | Path |
|----|-------|------|
| T01 | Policy Template | ../../templates/_TEMPLATE-Policy.md |
| T02 | Procedure Template | ../../templates/_TEMPLATE-Procedure.md |
| T03 | Change Request Form | ../../templates/Change-Request-Form.md |
| T04 | Access Request Form | ../../templates/Access-Request-Form.md |
| T05 | Incident Report Form | ../../templates/Incident-Report-Form.md |
| T06 | Vendor Due Diligence Questionnaire | ../../templates/Vendor-Due-Diligence-Questionnaire.md |
| T07 | Franchise Site Onboarding Checklist | ../../templates/Franchise-Site-Onboarding-Checklist.md |
| T08 | Management Review Pack Template | ../../templates/Management-Review-Pack-Template.md |
| T09 | BC/DR Exercise Plan & Report Templates | ../../templates/BC-DR-Exercise-Templates.md |
| T10 | Customer CUEC Disclosure Template | ../../templates/Customer-CUEC-Disclosure-Template.md |

## Revision History

| Version | Date       | Author | Description |
|---------|------------|--------|-------------|
| 1.0.0   | 2025-11-05 |        | Seeded catalog entries for initial mapping. |


