---
title: "Data Protection Impact Assessment (DPIA) Procedure"
doc_type: "Procedure"
id: "GRS-ISMS-PRC-051"
version: "1.0.0"
status: "Draft"
owner: "Privacy Officer"
program_manager: "Josh Mayorga, Compliance Manager"
approver: "Executive Management, GridSite Technology LLC"
approval_date: ""
effective_date: ""
next_review_date: ""
classification: "Internal – Controlled"
organization: "GridSite Technology LLC and its operating subsidiaries"
related_documents:
  - ../policies/Privacy-and-Data-Protection-Policy.md
  - ../plans/Data-Inventory.md
  - ../policies/Data-Classification-and-Handling-Policy.md
  - ../policies/Supplier-and-Third-Party-Risk-Management-Policy.md
  - ../procedures/Subservice-Monitoring-Procedure.md
---

## Document Control

| Field | Value |
|-------|-------|
| Title | Data Protection Impact Assessment (DPIA) Procedure |
| Document ID | GRS-ISMS-PRC-051 |
| Version | 1.0.0 |
| Status | Draft |
| Owner | Privacy Officer |
| Program Manager | Josh Mayorga, Compliance Manager |
| Approver | Executive Management, GridSite Technology LLC |
| Approval Date |  |
| Effective Date |  |
| Next Review Date |  |

## 1. Purpose

Define when and how GridSite performs DPIAs to evaluate risks to personal data and implement proportionate controls.

## 2. Triggers

New or materially changed processing of personal data; new categories (special/sensitive); large‑scale monitoring;
use of new tech (AI/automation); new vendors/subprocessors; cross‑border transfers; adverse audit/incident findings.

## 3. Roles

Privacy Officer (owner), System/Data Owner, Legal Counsel, Security Engineering, ISMS Manager, Vendor Manager.

## 4. Procedure

1. Initiate: System/Data Owner submits DPIA request with purpose, data categories, subjects, volumes, transfers,
   vendors, and retention. Link to records in the Data Inventory.
2. Context & Necessity: Describe lawful basis, necessity, and proportionality; identify applicable regulations and
   contractual commitments.
3. Risk Analysis: Identify confidentiality, integrity, availability, and privacy risks to data subjects; evaluate
   likelihood/impact considering classifications and processing context.
4. Controls & Options: Propose mitigations (encryption, minimization, pseudonymization, access controls, logging,
   retention limits, DLP). Prefer Microsoft 365 SSO/OIDC/SAML and MFA for user access. Note manual evidence exports
   when systems cannot forward logs.
5. Consultation: Engage Legal/Privacy and, when required, consult supervisory authorities before proceeding.
6. Decision & Residual Risk: Document accept/remediate/postpone decision and residual risk; obtain approvals per
   Risk Management Policy and Exceptions Procedure for any deviations.
7. Implementation & Verification: Track mitigations to closure; verify effectiveness via tests or evidence; update the
   Data Inventory and vendor records.
8. Review: Re‑assess on significant change or annually, whichever comes first.

## 5. Records & Evidence

DPIA report, approvals, mitigations tracker, evidence exports, updated Data Inventory entries.

## 6. Metrics

Completion cycle time, high‑risk items reduced, mitigation on‑time rate, re‑assessment adherence.

## 7. Revision History

| Version | Date       | Author | Description |
|---------|------------|--------|-------------|
| 1.0.0   | 2025-11-05 |        | Initial DPIA procedure. |


