---
title: "Server Baseline (Linux/Windows)"
doc_type: "Standard"
id: "GRS-ISMS-STD-002"
version: "1.1.0"
status: "Draft"
owner: "Security Engineering Lead"
approver: "Executive Management, GridSite Technology LLC"
approval_date: ""
effective_date: ""
next_review_date: ""
related_documents:
  - ../policies/Information-Security-Policy.md
  - ../policies/Change-and-Release-Management-Policy.md
  - ../policies/Logging-Monitoring-and-SIEM-Policy.md
  - ../policies/Backup-and-Restore-Policy.md
  - ../procedures/Change-Control-Procedure.md
references:
  - CIS Benchmarks (Ubuntu LTS, Windows Server)
  - AICPA SOC 2 (CC6, CC7, CC8)
---

## Document Control

| Field | Value |
|-------|-------|
| Title | Server Baseline (Linux/Windows) |
| Document ID | GRS-ISMS-STD-002 |
| Version | 1.0.0 |
| Status | Draft |
| Owner | Security Engineering Lead |
| Approver | Executive Management, GridSite Technology LLC |
| Approval Date |  |
| Effective Date |  |
| Next Review Date |  |

## 1. Purpose

Define mandatory hardening, patching, identity, logging, and backup requirements for servers supporting
GridSite services. The organization is cloud‑first; physical servers and devices at offices/sites are minimized to only what is strictly required for operations.

## 2. Scope

All servers hosting corporate or production services. Cloud virtual machines are Ubuntu LTS or Windows
Server images provided by approved providers (currently Linode and DigitalOcean). Accounts and access are
managed per corporate IAM and change policies. On‑premises servers exist only by exception with documented
business need.

## 3. Baseline Requirements

Servers are provisioned from trusted images, remove unnecessary packages, and expose only required
services. Administrative access uses named accounts with MFA enforced at the control plane and via
approved bastions or jump hosts where applicable. SSH uses keys with strong algorithms and, where feasible,
short‑lived certificates; RDP is restricted and monitored. From a network perspective, SSH and RDP services
on locally hosted servers at offices/sites are reachable only from secure NOC networks and never directly
from the internet or general corporate subnets. Windows servers join Microsoft Entra ID (Azure AD) for
authentication; Linux servers use non‑privileged accounts and sudo for administrative elevation. Duo Security
is used to provide MFA for SSH and RDP sessions.

Operating systems apply security updates on a defined cadence with critical patches expedited. EDR/AV and
integrity monitoring are enabled. Secrets and keys are stored in approved vaults; plaintext secrets are
prohibited. Backups are configured per policy with periodic restore tests. Network segmentation restricts
east‑west traffic; internet‑facing services are protected by WAFs or equivalent controls. Logging is
centralized when integrations exist; where not possible, manual reviews on a defined cadence are documented
with retained evidence.

## 4. Control Requirements

| Req ID | Requirement | Implementation | Evidence |
|--------|-------------|----------------|----------|
| SVR-01 | Cloud‑first | Use Ubuntu LTS or Windows Server VMs from approved providers (Linode, DigitalOcean) | Provider account inventory |
| SVR-02 | Minimal physical | On‑prem servers/devices only when strictly required with documented approval | Exception records |
| SVR-03 | Hardened images | Trusted base images; remove unnecessary packages/services | Build docs; package lists |
| SVR-04 | Identity & MFA | Named admin accounts; MFA at control plane; bastion/jump access | IdP/panel settings; logs |
| SVR-05 | Patch cadence | Security updates on schedule; critical fast‑track | Patch reports |
| SVR-06 | EDR/monitoring | EDR/AV and integrity monitoring enabled | EDR console exports |
| SVR-07 | Secrets | Store secrets/keys in approved vaults; no plaintext | Vault policies; scans |
| SVR-08 | Backups | Backups per policy; quarterly restore tests (critical) | Test logs; backup dashboards |
| SVR-09 | Segmentation | Restrict east‑west; protect internet‑facing with WAF or equivalent | Network diagrams; WAF logs |
| SVR-10 | Logging | Centralize where possible; otherwise manual review cadence with evidence | SIEM list; review records |
| SVR-11 | Admin source restriction | SSH/RDP from secure NOC networks only for locally hosted servers | Firewall/NAC configs |
| SVR-12 | Windows Entra join | Windows servers joined to Microsoft Entra ID; Azure sign‑in | Entra/Azure portal exports |
| SVR-13 | Linux sudo model | Linux logins use non‑privileged users; sudo for elevation | PAM/sudoers configs |
| SVR-14 | Duo for SSH/RDP | Duo Security enforced for SSH and RDP interactive sessions | Duo policies; login logs |

## 5. Roles and Responsibilities

Security Engineering defines and validates baseline controls. IT Operations implements configurations and
patching. System Owners ensure application‑level requirements and support audits and restore tests.

## 6. Revision History

| Version | Date       | Author | Description |
|---------|------------|--------|-------------|
| 1.1.0   | 2025-11-05 |        | Added NOC‑only admin access, Entra join, sudo model, and Duo MFA for SSH/RDP. |
| 1.0.0   | 2025-11-05 |        | Initial cloud‑first server baseline reflecting provider approvals. |


