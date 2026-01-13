---
title: "Endpoint Security Policy"
doc_type: "Policy"
id: "GRS-ISMS-POL-012"
version: "1.1.0"
status: "Draft"
owner: "IT Operations Lead"
program_manager: "Josh Mayorga, Compliance Manager"
approver: "Executive Management, GridSite Technology LLC"
approval_date: ""
effective_date: ""
next_review_date: ""
classification: "Internal – Controlled"
organization: "GridSite Technology LLC and its operating subsidiaries"
related_documents:
  - ../standards/Workstation-Baseline.md
  - ./Data-Classification-and-Handling-Policy.md
  - ./Authentication-and-MFA-Policy.md
  - ./Backup-and-Restore-Policy.md
references:
  - ISO/IEC 27002:2022 (endpoint protection)
---

## Document Control

| Field | Value |
|-------|-------|
| Title | Endpoint Security Policy |
| Document ID | GRS-ISMS-POL-012 |
| Version | 1.1.0 |
| Status | Draft |
| Owner | IT Operations Lead |
| Program Manager | Josh Mayorga, Compliance Manager |
| Approver | Executive Management, GridSite Technology LLC |
| Approval Date |  |
| Effective Date |  |
| Next Review Date |  |

## 1. Purpose

Define endpoint protection requirements for company‑owned devices and usage constraints for BYOD consistent
with data classification and workstation baseline controls.

## 2. Scope

All company‑owned endpoints and any personal devices used to access corporate resources.

## 3. Policy Statements

Company‑owned endpoints are Azure AD joined, use MFA for access, enforce full‑disk encryption, run approved
EDR/AV, and receive security patches on a defined cadence. iDrive360 is used for workstation backups.

BYOD may be used only for PUBLIC and CONFIDENTIAL information via managed Microsoft 365 applications
(Outlook, Teams, Word, Excel, PowerPoint, SharePoint). Microsoft Intune App Protection Policies enforce a
6-digit app PIN, 30-minute inactivity timeout, and block copy/paste to unmanaged applications. INTERNAL and
RESTRICTED information may be accessed or processed only on managed devices.

Wireless uses UniFi Identity one‑click on corporate SSIDs; guest/unmanaged networks are segmented. Removable
media is restricted and must be encrypted for sensitive data.

## 4. Exceptions

Exceptions require risk assessment, approvals, and compensating controls with expiry.

## 5. Compliance Measurement

Measured via EDR coverage, patch compliance, backup status, and periodic audits.

## 6. Revision History

| Version | Date       | Author | Description |
|---------|------------|--------|-------------|
| 1.0.0   | 2025-11-05 |        | Initial endpoint security policy aligned to workstation baseline and labels. |
| 1.1.0   | 2026-01-13 | Jake Neal | Updated BYOD section: Added managed Microsoft 365 apps (Outlook, Teams, Word, Excel, PowerPoint, SharePoint) and Intune App Protection Policy controls (6-digit PIN, 30-minute timeout, copy/paste restrictions). Aligned with Mobile Device & BYOD Policy v1.3.0. |


