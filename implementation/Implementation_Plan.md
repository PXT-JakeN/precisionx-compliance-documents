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

- [ ] Review and approve [P01 Information Security Policy](../policies/Information-Security-Policy.md) and [P34 Quality & Document Control](../policies/Quality-and-Document-Control-Policy.md) in current cycle
- [ ] Publish and notify all personnel; record communication evidence
- [ ] Ensure policy references to Entra SSO, Duo for SSH/RDP, cloud-first posture are current
- [ ] File approvals and revision history in repo; link to evidence folder

Evidence: signed approval, comms export, repo revision log

### A.5.2 Information security roles and responsibilities (Owner: ISMS Manager)

- [ ] Update RACI covering ISMS, SecOps, IT Ops, BC/DR, Facilities, Finance
- [ ] Post RACI; obtain acknowledgement from role owners
- [ ] Link RACI into [P01 Information Security Policy](../policies/Information-Security-Policy.md) and onboarding pack

Evidence: RACI document, acknowledgements

### A.5.3 Segregation of duties (Owner: ISMS Manager; Support: Finance Controller)

- [ ] Maintain SoD matrix across engineering, operations, finance; align to [P35 Segregation of Duties](../policies/Segregation-of-Duties-Policy.md)
- [ ] Implement SoD checks in access reviews; document exceptions in [PR44 Exception & Compensating Controls](../procedures/Exception-and-Compensating-Controls-Procedure.md)

Evidence: SoD matrix, exception approvals

### A.5.4 Management responsibilities (Owner: ISMS Manager)

- [ ] Issue directive requiring adherence to policies and procedures
- [ ] Embed requirements into onboarding and manager training
- [ ] Track and review compliance quarterly

Evidence: communications, training logs; references in [P01](../policies/Information-Security-Policy.md)

### A.5.5 Contact with authorities (Owner: Security Operations Lead)

- [ ] Maintain contact registry (LE, CERT, regulators)
- [ ] Test notification pathways annually
- [ ] Store notification evidence

Evidence: registry, test artifacts; references in [P22 Incident Response](../policies/Incident-Response-Policy.md)

### A.5.6 Contact with special interest groups (Owner: ISMS Manager)

- [ ] Join relevant security forums/ISACs
- [ ] Subscribe to advisories; integrate into TI

Evidence: memberships, intake workflows; TI intake in [P21 Logging/Monitoring & SIEM](../policies/Logging-Monitoring-and-SIEM-Policy.md)

### A.5.7 Threat intelligence (Owner: Security Operations Lead)

- [ ] Enable TI feeds in SIEM
- [ ] Document detection updates from TI

Evidence: feed configs; rule changes; references in [P21](../policies/Logging-Monitoring-and-SIEM-Policy.md)

### A.5.8 Information security in project management (Owner: Product Engineering Lead)

- [ ] Establish security checkpoints in project lifecycle (design, build, test, release)
- [ ] Require threat models for new systems and major changes; record mitigations
- [ ] Embed security acceptance criteria in project charters and release gates

Evidence: design reviews; threat models; release gate records; mapped in [P18 Secure SDLC](../policies/Secure-Software-Development-Policy.md)

### A.5.9 Inventory of information and assets (Owner: IT Operations Lead)

- [ ] Maintain CMDB with owners/classification
- [ ] Reconcile quarterly

Evidence: CMDB exports; reconciliation logs; see [R02 Asset Inventory & CMDB](../plans/Asset-Inventory-and-CMDB.md), [PR10 Configuration Management](../procedures/Configuration-Management-Procedure.md)

### A.5.10 Acceptable use (Owner: ISMS Manager)

- [ ] Publish `P07 Acceptable Use` and obtain acknowledgements from all personnel
- [ ] Implement technical enforcement (screen lock, removable media, web filtering) per S01/S05
- [ ] Include AUP in onboarding and annual re-acknowledgement campaigns
- [ ] Monitor compliance and take disciplinary action per A.6.4 when necessary

Evidence: acknowledgement reports; device policy configs; campaign records; disciplinary logs; see [P07 Acceptable Use](../policies/Acceptable-Use-Policy.md), [S01 Workstation Baseline](../standards/Workstation-Baseline.md), [S05 Firewall/WAF](../standards/Firewall-and-WAF-Standard.md)

### A.5.23 Cloud services security (Owner: Security Engineering Lead)

- [ ] Enforce SSO/MFA to control planes
- [ ] Apply S22 guardrails via IaC; drift monitors
- [ ] Complete vendor DDQs; archive results

Evidence: IaC reports; SSO; DDQs; see [P15 Cloud Security](../policies/Cloud-Security-Policy.md), [S22 Cloud Landing Zone](../standards/Cloud-Landing-Zone-Standard.md), [T06 Vendor DDQ](../templates/Vendor-Due-Diligence-Questionnaire.md)

### A.5.24–A.5.28 Incident readiness, triage, response, lessons, evidence (Owner: Security Operations Lead)

- [ ] Maintain IR plan, roles, contact lists (P22/PL07)
- [ ] Implement triage workflow and severity scheme (PR20)
- [ ] Keep runbooks up to date (PR13/14/15/16/17)
- [ ] Capture PIRs and CAPA; maintain evidence collection SOP (PR18)

Evidence: incident tickets, PIRs, CAPA, chain-of-custody; see [P22 IR Policy](../policies/Incident-Response-Policy.md), [PL07 Playbooks](../plans/Incident-Playbooks.md), [PR20 Triage](../procedures/Alert-Triage-and-Escalation-Procedure.md), [PR18 Forensics](../procedures/Forensics-and-Evidence-Handling-SOP.md)

### A.5.29–A.5.30 IS during disruption; ICT readiness (Owner: BC/DR Lead)

- [ ] Ensure IS constraints in crisis/continuity plans (PL11/PL05)
- [ ] Test failover; verify logging/time sync post‑failover

Evidence: exercise reports, failover logs; see [PL11 Crisis Management](../plans/Crisis-Management-Plan.md), [PL05 DR Plans](../plans/Disaster-Recovery-Plans.md)

### A.6.1 Screening (Owner: HR Delegate)

- [ ] Apply background checks proportional to roles; retain proof
- [ ] Integrate checks into onboarding checklist (PR06)

Evidence: screening confirmations; see [PR06 Onboarding & Offboarding](../procedures/Onboarding-and-Offboarding-Procedure.md)

### A.6.7 Remote working (Owner: Security Engineering Lead)

- [ ] Enforce device posture, VPN, Duo MFA; sensitivity label limits for BYOD
- [ ] Review posture exceptions quarterly

Evidence: device compliance, VPN/MFA logs; see [P11 Remote Work / WFH](../policies/Remote-Work-Security-Policy.md), [P62 Remote Access](../policies/Remote-Access-Policy.md), [S01 Workstation Baseline](../standards/Workstation-Baseline.md)

### A.7.1–A.7.2 Physical perimeters and entry (Owner: Facilities Lead)

- [ ] Implement portal/kiosk 3‑factor; escort limits; guard fallback
- [ ] Export badge/visitor logs to evidence store

Evidence: access configs, exported logs; see [S17 Facility Physical Security](../standards/Facility-Physical-Security-Standard.md), [PR35 Visitor Management](../procedures/Visitor-Management-Procedure.md)

### A.8.1 Endpoints; A.8.2 Privileged access (Owners: IT Ops Lead; Security Engineering Lead)

- [ ] Enforce EDR, full‑disk encryption, iDrive360 backups
- [ ] Require Duo for SSH/RDP; record privileged sessions where feasible

Evidence: EDR/encryption reports; Duo/session records; see [P12 Endpoint Security](../policies/Endpoint-Security-Policy.md), [S01 Workstation Baseline](../standards/Workstation-Baseline.md), [P10 PAM](../policies/Privileged-Access-Management-Policy.md), [S06 Identity & PAM](../standards/Identity-and-PAM-Standard.md)

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

Evidence: SIEM onboarding/tuning; exports; NTP reports; see [P21 Logging/Monitoring & SIEM](../policies/Logging-Monitoring-and-SIEM-Policy.md), [S07 Logging & Time Sync](../standards/Logging-and-Time-Sync-Standard.md), [PR19 SIEM Onboarding](../procedures/Logging-and-SIEM-Onboarding-Procedure.md)

### A.5.31 Legal, statutory, regulatory and contractual requirements (Owner: ISMS Manager)

- [ ] Maintain obligations register; assign owners
- [ ] Review updates quarterly; record impacts

Evidence: register; impact notes; see [P63 Legal & Regulatory Compliance](../policies/Legal-and-Regulatory-Compliance-Policy.md)

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

Evidence: DPIAs; DLP/encryption logs; see [P31 Privacy & Data Protection](../policies/Privacy-and-Data-Protection-Policy.md), [S24 DLP](../standards/Data-Loss-Prevention-Standard.md)

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

Evidence: capacity dashboards; threshold alerts; test plans; see [P44 Capacity & Performance](../policies/Capacity-and-Performance-Management-Policy.md)

### A.8.7 Protection against malware (Owner: IT Operations Lead)

- [ ] Enforce AV/EDR baselines on all endpoints/servers; block unapproved executables
- [ ] Run phishing/awareness campaigns; track remediation for detections

Evidence: AV/EDR compliance reports; awareness results; incident tickets

### A.8.8 Management of technical vulnerabilities (Owner: Security Engineering Lead)

- [ ] Run authenticated scans for hosts, containers, apps; prioritize per S13 SLAs
- [ ] Integrate patching workflows; verify remediation via re-scan
- [ ] Track documented exceptions with risk acceptance and expiry

Evidence: scan results; remediation tickets; SLA dashboards; exception register; see [P20 Vulnerability & Patch Mgmt](../policies/Vulnerability-and-Patch-Management-Policy.md), [S23 Vulnerability Scanning](../standards/Vulnerability-Scanning-Standard.md), [S13 Severity & SLA](../standards/Vulnerability-Severity-and-SLA-Standard.md)

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

## 7. Master Document Implementation Tracker (all documents)

This section ensures every document in the library is implemented, communicated, and evidenced. Use the per-type checklist
below for each row and record status/proof as you go.

### 7.1 Per‑Type Implementation Checklists

Policies (apply to P##):

- [ ] Review and approve policy (latest version in repo)
- [ ] Publish and communicate to all applicable personnel; collect acknowledgements
- [ ] Train impacted roles (add to curriculum if recurring)
- [ ] Implement technical/process changes required by the policy
- [ ] Store approvals, comms, training, and configuration evidence in the evidence repository

Standards (apply to S##):

- [ ] Review and approve standard; align with policy
- [ ] Implement configurations/baselines; capture exports/screenshots
- [ ] Validate and report compliance; raise exceptions where needed (PR44)
- [ ] File approvals and evidence

Procedures/Runbooks (apply to PR##):

- [ ] Review and approve procedure; publish in runbook location
- [ ] Integrate into ITSM workflows; train operators
- [ ] Record first successful use or test; collect tickets/records as evidence

Plans/Narratives (apply to PL## and SD##):

- [ ] Review and approve plan/narrative
- [ ] Execute initial cycle (exercise/audit/assessment as applicable); store reports

Registers/Logs/Inventories (apply to R##):

- [ ] Stand up and populate register/log/inventory structure
- [ ] Record initial entries; define update cadence

Templates (apply to T##):

- [ ] Review and approve template; publish location
- [ ] Use in first live instance; capture completed artifact

### 7.2 Policies (P##)

| Doc ID | Title | Path | Owner | Status | Target Date |
|--------|-------|------|-------|--------|-------------|
| P01 | Information Security Policy (ISMS Charter) | [policies/Information-Security-Policy.md](../policies/Information-Security-Policy.md) | ISMS Manager |  |  |
| P02 | ISMS Scope & Context Policy | [policies/ISMS-Scope-and-Context-Policy.md](../policies/ISMS-Scope-and-Context-Policy.md) | ISMS Manager |  |  |
| P03 | Risk Management Policy | [policies/Risk-Management-Policy.md](../policies/Risk-Management-Policy.md) | ISMS Manager |  |  |
| P04 | Statement of Applicability (SoA) | [policies/Statement-of-Applicability.md](../policies/Statement-of-Applicability.md) | GRC Analyst |  |  |
| P05 | Asset Management Policy | [policies/Asset-Management-Policy.md](../policies/Asset-Management-Policy.md) | ISMS Manager |  |  |
| P06 | Data Classification & Handling Policy | [policies/Data-Classification-and-Handling-Policy.md](../policies/Data-Classification-and-Handling-Policy.md) | ISMS Manager |  |  |
| P07 | Acceptable Use Policy | [policies/Acceptable-Use-Policy.md](../policies/Acceptable-Use-Policy.md) | ISMS Manager |  |  |
| P08 | Identity & Access Management Policy | [policies/Identity-and-Access-Management-Policy.md](../policies/Identity-and-Access-Management-Policy.md) | Security Engineering Lead |  |  |
| P09 | Authentication & MFA Policy | [policies/Authentication-and-MFA-Policy.md](../policies/Authentication-and-MFA-Policy.md) | Security Engineering Lead |  |  |
| P10 | Privileged Access Management Policy | [policies/Privileged-Access-Management-Policy.md](../policies/Privileged-Access-Management-Policy.md) | Security Engineering Lead |  |  |
| P11 | Remote Work / WFH Security Policy | [policies/Remote-Work-Security-Policy.md](../policies/Remote-Work-Security-Policy.md) | ISMS Manager |  |  |
| P12 | Endpoint Security Policy | [policies/Endpoint-Security-Policy.md](../policies/Endpoint-Security-Policy.md) | ISMS Manager |  |  |
| P13 | Mobile Device & BYOD Policy | [policies/Mobile-Device-and-BYOD-Policy.md](../policies/Mobile-Device-and-BYOD-Policy.md) | ISMS Manager |  |  |
| P14 | Network Security Policy | [policies/Network-Security-Policy.md](../policies/Network-Security-Policy.md) | Security Engineering Lead |  |  |
| P15 | Cloud Security Policy | [policies/Cloud-Security-Policy.md](../policies/Cloud-Security-Policy.md) | Security Engineering Lead |  |  |
| P16 | Cryptography & Key Management Policy | [policies/Cryptography-and-Key-Management-Policy.md](../policies/Cryptography-and-Key-Management-Policy.md) | ISMS Manager |  |  |
| P17 | Secure Configuration & Hardening Policy | [policies/Secure-Configuration-and-Hardening-Policy.md](../policies/Secure-Configuration-and-Hardening-Policy.md) | ISMS Manager |  |  |
| P18 | Secure Software Development Policy | [policies/Secure-Software-Development-Policy.md](../policies/Secure-Software-Development-Policy.md) | Product Engineering Lead |  |  |
| P19 | Change & Release Management Policy | [policies/Change-and-Release-Management-Policy.md](../policies/Change-and-Release-Management-Policy.md) | IT Operations Lead |  |  |
| P20 | Vulnerability & Patch Management Policy | [policies/Vulnerability-and-Patch-Management-Policy.md](../policies/Vulnerability-and-Patch-Management-Policy.md) | Security Engineering Lead |  |  |
| P21 | Logging, Monitoring & SIEM Policy | [policies/Logging-Monitoring-and-SIEM-Policy.md](../policies/Logging-Monitoring-and-SIEM-Policy.md) | Security Operations Lead |  |  |
| P22 | Incident Response Policy | [policies/Incident-Response-Policy.md](../policies/Incident-Response-Policy.md) | Security Operations Lead |  |  |
| P23 | Business Continuity Management Policy | [policies/Business-Continuity-Policy.md](../policies/Business-Continuity-Policy.md) | BC/DR Lead |  |  |
| P24 | Disaster Recovery Policy | [policies/Disaster-Recovery-Policy.md](../policies/Disaster-Recovery-Policy.md) | BC/DR Lead |  |  |
| P25 | Backup & Restore Policy | [policies/Backup-and-Restore-Policy.md](../policies/Backup-and-Restore-Policy.md) | BC/DR Lead |  |  |
| P26 | Supplier & Third-Party Risk Management Policy | [policies/Supplier-and-Third-Party-Risk-Management-Policy.md](../policies/Supplier-and-Third-Party-Risk-Management-Policy.md) | ISMS Manager |  |  |
| P27 | Subservice Organization Oversight Policy | [policies/Subservice-Organization-Oversight-Policy.md](../policies/Subservice-Organization-Oversight-Policy.md) | ISMS Manager |  |  |
| P28 | Physical & Environmental Security Policy | [policies/Physical-and-Environmental-Security-Policy.md](../policies/Physical-and-Environmental-Security-Policy.md) | Facilities Lead |  |  |
| P29 | Visitor Management Policy | [policies/Visitor-Management-Policy.md](../policies/Visitor-Management-Policy.md) | Facilities Lead |  |  |
| P30 | Data Retention & Disposal Policy | [policies/Data-Retention-and-Disposal-Policy.md](../policies/Data-Retention-and-Disposal-Policy.md) | ISMS Manager |  |  |
| P31 | Privacy & Data Protection Policy | [policies/Privacy-and-Data-Protection-Policy.md](../policies/Privacy-and-Data-Protection-Policy.md) | Privacy Officer |  |  |
| P32 | Records Management & Evidence Policy | [policies/Records-Management-and-Evidence-Policy.md](../policies/Records-Management-and-Evidence-Policy.md) | ISMS Manager |  |  |
| P33 | Training & Security Awareness Policy | [policies/Training-and-Security-Awareness-Policy.md](../policies/Training-and-Security-Awareness-Policy.md) | ISMS Manager |  |  |
| P34 | Quality & Document Control Policy | [policies/Quality-and-Document-Control-Policy.md](../policies/Quality-and-Document-Control-Policy.md) | ISMS Manager |  |  |
| P35 | Segregation of Duties Policy | [policies/Segregation-of-Duties-Policy.md](../policies/Segregation-of-Duties-Policy.md) | ISMS Manager |  |  |
| P36 | Email & Communications Security Policy | [policies/Email-and-Communications-Security-Policy.md](../policies/Email-and-Communications-Security-Policy.md) | ISMS Manager |  |  |
| P37 | API Security Policy | [policies/API-Security-Policy.md](../policies/API-Security-Policy.md) | Product Engineering Lead |  |  |
| P38 | Application Security Testing Policy | [policies/Application-Security-Testing-Policy.md](../policies/Application-Security-Testing-Policy.md) | Product Engineering Lead |  |  |
| P39 | Penetration Testing & Red Team Policy | [policies/Penetration-Testing-and-Red-Team-Policy.md](../policies/Penetration-Testing-and-Red-Team-Policy.md) | Product Engineering Lead |  |  |
| P40 | Secrets Management Policy | [policies/Secrets-Management-Policy.md](../policies/Secrets-Management-Policy.md) | ISMS Manager |  |  |
| P41 | Open-Source Software Governance Policy | [policies/Open-Source-Software-Governance-Policy.md](../policies/Open-Source-Software-Governance-Policy.md) | Product Engineering Lead |  |  |
| P42 | AI & Automation Use Policy | [policies/AI-and-Automation-Use-Policy.md](../policies/AI-and-Automation-Use-Policy.md) | ISMS Manager |  |  |
| P43 | Service Continuity for SaaS Policy | [policies/Service-Continuity-for-SaaS-Policy.md](../policies/Service-Continuity-for-SaaS-Policy.md) | BC/DR Lead |  |  |
| P44 | Capacity & Performance Management Policy | [policies/Capacity-and-Performance-Management-Policy.md](../policies/Capacity-and-Performance-Management-Policy.md) | IT Operations Lead |  |  |
| P45 | Financial Controls Policy (ICFR) | [policies/Financial-Controls-Policy.md](../policies/Financial-Controls-Policy.md) | Finance Controller |  |  |
| P46 | Revenue Recognition & Billing Policy | [policies/Revenue-Recognition-and-Billing-Policy.md](../policies/Revenue-Recognition-and-Billing-Policy.md) | Finance Controller |  |  |
| P47 | Fraud Prevention & Whistleblower Policy | [policies/Fraud-Prevention-and-Whistleblower-Policy.md](../policies/Fraud-Prevention-and-Whistleblower-Policy.md) | Finance Controller |  |  |
| P48 | HR Security Policy | [policies/HR-Security-Policy.md](../policies/HR-Security-Policy.md) | HR |  |  |
| P49 | HSE Policy | [policies/HSE-Policy.md](../policies/HSE-Policy.md) | Facilities Lead |  |  |
| P50 | Facility & Franchise Compliance Policy | [policies/Facility-and-Franchise-Compliance-Policy.md](../policies/Facility-and-Franchise-Compliance-Policy.md) | Facilities Lead |  |  |
| P51 | Franchise Branding & Communications Policy | [policies/Franchise-Branding-and-Communications-Policy.md](../policies/Franchise-Branding-and-Communications-Policy.md) | ISMS Manager |  |  |
| P52 | CCTV & Surveillance Policy | [policies/CCTV-and-Surveillance-Policy.md](../policies/CCTV-and-Surveillance-Policy.md) | Facilities Lead |  |  |
| P53 | Badge & Key/Card Control Policy | [policies/Badge-and-Key-Card-Control-Policy.md](../policies/Badge-and-Key-Card-Control-Policy.md) | Facilities Lead |  |  |
| P54 | Media Handling & Removable Media Policy | [policies/Media-Handling-and-Removable-Media-Policy.md](../policies/Media-Handling-and-Removable-Media-Policy.md) | ISMS Manager |  |  |
| P55 | Customer Data Handling & Confidentiality Policy | [policies/Customer-Data-Handling-and-Confidentiality-Policy.md](../policies/Customer-Data-Handling-and-Confidentiality-Policy.md) | ISMS Manager |  |  |
| P56 | Data Residency & Sovereignty Policy | [policies/Data-Residency-and-Sovereignty-Policy.md](../policies/Data-Residency-and-Sovereignty-Policy.md) | ISMS Manager |  |  |
| P57 | Network Change Control Policy | [policies/Network-Change-Control-Policy.md](../policies/Network-Change-Control-Policy.md) | Security Engineering Lead |  |  |
| P58 | Incident Communications & PR Policy | [policies/Incident-Communications-and-PR-Policy.md](../policies/Incident-Communications-and-PR-Policy.md) | ISMS Manager |  |  |
| P59 | Exception & Compensating Controls Policy | [policies/Exception-and-Compensating-Controls-Policy.md](../policies/Exception-and-Compensating-Controls-Policy.md) | ISMS Manager |  |  |
| P60 | Metrics & Continuous Improvement Policy | [policies/Metrics-and-Continuous-Improvement-Policy.md](../policies/Metrics-and-Continuous-Improvement-Policy.md) | ISMS Manager |  |  |
| P61 | Clean Desk & Clear Screen Policy | [policies/Clean-Desk-and-Clear-Screen-Policy.md](../policies/Clean-Desk-and-Clear-Screen-Policy.md) | ISMS Manager |  |  |
| P62 | Remote Access Policy | [policies/Remote-Access-Policy.md](../policies/Remote-Access-Policy.md) | Security Engineering Lead |  |  |
| P63 | Legal & Regulatory Compliance Policy | [policies/Legal-and-Regulatory-Compliance-Policy.md](../policies/Legal-and-Regulatory-Compliance-Policy.md) | ISMS Manager |  |  |
| P64 | Access Control Policy | [policies/Access-Control-Policy.md](../policies/Access-Control-Policy.md) | Security Engineering Lead |  |  |

### 7.3 Standards & Baselines (S##)

| Doc ID | Title | Path | Owner | Status | Target Date |
|--------|-------|------|-------|--------|-------------|
| S01 | Workstation Baseline | [standards/Workstation-Baseline.md](../standards/Workstation-Baseline.md) | IT Operations Lead |  |  |
| S02 | Server Baseline | [standards/Server-Baseline.md](../standards/Server-Baseline.md) | IT Operations Lead |  |  |
| S03 | Container/Kubernetes Baseline | [standards/Container-and-Kubernetes-Baseline.md](../standards/Container-and-Kubernetes-Baseline.md) | Product Eng Lead |  |  |
| S04 | Network Segmentation Standard | [standards/Network-Segmentation-Standard.md](../standards/Network-Segmentation-Standard.md) | Security Eng Lead |  |  |
| S05 | Firewall/WAF Standard | [standards/Firewall-and-WAF-Standard.md](../standards/Firewall-and-WAF-Standard.md) | Security Eng Lead |  |  |
| S06 | Identity & PAM Standard | [standards/Identity-and-PAM-Standard.md](../standards/Identity-and-PAM-Standard.md) | Security Eng Lead |  |  |
| S07 | Logging & Time Sync Standard | [standards/Logging-and-Time-Sync-Standard.md](../standards/Logging-and-Time-Sync-Standard.md) | Security Ops Lead |  |  |
| S08 | Backup & Immutability Standard | [standards/Backup-and-Immutability-Standard.md](../standards/Backup-and-Immutability-Standard.md) | BC/DR Lead |  |  |
| S09 | Secrets Management Standard | [standards/Secrets-Management-Standard.md](../standards/Secrets-Management-Standard.md) | ISMS Manager |  |  |
| S10 | CI/CD Security Standard | [standards/CI-CD-Security-Standard.md](../standards/CI-CD-Security-Standard.md) | Product Eng Lead |  |  |
| S11 | API Security Standard | [standards/API-Security-Standard.md](../standards/API-Security-Standard.md) | Product Eng Lead |  |  |
| S12 | Data Classification Marking Standard | [standards/Data-Classification-Marking-Standard.md](../standards/Data-Classification-Marking-Standard.md) | ISMS Manager |  |  |
| S13 | Vulnerability Severity & SLA Standard | [standards/Vulnerability-Severity-and-SLA-Standard.md](../standards/Vulnerability-Severity-and-SLA-Standard.md) | Security Eng Lead |  |  |
| S14 | SaaS Multi-Tenancy & Isolation Standard | [standards/SaaS-Multi-Tenancy-and-Isolation-Standard.md](../standards/SaaS-Multi-Tenancy-and-Isolation-Standard.md) | Product Eng Lead |  |  |
| S15 | NOC Build Standard | [standards/NOC-Build-Standard.md](../standards/NOC-Build-Standard.md) | Facilities Lead |  |  |
| S16 | DCIM/Telemetry Standard | [standards/DCIM-Telemetry-Standard.md](../standards/DCIM-Telemetry-Standard.md) | Facilities Lead |  |  |
| S17 | Facility Physical Security Standard | [standards/Facility-Physical-Security-Standard.md](../standards/Facility-Physical-Security-Standard.md) | Facilities Lead |  |  |
| S18 | EHS/LOTO Standard | [standards/EHS-LOTO-Standard.md](../standards/EHS-LOTO-Standard.md) | Facilities Lead |  |  |
| S19 | Maintenance & MEP Change Standard | [standards/Maintenance-and-MEP-Change-Standard.md](../standards/Maintenance-and-MEP-Change-Standard.md) | Facilities Lead |  |  |
| S20 | Franchise Technical Baseline Standard | [standards/Franchise-Technical-Baseline-Standard.md](../standards/Franchise-Technical-Baseline-Standard.md) | Franchise Program Director |  |  |
| S21 | Database Security Standard | [standards/Database-Security-Standard.md](../standards/Database-Security-Standard.md) | Security Eng Lead |  |  |
| S22 | Cloud Landing Zone Standard | [standards/Cloud-Landing-Zone-Standard.md](../standards/Cloud-Landing-Zone-Standard.md) | Security Eng Lead |  |  |
| S23 | Vulnerability Scanning Standard | [standards/Vulnerability-Scanning-Standard.md](../standards/Vulnerability-Scanning-Standard.md) | Security Eng Lead |  |  |
| S24 | Data Loss Prevention (DLP) Standard | [standards/Data-Loss-Prevention-Standard.md](../standards/Data-Loss-Prevention-Standard.md) | ISMS Manager |  |  |

### 7.4 Procedures & Runbooks (PR##)

| Doc ID | Title | Path | Owner | Status | Target Date |
|--------|-------|------|-------|--------|-------------|
| PR01 | ISMS Implementation Procedure | [procedures/ISMS-Implementation-Procedure.md](../procedures/ISMS-Implementation-Procedure.md) | ISMS Manager |  |  |
| PR02 | Risk Assessment Procedure | [procedures/Risk-Assessment-Procedure.md](../procedures/Risk-Assessment-Procedure.md) | GRC Analyst |  |  |
| PR03 | BIA Procedure | [procedures/BIA-Procedure.md](../procedures/BIA-Procedure.md) | BC/DR Lead |  |  |
| PR04 | Access Provisioning/Deprovisioning Procedure | [procedures/Access-Provisioning-and-Deprovisioning-Procedure.md](../procedures/Access-Provisioning-and-Deprovisioning-Procedure.md) | Security Eng Lead |  |  |
| PR05 | Privileged Access Elevation Procedure | [procedures/Privileged-Access-Elevation-Procedure.md](../procedures/Privileged-Access-Elevation-Procedure.md) | Security Eng Lead |  |  |
| PR06 | Onboarding & Offboarding Procedure | [procedures/Onboarding-and-Offboarding-Procedure.md](../procedures/Onboarding-and-Offboarding-Procedure.md) | HR |  |  |
| PR07 | Change Control Procedure | [procedures/Change-Control-Procedure.md](../procedures/Change-Control-Procedure.md) | IT Ops Lead |  |  |
| PR08 | Emergency Change Procedure | [procedures/Emergency-Change-Procedure.md](../procedures/Emergency-Change-Procedure.md) | IT Ops Lead |  |  |
| PR09 | Release Management Procedure | [procedures/Release-Management-Procedure.md](../procedures/Release-Management-Procedure.md) | Product Eng Lead |  |  |
| PR10 | Configuration Management Procedure | [procedures/Configuration-Management-Procedure.md](../procedures/Configuration-Management-Procedure.md) | IT Ops Lead |  |  |
| PR11 | Vulnerability Management Procedure | [procedures/Vulnerability-Management-Procedure.md](../procedures/Vulnerability-Management-Procedure.md) | Security Eng Lead |  |  |
| PR12 | Patch Management Procedure | [procedures/Patch-Management-Procedure.md](../procedures/Patch-Management-Procedure.md) | Security Eng Lead |  |  |
| PR13 | Incident Response Runbook (General) | [procedures/IR-Runbook-General.md](../procedures/IR-Runbook-General.md) | Security Ops Lead |  |  |
| PR14 | IR Runbook – Credential Leak (Cloud) | [procedures/IR-Runbook-Credential-Leak.md](../procedures/IR-Runbook-Credential-Leak.md) | Security Ops Lead |  |  |
| PR15 | IR Runbook – Ransomware | [procedures/IR-Runbook-Ransomware.md](../procedures/IR-Runbook-Ransomware.md) | Security Ops Lead |  |  |
| PR16 | IR Runbook – DDoS/WAF Evasion | [procedures/IR-Runbook-DDoS-WAF.md](../procedures/IR-Runbook-DDoS-WAF.md) | Security Ops Lead |  |  |
| PR17 | IR Runbook – Data Breach (PII/CI) | [procedures/IR-Runbook-Data-Breach.md](../procedures/IR-Runbook-Data-Breach.md) | Security Ops Lead |  |  |
| PR18 | Forensics & Evidence Handling SOP | [procedures/Forensics-and-Evidence-Handling-SOP.md](../procedures/Forensics-and-Evidence-Handling-SOP.md) | Security Ops Lead |  |  |
| PR19 | Logging & SIEM Onboarding Procedure | [procedures/Logging-and-SIEM-Onboarding-Procedure.md](../procedures/Logging-and-SIEM-Onboarding-Procedure.md) | Security Ops Lead |  |  |
| PR20 | Alert Triage & Escalation Procedure | [procedures/Alert-Triage-and-Escalation-Procedure.md](../procedures/Alert-Triage-and-Escalation-Procedure.md) | Security Ops Lead |  |  |
| PR21 | Backup & Restore Procedure | [procedures/Backup-and-Restore-Procedure.md](../procedures/Backup-and-Restore-Procedure.md) | BC/DR Lead |  |  |
| PR22 | DR Invocation & Recovery Procedure | [procedures/DR-Invocation-and-Recovery-Procedure.md](../procedures/DR-Invocation-and-Recovery-Procedure.md) | BC/DR Lead |  |  |
| PR23 | Tabletop Exercise Procedure | [procedures/Tabletop-Exercise-Procedure.md](../procedures/Tabletop-Exercise-Procedure.md) | BC/DR Lead |  |  |
| PR24 | SAST/DAST & Code Review Procedure | [procedures/SAST-DAST-and-Code-Review-Procedure.md](../procedures/SAST-DAST-and-Code-Review-Procedure.md) | Product Eng Lead |  |  |
| PR25 | Secrets Rotation Procedure | [procedures/Secrets-Rotation-Procedure.md](../procedures/Secrets-Rotation-Procedure.md) | ISMS Manager |  |  |
| PR26 | CI/CD Hardening Procedure | [procedures/CI-CD-Hardening-Procedure.md](../procedures/CI-CD-Hardening-Procedure.md) | Product Eng Lead |  |  |
| PR27 | Data Retention & Destruction Procedure | [procedures/Data-Retention-and-Destruction-Procedure.md](../procedures/Data-Retention-and-Destruction-Procedure.md) | ISMS Manager |  |  |
| PR28 | Customer Onboarding & Offboarding Procedure | [procedures/Customer-Onboarding-and-Offboarding-Procedure.md](../procedures/Customer-Onboarding-and-Offboarding-Procedure.md) | ISMS Manager |  |  |
| PR29 | Support & Escalation Procedure | [procedures/Support-and-Escalation-Procedure.md](../procedures/Support-and-Escalation-Procedure.md) | ISMS Manager |  |  |
| PR30 | Vendor Due Diligence & Onboarding Procedure | [procedures/Vendor-Due-Diligence-and-Onboarding-Procedure.md](../procedures/Vendor-Due-Diligence-and-Onboarding-Procedure.md) | ISMS Manager |  |  |
| PR31 | Subservice Monitoring Procedure | [procedures/Subservice-Monitoring-Procedure.md](../procedures/Subservice-Monitoring-Procedure.md) | ISMS Manager |  |  |
| PR32 | Franchise Site Onboarding Procedure | [procedures/Franchise-Site-Onboarding-Procedure.md](../procedures/Franchise-Site-Onboarding-Procedure.md) | Franchise Program Director |  |  |
| PR33 | Franchise Compliance Audit Procedure | [procedures/Franchise-Compliance-Audit-Procedure.md](../procedures/Franchise-Compliance-Audit-Procedure.md) | Franchise Program Director |  |  |
| PR34 | NOC Operations Manual | [procedures/NOC-Operations-Manual.md](../procedures/NOC-Operations-Manual.md) | Security Ops Lead |  |  |
| PR35 | Visitor Management Procedure | [procedures/Visitor-Management-Procedure.md](../procedures/Visitor-Management-Procedure.md) | Facilities Lead |  |  |
| PR36 | Badge Issuance & Revocation Procedure | [procedures/Badge-Issuance-and-Revocation-Procedure.md](../procedures/Badge-Issuance-and-Revocation-Procedure.md) | Facilities Lead |  |  |
| PR37 | EHS Incident Reporting Procedure | [procedures/EHS-Incident-Reporting-Procedure.md](../procedures/EHS-Incident-Reporting-Procedure.md) | Facilities Lead |  |  |
| PR38 | LOTO Procedure | [procedures/LOTO-Procedure.md](../procedures/LOTO-Procedure.md) | Facilities Lead |  |  |
| PR39 | MEP SOP | [procedures/MEP-SOP.md](../procedures/MEP-SOP.md) | Facilities Lead |  |  |
| PR40 | CCTV Export & Review Procedure | [procedures/CCTV-Export-and-Review-Procedure.md](../procedures/CCTV-Export-and-Review-Procedure.md) | Facilities Lead |  |  |
| PR41 | Penetration Testing Procedure | [procedures/Penetration-Testing-Procedure.md](../procedures/Penetration-Testing-Procedure.md) | Product Eng Lead |  |  |
| PR42 | Continuous Control Monitoring Procedure | [procedures/Continuous-Control-Monitoring-Procedure.md](../procedures/Continuous-Control-Monitoring-Procedure.md) | ISMS Manager |  |  |
| PR43 | Metrics & KRIs Reporting Procedure | [procedures/Metrics-and-KRIs-Reporting-Procedure.md](../procedures/Metrics-and-KRIs-Reporting-Procedure.md) | ISMS Manager |  |  |
| PR44 | Exception & Compensating Controls Procedure | [procedures/Exception-and-Compensating-Controls-Procedure.md](../procedures/Exception-and-Compensating-Controls-Procedure.md) | ISMS Manager |  |  |
| PR45 | Internal Audit Procedure | [procedures/Internal-Audit-Procedure.md](../procedures/Internal-Audit-Procedure.md) | Internal Audit |  |  |
| PR46 | Management Review Procedure | [procedures/Management-Review-Procedure.md](../procedures/Management-Review-Procedure.md) | ISMS Manager |  |  |
| PR47 | Quality Assurance Procedure | [procedures/Quality-Assurance-Procedure.md](../procedures/Quality-Assurance-Procedure.md) | Product Eng Lead |  |  |
| PR48 | Revenue & Billing Controls Procedure | [procedures/Revenue-and-Billing-Controls-Procedure.md](../procedures/Revenue-and-Billing-Controls-Procedure.md) | Finance Controller |  |  |
| PR49 | Financial System Access Procedure | [procedures/Financial-System-Access-Procedure.md](../procedures/Financial-System-Access-Procedure.md) | Finance Controller |  |  |
| PR50 | Reconciliations & Exception Management Procedure | [procedures/Reconciliations-and-Exception-Management-Procedure.md](../procedures/Reconciliations-and-Exception-Management-Procedure.md) | Finance Controller |  |  |
| PR51 | DPIA Procedure | [procedures/DPIA-Procedure.md](../procedures/DPIA-Procedure.md) | Privacy Officer |  |  |

### 7.5 Plans, Narratives & Playbooks (PL##, SD##)

| Doc ID | Title | Path | Owner | Status | Target Date |
|--------|-------|------|-------|--------|-------------|
| PL01 | Program Plan | [plans/Program-Plan.md](../plans/Program-Plan.md) | ISMS Manager |  |  |
| PL02 | Security Awareness & Phishing Plan | [plans/Security-Awareness-and-Phishing-Plan.md](../plans/Security-Awareness-and-Phishing-Plan.md) | ISMS Manager |  |  |
| PL03 | BIA Reports – by Function | [plans/BIA-Reports.md](../plans/BIA-Reports.md) | BC/DR Lead |  |  |
| PL04 | BCMS Strategy Plan | [plans/BCMS-Strategy-Plan.md](../plans/BCMS-Strategy-Plan.md) | BC/DR Lead |  |  |
| PL05 | DR Plans – by System | [plans/Disaster-Recovery-Plans.md](../plans/Disaster-Recovery-Plans.md) | BC/DR Lead |  |  |
| PL06 | Crisis Communications Plan | [plans/Crisis-Communications-Plan.md](../plans/Crisis-Communications-Plan.md) | ISMS Manager |  |  |
| PL07 | Incident Playbooks – by Scenario | [plans/Incident-Playbooks.md](../plans/Incident-Playbooks.md) | Security Ops Lead |  |  |
| PL08 | Pen-Test & AppSec Annual Plan | [plans/Pen-Test-and-AppSec-Annual-Plan.md](../plans/Pen-Test-and-AppSec-Annual-Plan.md) | Product Eng Lead |  |  |
| PL09 | Audit & Assessment Plan | [plans/Audit-and-Assessment-Plan.md](../plans/Audit-and-Assessment-Plan.md) | ISMS Manager |  |  |
| PL10 | Franchise Compliance Plan | [plans/Franchise-Compliance-Plan.md](../plans/Franchise-Compliance-Plan.md) | Franchise Program Director |  |  |
| PL11 | Crisis Management Plan | [plans/Crisis-Management-Plan.md](../plans/Crisis-Management-Plan.md) | ISMS Manager |  |  |
| PL12 | Workforce Continuity Plan | [plans/Workforce-Continuity-Plan.md](../plans/Workforce-Continuity-Plan.md) | BC/DR Lead |  |  |
| SD01 | SOC SysDesc – GridSite Marketplace | [plans/SD-GridSite-Marketplace.md](../plans/SD-GridSite-Marketplace.md) | ISMS Manager |  |  |
| SD02 | SOC SysDesc – ComputeComplete & GridColo | [plans/SD-ComputeComplete-and-GridColo.md](../plans/SD-ComputeComplete-and-GridColo.md) | ISMS Manager |  |  |
| SD03 | SOC SysDesc – Vendor Network | [plans/SD-Vendor-Network.md](../plans/SD-Vendor-Network.md) | ISMS Manager |  |  |
| SD04 | ICFR Narrative – Billing & Revenue | [plans/ICFR-Narrative-Billing-and-Revenue.md](../plans/ICFR-Narrative-Billing-and-Revenue.md) | Finance Controller |  |  |
| SD05 | Network & Data Flow Diagrams | [plans/Network-and-Data-Flow-Diagrams.md](../plans/Network-and-Data-Flow-Diagrams.md) | Security Eng Lead |  |  |
| SD06 | Threat Models (STRIDE) – by system | [plans/Threat-Models-STRIDE.md](../plans/Threat-Models-STRIDE.md) | Product Eng Lead |  |  |
| SD07 | NOC Design Package | [plans/NOC-Design-Package.md](../plans/NOC-Design-Package.md) | Facilities Lead |  |  |
| SD08 | Franchise Standards Manual | [plans/Franchise-Standards-Manual.md](../plans/Franchise-Standards-Manual.md) | Franchise Program Director |  |  |

### 7.6 Registers, Logs & Inventories (R##)

| Doc ID | Title | Path | Owner | Status | Target Date |
|--------|-------|------|-------|--------|-------------|
| R01 | Risk Register | [plans/Risk-Register.md](../plans/Risk-Register.md) | GRC Analyst |  |  |
| R02 | Asset Inventory & CMDB | [plans/Asset-Inventory-and-CMDB.md](../plans/Asset-Inventory-and-CMDB.md) | IT Ops Lead |  |  |
| R03 | Data Inventory | [plans/Data-Inventory.md](../plans/Data-Inventory.md) | Privacy Officer |  |  |
| R04 | Access Control Matrix | [plans/Access-Control-Matrix.md](../plans/Access-Control-Matrix.md) | Security Eng Lead |  |  |
| R05 | Privileged Accounts Register | [plans/Privileged-Accounts-Register.md](../plans/Privileged-Accounts-Register.md) | Security Eng Lead |  |  |
| R06 | Keys & Certificates Inventory | [plans/Keys-and-Certificates-Inventory.md](../plans/Keys-and-Certificates-Inventory.md) | ISMS Manager |  |  |
| R07 | Vendor/Subservice Register | [plans/Vendor-and-Subservice-Register.md](../plans/Vendor-and-Subservice-Register.md) | ISMS Manager |  |  |
| R08 | Customer Commitments & SLAs Register | [plans/Customer-Commitments-and-SLAs-Register.md](../plans/Customer-Commitments-and-SLAs-Register.md) | ISMS Manager |  |  |
| R09 | Change Log | [plans/Change-Log.md](../plans/Change-Log.md) | IT Ops Lead |  |  |
| R10 | Incident Log | [plans/Incident-Log.md](../plans/Incident-Log.md) | Security Ops Lead |  |  |
| R11 | Vulnerability Register | [plans/Vulnerability-Register.md](../plans/Vulnerability-Register.md) | Security Eng Lead |  |  |
| R12 | Patch Register | [plans/Patch-Register.md](../plans/Patch-Register.md) | Security Eng Lead |  |  |
| R13 | Training Attendance & Results | [plans/Training-Attendance-and-Results.md](../plans/Training-Attendance-and-Results.md) | ISMS Manager |  |  |
| R14 | Internal Audit Findings & CAPA Tracker | [plans/Internal-Audit-Findings-and-CAPA-Tracker.md](../plans/Internal-Audit-Findings-and-CAPA-Tracker.md) | Internal Audit |  |  |
| R15 | BC/DR Test Records | [plans/BC-DR-Test-Records.md](../plans/BC-DR-Test-Records.md) | BC/DR Lead |  |  |
| R16 | Backup & Restore Test Logs | [plans/Backup-and-Restore-Test-Logs.md](../plans/Backup-and-Restore-Test-Logs.md) | BC/DR Lead |  |  |
| R17 | Pen-Test Reports & Remediation Tracker | [plans/Pen-Test-Reports-and-Remediation-Tracker.md](../plans/Pen-Test-Reports-and-Remediation-Tracker.md) | Product Eng Lead |  |  |
| R18 | Capacity & Availability Reports | [plans/Capacity-and-Availability-Reports.md](../plans/Capacity-and-Availability-Reports.md) | IT Ops Lead |  |  |
| R19 | Energy & PUE Reports | [plans/Energy-and-PUE-Reports.md](../plans/Energy-and-PUE-Reports.md) | Facilities Lead |  |  |
| R20 | Visitor & Badge Logs | [plans/Visitor-and-Badge-Logs.md](../plans/Visitor-and-Badge-Logs.md) | Facilities Lead |  |  |
| R21 | ISMS Objectives Register | [plans/ISMS-Objectives-Register.md](../plans/ISMS-Objectives-Register.md) | ISMS Manager |  |  |

### 7.7 Templates (T##)

| Doc ID | Title | Path | Owner | Status | Target Date |
|--------|-------|------|-------|--------|-------------|
| T01 | Policy Template | [templates/_TEMPLATE-Policy.md](../templates/_TEMPLATE-Policy.md) | ISMS Manager |  |  |
| T02 | Procedure Template | [templates/_TEMPLATE-Procedure.md](../templates/_TEMPLATE-Procedure.md) | ISMS Manager |  |  |
| T03 | Change Request Form | [templates/Change-Request-Form.md](../templates/Change-Request-Form.md) | IT Ops Lead |  |  |
| T04 | Access Request Form | [templates/Access-Request-Form.md](../templates/Access-Request-Form.md) | Security Eng Lead |  |  |
| T05 | Incident Report Form | [templates/Incident-Report-Form.md](../templates/Incident-Report-Form.md) | Security Ops Lead |  |  |
| T06 | Vendor Due Diligence Questionnaire | [templates/Vendor-Due-Diligence-Questionnaire.md](../templates/Vendor-Due-Diligence-Questionnaire.md) | ISMS Manager |  |  |
| T07 | Franchise Site Onboarding Checklist | [templates/Franchise-Site-Onboarding-Checklist.md](../templates/Franchise-Site-Onboarding-Checklist.md) | Franchise Director |  |  |
| T08 | Management Review Pack Template | [templates/Management-Review-Pack-Template.md](../templates/Management-Review-Pack-Template.md) | ISMS Manager |  |  |
| T09 | BC/DR Exercise Templates | [templates/BC-DR-Exercise-Templates.md](../templates/BC-DR-Exercise-Templates.md) | BC/DR Lead |  |  |
| T10 | Customer CUEC Disclosure Template | [templates/Customer-CUEC-Disclosure-Template.md](../templates/Customer-CUEC-Disclosure-Template.md) | ISMS Manager |  |  |

