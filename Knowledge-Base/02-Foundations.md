
# 02 - Foundations

> Version: 0.4

# Learning Objectives

After this module you should be able to:

- Explain why Domain 6 exists.
- Differentiate **assurance**, **assessment**, **audit**, **review**, **inspection**, **verification**, and **validation**.
- Understand how evidence creates management confidence.

---

# 1. Why Domain 6 Exists

Security controls are implemented to reduce risk.

The problem is simple:

> **How do we know the controls actually work?**

Domain 6 answers that question.

```text
Risk
  │
  ▼
Security Controls
  │
  ▼
Assessment
  │
  ▼
Evidence
  │
  ▼
Assurance
  │
  ▼
Management Confidence
```

---

# 2. Security Assurance (D6-001)

## Definition

Security assurance is the **confidence**, based on objective evidence, that security controls operate as intended.

## Key Idea

A firewall may be installed.

Assurance asks:

> "Can we prove it is protecting the organization?"

## Memory Hook

**Assurance = Confidence backed by Evidence**

---

# 3. Security Assessment (D6-002)

## Definition

A structured process used to determine whether security controls are correctly designed, implemented and operating effectively.

Assessment measures.

It does **not** necessarily exploit weaknesses.

---

# 4. Verification vs Validation

| Verification | Validation |
|--------------|------------|
| Built correctly? | Built the correct thing? |
| Checks implementation | Checks business need |
| "Did we follow the specification?" | "Does it solve the user's problem?" |

### Memory

**Verification → Specification**

**Validation → User Expectation**

---

# 5. Assessment Vocabulary

| Activity | Primary Purpose |
|----------|------------------|
| Assessment | Measure security posture |
| Review | Examine documentation or process |
| Inspection | Examine configuration or implementation |
| Audit | Verify compliance against criteria |
| Testing | Demonstrate expected behavior |

Remember:

> **Every audit is an assessment. Not every assessment is an audit.**

---

# 6. Evidence

Evidence is objective information collected during assessment.

Examples:

- Log entries
- Scan reports
- Configuration snapshots
- Audit records
- Test results

Without evidence there is no assurance.

```text
Assessment
     │
     ▼
Evidence
     │
     ▼
Assurance
```

---

# 7. Mental Model

```text
Implement Controls
        │
        ▼
Assess Controls
        │
        ▼
Collect Evidence
        │
        ▼
Gain Assurance
        │
        ▼
Improve Security
```

This lifecycle appears repeatedly throughout Domain 6.

---

# 8. CISSP Exam Traps

| If you see... | Think... |
|---------------|----------|
| Confidence | Assurance |
| Compliance | Audit |
| Weakness identification | Assessment |
| Exploit to prove risk | Penetration Test |
| Objective proof | Evidence |

---

# 9. Related Question Topics

This module prepares you for questions involving:

- Penetration testing vs. vulnerability assessment
- Audit terminology
- Software testing terminology
- Evidence collection
- Compliance

---

# 30-Second Revision

- Assurance = confidence.
- Assessment = measure.
- Audit = compliance.
- Evidence enables assurance.
- Verification = built correctly.
- Validation = built the correct thing.

---

Next: **03-Assessment.md**
