---
title: "Cloud Security Policy"
doc_type: "Policy"
id: "GRS-ISMS-POL-015"
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
  - ../standards/Cloud-Landing-Zone-Standard.md
  - ../standards/Secrets-Management-Standard.md
  - ../standards/Logging-and-Time-Sync-Standard.md
  - ../policies/Backup-and-Restore-Policy.md
references:
  - CIS Benchmarks (cloud)
---

## Document Control

| Field | Value |
|-------|-------|
| Title | Cloud Security Policy |
| Document ID | GRS-ISMS-POL-015 |
| Version | 1.0.0 |
| Status | Draft |
| Owner | Security Engineering Lead |
| Program Manager | Josh Mayorga, Compliance Manager |
| Approver | Executive Management, GridSite Technology LLC |
| Approval Date |  |
| Effective Date |  |
| Next Review Date |  |

## 1. Purpose

Set policy for secure design and operation of public cloud environments, reflecting GridSite’s cloud‑first
posture and provider guardrails.

## 2. Scope

All cloud accounts/projects used for GridSite services (VMs currently on Linode and DigitalOcean) and any
future approved providers.

## 3. Policy Statements

Cloud control planes must integrate Microsoft 365 SSO/MFA. Accounts are structured to separate production
and non‑production and to minimize blast radius. Networks are segmented with default‑deny and NOC‑restricted
admin ingress for on‑prem integrations. Logging and time synchronization are enabled centrally where
available; manual reviews are performed when integrations are not possible. Data is encrypted at rest and in
transit; secrets are stored in vaults; backups leverage immutability where available and are tested.
Infrastructure is provisioned using IaC with change control and evidence. Provider account governance and
access follow corporate IAM and exception workflows.

## 4. Exceptions

Exceptions require risk assessment, approvals, and compensating controls with expiry.

## 5. Compliance Measurement

Measured via account baselines, IaC reviews, and audit of logs/backups and identity configurations.

## 6. Revision History

| Version | Date       | Author | Description |
|---------|------------|--------|-------------|
| 1.0.0   | 2025-11-05 |        | Initial cloud security policy. |


