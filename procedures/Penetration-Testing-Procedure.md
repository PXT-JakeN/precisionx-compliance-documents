---
title: "Penetration Testing Procedure"
doc_type: "Procedure"
id: "GRS-ISMS-PRC-041"
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
  - ../policies/Penetration-Testing-and-Red-Team-Policy.md
  - ../standards/Vulnerability-Severity-and-SLA-Standard.md
  - ../policies/Incident-Response-Policy.md
  - ../standards/CI-CD-Security-Standard.md
---

## Document Control

| Field | Value |
|-------|-------|
| Title | Penetration Testing Procedure |
| Document ID | GRS-ISMS-PRC-041 |
| Version | 1.0.0 |
| Status | Draft |
| Owner | Security Operations Lead |
| Program Manager | Josh Mayorga, Compliance Manager |
| Approver | Executive Management, GridSite Technology LLC |
| Approval Date |  |
| Effective Date |  |
| Next Review Date |  |

## 1. Purpose

Define steps to scope, authorize, execute, and close penetration tests of GridSite assets and services.

## 2. Roles

Test Coordinator (SecOps), System Owner, Vendor Tester (if used), Legal, ISMS, SRE/Engineering.

## 3. Prerequisites

Rules of engagement (ROE), written authorization, test windows, out‑of‑scope constraints, contacts, and rollback
plans; evidence repository and SIEM integrations (or manual export plan if forwarding is unavailable).

## 4. Procedure

1. Plan: Define scope, objectives, environments, and success criteria; validate independence and qualifications; get
   Legal approval for ROE.
2. Prepare: Create safe‑lists, monitoring alerts, and backup/rollback; notify NOC and stakeholders.
3. Execute: Perform testing per ROE; avoid unacceptable risks; capture detailed evidence; immediately report
   critical findings.
4. Analyze & Report: Deduplicate and rate findings per severity standard; produce report with PoC and impact.
5. Remediate & Verify: Create tickets; remediate within SLAs; retest to confirm fixes; attach evidence.
6. Close & Learn: Hold review; update detections and baselines; archive artifacts to evidence store.

## 5. Records & Evidence

ROE, authorizations, tester qualifications, test logs, findings, remediation tickets, retest confirmations.

## 6. Metrics

Critical/high findings count, time‑to‑mitigate, retest pass rate, repeat finding rate.

## 7. Revision History

| Version | Date       | Author | Description |
|---------|------------|--------|-------------|
| 1.0.0   | 2025-11-05 |        | Initial penetration testing procedure. |


