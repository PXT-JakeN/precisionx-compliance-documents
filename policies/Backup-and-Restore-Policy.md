---
title: "Backup & Restore Policy"
doc_type: "Policy"
id: "GRS-ISMS-POL-025"
version: "1.2.0"
status: "Draft"
owner: "BC/DR Lead"
program_manager: "Josh Mayorga, Compliance Manager"
approver: "Executive Management, GridSite Technology LLC"
approval_date: ""
effective_date: ""
next_review_date: ""
classification: "Internal – Controlled"
organization: "GridSite Technology LLC and its operating subsidiaries"
related_documents:
  - ./Business-Continuity-Policy.md
  - ../procedures/Backup-and-Restore-Procedure.md
  - ../standards/Server-Baseline.md
  - ../standards/Workstation-Baseline.md
  - ../plans/Backup-and-Restore-Test-Logs.md
references:
  - ISO/IEC 27001:2022 Annex A (Information Security Continuity)
  - ISO/IEC 27002:2022 8.13 Information backup
  - ISO 22301:2019 Continuity requirements
iso_clauses: ["8"]
soc2_criteria: ["A","CC7"]
bcms_clauses: ["ISO 22301"]
---

## Document Control

| Field | Value |
|-------|-------|
| Title | Backup & Restore Policy |
| Document ID | GRS-ISMS-POL-025 |
| Version | 1.0.0 |
| Status | Draft |
| Owner | BC/DR Lead |
| Program Manager | Josh Mayorga, Compliance Manager |
| Approver | Executive Management, GridSite Technology LLC |
| Approval Date |  |
| Effective Date |  |
| Next Review Date |  |
| Classification | Internal – Controlled |
| Organization | GridSite Technology LLC and its operating subsidiaries |

## 1. Purpose

Define mandatory requirements for reliable, secure backups and validated restores to meet recovery objectives
and contractual/regulatory obligations.

## 2. Scope

Applies to all critical systems, applications, databases, and data sets within ISMS/BCMS scope across cloud,
on-premises, and facility contexts.

## 3. Roles and Responsibilities

| Role | Responsibilities |
|------|------------------|
| BC/DR Lead | Owns backup strategy, restore testing, and reporting. |
| IT Operations Lead | Implements schedules, monitoring, and remediation of failures. |
| System/Service Owners | Define RTO/RPO; identify data sets; validate restores. |
| Security Engineering Lead | Enforces encryption, key management, and access controls for backup stores. |

## 4. Policy Statements

### 4.1 Strategy and Objectives

Recovery targets (RTO/RPO) are defined per service. Redundancy follows a “3‑2‑1” style approach—multiple
copies on different media with at least one logically isolated or immutable—proportional to risk.

### 4.2 Scope, Frequency, and Retention

Backups include operating system configurations, application data, and databases. Frequency and retention
align to business and regulatory requirements and are documented per data classification.

### 4.3 Security Controls

Backups are encrypted in transit and at rest. Where supported, immutability and MFA for administrative
actions are enabled. Access is restricted to named roles with least privilege and logged.

### 4.4 Monitoring and Failure Handling

Backup jobs are continuously monitored. Failures create incidents, and repeated failures trigger problem
management and corrective actions.

### 4.5 Restore Validation

Periodic restore tests—at least quarterly for critical systems—verify data integrity and recovery time. Results
are recorded in test logs and exceptions are reported for remediation.

### 4.6 Records
### 4.7 Endpoint Backup Platform

Company‑owned workstations are backed up using iDrive360 with centrally managed policies. Coverage and
job status are monitored; failures are remediated promptly and exceptions require approval with documented
compensating controls.

- Maintain inventories of protected systems/data, schedules, retention policies, success/failure metrics, and test
  evidence. Keep admin activity logs for backup platforms.

## 5. Exceptions

Exceptions require documented risk assessment, approval by BC/DR Lead (and Executive Management for High
residual risk), and compensating controls with expiry.

## 6. Compliance Measurement

Measured via backup success rates, restore test success and time, and audit sampling of encryption/immutability.

## 7. Enforcement

Non-compliance may result in disciplinary action up to and including termination of employment or contract.

## 8. Revision History

| Version | Date       | Author | Description |
|---------|------------|--------|-------------|
| 1.2.0   | 2025-11-05 |        | Mandated iDrive360 for endpoint backups. |
| 1.1.0   | 2025-11-05 |        | Expanded narrative sections and clarified security/monitoring expectations. |
| 1.0.0   | 2025-11-05 |        | Initial comprehensive Backup & Restore policy. |


