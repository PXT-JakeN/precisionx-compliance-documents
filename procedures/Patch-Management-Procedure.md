---
title: "Patch Management Procedure"
doc_type: "Procedure"
id: "GRS-ISMS-PRC-012"
version: "1.0.0"
status: "Draft"
owner: "IT Operations Lead"
program_manager: "Josh Mayorga, Compliance Manager"
approver: "Executive Management, GridSite Technology LLC"
approval_date: ""
effective_date: ""
next_review_date: ""
classification: "Internal – Controlled"
organization: "GridSite Technology LLC and its operating subsidiaries"
related_documents:
  - ../policies/Vulnerability-and-Patch-Management-Policy.md
  - ../standards/Vulnerability-Severity-and-SLA-Standard.md
  - ../standards/Server-Baseline.md
  - ../standards/Workstation-Baseline.md
  - ../standards/Cloud-Landing-Zone-Standard.md
---

## Document Control

| Field | Value |
|-------|-------|
| Title | Patch Management Procedure |
| Document ID | GRS-ISMS-PRC-012 |
| Version | 1.0.0 |
| Status | Draft |
| Owner | IT Operations Lead |
| Program Manager | Josh Mayorga, Compliance Manager |
| Approver | Executive Management, GridSite Technology LLC |
| Approval Date |  |
| Effective Date |  |
| Next Review Date |  |

## 1. Purpose

Define the process to acquire, test, deploy, and verify patches for operating systems, applications, firmware,
and cloud services.

## 2. Roles

IT Operations (owner), Security Operations, System Owners, SRE, ISMS.

## 3. Prerequisites

Asset inventory; vulnerability inputs; maintenance windows; rollback plans; bastions/NOC ingress; Duo for RDP/SSH.

## 4. Procedure

1. Intake & Prioritization: Aggregate vulnerability inputs; map to assets; prioritize per severity SLA.
2. Testing: Apply patches in staging; run smoke and regression tests; validate rollback path.
3. Scheduling: Align to maintenance windows; communicate impact; obtain approvals via change control.
4. Deployment: Use automation where possible; restrict admin ingress to NOC networks; monitor during rollout.
5. Verification: Reboot/validate services; re‑scan for vulnerability closure; collect evidence and logs.
6. Exceptions: Document deferrals with risk acceptance and compensating controls.

## 5. Records & Evidence

Patch catalogs, approvals, deployment logs, test results, re‑scan confirmations.

## 6. Metrics

Patch latency by severity, success rate, rollback rate, and backlog trend.

## 7. Revision History

| Version | Date       | Author | Description |
|---------|------------|--------|-------------|
| 1.0.0   | 2025-11-05 |        | Initial patch management procedure. |


