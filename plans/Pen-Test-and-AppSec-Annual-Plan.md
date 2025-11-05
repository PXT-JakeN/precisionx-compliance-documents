---
title: "Pen-Test & AppSec Annual Plan"
doc_type: "Plan"
id: "GRS-ISMS-PLN-008"
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
  - ../policies/Application-Security-Testing-Policy.md
  - ../procedures/Penetration-Testing-Procedure.md
  - ../procedures/SAST-DAST-and-Code-Review-Procedure.md
  - ../standards/Vulnerability-Severity-and-SLA-Standard.md
---

## Document Control

| Field | Value |
|-------|-------|
| Title | Pen-Test & AppSec Annual Plan |
| Document ID | GRS-ISMS-PLN-008 |
| Version | 1.0.0 |
| Status | Draft |
| Owner | Security Operations Lead |
| Program Manager | Josh Mayorga, Compliance Manager |
| Approver | Executive Management, GridSite Technology LLC |
| Approval Date |  |
| Effective Date |  |
| Next Review Date |  |

## 1. Purpose

Plan the annual cadence of penetration testing and application security activities across GridSite services.

## 2. Scope and Independence

Cover external perimeter, internal networks, cloud control planes, SaaS applications/APIs, and third‑party hosted
surfaces. Use qualified independent testers for material systems; rotate vendors to avoid bias.

## 3. Cadence and Activities

Quarterly SAST/DAST and dependency scanning; semiannual external pen‑tests for internet‑facing systems; annual
comprehensive pen‑test for critical platforms; threat modeling refreshes; secure code reviews for major releases; and
pipeline security checks per CI/CD standard.

## 4. Risk and Remediation

Rate findings per severity standard; enforce SLAs; retest to confirm remediation; track repeat findings; update
detections and baselines accordingly.

## 5. Evidence and Reporting

Store ROE, tester quals, reports, tickets, and retest confirmations; export evidence manually where forwarding is not
available. Provide quarterly summaries to management reviews and audit planning.

## 6. Revision History

| Version | Date       | Author | Description |
|---------|------------|--------|-------------|
| 1.0.0   | 2025-11-05 |        | Initial pen‑test & AppSec annual plan. |


