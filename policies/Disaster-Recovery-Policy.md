---
title: "Disaster Recovery Policy"
doc_type: "Policy"
id: "GRS-ISMS-POL-024"
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
  - ../procedures/DR-Invocation-and-Recovery-Procedure.md
  - ../standards/Backup-and-Immutability-Standard.md
references:
  - ISO 22301:2019
---

## Document Control

| Field | Value |
|-------|-------|
| Title | Disaster Recovery Policy |
| Document ID | GRS-ISMS-POL-024 |
| Version | 1.0.0 |
| Status | Draft |
| Owner | BC/DR Lead |
| Program Manager | Josh Mayorga, Compliance Manager |
| Approver | Executive Management, GridSite Technology LLC |
| Approval Date |  |
| Effective Date |  |
| Next Review Date |  |

## 1. Purpose

Define objectives, governance, and testing for recovering services following disruptive incidents.

## 2. Scope

Critical services, platforms, and shared infrastructure supporting GridSite and PrecisionX operations.

## 3. Policy Statements

Recovery objectives (RTO/RPO) are defined per service via BIAs. DR strategies use multi‑region cloud
architectures, backups with immutability where available, and secondary NOC capabilities. The DR Invocation
and Recovery Procedure governs failover execution. Exercises (tabletop and technical) are conducted on a
schedule with results captured and corrective actions tracked. Evidence of successful restores and failovers is
retained for audit.

## 4. Exceptions

Exceptions require risk assessment, approvals, and compensating controls; deviations are documented with
remediation timelines.

## 5. Compliance Measurement

Measured via exercise completion, restore timing, and achievement of RTO/RPO targets.

## 6. Revision History

| Version | Date       | Author | Description |
|---------|------------|--------|-------------|
| 1.0.0   | 2025-11-05 |        | Initial disaster recovery policy. |


