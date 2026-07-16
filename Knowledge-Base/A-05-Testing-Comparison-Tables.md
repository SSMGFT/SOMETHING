
# Appendix A-05 - Testing Comparison Tables

> Version: 1.8

# Purpose

Quickly distinguish commonly confused CISSP Domain 6 concepts.

---

# Assessment vs Audit vs Penetration Test

| Feature | Assessment | Audit | Penetration Test |
|---|---|---|---|
| Primary Goal | Find weaknesses | Verify compliance | Prove exploitability |
| Focus | Security posture | Requirements | Real-world attack |
| Output | Findings | Compliance report | Exploitation report |

---

# Vulnerability Assessment vs Penetration Test

| Vulnerability Assessment | Penetration Test |
|---|---|
| Identifies vulnerabilities | Exploits vulnerabilities |
| Broad coverage | Focused validation |
| Lower risk | Higher operational risk |

---

# Verification vs Validation

| Verification | Validation |
|---|---|
| Built correctly? | Built the correct solution? |
| Specification focused | Business/user focused |

---

# Static vs Dynamic Testing

| Static | Dynamic |
|---|---|
| No execution | Executes application |
| Source/design review | Runtime behavior |

---

# Unit vs Integration vs System vs Acceptance

| Test | Scope | Typical Performer |
|---|---|---|
| Unit | Single component | Developer |
| Integration | Multiple components | Development/Test |
| System | Entire application | Test team |
| Acceptance | Business requirements | User/Business |

---

# Fuzzing vs Mutation Testing

| Fuzzing | Mutation Testing |
|---|---|
| Random inputs | Artificial code defects |
| Tests application robustness | Tests test-suite quality |

---

# Credentialed vs Non-Credentialed Scan

| Credentialed | Non-Credentialed |
|---|---|
| Authenticated | External perspective |
| Better visibility | Attacker simulation |

---

# Internal vs External Pen Test

| Internal | External |
|---|---|
| Insider simulation | Internet attacker simulation |
| Starts inside network | Starts outside perimeter |

---

# Logs vs Events vs Alerts vs Incidents

| Term | Meaning |
|---|---|
| Log | Raw record |
| Event | Noteworthy occurrence |
| Alert | Notification |
| Incident | Confirmed security issue |

---

# KPI vs KRI

| KPI | KRI |
|---|---|
| Performance | Risk |
| Operational success | Risk exposure |

---

# Rapid Recall

- Assessment → Find
- Audit → Verify
- Pen Test → Prove
- Static → Not running
- Dynamic → Running
- Fuzz → Random inputs
- Mutation → Test the tests
- KPI → Performance
- KRI → Risk
