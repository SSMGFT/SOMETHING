
# Appendix A-01 - High-Yield CISSP Domain 6 Exam Traps

> Version: 1.4

# Purpose

These are the most common distinctions tested in Domain 6.

---

| If the question says... | Think... | Don't Confuse With |
|-------------------------|----------|--------------------|
| Identify weaknesses | Vulnerability Assessment | Penetration Test |
| Prove exploitability | Penetration Test | Vulnerability Assessment |
| Verify compliance | Audit | Assessment |
| Objective proof | Evidence | Opinion |
| Confidence controls work | Assurance | Security |
| Built correctly | Verification | Validation |
| Built the correct solution | Validation | Verification |
| Random inputs | Fuzz Testing | Mutation Testing |
| Artificial defects in code | Mutation Testing | Fuzz Testing |
| No code execution | Static Testing | Dynamic Testing |
| Execute application | Dynamic Testing | Static Testing |
| One component | Unit Test | Integration Test |
| Components together | Integration Test | System Test |
| Whole application | System Test | Acceptance Test |
| Business approval | User Acceptance Test | System Test |
| Existing features still work | Regression Test | Unit Test |
| Collect logs | Logging | SIEM |
| Correlate logs | SIEM | Log Server |
| Normal behaviour | Baseline | Alert |
| Ongoing visibility | Continuous Monitoring | One-time Assessment |
| Executive audience | Business Impact | Technical Detail |
| Technical audience | Detailed Findings | Executive Summary |
| Credentialed scan | Internal visibility | External attack simulation |
| External attacker simulation | Non-credentialed Scan | Credentialed Scan |
| Authorization required | Rules of Engagement | Scope |
| Cloud assurance | SOC Report | Vulnerability Scan |

---

# CISSP Decision Order

```text
Business
    │
    ▼
Risk
    │
    ▼
Policy
    │
    ▼
Assessment
    │
    ▼
Evidence
    │
    ▼
Decision
    │
    ▼
Implementation
```

When two answers appear technically correct, prefer the one that:

1. Reduces business risk.
2. Follows the correct process.
3. Uses objective evidence.
4. Minimizes business disruption.
5. Aligns with governance.

---

# 60-Second Review

- Assessment finds.
- Pen Test proves.
- Audit verifies compliance.
- Evidence creates assurance.
- SIEM correlates.
- Baselines define normal.
- Verification = built correctly.
- Validation = built the correct thing.
- Fuzzing attacks the application.
- Mutation testing attacks the test suite.
