---
title: "Secure Software Development Policy"
doc_type: "Policy"
id: "GRS-ISMS-POL-018"
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
  - ../standards/API-Security-Standard.md
  - ../procedures/SAST-DAST-and-Code-Review-Procedure.md
references:
  - OWASP ASVS; OWASP Top 10; NIST SSDF
---

## Document Control

| Field | Value |
|-------|-------|
| Title | Secure Software Development Policy |
| Document ID | GRS-ISMS-POL-018 |
| Version | 1.0.0 |
| Status | Draft |
| Owner | Security Engineering Lead |
| Program Manager | Josh Mayorga, Compliance Manager |
| Approver | Executive Management, GridSite Technology LLC |
| Approval Date |  |
| Effective Date |  |
| Next Review Date |  |

## 1. Purpose

Direct GridSite’s SSDLC to integrate security activities from design through deployment and operations.

## 2. Scope

All software developed or maintained by GridSite, including infrastructure‑as‑code and pipelines.

## 3. Policy Statements

Threat modeling is performed for new services and major changes. Dependencies are managed with SBOM and
SCA; vulnerable components are remediated per SLAs. Code is reviewed by peers; secrets are prohibited from
source code and scanned continuously. CI/CD pipelines enforce SAST/SCA/DAST with break‑build thresholds
for critical findings and evidence retention. Artifacts are signed and stored in controlled registries; deployment
gates enforce approvals and change control. Post‑deployment monitoring and logging support incident
response and continuous improvement.

## 4. Exceptions

Exceptions require risk assessment, approvals, and compensating controls.

## 5. Compliance Measurement

Measured via pipeline reports, review records, and artifact integrity checks.

## 6. Revision History

| Version | Date       | Author | Description |
|---------|------------|--------|-------------|
| 1.0.0   | 2025-11-05 |        | Initial SSDLC policy. |


