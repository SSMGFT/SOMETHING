
# 04 - Scanning and Enumeration

> Version: 0.6

# Learning Objectives

After this module you should be able to:

- Explain the difference between discovery, scanning and enumeration.
- Understand the information gained at each stage.
- Recognize common CISSP scenarios involving ports and services.

---

# The Information Gathering Pipeline

```text
Unknown Network
      │
      ▼
Host Discovery
      │
      ▼
Port Scanning
      │
      ▼
Service Identification
      │
      ▼
Banner Grabbing
      │
      ▼
Fingerprinting
      │
      ▼
Enumeration
      │
      ▼
Vulnerability Assessment
```

Each stage answers a different question.

| Stage | Question Answered |
|-------|--------------------|
| Host Discovery | What systems are alive? |
| Port Scanning | Which ports are open? |
| Service Identification | Which services are running? |
| Banner Grabbing | Which versions are exposed? |
| Fingerprinting | What OS/device is this? |
| Enumeration | What additional information can be collected? |

---

# Host Discovery

Purpose: Find reachable hosts.

Typical techniques:

- ICMP Echo
- ARP discovery (local network)
- TCP SYN/Ping techniques

Output:

A list of active systems.

---

# Port Scanning

Purpose:

Determine which network ports are open, closed or filtered.

Remember:

> **Open ports represent potential attack surface.**

---

# Service Identification

Open ports become meaningful only after mapping them to services.

Examples:

| Port | Service | CISSP Insight |
|------|----------|---------------|
| 22 | SSH | Secure remote administration |
| 80 | HTTP | Unencrypted web |
| 443 | HTTPS | Encrypted web |
| 445 | SMB | Windows file sharing |
| 1433 | Microsoft SQL Server | Database service |

Do not memorize numbers alone.

Think:

**Port → Service → Business Function → Security Risk**

---

# Banner Grabbing

Goal:

Collect service information such as:

- Software name
- Version
- Vendor

Older versions often indicate possible vulnerabilities.

---

# Fingerprinting

Purpose:

Identify characteristics of a target.

Examples:

- Operating system
- Device type
- Network stack
- Server software

Fingerprinting helps select the correct assessment approach.

---

# Enumeration

Enumeration goes beyond discovery.

Instead of asking:

> "What exists?"

It asks:

> "What information can I extract?"

Examples:

- User accounts
- Shared folders
- DNS information
- Directory services
- SNMP details

Enumeration provides valuable information for later assessment.

---

# Relationship Diagram

```text
Discovery
    │
    ▼
Scanning
    │
    ▼
Identification
    │
    ▼
Enumeration
    │
    ▼
Assessment
```

---

# CISSP Exam Traps

| If you read... | Think... |
|---------------|----------|
| Find live hosts | Discovery |
| Identify open ports | Port scan |
| Identify software version | Banner grabbing |
| Identify operating system | Fingerprinting |
| Gather usernames/shares | Enumeration |

---

# Related Question Topics

This module supports questions involving:

- Windows ports (e.g., SMB, SQL Server)
- Service identification
- Enumeration
- Fingerprinting
- Banner grabbing

---

# 30-Second Revision

- Discovery finds systems.
- Port scanning finds open ports.
- Banner grabbing identifies versions.
- Fingerprinting identifies systems.
- Enumeration extracts detailed information.
- These activities prepare for vulnerability assessment.

---

Next: **05-Vulnerability-Assessment.md**
