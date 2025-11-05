---
title: "Configuration Management Procedure"
doc_type: "Procedure"
id: "GRS-ISMS-PRC-010"
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
  - ../policies/Secure-Configuration-and-Hardening-Policy.md
  - ../standards/Server-Baseline.md
  - ../standards/Workstation-Baseline.md
  - ../standards/Cloud-Landing-Zone-Standard.md
  - ../standards/Logging-and-Time-Sync-Standard.md
---

## Document Control

| Field | Value |
|-------|-------|
| Title | Configuration Management Procedure |
| Document ID | GRS-ISMS-PRC-010 |
| Version | 1.0.0 |
| Status | Draft |
| Owner | Security Engineering Lead |
| Program Manager | Josh Mayorga, Compliance Manager |
| Approver | Executive Management, GridSite Technology LLC |
| Approval Date |  |
| Effective Date |  |
| Next Review Date |  |

## 1. Purpose

Define processes to establish, maintain, and verify secure configurations for systems, cloud services, and devices.

## 2. Roles

Security Engineering, IT Operations, Cloud Engineering, SRE, ISMS.

## 3. Prerequisites

Approved baselines; IaC repositories with guardrails; configuration scanning tools; CMDB/asset inventory.

## 4. Procedure

1. Baseline Definition: Maintain CIS‑aligned baselines for servers, workstations, containers, and cloud. Document
   deviations and approvals.
2. Provisioning: Build from approved images; ensure time sync and logging enabled; restrict admin ingress to NOC
   networks; enforce Duo for RDP/SSH; store secrets in central vault.
3. Drift Detection: Continuously scan configurations; open tickets for drift; remediate per risk/SLA.
4. Change Management: Apply configuration changes via change control; use peer review; track in version control.
5. Verification: Periodically audit systems against baselines; validate that non‑forwarding systems export logs
   for manual review on cadence.

## 5. Records & Evidence

Baseline documents, scan results, remediation tickets, approvals, and audit reports.

## 6. Metrics

Baseline coverage, drift MTTR, percent compliant hosts, recurring drift rate.

## 7. Revision History

| Version | Date       | Author | Description |
|---------|------------|--------|-------------|
| 1.0.0   | 2025-11-05 |        | Initial configuration management procedure. |


