---
title: "IR Runbook – Ransomware"
doc_type: "Procedure"
id: "GRS-ISMS-PRC-015"
version: "1.0.0"
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
  - ../policies/Incident-Response-Policy.md
  - ../standards/Backup-and-Immutability-Standard.md
  - ../policies/Disaster-Recovery-Policy.md
  - ../procedures/DR-Invocation-and-Recovery-Procedure.md
---

## Document Control

| Field | Value |
|-------|-------|
| Title | IR Runbook – Ransomware |
| Document ID | GRS-ISMS-PRC-015 |
| Version | 1.0.0 |
| Status | Draft |
| Owner | Security Operations Lead |
| Program Manager | Josh Mayorga, Compliance Manager |
| Approver | Executive Management, GridSite Technology LLC |
| Approval Date |  |
| Effective Date |  |
| Next Review Date |  |

## 1. Purpose

Provide time‑boxed steps to contain ransomware, preserve evidence, and restore from immutable backups.

## 2. Actions

1. Detect & Declare: Confirm indicators; isolate impacted hosts/networks; block lateral movement.
2. Contain: Disable affected identities; block external access; snapshot before shutdown where feasible.
3. Eradicate: Wipe/rebuild from golden images; patch initial vector; rotate credentials.
4. Recover: Restore from immutable backups; validate integrity; bring up in stages with monitoring.
5. Notify: Follow Incident Communications & PR Policy for required notifications; consult Legal for breach triggers.
6. PIR/CAPA: Document lessons, close gaps, and test restores more frequently.

## 3. Records

Incident ticket, forensic images, backup/restore logs, communications, PIR/CAPA.

## 4. Revision History

| Version | Date       | Author | Description |
|---------|------------|--------|-------------|
| 1.0.0   | 2025-11-05 |        | Initial ransomware runbook. |


