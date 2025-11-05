---
title: "Logging, Monitoring & SIEM Policy"
doc_type: "Policy"
id: "GRS-ISMS-POL-021"
version: "1.1.0"
status: "Draft"
owner: "Security Operations Lead"
program_manager: "Josh Mayorga, Compliance Manager"
approver: "Executive Management, GridSite Technology LLC"
approval_date: ""
effective_date: ""
next_review_date: ""
classification: "Internal – Controlled"
organization: "GridSite Technology LLC and its operating subsidiaries"
related_documents:
  - ./Information-Security-Policy.md
  - ./Incident-Response-Policy.md
  - ./Access-Control-Policy.md
  - ./Identity-and-Access-Management-Policy.md
  - ../procedures/Logging-and-SIEM-Onboarding-Procedure.md
  - ../procedures/IR-Runbook-General.md
  - ../standards/Logging-and-Time-Sync-Standard.md
  - ../plans/Incident-Log.md
references:
  - ISO/IEC 27001:2022 Annex A (Monitoring, Logging)
  - ISO/IEC 27002:2022 (8.15, 8.16 Logging/Monitoring)
  - AICPA SOC 2 TSC (CC7 Monitoring)
iso_clauses: ["8"]
soc2_criteria: ["CC7"]
bcms_clauses: []
---

## Document Control

| Field | Value |
|-------|-------|
| Title | Logging, Monitoring & SIEM Policy |
| Document ID | GRS-ISMS-POL-021 |
| Version | 1.0.1 |
| Status | Draft |
| Owner | Security Operations Lead |
| Program Manager | Josh Mayorga, Compliance Manager |
| Approver | Executive Management, GridSite Technology LLC |
| Approval Date |  |
| Effective Date |  |
| Next Review Date |  |
| Classification | Internal – Controlled |
| Organization | GridSite Technology LLC and its operating subsidiaries |

## 1. Purpose

Define mandatory requirements for centralized logging, monitoring, alerting, and event retention to detect,
investigate, and respond to security incidents and performance anomalies across GridSite’s environments.

## 2. Scope

Applies to all production and corporate systems, including cloud infrastructure, platforms, applications,
endpoints, network devices, identity providers, CI/CD, and facility systems where applicable (e.g., DCIM).

## 3. Roles and Responsibilities

| Role | Responsibilities |
|------|------------------|
| Security Operations Lead | Owns SIEM, detections, triage, and response integration. |
| Security Engineering Lead | Ensures log sources and time sync are architected and standardized. |
| IT Operations Lead | Ensures system/endpoint logging, retention, and forwarding are configured. |
| System/Service Owners | Onboard sources; ensure application logs meet requirements; remediate gaps. |
| Compliance Manager | Verifies evidence retention; aligns monitoring with audit and regulatory needs. |

## 4. Policy Statements

### 4.1 Time Synchronization

All systems synchronize time with approved NTP sources. Critical systems must alert on material drift to
preserve event sequencing and investigative integrity.

### 4.2 Log Sources and Content

Mandatory sources include identity/authentication, access control decisions, administrative actions, network
security devices, servers, endpoints, container/orchestrators, key/secret management, cloud audit services,
and critical applications. Events include user/service identifiers, timestamps, source/destination, action,
result, and failure details.

### 4.3 Centralization and Integrity

Security‑relevant events are forwarded to the centralized SIEM or logging platform when integrations are
available. For high‑value sources, immutability or equivalent protection is used to deter tampering.

### 4.4 Retention and Privacy

Retention meets business, legal, and contractual requirements; security audit logs are retained for at least one
year unless stricter obligations apply. Logs containing personal data are minimized and protected consistent
with privacy requirements.

### 4.5 Detection Engineering and Alerting

Detection content addresses priority use cases such as MFA failures, privilege elevation, suspicious
administrative changes, malware/EDR alerts, WAF events, and exfiltration patterns. Severity, routing, and
playbooks are defined with on‑call schedules, acknowledgment SLAs, and escalation paths.

### 4.6 Monitoring of Third Parties and Subservices

Where feasible, subservice logs and alerts are integrated. If a system or provider cannot forward events,
documented manual reviews occur on a defined cadence with screenshots/exports retained as evidence;
reports and feeds are obtained commensurate with risk, and CUECs are documented for customer obligations.

### 4.7 Evidence and Reporting

Incident evidence (queries, dashboards, exports) is preserved with case records. Monthly metrics on MTTD,
alert volumes, false positive rates, and coverage are reported into Management Review and used to tune
controls.

### 4.8 Exceptions

- Exceptions require a documented risk assessment, compensating controls, and approval by the Security
  Operations Lead (and Executive Management for High residual risk).

## 5. Compliance Measurement

Compliance shall be measured via source onboarding coverage, alert SLA adherence, retention verification,
and audit sampling of critical detections.

## 6. Enforcement

Non-compliance may result in disciplinary action up to and including termination of employment or contract.

## 7. Revision History

| Version | Date       | Author | Description |
|---------|------------|--------|-------------|
| 1.1.0   | 2025-11-05 |        | Added manual monitoring fallback and expanded narrative sections. |
| 1.0.1   | 2025-11-05 |        | Added Document Control section; standardized header format. |
| 1.0.0   | 2025-11-05 |        | Initial comprehensive Logging, Monitoring & SIEM policy. |


