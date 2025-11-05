---
title: "Logging and Time Synchronization Standard"
doc_type: "Standard"
id: "GRS-ISMS-STD-007"
version: "1.0.0"
status: "Draft"
owner: "Security Operations Lead"
approver: "Executive Management, GridSite Technology LLC"
approval_date: ""
effective_date: ""
next_review_date: ""
related_documents:
  - ../policies/Logging-Monitoring-and-SIEM-Policy.md
  - ../policies/Incident-Response-Policy.md
  - ../procedures/Logging-and-SIEM-Onboarding-Procedure.md
references:
  - ISO/IEC 27002:2022 (8.15, 8.16)
  - AICPA SOC 2 (CC7)
---

## Document Control

| Field | Value |
|-------|-------|
| Title | Logging and Time Synchronization Standard |
| Document ID | GRS-ISMS-STD-007 |
| Version | 1.0.0 |
| Status | Draft |
| Owner | Security Operations Lead |
| Approver | Executive Management, GridSite Technology LLC |
| Approval Date |  |
| Effective Date |  |
| Next Review Date |  |

## 1. Purpose

Specify mandatory logging coverage, event content, onboarding, retention, and time synchronization
requirements to support detection, investigation, and evidencing.

## 2. Scope

All production and corporate systems within ISMS scope, including cloud services, applications, endpoints,
network devices, and facility systems where applicable.

## 3. Control Requirements

| Req ID | Requirement | Implementation | Evidence |
|--------|-------------|----------------|----------|
| LTS-01 | Approved NTP | Systems sync with approved NTP; critical drift alerts enabled | Config exports; alert screenshots |
| LTS-02 | Source onboarding | Identity, admin, server, endpoint, network, cloud, and critical app logs onboarded to SIEM when supported | SIEM source list; connector configs |
| LTS-03 | Event content | Include subject identifier, timestamp, source/destination, action, result, failure data | Sample events; parser mappings |
| LTS-04 | Integrity | Use immutability/write-once or equivalent for critical logs | Storage settings; immutability policy |
| LTS-05 | Retention | Retain security logs ≥ 12 months unless stricter obligations apply | Retention policy; storage lifecycle |
| LTS-06 | Manual review | For non-forwarding systems, define review cadence, reviewer, checklist, and evidence capture | Runbooks; screenshots/exports |
| LTS-07 | Detections | Implement detections for MFA failures, privilege elevation, admin changes, malware/EDR, WAF, exfil patterns | Rule inventory; alert metrics |
| LTS-08 | Alert routing | Route alerts to on-call with SLAs and escalation; log acknowledgments | On-call schedule; ticket/alert links |
| LTS-09 | Privacy minimization | Avoid storing sensitive personal data; mask where feasible | Parser rules; data classification |

## 4. Roles and Responsibilities

Security Operations owns detections and onboarding; Security Engineering owns architecture and time sync;
IT Operations ensures host and endpoint configurations; System Owners ensure application logs meet this
standard and remediate gaps.

## 5. Revision History

| Version | Date       | Author | Description |
|---------|------------|--------|-------------|
| 1.0.0   | 2025-11-05 |        | Initial logging and time sync standard. |


