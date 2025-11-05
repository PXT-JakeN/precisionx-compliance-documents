---
title: "Backup & Restore Policy"
doc_type: "Policy"
id: "GRS-ISMS-POL-025"
version: "1.0.0"
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

- Define RTO/RPO per service; maintain 3-2-1 style redundancy (multiple copies, media, and offsite/immutable
  storage) commensurate with risk.

### 4.2 Scope, Frequency, and Retention

- Backups shall include operating system configs, application data, and databases; frequency and retention shall
  align to business and regulatory requirements with documented schedules and data classification.

### 4.3 Security Controls

- Backups must be encrypted in transit and at rest; where supported, use immutability and MFA for administrative
  actions; access is restricted to named roles with least privilege.

### 4.4 Monitoring and Failure Handling

- Backup jobs shall be monitored; failures are opened as incidents; repeated failures require problem management
  and CAPA.

### 4.5 Restore Validation

- Perform periodic restore tests (at least quarterly for critical systems) to verify integrity and recovery time; record
  results in test logs and report exceptions.

### 4.6 Records

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
| 1.0.0   | 2025-11-05 |        | Initial comprehensive Backup & Restore policy. |


