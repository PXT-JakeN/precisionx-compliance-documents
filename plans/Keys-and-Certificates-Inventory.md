---
title: "Keys & Certificates Inventory"
doc_type: "Register"
id: "GRS-ISMS-REG-006"
version: "1.0.0"
status: "Draft"
owner: "Security Engineering Lead"
program_manager: "Josh Mayorga, Compliance Manager"
approver: "Executive Management, GridSite Technology LLC"
approval_date: ""
effective_date: ""
next_review_date: ""
classification: "Internal – Controlled"
organization: "GridSite Technology LLC and its operating subsidiaries"
related_documents:
  - ../policies/Cryptography-and-Key-Management-Policy.md
  - ../standards/Secrets-Management-Standard.md
  - ../standards/Cloud-Landing-Zone-Standard.md
  - ../policies/Records-Management-and-Evidence-Policy.md
---

## Document Control

| Field | Value |
|-------|-------|
| Title | Keys & Certificates Inventory |
| Document ID | GRS-ISMS-REG-006 |
| Version | 1.0.0 |
| Status | Draft |
| Owner | Security Engineering Lead |
| Program Manager | Josh Mayorga, Compliance Manager |
| Approver | Executive Management, GridSite Technology LLC |
| Approval Date |  |
| Effective Date |  |
| Next Review Date |  |

## 1. Purpose

Track cryptographic keys, certificates, and CAs to enforce lifecycle controls, rotation, and compliance.

## 2. Required Fields

Item ID; type (TLS cert, code signing, KMS key, database key); system/endpoint; owner; algorithm/length; issuance/
activation/expiration dates; storage location (vault/HSM/KMS); rotation cadence; dependent services; mTLS usage;
revocation status; last audit date.

## 3. Maintenance

Automate discovery where possible; alert 60/30/7 days before expiry; rotate per standards; export evidence if the
platform cannot forward to the repository.

## 4. Revision History

| Version | Date       | Author | Description |
|---------|------------|--------|-------------|
| 1.0.0   | 2025-11-05 |        | Initial keys & certificates inventory. |


