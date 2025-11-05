---
title: "SAST/DAST & Code Review Procedure"
doc_type: "Procedure"
id: "GRS-ISMS-PRC-024"
version: "1.0.0"
status: "Draft"
owner: "Security Engineering Lead"
approver: "Executive Management, GridSite Technology LLC"
approval_date: ""
effective_date: ""
next_review_date: ""
related_documents:
  - ../standards/CI-CD-Security-Standard.md
  - ../policies/Secure-Software-Development-Policy.md
references:
  - OWASP ASVS; OWASP Top 10; NIST SSDF
---

## Document Control

| Field | Value |
|-------|-------|
| Title | SAST/DAST & Code Review Procedure |
| Document ID | GRS-ISMS-PRC-024 |
| Version | 1.0.0 |
| Status | Draft |
| Owner | Security Engineering Lead |
| Approver | Executive Management, GridSite Technology LLC |
| Approval Date |  |
| Effective Date |  |
| Next Review Date |  |

## 1. Purpose

Define repeatable steps for static analysis, software composition analysis, dynamic testing, and code review
within CI/CD with documented evidence and thresholds.

## 2. Scope

All repositories and pipelines used for GridSite software.

## 3. Procedure

1. Configure Pipelines
   - Add SCA/SAST stages on PRs; configure break‑build thresholds for critical vulnerabilities and secrets.
2. Configure DAST
   - Run DAST on major releases and nightly for stable environments; include auth flows; mask secrets.
3. Code Reviews
   - Require at least one qualified reviewer; validate threat model considerations and security‑relevant changes.
4. Evidence Retention
   - Store scan reports and review approvals with build artifacts; retain screenshots/exports if tools cannot
     integrate.
5. Remediation
   - Create tickets for findings; track to closure per SLA standard; verify fixes with re‑scans.
6. Governance
   - Periodically tune rules to reduce false positives; report metrics to Management Review.

## 4. Records

Pipeline configs, scan reports, PR approvals, and remediation tickets.

## 5. Revision History

| Version | Date       | Author | Description |
|---------|------------|--------|-------------|
| 1.0.0   | 2025-11-05 |        | Initial SAST/DAST + code review procedure. |


