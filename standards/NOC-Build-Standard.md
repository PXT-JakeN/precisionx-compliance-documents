---
title: "NOC Build Standard"
doc_type: "Standard"
id: "GRS-ISMS-STD-015"
version: "1.1.0"
status: "Draft"
owner: "Security Engineering Lead"
approver: "Executive Management, GridSite Technology LLC"
approval_date: ""
effective_date: ""
next_review_date: ""
related_documents:
  - ../standards/Network-Segmentation-Standard.md
  - ../standards/Firewall-and-WAF-Standard.md
  - ../policies/Incident-Response-Policy.md
references:
  - ISO/IEC 27002:2022 (physical and environmental)
---

## Document Control

| Field | Value |
|-------|-------|
| Title | NOC Build Standard |
| Document ID | GRS-ISMS-STD-015 |
| Version | 1.0.0 |
| Status | Draft |
| Owner | Security Engineering Lead |
| Approver | Executive Management, GridSite Technology LLC |
| Approval Date |  |
| Effective Date |  |
| Next Review Date |  |

## 1. Purpose

Define minimum physical, network, and operational requirements for GridSite Network Operations Centers
to support secure operations and incident coordination.

## 2. Scope

Primary NOC (Plano) and secondary NOC facilities, including network rooms and secure operator areas.

## 3. Control Requirements

| Req ID | Requirement | Implementation | Evidence |
|--------|-------------|----------------|----------|
| NOC-01 | Access control | Badged entry with logging; visitor escort; mantrap or two‑factor where feasible | Access logs; badge configs |
| NOC-02 | Surveillance | CCTV coverage of entrances, operator floor, racks; 30–90 day retention | Camera maps; footage samples |
| NOC-03 | Power | Redundant feeds/UPS; generator or extended runtime plan; tested quarterly | Test logs; maintenance records |
| NOC-04 | Racks & cabling | Labeled racks/cables; structured cabling; locked racks for sensitive gear | Photos; diagrams |
| NOC-05 | Environmental | Temperature/humidity monitoring with alerts; fire detection/suppression | Sensor exports; test docs |
| NOC-06 | Network | Segmented mgmt/control/data; admin ingress limited to NOC for on‑prem servers | Network diagrams; ACLs |
| NOC-07 | Workstations | Wired preferred; UniFi Identity Wi‑Fi as fallback; clean desk enforcement | Configs; audit checklists |
| NOC-08 | Logging | Forward physical/security events where supported or perform manual reviews | Logs; review records |
| NOC-09 | DR readiness | Secondary NOC with minimum seats and connectivity; periodic failover tests | Exercise reports |
| NOC-10 | Dual‑NOC role separation | Primary NOC: NOC Manager + Analyst (backup dispatcher); Secondary NOC: Dispatcher + backup Analyst | Staffing rosters; shift plans |
| NOC-11 | Live AV link | Maintain 24×7 AV link between NOCs via dedicated Teams accounts for shared situational awareness | Teams configs; screenshots |
| NOC-12 | Surge participation | Authorized personnel can be added to AV link during incidents to assist assessment and response | Call logs; incident records |
| NOC-13 | AV resiliency | Provide fallback (secondary accounts/endpoints) and documented steps if AV equipment fails | Runbooks; test results |
| NOC-14 | Radio/voice | Cellular PTT and UHF radio available for local/backup comms; SIP alert phone for emergency voice | Inventory; test logs |

## 4. Roles and Responsibilities

Facilities/IT implement and maintain physical and power systems; Security Engineering owns network and
access standards; SecOps verifies monitoring and drills.

## 5. Revision History

| Version | Date       | Author | Description |
|---------|------------|--------|-------------|
| 1.1.0   | 2025-11-05 |        | Added dual‑NOC role separation, 24×7 AV link, surge participation, and AV resiliency controls. |
| 1.0.0   | 2025-11-05 |        | Initial NOC build standard. |


