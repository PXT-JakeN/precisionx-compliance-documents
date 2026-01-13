---
title: "Data Classification & Handling Policy"
doc_type: "Policy"
id: "GRS-ISMS-POL-006"
version: "1.2.0"
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
  - ./Information-Security-Policy.md
  - ./Access-Control-Policy.md
  - ./Identity-and-Access-Management-Policy.md
  - ./Backup-and-Restore-Policy.md
  - ./Records-Management-and-Evidence-Policy.md
  - ../standards/Workstation-Baseline.md
  - ../standards/Server-Baseline.md
references:
  - ISO/IEC 27001:2022 Annex A (Information classification & handling)
  - ISO/IEC 27002:2022 (8.10–8.12)
  - AICPA SOC 2 (CC6, CC7)
iso_clauses: ["8"]
soc2_criteria: ["CC6","CC7"]
bcms_clauses: []
---

## Document Control

| Field | Value |
|-------|-------|
| Title | Data Classification & Handling Policy |
| Document ID | GRS-ISMS-POL-006 |
| Version | 1.2.0 |
| Status | Draft |
| Owner | ISMS Manager |
| Program Manager | Josh Mayorga, Compliance Manager |
| Approver | Executive Management, GridSite Technology LLC |
| Approval Date |  |
| Effective Date |  |
| Next Review Date |  |
| Classification | Internal – Controlled |
| Organization | GridSite Technology LLC and its operating subsidiaries |

## 1. Purpose

Establish a consistent scheme for classifying information and prescriptive handling rules to protect PrecisionX
and GridSite data across its lifecycle. This policy codifies label definitions, marking conventions, permitted
access channels (including BYOD limitations), and storage/transmission requirements.

## 2. Scope

All information processed by PrecisionX and GridSite, regardless of format or storage location, and all
personnel and third parties who access such information.

## 3. Roles and Responsibilities

Executive Management approves this policy and resources for implementation. The ISMS Manager owns the
classification scheme, monitoring, and improvement. Asset and Data Owners classify their information assets
and ensure handling rules are followed. All personnel apply correct labels and handle data accordingly.

## 4. Classification Scheme and Marking

The following labels SHALL be applied. Unmarked information SHALL be treated as INTERNAL until classified.

| Label | Marking | Description |
|-------|---------|-------------|
| PUBLIC | PUBLIC | Content approved for anyone, inside or outside PrecisionX/GridSite. |
| CONFIDENTIAL | CONFIDENTIAL | Sensitive business information limited to a department, project, or third parties under NDA. |
| INTERNAL | INTERNAL | Non‑public internal work product not intended for external sharing. |
| RESTRICTED | RESTRICTED | Most sensitive information (customer data, security/infrastructure, investor materials). |

Marking conventions: Apply the label in document properties or headers/footers, or via Microsoft 365
sensitivity labels where available. For structured systems, record the label in metadata or access policies.

## 5. Handling Rules by Label

Handling requirements are set out below. Where a system cannot technically enforce a control, equivalent
compensating measures and documented reviews are required.

| Aspect | PUBLIC | CONFIDENTIAL | INTERNAL | RESTRICTED |
|--------|--------|--------------|---------|------------|
| Access | Unrestricted | Role‑based; NDA required for external sharing | PrecisionX/GridSite personnel only | Strict need‑to‑know; minimal access |
| BYOD | Managed M365 apps only | Managed M365 apps only | Not allowed | Not allowed |
| Storage | Any approved platform | Approved corporate platforms | Managed corporate systems only | Managed corporate systems only |
| Transmission | No special controls | Encrypted channels; verify NDA | Encrypted channels | Encrypted channels; pre‑approved recipients |
| Sharing | Public channels | With NDA and business need | Internal only | Internal least‑privilege; external only if contractually required |
| Backup | Standard | Encrypted backups per policy | Encrypted backups per policy | Encrypted, immutable backups; access logged |
| Disposal | Normal deletion | Secure deletion | Secure deletion | Secure deletion with verification |

Notes and examples:
- PUBLIC: Public websites, marketing materials.
- CONFIDENTIAL: Departmental plans, project documents; third‑party sharing requires active NDA and documented business need.
- INTERNAL: General internal work product not intended for external sharing.
- RESTRICTED: Customer data; security/infrastructure details; investor materials.

## 6. BYOD and Channel Restrictions

PrecisionX is a Windows‑first environment. Personal devices (including phones and tablets) MAY be used only
to access the following Microsoft 365 managed applications for PUBLIC and CONFIDENTIAL information:
Outlook, Teams, Word, Excel, PowerPoint, and SharePoint. No other applications or systems are permitted on
BYOD devices.

Microsoft Intune App Protection Policies enforce the following controls on BYOD devices:
- 6-digit PIN required to open managed applications
- PIN re-entry required after 30 minutes of inactivity
- Copy and paste from managed apps to personal apps is blocked
- Saving to personal cloud storage is blocked

INTERNAL and RESTRICTED information MAY ONLY be accessed or processed on company‑approved and managed
systems. Unmarked data is treated as INTERNAL until labeled.

## 7. Storage, Transmission, and Evidence

Store data on approved systems with encryption at rest and in transit commensurate with label. Use Microsoft
365 sensitivity labels and access controls where available. Retain evidence of NDA status for CONFIDENTIAL
sharing and approvals for any RESTRICTED disclosures. Where integrations are unavailable, capture
screenshots/exports to evidence compliance.

## 8. Exceptions

Exceptions to handling rules require a documented risk assessment, approval by the ISMS Manager (and
Executive Management for RESTRICTED), and compensating controls with expiry and review.

## 9. Compliance Measurement

Compliance is measured via audit sampling of labels, sharing records (including NDAs), access controls,
backups, and disposal evidence. Findings drive corrective actions.

## 10. Revision History

| Version | Date       | Author | Description |
|---------|------------|--------|-------------|
| 1.0.0   | 2025-11-05 |        | Initial policy codifying labels, BYOD limits, and handling rules. |
| 1.1.0   | 2026-01-13 | Jake Neal | Clarified BYOD restrictions: personal devices may only access Microsoft Teams and Outlook for PUBLIC and CONFIDENTIAL data. Aligned with Mobile Device & BYOD Policy v1.2.0. |
| 1.2.0   | 2026-01-13 | Jake Neal | Expanded BYOD managed apps to include Word, Excel, PowerPoint, and SharePoint. Added Intune App Protection Policy controls: 6-digit app PIN, 30-minute inactivity timeout, and copy/paste restrictions. Aligned with Mobile Device & BYOD Policy v1.3.0. |


