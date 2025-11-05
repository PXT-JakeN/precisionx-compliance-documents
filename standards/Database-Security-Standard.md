---
title: "Database Security Standard"
doc_type: "Standard"
id: "GRS-ISMS-STD-021"
version: "1.0.0"
status: "Draft"
owner: "Security Engineering Lead"
approver: "Executive Management, GridSite Technology LLC"
approval_date: ""
effective_date: ""
next_review_date: ""
related_documents:
  - ../standards/Server-Baseline.md
  - ../standards/Secrets-Management-Standard.md
  - ../policies/Logging-Monitoring-and-SIEM-Policy.md
  - ../policies/Data-Classification-and-Handling-Policy.md
references:
  - CIS Benchmarks (MySQL/Postgres/SQL Server)
  - OWASP ASVS (data protection)
---

## Document Control

| Field | Value |
|-------|-------|
| Title | Database Security Standard |
| Document ID | GRS-ISMS-STD-021 |
| Version | 1.0.0 |
| Status | Draft |
| Owner | Security Engineering Lead |
| Approver | Executive Management, GridSite Technology LLC |
| Approval Date |  |
| Effective Date |  |
| Next Review Date |  |

## 1. Purpose

Define mandatory controls for securing databases, covering identity, network access, configuration, encryption,
backup, logging, and evidencing.

## 2. Scope

All production and corporate databases and managed database services.

## 3. Control Requirements

| Req ID | Requirement | Implementation | Evidence |
|--------|-------------|----------------|----------|
| DB-01 | Identity | Use named accounts; no shared admin users; least privilege roles | Role maps; user lists |
| DB-02 | Network access | Restrict to app subnets/bastions; admin from secure NOC only | SG/ACLs; firewall rules |
| DB-03 | Encryption | Encrypt at rest and in transit (TLS 1.2+); manage certs/keys | KMS settings; cert inventory |
| DB-04 | Configuration | Apply CIS‑aligned hardening; disable unused features; strong auth params | Config dumps |
| DB-05 | Secrets | Use vault‑delivered credentials; rotate regularly; no plaintext | Vault policies; rotation logs |
| DB-06 | Logging/Audit | Enable audit logs for auth and schema changes; centralize or manual reviews | Audit logs; review records |
| DB-07 | Backup/Restore | Backups with immutability where available; periodic restore tests | Backup dashboards; test logs |
| DB-08 | Data classification | Align storage and access with classification policy; mask where feasible | Label docs; masking configs |
| DB-09 | Change control | Schema changes via PR07 with rollback and evidence | Change tickets |

## 4. Roles and Responsibilities

Security Engineering defines standards and validates compliance; DBAs/System Owners implement configs and
backups; SecOps monitors logging and alerts.

## 5. Revision History

| Version | Date       | Author | Description |
|---------|------------|--------|-------------|
| 1.0.0   | 2025-11-05 |        | Initial database security standard. |


