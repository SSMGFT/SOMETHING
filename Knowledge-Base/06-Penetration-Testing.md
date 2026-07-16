
# 06 - Penetration Testing

> Version: 0.8

# Learning Objectives

After this module you should be able to:

- Explain the purpose of penetration testing.
- Differentiate penetration testing from vulnerability assessment.
- Understand the penetration testing lifecycle.
- Compare black-box, white-box and gray-box testing.
- Apply ISC² manager thinking to penetration testing scenarios.

---

# 1. Purpose

A penetration test answers one question:

> **Can an identified weakness actually be exploited?**

Unlike a vulnerability assessment, the objective is to **validate risk**, not merely identify it.

```text
Weakness
   │
   ▼
Attempt Exploitation
   │
   ▼
Success?
   │
 ┌─┴────────────┐
 │              │
 ▼              ▼
Validated   Not Exploitable
Risk         (Current State)
```

---

# 2. Vulnerability Assessment vs Penetration Test

| Vulnerability Assessment | Penetration Test |
|--------------------------|------------------|
| Identifies weaknesses | Attempts controlled exploitation |
| Broad coverage | Focused validation |
| Usually automated | Mix of manual and automated |
| Lower operational risk | Higher operational risk |
| Produces findings | Produces proof and impact |

---

# 3. Penetration Testing Lifecycle

```text
Planning
   │
   ▼
Rules of Engagement
   │
   ▼
Reconnaissance
   │
   ▼
Enumeration
   │
   ▼
Exploitation
   │
   ▼
Post-Exploitation
   │
   ▼
Cleanup
   │
   ▼
Reporting
```

## Planning

- Define objectives
- Obtain authorization
- Identify scope
- Identify success criteria

## Rules of Engagement (RoE)

Defines:

- Scope
- Time window
- Approved techniques
- Communication plan
- Safety constraints

**No penetration test should begin without authorization and agreed RoE.**

---

# 4. Reconnaissance

Collect information before attacking.

Examples:

- DNS
- WHOIS
- Public websites
- Employee information
- Network ranges

Good reconnaissance reduces unnecessary testing.

---

# 5. Exploitation

Purpose:

Determine whether discovered vulnerabilities can actually be exploited.

The objective is **proof**, not destruction.

---

# 6. Post-Exploitation

Activities may include:

- Demonstrating access
- Showing business impact
- Collecting evidence
- Avoiding unnecessary damage

Persistence is demonstrated only if permitted by the RoE.

---

# 7. Cleanup

A professional penetration test ends by:

- Removing test accounts
- Removing uploaded tools
- Restoring configurations
- Confirming no residual impact

---

# 8. Reporting

A quality report should include:

- Executive summary
- Technical findings
- Business impact
- Evidence
- Risk rating
- Remediation recommendations

The report is often the most valuable deliverable.

---

# 9. Testing Approaches

| Type | Tester Knowledge | Typical Use |
|------|------------------|-------------|
| Black-box | None | External attacker simulation |
| Gray-box | Partial | Insider/partner simulation |
| White-box | Full | Thorough security evaluation |

---

# 10. Internal vs External

| Internal | External |
|----------|----------|
| Simulates insider | Simulates Internet attacker |
| Starts inside network | Starts outside perimeter |

---

# 11. CISSP Exam Traps

| Question Mentions | Think |
|-------------------|-------|
| Prove exploitability | Penetration test |
| Obtain permission | Rules of Engagement |
| Demonstrate business impact | Reporting |
| Find weaknesses only | Vulnerability assessment |
| Restore environment | Cleanup |

---

# 12. Related Chapter 6 Topics

- Rules of Engagement
- Black/Gray/White-box testing
- Reconnaissance
- Exploitation
- Reporting
- Penetration testing process

---

# 30-Second Revision

- Penetration testing validates risk.
- Always obtain authorization.
- Rules of Engagement govern the test.
- Exploitation should be controlled.
- Cleanup is mandatory.
- Reporting converts technical findings into business decisions.

---

Next: **07-Application-Security-Testing.md**
