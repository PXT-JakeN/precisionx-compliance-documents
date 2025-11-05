---
title: "Segregation of Duties Policy"
doc_type: "Policy"
id: "GRS-ISMS-POL-035"
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
  - ./Identity-and-Access-Management-Policy.md
  - ./Change-and-Release-Management-Policy.md
  - ./Access-Control-Policy.md
  - ./Financial-Controls-Policy.md
  - ../standards/CI-CD-Security-Standard.md
references:
  - ISO/IEC 27001:2022 A.6; A.8; SOC 2 CC6/CC7; SOC 1 ICFR principles
---

## Document Control

| Field | Value |
|-------|-------|
| Title | Segregation of Duties Policy |
| Document ID | GRS-ISMS-POL-035 |
| Version | 1.0.0 |
| Status | Draft |
| Owner | ISMS Manager |
| Program Manager | Josh Mayorga, Compliance Manager |
| Approver | Executive Management, GridSite Technology LLC |
| Approval Date |  |
| Effective Date |  |
| Next Review Date |  |

## 1. Purpose

Establish principles that prevent a single individual from controlling conflicting stages of sensitive processes,
reducing the risk of error, fraud, and unauthorized changes across technical and financial domains.

## 2. Scope

All business processes and information systems within ISMS scope, including SaaS platforms, GridColo
operations, finance functions relevant to ICFR, CI/CD pipelines, and infrastructure administration.

## 3. Policy Statements

Conflicting duties shall be separated wherever feasible. At minimum, development, approval, and deployment of
changes must involve distinct roles; emergency changes require retrospective approval. Access provisioning,
approval, and review shall be performed by different individuals or roles. Production data access for developers is
prohibited by default and requires time‑bound, approved elevation with logging. In CI/CD, code authorship,
review, and release approvals shall be distinct with enforced branch protections. Financial processes (e.g.,
customer billing, revenue recognition, and reconciliation) must maintain segregation between initiation,
authorization, custody, and recording. Where full separation is impractical, detective and compensating controls
shall be implemented (e.g., enhanced logging with independent review, dual approval, session recording). SoD
matrices are maintained in the Access Control Matrix and reviewed at least quarterly.

## 4. Exceptions

Exceptions require documented risk assessment, ISMS approval, and compensating controls with defined expiry.

## 5. Compliance Measurement

Measured via access reviews, change record sampling, CI/CD audit trails, and finance control testing.

## 6. Revision History

| Version | Date       | Author | Description |
|---------|------------|--------|-------------|
| 1.0.0   | 2025-11-05 |        | Initial segregation of duties policy. |


