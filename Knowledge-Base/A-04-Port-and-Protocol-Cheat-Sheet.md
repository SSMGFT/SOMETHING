
# Appendix A-04 - Port and Protocol Cheat Sheet

> Version: 1.7

# Purpose

Memorize **service → purpose → security implication**, not just port numbers.

| Port | Service | Primary Purpose | CISSP Security Insight |
|-----:|---------|-----------------|------------------------|
| 20/21 | FTP | File Transfer | Unencrypted; prefer SFTP/FTPS |
| 22 | SSH | Secure Remote Administration | Encrypted management |
| 23 | Telnet | Remote Administration | Insecure; avoid |
| 25 | SMTP | Email Transfer | Secure with TLS where possible |
| 53 | DNS | Name Resolution | Critical infrastructure; watch for poisoning/transfers |
| 67/68 | DHCP | Dynamic IP Assignment | Rogue DHCP risk |
| 69 | TFTP | Simple File Transfer | No authentication or encryption |
| 80 | HTTP | Web Traffic | Unencrypted |
| 88 | Kerberos | Network Authentication | Enterprise authentication |
| 110 | POP3 | Email Retrieval | Use secure variants |
| 123 | NTP | Time Synchronization | Essential for accurate logs |
| 137-139 | NetBIOS | Windows Networking | Legacy Windows services |
| 143 | IMAP | Email Retrieval | Secure with TLS |
| 161/162 | SNMP | Network Management | Default communities are risky |
| 389 | LDAP | Directory Services | Secure with LDAPS |
| 443 | HTTPS | Secure Web | Encrypted HTTP |
| 445 | SMB | Windows File Sharing | Frequent attack target |
| 514 | Syslog | Centralized Logging | Key log source |
| 636 | LDAPS | Secure LDAP | Encrypted directory access |
| 1433 | Microsoft SQL Server | Database Service | Valuable target for assessment |
| 3389 | RDP | Remote Desktop | Restrict and monitor access |

---

# High-Yield Associations

| If you see... | Think... |
|---------------|----------|
| 445 | SMB / Windows file sharing |
| 1433 | Microsoft SQL Server |
| 389 | LDAP |
| 636 | LDAPS |
| 514 | Syslog |
| 161 | SNMP |
| 3389 | Remote Desktop |

---

# Memory Clusters

## Remote Administration
- 22 SSH
- 23 Telnet
- 3389 RDP

## Web
- 80 HTTP
- 443 HTTPS

## Email
- 25 SMTP
- 110 POP3
- 143 IMAP

## Windows
- 137–139 NetBIOS
- 445 SMB

## Directory Services
- 389 LDAP
- 636 LDAPS

## Management & Logging
- 161 SNMP
- 514 Syslog
- 123 NTP

---

# Exam Tip

Do not memorize ports in isolation.

Think:

**Port → Service → Business Function → Security Risk**

Example:

445 → SMB → Windows File Sharing → Credential attacks / Lateral movement

1433 → SQL Server → Database → Sensitive data exposure
