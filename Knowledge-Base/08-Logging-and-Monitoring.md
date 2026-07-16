
# 08 - Logging and Monitoring

> Version: 1.0

# Learning Objectives

After this module you should be able to:

- Explain why logging is essential.
- Differentiate logs, events, alerts and incidents.
- Understand SIEM capabilities.
- Explain baselines and continuous monitoring.
- Select the correct CISSP answer for monitoring scenarios.

---

# Monitoring Lifecycle

```text
Activity
   │
   ▼
Log Generation
   │
   ▼
Collection
   │
   ▼
Correlation
   │
   ▼
Alerting
   │
   ▼
Investigation
   │
   ▼
Response
```

---

# Logs vs Events vs Alerts

| Term | Meaning |
|------|---------|
| Log | Raw record of an activity |
| Event | Something noteworthy in the logs |
| Alert | Notification that action may be required |
| Incident | Confirmed adverse security event |

**Mental Model**

```
Many Logs
    ↓
Interesting Event
    ↓
Alert
    ↓
Investigation
    ↓
Incident (if confirmed)
```

---

# Log Sources

Common sources include:

- Firewalls
- IDS/IPS
- Operating systems
- Applications
- Databases
- Authentication systems
- Cloud services
- Network devices

The more complete the coverage, the better the visibility.

---

# SIEM (Security Information and Event Management)

## Primary Functions

| Function | Purpose |
|----------|---------|
| Collection | Gather logs |
| Normalization | Convert to common format |
| Correlation | Link related events |
| Alerting | Notify analysts |
| Reporting | Dashboards and compliance reports |

**Key CISSP Idea:** A SIEM adds value through **correlation**, not simply by storing logs.

---

# Baselines

A baseline represents **normal behavior**.

Examples:

- Typical login hours
- Average network traffic
- Normal CPU utilization
- Regular authentication patterns

Security monitoring compares current activity against the baseline.

---

# Continuous Monitoring

Continuous monitoring provides ongoing visibility into the security posture.

Goals:

- Detect change quickly
- Verify controls remain effective
- Support continuous improvement

---

# Common CISSP Traps

| If the question says... | Think... |
|-------------------------|----------|
| Raw record | Log |
| Link multiple events | Correlation |
| Centralized analysis | SIEM |
| Normal behavior | Baseline |
| Ongoing visibility | Continuous Monitoring |

---

# Related Chapter 6 Topics

- SIEM
- Log analysis
- Correlation
- Baselines
- Continuous monitoring
- Security reporting

---

# 30-Second Revision

- Logs record activity.
- Events are noteworthy log entries.
- Alerts require attention.
- SIEM correlates data from multiple sources.
- Baselines define normal.
- Continuous monitoring provides ongoing assurance.

---

Next: **09-Audit-and-Compliance.md**
