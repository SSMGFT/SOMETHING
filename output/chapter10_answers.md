# CISSP Practice Tests - Chapter 10: Practice Test 2 Answer Key

## Question 1
**Correct Answer:** D

**Explanation:**
The recovery point objective (RPO) identifies the maximum amount of data, measured in time, that may be lost during a recovery effort. The recovery time objective (RTO) is the amount of time expected to return an IT service or component to operation after a failure. The maximum tolerable downtime (MTD) is the longest amount of time that an IT service or component may be unavailable without causing serious damage to the organization. Service-level agreements (SLAs) are written contracts that document service expectations.

---

## Question 2
**Correct Answer:** C

**Explanation:**
Due care and due diligence can be a confusing pair of terms to keep straight. Chris is engaging in due diligence when he does the preparation and research. Once that is done, he must use due care while undertaking the actions. This is often described in the context of the prudent person rule: would a prudent person have taken the action given the same knowledge? Compliance efforts work to ensure an organization meets regulatory or other requirements. Organizations typically don't take regulatory action— that's left to the government.

---

## Question 3
**Correct Answer:** D

**Explanation:**
Blue teams are defenders, red teams are attackers, and purple teams combine both attack and defense activities. Yellow and green teams are not commonly described as part of penetration testing.

---

## Question 4
**Correct Answer:** C

**Explanation:**
Hardware and software can be subject to import and export controls. In the case of AI computation hardware, there are specific limits on what can be exported to China, including limits on performance. Sharif needs to engage the appropriate experts to determine what can and cannot be exported. AI hardware is legal in China, dollar values are not

typically the limiting factor for hardware import/export restrictions, and ethics are not a regulatory issue.

---

## Question 5
**Correct Answer:** B

**Explanation:**
The most realistic but also most disruptive option for disaster recovery plan testing is a full interruption. The least obtrusive but also least similar to real-world scenarios is a read-through. After that, walk-throughs and simulations are each closer to a true scenario, but parallel operations are often the most popular option because it can be done without disrupting the organization and still reasonably test capabilities.

---

## Question 6
**Correct Answer:** C

**Explanation:**
Cold sites are facilities large enough to use for recovery operations with appropriate power and environmental capabilities but without any additional readiness work done for computing, connectivity, or other needs. Warm sites have equipment and connectivity in place but are not actively handling live data. Hot sites have live data and could take over operations immediately. Frozen site is not a term used to describe a failover or recovery site.

---

## Question 7
**Correct Answer:** B

**Explanation:**
The data owner is normally responsible for classifying information at an appropriate level. This role is typically filled by a senior manager or director, who then delegates operational responsibility to a data custodian. Data creators do just that—create data— although data creators is not a commonly used role name in data role lists. CISOs are chief information security officers and are typically the top-level individual responsible for security in organizations.

---

## Question 8
**Correct Answer:** A

**Explanation:**
Off-site backups are the best option for disaster recovery in a scenario where a disaster directly impacts the data center. None of the other scenarios as described will directly address the issue, although snapshots to a remote storage location can act as a form of off-site backup.

---

## Question 9
**Correct Answer:** C

**Explanation:**
While all of the listed controls would improve authentication security, most simply strengthen the use of knowledge-based authentication. The best way to improve the authentication process would be to add a factor that is not based on knowledge through the use of multifactor authentication. This may include the use of biometric controls or token-based authentication.

---

## Question 10
**Correct Answer:** C

**Explanation:**
Software-defined networking (SDN) is a converged protocol that allows virtualization concepts and practices to be applied to networks. MPLS handles a wide range of protocols like asynchronous transfer mode (ATM), digital subscriber line (DSL), and others, but isn't intended to provide the centralization capabilities that SDN does. A content distribution network (CDN) is not a converged protocol, and FCoE is Fibre Channel over Ethernet, a converged protocol for storage.

---

## Question 11
**Correct Answer:** C

**Explanation:**
The best way to ensure that data on DVDs is fully gone is to destroy them, and pulverizing DVDs is an appropriate means of destruction. DVD-ROMs are write-only media, meaning that secure erase and zero wipes won't work. Degaussing works only on magnetic media and cannot guarantee that there will be zero data remanence.

---

## Question 12
**Correct Answer:** C

**Explanation:**
Backout plans are required in some change management processes to ensure that the thought process and procedures for what to do if something does not go as planned are needed. Validating backout plan quality can be just as important as the change, and you may find, in many organizations, if nobody is watching, that backout plans may read, “Undo the change we made.” Rejecting the change won't fix the problem if the change has been made. A change review is useful to identify problems before the change is

made. Failover plans are not a term commonly used in change management processes.

---

## Question 13
**Correct Answer:** A

**Explanation:**
All packets leaving Angie's network should have a source address from her public IP address block. Packets with a destination address from Angie's network should not be leaving the network. Packets with source addresses from other networks are likely spoofed and should be blocked by egress filters. Packets with private IP addresses as sources or destinations should never be routed onto the Internet.

---

## Question 14
**Correct Answer:** B

**Explanation:**
Virtual private clouds (VPCs) run on cloud-hosted infrastructure providing a secure, isolated pool of resources to be used by organizations to meet their needs. A VLAN is a virtual local area network. While VLANs are part of how most VPCs work, they alone aren't sufficient to create a VPC. An SDN, or software defined network, is used to manage networks through code, and CDNs are content delivery networks used to provide access to content around the globe that helps offload traffic while protecting against denial-of-service (DoS) attacks and other issues.

---

## Question 15
**Correct Answer:** A

**Explanation:**
While developers may feel like they have a business need to be able to move code into production, the principle of separation of duties dictates that they should not have the ability to both write code and place it on a production server. The deployment of code is often performed by change management staff. Two- person control requires two individuals to perform an action to ensure appropriate oversight. Least privilege is the concept of only providing privileges required to perform a role, and job rotation moves individuals through job roles to ensure that different people perform tasks preventing an individual from exploiting their job function over time.

---

## Question 16
**Correct Answer:** A

**Explanation:**
Applying a digital signature to a message allows the sender to achieve the goal of nonrepudiation. This allows the recipient of a message to prove to a third party that the message came from the purported sender. Symmetric encryption does not support nonrepudiation. Firewalls and IDS are network security tools that are not used to provide nonrepudiation.

---

## Question 17
**Correct Answer:** A

**Explanation:**
System A should send an ACK to end the three-way handshake. The TCP three-way handshake is SYN, SYN/ACK, ACK. FIN is used to end a TCP connection, while RST resets the connection.

---

## Question 18
**Correct Answer:** B

**Explanation:**
TACACS+ is the most modern version of TACACS, the Terminal Access Controller Access-Control System. It is a Cisco proprietary protocol with added features beyond what RADIUS provides, meaning it is commonly used on Cisco networks. XTACACS is an earlier version, Kerberos is a network authentication protocol rather than a remote user authentication protocol, and RADIUS+ is a made-up term.

---

## Question 19
**Correct Answer:** C

**Explanation:**
Call managers and VoIP phones can be thought of as servers or appliances and embedded or network devices. That means that the most likely threats that they will face are denial-of-service (DoS) attacks and attacks against the host operating system. Malware and Trojans are less likely to be effective against a server or embedded system that doesn't browse the Internet or exchange data files; buffer overflows are usually aimed at specific applications or services.

---

## Question 20
**Correct Answer:** C

**Explanation:**
The blacklist approach to application control blocks certain prohibited packages but allows the installation of other software on systems. The whitelist approach uses the reverse philosophy and allows only approved software. It is worth noting that the terms blacklist and whitelist are increasingly deprecated and that you may

encounter terms like block list or deny list and allow list as language and terminology shifts. As you prepare for the exam and your professional work, make sure to consider these equivalents. Antivirus software would only detect the installation of malicious software after the fact. Heuristic detection is a variant of antivirus software.

---

## Question 21
**Correct Answer:** B

**Explanation:**
The exposure factor (EF) is the percentage of the facility that risk managers expect will be damaged if a risk materializes. It is calculated by dividing the amount of damage by the asset value. In this case, that is $20 million in damage divided by the $100 million facility value, or 20%.

---

## Question 22
**Correct Answer:** B

**Explanation:**
The annualized rate of occurrence (ARO) is the number of times each year that risk analysts expect a risk to happen in any given year. In this case, the analysts expect floods once every 200 years, or 0.005 times per year.

---

## Question 23
**Correct Answer:** B

**Explanation:**
The annualized loss expectancy (ALE) is calculated by multiplying the single loss expectancy (SLE) by the annualized rate of occurrence (ARO). In this case, the SLE is $20 million, and the ARO is 0.005. Multiplying these numbers together gives you the ALE of $100,000.

---

## Question 24
**Correct Answer:** B

**Explanation:**
The most frequent target of account management reviews are highly privileged accounts, as they create the greatest risk. Random samples are the second most likely choice. Accounts that have existed for a longer period of time are more likely to have a problem due to privilege creep than recently created accounts, but neither of these choices is likely unless there is a specific organizational reason to choose them.

---

## Question 25
**Correct Answer:** D

**Explanation:**
The cloud service offerings in order from the case where the customer bears the least responsibility to

where the customer bears the most responsibility are SaaS, PaaS, and IaaS. In an infrastructure-as-a-service (IaaS) cloud computing model, the customer retains responsibility for managing operating system and application security, while the vendor manages security at the hypervisor level and below. In a platform-as-a- service (PaaS) environment, the vendor takes on responsibility for the operating system, but the customer writes and configures any applications. In a software-as-a-service (SaaS) environment, the vendor takes on responsibility for the development and implementation of the application while the customer merely configures security settings within the application.

---

## Question 26
**Correct Answer:** A

**Explanation:**
Breach-and-attack simulation (BAS) tools typically leverage SaaS platforms as well as software agents and virtual machines to perform simulated attacks, which they leverage to provide detailed reports about security issues and their relative risk levels.

---

## Question 27
**Correct Answer:** D

**Explanation:**
Duress systems are intended to allow employees to notify security or others when they are in a dangerous situation or when they need help. Duress systems may be as simple as a push button and as complex as a code word or digital system that allows specific entries to trigger alarms while still performing a desired or deceptive but real-appearing action.

---

## Question 28
**Correct Answer:** C

**Explanation:**
While inode information leakage could represent a security concern, it does not pose the same immediate and direct risk as clickjacking, XSS vulnerabilities, or even the contextual importance of knowing the server's operating system. Clickjacking and cross-site scripting are both important issues, and knowing that the server is a Linux server is also important.

---

## Question 29
**Correct Answer:** D

**Explanation:**
The hearsay rule says that a witness cannot testify about what someone else told them, except under very specific exceptions. The courts have applied the hearsay rule to include the concept that attorneys may not introduce logs into evidence unless they are authenticated by the system administrator. In this scenario, George might also be able to provide a sworn affidavit, but the question doesn't include that option. The best evidence rule states that copies of documents may not be submitted into evidence if the originals are available. The parol evidence rule states that if two parties enter into a written agreement, that written document is assumed to contain all of the terms of the agreement. Testimonial evidence is a type of evidence, not a rule of evidence.

---

## Question 30
**Correct Answer:** B

**Explanation:**
Key risk indicators (KRIs) are valuable for organizational risk planning and understanding risk perceptions but are not designed for real-time security incident response. Tools like intrusion prevention systems (IPSs), security information and event management (SIEM) systems, and others are better equipped for immediate threat detection and response.

---

## Question 31
**Correct Answer:** B

**Explanation:**
Worms have built-in propagation mechanisms that do not require user interaction, such as scanning for systems containing known vulnerabilities and then exploiting those vulnerabilities to gain access. Viruses and Trojan horses typically require user interaction to spread. Logic bombs do not spread from system to system but lie in wait until certain conditions are met, triggering the delivery of their payload.

---

## Question 32
**Correct Answer:** A

**Explanation:**
As simple as the answer may seem, labeling media or even color coding it with sensitivity levels and ensuring staff are appropriately trained on what the levels mean will normally have the biggest impact.

Encrypting media can help, but without the labels, files may be stored on inappropriate media. A clear desk policy can help if casual media theft is an issue but is not likely to be an important control in this scenario. Dual control is used to ensure that a task cannot be performed by a single staff member to avoid malfeasance and is not directly useful here.

---

## Question 33
**Correct Answer:** B

**Explanation:**
MITRE's ATT&CK framework is broadly adopted by threat modeling and threat intelligence organizations and is used as a default model in many software packages and tools. The Diamond Model specifically addresses how to think about intrusions but does not address broader threats, and the other answers were made up for this question.

---

## Question 34
**Correct Answer:** A

**Explanation:**
The Agile approach to software development states that working software is the primary measure of progress, that simplicity is essential, and that businesspeople and developers must work together daily. It also states that the most efficient method of conveying information is face to face, not electronic.

---

## Question 35
**Correct Answer:** C

**Explanation:**
Integrity verification software would protect against this attack by identifying unexpected changes in protected data. Encryption, access controls, and firewalls would not be effective in this example because the accountants have legitimate access to the data.

---

## Question 36
**Correct Answer:** C

**Explanation:**
CAPEC, or Common Attack Pattern Enumeration and Classification, is a dictionary of known attack patterns. STIX is the Structured Threat Information eXpression language used to describe threats in a standardized way, and TAXII, the Trusted Automated eXchange of Indicator Information, defines how threat information can be shared and exchanged. All of these are examples of threat intelligence feed standards.

---

## Question 37
**Correct Answer:** B

**Explanation:**
Sole sourcing, or relying on a single vendor, can create additional fragility in supply chains due to reliance on a single supplier. Contractual controls including requirements for supplier insurance and liability limitations, having multiple suppliers, and validating their financial stability are all common ways to help reduce supply chain risk.

---

## Question 38
**Correct Answer:** B

**Explanation:**
SOC 2 reports are released under NDA to select partners or customers and can provide details on the controls and any issues they may have. A SOC 1 report would provide only financial control information, and a SOC 3 report provides less information since it is publicly available.

---

## Question 39
**Correct Answer:** C

**Explanation:**
An SOC 2, Type 2 report includes information about a data center's security, availability, processing integrity, confidentiality, and privacy, and includes an auditor's opinion on the operational effectiveness of the controls. SOC 3 does not have types, and a SOC 2 Type 1 is only conducted at a point in time.

---

## Question 40
**Correct Answer:** B

**Explanation:**
Susan asked for a security controls report (SOC 2) and received a financial internal controls report (SOC 1). This question doesn't specify whether a Type 1 or Type 2 report is desired, but most security practitioners will prefer a Type 2 report if they can get it since it tests the actual controls and their implementation instead of their descriptions.

---

## Question 41
**Correct Answer:** C

**Explanation:**
External auditors can provide an unbiased and impartial view of an organization's controls to third parties. Internal auditors are useful when reporting to senior management of the organization but are typically not asked to report to third parties. Penetration tests test technical controls but are not as well suited to testing many administrative controls. The employees who build and maintain controls are more

likely to bring a bias to the testing of those controls and should not be asked to report on them to third parties.

---

## Question 42
**Correct Answer:** C

**Explanation:**
Bell–LaPadula uses security labels on objects and clearances for subjects and is therefore a MAC model. It does not use discretionary, rule-based, role-based, or attribute-based access control.

---

## Question 43
**Correct Answer:** D

**Explanation:**
The Family Educational Rights and Privacy Act (FERPA) protects the privacy of students in any educational institution that accepts any form of federal funding. HIPAA is the Health Insurance Portability and Accountability Act and protects sensitive patient data in the hands of insurance and medical providers. The HITECH focuses on electronic health records and data security for healthcare data. COPPA is the Children's Online Privacy Protection Act.

---

## Question 44
**Correct Answer:** D

**Explanation:**
The Health Insurance Portability and Accountability Act (HIPAA) mandates the protection of protected health information (PHI). The Secure and Fair Enforcement for Mortgage Licensing (SAFE) Act deals with mortgages, the Graham–Leach–Bliley Act (GLBA) covers financial institutions, and the Family Educational Rights and Privacy Act (FERPA) deals with student data.

---

## Question 45
**Correct Answer:** D

**Explanation:**
Sandboxing tools allow defenders to execute potentially malicious software in an isolated environment that provides instrumentation to capture all actions and changes performed when it is run. SIEM, or security information and event management, tools and SOAR, or security orchestration, automation, and response, tools are used to monitor environments and to respond to incidents but do not provide the ability to test and observe malicious software. SAST, or Static Application Security Testing, tools analyze source code to identify security issues.

---

## Question 46
**Correct Answer:** D

**Explanation:**
Implementations of syslog vary, but most provide a setting for severity level, allowing the configuration of a value that determines what messages are sent. Typical severity levels include debug, informational, notice, warning, error, critical, alert, and emergency. The facility code is also supported by syslog but is associated with which services are being logged. Security level and log priority are not typical syslog settings.

---

## Question 47
**Correct Answer:** D

**Explanation:**
RAID 5 is commonly used because it balances resilience and efficiency of storage space used by relying on distributed parity. RAID 0 uses two disks as a single volume, allowing for an increase in speed but a decrease in reliability. In RAID 1, also known as disk mirroring, systems contain two physical disks. Each disk contains copies of the same data, and either one may be used in the event the other disk fails RAID 3 is rarely used and uses byte-level striping and a dedicated parity disk.

---

## Question 48
**Correct Answer:** A

**Explanation:**
Most vendors use the term end of life, or EOL, to denote when the product will stop being sold. End of support typically comes sometime after end of life, and this problem does not specify when end of support (EOS) will occur. Devices will still function after end of life and likely after end of support, but security professionals should raise concerns about the security of devices or software after the end of support because patches and updates will likely no longer be available.

---

## Question 49
**Correct Answer:** C

**Explanation:**
Interviews, surveys, and audits are all useful for assessing awareness. Code quality is best judged by code review, service vulnerabilities are tested using vulnerability scanners and related tools, and the attack surface of an organization requires both technical and administrative review.

---

## Question 50
**Correct Answer:** B

**Explanation:**
Unconstrained API calls can lead to denial-of-service conditions, one of the top 10 API security risks identified by OWASP in 2023. Attributing actions to an account requires proper authentication and logging, which are not tied to resource over-consumption. Malicious file access is typically due to improperly configured security, and request forgery attacks typically occur when user-supplied URIs are not validated.

---

## Question 51
**Correct Answer:** C

**Explanation:**
Tokens are hardware devices (something you have) that generate a one-time password (OTP) based on time or an algorithm. They are typically combined with another factor like a password to authenticate users. CAC and PIV cards are U.S. government–issued smartcards.

---

## Question 52
**Correct Answer:** B

**Explanation:**
A nondisclosure agreement (NDA) is a legal agreement between two parties that specifies what data they will not disclose. NDAs are common in industries that have sensitive or trade secret information they do not want employees to take to new jobs. Encryption would only help in transit or at rest, and Fred will likely have access to the data in unencrypted form as part of his job. An AUP is an acceptable use policy, and a stop-loss order is used on the stock market.

---

## Question 53
**Correct Answer:** C

**Explanation:**
Civil cases typically rely on a preponderance of evidence. Criminal cases must be proven beyond a reasonable doubt. Real evidence is object evidence— tangible things that can be brought into a court of law. Documentary evidence are written items used to prove facts. Neither of these is an evidentiary standard; instead, they describe types of evidence.

---

## Question 54
**Correct Answer:** C

**Explanation:**
Binary key spaces contain a number of keys equal to 2 raised to the power of the number of bits. Two to the

eighth power is 256, so an 8-bit key space contains 256 possible keys.

---

## Question 55
**Correct Answer:** C

**Explanation:**
Scoping is the process of reviewing and selecting security controls based on the system that they will be applied to. Editing is not a commonly used term in this context. Baselines are used as a base set of security controls, often from a third-party organization that creates them. Standardization isn't a relevant term here.

---

## Question 56
**Correct Answer:** B

**Explanation:**
Background checks are frequently performed to identify potential issues before hiring a new employee. They can identify a variety of concerns and are commonly used across many industries. Nondisclosure agreements (NDAs) are used during and after employment to protect confidential information. Noncompetes are used to prevent employees from working in a similar industry for a given period of time after departure. COA, or certificate of authenticity, is not used in employment situations.

---

## Question 57
**Correct Answer:** D

**Explanation:**
Systems and media should be labeled with the highest level of sensitivity that they store or handle. In this case, based on the U.S. government classification scheme, the highest classification level in use on the system is Secret. Mixed classification provides no useful information about the level, whereas Top Secret and Confidential are too high and too low, respectively.

---

## Question 58
**Correct Answer:** C

**Explanation:**
She has placed compensating controls in place. Compensating controls are used when controls like the locks in this example are not sufficient. While the alarm is a physical control, the signs she posted are not. Similarly, the alarms are not administrative controls. None of these controls helps to recover from an issue, and they are thus not recovery controls.

---

## Question 59
**Correct Answer:** D

**Explanation:**
Insurance is a form of risk transfer. Organizations pay insurers premiums, transferring the risk to them in exchange for the payment. Insurers may mitigate their risk through the terms of the insurance policy and may also insure themselves. Acceptance simply means acknowledging the risk, avoidance would require means to prevent the risk from occurring, and mitigation attempts to reduce the impact of the risk if it occurs.

---

## Question 60
**Correct Answer:** D

**Explanation:**
A SOC 2 assessment looks at controls that affect security, and a Type 2 report validates the operating effectiveness of the controls. SOC 1 engagement assesses controls that might impact financial reporting, and a Type 1 report provides the auditors opinions of the descriptions of controls provided by management at a single point in time—not the actual implementations of the controls.

---

## Question 61
**Correct Answer:** C

**Explanation:**
The ability to inspect open-source software (OSS) means that organizations can inspect it but more importantly that others can and often have also inspected it. This results in software that has had far more review than some closed-source or commercial packages (although large organizations may perform more review). The ability to change the code can sometimes be important as well, but changing open- source code in-house can create maintenance issues in the future. Open-source software may be compiled, but the source will still be available. The code being free is not a security advantage or disadvantage.

---

## Question 62
**Correct Answer:** B

**Explanation:**
Provisioning includes the creation, maintenance, and removal of user objects from applications, systems, and directories. Registration occurs when users are enrolled in a biometric system; population and authenticator loading are not common industry terms.

---

## Question 63
**Correct Answer:** C

**Explanation:**
Release control occurs after changes are finalized. With changes that are ready to be implemented in hand, release managers can follow their process with steps that typically include removing debugging code and conducting acceptance testing. Request control is the start of a process that allows users to submit change requests, while change control handles the process of ensuring quality assurance happens, that documentation is done, and that security testing is handled. Finally, configuration control is part of software configuration management, not the change process.

---

## Question 64
**Correct Answer:** C

**Explanation:**
The formula for determining the number of encryption keys required by a symmetric algorithm is ((n*(n − 1))/2). With six users, you will need ((6*5)/2), or 15 keys.

---

## Question 65
**Correct Answer:** B

**Explanation:**
Patents have the shortest duration of the techniques listed: at most, 20 years. Copyrights last for 70 years beyond the death of the author if owned by an individual, or 95 years from publication or 120 years from creation if owned by a corporation. Trademarks are renewable indefinitely, and trade secrets are protected as long as they remain secret.

---

## Question 66
**Correct Answer:** C

**Explanation:**
In a risk acceptance strategy, the organization chooses to take no action other than documenting the risk. Purchasing insurance would be an example of risk transference. Relocating the data center would be risk avoidance. Reengineering the facility is an example of a risk mitigation strategy.

---

## Question 67
**Correct Answer:** C

**Explanation:**
Uninterruptible power supplies (UPSs) provide immediate, battery-driven power for a short period of time to cover momentary losses of power. Generators are capable of providing backup power for a sustained period of time in the event of a power loss, but they

take time to activate. RAID and redundant servers are high-availability controls but do not cover power loss scenarios.

---

## Question 68
**Correct Answer:** C

**Explanation:**
Password histories retain a list of previous passwords, preferably a list of salted hashes for previous passwords, to ensure that users don't reuse their previous passwords. Longer minimum age can help prevent users from changing their passwords and then changing them back but won't prevent a determined user from eventually getting their old password back. Length requirements and complexity requirements tend to drive users to reuse passwords if they're not paired with tools like single sign-on, password storage systems, or other tools that decrease the difficulty of password management.

---

## Question 69
**Correct Answer:** B

**Explanation:**
The single loss expectancy (SLE) is the amount of damage that a risk is expected to cause each time it occurs. ALE is the annual loss expectancy (probability of loss times reduction in value if a loss occurs), ARO is the annual rate of occurrence or how often in a given year the event is likely to happen, and AV is the asset value.

---

## Question 70
**Correct Answer:** B

**Explanation:**
Sanitization includes steps such as removing the hard drive and other local storage from PCs before they are sold as surplus. Degaussing uses magnetic fields to wipe media, purging is an intense form of clearing used to ensure that data is removed and unrecoverable from media, and removing does not necessarily imply destruction of the drive.

---

## Question 71
**Correct Answer:** D

**Explanation:**
During the Reporting phase, incident responders assess their obligations under laws and regulations to report the incident to government agencies and other regulators.

---

## Question 72
**Correct Answer:** B

**Explanation:**
The bank that Charles works at is using job rotation to ensure that employees are not exploiting the rights and permissions that they have in their roles. The practice is intended to allow the next person in the role to identify irregularities and to prevent individuals from hiding malfeasance. Dual control requires two or more staff members to complete a task to ensure that a single employee cannot abuse their role. Cross-training ensures that multiple staff members have the necessary skills for a task, reducing the impact of losing a staff member.

---

## Question 73
**Correct Answer:** B

**Explanation:**
Full device encryption, when combined with mandatory passcodes, offers the strongest defense against data loss from stolen devices. Encryption secures data at rest, making it unreadable without the correct decryption key, while passcodes provide an initial barrier against unauthorized access. Although application management, remote wipe, and GPS tracking are valuable for overall device security and recovery, they do not offer the same level of data protection as encryption and passcodes. Specifically, encryption ensures data security independently of the device's network connectivity or physical location.

---

## Question 74
**Correct Answer:** D

**Explanation:**
SMTP servers that don't authenticate users before relaying their messages are known as open relays. Open relays that are Internet-exposed are typically quickly exploited to send email for spammers.

---

## Question 75
**Correct Answer:** D

**Explanation:**
Sending logs to a secure log server is the most effective way to ensure that logs survive a breach. Encrypting local logs won't stop an attacker from deleting them, and requiring administrative access won't stop attackers who have breached a machine and acquired escalated privileges. Log rotation archives logs based on time or file size and can also purge logs

after a threshold is hit. Rotation won't prevent an attacker from purging logs.

---

## Question 76
**Correct Answer:** C

**Explanation:**
A security information and event management (SIEM) tool is designed to provide automated analysis and monitoring of logs and security events. A SIEM tool that receives access to logs can help detect and alert on events such as logs being purged or other breach indicators. An IDS can help detect intrusions, but IDSs are not typically designed to handle central logs. A central logging server can receive and store logs but won't help with analysis without taking additional actions. Syslog is simply a log format.

---

## Question 77
**Correct Answer:** B

**Explanation:**
Requiring authentication can help provide accountability by ensuring that any action taken can be tracked back to a specific user. Storing logs centrally ensures that users can't erase the evidence of actions that they have taken. Log review can be useful when identifying issues, but digital signatures are not a typical part of a logging environment. Logging the use of administrative credentials helps for those users but won't cover all users, and encrypting the logs doesn't help with accountability. Authorization helps, but being able to specifically identify users through authentication is more important.

---

## Question 78
**Correct Answer:** B

**Explanation:**
Port address translation (PAT) is used to allow a network to use any IP address set inside without causing a conflict with the public Internet. PAT is often confused with network address translation (NAT), which maps one internal address to one external address. IPsec is a security protocol suite, software- defined networking (SDN) is a method of defining networks programmatically, and IPX is a non-IP network protocol.

---

## Question 79
**Correct Answer:** C

**Explanation:**
Each of the precautions listed helps to prevent social engineering by helping prevent exploitation of trust. Avoiding voice-only communications is particularly important, since establishing identity over the phone is difficult. The other listed attacks would not be prevented by these techniques.

---

## Question 80
**Correct Answer:** A

**Explanation:**
The CIS benchmarks provide a useful security standard and baseline to assess systems against or to configure them to. Organizations can adapt and modify the baseline to meet their specific needs while speeding up deployment by using an accepted industry standard. They are not a compliance standard and do not provide provisioning or automation, but tools that do may use the benchmark as a standard to do so.

---

## Question 81
**Correct Answer:** D

**Explanation:**
Remnant data is data that is left after attempts have been made to remove or erase it. Bitrot is a term used to describe aging media that decays over time. MBR is the master boot record, a boot sector found on hard drives and other media. Leftover data is not an industry term.

---

## Question 82
**Correct Answer:** C

**Explanation:**
During a parallel test, the team activates the disaster recovery site for testing, but the primary site remains operational. A simulation test involves a role- play of a prepared scenario overseen by a moderator. Responses are assessed to help improve the organization's response process. The checklist review is the least disruptive type of disaster recovery test. During a checklist review, team members each review the contents of their disaster recovery checklists on their own and suggest any necessary changes. During a tabletop exercise, team members come together and walk through a scenario without making any changes to information systems.

---

## Question 83
**Correct Answer:** C

**Explanation:**
Discretionary access control gives owners the right to decide who has access to the objects they own. Role- based access control uses administrators to make that decision for roles or groups of people with a role, task- based access control uses lists of tasks for each user, and rule-based access control applies a set of rules to all subjects.

---

## Question 84
**Correct Answer:** C

**Explanation:**
Trusted paths that secure network traffic from capture and link encryption are both ways to help prevent man-in-the-middle attacks. Brute-force and dictionary attacks can both be prevented using back-off algorithms that slow down repeated attacks. Log analysis tools can also create dynamic firewall rules, or an IPS can block attacks like these in real time. Spoofed login screens can be difficult to prevent, although user awareness training can help.

---

## Question 85
**Correct Answer:** D

**Explanation:**
The four canons of the ISC2 Code of Ethics are to protect society, the common good, the necessary public trust and confidence, and the infrastructure; act honorably, honestly, justly, responsibly, and legally; provide diligent and competent service to principals; and advance and protect the profession.

---

## Question 86
**Correct Answer:** A

**Explanation:**
The emergency response guidelines should include the immediate steps an organization should follow in response to an emergency situation. These include immediate response procedures, a list of individuals who should be notified of the emergency, and secondary response procedures for first responders. They do not include long-term actions such as activating business continuity protocols, ordering equipment, or activating DR sites.

---

## Question 87
**Correct Answer:** C

**Explanation:**
Security Assertion Markup Language (SAML) is the best choice for providing authentication and authorization information, particularly for browser-

based SSO. HTML is primarily used for web pages, SPML is used to exchange user information for SSO, and XACML is used for access control policy markup.

---

## Question 88
**Correct Answer:** D

**Explanation:**
Individuals with specific business continuity roles should receive training on at least an annual basis.

---

## Question 89
**Correct Answer:** B

**Explanation:**
Application programming interfaces (APIs), user interfaces (UIs), and physical interfaces are all tested during the software testing process. Network interfaces are not typically tested, and programmatic interfaces are another term for APIs.

---

## Question 90
**Correct Answer:** A

**Explanation:**
Product tampering, implants of software or hardware, and counterfeits are all common concerns for gray-market hardware. API vulnerabilities are a concern based on vendor software and may exist and require patching whether a device is purchased through an OEM or the gray market.

---

## Question 91
**Correct Answer:** C

**Explanation:**
Virtual routing and forwarding (VRF) allows multiple routing tables to be used on the same device simultaneously. This is similar to the concept of VLANs on a layer 2 switch but operating at layer 3. Routing instances operate independently, allowing IP addresses to overlap without conflict, supporting segmentation and thus permitting flexibility for zero trust implementations and other security solutions. VRF can be used to support VPCs, but that is not its only use. It is not like a VPN, and while it can be used with multilayer protocols, that isn't a primary purpose.

---

## Question 92
**Correct Answer:** A

**Explanation:**
RSA is an asymmetric encryption algorithm that requires only two keys for each user. IDEA, 3DES, and Skipjack are all symmetric encryption algorithms and would require a key for every unique pair of users in the system.

---

## Question 93
**Correct Answer:** D

**Explanation:**
Function-as-a-service deployments are an example of a serverless deployment running on the cloud provider's cloud environment. Serverless computing solutions like AWS Lambda, Microsoft Azure Functions, and Google Cloud functions require less overhead when applications are designed from the ground up to leverage function as a service technology. ICS is an industrial control system used to manage systems and processes such as utilities or factories. VPCs are virtual private clouds where infrastructure is provisioned and used like a virtual data center, and embedded systems are built into other devices.

---

## Question 94
**Correct Answer:** D

**Explanation:**
The log entries contained in this example show the allow/deny status for inbound and outbound TCP and UDP sessions. This is, therefore, an example of a firewall log.

---

## Question 95
**Correct Answer:** D

**Explanation:**
Zero-day vulnerabilities remain in the dangerous zero-day category until the release of a patch that corrects the vulnerability. At that time, it becomes the responsibility of IT professionals to protect their systems by applying the patch. Implementation of other security controls, such as encryption or firewalls, does not change the nature of the zero-day vulnerability.

---

## Question 96
**Correct Answer:** C

**Explanation:**
An HTML5-based VPN will provide Elle's staff with access to the applications they need without requiring the installation of a client that might be challenging or impossible without managed machines. A client-based IPsec VPN provides additional opportunities for control that a broadly deployed base of directly accessed machines via RDP does not, making it the second-best choice here. Deploying fiber for direct connections for end users is not viable for most organizations based on cost and complexity.

---

## Question 97
**Correct Answer:** B

**Explanation:**
Edge computing is a technology that involves placing infrastructure closer to the point of use. This approach offers several benefits such as reduced latency, improved performance for local processing, and reduced traffic to remote data centers or the cloud. On the other hand, cloud computing is typically provided at a remote facility, is scalable and frequently multitenant. Hybrid cloud is a combination of local and remote clouds. Finally, microservices utilize loosely coupled services that communicate via lightweight protocols to accomplish specific tasks that are then combined to achieve overall goals.

---

## Question 98
**Correct Answer:** C

**Explanation:**
The sender of a message encrypts the message using the public key of the message recipient.

---

## Question 99
**Correct Answer:** D

**Explanation:**
The recipient of a message uses their own private key to decrypt messages that were encrypted with the recipient's public key. This ensures that nobody other than the intended recipient can decrypt the message.

---

## Question 100
**Correct Answer:** D

**Explanation:**
Digital signatures enforce nonrepudiation. They prevent individuals from denying that they were the actual originator of a message.

---

## Question 101
**Correct Answer:** B

**Explanation:**
An individual creates a digital signature by encrypting the message digest with their own private key.

---

## Question 102
**Correct Answer:** D

**Explanation:**
The comparison of a factor to validate an identity is known as authentication. Identification would occur when Jim presented his user ID. Tokenization is a process that converts a sensitive data element to a nonsensitive representation of that element. Hashing transforms a string of characters into a fixed-length value or key that represents the original string.

---

## Question 103
**Correct Answer:** C

**Explanation:**
The most important item in facility design is the safety of personnel. Once designs take that into

account, security, operational effectiveness, and other concerns can be addressed.

---

## Question 104
**Correct Answer:** C

**Explanation:**
An access control vestibule (sometimes called a mantrap), which is composed of two sets of doors with an access mechanism that allows only one door to open at a time, is an example of a preventive access control because it can stop unwanted access by keeping intruders from accessing a facility due to an opened door or following legitimate staff in. It can serve as a deterrent by discouraging intruders who would be trapped in it without proper access, and of course, doors with locks are an example of a physical control. A compensating control attempts to make up for problems with an existing control or to add additional controls to improve a primary control.

---

## Question 105
**Correct Answer:** C

**Explanation:**
To ensure emails can be definitively attributed to their senders, Sally needs the capability of nonrepudiation. Digital signatures fulfill this need by using cryptographic techniques to bind a sender's identity to a message, making it impossible for the sender to deny having sent the email. Unlike IMAP, which is a protocol for accessing email, and DKIM, which verifies the domain origin of an email, digital signatures provide cryptographic proof of origin and integrity. Encryption, while securing the content of messages, does not inherently provide nonrepudiation.

---

## Question 106
**Correct Answer:** D

**Explanation:**
In most situations, employers may not access medical information due to healthcare privacy laws. Reference checks, criminal records checks, and credit history reports are all typically found during pre- employment background checks.

---

## Question 107
**Correct Answer:** A

**Explanation:**
Naomi's organization operates under the concept of least privilege. Individuals only receive the rights that they need to accomplish their tasks. This also means

that the organization will need to ensure that those rights do not accrue to users over time and that they are changed or removed when user roles change. Privileged account management is the process of properly managing accounts with higher levels of privilege like administrative accounts. Job rotation moves employees between roles to ensure that they do not take advantage of the role and that a new set of eyes can help identify problems. Privilege escalation is the process of gaining additional rights when attacking systems or services.

---

## Question 108
**Correct Answer:** A

**Explanation:**
When a data stream is converted into a segment (TCP) or a datagram (UDP), it transitions from the Session layer to the Transport layer. This change from a message sent to an encoded segment allows it to then traverse the Network layer.

---

## Question 109
**Correct Answer:** C

**Explanation:**
The user has successfully explained a valid “need to know” the data—completing the report requested by the CFO requires this access. However, the user has not yet demonstrated that they have appropriate clearance to access the information. A note from the CFO would meet this requirement.

---

## Question 110
**Correct Answer:** B

**Explanation:**
Sharif is using gamification, the process of making awareness efforts like a game to motivate users. Security champions are staff members who are selected or volunteer to advocate for and raise security awareness in their teams and divisions. Social engineering efforts leverage human behaviors, and awareness training is training intended to raise awareness of security risks, issues, and attacker techniques.

---

## Question 111
**Correct Answer:** D

**Explanation:**
A system inventory is most frequently used to associate individuals with systems or devices. This can help when tracking their support history and aids in

provisioning the proper tools, permissions, and data to a system. Both barcode and RFID property tags are used to identify systems, which can then be checked against a system inventory. Finally, enterprise content management tools are used to manage files and data as part of workflows and other business processes.

---

## Question 112
**Correct Answer:** C

**Explanation:**
The create rule allows a subject to create new objects and also creates an edge from the subject to that object, granting rights to the new object.

---

## Question 113
**Correct Answer:** A

**Explanation:**
Metasploit provides an extensible framework, allowing penetration testers to create their own exploits in addition to those that are built into the tool. Unfortunately, penetration testing can only cover the point in time when it is conducted. When conducting a penetration test, the potential to cause a denial of service due to a fragile service always exists, but it can test processes and policies through social engineering and operational testing that validates how those processes and policies work.

---

## Question 114
**Correct Answer:** A

**Explanation:**
Data remanence is a concern due to the storage devices often found in multifunction photocopier/printer devices, particularly for devices used in an administrative headquarters. While compliance may be a concern, we don't know enough about Colin's organization to know if compliance concerns would require this. Asset management and asset inventory can both handle either destruction or sale for most organizations.

---

## Question 115
**Correct Answer:** C

**Explanation:**
X.509 defines standards for public key certificates like those used with many smartcards. X.500 is a series of standards defining directory services. The Service Provisioning Markup Language (SPML) and the Security Assertion Markup Language (SAML) aren't

standards that Alex should expect to see when using a smartcard to authenticate.

---

## Question 116
**Correct Answer:** C

**Explanation:**
The Children's Online Privacy Protection Act (COPPA) regulates websites that cater to children or knowingly collect information from children younger than 13.

---

## Question 117
**Correct Answer:** A

**Explanation:**
The Health Insurance Portability and Accountability Act (HIPAA) applies to healthcare information and is unlikely to apply in this situation. The Federal Information Security Modernization Act (FISMA) and Government Information Security Reform Act regulate the activities of all government agencies. The Homeland Security Act (HSA) created the U.S. Department of Homeland Security and, more importantly for this question, included the Cyber Security Enhancement Act of 2002 and the Critical Infrastructure Information Act of 2002. The Computer Fraud and Abuse Act (CFAA) provides specific protections for systems operated by government agencies.

---

## Question 118
**Correct Answer:** C

**Explanation:**
FedRAMP is a U.S. government compliance program that standardizes how cloud services are assessed, monitored, and handle authorization. There is a FedRAMP marketplace for service providers and services that have been authorized by FedRAMP. COBIT is an IT management and governance framework, SABSA is a risk-based enterprise information security model, and PCI is a security standard created by and used by the payment card industry.

---

## Question 119
**Correct Answer:** C

**Explanation:**
Access control systems rely on identification and authentication to provide accountability. Effective authorization systems are desirable, but not required, since logs can provide information about who accessed

what resources, even if access to those resources is not managed well. Of course, poor authorization management can create many other problems.

---

## Question 120
**Correct Answer:** B

**Explanation:**
Checksums validate whether a file or other data object has been changed or modified, and thus, they support integrity.

---

## Question 121
**Correct Answer:** C

**Explanation:**
The 192.168.0.0 to 192.168.255.255 address range is one of the ranges defined by RFC 1918 as private, nonroutable IP ranges. Scott's ISP (and any other organization with a properly configured router) will not route traffic from these addresses over the public Internet.

---

## Question 122
**Correct Answer:** B

**Explanation:**
Jack's organization is using a continuous integration/continuous delivery (CI/CD) model where the application is updated and deployed on an ongoing basis. This can allow for an agile application but requires strong testing and validation practices to ensure that bad code doesn't make it into production. Waterfall is a development model that is based on a slower, precise process. SCM is software configuration management, and an IDE is an integrated development environment.

---

## Question 123
**Correct Answer:** A

**Explanation:**
A well-designed set of VLANs based on functional groupings will logically separate segments of the network, making it difficult to have data exposure issues between VLANs. Changing the subnet mask will only modify the broadcast domain and will not fix issues with packet sniffing. Gateways would be appropriate if network protocols were different on different segments. Port security is designed to limit which systems can connect to a given port.

---

## Question 124
**Correct Answer:** B

**Explanation:**
Any 10.x.x.x address is a private address as defined by RFC 1918. APIPA addresses are self-assigned by

Windows when they cannot contact a DHCP server. 127.0.0.1 is a loopback address that systems use to connect with themselves. Public IP addresses compose the majority of IP addresses with the exception of reserved addresses like those described in RFC 1918.

---

## Question 125
**Correct Answer:** D

**Explanation:**
Nikto is a web application and server scanning tool and is best suited to Jim's needs. Nmap is a port scanner, Hydra is a login cracking tool, and Metasploit is a complete penetration testing framework but isn't designed specifically to test web applications and servers.

---

