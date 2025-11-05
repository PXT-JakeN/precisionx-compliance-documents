---
title: "Secure Configuration & Hardening Policy"
doc_type: "Policy"
id: "GRS-ISMS-POL-017"
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
  - ../standards/Workstation-Baseline.md
  - ../standards/Server-Baseline.md
  - ../standards/Container-and-Kubernetes-Baseline.md
  - ../standards/Cloud-Landing-Zone-Standard.md
  - ../standards/Logging-and-Time-Sync-Standard.md
  - ../standards/Vulnerability-Scanning-Standard.md
references:
  - ISO/IEC 27002:2022 (secure configuration)
---

## Document Control

| Field | Value |
|-------|-------|
| Title | Secure Configuration & Hardening Policy |
| Document ID | GRS-ISMS-POL-017 |
| Version | 1.0.0 |
| Status | Draft |
| Owner | Security Engineering Lead |
| Program Manager | Josh Mayorga, Compliance Manager |
| Approver | Executive Management, GridSite Technology LLC |
| Approval Date |  |
| Effective Date |  |
| Next Review Date |  |

## 1. Purpose

Define the mandatory requirements for baseline configuration, hardening, and change discipline across
workstations, servers, cloud services, and containers.

## 2. Scope

All information systems within ISMS scope, including corporate, SaaS, GridColo, and franchise environments.

## 3. Policy Statements

Systems shall be provisioned from approved images and hardened per the applicable standards. Workstations are
Azure Entra‑joined; servers are cloud‑first (Ubuntu LTS or Windows Server VMs) on approved providers (Linode,
DigitalOcean) with administrative ingress restricted to secure NOC networks and MFA (Duo) for SSH/RDP.
Unnecessary services are disabled; least functionality is enforced. Time synchronization and centralized logging
are enabled; where sources cannot forward, documented manual review and export are performed. Secrets are
stored in a central vault; keys and credentials are rotated per standard. Configuration changes follow formal
change control with peer review and rollback. Vulnerabilities are remediated per severity SLAs. Baselines are
reviewed at least annually and after significant changes.

## 4. Exceptions

Exceptions require Security Engineering and ISMS approval with time‑bound remediation plans.

## 5. Compliance Measurement

Measured via configuration audits, CIS/IaC checks, vulnerability scans, and change record sampling.

## 6. Revision History

| Version | Date       | Author | Description |
|---------|------------|--------|-------------|
| 1.0.0   | 2025-11-05 |        | Initial secure configuration & hardening policy. |


