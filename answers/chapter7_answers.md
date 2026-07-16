# CISSP Practice Tests - Chapter 7: Security Operations (Domain 7) Answer Key

## Question 1
**Correct Answer:** A

**Explanation:**
The illustration shows an example of a failover cluster, where DB1 and DB2 are both configured as database servers. At any given time, only one will function as the active database server, while the other remains ready to assume responsibility if the first one fails. While the environment may use UPS, tape backup, and cold sites as disaster recovery and business continuity controls, they are not shown in the diagram.

---

## Question 2
**Correct Answer:** D

**Explanation:**
The principle of least privilege should guide Joe in this case. He should apply no access permissions by default and then give each user the necessary permissions to perform their job responsibilities. Read only, editor, and administrator permissions may be necessary for one or more of these users, but those permissions should be assigned based upon business need and not by default.

---

## Question 3
**Correct Answer:** C

**Explanation:**
While most organizations would want to log attempts to log in to a workstation, this is not considered a privileged administrative activity and would go through normal logging processes.

---

## Question 4
**Correct Answer:** B

**Explanation:**
Duress, or being under threat of violence or other constraints, is a concern for organizations such as banks, jewelry stores, or other organizations where an attacker may attempt to force an employee to perform actions. Organizations that expect that a scenario like this may occur will often use duress code words that let others know that they are performing actions under threat.

---

## Question 5
**Correct Answer:** D

**Explanation:**
Real evidence consists of things that may actually be brought into a courtroom as evidence. For example,

real evidence includes hard disks, weapons, and items containing fingerprints. Documentary evidence consists of written items that may or may not be in tangible form. Testimonial evidence is verbal testimony given by witnesses with relevant information. The parol evidence rule says that when an agreement is put into written form, the written document is assumed to contain all the terms of the agreement.

---

## Question 6
**Correct Answer:** C

**Explanation:**
A whitelist of allowed applications will ensure that Lauren's users can run only the applications that she preapproves. Blacklists would require her to maintain a list of every application that she doesn't want to allow, which is an almost impossible task. Graylisting is not a technology option. Configuration management can be useful for making sure the right applications are on a PC but typically can't directly prevent users from running undesired applications or programs.

---

## Question 7
**Correct Answer:** B

**Explanation:**
A pseudo-flaw is a false vulnerability in a system that may distract an attacker. A honeynet is a network of multiple honeypots that creates a more sophisticated environment for intruders to explore, rather than a feature Colin could use on a honeypot. A darknet is a segment of unused network address space that should have no network activity and, therefore, may be easily used to monitor for illicit activity. A warning banner is a legal tool used to notify intruders that they are not authorized to access a system.

---

## Question 8
**Correct Answer:** B

**Explanation:**
Social media is commonly used as a command-and- control system for botnet activity. The most likely scenario here is that the user's computer was infected with malware and joined to a botnet. This accounts for both the unusual social media traffic and the slow system activity.

---

## Question 9
**Correct Answer:** A

**Explanation:**
John's design provides multiple processing sites, distributing load to multiple regions. Not only does this provide business continuity and disaster recovery functionality, but it also means that his design will be more resilient to denial-of-service attacks.

---

## Question 10
**Correct Answer:** A

**Explanation:**
NetFlow records contain an entry for every network communication session that took place on a network and can be compared to a list of known malicious hosts. IDS logs may contain a relevant record, but it is less likely because they would create log entries only if the traffic triggers the IDS, as opposed to NetFlow records, which encompass all communications. Authentication logs and RFC logs would not have records of any network traffic.

---

## Question 11
**Correct Answer:** B

**Explanation:**
Gary should follow the least privilege principle and assign users only the permissions they need to perform their job responsibilities. Privilege creep is a term used to describe the unintentional accumulation of privileges over time. Segregation of duties and separation of privileges are principles used to secure sensitive processes.

---

## Question 12
**Correct Answer:** A

**Explanation:**
The matrix shown in the figure is known as a segregation of duties matrix. It is used to ensure that one person does not obtain two privileges that would create a potential conflict. Privilege creep is a term used to describe the unintentional accumulation of privileges over time. Two-person control is used when two people must work together to perform a sensitive action. Defense in depth is a general security principle used to describe a philosophy of overlapping security controls.

---

## Question 13
**Correct Answer:** B

**Explanation:**
Before granting access, Gary should verify that the user has a valid security clearance and a business need to know the information. Gary is performing an

authorization task, so he does not need to verify the user's credentials, such as a password or biometric scan.

---

## Question 14
**Correct Answer:** D

**Explanation:**
Gary should follow the principle of two-person control by requiring simultaneous action by two separate authorized individuals to gain access to the encryption keys. He should also apply the principles of least privilege and defense in depth, but these principles apply to all operations and are not specific to sensitive operations. Gary should avoid the security through obscurity principle, the reliance upon the secrecy of security mechanisms to provide security for a system or process.

---

## Question 15
**Correct Answer:** A, B, C

**Explanation:**
Privileged access reviews are one of the most critical components of an organization's security program because they ensure that only authorized users have access to perform the most sensitive operations. They should take place whenever a user with privileged access leaves the organization or changes roles as well as on a regular, recurring basis. However, it is not reasonable to expect that these time- consuming reviews would take place on a daily basis.

---

## Question 16
**Correct Answer:** D

**Explanation:**
Hotfixes, updates, and security fixes are all synonyms for single patches designed to correct a single problem. Service packs are collections of many different updates that serve as a major update to an operating system or application.

---

## Question 17
**Correct Answer:** C

**Explanation:**
A forensic disk controller performs four functions. One of those, write blocking, intercepts write commands sent to the device and prevents them from modifying data on the device. The other three functions include returning data requested by a read operation, returning access-significant information from the

device, and reporting errors from the device back to the forensic host.

---

## Question 18
**Correct Answer:** A

**Explanation:**
Lydia is following the need to know principle. While the user may have the appropriate security clearance to access this information, there is no business justification provided, so she does not know that the user has an appropriate need to know the information.

---

## Question 19
**Correct Answer:** C

**Explanation:**
Job rotation and mandatory vacations deter fraud by increasing the likelihood that it will be detected. Two- person control deters fraud by requiring collusion between two employees. Incident response does not normally serve as a deterrent mechanism.

---

## Question 20
**Correct Answer:** B

**Explanation:**
Quality of service is a feature found on routers and other network devices that can prioritize specific network traffic. QoS policies define which traffic is prioritized, and traffic is then handled based on the policy.

---

## Question 21
**Correct Answer:** A

**Explanation:**
The change log contains information about approved changes and the change management process. While other logs may contain details about the change's effect, the audit trail for change management would be found in the change log.

---

## Question 22
**Correct Answer:** B

**Explanation:**
While it may be tempting to tell her staff to simply not connect to any network, Susan knows that they will need connectivity to do their work. Using a VPN to connect their laptops and mobile devices to a trusted network and ensuring that all traffic is tunneled through the VPN is her best bet to secure their Internet usage. Susan may also want to ensure that they take “clean” laptops and devices that do not contain sensitive information or documents and that those systems are fully wiped when they return.

---

## Question 23
**Correct Answer:** D

**Explanation:**
The Common Vulnerabilities and Exposures (CVE) database contains standardized information on many different security issues. The Open Worldwide Application Security Project (OWASP) contains general guidance on web application security issues but does not track specific vulnerabilities or go beyond web applications. The Center for Internet Security (CIS) maintains benchmarks for securely configuring devices, operating systems, and applications. They do not track vulnerabilities. Microsoft Security Bulletins are also good sources of vulnerability information but are not comprehensive databases of known issues.

---

## Question 24
**Correct Answer:** A, B, C, D

**Explanation:**
A disaster is any event that can disrupt normal IT operations and can be either natural or human made. Hacking and terrorism are examples of human-made disasters, while flooding and fire are examples of natural disasters.

---

## Question 25
**Correct Answer:** D

**Explanation:**
The read-through is the least disruptive type of disaster recovery test. During a read-through, team members each review the contents of their disaster recovery checklists on their own and suggest any necessary changes. During a tabletop exercise, team members come together and discuss a specific scenario without making any changes to information systems. During a parallel test, the team actually activates the disaster recovery site for testing, but the primary site remains operational. During a full interruption test, the team takes down the primary site and confirms that the disaster recovery site is capable of handling regular operations. The full interruption test is the most thorough test but also the most disruptive.

---

## Question 26
**Correct Answer:** B

**Explanation:**
The Grandfather-Father-Son, Tower of Hanoi, and Six Cartridge Weekly schemes are all different approaches to rotating backup media that balance

reuse of media with data retention concerns. Meet-in- the-middle is a cryptographic attack against 2DES encryption.

---

## Question 27
**Correct Answer:** B

**Explanation:**
In this scenario, Helen designed a process that requires the concurrence of two people to perform a sensitive action. This is an example of two-person control. This is different from segregation of duties, where one individual may not have two separate permissions that, when combined, might allow an unwanted action. Segregation of duties applied to a situation like this one might say that the same person may not have both the ability to initiate a request and the ability to approve a request. Least privilege says that an individual should have only the necessary permissions required to carry out their job function. Job rotation is a scheme that has users periodically shift job functions in order to detect malfeasance.

---

## Question 28
**Correct Answer:** C

**Explanation:**
Evidence provided in court must be relevant to determining a fact in question, material to the case at hand, and competently obtained. Evidence does not need to be tangible. Witness testimony is an example of intangible evidence that may be offered in court.

---

## Question 29
**Correct Answer:** A

**Explanation:**
A lessons learned document is often created and distributed to involved parties after a postmortem review to ensure that those who were involved in the incident and others who may benefit from the knowledge are aware of what they can do to prevent future issues and to improve response in the event that one occurs.

---

## Question 30
**Correct Answer:** A, C, D

**Explanation:**
CSIRT representation normally includes at least representatives of senior management, information security professionals, legal representatives, public relations staff, human resources, and engineering/technical staff. Law

enforcement personnel would not be included on such a team and would only be consulted as necessary.

---

## Question 31
**Correct Answer:** C

**Explanation:**
In this scenario, all the files on the server will be backed up on Monday evening during the full backup. The differential backup on Wednesday will then copy all files modified since the last full backup. These include files 1, 2, 3, 5, and 6: a total of five files.

---

## Question 32
**Correct Answer:** C

**Explanation:**
Intrusion detection systems (IDSs) provide only passive responses, such as alerting administrators to a suspected attack. Intrusion prevention systems and firewalls, on the other hand, may take action to block an attack attempt. Antivirus software also may engage in active response by quarantining suspect files.

---

## Question 33
**Correct Answer:** C

**Explanation:**
Physical destruction, an appropriate contract with certification, and secure wiping are all reasonable options. In each case, a careful inventory and check should be done to ensure that each drive is handled appropriately. Reformatting drives can leave remnant data, making this a poor data life-cycle choice for drives that contain sensitive data.

---

## Question 34
**Correct Answer:** D

**Explanation:**
Secure router configuration guidelines are typically more technical and specific to IT professionals, making them less likely to be included in a general security training and awareness program. These programs usually focus on broader and more universally applicable topics like insider threats, which address risks from employees or contractors; social media impact, which covers the risks of sharing information online; and 2FA fatigue, which relates to the weariness or complacency in using two-factor authentication. These are relevant to a wider audience and are crucial for overall organizational security awareness. In contrast, the specifics of router configuration are usually handled by specialized IT staff.

---

## Question 35
**Correct Answer:** A

**Explanation:**
The service-level agreement (SLA) is between a service provider and a customer and documents in a formal manner expectations around availability, performance, and other parameters. An MOU may cover the same items but is not as formal a document. An OLA is between internal service organizations and does not involve customers. An SOW is an addendum to a contract describing work to be performed.

---

## Question 36
**Correct Answer:** A

**Explanation:**
The ITIL framework focuses on IT service management. The Project Management Body of Knowledge (PMBOK) provides a common core of project management expertise. The Payment Card Industry Data Security Standard (PCI DSS) contains

regulations for payment card security. The Open Group Architecture Framework (TOGAF) focuses on IT architecture issues.

---

## Question 37
**Correct Answer:** D

**Explanation:**
Latency is a delay in the delivery of packets from their source to their destination. Jitter is a variation in the latency for different packets. Packet loss is the disappearance of packets in transit that requires retransmission. Interference is electrical noise or other disruptions that corrupt the contents of packets.

---

## Question 38
**Correct Answer:** B

**Explanation:**
Running the program in a sandbox provides secure isolation that can prevent the malware from impacting other applications or systems. If Joe uses appropriate instrumentation, he can observe what the program does, what changes it makes, and any communications it may attempt. ASLR is a memory location randomization technology. Process isolation keeps processes from impacting each other. A sandbox typically provides greater utility in a scenario like this since it can be instrumented and managed in a way that better supports investigations. Clipping is a term often used in signal processing.

---

## Question 39
**Correct Answer:** D

**Explanation:**
A transformer explosion is a failure of a human- made electrical component. Flooding, mudslides, and hurricanes are all examples of natural disasters.

---

## Question 40
**Correct Answer:** A

**Explanation:**
Microsoft Configuration Manager (ConfigMgr) provides this capability and is designed to allow administrators to evaluate the configuration status of Windows workstations and servers, as well as providing asset management data. System Center Operations Manager (SCOM) is primarily used to monitor for health and performance. Group Policy can be used for a variety of tasks including deploying settings and software, and custom PowerShell scripts could do this but should not be required for a configuration check.

---

## Question 41
**Correct Answer:** B

**Explanation:**
The principle of least privilege says that an individual should only have the privileges necessary to complete their job functions. Removing administrative privileges from nonadministrative users is an example of least privilege.

---

## Question 42
**Correct Answer:** D

**Explanation:**
There is no need to conduct forensic imaging as a preventative measure. Rather, forensic imaging should be used during the incident response process. Maintaining patch levels, implementing intrusion detection/prevention, and removing unnecessary services and accounts are all basic preventive measures.

---

## Question 43
**Correct Answer:** B

**Explanation:**
A resource capacity agreement is the most appropriate for Chas's concern, as it specifically addresses the availability of resources in a disaster scenario. This type of agreement ensures that the cloud provider has sufficient resources to meet the needs of their clients, even in the event of multiple simultaneous disasters. It directly tackles the issue of resource allocation and availability, which is Chas's primary concern. In contrast, a nondisclosure agreement is more about confidentiality and doesn't address resource capacity. A mutual assistance agreement typically involves agreements between organizations for support during emergencies but doesn't guarantee specific resource availability. A business partnership agreement is broader and may not specifically cover the detailed aspects of resource availability in disaster scenarios.

---

## Question 44
**Correct Answer:** C

**Explanation:**
An incident negatively affects the confidentiality, integrity, or availability of information or assets and/or violates a security policy. A computer security incident is an incident that is the result of an attack or the result of malicious or intentional actions on the part of users.

The unauthorized vulnerability scan of a server does violate security policy and may negatively affect the security of that system, so it qualifies as a security incident. The failure of a backup to complete properly jeopardizes availability and is, therefore, an incident, but not a computer security incident. The logging of system access and update of antivirus signatures are all routine actions that do not violate policy or jeopardize security, so they are all events rather than incidents.

---

## Question 45
**Correct Answer:** C

**Explanation:**
Radio Frequency Identification (RFID) technology is a cost-effective way to track items around a facility. While Wi-Fi could be used for the same purpose, it would be much more expensive to implement.

---

## Question 46
**Correct Answer:** C

**Explanation:**
An attack committed against an organization by an insider, such as an employee, is known as sabotage. Espionage and confidentiality breaches involve the theft of sensitive information, which is not alleged to have occurred in this case. Integrity breaches involve the unauthorized modification of information, which is not described in this scenario.

---

## Question 47
**Correct Answer:** A

**Explanation:**
In a SYN flood attack, the attacker sends a large number of SYN packets to a system but does not respond to the SYN/ACK packets, attempting to overwhelm the attacked system's connection state table with half-open connections.

---

## Question 48
**Correct Answer:** B

**Explanation:**
The maximum tolerable downtime (MTD) is the longest amount of time that an IT service or component may be unavailable without causing serious damage to the organization. The recovery time objective (RTO) is the amount of time expected to return an IT service or component to operation after a failure. The recovery point objective (RPO) identifies the maximum amount of data, measured in time, that may be lost during a

recovery effort. Service-level agreements (SLAs) are written contracts that document service expectations.

---

## Question 49
**Correct Answer:** C

**Explanation:**
Zero-day attacks are those that are previously unknown to the security community and, therefore, have no available patch. These are especially dangerous attacks because they may be highly effective until a solution becomes available. The other attacks described here are all known attacks and would not be classified as zero-day events.

---

## Question 50
**Correct Answer:** D

**Explanation:**
Locard's principle is most relevant to Rob's forensic investigation for trace digital evidence, as it suggests that any contact between two objects results in an exchange of materials. In the context of digital forensics, this principle implies that there is always some form of digital trace or residue left behind when devices interact or when data is transferred. Kerckhoff's principle states that a system's security should not depend on the secrecy of its algorithm but rather on the secrecy of its keys. The principle of least privilege is a security concept in which a user is given the minimum levels of access—or permissions—needed to perform his job functions. Lastly, the defense-in- depth principle is a layered security approach that establishes multiple levels of defense to protect information. While these other three principles are important in cybersecurity, they do not directly relate to the collection and analysis of digital trace evidence like Locard's principle does.

---

## Question 51
**Correct Answer:** A

**Explanation:**
Interviews occur when investigators meet with an individual who may have information relevant to their investigation but is not a suspect. If the individual is a suspect, then the meeting is an interrogation.

---

## Question 52
**Correct Answer:** D

**Explanation:**
The image clearly contains the watermark of the U.S. Geological Survey (USGS), which ensures that anyone seeing the image knows its origin. It is not possible to tell from looking at the image whether steganography was used. Sampling and clipping are data analysis techniques and are not used to protect images.

---

## Question 53
**Correct Answer:** D

**Explanation:**
The annualized rate of occurrence (ARO) is the expected number of times an incident will occur each year. In the case of a 200-year flood plain, planners should expect a flood once every 200 years. This is equivalent to a 1/200 chance of a flood in any given year, or 0.005 floods per year.

---

## Question 54
**Correct Answer:** B

**Explanation:**
While all hackers with malicious intent pose a risk to the organization, the malicious insider poses the greatest risk to security because they likely have legitimate access to sensitive systems that may be used as a launching point for an attack. Other attackers do not begin with this advantage.

---

## Question 55
**Correct Answer:** C

**Explanation:**
In an electronic vaulting approach, automated technology moves database backups from the primary database server to a remote site on a scheduled basis, typically daily. Transaction logging is not a recovery technique alone; it is a process for generating the logs used in remote journaling. Remote journaling transfers transaction logs to a remote site on a more frequent basis than electronic vaulting, typically hourly. Remote mirroring maintains a live database server at the backup site and mirrors all transactions at the primary site on the server at the backup site.

---

## Question 56
**Correct Answer:** B

**Explanation:**
Hilda's design follows the principle of segregation of duties. Giving one user the ability to both create new accounts and grant administrative privileges combines

two actions that would result in a significant security change that should be divided among two users.

---

## Question 57
**Correct Answer:** C

**Explanation:**
While all of these assumptions are valid premises that Patrick might have going into the exercise, the basic assumption of a threat-hunting exercise is the so- called presumption of compromise. This means that Patrick should assume that attackers have already gained access to his system and then hunt for indicators of their presence.

---

## Question 58
**Correct Answer:** C

**Explanation:**
The end goal of the disaster recovery process is restoring normal business operations in the primary facility. All of the other actions listed may take place during the disaster recovery process, but the process is not complete until the organization is once again functioning normally in its primary facilities.

---

## Question 59
**Correct Answer:** C

**Explanation:**
A host-based intrusion detection system (HIDS) may be able to detect unauthorized processes running on a system. The other controls mentioned, network intrusion detection systems (NIDSs), firewalls, and DLP systems, are network-based and may not notice rogue processes.

---

## Question 60
**Correct Answer:** B

**Explanation:**
The scenario describes a privilege escalation attack where a malicious insider with authorized access to a system misused that access to gain privileged credentials.

---

## Question 61
**Correct Answer:** B

**Explanation:**
Carla's account has experienced privilege creep, where privileges accumulated over time. This condition is also known as aggregation and likely constitutes a violation of the least privilege principle.

---

## Question 62
**Correct Answer:** C

**Explanation:**
The mitigation phase of incident response focuses on actions that can contain the damage incurred during an incident. This includes limiting the scope and/or effectiveness of the incident. The detection phase

identifies that an incident is taking place. The response phase includes steps taken to assemble a team and triage the incident. At the conclusion of the recovery phase, normal operations are resumed.

---

## Question 63
**Correct Answer:** C

**Explanation:**
At this point in the process, Ann has no reason to believe that any actual security compromise or policy violation took place, so this situation does not meet the criteria for a security incident or intrusion. Rather, the alert generated by the intrusion detection system is simply a security event requiring further investigation. Security occurrence is not a term commonly used in incident handling.

---

## Question 64
**Correct Answer:** A

**Explanation:**
DNS traffic commonly uses port 53 for both TCP and UDP communications. SSH and SCP use TCP port 22. SSL and TLS do not have ports assigned to them but are commonly used for HTTPS traffic on port 443. Unencrypted web traffic over HTTP often uses port 80.

---

## Question 65
**Correct Answer:** D

**Explanation:**
The attack described in this scenario has all the hallmarks of a denial-of-service attack. More specifically, Ann's organization is likely experiencing a DNS amplification attack where an attacker sends false requests to third-party DNS servers with a forged source IP address belonging to the targeted system. Because the attack uses UDP requests, there is no three-way handshake. The attack packets are carefully crafted to elicit a lengthy response from a short query. The purpose of these queries is to generate responses headed to the target system that are sufficiently large and numerous enough to overwhelm the targeted network or system.

---

## Question 66
**Correct Answer:** B

**Explanation:**
Now that Ann suspects an attack against her organization, she has sufficient evidence to declare a security incident. The attack underway seems to have undermined the availability of her network, meeting

one of the criteria for a security incident. This is an escalation beyond a security event but does not reach the level of an intrusion because there is no evidence that the attacker has even attempted to gain access to systems on Ann's network. Security occurrence is not a term commonly used in incident handling.

---

## Question 67
**Correct Answer:** D

**Explanation:**
To be admissible, evidence must be relevant, material, and competent. The laptop in this case is clearly material because it contains logs related to the crime in question. It is also relevant because it provides evidence that ties the hacker to the crime. It is not competent because the evidence was not legally obtained.

---

## Question 68
**Correct Answer:** C

**Explanation:**
Gordon may conduct his investigation as he wants and use any information that is legally available to him, including information and systems belonging to his employer. There is no obligation to contact law enforcement. However, Gordon may not perform “hack back” activities because those may constitute violations of the law and/or ISC2 Code of Ethics.

---

## Question 69
**Correct Answer:** B

**Explanation:**
Software escrow agreements place a copy of the source code for a software package in the hands of an independent third party who will turn the code over to the customer if the vendor ceases business operations. Service-level agreements, mutual assistance agreements, and compliance agreements all lose some or all of their effectiveness if the vendor goes out of business.

---

## Question 70
**Correct Answer:** C

**Explanation:**
Most security professionals recommend at least one, and preferably two, weeks of vacation to deter fraud. The idea is that fraudulent schemes will be uncovered during the time that the employee is away and does not have the access required to perpetuate a cover-up.

---

## Question 71
**Correct Answer:** See Explanation

**Explanation:**
A, B, C, E, F.  Any attempt to undermine the security of an organization or violation of a security policy is a security incident. All of the events described meet this definition and should be treated as an incident, with one exception. A successful attempt to access a file is certainly a security event, but it is not a security incident unless it is established that the individual accessing the file was not authorized to do so.

---

## Question 72
**Correct Answer:** A, B, C

**Explanation:**
Egress filtering scans outbound traffic for potential security policy violations. This includes traffic that is likely malicious, such as an outbound SSH scan on port 22. It also includes traffic that appears to be part of an attack or misconfiguration, such as sending traffic to a broadcast destination address. Finally, it includes spoofed traffic generated by internal systems, which may bear a source address from an external network. The normal traffic that the firewall should expect to see is that bearing a destination address on an external network.

---

## Question 73
**Correct Answer:** C

**Explanation:**
The two main methods of choosing records from a large pool for further analysis are sampling and clipping. Sampling uses statistical techniques to choose a sample that is representative of the entire pool, while clipping uses threshold values to select those records that exceed a predefined threshold because they may be of most interest to analysts. In this case, Allie is only selecting records that exceed an invalid login threshold, making this an example of clipping. She is not using statistical techniques to select a subset of records, so this is not an example of sampling.

---

## Question 74
**Correct Answer:** B

**Explanation:**
NetFlow data contains information on the source, destination, and size of all network communications and is routinely saved as a matter of normal activity. Packet capture data would provide relevant

information, but it must be captured during the suspicious activity and cannot be re-created after the fact unless the organization is already conducting 100% packet capture, which is rare. Additionally, the use of encryption limits the effectiveness of packet capture. Intrusion detection system logs would not likely contain relevant information because the encrypted traffic would probably not match intrusion signatures. Centralized authentication records would not contain information about network traffic.

---

## Question 75
**Correct Answer:** C

**Explanation:**
Baseline configurations serve as the starting point for configuring secure systems and applications. They contain the security settings necessary to comply with an organization's security policy and may then be customized to meet the specific needs of an implementation. While security policies and guidelines may contain information needed to secure a system, they do not contain a set of configuration settings that may be applied to a system. The running configuration of a system is the set of currently applied settings, which may or may not be secure.

---

## Question 76
**Correct Answer:** B

**Explanation:**
During a parallel test, the team actually activates the disaster recovery site for testing, but the primary site remains operational. During a full interruption test, the team takes down the primary site and confirms that the disaster recovery site is capable of handling regular operations. The full interruption test is the most thorough test but also the most disruptive. The read- through is the least disruptive type of disaster recovery test. During a read-through, team members each review the contents of their disaster recovery checklists on their own and suggest any necessary changes. During a tabletop exercise, team members come together and work through a specific scenario without making any changes to information systems.

---

## Question 77
**Correct Answer:** C

**Explanation:**
Both the receipt of alerts and the verification of their accuracy occur during the Detection phase of the incident response process.

---

## Question 78
**Correct Answer:** C

**Explanation:**
According to NIST SP 800-137, organizations should use the following factors to determine assessment and monitoring frequency: security control volatility, system categorizations/impact levels, security controls or specific assessment objects providing critical functions, security controls with identified weaknesses, organizational risk tolerance, threat information, vulnerability information, risk assessment results, the output of monitoring strategy reviews, and reporting requirements.

---

## Question 79
**Correct Answer:** D

**Explanation:**
All of these technologies have the potential to monitor user behavior on endpoint devices. The key to answering this question correctly is realizing the emphasis on the user. Intrusion detection and prevention systems (IDSs/IPSs) focus on network and host behavior. Endpoint detection and response (EDR) systems focus on endpoint devices. User and entity behavior analytics (UEBA) solutions focus on the user and, therefore, would be the best way to meet Hunter's requirement.

---

## Question 80
**Correct Answer:** C

**Explanation:**
SSH uses TCP port 22, so this attack is likely an attempt to scan for open or weakly secured SSH servers. FTP uses ports 20 and 21. Telnet uses port 23, and HTTP uses port 80.

---

## Question 81
**Correct Answer:** B

**Explanation:**
Remediation activities seek to address the issue that caused the incident. In this case, that was a web application that was open to SQL injection attack. Adding input validation seeks to remediate this vulnerability. Rebuilding the database is a recovery action, while reviewing logs is done as part of the detection and response effort.

---

## Question 82
**Correct Answer:** C

**Explanation:**
In an infrastructure-as-a-service environment, the vendor is responsible for hardware- and network- related responsibilities. These include configuring network firewalls, maintaining the hypervisor, and managing physical equipment. The customer retains responsibility for patching operating systems on its virtual machine instances.

---

## Question 83
**Correct Answer:** B

**Explanation:**
Sandboxing is a technique where application developers (or the recipients of an untrusted application) may test the code in a virtualized environment that is isolated from production systems. White-box testing, black-box testing, and penetration testing are all common software testing techniques but do not require the use of an isolated system.

---

## Question 84
**Correct Answer:** C

**Explanation:**
While it may not immediately seem like the obvious answer, many firewalls have a built-in anti–SYN flood defense that responds to SYNs on behalf of protected systems. Once the remote system proves to be a legitimate connection by continuing the three-way handshake, the rest of the TCP session is passed through. If the connection proves to be an attack, the firewall handles the additional load using appropriate mitigation techniques. Blocking SYNs from known or unknown IP addresses is likely to cause issues with systems that should be able to connect, and turning off TCP will break most modern network services!

---

## Question 85
**Correct Answer:** A, B, D

**Explanation:**
EDR platforms do not conduct simulated phishing campaigns. The most common features of EDR systems are analyzing endpoint memory, filesystem, and network activity for signs of malicious activity; isolating possible malicious activity to contain the potential damage; integrating with threat intelligence sources; and integrating with other incident response mechanisms.

---

## Question 86
**Correct Answer:** A

**Explanation:**
While any cybersecurity activity has the potential to benefit from machine learning and artificial intelligence capabilities, this technology really shines when used for pattern detection and anomaly detection problems. This is the type of activity performed by an intrusion detection system, and, therefore, this system would benefit the most from the use of ML/AI technology.

---

## Question 87
**Correct Answer:** A

**Explanation:**
Companies have an obligation to preserve evidence whenever they believe that the threat of litigation is imminent. The statement made by this customer that “we will have to take this matter to court” is a clear threat of litigation and should trigger the preservation of any related documents and records.

---

## Question 88
**Correct Answer:** A

**Explanation:**
Incremental backups provide the option that includes the smallest amount of data. In this case, that would be only the data modified since the most recent incremental backup. A differential backup would back up all data modified since the last full backup, which would be a substantial amount. The full backup would include all information on the server. Transaction log backups are specifically designed to support database servers and would not be effective on a file server.

---

## Question 89
**Correct Answer:** A

**Explanation:**
Expert opinion evidence allows individuals to offer their opinion based upon the facts in evidence and their personal knowledge. Expert opinion evidence may be offered only if the court accepts the witness as an expert in a particular field. Direct evidence is when witnesses testify about their direct observations. Real evidence consists of tangible items brought into court as evidence. Documentary evidence consists of written records used as evidence in court.

---

## Question 90
**Correct Answer:** D

**Explanation:**
The standard methods for clearing magnetic tapes, according to the NIST Guidelines for Media Sanitization, are overwriting the tape with nonsensitive

data, degaussing, and physical destruction via shredding. Reformatting a tape does not remove remnant data.

---

## Question 91
**Correct Answer:** B

**Explanation:**
RAID level 1, also known as disk mirroring, uses a minimum of two disks that contain identical information. If one disk fails, the other contains the data needed for the system to continue operation.

---

## Question 92
**Correct Answer:** B

**Explanation:**
The analysis of application logs is one of the core tasks of software analysis. This is the correct answer because SQL injection attacks are application attacks.

---

## Question 93
**Correct Answer:** C

**Explanation:**
Quigley may choose to use any or all of these security controls, but data encryption is, by far, the most important control. It protects the confidentiality of data stored on the tapes, which are most vulnerable to theft while in transit between two secure locations.

---

## Question 94
**Correct Answer:** C

**Explanation:**
Data loss prevention (DLP) systems may identify sensitive information stored on endpoint systems or in transit over a network. This is their primary purpose. DLP systems are commonly available as a third-party managed service offering. Intrusion detection and prevention systems (IDSs/IPSs) may be used to identify some sensitive information using signatures built for that purpose, but this is not the primary role of those tools, and they would not be as effective as DLP systems at this task. TLS is a network encryption protocol that may be used to protect sensitive information, but it does not have any ability to identify sensitive information.

---

## Question 95
**Correct Answer:** C

**Explanation:**
Disaster recovery teams should always refer media inquiries to the public relations team to ensure a coordinated, consistent response. They should not attempt to answer questions themselves.

---

## Question 96
**Correct Answer:** D

**Explanation:**
All of these considerations are important when developing an emergency management plan. However, the safety of human life should always be the overwhelming priority, above all other considerations.

---

## Question 97
**Correct Answer:** D

**Explanation:**
Barry should recruit an independent moderator to facilitate the session. Having a moderator who was not directly involved in the effort encourages honest and open feedback. While it is not necessary to use an external consultant, they may easily fill this role. While it is also possible to find a qualified internal employee to fill this position, it should not be someone who was involved in the incident response effort or has a major stake in the plan, such as Barry, the CISO, or the DR team leader.

---

## Question 98
**Correct Answer:** C

**Explanation:**
Generators are capable of providing backup power for a sustained period of time in the event of a power loss, but they take time to activate. Uninterruptible power supplies (UPSs) provide immediate, battery- driven power for a short period of time to cover momentary losses of power, which would not cover a sustained period of power loss. RAID and redundant servers are high-availability controls but do not cover power loss scenarios.

---

## Question 99
**Correct Answer:** See Explanation

**Explanation:**
The terms match with the definitions as follows: 1. Honeypot: C. A system set up with intentional vulnerabilities 2. Honeynet: B. A network set up with intentional vulnerabilities 3. Pseudo-flaw: A. An intentionally designed vulnerability used to lure in an attacker 4. Darknet: D. A monitored network without any hosts

---

## Question 100
**Correct Answer:** See Explanation

**Explanation:**
The terms match with the definitions as follows:

1. Hot site: B. A site with dedicated storage and real- time data replication, often with shared equipment that allows restoration of service in a very short time 2. Cold site: D. A rented space with power, cooling, and connectivity that can accept equipment as part of a recovery effort 3. Warm site: C. A site that relies on shared storage and backups for recovery 4. Service bureau: A. An organization that can provide on-site or off-site IT services in the event of a disaster

---

