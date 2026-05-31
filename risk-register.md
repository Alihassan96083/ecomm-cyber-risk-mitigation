# Risk Register
**Project:** Cybersecurity Risk Assessment and Mitigation Strategy for an E-Commerce Platform  
**Last Updated:** May 2026  

---

## Risk Matrix

| Risk ID | Description | Probability (1–5) | Impact (1–5) | Score | Priority | Response Strategy | Action Plan |
|---------|-------------|:-----------------:|:------------:|:-----:|----------|-------------------|-------------|
| R1 | New zero-day vulnerability discovered during project | 3 | 5 | 15 | Medium | Mitigate | Allocate 2 days buffer for emergency patches; monitor security advisories daily. |
| R2 | Key team member resigns | 3 | 4 | 12 | Medium | Mitigate | Cross-train two people on each critical task; document all processes. |
| R3 | Production downtime exceeds agreed 2 hours | 2 | 5 | 10 | Medium | Mitigate | Schedule changes after business hours; create a rollback plan for each change. |
| R4 | Penetration test crashes the live site | 2 | 5 | 10 | Medium | Avoid | Run penetration tests on a staging environment first, not on production. |
| R5 | Budget cut | 2 | 5 | 10 | Medium | Accept | Prioritise critical controls only; maintain a contingency of $5,000 (10% of budget). |
| R6 | Major compliance requirement changes mid-project | 1 | 5 | 5 | Low | Accept | Review regulations weekly; engage legal advisor if needed. |

---

## Priority Legend

| Risk Score | Priority |
|:----------:|----------|
| 16 – 25 | 🔴 High – must be addressed immediately |
| 8 – 15 | 🟡 Medium – address after high risks |
| 1 – 7 | 🟢 Low – monitor only |

---

## Issues Log

| Issue ID | Date | Description | Priority | Owner | Status | Resolution Plan |
|----------|------|-------------|----------|-------|--------|-----------------|
| ISS-001 | Day 5 | Firewall rule misconfigured during vulnerability scan | High | Team Lead | Resolved | Rolled back to previous config; added peer review for all future changes. |

---

*This document is a living record. It will be updated weekly during the project status meeting by the Project Manager.*
