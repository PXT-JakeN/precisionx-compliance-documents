---
title: "Access Request Form"
doc_type: "Template"
id: "GRS-ISMS-TMP-004"
version: "1.0.0"
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
  - ../policies/Access-Control-Policy.md
  - ../policies/Identity-and-Access-Management-Policy.md
  - ../policies/Privileged-Access-Management-Policy.md
  - ../procedures/Access-Provisioning-and-Deprovisioning-Procedure.md
---

## Document Control

| Field | Value |
|-------|-------|
| Title | Access Request Form |
| Document ID | GRS-ISMS-TMP-004 |
| Version | 1.0.0 |
| Status | Draft |
| Owner | ISMS Manager |
| Program Manager | Josh Mayorga, Compliance Manager |
| Approver | Executive Management, GridSite Technology LLC |
| Approval Date |  |
| Effective Date |  |
| Next Review Date |  |

## Requestor Information

| Field | Entry |
|-------|-------|
| Name |  |
| Department/Role |  |
| Manager |  |
| Employment Type (Employee/Contractor) |  |

## Access Details

| Field | Entry |
|-------|-------|
| System/Application |  |
| Environment (Prod/Non‑Prod) |  |
| Requested Role(s)/Permissions |  |
| Justification (business need) |  |
| Start/End Date (if temporary) |  |

Notes:
- Use Microsoft 365 SSO/SAML/OIDC where available; MFA required for all privileged/remote access.
- For Windows servers, use Entra ID; for Linux, use non‑privileged accounts with sudo elevation.
- Ensure SoD: confirm no conflicts with existing roles per Access Control Matrix.

## Approvals

| Role | Name | Date | Decision |
|------|------|------|----------|
| Requestor |  |  |  |
| Manager |  |  |  |
| System Owner |  |  |  |
| ISMS/GRC (SoD review) |  |  |  |
| Finance Owner (financial systems) |  |  |  |

## Provisioning Checklist

- [ ] Account created/role assigned
- [ ] MFA enrolled (Duo for SSH/RDP where applicable)
- [ ] Logging enabled; evidence export configured if forwarding unavailable
- [ ] User notified and usage guidelines shared


