---
title: "CI/CD Hardening Procedure"
doc_type: "Procedure"
id: "GRS-ISMS-PRC-026"
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
  - ../standards/CI-CD-Security-Standard.md
  - ../policies/Secure-Software-Development-Policy.md
  - ../standards/Secrets-Management-Standard.md
---

## Document Control

| Field | Value |
|-------|-------|
| Title | CI/CD Hardening Procedure |
| Document ID | GRS-ISMS-PRC-026 |
| Version | 1.0.0 |
| Status | Draft |
| Owner | Security Engineering Lead |
| Program Manager | Josh Mayorga, Compliance Manager |
| Approver | Executive Management, GridSite Technology LLC |
| Approval Date |  |
| Effective Date |  |
| Next Review Date |  |

## 1. Purpose

Define steps to secure source, build, and deployment pipelines and reduce supply‑chain risk.

## 2. Roles

Security Engineering (owner), Dev Leads, SRE, Platform Engineering, ISMS.

## 3. Prerequisites

Repository admin access; pipeline admin; OIDC workload identity for cloud deploys; secret scanning; code owners.

## 4. Procedure

1. Repos: Enforce branch protections, required reviews, signed commits, and CODEOWNERS; enable secret/SAST/SCA
   scanning with blocking thresholds.
2. Runners/Agents: Isolate runners per trust level; avoid shared credentials; prefer OIDC to cloud over long‑lived
   keys; restrict egress; log builds.
3. Artifacts: Sign and store in restricted registries; pin by digest; run image scans on push and deploy.
4. Pipelines: Use least‑privilege service accounts; separate build and deploy stages; store logs immutably or export
   if forwarding is unavailable.
5. Releases: Require change ticket linkage, approvals, and rollback; verify SBOM and provenance before deploy.

## 5. Records & Evidence

Repo settings exports, scan results, build logs, artifact metadata, approvals.

## 6. Metrics

Coverage of protected repos, scan pass rates, drift in runner isolation, artifact signing coverage.

## 7. Revision History

| Version | Date       | Author | Description |
|---------|------------|--------|-------------|
| 1.0.0   | 2025-11-05 |        | Initial CI/CD hardening procedure. |


