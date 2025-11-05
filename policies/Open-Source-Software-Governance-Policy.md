---
title: "Open-Source Software Governance Policy"
doc_type: "Policy"
id: "GRS-ISMS-POL-041"
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
  - ../procedures/SAST-DAST-and-Code-Review-Procedure.md
  - ../standards/CI-CD-Security-Standard.md
  - ../standards/Vulnerability-Severity-and-SLA-Standard.md
  - ./Legal-and-Regulatory-Compliance-Policy.md
references:
  - ISO/IEC 27002:2022 (supplier relationships, development); OWASP SAMM
---

## Document Control

| Field | Value |
|-------|-------|
| Title | Open-Source Software Governance Policy |
| Document ID | GRS-ISMS-POL-041 |
| Version | 1.0.0 |
| Status | Draft |
| Owner | Security Engineering Lead |
| Program Manager | Josh Mayorga, Compliance Manager |
| Approver | Executive Management, GridSite Technology LLC |
| Approval Date |  |
| Effective Date |  |
| Next Review Date |  |

## 1. Purpose

Define requirements for secure, compliant use of open‑source software (OSS) and for contributions to OSS
projects by GridSite personnel.

## 2. Scope

All software components incorporated into GridSite products and services, and employee contributions made on
behalf of GridSite.

## 3. Policy Statements

OSS components shall be included only when vetted for license compatibility and security posture. Software
composition analysis (SCA) is required in CI; known vulnerabilities must be remediated per severity SLAs or
explicitly risk‑accepted. Components must be pinned by version or digest and tracked via SBOM. Any external
distribution of GridSite code or modifications requires management approval and legal review. Employee
contributions to OSS must avoid disclosure of non‑public or RESTRICTED information; use company accounts
and approved tooling. When upstream vulnerabilities affect GridSite services, fixes shall be backported or
mitigations applied promptly. Logs and evidence of SCA and license checks are retained; systems that cannot
forward results require periodic export and manual review.

## 4. Exceptions

Exceptions require Security Engineering and Legal approval with documented constraints and follow‑up actions.

## 5. Compliance Measurement

Measured via SBOM coverage, SCA reports, license audits, and exception tracking.

## 6. Revision History

| Version | Date       | Author | Description |
|---------|------------|--------|-------------|
| 1.0.0   | 2025-11-05 |        | Initial OSS governance policy. |


