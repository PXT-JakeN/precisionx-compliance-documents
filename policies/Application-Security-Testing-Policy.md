---
title: "Application Security Testing Policy"
doc_type: "Policy"
id: "GRS-ISMS-POL-038"
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
  - ./Secure-Software-Development-Policy.md
  - ../standards/CI-CD-Security-Standard.md
  - ../procedures/SAST-DAST-and-Code-Review-Procedure.md
  - ../standards/Vulnerability-Scanning-Standard.md
  - ../standards/Vulnerability-Severity-and-SLA-Standard.md
references:
  - ISO/IEC 27002:2022 (secure development); OWASP ASVS
---

## Document Control

| Field | Value |
|-------|-------|
| Title | Application Security Testing Policy |
| Document ID | GRS-ISMS-POL-038 |
| Version | 1.0.0 |
| Status | Draft |
| Owner | Security Engineering Lead |
| Program Manager | Josh Mayorga, Compliance Manager |
| Approver | Executive Management, GridSite Technology LLC |
| Approval Date |  |
| Effective Date |  |
| Next Review Date |  |

## 1. Purpose

Define mandatory security testing activities across the software development lifecycle to prevent, detect, and
remediate vulnerabilities prior to release and during operations.

## 2. Scope

All custom applications and services developed or operated by GridSite, including APIs and infrastructure‑as‑code.

## 3. Policy Statements

Projects shall integrate automated SAST, SCA, and secret scanning in CI with blocking thresholds aligned to the
Vulnerability Severity & SLA Standard. DAST is required for internet‑exposed services prior to release and at least
quarterly thereafter, with authenticated coverage where feasible. High‑risk changes require targeted threat
modeling and manual review. Findings are triaged, tracked, and remediated within SLAs; exceptions require risk
acceptance. Test artifacts and results are retained as evidence. Where tools cannot forward logs or results,
periodic exports and manual review are performed.

## 4. Exceptions

Exceptions require Security Engineering and ISMS approval with documented rationale and timeframe.

## 5. Compliance Measurement

Measured via CI gate results, defect aging reports, and release readiness checklists.

## 6. Revision History

| Version | Date       | Author | Description |
|---------|------------|--------|-------------|
| 1.0.0   | 2025-11-05 |        | Initial application security testing policy. |


