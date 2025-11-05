---
title: "Onboarding & Offboarding Procedure"
doc_type: "Procedure"
id: "GRS-ISMS-PRC-006"
version: "1.0.0"
status: "Draft"
owner: "HR Director"
program_manager: "Josh Mayorga, Compliance Manager"
approver: "Executive Management, GridSite Technology LLC"
approval_date: ""
effective_date: ""
next_review_date: ""
classification: "Internal – Controlled"
organization: "GridSite Technology LLC and its operating subsidiaries"
related_documents:
  - ../policies/HR-Security-Policy.md
  - ../procedures/Access-Provisioning-and-Deprovisioning-Procedure.md
  - ../policies/Acceptable-Use-Policy.md
  - ../standards/Workstation-Baseline.md
  - ../policies/Remote-Work-Security-Policy.md
  - ../standards/Facility-Physical-Security-Standard.md
---

## Document Control

| Field | Value |
|-------|-------|
| Title | Onboarding & Offboarding Procedure |
| Document ID | GRS-ISMS-PRC-006 |
| Version | 1.0.0 |
| Status | Draft |
| Owner | HR Director |
| Program Manager | Josh Mayorga, Compliance Manager |
| Approver | Executive Management, GridSite Technology LLC |
| Approval Date |  |
| Effective Date |  |
| Next Review Date |  |

## 1. Purpose

Define end-to-end steps for onboarding and offboarding personnel to ensure timely access enablement/removal,
training, asset issuance/return, and facility credential handling.

## 2. Roles

HR, Hiring Manager, IT Operations, Security Engineering, Facilities/Guard Desk, ISMS.

## 3. Prerequisites

Approved offer/termination notice; ticket created; role profile; Microsoft Entra ID and SSO integrations; Duo for
RDP/SSH; workstation inventory; access portal for badges/kiosk.

## 4. Procedure

1. Pre-Onboarding: HR opens ticket with start date, manager, role. IT stages endpoint per Workstation Baseline
   and creates accounts pending Day 1 activation. Facilities pre-enroll badge in access portal.
2. Day 1 Activation: IT activates Entra ID account, enables SSO and MFA; issues endpoint; confirms AUP and
   mandatory training assignments. Facilities verifies identity, provides badge and kiosk enrollment (badge/face/PIN).
3. Access Provisioning: Manager requests role-based access via JML workflow (see PR04). IT grants least-privilege
   entitlements; vault/service access as required; log evidence.
4. Role Changes: Process via JML—revoke obsolete rights, validate SoD, refresh training if elevated privileges.
5. Offboarding Initiation: Upon notice or termination event, HR opens urgent ticket with time of access cutoff.
6. Logical Revocation: Disable Entra ID sign-in, revoke tokens, remove groups/SSO roles, disable VPN and Duo for
   RDP/SSH; rotate affected secrets/keys.
7. Physical Revocation: Facilities deactivates badge in portal; guard recovers badge/equipment if onsite; kiosk
   status updated. Document returns; initiate replacement charges if needed.
8. Evidence & Closure: Store approvals, timestamps, logs, and inventory updates in records repository. For systems
   that cannot forward logs, export and attach artifacts.

## 5. Records & Evidence

Onboarding/offboarding tickets, approvals, training records, badge logs, device inventory, directory/app logs.

## 6. Metrics

Time-to-productive, deprovisioning SLA, percentage of assets recovered, exceptions closed.

## 7. Revision History

| Version | Date       | Author | Description |
|---------|------------|--------|-------------|
| 1.0.0   | 2025-11-05 |        | Initial onboarding & offboarding procedure. |


