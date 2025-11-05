---
title: "Quality Assurance (QA) Procedure"
doc_type: "Procedure"
id: "GRS-ISMS-PRC-047"
version: "1.0.0"
status: "Draft"
owner: "Quality Lead"
program_manager: "Josh Mayorga, Compliance Manager"
approver: "Executive Management, GridSite Technology LLC"
approval_date: ""
effective_date: ""
next_review_date: ""
classification: "Internal – Controlled"
organization: "GridSite Technology LLC and its operating subsidiaries"
related_documents:
  - ../policies/Quality-and-Document-Control-Policy.md
  - ../policies/Secure-Software-Development-Policy.md
  - ../standards/CI-CD-Security-Standard.md
  - ../procedures/SAST-DAST-and-Code-Review-Procedure.md
---

## Document Control

| Field | Value |
|-------|-------|
| Title | Quality Assurance (QA) Procedure |
| Document ID | GRS-ISMS-PRC-047 |
| Version | 1.0.0 |
| Status | Draft |
| Owner | Quality Lead |
| Program Manager | Josh Mayorga, Compliance Manager |
| Approver | Executive Management, GridSite Technology LLC |
| Approval Date |  |
| Effective Date |  |
| Next Review Date |  |

## 1. Purpose

Establish QA practices that ensure product and service quality across the SDLC and operations.

## 2. Roles

Quality Lead (owner), Engineering Managers, SRE, Product Owners, SecOps, ISMS.

## 3. Procedure

1. Plan Quality: Define acceptance criteria, test strategies, and gates per release; align with risk and regulatory
   requirements.
2. Assure: Enforce peer review, static/dynamic testing, dependency hygiene, and environment parity. Require branch
   protection and signed artifacts per standards.
3. Validate: Execute functional, performance, and security tests; track defects; require pass criteria before release.
4. Monitor & Improve: Capture field quality metrics (incidents, SLOs); open CAPA for systemic issues; verify fixes.

## 4. Records & Evidence

Test plans/results, review records, build artifacts and signatures, defect logs, release approvals.

## 5. Metrics

Defect escape rate, test coverage, change failure rate, MTTR, release compliance rate.

## 6. Revision History

| Version | Date       | Author | Description |
|---------|------------|--------|-------------|
| 1.0.0   | 2025-11-05 |        | Initial QA procedure. |


