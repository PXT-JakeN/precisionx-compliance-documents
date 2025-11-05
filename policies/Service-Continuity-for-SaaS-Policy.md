---
title: "Service Continuity for SaaS Policy"
doc_type: "Policy"
id: "GRS-ISMS-POL-043"
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
  - ./Disaster-Recovery-Policy.md
  - ../plans/Disaster-Recovery-Plans.md
  - ../plans/BCMS-Strategy-Plan.md
  - ../procedures/DR-Invocation-and-Recovery-Procedure.md
  - ../standards/Cloud-Landing-Zone-Standard.md
  - ../standards/Backup-and-Immutability-Standard.md
references:
  - ISO/IEC 27001:2022 A.5 and A.8; ISO 22301:2019 continuity requirements; SOC 2 A1
---

## Document Control

| Field | Value |
|-------|-------|
| Title | Service Continuity for SaaS Policy |
| Document ID | GRS-ISMS-POL-043 |
| Version | 1.0.0 |
| Status | Draft |
| Owner | BC/DR Lead |
| Program Manager | Josh Mayorga, Compliance Manager |
| Approver | Executive Management, GridSite Technology LLC |
| Approval Date |  |
| Effective Date |  |
| Next Review Date |  |

## 1. Purpose

Define continuity and recovery requirements for GridSite SaaS platforms to meet customer and regulatory
commitments.

## 2. Scope

All production SaaS services and shared supporting platforms operated by GridSite.

## 3. Policy Statements

Each SaaS platform shall define RTO and RPO targets based on customer obligations and conduct BIAs to
identify critical functions. Architectures will be cloud‑first with regional redundancy where feasible; backups are
encrypted, tested, and include immutable tiers for critical data. Administrative access is restricted to NOC
networks with MFA; configuration and secrets are recoverable. DR plans exist per system with at least annual
testing; significant changes require retest. Dependencies on subservice organizations are documented and
monitored; continuity risks are tracked. Communications during incidents follow the Crisis Communications Plan.
Continuity telemetry and test evidence are retained; where systems cannot forward, periodic manual export and
review are performed.

## 4. Exceptions

Exceptions require BC/DR Lead and ISMS approval with risk treatment and planned remediation.

## 5. Compliance Measurement

Measured via DR test results, backup/restore logs, BIA records, and SLA reports.

## 6. Revision History

| Version | Date       | Author | Description |
|---------|------------|--------|-------------|
| 1.0.0   | 2025-11-05 |        | Initial SaaS continuity policy. |


