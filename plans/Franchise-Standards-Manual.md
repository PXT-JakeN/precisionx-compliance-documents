---
title: "Franchise Standards Manual"
doc_type: "System Description"
id: "GRS-ISMS-SD-008"
version: "1.0.0"
status: "Draft"
owner: "Franchise Program Director"
program_manager: "Josh Mayorga, Compliance Manager"
approver: "Executive Management, GridSite Technology LLC"
approval_date: ""
effective_date: ""
next_review_date: ""
classification: "Internal – Controlled"
organization: "GridSite Technology LLC and its operating subsidiaries"
related_documents:
  - ../standards/Franchise-Technical-Baseline-Standard.md
  - ../standards/Facility-Physical-Security-Standard.md
  - ../standards/NOC-Build-Standard.md
  - ../procedures/Franchise-Site-Onboarding-Procedure.md
  - ../procedures/Franchise-Compliance-Audit-Procedure.md
---

## Document Control

| Field | Value |
|-------|-------|
| Title | Franchise Standards Manual |
| Document ID | GRS-ISMS-SD-008 |
| Version | 1.0.0 |
| Status | Draft |
| Owner | Franchise Program Director |
| Program Manager | Josh Mayorga, Compliance Manager |
| Approver | Executive Management, GridSite Technology LLC |
| Approval Date |  |
| Effective Date |  |
| Next Review Date |  |

## 1. Purpose

Provide an authoritative manual of technical, physical, and operational standards required for participation in the
Powered by GridSite franchise program.

## 2. Governance & Compliance

Franchisees must adopt the Franchise Technical Baseline (S20) and comply with applicable GridSite standards and
policies. Compliance is verified during onboarding and through periodic audits (PR33) and telemetry checks.

## 3. Site Build & Access Management

Sites must deploy the integrated access portal and kiosk with three‑factor authentication (badge, face, PIN), ID
validation at enrollment, background checks for staff/vendors, escort controls (max five escortees), guard terminal
fallback, and auditable logs with an integrated appeal process.

## 4. Network & Connectivity

Secure tunnels connect sites to GridSite cloud environments; admin ingress is restricted to NOC networks. Implement
segmentation (management/control/data/guest), default‑deny firewalls, and WAF protections for internet‑facing services.
Corporate Wi‑Fi shall be provisioned via UniFi Identity; workstations prefer wired connectivity.

## 5. Identity, Access & Endpoints

Use Microsoft 365 SSO with SAML/OIDC; enforce MFA for all privileged and remote access; Duo MFA for SSH/RDP. Entra ID
for Windows servers; named non‑privileged Linux accounts with sudo elevation. BYOD access is limited to PUBLIC and
CONFIDENTIAL data; INTERNAL/RESTRICTED data requires managed endpoints. Apply S01 and S02 baselines.

## 6. Monitoring, Logging & Evidence

Centralize logs and time sync; when forwarding is not possible, perform manual exports to the evidence repository on
defined cadences. Enable DCIM telemetry and maintain CCTV coverage with retention and export procedures.

## 7. Backups & Continuity

Encrypt and protect backups with immutability for critical data; validate quarterly restores. Register endpoints with
iDrive360 and meet success SLOs. Participate in BC/DR exercises and record outcomes per templates.

## 8. Operations & Change Control

Maintain an asset inventory/CMDB; onboard vendors via due diligence; use formal change control with maintenance MOPs; 
record exceptions and compensating controls with approvals and remediation timelines.

## 9. Performance & Customer Commitments

Monitor capacity and availability; meet SLA targets; document variances and corrective actions in reports and audit
packs. Keep customer CUEC disclosures current for shared responsibilities.

## 10. Non‑Conformance

Material deviations require approved exceptions; repeated or unremediated non‑conformance may result in suspension of
connectivity until resolved.

## 11. Revision History

| Version | Date       | Author | Description |
|---------|------------|--------|-------------|
| 1.0.0   | 2025-11-05 |        | Initial franchise standards manual. |


