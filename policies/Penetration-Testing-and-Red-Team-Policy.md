---
title: "Penetration Testing & Red Team Policy"
doc_type: "Policy"
id: "GRS-ISMS-POL-039"
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
  - ../procedures/Penetration-Testing-Procedure.md
  - ./Vulnerability-and-Patch-Management-Policy.md
  - ../standards/Vulnerability-Severity-and-SLA-Standard.md
references:
  - ISO/IEC 27002:2022 (testing and review); OWASP; NIST SP 800‑115
---

## Document Control

| Field | Value |
|-------|-------|
| Title | Penetration Testing & Red Team Policy |
| Document ID | GRS-ISMS-POL-039 |
| Version | 1.0.0 |
| Status | Draft |
| Owner | Security Operations Lead |
| Program Manager | Josh Mayorga, Compliance Manager |
| Approver | Executive Management, GridSite Technology LLC |
| Approval Date |  |
| Effective Date |  |
| Next Review Date |  |

## 1. Purpose

Define the strategy and requirements for penetration testing and adversary simulation to validate the
effectiveness of security controls and response capabilities.

## 2. Scope

Internet‑facing assets, critical internal services, APIs, and applications in production and pre‑production, along
with people and processes where social engineering is in scope per rules of engagement.

## 3. Policy Statements

External penetration testing of internet‑exposed systems shall occur at least annually and after material
changes; application‑focused tests align to release risk. Red team or purple team exercises are scheduled to
validate detection and response. Activities follow documented rules of engagement, legal authorization, and
safe‑harbor guidance; testing artifacts, evidence, and findings are retained. Findings are triaged and remediated
per severity SLAs; high‑risk items require prompt mitigation and retest. Where service providers are involved,
independence and qualifications are verified. Test logs and telemetry feed the SIEM; if forwarding is not
possible, results are exported and manually reviewed.

## 4. Exceptions

Exceptions require Security Operations and ISMS approval with documented risk treatment.

## 5. Compliance Measurement

Measured via test schedules, reports, remediation trackers, and retest confirmations.

## 6. Revision History

| Version | Date       | Author | Description |
|---------|------------|--------|-------------|
| 1.0.0   | 2025-11-05 |        | Initial penetration testing & red team policy. |


