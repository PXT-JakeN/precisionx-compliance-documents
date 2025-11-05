---
title: "Cryptography & Key Management Policy"
doc_type: "Policy"
id: "GRS-ISMS-POL-016"
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
  - ../standards/Secrets-Management-Standard.md
  - ../standards/Cloud-Landing-Zone-Standard.md
  - ./Data-Classification-and-Handling-Policy.md
references:
  - NIST SP 800-57; NIST SP 800-131A; FIPS 140‑validated modules
---

## Document Control

| Field | Value |
|-------|-------|
| Title | Cryptography & Key Management Policy |
| Document ID | GRS-ISMS-POL-016 |
| Version | 1.0.0 |
| Status | Draft |
| Owner | Security Engineering Lead |
| Program Manager | Josh Mayorga, Compliance Manager |
| Approver | Executive Management, GridSite Technology LLC |
| Approval Date |  |
| Effective Date |  |
| Next Review Date |  |

## 1. Purpose

Set requirements for approved algorithms, generation, storage, rotation, and retirement of cryptographic keys
and certificates.

## 2. Scope

All use of cryptography for data at rest, data in transit, authentication, and code signing.

## 3. Policy Statements

Use industry‑accepted algorithms and key sizes (e.g., TLS 1.2+ with modern ciphers; AES‑GCM; SHA‑256+; RSA
2048+/ECC P‑256+). Keys are generated using approved randomness and stored in an approved vault or HSM
where available. Private keys are never stored unencrypted or checked into source code. Certificates and keys
have defined rotation intervals and replacement processes; expired and revoked keys are removed promptly.
All cryptographic modules should be FIPS 140 validated where feasible. Secrets and keys are transmitted over
secure channels and access is restricted to least privilege; all access is auditable. Compromise of keys or
certificates is treated as a security incident with immediate rotation and impact analysis.

## 4. Exceptions

Exceptions require risk assessment, approvals, and compensating controls.

## 5. Compliance Measurement

Measured via key inventory reviews, certificate expiry dashboards, and audit sampling.

## 6. Revision History

| Version | Date       | Author | Description |
|---------|------------|--------|-------------|
| 1.0.0   | 2025-11-05 |        | Initial cryptography & key management policy. |


