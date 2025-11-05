---
title: "IR Runbook – Credential Leak (Cloud)"
doc_type: "Procedure"
id: "GRS-ISMS-PRC-014"
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
  - ../standards/Secrets-Management-Standard.md
  - ../standards/Identity-and-PAM-Standard.md
  - ../policies/Authentication-and-MFA-Policy.md
---

## Document Control

| Field | Value |
|-------|-------|
| Title | IR Runbook – Credential Leak (Cloud) |
| Document ID | GRS-ISMS-PRC-014 |
| Version | 1.0.0 |
| Status | Draft |
| Owner | Security Operations Lead |
| Program Manager | Josh Mayorga, Compliance Manager |
| Approver | Executive Management, GridSite Technology LLC |
| Approval Date |  |
| Effective Date |  |
| Next Review Date |  |

## 1. Purpose

Guide containment and eradication when access keys, tokens, or passwords are exposed in code repos, CI logs,
or third‑party breaches.

## 2. Severity & Triggers

Treat as High/Critical if production or privileged scopes are implicated; trigger from SCA/secret scanners, SIEM,
or external notifications.

## 3. Actions

1. Identify Scope: Determine accounts, roles, environments, and last‑use time from logs.
2. Contain: Revoke tokens/keys; force password resets; disable affected identities; block from NOC‑restricted
   ingress; enforce step‑up MFA.
3. Eradicate: Rotate secrets centrally via vault; invalidate caches; remove exposed artifacts from repos/logs.
4. Hunt & Monitor: Search for misuse indicators; elevate logging; if forwarding not possible, export logs manually
   for review; monitor for new auth anomalies.
5. Recover: Validate access paths; re‑enable least‑privilege; add detections; require PIR with CAPA.

## 4. Records

Tickets, rotation evidence, identity logs, detections, PIR and CAPA items.

## 5. Revision History

| Version | Date       | Author | Description |
|---------|------------|--------|-------------|
| 1.0.0   | 2025-11-05 |        | Initial credential leak runbook. |


