---
title: "Security & Compliance Implementation Plan and Checklist"
doc_type: "Plan"
id: "GRS-ISMS-IMPL-001"
version: "1.0.0"
status: "Draft"
owner: "ISMS Manager"
program_manager: "Josh Mayorga, Compliance Manager"
approver: "Executive Management, GridSite Technology LLC"
approval_date: ""
effective_date: "2025-11-06"
next_review_date: ""
classification: "Internal – Controlled"
organization: "GridSite Technology LLC and its operating subsidiaries"
related_documents:
  - ../coordination/catalogs/ISO27001-AnnexA.md
  - ../coordination/catalogs/ISO22301-Clauses.md
  - ../coordination/catalogs/SOC2-TSC.md
  - ../coordination/catalogs/SOC1-ICFR-Objectives.md
---

## Document Control

| Field | Value |
|-------|-------|
| Title | Security & Compliance Implementation Plan and Checklist |
| Document ID | GRS-ISMS-IMPL-001 |
| Version | 1.0.0 |
| Status | Draft |
| Owner | ISMS Manager |
| Program Manager | Josh Mayorga, Compliance Manager |
| Approver | Executive Management, GridSite Technology LLC |
| Effective Date | 2025-11-06 |
| Next Review Date |  |

## 1. Purpose

Provide a single, auditable plan and checklist to implement each control requirement across ISO 27001 Annex A (and
subsequently ISO 22301, SOC 2, SOC 1), assign ownership, track status, and link to evidence.

## 2. How to Use

- Status values: Planned, In Progress, Blocked, In Review, Implemented, Evidenced.
- For each control, the checklist must be completed and evidence stored or exported where forwarding is not feasible.
- Record work items as links to tickets/PRs and keep owners current.

## 3. Roles and Responsibilities (initial)

| Role | Name/Group |
|------|------------|
| ISMS Manager |  |
| GRC Analyst |  |
| Security Operations Lead |  |
| Security Engineering Lead |  |
| IT Operations Lead |  |
| BC/DR Lead |  |
| Facilities Lead |  |
| Product Engineering Lead |  |
| Finance Controller |  |

## 4. Evidence Repositories

- SIEM: security logs, alerts, tuning; manual exports for non-forwarding systems
- Repo: policies/standards/procedures; approvals; revision history
- Ticketing/ITSM: change, access, incident, problem, service requests
- Vaults/Key stores: key rotation records; credential management

## 5. ISO/IEC 27001:2022 Annex A – Implementation Matrix (starter)

| Req ID | Title | Primary Owner | Supporting Roles | Status | Target Date | Evidence to Collect | Links |
|--------|-------|---------------|------------------|--------|-------------|---------------------|-------|
| A.5.1 | Policies for information security | ISMS Manager | GRC Analyst | Planned |  | Approved P01; P34 rev history; comms proof | ../coordination/catalogs/ISO27001-AnnexA.md |
| A.5.2 | IS roles and responsibilities | ISMS Manager | Sec Eng Lead | Planned |  | RACI; role assignments; acknowledgements | ../coordination/catalogs/ISO27001-AnnexA.md |
| A.5.3 | Segregation of duties | ISMS Manager | Finance Controller | Planned |  | SoD matrix; exception approvals; review logs | ../coordination/catalogs/ISO27001-AnnexA.md |
| A.5.10 | Acceptable use | ISMS Manager | IT Ops Lead | Planned |  | AUP acks; endpoint compliance reports | ../coordination/catalogs/ISO27001-AnnexA.md |
| A.5.23 | Cloud services security | Sec Eng Lead | IT Ops Lead | Planned |  | Cloud guardrails; IaC scans; vendor DDQs | ../coordination/catalogs/ISO27001-AnnexA.md |
| A.5.24 | IR planning & preparation | SecOps Lead | ISMS Manager | Planned |  | IR plan; call trees; duty rosters | ../coordination/catalogs/ISO27001-AnnexA.md |
| A.5.25 | Event assessment & decision | SecOps Lead | GRC Analyst | Planned |  | Triage SOP; alert categorizations; cases | ../coordination/catalogs/ISO27001-AnnexA.md |
| A.5.26 | Incident response | SecOps Lead | IT Ops Lead | Planned |  | Incident tickets; timelines; PIRs | ../coordination/catalogs/ISO27001-AnnexA.md |
| A.5.28 | Collection of evidence | SecOps Lead | GRC Analyst | Planned |  | Chain-of-custody forms; exports | ../coordination/catalogs/ISO27001-AnnexA.md |
| A.5.29 | IS during disruption | BC/DR Lead | SecOps Lead | Planned |  | Plans referencing IS constraints | ../coordination/catalogs/ISO27001-AnnexA.md |
| A.5.30 | ICT readiness for BC | BC/DR Lead | IT Ops Lead | Planned |  | DR tests; NTP; failover results | ../coordination/catalogs/ISO27001-AnnexA.md |
| A.6.1 | Screening | HR (Delegate) | GRC Analyst | Planned |  | Background checks; policy acks | ../coordination/catalogs/ISO27001-AnnexA.md |
| A.6.7 | Remote working | Sec Eng Lead | IT Ops Lead | Planned |  | Device posture; VPN; MFA | ../coordination/catalogs/ISO27001-AnnexA.md |
| A.7.1 | Physical security perimeters | Facilities Lead | SecOps Lead | Planned |  | Site diagrams; access configs | ../coordination/catalogs/ISO27001-AnnexA.md |
| A.7.2 | Physical entry | Facilities Lead | Site Security | Planned |  | Badge/kiosk logs; visitor logs | ../coordination/catalogs/ISO27001-AnnexA.md |
| A.8.1 | User endpoint devices | IT Ops Lead | Sec Eng Lead | Planned |  | EDR; encryption; backup success (iDrive360) | ../coordination/catalogs/ISO27001-AnnexA.md |
| A.8.2 | Privileged access rights | Sec Eng Lead | SecOps Lead | Planned |  | PAM approvals; session recordings; Duo | ../coordination/catalogs/ISO27001-AnnexA.md |
| A.8.8 | Technical vulnerabilities | Sec Eng Lead | IT Ops Lead | Planned |  | Scans; SLAs; remediation tickets | ../coordination/catalogs/ISO27001-AnnexA.md |
| A.8.13 | Information backup | BC/DR Lead | IT Ops Lead | Planned |  | Backup jobs; restore tests; immutability | ../coordination/catalogs/ISO27001-AnnexA.md |
| A.8.15 | Logging | SecOps Lead | Sec Eng Lead | Planned |  | Log retention configs; manual exports | ../coordination/catalogs/ISO27001-AnnexA.md |
| A.8.16 | Monitoring activities | SecOps Lead | GRC Analyst | Planned |  | Alert SLAs; tuning records | ../coordination/catalogs/ISO27001-AnnexA.md |
| A.8.17 | Clock synchronization | SecOps Lead | IT Ops Lead | Planned |  | NTP config; skew reports | ../coordination/catalogs/ISO27001-AnnexA.md |

## 6. ISO 27001 – Detailed Implementation Checklists (initial controls)

### A.5.1 Policies for information security (Owner: ISMS Manager)

- [ ] Review and approve `P01 Information Security Policy` and `P34 Quality & Document Control` in current cycle
- [ ] Publish and notify all personnel; record communication evidence
- [ ] Ensure policy references to Entra SSO, Duo for SSH/RDP, cloud-first posture are current
- [ ] File approvals and revision history in repo; link to evidence folder

Evidence: signed approval, comms export, repo revision log

### A.5.2 IS roles and responsibilities (Owner: ISMS Manager)

- [ ] Update RACI covering ISMS, SecOps, IT Ops, BC/DR, Facilities, Finance
- [ ] Post RACI; obtain acknowledgement from role owners
- [ ] Link RACI into `P01` and onboarding pack

Evidence: RACI document, acknowledgements

### A.5.3 Segregation of duties (Owner: ISMS Manager; Support: Finance Controller)

- [ ] Maintain SoD matrix across engineering, operations, finance
- [ ] Implement SoD checks in access reviews; document exceptions in PR44 workflow

Evidence: SoD matrix, exception approvals

### A.5.23 Cloud services security (Owner: Security Engineering Lead)

- [ ] Enforce SSO/MFA to cloud control planes
- [ ] Apply baseline guardrails (S22) via IaC; document drift monitors
- [ ] Complete vendor due diligence and export evidence

Evidence: IaC/state reports, SSO configs, DDQs

### A.5.24–A.5.28 Incident readiness, triage, response, lessons, evidence (Owner: Security Operations Lead)

- [ ] Maintain IR plan, roles, contact lists (P22/PL07)
- [ ] Implement triage workflow and severity scheme (PR20)
- [ ] Keep runbooks up to date (PR13/14/15/16/17)
- [ ] Capture PIRs and CAPA; maintain evidence collection SOP (PR18)

Evidence: incident tickets, PIRs, CAPA, chain-of-custody

### A.5.29–A.5.30 IS during disruption; ICT readiness (Owner: BC/DR Lead)

- [ ] Ensure IS constraints in crisis/continuity plans (PL11/PL05)
- [ ] Test failover; verify logging/time sync post‑failover

Evidence: exercise reports, failover logs

### A.6.1 Screening (Owner: HR Delegate)

- [ ] Apply background checks proportional to roles; retain proof
- [ ] Integrate checks into onboarding checklist (PR06)

Evidence: screening confirmations

### A.6.7 Remote working (Owner: Security Engineering Lead)

- [ ] Enforce device posture, VPN, Duo MFA; sensitivity label limits for BYOD
- [ ] Review posture exceptions quarterly

Evidence: device compliance, VPN/MFA logs

### A.7.1–A.7.2 Physical perimeters and entry (Owner: Facilities Lead)

- [ ] Implement portal/kiosk 3‑factor; escort limits; guard fallback
- [ ] Export badge/visitor logs to evidence store

Evidence: access configs, exported logs

### A.8.1 Endpoints; A.8.2 Privileged access (Owners: IT Ops Lead; Security Engineering Lead)

- [ ] Enforce EDR, full‑disk encryption, iDrive360 backups
- [ ] Require Duo for SSH/RDP; record privileged sessions where feasible

Evidence: EDR/encryption reports; Duo/session records

### A.8.8 Vulnerability management (Owner: Security Engineering Lead)

- [ ] Run authenticated scans; track SLAs per S13; report exceptions

Evidence: scan results; SLA dashboards

### A.8.13 Backups (Owner: BC/DR Lead)

- [ ] Maintain encrypted, immutable backups; quarterly restores

Evidence: backup jobs; restore logs; immutability proofs

### A.8.15–A.8.17 Logging, monitoring, time (Owner: Security Operations Lead)

- [ ] Onboard sources to SIEM; document manual export cadence for non‑forwarding systems
- [ ] Define/measure alert SLAs; maintain tuning records
- [ ] Enforce NTP to approved sources; capture skew reports

Evidence: SIEM onboarding/tuning; exports; NTP reports

---

Future work: Add remaining Annex A controls to the matrix and detailed checklists, then proceed with ISO 22301, SOC 2, and SOC 1 sections.


