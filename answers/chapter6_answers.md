# CISSP Practice Tests - Chapter 6: Security Assessment and Testing (Domain 6) Answer Key

## Question 1
**Correct Answer:** B

**Explanation:**
TCP and UDP ports 137–139 are used for NetBIOS services, whereas 445 is used for Active Directory. TCP 1433 is the default port for Microsoft SQL, indicating that this is probably a Windows server providing SQL services.

---

## Question 2
**Correct Answer:** D

**Explanation:**
Mutation testing modifies a program in small ways and then tests that mutant to determine if it behaves as it should or if it fails. This technique is used to design and test software tests through mutation. Static code analysis and regression testing are both means of testing code, whereas code auditing is an analysis of source code rather than a means of designing and testing software tests.

---

## Question 3
**Correct Answer:** B

**Explanation:**
TCP port 443 normally indicates an HTTPS server. Nikto is useful for vulnerability scanning web servers and applications and is the best choice listed for a web server. Metasploit includes some scanning functionality but is not a purpose-built tool for vulnerability scanning. zzuf is a fuzzing tool and isn't relevant for vulnerability scans, whereas sqlmap is a SQL injection testing tool.

---

## Question 4
**Correct Answer:** A

**Explanation:**
Syslog is a widely used protocol for event and message logging. Eventlog, netlog, and Remote Log Protocol are all made-up terms.

---

## Question 5
**Correct Answer:** C

**Explanation:**
Fuzzers are tools designed to provide invalid or unexpected input to applications, testing for vulnerabilities like format string vulnerabilities, buffer overflow issues, and other problems. A static analysis relies on examining code without running the application or code and thus would not fill forms as part

of a web application. Brute-force tools attempt to bypass security by trying every possible combination for passwords or other values. A black box is a type of penetration test where the testers do not know anything about the environment.

---

## Question 6
**Correct Answer:** B

**Explanation:**
OpenVAS is an open-source vulnerability scanning tool that will provide Susan with a report of the vulnerabilities that it can identify from a remote, network-based scan. Nmap is an open-source port scanner. Both the Microsoft Baseline Security Analyzer (MBSA) and Nessus are closed-source tools, although Nessus was originally open source.

---

## Question 7
**Correct Answer:** B

**Explanation:**
CVSS, the Common Vulnerability Scoring System, is used to describe the severity of security vulnerabilities. CCE is Common Configuration Enumeration, a naming system for configuration issues. CPE is Common Platform Enumeration, which names operating systems, applications, and devices. OVAL is a language for describing security testing procedures.

---

## Question 8
**Correct Answer:** C

**Explanation:**
Jim has agreed to a black-box penetration test, which provides no information about the organization, its systems, or its defenses. A crystal- or white-box penetration test provides all of the information an attacker needs, whereas a gray-box penetration test provides some, but not all, information.

---

## Question 9
**Correct Answer:** A

**Explanation:**
The key to answering this question correctly is understanding the difference between SOC 1 and SOC 2 reports, and Type I and Type II audits. SOC 1 reports cover financial reporting, and SOC 2 reports look at security. Type I audits cover only a single point in time and are based on management descriptions of controls. They do not include an assessment of operating effectiveness. Type II audits cover a period of time and include an assessment of operating effectiveness.

---

## Question 10
**Correct Answer:** B

**Explanation:**
WPA3 uses SAE, or simultaneous authentication of equals, and does not send the password over the air. Traditional cracking methods used against previous versions of WPA and WPA2 no longer work. This is not because of complex passwords or MFA, but because of how the handshake's elements are created to avoid sending the password.

---

## Question 11
**Correct Answer:** D

**Explanation:**
In many cases when an exploit is initially reported, there are no prebuilt signatures or detections for vulnerability scanners, and the CVE database may not immediately have information about the attack. Jacob's best option is to quickly gather information and review potentially vulnerable servers based on their current configuration. As more information becomes available, signatures and CVE information are likely to be published. Unfortunately for Jacob, IDS and IPS signatures will detect only attacks and won't detect whether systems are vulnerable unless he sees the systems being exploited.

---

## Question 12
**Correct Answer:** C

**Explanation:**
Interface testing is used to ensure that software modules properly meet interface specifications and thus will properly exchange data. Dynamic testing tests software in a running environment, whereas fuzzing is a type of dynamic testing that feeds invalid input to running software to test error and input handling. API checksums are not a testing technique.

---

## Question 13
**Correct Answer:** B

**Explanation:**
Using a third-party auditor from a well-known and well-regarded firm is often the best option when providing audit and compliance information to third parties. Selah could engage an appropriate vendor for a SOC 2 Type II engagement as one example of a reasonable option to provide detail to her customers. Internal staff assessing against a common standard like COBIT would be the next most acceptable option on

this list, with an internal standard less useful than that. Finally, relying on internal personnel not specialized in audits proves to be the least effective strategy in this context.

---

## Question 14
**Correct Answer:** C

**Explanation:**
Breach and attack simulation (BAS) systems combine red team (attack) and blue team (defense) techniques together with automation to simulate advanced persistent threats and other advanced threat actors when run against your environment. This allows a variety of threats to be replicated and assessed in an environment without as much overhead as a fully staffed purple team would.

---

## Question 15
**Correct Answer:** D

**Explanation:**
Most organizations use surveys to assess security awareness. Phishing simulators are also frequently used, but only test awareness of phishing issues and techniques, not general security awareness. Gamified applications are continuing to grow in popularity, but the ease of use and availability of surveys make them the most popular. Finally, assessment tests may be used when compliance knowledge assessments are required to meet a specific standard, but testing is not as common as surveying.

---

## Question 16
**Correct Answer:** D

**Explanation:**
The IP addresses that his clients have provided are RFC 1918 nonroutable IP addresses, and Jim will not be able to scan them from off-site. To succeed in his penetration test, he will have to either first penetrate their network border or place a machine inside their network to scan from the inside. IP addresses overlapping is not a real concern for scanning, and the ranges can easily be handled by current scanning systems.

---

## Question 17
**Correct Answer:** B

**Explanation:**
Ethical (or responsible) disclosure practices will provide companies and organizations with a reasonable period of time to fix a flaw and to get that fix into the

hands of their customers. Two weeks is unlikely to be a reasonable amount of time for this. Unfortunately, Mark may not be able to persuade the individual to make a different decision, and Mark's company will need to determine what to do about the issue.

---

## Question 18
**Correct Answer:** B

**Explanation:**
Group Policy enforced by Active Directory can ensure consistent logging settings and can provide regular enforcement of policy on systems. Periodic configuration audits won't catch changes made between audits, and local policies can drift due to local changes or differences in deployments. A Windows syslog client will enable the Windows systems to send syslog to the SIEM appliance but won't ensure consistent logging of events.

---

## Question 19
**Correct Answer:** B

**Explanation:**
Windows systems generate logs in the Windows native logging format. To send syslog events, Windows systems require a helper application or tool. Enterprise wireless access points, firewalls, and Linux systems all typically support syslog.

---

## Question 20
**Correct Answer:** B

**Explanation:**
Network Time Protocol (NTP) can ensure that systems are using the same time, allowing time sequencing for logs throughout a centralized logging infrastructure. Syslog is a way for systems to send logs to a logging server and won't address time sequencing. Neither logsync nor SNAP is an industry term.

---

## Question 21
**Correct Answer:** A

**Explanation:**
When a tester does not have raw packet creation privileges, such as when they have not escalated privileges on a compromised host, a TCP connect scan can be used. TCP SYN scans require elevated privileges on most Linux systems due to the need to write raw packets. A UDP scan will miss most services that are provided via TCP, and an ICMP is merely a ping sweep of systems that respond to pings and won't identify services at all.

---

## Question 22
**Correct Answer:** B

**Explanation:**
Joseph may be surprised to discover FTP (TCP port 21) and Telnet (TCP port 23) open on his network since both services are unencrypted and have been largely replaced by SSH, and SCP or SFTP. SSH uses port 22, SMTP uses port 25, and POP3 uses port 110.

---

## Question 23
**Correct Answer:** D

**Explanation:**
Large organizations hire QSAs, or qualified security assessors, to conduct compliance checks. Third-party certification is required for large organizations by PCI- DSS, although smaller organizations can self-certify.

---

## Question 24
**Correct Answer:** A

**Explanation:**
A test coverage analysis is often used to provide insight into how well testing covered the set of use cases that an application is being tested for. Source code reviews look at the code of a program for bugs, not necessarily at a use case analysis, whereas fuzzing tests invalid inputs. A code review report might be generated as part of a source code review.

---

## Question 25
**Correct Answer:** C

**Explanation:**
Testing how a system could be misused, or misuse testing, focuses on behaviors that are not what the organization desires or that are counter to the proper function of a system or application. Use case testing is used to verify whether a desired functionality works. Dynamic testing is used to determine how code handles variables that change over time, whereas manual testing is just what it implies: testing code by hand.

---

## Question 26
**Correct Answer:** B

**Explanation:**
Synthetic transaction monitoring uses emulated or recorded transactions to monitor for performance changes in response time, functionality, or other performance monitors. Passive monitoring uses a span port or other method to copy traffic and monitor it in real time. Log analysis is typically performed against actual log data but can be performed on simulated traffic to identify issues. Simulated transaction analysis is not an industry term.

---

## Question 27
**Correct Answer:** B

**Explanation:**
Identity and access management (IAM) systems combine life-cycle management and monitoring tools to ensure that identity and authorization are properly handled throughout an organization. Derek should invest in a capable IAM system and ensure that it is configured to use appropriate workflows and to generate the logs and reports that he needs. EDR systems are endpoint detection and response tools and are used to protect against compromise by advanced attackers.

---

## Question 28
**Correct Answer:** C

**Explanation:**
Vulnerability scanners that do not have administrative rights to access a machine or that are not using an agent to scan remote machines to gather information, including fingerprints from responses to queries and connections, banner information from services, and related data. CVE information is Common Vulnerability and Exposure information, or vulnerability information. A port scanner gathers information about what service ports are open, although some port scanners blur the line between port and vulnerability scanners. Patch management tools typically run as an agent on a system to allow them to both monitor patch levels and update the system as needed. Service validation typically involves testing the functionality of a service, not its banner and response patterns.

---

## Question 29
**Correct Answer:** B

**Explanation:**
Emily is using synthetic transactions, which can use recorded or generated transactions, and is conducting use-case testing to verify that the application responds properly to actual use cases. Neither actual data nor dynamic monitoring is an industry term. Fuzzing involves sending unexpected inputs to a program to see how it responds. Passive monitoring uses a network tap or other capture technology to allow monitoring of actual traffic to a system or application.

---

## Question 30
**Correct Answer:** B

**Explanation:**
Real user monitoring (RUM) is a passive monitoring technique that records user interaction with an application or system to ensure performance and proper application behavior. RUM is often used as part of a predeployment process using the actual user interface. The other answers are all made up—synthetic monitoring uses simulated behavior, but synthetic user monitoring is not a testing method. Similarly, passive monitoring monitors actual traffic, but passive user recording is not an industry term or technique. Client- server testing merely describes one possible architecture.

---

## Question 31
**Correct Answer:** B

**Explanation:**
Jim should ask the information security team to flag the issue as resolved if he is sure the patch was installed. Many vulnerability scanners rely on version information or banner information and may flag patched versions if the software provider does not update the information they see. Uninstalling and reinstalling the patch will not change this. Changing the version information may not change all of the details that are being flagged by the scanner and may cause issues at a later date. Reviewing the vulnerability information for a workaround may be a good idea but should not be necessary if the proper patch is installed; it can create maintenance issues later.

---

## Question 32
**Correct Answer:** B

**Explanation:**
zzuf is the only fuzzer on the list, and zzuf is specifically designed to work with tools like web browsers, image viewers, and similar software by modifying network and file input to applications. Nmap is a port scanner, Nessus is a vulnerability scanner, and Nikto is a web server scanner.

---

## Question 33
**Correct Answer:** D

**Explanation:**
Most IaaS vendors will not allow customers to conduct an audit of their systems and infrastructure. Kara is likely to be able to obtain third-party audit

reports from her vendor, and the major IaaS vendors typically either make these available publicly or to paying or prospective customers. An internal audit will not assess the underlying infrastructure and services, only those that the organization uses.

---

## Question 34
**Correct Answer:** A

**Explanation:**
Passive scanning can help identify rogue devices by capturing MAC address vendor IDs that do not match deployed devices, by verifying that systems match inventories of organizationally owned hardware by hardware address and by monitoring for rogue SSIDs or connections. Scripted attacks are part of active scanning rather than passive scanning, and active scanning is useful for testing IDS or IPS systems, whereas passive scanning will not be detected by detection systems. Finally, a shorter dwell time can actually miss troublesome traffic, so balancing dwell time versus coverage is necessary for passive wireless scanning efforts.

---

## Question 35
**Correct Answer:** B

**Explanation:**
In most organizations, senior management needs to approve penetration tests because of the risk to the organization and the potential impact of the test. In a small number of organizations, the service owner may be able to make this decision, but penetration tests often have broader impacts than a single service, meaning that senior management is the proper path. Change advisory boards approve changes, not penetration tests, and system administrators may be advised of the test but do not have the authority in most organizations to sign off on a penetration test.

---

## Question 36
**Correct Answer:** D

**Explanation:**
Regression testing, which is a type of functional or unit testing, tests to ensure that changes have not introduced new issues. Nonregression testing checks to see whether a change has had the effect it was supposed to, smoke testing focuses on simple problems

with impact on critical functionality, and evolution testing is not a software testing technique.

---

## Question 37
**Correct Answer:** D

**Explanation:**
Nmap, Nessus, and Nikto all have OS fingerprinting or other operating system identification capabilities. Sqlmap is designed to perform automated detection and testing of SQL injection flaws and does not provide OS detection.

---

## Question 38
**Correct Answer:** C

**Explanation:**
Key risk indicators are used to tell those in charge of risk management how risky an activity is and how much impact changes are having on that risk profile. Identifying and monitoring key risk indicators can help track high-risk areas earlier in their life cycle. Yearly risk assessments may be a good idea but provide only a point-in-time view, whereas penetration tests may miss out on risks that are not directly security-related. Monitoring logs and events using a SIEM device can help detect issues as they occur but won't necessarily show trends in risk.

---

## Question 39
**Correct Answer:** C

**Explanation:**
Passive monitoring works only after issues have occurred because it requires actual traffic. Synthetic monitoring uses simulated or recorded traffic and thus can be used to proactively identify problems. Both synthetic and passive monitoring can be used to detect functionality issues.

---

## Question 40
**Correct Answer:** B

**Explanation:**
Getting authorization is the most critical element in the planning phase. Permission, and the “get-out-of-jail- free card” that demonstrates that organizational leadership is aware of the issues that a penetration test could cause, is the first step in any penetration test. Gathering tools and building a lab, as well as determining what type of test will be conducted, are all important, but nothing should happen without permission.

---

## Question 41
**Correct Answer:** C

**Explanation:**
Discovery can include both active and passive discovery. Port scanning is commonly done during discovery to assess what services the target provides, and nmap is one of the most popular tools used for this purpose. Nessus and Nikto might be used during the vulnerability scanning phase, and john, a password cracker, can be used to recover passwords during the exploitation phase.

---

## Question 42
**Correct Answer:** B

**Explanation:**
Penetration test reports often include information that could result in additional exposure if they were accidentally released or stolen. Therefore, determining how vulnerability data should be stored and sent is critical. Problems with off-limits targets are more likely to result in issues during the vulnerability assessment and exploitation phase, and reports should not be limited in length but should be as long as they need to be to accomplish the goals of the test.

---

## Question 43
**Correct Answer:** B

**Explanation:**
Code coverage testing most frequently requires that every function has been called, that each statement has been executed, that all branches have been fully explored, and that each condition has been evaluated for all possibilities. API, input, and loop testing are not common types of code coverage testing measures.

---

## Question 44
**Correct Answer:** B

**Explanation:**
Time to remediate a vulnerability is a commonly used key performance indicator for security teams. Time to live measures how long a packet can exist in hops, business criticality is a measure used to determine how important a service or system is to an organization, and coverage rates are used to measure how effective code testing is.

---

## Question 45
**Correct Answer:** D

**Explanation:**
Unique user IDs provide accountability when paired with auditable logs to provide that a specific user took any given action. Confidentiality, availability, and

integrity can be provided through other means like encryption, systems design, and digital signatures.

---

## Question 46
**Correct Answer:** B

**Explanation:**
Application programming interfaces (APIs), user interfaces (UIs), and physical interfaces are all important to test when performing software testing. Network interfaces are not part of the typical list of interfaces tested in software testing.

---

## Question 47
**Correct Answer:** C

**Explanation:**
The Common Vulnerabilities and Exposures (CVE) database provides a consistent reference for identifying security vulnerabilities. The Open Vulnerability and Assessment Language (OVAL) is used to describe the security condition of a system. The Extensible Configuration Checklist Description Format (XCCDF) is used to create security checklists in a standardized fashion. The Script Check Engine (SCE) is designed to make scripts interoperable with security policy definitions.

---

## Question 48
**Correct Answer:** B, C

**Explanation:**
Test 2's total failure is likely due to a failed test run, but the tests overall show continued improvement with full success in test 4. At this point, most testing processes would consider the testing complete. This does not show coverage, and there is no reason to run a fifth run if the fourth test was successful.

---

## Question 49
**Correct Answer:** C

**Explanation:**
Simply updating the version that an application provides may stop the vulnerability scanner from flagging it, but it won't fix the underlying issue. Patching, using workarounds, or installing an application layer firewall or IPS can all help to remediate or limit the impact of the vulnerability.

---

## Question 50
**Correct Answer:** C

**Explanation:**
Selah's social engineering attack succeeded in persuading a staff member at the help desk to change a password for someone who they not only couldn't see but who they couldn't verify actually needed their

password reset. Black box and zero knowledge are both terms describing penetration tests without information about the organization or system, and help-desk spoofing is not an industry term.

---

## Question 51
**Correct Answer:** D

**Explanation:**
The menu shown will archive logs when they reach the maximum size allowed (20 MB). These archives will be retained, which could fill the disk. Log data will not be overwritten, and log data should not be lost when the data is archived. The question does not include enough information to determine if needed information may not be logged.

---

## Question 52
**Correct Answer:** C

**Explanation:**
Penetration tests typically do not involve blackouts. Application crashes, denial of service due to system, network, or application failures, and even data corruption can all be hazards of penetration tests.

---

## Question 53
**Correct Answer:** B

**Explanation:**
NIST SP 800-53A is titled “Assessing Security and Privacy Controls in Federal Information Systems and Organizations: Building Effective Assessment Plans” and covers methods for assessing and measuring controls. NIST 800-12 is an introduction to computer security, 800-34 covers contingency planning, and 800- 86 is the “Guide to Integrating Forensic Techniques into Incident Response.”

---

## Question 54
**Correct Answer:** C

**Explanation:**
Simulations are the most complete test that can be conducted without the risk that a full failover test creates. Michelle should conduct a simulation to validate as much of her organization's plan as possible. Tabletop exercises and plan reviews provide less complete coverage.

---

## Question 55
**Correct Answer:** C

**Explanation:**
Hybrid environment audits involve the complexity of both cloud and on-premises audits. That means that the underlying cloud infrastructure may not be auditable, although Lucca's organization's use and configuration

of the cloud will be. On-premises audits are not any more challenging to complete than other audits, hybrid audits can be conducted by third parties, and hybrid audits include both on-premises and cloud auditing challenges and requirements as they are not the same as a cloud-only audit.

---

## Question 56
**Correct Answer:** A

**Explanation:**
Port 22 is used by the Secure Shell (SSH) protocol for administrative connections. If Kara wants to restrict administrative connections, she should block access on this port. Port 80 is used for HTTP, 443 for HTTPS, and 1433 for Microsoft SQL.

---

## Question 57
**Correct Answer:** C

**Explanation:**
The audit finding indicates that the backup administrator may not be monitoring backup logs and taking appropriate action based on what they report, thus resulting in potentially unusable backups. Issues with review, logging, or being aware of the success or failure of backups are less important than not having usable backups.

---

## Question 58
**Correct Answer:** C

**Explanation:**
ITIL, which originally stood for IT Infrastructure Library, is a set of practices for IT service management and is not typically used for auditing. The Control Objectives for Information and Related Technology (COBIT), ISO 27001, and the Statement on Standards for Attestation Engagements number 18 (SSAE-18) are all used for auditing.

---

## Question 59
**Correct Answer:** B

**Explanation:**
COBIT, the Control Objectives for Information and Related Technologies, is commonly used as an audit framework for evaluating the governance and management of enterprise IT in an organization. The DMCA is the Digital Millennium Copyright Act, IEC is the International Electrotechnical Commission that defines standards for electrotechnology, and FISA is the Federal Intelligence Surveillance Act, not an audit standard.

---

## Question 60
**Correct Answer:** B

**Explanation:**
Kelly's team is using regression testing, which is intended to prevent the recurrence of issues. This means measuring the rate of defect recurrence is appropriate for their work. Time to remediate vulnerabilities is associated with activities such as patching, rather than preparing the patch, whereas a weighted risk trend is used to measure risk over time to an organization. Finally, specific coverage may be useful to determine if they are fully testing their effort, but regression testing is more specifically covered by defect recurrence rates.

---

## Question 61
**Correct Answer:** C

**Explanation:**
Static program reviews are typically performed by an automated tool. Program understanding, program comprehension, pair programming, software inspections, and software walk-throughs are all human- centric methods for reviewing code.

---

## Question 62
**Correct Answer:** A

**Explanation:**
To fully test code, a white-box test is required. Without full visibility of the code, error conditions or other code could be missed, making a gray-box or black-box test an inappropriate solution. Using dynamic testing that runs against live code could also result in some conditions being missed due to sections of code not being exposed to typical usage.

---

## Question 63
**Correct Answer:** A

**Explanation:**
A test coverage report measures how many of the test cases have been completed and is used as a way to provide test metrics when using test cases. A penetration test report is provided when a penetration test is conducted—this is not a penetration test. A code coverage report covers how much of the code has been tested, and a line coverage report is a type of code coverage report, both of which cannot be created in a black-box test since the code is not accessible to testers.

---

## Question 64
**Correct Answer:** C

**Explanation:**
The changes from a testing environment with instrumentation inserted into the code and the production environment for the code can mask timing- related issues like race conditions. Bounds checking, input validation, and pointer manipulation are all related to coding issues rather than environmental issues and are more likely to be discoverable in a test environment.

---

## Question 65
**Correct Answer:** D

**Explanation:**
Once a vulnerability scanner identifies a potential problem, validation is necessary to verify that the issue exists. Reporting, patching, or other remediation actions can be conducted once the vulnerability has been confirmed.

---

## Question 66
**Correct Answer:** B

**Explanation:**
While handling errors and exceptions can be something of an art, the first thing to do in circumstances like these is to review error logs and notifications to try to find out what went wrong. From there, Andrea can make a decision to remediate a problem, send the code back for a fix, or take another action. She might even opt to send the code forward if the error occurred after testing was completed and was with the process flow or another noncritical element, but would do so only if she was absolutely certain that was the case.

---

## Question 67
**Correct Answer:** D

**Explanation:**
The Common Vulnerability Scoring System (CVSS) includes metrics and calculation tools for exploitability, impact, how mature exploit code is, and how vulnerabilities can be remediated, as well as a means to score vulnerabilities against users' unique requirements. NVD is the National Vulnerability Database, CSV is short for comma-separated values, and Visual SourceSafe (VSS) is an irrelevant term related to software development rather than vulnerability management.

---

## Question 68
**Correct Answer:** D

**Explanation:**
Network-enabled printers often provided services via TCP 515 and 9100 and have both nonsecure and secure web-enabled management interfaces on TCP 80 and 443. Web servers, access points, and file servers would not typically provide service on the LPR and LPD ports (515 and 9100).

---

## Question 69
**Correct Answer:** A

**Explanation:**
Nikto, Burp Suite, and Wapiti are all web application vulnerability scanners, tools designed specifically to scan web servers and applications. While they share some functionality with broader vulnerability scanners and port scanning tools, they have a narrower focus and typically have deeper capabilities than vulnerability scanners.

---

## Question 70
**Correct Answer:** A

**Explanation:**
APIs typically transfer data for web applications via HTTPS, meaning that the API itself is not responsible for encryption. If Frank's team discovers that TLS is not enabled, they will need to work with the infrastructure or systems administration team to ensure that TLS is enabled and in use rather than making API changes. Authorization for object access, authentication weaknesses, and rate limiting are all common API issues. If you're not familiar with the types of issues you might encounter in APIs, you can read more about them in the OWASP API security top 10 at https://owasp.org/API-Security/editions/2023/en/0x11-t10.

---

## Question 71
**Correct Answer:** B

**Explanation:**
Metasploit is an exploitation package that is designed to assist penetration testers. A tester using Metasploit can exploit known vulnerabilities for which an exploit has been created or can create their own exploits using the tool. While Metasploit provides built- in access to some vulnerability scanning functionality, a tester using Metasploit should primarily be expected to perform actual tests of exploitable vulnerabilities. Similarly, Metasploit supports creating buffer overflow

attacks, but it is not a purpose-built buffer overflow testing tool, and of course, testing systems for zero-day exploits doesn't work unless they have been released.

---

## Question 72
**Correct Answer:** D

**Explanation:**
Susan is conducting interface testing. Interface testing involves testing system or application components to ensure that they work properly together. Misuse case testing focuses on how an attacker might misuse the application and would not test normal cases. Fuzzing attempts to send unexpected input and might be involved in interface testing, but it won't cover the full set of concerns. Regression testing is conducted when testing changes and is used to ensure that the application or system functions as it did before the update or change.

---

## Question 73
**Correct Answer:** B

**Explanation:**
Not having enough log sources is not a common consideration in log management system design, although it may be a worry for security managers who can't capture the data they need. Log management system designs must take into account the volume of log data and the network bandwidth it consumes, the security of the data, and the amount of effort required to analyze the data.

---

## Question 74
**Correct Answer:** D

**Explanation:**
Random sampling of accounts is the recommended best practice if all accounts cannot be validated. Selecting only recently changed accounts will not identify long-term issues or historic issues, and checking only high-value accounts will not show if there are issues or bad practices with other account types.

---

## Question 75
**Correct Answer:** C

**Explanation:**
Rebooting a Windows machine results in an information log entry. Windows defines five types of events: errors, which indicate a significant problem; warnings, which may indicate future problems; information, which describes successful operation; success audits, which record successful security

accesses; and failure audits, which record failed security access attempts.

---

## Question 76
**Correct Answer:** C

**Explanation:**
Inconsistent timestamps are a common problem, often caused by improperly set time zones or due to differences in how system clocks are set. In this case, a consistent time difference often indicates that one system uses local time, and the other is using Greenwich mean time (GMT). Logs from multiple sources tend to cause problems with centralization and collection, whereas different log formats can create challenges in parsing log data. Finally, modified logs are often a sign of intrusion or malicious intent.

---

## Question 77
**Correct Answer:** A

**Explanation:**
Authenticated scans use a read-only account to access configuration files, allowing more accurate testing of vulnerabilities. Web application scans, unauthenticated scans, and port scans don't have access to configuration files unless they are inadvertently exposed.

---

## Question 78
**Correct Answer:** B

**Explanation:**
Notifying third parties of security issues and vulnerabilities in a confidential manner to allow them to address the issues is considered ethical disclosure. There is not enough information in the question to determine how it was found, and disclosure is not necessarily part of either penetration tests or application tests. How the information as found is not listed, so OSINT is not a useful answer either.

---

## Question 79
**Correct Answer:** D

**Explanation:**
Since a shared symmetric key could be used by any of the servers, transaction identification problems caused by a shared key are likely to involve a repudiation issue. If encrypted transactions cannot be uniquely identified by a server, they cannot be proved to have come from a specific server.

---

## Question 80
**Correct Answer:** C

**Explanation:**
Ben should engage a company that can perform a load or stress test to validate how the application performs under both expected and extreme loads so that he knows what a denial-of-service attack based on load will look like. Social engineering does not test the ability of sites to handle load, and penetration testers may conduct denial-of-service attacks but typically do not. Fuzzers send random input to test how applications handle unexpected input rather than relying on extreme load. They might help test for flaws that could result in a denial-of-service condition, but the question specifically asks about load-based conditions, not software flaws.

---

## Question 81
**Correct Answer:** D

**Explanation:**
The Network Time Protocol (NTP) allows the synchronization of system clocks with a standardized time source. The Secure Shell (SSH) protocol provides encrypted administrative connections to servers. The File Transfer Protocol (FTP) is used for data exchange. Transport Layer Security (TLS) is an encryption process used to protect information in transit over a network.

---

## Question 82
**Correct Answer:** C

**Explanation:**
Fuzz testers are capable of automatically generating input sequences to test an application. Therefore, testers do not need to manually generate input, although they may do so if they want. Fuzzers can reproduce errors (and thus, “fuzzers can't reproduce errors” is not an issue) but typically don't fully cover the code—code coverage tools are usually paired with fuzzers to validate how much coverage was possible. Fuzzers are often limited to simple errors because they won't handle business logic or attacks that require knowledge from the application user.

---

## Question 83
**Correct Answer:** D

**Explanation:**
Statement coverage tests verify that every line of code was executed during the test. Branch coverage

verifies that every if statement was executed under all if and else conditions. Condition coverage verifies that every logical test in the code was executed under all sets of inputs. Function coverage verifies that every function in the code was called and returns results.

---

## Question 84
**Correct Answer:** C

**Explanation:**
After scanning for open ports using a port scanning tool like nmap, penetration testers will identify interesting ports and then conduct vulnerability scans to determine what services may be vulnerable. This will perform many of the same activities that connecting via a web server will and will typically be more useful than trying to manually test for vulnerable accounts via Telnet. Sqlmap would typically be used after a vulnerability scanner identifies additional information about services, and the vulnerability scanner will normally provide a wider range of useful information.

---

## Question 85
**Correct Answer:** B

**Explanation:**
The system is likely a Linux system. The system shows X11, as well as login, shell, and nfs ports, all of which are more commonly found on Linux systems than Windows systems or network devices. This system is also very poorly secured; many of the services running on it should not be exposed in a modern secure network.

---

## Question 86
**Correct Answer:** D

**Explanation:**
Nmap scans only 1000 TCP and UDP ports by default, including ports outside the 0–1024 range of “well-known” ports. By using the defaults for nmap, Ben missed 64,535 ports. OS fingerprinting won't cover more ports but would have provided a best guess of the OS running on the scanned system.

---

## Question 87
**Correct Answer:** A

**Explanation:**
When Lucca reviews the recovery time objective (RTO) data, he needs to ensure that the organization can recover from an outage in less than two hours based on the maximum tolerable downtime (MTD) of two hours.

---

## Question 88
**Correct Answer:** C

**Explanation:**
Diana should request a SOC 3 report, which is intended for distribution to third parties. They include the auditor's opinions and management assertions, along with information about the service organization. SOC 3 reports are specifically intended for external release, unlike SOC 1 (financial reporting) and SOC 2 (confidentiality, security, and privacy) engagements. SOC 4 was made up for the question.

---

## Question 89
**Correct Answer:** A

**Explanation:**
Showing end users error information about the code, particularly with directory and file information included, means that the application does not perform proper exception handling. Errors should be logged or noted in a way that the administrator can handle, but end users (and attackers!) should not see that information. The software may be handling misuse properly, as the problem does not note if this was due to normal testing or misuse testing. There is no information about debugging code causing the output, and test coverage was not noted in the question.

---

## Question 90
**Correct Answer:** B

**Explanation:**
Port scanning is the first step toward identifying potentially exploitable services. Data gathering is used to acquire information to prepare for port scanning and other activities. Permission and planning are not used to identify exploitable services but are critical to the overall process.

---

## Question 91
**Correct Answer:** C

**Explanation:**
Validating that the organization has secure and usable backups is Josh's best answer. In case a system is affected by cryptographic malware, it's important to have reliable backups that are not encrypted by the malware. This requires keeping your backup systems separate from your main systems and potentially implementing version control so that your unencrypted backups are not overwritten by encrypted ones that become inaccessible. Encrypting sensitive data won't

stop attackers from re-encrypting it, making it inaccessible. Hashing to detect the attack won't stop it or make it possible to recover, and anti-encryption technology does not exist.

---

## Question 92
**Correct Answer:** D

**Explanation:**
IT service management, or ITSM, tools include change management and thus the type of approvals and review processes that Joanna is looking for. A SIEM helps with security logs and events, an IPS looks for intrusions and unwanted traffic, and a CMS is a content management tool.

---

## Question 93
**Correct Answer:** D

**Explanation:**
All of these are useful parts of a backup strategy, but performing full restores from backups on a regular basis is the best option listed. If regular restores work, then individual files will be recoverable, but individual files may not show larger issues with backups. Configuration and setting reviews are important but will not validate the backups themselves, and error messages can indicate problems but won't demonstrate intact logs either.

---

## Question 94
**Correct Answer:** C

**Explanation:**
Vulnerability scanners cannot detect vulnerabilities for which they do not have a test, plug-in, or signature. Signatures often include version numbers, service fingerprints, or configuration data. They can detect local vulnerabilities as well as those that require authentication if they are provided with credentials, and of course, they can detect service vulnerabilities.

---

## Question 95
**Correct Answer:** A, B

**Explanation:**
The number of staff who took a given training and the average change in their awareness from before the training to after the training can provide insight into how many trained staff you have and how impactful the training was. Over time, this will allow you to determine if your training is helping and if awareness is increasing. The length of the training does not assess its impact; in addition, the number of events

each individual attended does not mean that staff are becoming more aware.

---

## Question 96
**Correct Answer:** C

**Explanation:**
Ethical (or responsible) disclosure norms include notifying the vendor and providing them with a reasonable amount of time to remediate the issue. Public disclosures before notifying the vendor or in a short period of time are considered unethical in most circumstances. While this time frame varies, 90 to 120 days is not uncommon across the industry due to the complexity of software and other technologies.

---

## Question 97
**Correct Answer:** D

**Explanation:**
Privilege escalation occurs during the attack phase of a penetration test. Host and service information gathering, as well as activities like dumpster diving that can provide information about the organization, its systems, and security, are all part of the discovery phase.

---

## Question 98
**Correct Answer:** B

**Explanation:**
Once additional tools have been installed, penetration testers will typically use them to gain additional access. From there they can further escalate privileges, search for new targets or data, and, once again, install more tools to allow them to pivot further into infrastructure or systems.

---

## Question 99
**Correct Answer:** B

**Explanation:**
Penetration testing reports often do not include the specific data captured during the assessment, as the readers of the report may not be authorized to access all of the data, and exposure of the report could result in additional problems for the organization. A listing of the issues discovered, risk ratings, and remediation guidance are all common parts of a penetration test report.

---

## Question 100
**Correct Answer:** See Explanation

**Explanation:**
The status messages match with the descriptions as follows:

1. Open: C. The port is accessible on the remote system, and an application is accepting connections on that port. 2. Closed: B. The port is not accessible on the remote system. 3. Filtered: A. The port is accessible on the remote system, but no application is accepting connections on that port.

---

