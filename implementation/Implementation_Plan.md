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

## 5. ISO/IEC 27001:2022 Annex A – Implementation Matrix (full)

| Req ID | Title | Primary Owner | Supporting Roles | Status | Target Date | Evidence to Collect | Links |
|--------|-------|---------------|------------------|--------|-------------|---------------------|-------|
| A.5.1 | Policies for information security | ISMS Manager | GRC Analyst | Planned |  | Approved P01; P34 rev history; comms proof | [Annex A](../coordination/catalogs/ISO27001-AnnexA.md) |
| A.5.2 | Information security roles and responsibilities | ISMS Manager | Security Engineering Lead | Planned |  | RACI; role assignments; acknowledgements | [Annex A](../coordination/catalogs/ISO27001-AnnexA.md) |
| A.5.3 | Segregation of duties | ISMS Manager | Finance Controller | Planned |  | SoD matrix; exception approvals; review logs | [Annex A](../coordination/catalogs/ISO27001-AnnexA.md) |
| A.5.4 | Management responsibilities | ISMS Manager | All People Managers | Planned |  | Management directives; comms | [Annex A](../coordination/catalogs/ISO27001-AnnexA.md) |
| A.5.5 | Contact with authorities | Security Operations Lead | ISMS Manager | Planned |  | Contact lists; notifications | [Annex A](../coordination/catalogs/ISO27001-AnnexA.md) |
| A.5.6 | Contact with special interest groups | ISMS Manager | Security Operations Lead | Planned |  | Memberships; forum notes | [Annex A](../coordination/catalogs/ISO27001-AnnexA.md) |
| A.5.7 | Threat intelligence | Security Operations Lead | Security Engineering Lead | Planned |  | TI feeds; detections updates | [Annex A](../coordination/catalogs/ISO27001-AnnexA.md) |
| A.5.8 | Information security in project management | Product Engineering Lead | Security Engineering Lead | Planned |  | Design reviews; security gates | [Annex A](../coordination/catalogs/ISO27001-AnnexA.md) |
| A.5.9 | Inventory of information and other associated assets | IT Operations Lead | ISMS Manager | Planned |  | CMDB; ownership records | [Annex A](../coordination/catalogs/ISO27001-AnnexA.md) |
| A.5.10 | Acceptable use of information and other associated assets | ISMS Manager | IT Operations Lead | Planned |  | AUP acks; endpoint compliance | [Annex A](../coordination/catalogs/ISO27001-AnnexA.md) |
| A.5.11 | Return of assets | HR (Delegate) | IT Operations Lead | Planned |  | Offboarding checklists; return logs | [Annex A](../coordination/catalogs/ISO27001-AnnexA.md) |
| A.5.12 | Classification of information | ISMS Manager | GRC Analyst | Planned |  | Label policy; examples | [Annex A](../coordination/catalogs/ISO27001-AnnexA.md) |
| A.5.13 | Labelling of information | ISMS Manager | Security Engineering Lead | Planned |  | Label configs; auto-label rules | [Annex A](../coordination/catalogs/ISO27001-AnnexA.md) |
| A.5.14 | Information transfer | ISMS Manager | Security Engineering Lead | Planned |  | Transfer agreements; TLS/mTLS | [Annex A](../coordination/catalogs/ISO27001-AnnexA.md) |
| A.5.15 | Access control | Security Engineering Lead | ISMS Manager | Planned |  | Access policy; reviews | [Annex A](../coordination/catalogs/ISO27001-AnnexA.md) |
| A.5.16 | Identity management | Security Engineering Lead | IT Operations Lead | Planned |  | JML tickets; Entra logs | [Annex A](../coordination/catalogs/ISO27001-AnnexA.md) |
| A.5.17 | Authentication information | Security Engineering Lead | Security Operations Lead | Planned |  | MFA configs; reset logs | [Annex A](../coordination/catalogs/ISO27001-AnnexA.md) |
| A.5.18 | Access rights | Security Engineering Lead | IT Operations Lead | Planned |  | Access reviews; approvals | [Annex A](../coordination/catalogs/ISO27001-AnnexA.md) |
| A.5.19 | Information security in supplier relationships | ISMS Manager | Procurement | Planned |  | DDQs; risk tiers | [Annex A](../coordination/catalogs/ISO27001-AnnexA.md) |
| A.5.20 | Addressing IS within supplier agreements | ISMS Manager | Legal | Planned |  | Contract clauses; DPA | [Annex A](../coordination/catalogs/ISO27001-AnnexA.md) |
| A.5.21 | Managing IS in the ICT supply chain | Security Engineering Lead | ISMS Manager | Planned |  | Vendor monitoring; SBOMs | [Annex A](../coordination/catalogs/ISO27001-AnnexA.md) |
| A.5.22 | Monitoring, review and change of supplier services | ISMS Manager | GRC Analyst | Planned |  | SOC reports; gap trackers | [Annex A](../coordination/catalogs/ISO27001-AnnexA.md) |
| A.5.23 | Information security for use of cloud services | Security Engineering Lead | IT Operations Lead | Planned |  | Guardrails; IaC scans | [Annex A](../coordination/catalogs/ISO27001-AnnexA.md) |
| A.5.24 | IS incident management planning and preparation | Security Operations Lead | ISMS Manager | Planned |  | IR plan; call trees; rosters | [Annex A](../coordination/catalogs/ISO27001-AnnexA.md) |
| A.5.25 | Assessment and decision on IS events | Security Operations Lead | GRC Analyst | Planned |  | Triage SOP; categorizations | [Annex A](../coordination/catalogs/ISO27001-AnnexA.md) |
| A.5.26 | Response to IS incidents | Security Operations Lead | IT Operations Lead | Planned |  | Incident tickets; PIRs | [Annex A](../coordination/catalogs/ISO27001-AnnexA.md) |
| A.5.27 | Learning from IS incidents | ISMS Manager | Security Operations Lead | Planned |  | PIRs; CAPA | [Annex A](../coordination/catalogs/ISO27001-AnnexA.md) |
| A.5.28 | Collection of evidence | Security Operations Lead | GRC Analyst | Planned |  | Chain of custody; exports | [Annex A](../coordination/catalogs/ISO27001-AnnexA.md) |
| A.5.29 | Information security during disruption | BC/DR Lead | Security Operations Lead | Planned |  | Plans showing IS constraints | [Annex A](../coordination/catalogs/ISO27001-AnnexA.md) |
| A.5.30 | ICT readiness for business continuity | BC/DR Lead | IT Operations Lead | Planned |  | DR tests; NTP checks | [Annex A](../coordination/catalogs/ISO27001-AnnexA.md) |
| A.5.31 | Legal, statutory, regulatory and contractual requirements | ISMS Manager | Legal | Planned |  | Obligations register; attestations | [Annex A](../coordination/catalogs/ISO27001-AnnexA.md) |
| A.5.32 | Intellectual property rights | Legal | ISMS Manager | Planned |  | IPR procedures; access controls | [Annex A](../coordination/catalogs/ISO27001-AnnexA.md) |
| A.5.33 | Protection of records | ISMS Manager | GRC Analyst | Planned |  | Retention schedule; access logs | [Annex A](../coordination/catalogs/ISO27001-AnnexA.md) |
| A.5.34 | Privacy and protection of PII | ISMS Manager | Privacy Officer | Planned |  | DPIAs; DLP alerts | [Annex A](../coordination/catalogs/ISO27001-AnnexA.md) |
| A.5.35 | Independent review of information security | Internal Audit | ISMS Manager | Planned |  | IA plans; reports | [Annex A](../coordination/catalogs/ISO27001-AnnexA.md) |
| A.5.36 | Compliance with IS policies, rules and standards | Internal Audit | ISMS Manager | Planned |  | Review findings; actions | [Annex A](../coordination/catalogs/ISO27001-AnnexA.md) |
| A.5.37 | Documented operating procedures | IT Operations Lead | ISMS Manager | Planned |  | SOP repository; approvals | [Annex A](../coordination/catalogs/ISO27001-AnnexA.md) |
| A.6.1 | Screening | HR (Delegate) | GRC Analyst | Planned |  | Background checks; acks | [Annex A](../coordination/catalogs/ISO27001-AnnexA.md) |
| A.6.2 | Terms and conditions of employment | HR (Delegate) | ISMS Manager | Planned |  | Contract clauses; AUP acks | [Annex A](../coordination/catalogs/ISO27001-AnnexA.md) |
| A.6.3 | IS awareness, education and training | ISMS Manager | HR (Delegate) | Planned |  | Curriculum; attendance | [Annex A](../coordination/catalogs/ISO27001-AnnexA.md) |
| A.6.4 | Disciplinary process | HR (Delegate) | ISMS Manager | Planned |  | Disciplinary records | [Annex A](../coordination/catalogs/ISO27001-AnnexA.md) |
| A.6.5 | Responsibilities after termination or change | HR (Delegate) | IT Operations Lead | Planned |  | Exit acks; deprovision logs | [Annex A](../coordination/catalogs/ISO27001-AnnexA.md) |
| A.6.6 | Confidentiality or non-disclosure agreements | HR (Delegate) | Privacy Officer | Planned |  | Signed NDAs; policy refs | [Annex A](../coordination/catalogs/ISO27001-AnnexA.md) |
| A.6.7 | Remote working | Security Engineering Lead | IT Operations Lead | Planned |  | Device posture; VPN; MFA | [Annex A](../coordination/catalogs/ISO27001-AnnexA.md) |
| A.6.8 | IS event reporting | Security Operations Lead | ISMS Manager | Planned |  | Report forms; tickets | [Annex A](../coordination/catalogs/ISO27001-AnnexA.md) |
| A.7.1 | Physical security perimeters | Facilities Lead | Security Operations Lead | Planned |  | Site diagrams; access configs | [Annex A](../coordination/catalogs/ISO27001-AnnexA.md) |
| A.7.2 | Physical entry | Facilities Lead | Site Security | Planned |  | Badge/kiosk logs; visitor logs | [Annex A](../coordination/catalogs/ISO27001-AnnexA.md) |
| A.7.3 | Securing offices, rooms and facilities | Facilities Lead | Security Operations Lead | Planned |  | Photos; inspections | [Annex A](../coordination/catalogs/ISO27001-AnnexA.md) |
| A.7.4 | Physical security monitoring | Facilities Lead | Security Operations Lead | Planned |  | CCTV exports; retention | [Annex A](../coordination/catalogs/ISO27001-AnnexA.md) |
| A.7.5 | Protecting against physical and environmental threats | Facilities Lead | DC Ops | Planned |  | Alarms; thresholds | [Annex A](../coordination/catalogs/ISO27001-AnnexA.md) |
| A.7.6 | Working in secure areas | Facilities Lead | NOC Manager | Planned |  | SOP adherence | [Annex A](../coordination/catalogs/ISO27001-AnnexA.md) |
| A.7.7 | Clear desk and clear screen | ISMS Manager | Facilities Lead | Planned |  | Floor walk results | [Annex A](../coordination/catalogs/ISO27001-AnnexA.md) |
| A.7.8 | Equipment siting and protection | Facilities Lead | IT Operations Lead | Planned |  | Rack diagrams; controls | [Annex A](../coordination/catalogs/ISO27001-AnnexA.md) |
| A.7.9 | Security of assets off-premises | IT Operations Lead | ISMS Manager | Planned |  | Loaner/MDM logs | [Annex A](../coordination/catalogs/ISO27001-AnnexA.md) |
| A.7.10 | Storage media | ISMS Manager | IT Operations Lead | Planned |  | Disposal certs; wipe logs | [Annex A](../coordination/catalogs/ISO27001-AnnexA.md) |
| A.7.11 | Supporting utilities | Facilities Lead | DC Ops | Planned |  | UPS/Gen tests | [Annex A](../coordination/catalogs/ISO27001-AnnexA.md) |
| A.7.12 | Cabling security | Facilities Lead | Network Engineering | Planned |  | Cable routes; protection | [Annex A](../coordination/catalogs/ISO27001-AnnexA.md) |
| A.7.13 | Equipment maintenance | Facilities Lead | DC Ops | Planned |  | Maintenance logs | [Annex A](../coordination/catalogs/ISO27001-AnnexA.md) |
| A.7.14 | Secure disposal or re-use of equipment | ISMS Manager | IT Operations Lead | Planned |  | Sanitization records | [Annex A](../coordination/catalogs/ISO27001-AnnexA.md) |
| A.8.1 | User end point devices | IT Operations Lead | Security Engineering Lead | Planned |  | EDR; encryption; backups | [Annex A](../coordination/catalogs/ISO27001-AnnexA.md) |
| A.8.2 | Privileged access rights | Security Engineering Lead | Security Operations Lead | Planned |  | PAM approvals; sessions | [Annex A](../coordination/catalogs/ISO27001-AnnexA.md) |
| A.8.3 | Information access restriction | Security Engineering Lead | ISMS Manager | Planned |  | RBAC matrices | [Annex A](../coordination/catalogs/ISO27001-AnnexA.md) |
| A.8.4 | Access to source code | Product Engineering Lead | Security Engineering Lead | Planned |  | Repo ACLs; approvals | [Annex A](../coordination/catalogs/ISO27001-AnnexA.md) |
| A.8.5 | Secure authentication | Security Engineering Lead | ISMS Manager | Planned |  | MFA policies; logs | [Annex A](../coordination/catalogs/ISO27001-AnnexA.md) |
| A.8.6 | Capacity management | IT Operations Lead | ISMS Manager | Planned |  | Utilization dashboards | [Annex A](../coordination/catalogs/ISO27001-AnnexA.md) |
| A.8.7 | Protection against malware | IT Operations Lead | Security Engineering Lead | Planned |  | AV/EDR status | [Annex A](../coordination/catalogs/ISO27001-AnnexA.md) |
| A.8.8 | Management of technical vulnerabilities | Security Engineering Lead | IT Operations Lead | Planned |  | Scans; SLAs; tickets | [Annex A](../coordination/catalogs/ISO27001-AnnexA.md) |
| A.8.9 | Configuration management | IT Operations Lead | ISMS Manager | Planned |  | Baselines; drift reports | [Annex A](../coordination/catalogs/ISO27001-AnnexA.md) |
| A.8.10 | Information deletion | ISMS Manager | IT Operations Lead | Planned |  | Deletion logs; tickets | [Annex A](../coordination/catalogs/ISO27001-AnnexA.md) |
| A.8.11 | Data masking | Product Engineering Lead | Security Engineering Lead | Planned |  | Masking configs; queries | [Annex A](../coordination/catalogs/ISO27001-AnnexA.md) |
| A.8.12 | Data leakage prevention | Security Engineering Lead | ISMS Manager | Planned |  | DLP policies; alerts | [Annex A](../coordination/catalogs/ISO27001-AnnexA.md) |
| A.8.13 | Information backup | BC/DR Lead | IT Operations Lead | Planned |  | Backup jobs; restore tests; immutability | [Annex A](../coordination/catalogs/ISO27001-AnnexA.md) |
| A.8.14 | Redundancy of processing facilities | IT Operations Lead | BC/DR Lead | Planned |  | HA configs; failover tests | [Annex A](../coordination/catalogs/ISO27001-AnnexA.md) |
| A.8.15 | Logging | Security Operations Lead | Security Engineering Lead | Planned |  | Retention configs; exports | [Annex A](../coordination/catalogs/ISO27001-AnnexA.md) |
| A.8.16 | Monitoring activities | Security Operations Lead | GRC Analyst | Planned |  | Alert SLAs; tuning records | [Annex A](../coordination/catalogs/ISO27001-AnnexA.md) |
| A.8.17 | Clock synchronization | Security Operations Lead | IT Operations Lead | Planned |  | NTP config; skew reports | [Annex A](../coordination/catalogs/ISO27001-AnnexA.md) |
| A.8.18 | Use of privileged utility programs | Security Engineering Lead | ISMS Manager | Planned |  | Allow‑list; audit logs | [Annex A](../coordination/catalogs/ISO27001-AnnexA.md) |
| A.8.19 | Installation of software on operational systems | IT Operations Lead | Product Engineering Lead | Planned |  | Change approvals; UAT | [Annex A](../coordination/catalogs/ISO27001-AnnexA.md) |
| A.8.20 | Networks security | Security Engineering Lead | Network Engineering | Planned |  | Firewall baselines; configs | [Annex A](../coordination/catalogs/ISO27001-AnnexA.md) |
| A.8.21 | Security of network services | Security Engineering Lead | Network Engineering | Planned |  | Provider SLAs; configs | [Annex A](../coordination/catalogs/ISO27001-AnnexA.md) |
| A.8.22 | Segregation of networks | Security Engineering Lead | Network Engineering | Planned |  | Network maps; policies | [Annex A](../coordination/catalogs/ISO27001-AnnexA.md) |
| A.8.23 | Web filtering | Security Engineering Lead | IT Operations Lead | Planned |  | URL policy; logs | [Annex A](../coordination/catalogs/ISO27001-AnnexA.md) |
| A.8.24 | Use of cryptography | ISMS Manager | Security Engineering Lead | Planned |  | Keystore configs; rotations | [Annex A](../coordination/catalogs/ISO27001-AnnexA.md) |
| A.8.25 | Secure development life cycle | Product Engineering Lead | Security Engineering Lead | Planned |  | SDLC gates; sign‑offs | [Annex A](../coordination/catalogs/ISO27001-AnnexA.md) |
| A.8.26 | Application security requirements | Product Engineering Lead | ISMS Manager | Planned |  | Security requirements docs | [Annex A](../coordination/catalogs/ISO27001-AnnexA.md) |
| A.8.27 | Secure system architecture and engineering principles | Product Engineering Lead | Security Engineering Lead | Planned |  | Architecture reviews | [Annex A](../coordination/catalogs/ISO27001-AnnexA.md) |
| A.8.28 | Secure coding | Product Engineering Lead | Security Engineering Lead | Planned |  | Code review records | [Annex A](../coordination/catalogs/ISO27001-AnnexA.md) |
| A.8.29 | Security testing in development and acceptance | Product Engineering Lead | Security Engineering Lead | Planned |  | Test reports; gates | [Annex A](../coordination/catalogs/ISO27001-AnnexA.md) |
| A.8.30 | Outsourced development | Product Engineering Lead | Procurement | Planned |  | Contracts; oversight records | [Annex A](../coordination/catalogs/ISO27001-AnnexA.md) |
| A.8.31 | Separation of development, test and production environments | Product Engineering Lead | Security Engineering Lead | Planned |  | Env ACLs; pipelines | [Annex A](../coordination/catalogs/ISO27001-AnnexA.md) |
| A.8.32 | Change management | ISMS Manager | IT Operations Lead | Planned |  | Change tickets; approvals | [Annex A](../coordination/catalogs/ISO27001-AnnexA.md) |
| A.8.33 | Test information | Product Engineering Lead | Privacy Officer | Planned |  | Synthetic/anonymized data logs | [Annex A](../coordination/catalogs/ISO27001-AnnexA.md) |
| A.8.34 | Protection of IS during audit testing | ISMS Manager | Internal Audit | Planned |  | Test plans; approvals | [Annex A](../coordination/catalogs/ISO27001-AnnexA.md) |

## 6. ISO 27001 – Detailed Implementation Checklists (all controls)

### A.5.1 Policies for information security (Owner: ISMS Manager)

- [ ] Review and approve `P01 Information Security Policy` and `P34 Quality & Document Control` in current cycle
- [ ] Publish and notify all personnel; record communication evidence
- [ ] Ensure policy references to Entra SSO, Duo for SSH/RDP, cloud-first posture are current
- [ ] File approvals and revision history in repo; link to evidence folder

Evidence: signed approval, comms export, repo revision log

### A.5.2 Information security roles and responsibilities (Owner: ISMS Manager)

- [ ] Update RACI covering ISMS, SecOps, IT Ops, BC/DR, Facilities, Finance
- [ ] Post RACI; obtain acknowledgement from role owners
- [ ] Link RACI into `P01` and onboarding pack

Evidence: RACI document, acknowledgements

### A.5.3 Segregation of duties (Owner: ISMS Manager; Support: Finance Controller)

- [ ] Maintain SoD matrix across engineering, operations, finance
- [ ] Implement SoD checks in access reviews; document exceptions in PR44 workflow

Evidence: SoD matrix, exception approvals

### A.5.4 Management responsibilities (Owner: ISMS Manager)

- [ ] Issue directive requiring adherence to policies and procedures
- [ ] Embed requirements into onboarding and manager training
- [ ] Track and review compliance quarterly

Evidence: communications, training logs

### A.5.5 Contact with authorities (Owner: Security Operations Lead)

- [ ] Maintain contact registry (LE, CERT, regulators)
- [ ] Test notification pathways annually
- [ ] Store notification evidence

Evidence: registry, test artifacts

### A.5.6 Contact with special interest groups (Owner: ISMS Manager)

- [ ] Join relevant security forums/ISACs
- [ ] Subscribe to advisories; integrate into TI

Evidence: memberships, intake workflows

### A.5.7 Threat intelligence (Owner: Security Operations Lead)

- [ ] Enable TI feeds in SIEM
- [ ] Document detection updates from TI

Evidence: feed configs; rule changes

### A.5.8 Information security in project management (Owner: Product Engineering Lead)

- [ ] Establish security checkpoints in project lifecycle (design, build, test, release)
- [ ] Require threat models for new systems and major changes; record mitigations
- [ ] Embed security acceptance criteria in project charters and release gates

Evidence: design reviews; threat models; release gate records

### A.5.9 Inventory of information and assets (Owner: IT Operations Lead)

- [ ] Maintain CMDB with owners/classification
- [ ] Reconcile quarterly

Evidence: CMDB exports; reconciliation logs

### A.5.10 Acceptable use (Owner: ISMS Manager)

- [ ] Publish `P07 Acceptable Use` and obtain acknowledgements from all personnel
- [ ] Implement technical enforcement (screen lock, removable media, web filtering) per S01/S05
- [ ] Include AUP in onboarding and annual re-acknowledgement campaigns
- [ ] Monitor compliance and take disciplinary action per A.6.4 when necessary

Evidence: acknowledgement reports; device policy configs; campaign records; disciplinary logs

### A.5.23 Cloud services security (Owner: Security Engineering Lead)

- [ ] Enforce SSO/MFA to control planes
- [ ] Apply S22 guardrails via IaC; drift monitors
- [ ] Complete vendor DDQs; archive results

Evidence: IaC reports; SSO; DDQs

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

- [ ] Maintain encrypted, immutable backups for critical systems; test quarterly restores
- [ ] Validate restore RTO/RPO; document results and corrective actions

Evidence: backup job reports; restore logs; immutability configs; test summaries

### A.8.15–A.8.17 Logging, monitoring, time (Owner: Security Operations Lead)

- [ ] Onboard sources to SIEM; document manual export cadence for non‑forwarding systems
- [ ] Define/measure alert SLAs; maintain tuning records
- [ ] Enforce NTP to approved sources; capture skew reports

Evidence: SIEM onboarding/tuning; exports; NTP reports

### A.5.31 Legal, statutory, regulatory and contractual requirements (Owner: ISMS Manager)

- [ ] Maintain obligations register; assign owners
- [ ] Review updates quarterly; record impacts

Evidence: register; impact notes

### A.5.32 Intellectual property rights (Owner: Legal)

- [ ] Define IPR protection procedures
- [ ] Enforce access controls and license compliance

Evidence: procedures; access logs

### A.5.33 Protection of records (Owner: ISMS Manager)

- [ ] Implement retention schedules; access restrictions
- [ ] Test retrieval and integrity

Evidence: retrieval tests; access logs

### A.5.34 Privacy and protection of PII (Owner: Privacy Officer)

- [ ] Conduct DPIAs; track mitigations
- [ ] Enforce DLP and encryption as needed

Evidence: DPIAs; DLP/encryption logs

### A.5.35 Independent review of information security (Owner: Internal Audit)

- [ ] Plan and execute IS audits; report results
- [ ] Track CAPA to closure

Evidence: IA reports; CAPA tracker

### A.5.36 Compliance with IS policies, rules and standards (Owner: Internal Audit)

- [ ] Perform periodic compliance reviews
- [ ] Report deviations and remediation

Evidence: review reports

### A.5.37 Documented operating procedures (Owner: IT Operations Lead)

- [ ] Maintain SOP repository; approvals
- [ ] Validate procedures annually

Evidence: SOP list; approvals

### A.6.2 Terms and conditions of employment (Owner: HR Delegate)

- [ ] Embed IS clauses in contracts
- [ ] Capture acknowledgements (AUP, policies)

Evidence: signed contracts; acks

### A.6.3 IS awareness, education and training (Owner: ISMS Manager)

- [ ] Maintain curriculum; role-based modules
- [ ] Track attendance and effectiveness

Evidence: R13 exports; quiz results

### A.6.4 Disciplinary process (Owner: HR Delegate)

- [ ] Publish disciplinary policy for IS violations
- [ ] Record actions taken

Evidence: HR records

### A.6.5 Responsibilities after termination or change (Owner: HR Delegate)

- [ ] Define post-termination obligations
- [ ] Validate deprovisioning and asset return

Evidence: exit checklist; logs

### A.6.6 Confidentiality or NDAs (Owner: HR Delegate; Privacy Officer)

- [ ] Maintain NDA templates; signatures
- [ ] Review NDA coverage annually

Evidence: NDA archive

### A.6.8 IS event reporting (Owner: Security Operations Lead)

- [ ] Provide reporting mechanism and training
- [ ] Track reports and time-to-triage

Evidence: tickets; metrics

### A.7.3 Securing offices, rooms and facilities (Owner: Facilities Lead)

- [ ] Implement physical controls per S17
- [ ] Periodic inspections and remediation

Evidence: inspection logs

### A.7.4 Physical security monitoring (Owner: Facilities Lead)

- [ ] Maintain CCTV retention and export procedure
- [ ] Validate coverage periodically

Evidence: exports; coverage map

### A.7.5 Protecting against physical/environmental threats (Owner: Facilities Lead)

- [ ] Set thresholds and alarms (S16)
- [ ] Test power/cooling redundancy

Evidence: threshold logs; test reports

### A.7.6 Working in secure areas (Owner: Facilities Lead)

- [ ] Define secure area SOPs; train staff
- [ ] Monitor compliance

Evidence: SOP; training; audits

### A.7.7 Clear desk and clear screen (Owner: ISMS Manager)

- [ ] Publish rules; conduct periodic spot checks in offices and NOCs
- [ ] Enforce auto-lock policies; prohibit unattended unlocked sessions

Evidence: spot check results; GPO/MEM policy exports

### A.7.8 Equipment siting and protection (Owner: Facilities Lead)

- [ ] Secure siting (access path control, rack locking) and environmental safeguards
- [ ] Document and review siting risks; remediate deficiencies

Evidence: photos; site diagrams; remediation tickets

### A.7.9 Security of assets off‑premises (Owner: IT Operations Lead)

- [ ] Enforce MDM; track loaners

Evidence: MDM reports; logs

### A.7.10 Storage media (Owner: ISMS Manager)

- [ ] Manage media lifecycle (acquisition, use, transport, disposal) per classification
- [ ] Enforce encryption for portable media; prohibit unapproved devices
- [ ] Maintain chain-of-custody for off-site transfers

Evidence: media inventory logs; encryption policy; disposal certificates; transfer records

### A.7.11 Supporting utilities (Owner: Facilities Lead)

- [ ] Maintain UPS/generator; test per schedule and document outcomes
- [ ] Implement dual power paths where feasible; monitor alarms

Evidence: maintenance schedule; test logs; alarm history

### A.7.12 Cabling security (Owner: Facilities Lead)

- [ ] Protect power/data cabling against interception/interference; secure conduits
- [ ] Maintain and review cable route diagrams; control access to risers

Evidence: as-built drawings; inspection reports; access logs

### A.7.13 Equipment maintenance (Owner: Facilities Lead)

- [ ] Perform scheduled maintenance; retain vendor service reports
- [ ] Verify maintenance does not compromise security (post-maintenance checks)

Evidence: maintenance tickets; vendor reports; post-check records

### A.7.14 Secure disposal or re‑use (Owner: ISMS Manager)

- [ ] Sanitization SOP; verification

Evidence: wipe logs; certs

### A.8.1 User end point devices (Owner: IT Operations Lead)

- [ ] Enforce EDR, encryption, backups (iDrive360)
- [ ] Monitor compliance

Evidence: EDR/encryption; backup success

### A.8.2 Privileged access rights (Owner: Security Engineering Lead)

- [ ] Duo MFA; per‑use elevation; session recording

Evidence: Duo; session records

### A.8.3 Information access restriction (Owner: Security Engineering Lead)

- [ ] RBAC matrices; periodic reviews

Evidence: RBAC; review logs

### A.8.4 Access to source code (Owner: Product Engineering Lead)

- [ ] Restrict read/write; require reviews

Evidence: repo ACLs; PR history

### A.8.5 Secure authentication (Owner: Security Engineering Lead)

- [ ] Strong auth policies; session controls

Evidence: policy; system configs

### A.8.6 Capacity management (Owner: IT Operations Lead)

- [ ] Monitor capacity/utilization for compute, storage, network; set thresholds
- [ ] Plan scaling actions; document performance tests before major changes

Evidence: capacity dashboards; threshold alerts; test plans

### A.8.7 Protection against malware (Owner: IT Operations Lead)

- [ ] Enforce AV/EDR baselines on all endpoints/servers; block unapproved executables
- [ ] Run phishing/awareness campaigns; track remediation for detections

Evidence: AV/EDR compliance reports; awareness results; incident tickets

### A.8.8 Management of technical vulnerabilities (Owner: Security Engineering Lead)

- [ ] Run authenticated scans for hosts, containers, apps; prioritize per S13 SLAs
- [ ] Integrate patching workflows; verify remediation via re-scan
- [ ] Track documented exceptions with risk acceptance and expiry

Evidence: scan results; remediation tickets; SLA dashboards; exception register

### A.8.14 Redundancy of processing facilities (Owner: IT Operations Lead)

- [ ] Implement HA; document failover

Evidence: HA configs; tests

### A.8.18 Use of privileged utility programs (Owner: Security Engineering Lead)

- [ ] Maintain allow-list of utilities; restrict execution to admins with MFA
- [ ] Review utility use logs monthly; revoke unused/abused tools

Evidence: allow‑list; utility audit logs; review records

### A.8.19 Installation of software on operational systems (Owner: IT Operations Lead)

- [ ] Enforce controlled installs via PR07/PR09; require approvals and UAT
- [ ] Maintain software inventory and provenance for operational systems

Evidence: change tickets; UAT evidence; software inventory exports

### A.8.20 Networks security (Owner: Security Engineering Lead)

- [ ] Baseline firewall/WAF configs; restrict admin ingress to NOC networks
- [ ] Periodically review and recertify network rules; remove stale entries

Evidence: configuration exports; rule review records

### A.8.21 Security of network services (Owner: Security Engineering Lead)

- [ ] Validate provider security features and SLAs; document encryption and isolation
- [ ] Monitor provider performance/security reports; escalate deviations

Evidence: contracts; provider attestations; monitoring reports

### A.8.22 Segregation of networks (Owner: Security Engineering Lead)

- [ ] Enforce default‑deny; segment management, control, tenant/data, guest
- [ ] Validate segmentation via tests and monitoring; block lateral movement

Evidence: segmentation policies; diagrams; test reports

### A.8.23 Web filtering (Owner: Security Engineering Lead)

- [ ] Enforce URL filtering; categorize sites; block malicious content
- [ ] Review and expire exceptions; monitor usage patterns

Evidence: proxy logs; exception approvals; review records

### A.8.24 Use of cryptography (Owner: ISMS Manager)

- [ ] Define approved algorithms and key management rules; enforce rotation cadences
- [ ] Protect keys in vault/HSM; implement separation of duties for key ops

Evidence: key/cert inventory; rotation logs; HSM/vault configs

### A.8.25 Secure development life cycle (Owner: Product Engineering Lead)

- [ ] Implement secure SDLC with sign‑offs at design, code review, test, release
- [ ] Track security debt and remediation in backlog

Evidence: SDLC checklists; backlog reports

### A.8.26 Application security requirements (Owner: Product Engineering Lead)

- [ ] Define and approve security requirements per system; map to risks and standards
- [ ] Review requirements at each major release; update as needed

Evidence: requirement specs; review minutes

### A.8.27 Secure system architecture and engineering principles (Owner: Product Engineering Lead)

- [ ] Establish secure architecture principles; apply to all new systems
- [ ] Perform architecture reviews and threat models; track mitigations

Evidence: principles doc; review records; models

### A.8.28 Secure coding (Owner: Product Engineering Lead)

- [ ] Enforce secure coding standards and linters; prevent high‑risk patterns
- [ ] Train developers annually on secure coding

Evidence: code review results; SAST/DAST scans; training records

### A.8.29 Security testing in development and acceptance (Owner: Product Engineering Lead)

- [ ] Define security testing processes (SAST, DAST, pen test as needed)
- [ ] Enforce release gates tied to severity thresholds

Evidence: test reports; gate approvals

### A.8.30 Outsourced development (Owner: Product Engineering Lead)

- [ ] Direct, monitor, review vendor development; require security clauses
- [ ] Validate vendor controls and deliverable quality before acceptance

Evidence: contracts; oversight logs; acceptance reviews

### A.8.31 Separation of development, test and production environments (Owner: Product Engineering Lead)

- [ ] Separate environments; restrict access via least privilege
- [ ] Prevent production data in lower environments unless masked/anonymized

Evidence: ACLs; configs; masking evidence

### A.8.32 Change management (Owner: ISMS Manager)

- [ ] Enforce PR07/PR09 with documented approvals, testing, and rollback
- [ ] Perform change reviews; track emergency changes distinctly

Evidence: change records; CAB minutes; emergency change logs

### A.8.33 Test information (Owner: Product Engineering Lead)

- [ ] Use anonymized/synthetic data; restrict access and retention
- [ ] Periodically purge test data per retention policy

Evidence: data catalogs; access logs; purge records

### A.8.34 Protection of IS during audit testing (Owner: ISMS Manager)

- [ ] Plan/agree audit tests to avoid impact; define windows and backout
- [ ] Monitor tests in real time; capture deviations and lessons learned

Evidence: approved plans; monitoring logs; PIR notes

---

Future work: Add remaining Annex A controls to the matrix and detailed checklists, then proceed with ISO 22301, SOC 2, and SOC 1 sections.


