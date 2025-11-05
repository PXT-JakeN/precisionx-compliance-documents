---
title: "Facility Physical Security Standard"
doc_type: "Standard"
id: "GRS-ISMS-STD-017"
version: "1.1.0"
status: "Draft"
owner: "Facilities Lead"
approver: "Executive Management, GridSite Technology LLC"
approval_date: ""
effective_date: ""
next_review_date: ""
related_documents:
  - ../policies/Information-Security-Policy.md
  - ../standards/NOC-Build-Standard.md
  - ../policies/Incident-Response-Policy.md
references:
  - ISO/IEC 27002:2022 (physical and environmental)
---

## Document Control

| Field | Value |
|-------|-------|
| Title | Facility Physical Security Standard |
| Document ID | GRS-ISMS-STD-017 |
| Version | 1.0.0 |
| Status | Draft |
| Owner | Facilities Lead |
| Approver | Executive Management, GridSite Technology LLC |
| Approval Date |  |
| Effective Date |  |
| Next Review Date |  |

## 1. Purpose

Establish physical security controls at offices, NOCs, and GridColo sites to deter, detect, delay, and respond
to threats.

## 2. Scope

Perimeter, entry points, internal access to secure areas, and protection of network rooms and racks. The
integrated access management portal and kiosk system described below applies to all sites (offices and
corporate‑owned/licensed data centers).

## 3. Control Requirements

| Req ID | Requirement | Implementation | Evidence |
|--------|-------------|----------------|----------|
| PHY-01 | Perimeter | Lighting, signage, and barriers; clear lines of sight | Photos; site checklists |
| PHY-02 | Access control | Badging with logging; visitor management with ID and escort | Access logs; visitor logs |
| PHY-03 | Surveillance | CCTV for entrances, corridors, and secure rooms with retention | Camera maps; samples |
| PHY-04 | Secure areas | Locked network rooms/racks; limited keys/cards; periodic audits | Audit results; key logs |
| PHY-05 | Incident support | Panic/duress procedures; quick link to IR; drill annually | Procedures; drill logs |
| PHY-06 | Environmental | Fire/smoke detection; extinguishers; clean agent where appropriate | Inspection records |
| PHY-07 | Access portal roles | Portal allows tenants, vendors, and personnel to create users and assign site roles (security, maintenance/janitorial, facility management); elevated portal roles grant additional capabilities | Role matrix; portal screenshots |
| PHY-08 | Enrollment & vetting | All users enroll with ID validation; vendors/facility staff require background checks; pending checks prohibit unescorted access | Enrollment logs; BG check status |
| PHY-09 | Kiosk 3‑factor auth | Sign‑in kiosk enforces badge + face + PIN; appointments/guests processed via kiosk; escort limit of 5 enforced | Kiosk configs; sign‑in records |
| PHY-10 | Guard terminal fallback | Guard terminal supports face/PIN sign‑in if kiosk fails; paper records maintained for backup | Guard logs; paper forms |
| PHY-11 | Government ID checks | Guard validates government ID on first access and when photo/PIN reset | ID check logs |
| PHY-12 | Lobby access staging | Exterior doors allow cardholders to lobby only; additional access enabled after kiosk sign‑in and removed at sign‑out; kiosk prevents duplicate sign‑ins | Access control events |
| PHY-13 | Lost/forgotten badge | Self‑service flow for forgotten badge; guard verifies ID and issues temporary credential; lost badges deactivated and replacement ordered | Tickets; issuance logs |
| PHY-14 | Escort attestation | Cardholder must declare escorted guests at kiosk; audit log records escort/escorted parties | Escort logs |
| PHY-15 | Disqualifying offenses & appeal | Disqualifying convictions defined; denied users can appeal via portal or kiosk; decisions logged | Appeal records |
| PHY-16 | Auditable logs | All access events and admin actions are retained and auditable | Log retention policy; exports |

## 4. Roles and Responsibilities

Facilities manages physical controls and vendor coordination; SecOps reviews incidents and supports drills; NOC
reports anomalies.

## 5. Revision History

| Version | Date       | Author | Description |
|---------|------------|--------|-------------|
| 1.1.0   | 2025-11-05 |        | Added integrated access portal/kiosk controls, enrollment/vetting, escort limits, fallback processes, and auditability. |
| 1.0.0   | 2025-11-05 |        | Initial facility physical security standard. |


