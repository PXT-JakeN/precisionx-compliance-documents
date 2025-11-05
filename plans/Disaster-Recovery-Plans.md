---
title: "Disaster Recovery Plans – by System"
doc_type: "Plan"
id: "GRS-ISMS-PLN-005"
version: "1.0.0"
status: "Draft"
owner: "BC/DR Lead"
program_manager: "Josh Mayorga, Compliance Manager"
approver: "Executive Management, GridSite Technology LLC"
approval_date: ""
effective_date: ""
next_review_date: ""
classification: "Internal – Controlled"
organization: "GridSite Technology LLC and its operating subsidiaries"
related_documents:
  - ../policies/Disaster-Recovery-Policy.md
  - ./BIA-Reports.md
  - ./BCMS-Strategy-Plan.md
  - ../standards/Cloud-Landing-Zone-Standard.md
---

## Document Control

| Field | Value |
|-------|-------|
| Title | Disaster Recovery Plans – by System |
| Document ID | GRS-ISMS-PLN-005 |
| Version | 1.0.0 |
| Status | Draft |
| Owner | BC/DR Lead |
| Program Manager | Josh Mayorga, Compliance Manager |
| Approver | Executive Management, GridSite Technology LLC |
| Approval Date |  |
| Effective Date |  |
| Next Review Date |  |

## 1. Purpose

Define the standard content and maintenance model for per‑system Disaster Recovery Plans (DRPs).

## 2. DRP Template

Each system DRP must include: scope and dependencies; RTO/RPO targets from the BIA; roles and contacts; recovery
locations/environments; data protection (backups/immutability/encryption/keys); step‑by‑step failover and failback;
validation tests; communication steps; and evidence capture instructions. Prefer cloud‑native automation and IaC.

## 3. Plan Ownership & Updates

System Owners maintain DRPs; review at least annually or after material changes; align with production changes via
Change Control; record version history and store artifacts in the evidence repository (manual export if needed).

## 4. Testing & Assurance

Quarterly restore tests for critical data; annual DR exercises for key systems; track outcomes and CAPA; demonstrate
meeting or improving RTO/RPO.

## 5. Revision History

| Version | Date       | Author | Description |
|---------|------------|--------|-------------|
| 1.0.0   | 2025-11-05 |        | Initial DR plans master guidance. |


