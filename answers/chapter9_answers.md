# CISSP Practice Tests - Chapter 9: Practice Test 1 Answer Key

## Question 1
**Correct Answer:** A, B, D

**Explanation:**
Packets with public IP addresses will routinely be allowed to enter the network, so you should not create a rule to block them. Packets with internal source addresses should never originate from outside the network, so they should be blocked from entering the network. Packets with external source addresses should never be found on the internal network, so they should be blocked from leaving the network. Finally, private IP addresses should never be used on the Internet, so packets containing private IP addresses should be blocked from leaving the network.

---

## Question 2
**Correct Answer:** B

**Explanation:**
A content distribution network (CDN) is designed to provide reliable, low-latency, geographically distributed content distribution. In this scenario, a CDN is an ideal solution. A P2P CDN like BitTorrent isn't a typical choice for a commercial entity, whereas redundant servers or a hot site can provide high availability but won't provide the remaining requirements.

---

## Question 3
**Correct Answer:** A, B, C

**Explanation:**
A forensic disk controller performs four functions. One of those, write blocking, intercepts write commands sent to the device and prevents them from modifying data on the device. The other three functions include returning data requested by a read operation, returning access-significant information from the device, and reporting errors from the device back to the forensic host. The controller should not prevent read commands from being sent to the device because those commands may return crucial information.

---

## Question 4
**Correct Answer:** B

**Explanation:**
RAID 1, disk mirroring, requires two physical disks that will contain copies of the same data.

---

## Question 5
**Correct Answer:** D

**Explanation:**
The TGS, or ticket-granting service (which is usually on the same server as the KDC), receives a TGT from

the client. It validates the TGT and the user's rights to access the service they are requesting to use. The TGS then issues a ticket and session keys to the client. The AS serves as the authentication server, which forwards the username to the KDC. It's worth noting that the client doesn't communicate with the KDC directly. Instead, it will communicate with the TGT and the AS, which means KDC isn't an appropriate answer here.

---

## Question 6
**Correct Answer:** C

**Explanation:**
This is an example of a civil investigation because it relates to a contract dispute and will likely wind up being litigated in civil court. Administrative investigations are for internal purposes and are not applicable when a third party is being investigated. Criminal and regulatory investigations may only be initiated by those with regulatory authority, typically government agencies.

---

## Question 7
**Correct Answer:** C

**Explanation:**
Wave pattern motion detectors transmit ultrasonic or microwave signals into the monitored area, watching for changes in the returned signals bouncing off objects. Infrared heat-based detectors watch for unusual heat patterns. Capacitance detectors work based upon electromagnetic fields.

---

## Question 8
**Correct Answer:** C

**Explanation:**
Stateful packet inspection firewalls, also known as dynamic packet filtering firewalls, track the state of a conversation and can allow a response from a remote system based on an internal system being allowed to start the communication. Static packet filtering and circuit-level gateways only filter based on source and destination IP addresses and ports along with the protocol being used, whereas application-level gateway firewalls proxy traffic for specific applications.

---

## Question 9
**Correct Answer:** B

**Explanation:**
A captive portal can require those who want to connect to and use Wi-Fi to provide an email address to connect. This allows Ben to provide easy-to-use

wireless while meeting his business purposes. WPA2- PSK is the preshared key mode of WPA and won't provide information about users who are given a key. WPA3's SAE mode would be preferable to WPA2-PSK, but it still does not allow for the data gathering Ben desires. Sharing a password doesn't allow for data gathering either.

---

## Question 10
**Correct Answer:** B

**Explanation:**
Many modern wireless routers can provide multiple SSIDs. Ben can create a private, secure network for his business operations, but he will need to make sure that the customer and business networks are firewalled or otherwise logically separated from each other. Running WPA3 on the same SSID isn't possible without creating another wireless network and would cause confusion for customers (SSIDs aren't required to be unique). Running a network in Enterprise mode isn't used for open networks, and WEP is outdated and incredibly vulnerable.

---

## Question 11
**Correct Answer:** D

**Explanation:**
Unencrypted open networks broadcast traffic in the clear. This means that unencrypted sessions to websites can be easily captured with a packet sniffer. Some tools like FireSheep have been specifically designed to capture sessions from popular websites. Fortunately, many websites now use TLS by default, but other sites still send user session information in the clear. Shared passwords are not the cause of the vulnerability, ARP spoofing isn't an issue with wireless networks, and a Trojan is designed to look like safe software, not to compromise a router.

---

## Question 12
**Correct Answer:** C

**Explanation:**
It is possible that Kevin could use any one of these documents. We should zero in on the portion of the question where it indicates that these are best practices. This implies that the advice is not mandatory and, therefore, would not go into a policy or standard.

The fact that the advice is general in nature means that it is likely not well-suited to the step-by-step nature of a procedure. A guideline would be the perfect place to document these best practices.

---

## Question 13
**Correct Answer:** D

**Explanation:**
Clipping is an analysis technique that reports alerts only after they exceed a set threshold. It is a specific form of sampling, which is a more general term that describes any attempt to excerpt records for review. Thresholding is not a commonly used term. Administrators may choose to configure automatic or manual account lockout after failed login attempts, but that is not described in the scenario.

---

## Question 14
**Correct Answer:** B

**Explanation:**
RADIUS is a common AAA technology used to provide services for dial-up, wireless networks, network devices, and a range of other systems. OAuth is an authorization protocol used to allow applications to act on a user's behalf without sharing the password and is used for many web applications. OpenID Connect is an authentication layer on top of OAuth that allows clients to verify the identity of an end user. XTACACS, an earlier protocol for network authentication, has largely been superseded by more secure and robust protocols like RADIUS, and its proprietary nature does not fit Sally's criteria.

---

## Question 15
**Correct Answer:** C

**Explanation:**
In an inference attack, the attacker uses several pieces of generic nonsensitive information to determine a specific sensitive value. In a salami slicing attack, the attacker siphons off minute quantities of money many times to accumulate a large amount of funds. In a data diddling attack, the attacker alters the contents of a database. Social engineering attacks exploit human psychology to achieve their goals.

---

## Question 16
**Correct Answer:** A

**Explanation:**
The Take rule in the Take-Grant protection model allows a subject to take rights from another object if

the subject has the take right over that object. In this scenario, if Alice has the take right over Bob and Bob has read permissions on an object, Alice can use the Take rule to grant herself the read permissions that Bob possesses. The Grant rule is for granting rights to other subjects, not for taking them for oneself. The Create rule is used to create new objects or rights, not to transfer existing ones. There is no Remote rule in the Take-Grant protection model.

---

## Question 17
**Correct Answer:** B

**Explanation:**
Brute-force attacks try every possible password. In this attack, the password is changing by one letter at each attempt, which indicates that it is a brute-force attack. A dictionary attack would use dictionary words for the attack, whereas a man-in-the-middle or pass- the-hash attack would most likely not be visible in an authentication log except as a successful login.

---

## Question 18
**Correct Answer:** B

**Explanation:**
Isolation requires that transactions operate separately from each other. Atomicity ensures that if any part of a database transaction fails, the entire transaction must be rolled back as if it never occurred. Consistency ensures that all transactions are consistent with the logical rules of the database, such as having a primary key. Durability requires that once a transaction is committed to the database it must be preserved. Together, these properties make up the ACID model.

---

## Question 19
**Correct Answer:** B

**Explanation:**
Worms have built-in propagation mechanisms that do not require user interaction, such as scanning for systems containing known vulnerabilities and then exploiting those vulnerabilities to gain access. Viruses and Trojan horses typically require user interaction to spread. Logic bombs do not spread from system to system but lie in wait until certain conditions are met, triggering the delivery of their payload.

---

## Question 20
**Correct Answer:** B, C

**Explanation:**
The Health Insurance Portability and Accountability Act (HIPAA) is a U.S. law governing the healthcare sector that does provide for criminal penalties. The Sarbanes–Oxley (SOX) Act governs publicly traded corporations and also provides for criminal penalties. The Family Educational Rights and Privacy Act (FERPA) is a U.S. law governing educational records, but it does not provide for criminal penalties. PCI DSS, the Payment Card Industry Data Security Standard, is an industry standard for payment card operations and handling. Because it is not a law, PCI DSS violations cannot incur criminal sanctions.

---

## Question 21
**Correct Answer:** C

**Explanation:**
The TCP three-way handshake consists of an initial contact via a SYN, or synchronize flagged packet, which receives a response with a SYN/ACK, or synchronize and acknowledge flagged packet, which is acknowledged by the original sender with an ACK, or acknowledge packet. RST is used in TCP to reset a connection, PSH is used to send data immediately, and FIN is used to end a connection.

---

## Question 22
**Correct Answer:** A, C, D

**Explanation:**
MDM products do not have the capability of assuming control of a device not currently managed by the organization. This would be equivalent to hacking into a device owned by someone else and might constitute a crime. They do normally provide the ability to manage device backups, enforce the use of encryption, and remotely wipe the contents of mobile devices.

---

## Question 23
**Correct Answer:** A

**Explanation:**
Identity as a service (IDaaS) provides an identity platform as a third-party service. This can provide benefits, including integration with cloud services and removing overhead for maintenance of traditional on- premises identity systems but can also create risk due

to third-party control of identity services and reliance on an off-site identity infrastructure.

---

## Question 24
**Correct Answer:** A

**Explanation:**
Gina's actions harm the CISSP certification and information security community by undermining the integrity of the examination process. While Gina also is acting dishonestly, the harm to the profession is more of a direct violation of the ISC2 Code of Ethics.

---

## Question 25
**Correct Answer:** A

**Explanation:**
The annualized loss expectancy (ALE) is the amount of damage that the organization expects to occur each year as the result of a given risk. ALE is calculated by multiplying the single loss expectancy (SLE), which is the expected financial loss from a single flooding event, by the annual rate of occurrence (ARO), which is the expected frequency of flooding events per year. The ALE helps organizations to understand the potential impact of risks and to make informed decisions about risk mitigation strategies and investments in protective measures. The exposure factor (EF) is the percentage of the asset expected to be damaged during an incident.

---

## Question 26
**Correct Answer:** C

**Explanation:**
The whitelisting approach to application control allows users to install only those software packages specifically approved by administrators. This would be an appropriate approach in a scenario where application installation needs to be tightly controlled. Blacklisting, which blocks known malicious or unauthorized applications, would not be as effective in this scenario because it allows all software to run unless it appears on the blacklist. Graylisting and bluelisting are made-up terms.

---

## Question 27
**Correct Answer:** A

**Explanation:**
This is a clear example of a denial-of-service attack —denying legitimate users authorized access to the system through the use of overwhelming traffic. It goes beyond a reconnaissance attack because the attacker is

affecting the system, but it is not a compromise because the attacker did not attempt to gain access to the system. There is no reason to believe that a malicious insider was involved.

---

## Question 28
**Correct Answer:** A

**Explanation:**
The Company ID column is likely unique for each row in the table, making it the best choice for a primary key. There may be multiple companies that share the same name or ZIP code. Similarly, a single sales representative likely serves more than one company, making those fields unsuitable for use as a unique identifier.

---

## Question 29
**Correct Answer:** C

**Explanation:**
Personally identifiable information (PII) includes data that can be used to distinguish or trace that person's identity and also includes their educational, financial, and employment information. PHI is personal health information, EDI is electronic data interchange, and proprietary data is used to maintain an organization's competitive advantage.

---

## Question 30
**Correct Answer:** D

**Explanation:**
129.53.44.124 is a valid public IP address and a legitimate destination for traffic leaving Bob's network. 12.8.195.15 is a public address on Bob's network and should not be a destination address on a packet leaving the network. 10.8.15.9 and 192.168.109.55 are both private IP addresses that should not be routed to the Internet.

---

## Question 31
**Correct Answer:** D

**Explanation:**
Binary keyspaces contain a number of keys equal to 2 raised to the power of the number of bits. Two to the eighth power is 256, so the keyspace will increase by a factor of 256.

---

## Question 32
**Correct Answer:** A, B, C, D

**Explanation:**
Traditional office shredding machines may be used for the disposal of paper records and, depending upon their grade, may also be able to shred credit cards. Industrial shredders are capable of

destroying larger pieces of equipment, including removable media and both traditional and SSD hard drives.

---

## Question 33
**Correct Answer:** A

**Explanation:**
Encrypting the files reduces the probability that the data will be successfully stolen, so it is an example of risk mitigation. Deleting the files would be risk avoidance. Purchasing insurance would be risk transference. Taking no action would be risk acceptance.

---

## Question 34
**Correct Answer:** C

**Explanation:**
Sampling should be done randomly to avoid human bias. Sampling is an effective process if it is done on a truly random sample of sufficient size to provide effective coverage of the userbase. It is infeasible for a single person to review every single record. In an organization of 50,000 users with a 24% annual turnover, it is likely that at least 1,000 of those records have changed in the last month. This is still too many records to review. Asking account administrators to select the records to review is a conflict of interest, as they are the group being audited.

---

## Question 35
**Correct Answer:** A

**Explanation:**
In the case of an involuntary termination under adverse circumstances, the user is being fired and may have a negative and potentially hostile reaction. For this reason, it is important to terminate access immediately upon the user being informed of the termination. Terminating access prior to notification may tip the user off to the termination in advance. Leaving access privileges available after termination poses a risk of malicious insider activity.

---

## Question 36
**Correct Answer:** C

**Explanation:**
The file clearly shows HTTP requests, as evidenced by the many GET commands. Therefore, this is an example of an application log from an HTTP server.

---

## Question 37
**Correct Answer:** A

**Explanation:**
The Common Vulnerability Scoring System (CVSS) is a standardized approach to rating the severity of vulnerabilities and would be the most helpful tool for Roger's work. The STRIDE and ATT&CK models are used to classify the nature, not the severity, of threats. The PASTA model is designed to help with countermeasure selection.

---

## Question 38
**Correct Answer:** B

**Explanation:**
Social engineering exploits humans to allow attacks to succeed. Since help-desk employees are specifically tasked with being helpful, they may be targeted by attackers posing as legitimate employees. Trojans are a type of malware, whereas phishing is a targeted attack via electronic communication methods intended to capture passwords or other sensitive data. Whaling is a type of phishing aimed at high-profile or important targets.

---

## Question 39
**Correct Answer:** B

**Explanation:**
If the vendor operates with reasonable security procedures, it is unlikely that the devices will be tampered with at the vendor's site. Similarly, if Greg's organization has reasonable security procedures, tampering at his site is also unlikely. Misconfiguration by an administrator is always possible, but this is a post-installation risk and not a supply chain risk. It is possible that devices will be intercepted and tampered with while in transit from the vendor to Greg's organization.

---

## Question 40
**Correct Answer:** C

**Explanation:**
In a single-level security environment, systems should be assigned the classification level of the highest classification of information they are ever expected to process. Systems may not process information that is above their classification level without reclassifying the system upward.

---

## Question 41
**Correct Answer:** C

**Explanation:**
A hybrid authentication service can provide authentication services both in the cloud and on-

premises, ensuring that service outages due to interrupted links are minimized. An on-site service would continue to work during an Internet outage but would not allow the e-commerce website to authenticate. A cloud service would leave the corporate location offline. Outsourcing authentication does not indicate whether the solution is on- or off-premises and thus isn't a useful answer.

---

## Question 42
**Correct Answer:** C

**Explanation:**
Federation links identity information between multiple organizations. Federating with a business partner can allow identification and authorization to occur between them, making integration much easier. Single sign-on would reduce the number of times a user has to log in but will not facilitate the sharing of identity information. Multifactor authentication can help secure authentication but again doesn't help integrate with a third party. Finally, an identity as a service provider might provide federation but doesn't guarantee it.

---

## Question 43
**Correct Answer:** B

**Explanation:**
Security Assertion Markup Language (SAML) is frequently used to integrate cloud services and provides the ability to make authentication and authorization assertions. Active Directory integrations are possible but are less common for cloud service providers, and RADIUS is not typically used for integrations like this. Service Provisioning Markup Language (SPML) is used to provision users, resources, and services, not for authentication and authorization.

---

## Question 44
**Correct Answer:** B

**Explanation:**
Rainbow tables use precomputed password hashes to conduct cracking attacks against password files. They may be frustrated by the use of salting, which adds a specified value to the password prior to hashing, making it much more difficult to perform precomputation. Password expiration policies,

password complexity policies, and user education may all contribute to password security, but they are not direct defenses against the use of rainbow tables.

---

## Question 45
**Correct Answer:** C

**Explanation:**
A honeypot is a decoy computer system used to bait intruders into attacking. A honeynet is a network of multiple honeypots that creates a more sophisticated environment for intruders to explore. A pseudoflaw is a false vulnerability in a system that may attract an attacker. A darknet is a segment of unused network address space that should have no network activity and, therefore, may be easily used to monitor for illicit activity.

---

## Question 46
**Correct Answer:** C

**Explanation:**
The false acceptance rate (FAR) is the rate at which the system inadvertently admits an unauthorized user, while the false rejection rate (FRR) is the rate at which the system inadvertently rejects an authorized user. Both the FAR and FRR may be modified by adjusting the sensitivity of the system. The crossover error rate (CER) is the point where both the false acceptance rate and the false rejection rate cross. The CER is less subject to manipulation and is, therefore, the best metric to use for evaluating systems. The FDR is not a metric used to evaluate authentication systems.

---

## Question 47
**Correct Answer:** C

**Explanation:**
Steganography is the art of using cryptographic techniques to embed secret messages within other content. Steganographic algorithms work by making invisible alterations to files, such as modifying the least significant bits of the many bits that make up image files. VPNs may be used to obscure secret communications, but they provide protection in transit and can't be used to embed information in an image. Watermarking does embed information in an image but with the intent of protecting intellectual property. A

still image would not be used for a covert timing channel because it is a fixed file.

---

## Question 48
**Correct Answer:** A

**Explanation:**
JavaScript is an interpreted language so the code is not compiled prior to execution, allowing Roger to inspect the contents of the code. C, C++, and Java are all compiled languages—a compiler produces an executable file that is not human-readable.

---

## Question 49
**Correct Answer:** D

**Explanation:**
When a system is configured to use shadowed passwords, the /etc/passwd file contains only the character x in the place of a password. It would not contain any passwords, in either plaintext, encrypted, or hashed form.

---

## Question 50
**Correct Answer:** C

**Explanation:**
The end-of-life (EOL) date for a product is normally the date that the vendor will stop selling a product. It is reasonable to continue using the product as long as support remains available. Rob should begin making plans to discontinue use of the product, pending the announcement of an end-of-support (EOS) date.

---

## Question 51
**Correct Answer:** D

**Explanation:**
The due care principle states that an individual should react in a situation using the same level of care that would be expected from any reasonable person. It is a very broad standard. The due diligence principle is a more specific component of due care that states that an individual assigned a responsibility should exercise due care to complete it accurately and in a timely manner. Least privilege says that an individual should have the minimum set of permissions necessary to carry out their work. Separation of duties says that no single person should have the right to perform two distinct tasks, which, when combined, constitute a highly privileged action.

---

## Question 52
**Correct Answer:** A

**Explanation:**
Information should be classified based upon its sensitivity. This may be due to the value of the

information to the organization, the damage caused if lost or compromised, or other factors. The source of the information is one possible contributing factor to the sensitivity level. The likelihood of loss or theft is a component of risk but does not contribute to the classification level.

---

## Question 53
**Correct Answer:** A

**Explanation:**
All of these controls are good practices for protecting sensitive information. However, Perry is most concerned about the risk of interception while in transit over the Internet. Transport encryption would, therefore, be the most appropriate control, as anyone intercepting the information would be unable to read its contents. Storage encryption would protect against the theft of information at rest, rather than in transit over a network. Classification and labeling would not protect against interception. Data loss prevention technology may block the transfer entirely and would not meet the business requirement if it blocked the transmission and would not meet the security requirement if it did not detect the data transfer.

---

## Question 54
**Correct Answer:** B, D

**Explanation:**
Tangible asset inventories include physical items owned by the organization. This would include server hardware and mobile devices. Intellectual property and files stored on a server are not tangible property and would instead be included in an intangible asset inventory.

---

## Question 55
**Correct Answer:** D

**Explanation:**
The Physical layer deals with the electrical impulses or optical pulses that are sent as bits to convey data. This is the layer where cable tapping would occur. Attacks at the Data Link, Network, or Transport layers would involve higher levels of activity in the OSI model, such as compromising a device and using a protocol analyzer to sniff network traffic.

---

## Question 56
**Correct Answer:** A

**Explanation:**
In an IaaS server environment, the customer retains responsibility for most server security operations under the shared responsibility model. This includes managing OS security settings, maintaining host firewalls, and configuring server access control. The vendor would be responsible for all security mechanisms at the hypervisor layer and below.

---

## Question 57
**Correct Answer:** B

**Explanation:**
Proactive monitoring, aka synthetic monitoring, uses recorded or generated traffic to test systems and software. Passive monitoring uses a network span, tap, or other device to capture traffic to be analyzed. Reactive and replay are not industry terms for types of monitoring.

---

## Question 58
**Correct Answer:** A

**Explanation:**
Kailey should consult her organization's record retentions policy to determine the appropriate length of time to preserve the records. The organization may be subject to tax requirements in this regard, and many accountants recommend preserving records for at least seven years, but the organization's own requirements may be stricter than these requirements.

---

## Question 59
**Correct Answer:** B

**Explanation:**
The use of an electromagnetic coil inside the card indicates that this is a proximity card.

---

## Question 60
**Correct Answer:** C

**Explanation:**
During a parallel test, the team actually activates the disaster recovery site for testing, but the primary site remains operational. During a full interruption test, the team takes down the primary site and confirms that the disaster recovery site is capable of handling regular operations. The full interruption test is the most thorough test but also the most disruptive. The read- through is the least disruptive type of disaster recovery test. During a read-through, team members each review the contents of their disaster recovery checklists on their own and suggest any necessary changes. During a tabletop exercise, team members come

together and walk through a specific scenario without making any changes to information systems.

---

## Question 61
**Correct Answer:** B

**Explanation:**
The Agile approach to software development embraces 12 core principles, found in the Agile Manifesto. One of these principles is that the best architecture, requirements, and designs emerge from self-organizing teams. Another is that teams should welcome changing requirements at any step in the process. A third is that simplicity is essential. The Agile approach emphasizes delivering software frequently, not infrequently.

---

## Question 62
**Correct Answer:** B

**Explanation:**
Hand geometry scanners assess the physical dimensions of an individual's hand but do not verify other unique factors about the individual, or even verify if they are alive. This means that hand geometry scanners should not be implemented as the sole authentication factor for secure environments. Hand geometry scanners do not have an abnormally high FRR and do not stand out as a particular issue from an accessibility standpoint compared to other biometric systems.

---

## Question 63
**Correct Answer:** A

**Explanation:**
The maximum tolerable downtime (MTD) is the amount of time that a business may be without a service before irreparable harm occurs. This measure is sometimes also called maximum tolerable outage (MTO) or maximum allowable downtime (MAD). The Recovery Point Objective (RPO) and Recovery Time Objective (RTO) are related but distinct measures. The RPO focuses on data loss, indicating the maximum period in which data might be lost due to a disruption, and is used to establish the frequency of backups. The RTO, meanwhile, is the target time set for the recovery of IT and business activities after a disruption, aimed to be within the MTD but is not itself a measure of the

direct impact on the business operation. The annual loss expectancy (ALE) is not directly related to service interruption but is a metric used in risk assessment to quantify potential annual financial loss from risks.

---

## Question 64
**Correct Answer:** C

**Explanation:**
Cloud access security brokers (CASBs) are designed to enforce security policies consistently across cloud services and would best meet Bailey's needs. Data loss prevention (DLP) and digital rights management (DRM) solutions may be able to detect, block, and control some use of information in the cloud, but they would not provide a way to consistently enforce security policies across cloud platforms. Intrusion prevention systems (IPS) are designed to detect and block malicious activity and would not be relevant in this scenario.

---

## Question 65
**Correct Answer:** A, D

**Explanation:**
Organizations should always label classified information in whatever form, paper or electronic, that it appears. This allows employees to apply proper handling procedures. It is also a common practice to encrypt sensitive information both at rest and in transit. Organizations should grant access to classified information on a need-to-know basis. Automatically granting access to information, whether it is to a visitor or a senior executive, should not occur.

---

## Question 66
**Correct Answer:** B

**Explanation:**
Masquerading (or impersonation) attacks use stolen or falsified credentials to bypass authentication mechanisms. That term does describe this attack, but you should keep reading the answer choices even after finding a possible correct answer. In this case, replay attacks are a more specific type of masquerading attack that relies on captured authentication tokens, and this is, therefore, a better answer. Spoofing attacks rely on falsifying an identity like an IP address or hostname without credentials. Modification attacks

occur when captured packets are modified and replayed to a system to attempt to perform an action.

---

## Question 67
**Correct Answer:** A

**Explanation:**
OpenID Connect is an authentication layer that works with OAuth 2.0 as its underlying authorization framework. It has been widely adopted by cloud service providers and is widely supported. SAML, RADIUS, and Kerberos are alternative authentication technologies but do not have the same level of seamless integration with OAuth 2.0.

---

## Question 68
**Correct Answer:** C

**Explanation:**
This scenario describes separation of duties—not allowing the same person to hold two roles that, when combined, are sensitive. While two-person control is a similar concept, it does not apply in this case because the scenario does not say that either action requires the concurrence of two users. Least privilege says that an individual should have the minimum set of permissions necessary to carry out their work. Job rotation moves people through jobs on a periodic basis to deter fraud.

---

## Question 69
**Correct Answer:** C

**Explanation:**
The parol evidence rule states that when an agreement between two parties is put into written form, it is assumed to be the entire agreement unless amended in writing. The best evidence rule says that a copy of a document is not admissible if the original document is available. Real evidence and testimonial evidence are evidence types, not rules of evidence.

---

## Question 70
**Correct Answer:** A

**Explanation:**
Network Address Translation (NAT) translates an internal address to an external address. VLANs are used to logically divide networks, BGP is a routing protocol, and G/NAT is a made-up term.

---

## Question 71
**Correct Answer:** B, C, D

**Explanation:**
SSAE-18 does not assert specific controls. Instead, it reviews the use and application of controls in an audited organization. It is an attestation standard,

used for external audits, and forms part of the underlying framework for SOC 1, 2, and 3 reports.

---

## Question 72
**Correct Answer:** A

**Explanation:**
When creating a digital signature, the sender of a message always encrypts the message digest with their own private key. The recipient (or any third party) may then verify the digital signature by decrypting it with the sender's public key and then comparing that decrypted signature with a message digest that the recipient computes themselves.

---

## Question 73
**Correct Answer:** B

**Explanation:**
The recovery time objective (RTO) is the amount of time expected to return an IT service or component to operation after a failure. The maximum tolerable downtime (MTD) is the longest amount of time that an IT service or component may be unavailable without causing serious damage to the organization. The recovery point objective (RPO) identifies the maximum amount of data, measured in time, that may be lost during a recovery effort. Service-level agreements (SLAs) are written contracts that document service expectations.

---

## Question 74
**Correct Answer:** C

**Explanation:**
Change management typically requires sign-off from a manager or supervisor before changes are made. This helps to ensure proper awareness and communication. SDN stands for software-defined networking, release management is the process that new software releases go through to be accepted, and versioning is used to differentiate versions of software, code, or other objects.

---

## Question 75
**Correct Answer:** B

**Explanation:**
Wet pipe suppression systems have water present in the pipes at all times, posing an unacceptable level of risk for a data center containing electronics that might be damaged if a pipe leaks. Dry pipe and pre-action systems only contain water when triggered in the event

of a possible fire. FM-200 is a chemical suppressant commonly used in place of water in data centers.

---

## Question 76
**Correct Answer:** D

**Explanation:**
Notifications and procedures like the signs posted at the company Chris works for are examples of directive access controls. Detective controls are designed to operate after the fact. The doors and the locks on them are examples of physical controls. Preventive controls are designed to stop an event and could also include the locks that are present on the doors.

---

## Question 77
**Correct Answer:** B, D

**Explanation:**
Deterrent controls seek to prevent an intruder from attempting an attack in the first place. Guard dogs have an intimidating presence that serves this purpose well. They do also serve to deny, detect, and delay intrusions depending upon their training. Lighting also deters attacks by making potential intrusions more visible, reducing the likelihood that an intruder will enter a well-lit area. Access control vestibules (also known as mantraps) are intended to deny intruders access, rather than deter attempts. Motion detectors are intended to detect intruders rather than deter them.

---

## Question 78
**Correct Answer:** B

**Explanation:**
This is an example of function-as-a-service (FaaS) computing. However, FaaS is not listed as an answer choice, so you must also know that FaaS is a subcategory of platform-as-a-service (PaaS) computing to answer this question correctly. This model does not necessarily take advantage of containerization. The cloud provider is managing the infrastructure and only making the platform available to customers, so it is not infrastructure as a service (IaaS). The customers are running their own code, so it is not software as a service (SaaS).

---

## Question 79
**Correct Answer:** C, D

**Explanation:**
The attacker may attempt to perform frequency analysis or a brute-force attack against the large volume of encrypted ciphertext. As the attacker does not have access to the plaintext information, a known plaintext attack is not possible. The attacker also does not have the ability to encrypt information, so they cannot use a chosen ciphertext attack.

---

## Question 80
**Correct Answer:** B

**Explanation:**
Provisioning that occurs through an established workflow, such as through an HR process, is workflow- based account provisioning. If Alex had set up accounts for his new hire on the systems he manages, he would have been using discretionary account provisioning. If the provisioning system allowed the new hire to sign up for an account on their own, they would have used self- service account provisioning, and if there was a central, software-driven process, rather than HR forms, it would have been automated account provisioning.

---

## Question 81
**Correct Answer:** C

**Explanation:**
As Alex has changed roles, he retained access to systems that he no longer administers. The provisioning system has provided rights to workstations and the application servers he manages, but he should not have access to the databases he no longer administers. Privilege levels are not specified, so we can't determine if he has excessive privileges. Logging may or may not be enabled, but it isn't possible to tell from the diagram or problem.

---

## Question 82
**Correct Answer:** C

**Explanation:**
When a user's role changes, they should be provisioned based on their role and other access entitlements. De-provisioning and re-provisioning are time-consuming and can lead to problems with changed IDs and how existing credentials work. Simply adding new rights leads to privilege creep, and matching another user's rights can lead to excessive privileges due to privilege creep for that other user.

---

## Question 83
**Correct Answer:** B

**Explanation:**
EAL2 assurance applies when the system has been structurally tested. It is the second-to-lowest level of assurance under the Common Criteria.

---

## Question 84
**Correct Answer:** C

**Explanation:**
Before granting any user access to information, Adam should verify that the user has an appropriate security clearance as well as a business need to know for the information in question.

---

## Question 85
**Correct Answer:** B

**Explanation:**
During the preservation phase, the organization ensures that information related to the matter at hand is protected against intentional or unintentional alteration or deletion. The identification phase locates relevant information but does not preserve it. The collection phase occurs after preservation and gathers responsive information. The processing phase performs a rough cut of the collected information for relevance.

---

## Question 86
**Correct Answer:** C

**Explanation:**
The original version of RIPEMD and the MD5 hash algorithms have known vulnerabilities and should no longer be used. SHA-2 and SHA-3 are both considered secure today and provide the same level of security. SHA-3 is, however, less efficient than SHA-2, making SHA-2 the better choice for Dana's needs.

---

## Question 87
**Correct Answer:** D

**Explanation:**
In the subject/object model, the object is the resource being requested by a subject. In this example, Harry would like access to the document, making the document the object of the request.

---

## Question 88
**Correct Answer:** C

**Explanation:**
The process of removing a header (and possibly a footer) from the data received from a previous layer in the OSI model is known as de-encapsulation. Encapsulation occurs when the header or footer is added. Payloads are the data portion of a packet, but payloading is not a technical term. Similarly, packet unwrapping is a made-up term.

---

## Question 89
**Correct Answer:** A

**Explanation:**
CPTED implements three strategies: natural access control, natural surveillance, and natural territorial reinforcement. Natural access control uses barricades and other physical elements to create a separation between secure and insecure spaces. Natural surveillance designs the environment to expose potential intruders to natural scrutiny by legitimate occupants. Natural territorial reinforcement uses fences, signs, and other elements to clearly define secure spaces. Natural intrusion detection is not an element of CPTED.

---

## Question 90
**Correct Answer:** C

**Explanation:**
If Shahla's organization expands into Canada and handles personally identifiable information as part of its routine business, the most likely new law to affect the organization would be the Personal Information Protection and Electronic Documents Act (PIPEDA). This Canadian federal privacy law governs the collection, use, and disclosure of personal information in the course of commercial business. PIPL is China's Personal Information Protection Law, POPIA is South Africa's Protection of Personal Information Act, and the CCPA is the California Consumer Privacy Act. Each of these laws governs the handling of personal information within their respective jurisdictions, but would not be the primary concern for a U.S. organization considering expansion into Canada.

---

## Question 91
**Correct Answer:** D

**Explanation:**
The use of a probability/impact matrix is the hallmark of a qualitative risk assessment. It uses subjective measures of probability and impact, such as “high,” “moderate,” and “low,” in place of quantitative measures.

---

## Question 92
**Correct Answer:** B

**Explanation:**
Mandatory access control systems can be hierarchical, where each domain is ordered and related to other domains above and below it;

compartmentalized, where there is no relationship between each domain; or hybrid, where both hierarchy and compartments are used. There is no concept of bracketing in mandatory access control design.

---

## Question 93
**Correct Answer:** B

**Explanation:**
Asymmetric encryption algorithms require two keys per user, regardless of the number of participants. Therefore, this six-member team would require 12 keys. If this team were to use symmetric cryptography, they would require (n*(n-1))/2, or (6*(6-1))/2 = 15 keys.

---

## Question 94
**Correct Answer:** B

**Explanation:**
Category 5e and Category 6 UTP cables are both rated to 1000Mbps. Cat 5 (not Cat 5e) is only rated to 100Mbps, whereas Cat 7 is rated to 10Gbps. There is no Cat 4e.

---

## Question 95
**Correct Answer:** C

**Explanation:**
While Ursula may use a variety of different options to meet her needs, the best approach would be the use of a content delivery network (CDN). CDNs are specifically designed for this role, distributing content to many remote endpoints where it may be quickly loaded by local users.

---

## Question 96
**Correct Answer:** D

**Explanation:**
Smurf attacks use a distributed attack approach to send ICMP echo replies at a targeted system from many different source addresses. The most effective way to block this attack would be to block inbound ICMP traffic. Blocking the source addresses is not feasible because the attacker would likely simply change the source addresses. Blocking destination addresses would likely disrupt normal activity. The smurf attack does not use UDP, so blocking that traffic would have no effect.

---

## Question 97
**Correct Answer:** C

**Explanation:**
Static packet filtering firewalls are known as first- generation firewalls and do not track connection state. Stateful inspection, application proxying, and next-

generation firewalls all add connection state tracking capability.

---

## Question 98
**Correct Answer:** C

**Explanation:**
All of these controls serve to increase the reliability of power to a server. However, only dual power supplies address hardware issues that arise within the server, allowing the server to continue operation if one of the power supplies fails. Redundant power sources, backup generators, and uninterruptible power supplies (UPS) are designed to increase the reliability of power flowing to the server.

---

## Question 99
**Correct Answer:** A, C

**Explanation:**
The Remote Desktop Protocol (RDP) and Secure Shell (SSH) are modern approaches to remote access that include encryption features. Telnet and dial-up are outdated approaches that do not provide encryption and should not be relied upon for secure access.

---

## Question 100
**Correct Answer:** B

**Explanation:**
Latency is a delay in the delivery of packets from their source to their destination. Jitter is a variation in the latency for different packets. Packet loss is the disappearance of packets in transit that requires retransmission. Interference is electrical noise or other disruptions that corrupt the contents of packets.

---

## Question 101
**Correct Answer:** A, B, D

**Explanation:**
It is entirely appropriate to distribute internal audit reports to anyone in the organization who has a valid need to know. This may include both management and individual contributors responsible for remediating issues as well as board members charged with oversight. It would not normally be appropriate to distribute internal audit reports to external entities, such as suppliers and customers.

---

## Question 102
**Correct Answer:** B

**Explanation:**
Web applications communicate with web browsers via an interface, making interface testing the best answer here. Regression testing might be used as part of the interface test but is too specific to be the best

answer. Similarly, the test might be a white-box, or full knowledge, test, but interface testing better describes this specific example. Fuzzing is less likely a part of a browser compatibility test, as it tests unexpected inputs, rather than functionality.

---

## Question 103
**Correct Answer:** A

**Explanation:**
Role-based access control gives each user an array of permissions based on their position in the organization, such as the scheme shown here. Task- based access control is not a standard approach. Rule- based access controls use rules that apply to all subjects, which isn't something we see in the list. Discretionary access control gives object owners rights to choose how the objects they own are accessed, which is not what this list shows.

---

## Question 104
**Correct Answer:** D

**Explanation:**
Fire suppression systems do not stop a fire from occurring but do reduce the damage that fires cause. This is an example of reducing risk by lowering the impact of an event.

---

## Question 105
**Correct Answer:** D

**Explanation:**
Patents and trade secrets can both protect intellectual property in the form of a process. Patents require public disclosure and have expiration dates, while trade secrets remain in force for as long as they remain secret. Therefore, trade secret protection most closely aligns with the company's goals.

---

## Question 106
**Correct Answer:** D

**Explanation:**
The Security Content Automation Protocol (SCAP) is a suite of specifications used to handle vulnerability and security configuration information. The National Vulnerability Database provided by NIST uses SCAP. XACML is the eXtensible Access Control Markup Language, an OASIS standard used for access control decisions, and neither VSML nor SCML is an industry term.

---

## Question 107
**Correct Answer:** D

**Explanation:**
Breach and attack simulation (BAS) platforms are intended to automate some aspects of penetration testing. These systems are designed to inject threat indicators onto systems and networks in an effort to trigger other security controls. White-box, gray-box, and black-box testing all involve more significant manual effort.

---

## Question 108
**Correct Answer:** A

**Explanation:**
The Simple Security Property prevents an individual from reading information at a higher security level than their clearance allows. This is also known as the “no read up” rule. The Simple Integrity Property says that a subject cannot read an object at a lower integrity level (no read down). The *-Security Property says that users can't write data to a lower security level than their own. The Discretionary Security Property allows the use of a matrix to determine access permissions.

---

## Question 109
**Correct Answer:** B

**Explanation:**
The work breakdown structure (WBS) is an important project management tool that divides the work done for a large project into smaller components. It is not a project plan because it does not describe timing or resources. Test analyses are used during later phases of the development effort to report test results. Functional requirements may be included in a work breakdown structure, but they are not the full WBS.

---

## Question 110
**Correct Answer:** B

**Explanation:**
Network Access Control (NAC) systems can be used to authenticate users and then validate their system's compliance with a security standard before they are allowed to connect to the network. Enforcing security profiles can help reduce zero-day attacks, making NAC a useful solution. A firewall can't enforce system security policies, whereas an IDS can only monitor for attacks and alarm when they happen. Thus, neither a firewall nor an IDS meets Kolin's needs. Finally, port security is a MAC address-based security feature that

can restrict only which systems or devices can connect to a given port.

---

## Question 111
**Correct Answer:** C

**Explanation:**
This scenario violates the least privilege principle because an application should never require full administrative rights to run. Gwen should update the service account to have only the privileges necessary to support the application.

---

## Question 112
**Correct Answer:** B, C, D

**Explanation:**
Organizations typically use the time to resolve vulnerabilities, the number of account compromises, and the number of attempts by users to visit malicious sites as indicators. The number of scheduled audits is not normally a measure of the performance of an information security team. A more appropriate indicator in this area is the number of repeat audit findings.

---

## Question 113
**Correct Answer:** A

**Explanation:**
This is a true positive report because the scan detected the vulnerability, and the vulnerability actually existed. The fact that the team later remediated the vulnerability could be noted in the report, but it does not change the result of the scan or its classification. True negatives occur when scans correctly note the absence of a vulnerability. False positives occur when scans report the presence of a vulnerability that does not actually exist. False negatives occur when scans report that no vulnerability exists when one does, in fact, exist.

---

## Question 114
**Correct Answer:** C

**Explanation:**
Test directories often include scripts that may have poor protections or may have other data that can be misused. There is not a default test directory that allows administrative access to PHP. Test directories are not commonly used to store sensitive data, nor is the existence of a test directory a common indicator of compromise.

---

## Question 115
**Correct Answer:** A

**Explanation:**
Directory indexing may not initially seem like an issue during a penetration test, but simply knowing the name and location of files can provide an attacker with quite a bit of information about an organization, as well as a list of potentially accessible files. XDRF is not a type of attack, and indexing is not a denial-of-service attack vector. Directory indexing being turned on is typically either due to design or because the server was misconfigured at setup, rather than being a sign of attack.

---

## Question 116
**Correct Answer:** B

**Explanation:**
Cross-site tracing (XST) leverages the HTTP TRACE or TRACK methods and could be used to steal a user's cookies via cross-site scripting (XSS). The other options are not industry terms for web application or web server attacks or vulnerabilities.

---

## Question 117
**Correct Answer:** C

**Explanation:**
The chief audit executive (CAE) should report to the most senior possible leader to avoid conflicts of interest. Of the choices provided, the chief executive officer (CEO) is the most senior position and the best option. It is also possible to provide an added degree of independence by having the CAE report to the board of directors, either as a primary reporting line or as a dotted line relationship.

---

## Question 118
**Correct Answer:** C

**Explanation:**
Data loss prevention (DLP) systems specialize in the identification of sensitive information. In this case, Ursula would like to identify the presence of this information on endpoint devices, so she should choose an endpoint DLP control. Network-based DLP would not detect stored information unless the user transmits it over the network. Intrusion prevention systems (IPSs) are designed to detect and block attacks in progress, not necessarily the presence of sensitive information.

---

## Question 119
**Correct Answer:** B

**Explanation:**
In the private cloud computing model, the cloud computing environment is dedicated to a single organization and does not follow the shared tenancy model. The environment may be built by the company in its own data center or built by a vendor at a co- location site.

---

## Question 120
**Correct Answer:** A

**Explanation:**
Load balancing helps to ensure that a failed server will not take a website or service offline. Dual power supplies only work to prevent failure of a power supply or power source. IPS can help to prevent attacks, and RAID can help prevent a disk failure from taking a system offline.

---

## Question 121
**Correct Answer:** D

**Explanation:**
Integrity ensures that unauthorized changes are not made to data while stored or in transit.

---

## Question 122
**Correct Answer:** C

**Explanation:**
A star topology uses a central connection device. Ethernet networks may look like a star, but they are actually a logical bus topology that is sometimes deployed in a physical star.

---

## Question 123
**Correct Answer:** C

**Explanation:**
Input validation ensures that the data provided to a program as input matches the expected parameters. Limit checks are a special form of input validation that ensure that the value remains within an expected range, as is the case described in this scenario. Fail open and fail secure are options when planning for possible system failures. Buffer bounds are not a type of software control.

---

## Question 124
**Correct Answer:** See Explanation

**Explanation:**
The testing methodologies match with the level of knowledge as follows: 1. Black box: C. No prior knowledge of the system 2. White box: A. Full knowledge of the system 3. Gray box: B. Partial or incomplete knowledge

---

## Question 125
**Correct Answer:** See Explanation

**Explanation:**
The factors match to the types as follows:

A. A PIN: 1. Something you know B. A token: 2. Something you have C. A fingerprint: 3. Something you are D. A password: 1. Something you know E. A smartcard: 2. Something you have F. A retinal scan: 3. Something you are G. A security question/answer: 1. Something you know

---

