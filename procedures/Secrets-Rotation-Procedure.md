---
title: "Secrets Rotation Procedure"
doc_type: "Procedure"
id: "GRS-ISMS-PRC-025"
version: "1.0.0"
status: "Draft"
owner: "Security Engineering Lead"
program_manager: "Josh Mayorga, Compliance Manager"
approver: "Executive Management, GridSite Technology LLC"
approval_date: ""
effective_date: ""
next_review_date: ""
classification: "Internal – Controlled"
organization: "GridSite Technology LLC and its operating subsidiaries"
related_documents:
  - ../standards/Secrets-Management-Standard.md
  - ../policies/Secrets-Management-Policy.md
  - ../standards/Vulnerability-Severity-and-SLA-Standard.md
---

## Document Control

| Field | Value |
|-------|-------|
| Title | Secrets Rotation Procedure |
| Document ID | GRS-ISMS-PRC-025 |
| Version | 1.0.0 |
| Status | Draft |
| Owner | Security Engineering Lead |
| Program Manager | Josh Mayorga, Compliance Manager |
| Approver | Executive Management, GridSite Technology LLC |
| Approval Date |  |
| Effective Date |  |
| Next Review Date |  |

## 1. Purpose

Define the steps to rotate credentials, keys, and tokens safely, minimizing downtime and reducing exposure.

## 2. Roles

Security Engineering (owner), System Owners, DevOps/SRE, ISMS.

## 3. Prerequisites

Central vault configured with role-based access; application support for key rollover; break-glass process; change
ticket and maintenance window where required.

## 4. Procedure

1. Plan: Identify secret type, consumers, rotation method (dual key, phased deploy), and rollback.
2. Generate: Create strong secret in vault; restrict visibility; record audit entry.
3. Distribute: Update apps via configuration or orchestration; avoid storing in code/images; reload without restart
   where possible.
4. Cutover: Activate new secret; deactivate old after verification; monitor errors and access patterns.
5. Validate: Confirm application health; check logs; re‑enable normal monitoring thresholds.
6. Record: Capture vault logs, change records, and evidence; export logs manually when forwarding is not possible.

## 5. Cadence

Default: API keys/tokens 90 days, passwords 90 days, TLS certs per CA lifetime with 60‑day renewal window, and
immediate rotation upon compromise or role change.

## 6. Records & Evidence

Vault audit logs, deployment logs, change tickets, error dashboards, validation checks.

## 7. Metrics

On‑time rotations, failed rotations, incidents due to stale secrets.

## 8. Revision History

| Version | Date       | Author | Description |
|---------|------------|--------|-------------|
| 1.0.0   | 2025-11-05 |        | Initial secrets rotation procedure. |


