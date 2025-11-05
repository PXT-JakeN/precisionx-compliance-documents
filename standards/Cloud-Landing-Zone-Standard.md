---
title: "Cloud Landing Zone Standard"
doc_type: "Standard"
id: "GRS-ISMS-STD-022"
version: "1.0.0"
status: "Draft"
owner: "Security Engineering Lead"
approver: "Executive Management, GridSite Technology LLC"
approval_date: ""
effective_date: ""
next_review_date: ""
related_documents:
  - ../policies/Information-Security-Policy.md
  - ../standards/Network-Segmentation-Standard.md
  - ../standards/Logging-and-Time-Sync-Standard.md
  - ../policies/Backup-and-Restore-Policy.md
references:
  - CIS Benchmarks (cloud)
  - AICPA SOC 2 (CC6, CC7, CC8)
---

## Document Control

| Field | Value |
|-------|-------|
| Title | Cloud Landing Zone Standard |
| Document ID | GRS-ISMS-STD-022 |
| Version | 1.0.0 |
| Status | Draft |
| Owner | Security Engineering Lead |
| Approver | Executive Management, GridSite Technology LLC |
| Approval Date |  |
| Effective Date |  |
| Next Review Date |  |

## 1. Purpose

Define baseline guardrails for identity, networking, logging, encryption, secrets, backups, and automation in
GridSite cloud environments.

## 2. Scope

Cloud accounts/projects used for GridSite services. Current approved VM providers are Linode and
DigitalOcean; principles apply generically across providers.

## 3. Control Requirements

| Req ID | Requirement | Implementation | Evidence |
|--------|-------------|----------------|----------|
| CLZ-01 | Identity & SSO | Enforce Microsoft 365 SSO/MFA for control planes; restrict local users | IdP configs; panel exports |
| CLZ-02 | Account structure | Separate prod/non‑prod; limit blast radius; tag ownership/cost | Account trees; tags |
| CLZ-03 | Networking | Segment mgmt/control/data; default‑deny security groups; restrict admin ingress to NOC | SG/NACL configs |
| CLZ-04 | Logging & time | Centralize logs where supported; time sync; manual reviews for gaps | Log settings; reviews |
| CLZ-05 | Encryption | Encrypt at rest and in transit; manage keys; rotate certs | KMS settings; cert inventory |
| CLZ-06 | Secrets | Use vault; no plaintext in code or images; rotate | Vault policies; scans |
| CLZ-07 | Backups | Configure backups/snapshots with immutability where available; test restores | Backup dashboards |
| CLZ-08 | Hardening | Baseline images; CIS where applicable; IaC for repeatability | Templates; pipelines |
| CLZ-09 | Change control | Apply PR07 and P19 for infra changes; maintain evidence | Change records |

## 4. Roles and Responsibilities

Security Engineering defines guardrails and validates compliance; Platform/IT implements and maintains
configs; SecOps monitors logs and detections.

## 5. Revision History

| Version | Date       | Author | Description |
|---------|------------|--------|-------------|
| 1.0.0   | 2025-11-05 |        | Initial cloud landing zone standard. |


