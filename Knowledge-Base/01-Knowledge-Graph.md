
# 01 - Knowledge Graph

> Version: 0.3

# Purpose

This document is the master map of Domain 6. Every module expands one or more
branches of this graph.

---

# Domain 6 in One View

```text
Security Assessment & Testing
│
├── Foundations
│   ├── Assurance
│   ├── Assessment
│   ├── Verification
│   ├── Validation
│   ├── Evidence
│   └── Trust
│
├── Assessment Activities
│   ├── Review
│   ├── Audit
│   ├── Inspection
│   ├── Testing
│   └── Reporting
│
├── Technical Assessment
│   ├── Discovery
│   ├── Enumeration
│   ├── Port Scanning
│   ├── Banner Grabbing
│   ├── Fingerprinting
│   └── Vulnerability Assessment
│
├── Penetration Testing
│   ├── Planning
│   ├── Rules of Engagement
│   ├── Reconnaissance
│   ├── Exploitation
│   ├── Cleanup
│   └── Report
│
├── Software Testing
│   ├── Static
│   ├── Dynamic
│   ├── Unit
│   ├── Integration
│   ├── Regression
│   ├── Acceptance
│   ├── Fuzzing
│   └── Mutation Testing
│
└── Operations
    ├── Logging
    ├── SIEM
    ├── Continuous Monitoring
    ├── Metrics
    ├── Compliance
    └── SOC Reports
```

---

# Dependency Graph

```text
Business Objectives
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

```text
Discovery
    │
    ▼
Enumeration
    │
    ▼
Vulnerability Assessment
    │
    ▼
Penetration Testing
    │
    ▼
Monitoring
    │
    ▼
Audit
```

---

# Concept Categories

| Category | Examples |
|----------|----------|
| Principle | Assurance, Trust |
| Activity | Assessment, Audit |
| Technique | Fuzzing, Enumeration |
| Test | Unit, Regression, Penetration |
| Technology | SIEM, Vulnerability Scanner |
| Output | Evidence, Reports, Metrics |

---

# Reading Rule

Before studying any topic, identify:

1. Parent concept
2. Child concepts
3. Inputs
4. Outputs
5. Common exam confusion

This creates a connected understanding instead of isolated facts.

---

# Module Mapping

| Graph Branch | Module |
|--------------|--------|
| Foundations | 02 |
| Assessment Activities | 03 |
| Technical Assessment | 04-06 |
| Software Testing | 07 |
| Operations | 08-10 |

---

Next: **02-Foundations.md**
