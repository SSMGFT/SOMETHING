
# 07 - Application Security Testing

> Version: 0.9

# Learning Objectives

After this module you should be able to:

- Differentiate major software testing techniques.
- Select the correct testing method for a CISSP scenario.
- Distinguish static from dynamic testing.
- Explain fuzzing and mutation testing.

---

# Testing in the SDLC

```text
Requirements
    │
Design
    │
Development
    │
Static Testing
    │
Build
    │
Unit Testing
    │
Integration Testing
    │
System Testing
    │
Dynamic Testing
    │
Acceptance Testing
    │
Deployment
```

Testing should begin as early as possible.

---

# Static vs Dynamic Testing

| Static Testing | Dynamic Testing |
|---------------|-----------------|
| No execution | Executes the application |
| Reviews code/design | Observes runtime behavior |
| Finds defects early | Finds runtime issues |

**Memory:** Static = *code is still*. Dynamic = *code is running*.

---

# Unit Testing

**Purpose:** Verify a single function, class, or module.

Usually performed by developers.

---

# Integration Testing

**Purpose:** Verify interaction between components.

Looks for interface and communication defects.

---

# System Testing

**Purpose:** Test the complete integrated application.

Focuses on end-to-end functionality.

---

# User Acceptance Testing (UAT)

**Purpose:** Confirm the solution satisfies business requirements.

Performed by users or business representatives.

**Think:** "Does the business accept the product?"

---

# Regression Testing

**Purpose:** Ensure recent changes did not break existing functionality.

Typically repeated after bug fixes or updates.

---

# Code Review

A manual examination of source code to identify:

- Security flaws
- Logic errors
- Coding standard violations
- Maintainability issues

---

# Fuzz Testing (Fuzzing)

Feed unexpected, malformed, or random input to an application.

Goal:

- Trigger crashes
- Reveal input validation weaknesses
- Expose security defects

---

# Mutation Testing

Artificially introduce small defects into source code.

Goal:

Evaluate whether existing test cases detect the introduced defects.

**Exam clue:** Mutation testing measures the **quality of the tests**, not the quality of the application.

---

# Comparison Table

| Technique | Main Goal |
|-----------|-----------|
| Static | Find defects before execution |
| Dynamic | Observe runtime behavior |
| Unit | Verify one component |
| Integration | Verify component interaction |
| System | Verify complete system |
| Acceptance | Verify business needs |
| Regression | Verify nothing broke |
| Fuzzing | Discover unexpected failures |
| Mutation | Evaluate test effectiveness |

---

# CISSP Exam Traps

| If you see... | Think... |
|---------------|----------|
| Review source without execution | Static Testing |
| Execute application | Dynamic Testing |
| Random inputs | Fuzzing |
| Artificial defects | Mutation Testing |
| Verify bug fix didn't break features | Regression |
| Business approval | Acceptance Testing |

---

# Related Chapter 6 Topics

- Static vs Dynamic
- Regression Testing
- Acceptance Testing
- Fuzzing
- Mutation Testing
- Code Review

---

# 30-Second Revision

- Static = no execution.
- Dynamic = executes software.
- Unit tests one component.
- Integration tests component interaction.
- System tests the whole application.
- Acceptance confirms business requirements.
- Regression protects existing functionality.
- Fuzzing finds unexpected failures.
- Mutation evaluates the quality of the test suite.

---

Next: **08-Logging-and-Monitoring.md**
