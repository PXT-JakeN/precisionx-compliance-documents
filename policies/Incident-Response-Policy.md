---
title: "Incident Response Policy"
doc_type: "Policy"
id: "GRS-ISMS-POL-022"
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
  - ./Business-Continuity-Policy.md
  - ./ISMS-Scope-and-Context-Policy.md
  - ./Logging-Monitoring-and-SIEM-Policy.md
  - ../procedures/IR-Runbook-General.md
  - ../plans/Incident-Playbooks.md
  - ../plans/Crisis-Communications-Plan.md
  - ../plans/Incident-Log.md
references:
  - ISO/IEC 27001:2022 Annex A (Incident management)
  - ISO/IEC 27035 (Information security incident management)
  - AICPA SOC 2 TSC (CC7, A)
iso_clauses: ["8"]
soc2_criteria: ["CC7","A"]
bcms_clauses: ["ISO 22301 Operation/Response"]
---

## Document Control

| Field | Value |
|-------|-------|
| Title | Incident Response Policy |
| Document ID | GRS-ISMS-POL-022 |
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

Establish principles and requirements for timely detection, triage, containment, eradication, recovery, and
post-incident learning across GridSite, integrating legal/contractual obligations and communication.

## 2. Scope

Applies to all security events and incidents affecting in-scope systems, data, and services across corporate,
SaaS, GridColo, and franchise contexts, including suppliers and subservices where impacts occur.

## 3. Roles and Responsibilities

| Role | Responsibilities |
|------|------------------|
| Security Operations Lead | Owns IR program; declares incidents; coordinates response and reporting. |
| Incident Commander (on-call) | Leads tactical response, decisions, and documentation. |
| Forensics Lead | Oversees evidence handling and forensic activities; preserves chain of custody. |
| Communications Lead | Manages internal/external communications per Crisis Comms Plan. |
| Legal/Privacy | Advises on regulatory/contractual notification and evidence preservation. |
| System/Service Owners | Provide technical support, changes, and validation during recovery. |
| Compliance Manager | Ensures records, PIRs, and CAPA tracking are complete. |

## 4. Policy Statements

### 4.1 Classification and Severity

Events are triaged and, when criteria are met, classified as incidents with severity (e.g., SEV1–SEV4) based on
impact to confidentiality, integrity, availability, safety, or compliance.

### 4.2 Lifecycle and Playbooks

The lifecycle follows Preparation → Detection → Triage → Containment → Eradication → Recovery → Post‑Incident
Review. Playbooks cover common scenarios (credential theft, ransomware, data breach, DDoS) with clear entry
and exit criteria and role assignments.

### 4.3 Evidence and Forensics

Evidence is collected and preserved with chain‑of‑custody, including images and logs. Actions are documented
as they occur. Forensic analysis is performed or overseen by qualified personnel.

### 4.4 Notifications and Communications

Notifications to customers, regulators, law enforcement, and partners comply with legal and contractual
timelines and follow the Crisis Communications Plan. Holding statements and approvals are prepared for any
public communications.

### 4.5 Integration with Monitoring and BCMS

SIEM detections and on‑call processes integrate with incident declaration and paging. If a system cannot
forward logs, responders retrieve evidence manually on a defined cadence and preserve screenshots or
exports with the case file. IR aligns with BCMS strategies for recovery and DR runbooks when service impact
exists.

### 4.6 Post-Incident Review and Improvement

A PIR is conducted for SEV1–SEV2 incidents (and material SEV3) within 10 business days to document root
cause, contributing factors, and corrective/preventive actions with owners and due dates.

### 4.7 Records and Retention

Incident tickets, timelines, evidence manifests, communications, and PIRs are retained per the Records
Management Policy and made available for audits.

### 4.8 Exceptions

- Exceptions require documented risk assessment, approval by the Security Operations Lead (and Executive
  Management for High residual risk), and compensating controls.

## 5. Compliance Measurement

Compliance shall be measured via MTTD/MTTR, SLA adherence for notifications, PIR completion rates, and
closure of CAPA items.

## 6. Enforcement

Non-compliance may result in disciplinary action up to and including termination of employment or contract.

## 7. Revision History

| Version | Date       | Author | Description |
|---------|------------|--------|-------------|
| 1.1.0   | 2025-11-05 |        | Added manual-evidence fallback for non-forwarding systems and expanded narrative sections. |
| 1.0.1   | 2025-11-05 |        | Added Document Control section; standardized header format. |
| 1.0.0   | 2025-11-05 |        | Initial comprehensive Incident Response policy. |


