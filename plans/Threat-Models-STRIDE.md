---
title: "Threat Models (STRIDE) – by system"
doc_type: "System Description"
id: "GRS-ISMS-SD-006"
version: "1.0.0"
status: "Draft"
owner: "Security Architecture Lead"
program_manager: "Josh Mayorga, Compliance Manager"
approver: "Executive Management, GridSite Technology LLC"
approval_date: ""
effective_date: ""
next_review_date: ""
classification: "Internal – Controlled"
organization: "GridSite Technology LLC and its operating subsidiaries"
related_documents:
  - ../policies/Secure-Software-Development-Policy.md
  - ../standards/API-Security-Standard.md
  - ../standards/CI-CD-Security-Standard.md
---

## Document Control

| Field | Value |
|-------|-------|
| Title | Threat Models (STRIDE) – by system |
| Document ID | GRS-ISMS-SD-006 |
| Version | 1.0.0 |
| Status | Draft |
| Owner | Security Architecture Lead |
| Program Manager | Josh Mayorga, Compliance Manager |
| Approver | Executive Management, GridSite Technology LLC |
| Approval Date |  |
| Effective Date |  |
| Next Review Date |  |

## 1. Purpose

Standardize and catalog system threat models using STRIDE, informing design and testing.

## 2. Method

Decompose system with data flows; enumerate STRIDE threats; record mitigations (authN/Z, input validation, rate
limits, encryption, secrets handling, logging); trace to tests and detections.

## 3. Artifacts & Maintenance

Store DFDs, threat tables, and mitigation status; review at major releases; export artifacts if tooling cannot forward.


