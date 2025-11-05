---
title: "Network Segmentation Standard"
doc_type: "Standard"
id: "GRS-ISMS-STD-004"
version: "1.0.0"
status: "Draft"
owner: "Security Engineering Lead"
approver: "Executive Management, GridSite Technology LLC"
approval_date: ""
effective_date: ""
next_review_date: ""
related_documents:
  - ../policies/Information-Security-Policy.md
  - ../policies/Logging-Monitoring-and-SIEM-Policy.md
  - ./Firewall-and-WAF-Standard.md
references:
  - ISO/IEC 27002:2022 (8.20 Network security)
  - AICPA SOC 2 (CC6)
---

## Document Control

| Field | Value |
|-------|-------|
| Title | Network Segmentation Standard |
| Document ID | GRS-ISMS-STD-004 |
| Version | 1.0.0 |
| Status | Draft |
| Owner | Security Engineering Lead |
| Approver | Executive Management, GridSite Technology LLC |
| Approval Date |  |
| Effective Date |  |
| Next Review Date |  |

## 1. Purpose

Define segmentation requirements to reduce attack surface and lateral movement across GridSite corporate,
cloud, and facility networks.

## 2. Scope

Corporate offices, NOCs, GridColo sites, and virtual networks in cloud providers.

## 3. Control Requirements

| Req ID | Requirement | Implementation | Evidence |
|--------|-------------|----------------|----------|
| NET-01 | Zone model | Define zones: Management, Control, Data, Corporate, Guest/Unmanaged; document flows | Diagrams; ACLs |
| NET-02 | Default deny | Enforce default‑deny between zones; allow least privilege flows only | Firewall rules; policies |
| NET-03 | NOC admin ingress | Allow SSH/RDP to local servers only from secure NOC networks | ACLs; firewall configs |
| NET-04 | Wireless segmentation | Separate corporate SSIDs (UniFi Identity), guest, and unmanaged networks | UniFi exports; VLAN maps |
| NET-05 | Cloud segmentation | Segment VPC/VNet subnets for mgmt/control/data; restrict east‑west | Cloud SG/NACL configs |
| NET-06 | Egress control | Restrict egress for sensitive zones; log and review exceptions | Egress policies; logs |
| NET-07 | Monitoring | Mirror critical segments to sensors; forward logs or document manual reviews | Sensor configs; review records |

## 4. Roles and Responsibilities

Security Engineering maintains the zone model and approves exceptions. IT Operations implements changes and
maintains rule hygiene.

## 5. Revision History

| Version | Date       | Author | Description |
|---------|------------|--------|-------------|
| 1.0.0   | 2025-11-05 |        | Initial network segmentation standard. |


