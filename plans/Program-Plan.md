---
title: "ISMS/BCMS Program Plan"
doc_type: "Plan"
id: "GRS-ISMS-PLN-001"
version: "1.0.0"
status: "Draft"
owner: "ISMS Manager"
program_manager: "Josh Mayorga, Compliance Manager"
approver: "Executive Management, GridSite Technology LLC"
approval_date: ""
effective_date: ""
next_review_date: ""
classification: "Internal – Controlled"
organization: "GridSite Technology LLC and its operating subsidiaries"
related_documents:
  - ../WRITING-PLAN.md
  - ../policies/Information-Security-Policy.md
  - ../policies/Business-Continuity-Policy.md
  - ../plans/Audit-and-Assessment-Plan.md
---

## Document Control

| Field | Value |
|-------|-------|
| Title | ISMS/BCMS Program Plan |
| Document ID | GRS-ISMS-PLN-001 |
| Version | 1.0.0 |
| Status | Draft |
| Owner | ISMS Manager |
| Program Manager | Josh Mayorga, Compliance Manager |
| Approver | Executive Management, GridSite Technology LLC |
| Approval Date |  |
| Effective Date |  |
| Next Review Date |  |

## 1. Purpose

Define scope, objectives, governance, resourcing, schedule, and deliverables of GridSite’s integrated ISMS/BCMS.

## 2. Objectives

Achieve ISO 27001 Stage 1 readiness and SOC readiness at Day 90, followed by SOC 1/2 Type 1 in Q1 2026.

## 3. Scope & Boundaries

Corporate operations, SaaS platforms, GridColo sites, and Powered by GridSite programs; cloud‑first infrastructure in
Linode/DigitalOcean connected to managed sites via secure tunnels; hybrid workforce with WFH, coworking, and dual NOC.

## 4. Governance & Roles

Executive Sponsor; ISMS Manager; Control Owners (Security Eng, SecOps, IT Ops, BC/DR, Facilities); Privacy Officer;
Internal Audit. Management Reviews quarterly (min semi‑annual) per PR46.

## 5. Workstreams & Deliverables

Policy/Standard/Procedure authoring, control implementation and evidence, risk/SOA management, BC/DR exercises,
awareness and phishing program, supplier oversight, audit/assessments, metrics & KRIs, and SOC descriptions.

## 6. Schedule & Milestones

- Day 0–30: Governance, Scope/Context, Risk/SoA, top security policies, access/change/IR/BC.
- Day 31–60: Baselines and procedures (IAM, endpoints, logging, vuln/patch, backups), initial exercises.
- Day 61–90: Plans, playbooks, registers, internal audits, and Stage 1/SOC readiness.

## 7. Methods & Tools

Microsoft 365 SSO/OIDC/SAML with MFA; Duo for SSH/RDP; UniFi Identity for Wi‑Fi; centralized logging/time sync with
manual evidence exports if forwarding unavailable; backups incl. iDrive360 endpoints; IaC guardrails and CI/CD security.

## 8. Communications & Reporting

Monthly progress updates, dashboards for CCM and metrics, management review packs, and executive status reports.

## 9. Risks & Dependencies

Key risks: control gaps, vendor delays, evidence completeness. Dependencies: provider access, portal/kiosk rollouts,
tooling integrations. Mitigate through early pilots, exceptions workflow, and CAPA tracking.

## 10. Continuous Improvement

Feed audit/assessment results, incidents, and metrics into CAPA; update objectives and measures quarterly.

## 11. Revision History

| Version | Date       | Author | Description |
|---------|------------|--------|-------------|
| 1.0.0   | 2025-11-05 |        | Initial program plan. |


