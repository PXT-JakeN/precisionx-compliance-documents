---
title: "Workstation Baseline (Windows/macOS/Linux)"
doc_type: "Standard"
id: "GRS-ISMS-STD-001"
version: "1.1.0"
status: "Draft"
owner: "IT Operations Lead"
approver: "Executive Management, GridSite Technology LLC"
approval_date: ""
effective_date: ""
next_review_date: ""
related_documents:
  - ../policies/Identity-and-Access-Management-Policy.md
  - ../policies/Authentication-and-MFA-Policy.md
  - ../policies/Logging-Monitoring-and-SIEM-Policy.md
  - ../policies/Information-Security-Policy.md
  - ../procedures/Access-Provisioning-and-Deprovisioning-Procedure.md
references:
  - ISO/IEC 27002:2022 (endpoint security, encryption, logging)
  - AICPA SOC 2 (CC6, CC7)
---

## Document Control

| Field | Value |
|-------|-------|
| Title | Workstation Baseline (Windows/macOS/Linux) |
| Document ID | GRS-ISMS-STD-001 |
| Version | 1.0.0 |
| Status | Draft |
| Owner | IT Operations Lead |
| Approver | Executive Management, GridSite Technology LLC |
| Approval Date |  |
| Effective Date |  |
| Next Review Date |  |

## 1. Purpose

Define mandatory configuration and operational requirements for GridSite workstations. Devices are Azure AD
(Microsoft 365 Entra ID) joined; GridSite does not operate traditional on‑premises Active Directory. The
baseline emphasizes identity‑centric controls, encryption, patching, network hygiene, and evidencing.

## 2. Scope

All company‑owned workstations (Windows, macOS, Linux) used by employees and contractors. BYOD usage is
limited: GridSite is a Windows‑first environment, and personal devices (including phones and tablets) may be
used only for PUBLIC and CONFIDENTIAL information. INTERNAL and RESTRICTED information may be accessed
or processed only on company‑approved and managed systems. Unmarked information is treated as INTERNAL
until classified. BYOD must be explicitly approved and meet mobile/endpoint controls where applicable.

## 3. Baseline Requirements

Workstations authenticate users through Microsoft 365 SSO with MFA, aligning device identity to user identity.
Local administrative rights are restricted to approved technicians; standard users operate without admin rights.
Full‑disk encryption is mandatory (BitLocker, FileVault, or LUKS), and screen locks engage after short periods of
inactivity. Operating systems and browsers receive security updates on a defined cadence; critical patches are
prioritized. Endpoint protection (EDR/AV) runs continuously with tamper protection enabled. Storage of
secrets or credentials in plaintext is prohibited; approved password managers or platform keychains must be
used.

Networking favors wired connections where practical to provide stable performance and reduced RF exposure.
When wireless is necessary, devices connect using the UniFi Identity application and the office Wi‑Fi is
configured for the UniFi one‑click workflow to simplify strong authentication and reduce misconfiguration risk.
Guest and unmanaged networks are logically separated from corporate segments. DNS, NTP, and proxy
settings follow corporate configuration. When logging integrations exist, security‑relevant events are
forwarded to the SIEM; where a platform cannot forward events, administrators conduct manual reviews on a
defined cadence and retain screenshots/exports as evidence.

All company‑owned workstations are backed up using iDrive360 according to centrally managed schedules;
backup status is monitored and failures remediated promptly.

Removable media usage is restricted to business need and scanned prior to use; sensitive data must be
encrypted at rest and in transit. Browsers are configured with safe defaults (blocking dangerous downloads and
third‑party cookies where feasible) and enterprise policies to enforce updates and extensions controls.

## 4. Control Requirements

| Req ID | Requirement | Implementation | Evidence |
|--------|-------------|----------------|----------|
| WS-01 | Azure AD join | Devices are Azure AD (Entra ID) joined; no on‑prem AD | Device inventory; join status |
| WS-02 | Account control | Standard user by default; no shared local accounts; exceptions per policy | Local group membership reports |
| WS-03 | MFA & SSO | Microsoft 365 SSO with MFA for interactive access | IdP policies; auth logs/exports |
| WS-04 | Disk encryption | BitLocker/FileVault/LUKS enabled with escrow of recovery info | MDM or config reports |
| WS-05 | Patching | OS and browser security updates on defined cadence; critical fast‑track | Patch compliance reports |
| WS-06 | EDR/AV | Endpoint protection with tamper protection enabled | EDR console screenshots/exports |
| WS-07 | Network | Prefer wired; otherwise UniFi Identity one‑click Wi‑Fi on corporate SSIDs | Network config; UniFi admin exports |
| WS-08 | Segmentation | Corporate, guest, and unmanaged separated; no bridging | VLAN/SSID diagrams |
| WS-09 | Logging | Forward to SIEM when supported; otherwise manual review cadence and evidencing | SIEM source list; review records |
| WS-10 | Removable media | Restricted, scanned, and encrypted for sensitive data | Ticket approvals; scan logs |
| WS-11 | Browser hardening | Enterprise policies for updates and dangerous download protection | Browser policy exports |
| WS-12 | BYOD classification | BYOD limited to PUBLIC/CONFIDENTIAL; INTERNAL/RESTRICTED on managed devices only | AUP/acknowledgments |
| WS-13 | Endpoint backups | Company‑owned devices backed up with iDrive360 | iDrive360 console reports |

## 5. Roles and Responsibilities

IT Operations maintains baseline configurations and compliance reporting. Security Operations monitors
events and validates evidencing. System Owners and users cooperate with remediation and reviews.

## 6. Revision History

| Version | Date       | Author | Description |
|---------|------------|--------|-------------|
| 1.1.0   | 2025-11-05 |        | Added BYOD and sensitivity label handling; mandated iDrive360 backups. |
| 1.0.0   | 2025-11-05 |        | Initial Azure AD and UniFi‑aligned workstation baseline. |


