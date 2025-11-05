---
title: "Release Management Procedure"
doc_type: "Procedure"
id: "GRS-ISMS-PRC-009"
version: "1.0.0"
status: "Draft"
owner: "SRE Lead"
program_manager: "Josh Mayorga, Compliance Manager"
approver: "Executive Management, GridSite Technology LLC"
approval_date: ""
effective_date: ""
next_review_date: ""
classification: "Internal – Controlled"
organization: "GridSite Technology LLC and its operating subsidiaries"
related_documents:
  - ../policies/Change-and-Release-Management-Policy.md
  - ../standards/CI-CD-Security-Standard.md
  - ../policies/Secure-Software-Development-Policy.md
  - ../standards/Vulnerability-Severity-and-SLA-Standard.md
---

## Document Control

| Field | Value |
|-------|-------|
| Title | Release Management Procedure |
| Document ID | GRS-ISMS-PRC-009 |
| Version | 1.0.0 |
| Status | Draft |
| Owner | SRE Lead |
| Program Manager | Josh Mayorga, Compliance Manager |
| Approver | Executive Management, GridSite Technology LLC |
| Approval Date |  |
| Effective Date |  |
| Next Review Date |  |

## 1. Purpose

Define consistent steps to promote builds through environments with integrity, safety, and traceability.

## 2. Roles

Product Owner, Engineering Lead, SRE, Security Engineering, CAB.

## 3. Prerequisites

Branch protections; passing CI (build, tests, SAST/SCA/secrets); signed artifacts; change ticket approved.

## 4. Procedure

1. Pre‑Deploy Checks: Verify ticket approvals, impact/risk notes, rollout and rollback plans, and maintenance window.
2. Artifact Integrity: Use signed, digest‑pinned images/packages; verify provenance and SBOM.
3. Deployment: Execute via automated pipelines; restrict deploy rights to approved roles; isolate runners; store logs.
4. Post‑Deploy Validation: Run health checks, functional smoke tests, and security checks; monitor error budgets.
5. Approval & Close: Confirm success with stakeholders; update ticket with evidence; schedule hotfixes if defects.
6. Rollback: If necessary, revert to last known good artifact; open defect; initiate emergency change if urgent.

## 5. Records & Evidence

Build and deployment logs, approvals, SBOMs, test results, release notes.

## 6. Metrics

Change failure rate, MTTR, deployment frequency, lead time for changes.

## 7. Revision History

| Version | Date       | Author | Description |
|---------|------------|--------|-------------|
| 1.0.0   | 2025-11-05 |        | Initial release management procedure. |


