---
title: "Franchise Site Onboarding Checklist"
doc_type: "Template"
id: "GRS-ISMS-TMP-007"
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
  - ../procedures/Franchise-Site-Onboarding-Procedure.md
  - ../standards/Facility-Physical-Security-Standard.md
  - ../standards/NOC-Build-Standard.md
---

## Document Control

| Field | Value |
|-------|-------|
| Title | Franchise Site Onboarding Checklist |
| Document ID | GRS-ISMS-TMP-007 |
| Version | 1.0.0 |
| Status | Draft |
| Owner | Franchise Program Director |
| Program Manager | Josh Mayorga, Compliance Manager |
| Approver | Executive Management, GridSite Technology LLC |
| Approval Date |  |
| Effective Date |  |
| Next Review Date |  |

## Use

Use this checklist to validate technical, security, and operational readiness of new franchise sites.

## Checklist

- [ ] Secure tunnel to cloud environments configured and verified
- [ ] NOC live AV link and surge participation tested
- [ ] Portal/kiosk deployed; enrollment workflow tested (badge, face, PIN)
- [ ] Guard terminal fallback validated; paper process documented
- [ ] Escort workflow enforced with limit of five escortees per escort
- [ ] Wired workstation connectivity verified; UniFi Identity Wi‑Fi configured for secure access
- [ ] Duo MFA enforced for SSH/RDP; Entra ID for Windows servers; sudo model on Linux
- [ ] Logging/time sync configured; evidence exports scheduled where forwarding unavailable
- [ ] Backup endpoints (including iDrive360) registered and tested restore
- [ ] Physical access: exterior‑to‑lobby gating and sign‑in activation rules validated
- [ ] CCTV retention and export procedure validated
- [ ] Site personnel trained on incident/maintenance procedures; contacts registered with NOC
- [ ] Initial compliance audit scheduled; deficiencies tracked to closure


