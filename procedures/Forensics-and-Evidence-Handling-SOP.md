---
title: "Forensics & Evidence Handling SOP"
doc_type: "Procedure"
id: "GRS-ISMS-PRC-018"
version: "1.0.0"
status: "Draft"
owner: "Security Operations Lead"
program_manager: "Josh Mayorga, Compliance Manager"
approver: "Executive Management, GridSite Technology LLC"
approval_date: ""
effective_date: ""
next_review_date: ""
classification: "Internal – Controlled"
organization: "GridSite Technology LLC and its operating subsidiaries"
related_documents:
  - ../policies/Incident-Response-Policy.md
  - ../policies/Records-Management-and-Evidence-Policy.md
  - ../standards/Logging-and-Time-Sync-Standard.md
---

## Document Control

| Field | Value |
|-------|-------|
| Title | Forensics & Evidence Handling SOP |
| Document ID | GRS-ISMS-PRC-018 |
| Version | 1.0.0 |
| Status | Draft |
| Owner | Security Operations Lead |
| Program Manager | Josh Mayorga, Compliance Manager |
| Approver | Executive Management, GridSite Technology LLC |
| Approval Date |  |
| Effective Date |  |
| Next Review Date |  |

## 1. Purpose

Define standardized steps to collect, preserve, analyze, and transfer digital evidence while maintaining chain of
custody and admissibility.

## 2. Roles

Incident Commander, Forensics Handler, Custodian, Legal, ISMS.

## 3. Prerequisites

Time-synced systems; approved tools (write blockers, imaging tools); secure evidence storage; chain-of-custody
forms; process for manual log export when forwarding is not possible.

## 4. Procedure

1. Prepare: Assign roles; create evidence log; photograph/record initial state where applicable.
2. Collect: Acquire bit-for-bit images or logical exports; use write blockers; capture volatile data when needed.
3. Preserve: Hash all artifacts (pre/post); seal and label media; store in tamper-evident containers or encrypted
   evidence vaults; restrict access to authorized custodians only.
4. Document: Maintain chain-of-custody for each transfer; record date/time (UTC), handlers, purpose, and hashes.
5. Analyze: Work from verified copies in a controlled workspace; record all steps and tools with versions.
6. Transfer/Disclose: Coordinate with Legal; redact where required; use secure transfer methods; update custody.
7. Retain/Dispose: Retain per Records Management and legal hold; securely destroy upon release with certificates.

## 5. Records & Evidence

Chain-of-custody forms, imaging logs, hashes, analysis notes, exported logs, storage access logs.

## 6. Metrics

Completeness of custody records, hash verification pass rate, time from collection to analysis readiness.

## 7. Revision History

| Version | Date       | Author | Description |
|---------|------------|--------|-------------|
| 1.0.0   | 2025-11-05 |        | Initial forensics & evidence handling SOP. |


