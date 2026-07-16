# CISSP Practice Tests - Chapter 11: Practice Test 3 Answer Key

## Question 1
**Correct Answer:** B

**Explanation:**
NIST SP 800-18 describes system owner responsibilities that include helping to develop system security plans, maintaining the plan, ensuring training, and identifying, implementing, and assessing security controls. A data owner is more likely to delegate these tasks to the system owner. Custodians may be asked to enforce those controls, whereas a user will be directly affected by them.

---

## Question 2
**Correct Answer:** C

**Explanation:**
ESP's Transport mode encrypts IP packet data but leaves the packet header unencrypted. Tunnel mode encrypts the entire packet and adds a new header to support transmission through the tunnel.

---

## Question 3
**Correct Answer:** B

**Explanation:**
In level 2, the Repeatable level of the SW-CMM, the organization introduces basic life cycle management processes. Reuse of code in an organized fashion begins, and repeatable results are expected from similar projects. The crucial process areas for this level include Requirements Management, Software Project Planning, Software Project Tracking and Oversight, Software Subcontract Management, Software Quality Assurance, and Software Configuration Management. Software Quality Management is a process that occurs during level 4, the Managed stage of the SW-CMM.

---

## Question 4
**Correct Answer:** A

**Explanation:**
Key risk indicators (KRIs) are often used to monitor risk for organizations that establish an ongoing risk management program. Using automated data gathering and tools that allow data to be digested and summarized can provide predictive information about how organizational risks are changing. KPIs are key performance indicators, which are used to assess how an organization is performing. Quantitative risk assessments are good for point-in-time views with

detailed valuation and measurement-based risk assessments, whereas a penetration test would provide details of how well an organization's security controls are working.

---

## Question 5
**Correct Answer:** D

**Explanation:**
The three-way handshake is SYN, SYN/ACK, ACK. System B should respond with “Synchronize and Acknowledge” to System A after it receives a SYN.

---

## Question 6
**Correct Answer:** A

**Explanation:**
Systems that respond to pings will show the time to live for packets that reach them. Since TTL is decremented at each hop, this can help build a rough network topology map. In addition, some firewalls respond differently to pings than a normal system, which means pinging a network can sometimes reveal the presence of firewalls that would otherwise be invisible. Hostnames are revealed by a DNS lookup, and ICMP types allowed through a firewall are not revealed by only performing a ping. ICMP can be used for router advertisements, but pinging won't show them!

---

## Question 7
**Correct Answer:** C

**Explanation:**
Authorization defines what a subject can or can't do. Identification occurs when a subject claims an identity, accounting is provided by the logs and audit trail that track what occurs on a system, and authentication occurs when that identity is validated.

---

## Question 8
**Correct Answer:** C

**Explanation:**
When a system uses shadowed passwords, the hashed password value is stored in /etc/shadow instead of /etc/passwd. The /etc/passwd file would not contain the password in plaintext or hashed form. Instead, it would contain an x to indicate that the password hash is in the shadow file. The * character is normally used to disable interactive logins to an account.

---

## Question 9
**Correct Answer:** B

**Explanation:**
The log entries show the characteristic pattern of a port scan. The attacking system sends connection

attempts to the target system against a series of commonly used ports.

---

## Question 10
**Correct Answer:** A

**Explanation:**
Testing for desired functionality is use-case testing. Dynamic testing is used to determine how code handles variables that change over time. Misuse testing focuses on how code handles examples of misuse, and fuzzing feeds unexpected data as an input to see how the code responds.

---

## Question 11
**Correct Answer:** B

**Explanation:**
Privilege creep is a common problem when employees change roles over time and their privileges and permissions are not properly modified to reflect their new roles. Least privilege issues are a design or implementation problem, and switching roles isn't typically what causes them to occur. Account creep is not a common industry term, and account termination would imply that someone has removed her account instead of switching her to new groups or new roles.

---

## Question 12
**Correct Answer:** C

**Explanation:**
These are examples of private IP addresses. RFC 1918 defines a set of private IP addresses for use in internal networks. These private addresses including 10.0.0.0 to 10.255.255.255, 172.16.0.0 to 172.31.255.255, and 192.168.0.0 to 192.168.255.255 should never be routable on the public Internet.

---

## Question 13
**Correct Answer:** B

**Explanation:**
A cognitive password authenticates users based on a series of facts or answers to questions that they know. Preset questions for cognitive passwords typically rely on common information about a user like their mother's maiden name or the name of their pet, and that information can frequently be found on the Internet. The best cognitive password systems let users make up their own questions.

---

## Question 14
**Correct Answer:** B

**Explanation:**
The Linux tool dd creates a bit-by-bit copy of the target drive that is well suited to forensic use, and

special forensic versions of dd exist that can provide even more forensic features. Simply copying files using a tool like xcopy does not create a forensically sound copy. DBAN is a drive wiping tool and would cause Megan to lose the data she is seeking to copy. ImageMagick is a graphics manipulation and editing program.

---

## Question 15
**Correct Answer:** C

**Explanation:**
The blacklist approach to application control blocks certain prohibited packages but allows the installation of other software on systems. The whitelist approach uses the reverse philosophy and allows only approved software. Antivirus software would detect the installation of malicious software only after the fact. Heuristic detection is a variant of antivirus software.

---

## Question 16
**Correct Answer:** C

**Explanation:**
Protected health information (PHI) is specifically defined by HIPAA to include information about an individual's medical bills. PCI could refer to the payment card industry's security standard but would apply only in relation to payment cards. PII is a broadly defined term for personally identifiable information, and personal billing data isn't a broadly used industry term.

---

## Question 17
**Correct Answer:** D

**Explanation:**
A social engineering attack may trick a user into revealing their password to the attacker. Other attacks that depend on guessing passwords, such as brute- force attacks, rainbow table attacks, and dictionary attacks, are unlikely to be successful in light of the organization's strong password policy.

---

## Question 18
**Correct Answer:** A

**Explanation:**
When someone is forced to perform an action under threat, it is known as duress.

---

## Question 19
**Correct Answer:** A

**Explanation:**
The term that best describes the type of cloud environment used by Kayla's company, which leverages a major IaaS provider for hosting its web services and a

SaaS email system operating in multitenant environments, is a public cloud. A public cloud is where the services are delivered over the public Internet and shared across different organizations. A dedicated cloud, also known as a private cloud, is operated solely for one organization, and this is not the case for Kayla's company. A private cloud is infrastructure operated solely for a single organization, whether managed internally or by a third-party, and hosted either internally or externally, which also does not apply here. A hybrid cloud is a composition of two or more cloud delivery models (private, community, or public) that remain distinct entities but are bound together, offering the benefits of multiple deployment models, which again does not match the company's use of exclusively public cloud services.

---

## Question 20
**Correct Answer:** B

**Explanation:**
In this scenario, all of the files on the server will be backed up on Monday evening during the full backup. Tuesday's incremental backup will include all files changed since Monday's full backup: files 1, 2, and 5. Wednesday's incremental backup will then include all files modified since Tuesday's incremental backup: files 3 and 6. Therefore, only two files are included in Wednesday's incremental backup.

---

## Question 21
**Correct Answer:** A

**Explanation:**
Susan is performing passive monitoring, which uses a network tap or SPAN port to capture traffic to analyze it without impacting the network or devices that it is used to monitor. Synthetic, or active, monitoring uses recorded or generated traffic to test for performance and other issues. Signature-based technologies include IDS, IPS, and antimalware systems.

---

## Question 22
**Correct Answer:** A

**Explanation:**
In a man-in-the-middle attack, attackers manage to insert themselves into a connection between a user and

a legitimate website, relaying traffic between the two parties while eavesdropping on the connection. Although similarly named, the meet-in-the-middle attack is a cryptographic attack that does not necessarily involve connection tampering. Fraggle is a network-based denial-of-service attack using UDP packets. Wardriving is a reconnaissance technique for discovering open or weakly secured wireless networks.

---

## Question 23
**Correct Answer:** C

**Explanation:**
One of the core capabilities of infrastructure as a service is providing servers on a vendor-managed virtualization platform. Web-based payroll and email systems are examples of software as a service. An application platform managed by a vendor that runs customer code is an example of platform as a service.

---

## Question 24
**Correct Answer:** D

**Explanation:**
The exposure factor is the percentage of the facility that risk managers expect will be damaged if a risk materializes. It is calculated by dividing the amount of damage by the asset value. In this case, that is $750,000 in damage divided by the $2 million facility value, or 37.5%.

---

## Question 25
**Correct Answer:** C

**Explanation:**
The annualized rate of occurrence is the number of times each year that risk analysts expect a risk to happen. In this case, the analysts expect fires will occur once every 50 years, or 0.02 times per year.

---

## Question 26
**Correct Answer:** A

**Explanation:**
The annualized loss expectancy is calculated by multiplying the single loss expectancy (SLE) by the annualized rate of occurrence (ARO). In this case, the SLE is $750,000, and the ARO is 0.02. Multiplying these numbers together gives you the ALE of $15,000.

---

## Question 27
**Correct Answer:** C

**Explanation:**
The two main methods of choosing records from a large pool for further analysis are sampling and clipping. Sampling uses statistical techniques to choose a sample that is representative of the entire pool, while

clipping uses threshold values to select those records that exceed a predefined threshold because they may be of most interest to analysts.

---

## Question 28
**Correct Answer:** C

**Explanation:**
API keys, or application programming interface keys, are passed to services and identify the program, developer, or user. With this information, Mike can programmatically control API usage per user. Of course, if the keys are inadvertently exposed, the API keys themselves could be abused. Session IDs are typically used to identify users of an application, not an API. API firewalls and API buffers were made up for this question.

---

## Question 29
**Correct Answer:** A

**Explanation:**
An application programming interface (API) allows external users to directly call routines within Fran's code. They can embed API calls within scripts and other programs to automate interactions with Fran's company. A web scraper or call center might facilitate the same tasks, but they do not do so in a direct integration. Data dictionaries might provide useful information, but they also do not allow direct integration.

---

## Question 30
**Correct Answer:** A

**Explanation:**
A fault is a momentary loss of power. Blackouts are sustained complete losses of power. Sags and brownouts are not complete power disruptions but rather periods of low-voltage conditions.

---

## Question 31
**Correct Answer:** A

**Explanation:**
Lauren's team would benefit from a credential management system. Credential management systems offer features like password management, multifactor authentication to retrieve passwords, logging, audit, and password rotation capabilities. A strong password policy would only make maintenance of passwords for many systems a more difficult task if done manually. Single sign-on would help if all the systems had the

same sensitivity levels, but different credentials are normally required for higher-sensitivity systems.

---

## Question 32
**Correct Answer:** C

**Explanation:**
Windows systems will assign themselves an APIPA address between 169.254.0.1 and 169.254.255.254 if they cannot contact a DHCP server.

---

## Question 33
**Correct Answer:** A

**Explanation:**
Enrollment, or registration, is the initial creation of a user account in the provisioning process. Clearance verification and background checks are sometimes part of the process that ensures that the identity of the person being enrolled matches who they claim to be. Initialization is not used to describe the provisioning process.

---

## Question 34
**Correct Answer:** B

**Explanation:**
Criminal forensic investigations typically have the highest standards for evidence, as they must be able to help prove the case beyond a reasonable doubt. Administrative investigations merely need to meet the standards of the organization and to be able to be defended in court, while civil investigations operate on a preponderance of evidence. There is not a category of forensic investigation referred to as “industry” in the CISSP exam's breakdown of forensic types.

---

## Question 35
**Correct Answer:** B

**Explanation:**
The Fourth Amendment states, in part, that “the right of the people to be secure in their persons, houses, papers and effects, against unreasonable searches and seizures, shall not be violated, and no Warrants shall issue, but upon probable cause, supported by Oath or affirmation, and particularly describing the place to be searched, and the persons or things to be seized.” The First Amendment contains protections related to freedom of speech. The Fifth Amendment ensures that no person will be required to serve as a witness against themselves. The Fifteenth Amendment protects the voting rights of citizens.

---

## Question 36
**Correct Answer:** A

**Explanation:**
The Electronic Communications Privacy Act (ECPA) makes it a crime to invade the electronic privacy of an individual. It prohibits the unauthorized monitoring of email and voicemail communications.

---

## Question 37
**Correct Answer:** D

**Explanation:**
The kernel lies within the central ring, Ring 0. Ring 1 contains other operating system components. Ring 2 is used for drivers and protocols. User-level programs and applications run at Ring 3. Rings 0–2 run in privileged mode, whereas Ring 3 runs in user mode.

---

## Question 38
**Correct Answer:** D

**Explanation:**
The hypervisor runs within the virtualization platform and serves as the moderator between virtual resources and physical resources.

---

## Question 39
**Correct Answer:** A

**Explanation:**
In the public cloud computing model, the vendor builds a single platform that is shared among many different customers. This is also known as the shared tenancy model.

---

## Question 40
**Correct Answer:** D

**Explanation:**
During a tabletop exercise, team members come together and walk through a scenario without making any changes to information systems. The read-through is the least disruptive type of disaster recovery test. During a read-through, team members each review the contents of their disaster recovery checklists on their own and suggest any necessary changes. During a parallel test, the team actually activates the disaster recovery site for testing, but the primary site remains operational. During a full interruption test, the team takes down the primary site and confirms that the disaster recovery site is capable of handling regular operations. The full interruption test is the most thorough test but also the most disruptive.

---

## Question 41
**Correct Answer:** C

**Explanation:**
OpenID Connect is a widely supported standard that allows a user to use a single account to log into

multiple sites, and Google accounts are frequently used with OpenID Connect.

---

## Question 42
**Correct Answer:** D

**Explanation:**
Risk acceptance occurs when an organization determines that the costs involved in pursuing other risk management strategies are not justified and they choose not to pursue any action.

---

## Question 43
**Correct Answer:** A, D

**Explanation:**
Accounting departments are normally required to separate sensitive duties, such as the ability to add a new vendor and issue a check. Allowing the manager to perform both of these actions would, therefore, violate the principle of separation of duties. Also, it is quite likely that the manager does not need all of these privileges to carry out their work, violating the principle of least privilege. There is no indication that the situation does not follow job rotation assignments or that the access was not properly granted and subject to a management review.

---

## Question 44
**Correct Answer:** C

**Explanation:**
Decentralized access control makes sense because it allows local control over access. When network connectivity to a central control point is a problem or if rules and regulations may vary significantly from location to location, centralized control can be less desirable than decentralized control despite its challenges with consistency. Since the problem does not describe specific control needs, mandatory access control and rule-based access controls could fit the need but aren't the best answer.

---

## Question 45
**Correct Answer:** B

**Explanation:**
The U.S. government classifies data that could reasonably be expected to cause damage to national security if disclosed, and for which the damage can be identified or described, as Secret. The U.S. government does not use Classified in its formal four levels of classification. Top Secret data could cause

exceptionally grave damage, whereas Confidential data could be expected to cause damage.

---

## Question 46
**Correct Answer:** A

**Explanation:**
The purpose of a digital certificate is to provide the general public with an authenticated copy of the certificate subject's public key.

---

## Question 47
**Correct Answer:** D

**Explanation:**
The last step of the certificate creation process is the digital signature. During this step, the certificate authority signs the certificate using its own private key.

---

## Question 48
**Correct Answer:** C

**Explanation:**
When an individual receives a copy of a digital certificate, the person verifies the authenticity of that certificate by using the CA's public key to validate the digital signature contained on the certificate.

---

## Question 49
**Correct Answer:** A

**Explanation:**
Mike uses the public key that he extracted from Renee's digital certificate to encrypt the message that he would like to send to Renee.

---

## Question 50
**Correct Answer:** C

**Explanation:**
Wireshark is a network monitoring tool that can capture and replay communications sent over a data network, including Voice over IP (VoIP) communications. Nmap, Nessus, and Nikto are all security tools that may identify security flaws in the network, but they do not directly undermine confidentiality because they do not have the ability to capture communications.

---

## Question 51
**Correct Answer:** C

**Explanation:**
The ISC2 Code of Ethics applies only to information security professionals who are members of ISC2. Adherence to the code is a condition of certification, and individuals found in violation of the code may have their certifications revoked. ISC2 members who observe a breach of the code are required to report the possible violation by following the ethics complaint procedures.

---

## Question 52
**Correct Answer:** D

**Explanation:**
Nonrepudiation is possible only with an asymmetric encryption algorithm. RSA is an asymmetric algorithm.

AES, DES, and Blowfish are all symmetric encryption algorithms that do not provide nonrepudiation.

---

## Question 53
**Correct Answer:** D

**Explanation:**
Modification of audit logs will allow repudiation because the data cannot be trusted, and thus actions can be provably denied. The modification of the logs is also a direct example of tampering. It might initially be tempting to answer elevation of privileges and tampering, as the attacker made changes to files that should be protected, but this is an unknown without more information. Similarly, the attacker may have accessed the files, resulting in information disclosure in addition to tampering, but again, this is not specified in the question. Finally, this did not cause a denial of service, and thus that answer can be ignored.

---

## Question 54
**Correct Answer:** B

**Explanation:**
Content delivery networks (CDNs) place endpoints at geographic locations around the world and then cache customer content at those endpoints. The CDN servers then handle user requests for data, greatly reducing the burden on the organization's own servers and improving load time. Load balancers would distribute the load among Carmen's own servers and would, therefore, not meet her requirements. TLS acceleration may improve load time by reducing the burden of encryption on servers, but they would not place content closer to end users. Web application firewalls would be used to protect the servers against attack, but this does not match Carmen's requirements.

---

## Question 55
**Correct Answer:** D

**Explanation:**
The scenario describes a mix of public cloud and private cloud services. This is an example of a hybrid cloud environment.

---

## Question 56
**Correct Answer:** B

**Explanation:**
Each of the attributes linked to Ben's access provides information for an attribute-based information control system. Attribute-based information controls like those described in NIST SP 800-162 can take many

details about the user, actions, and objects into consideration before allowing access to occur. A role- based access control would simply consider Ben's role, whereas both administrative and system discretionary access controls are not commonly used terms to describe access controls.

---

## Question 57
**Correct Answer:** B, D

**Explanation:**
All of these techniques are valid components of a security awareness and training program. However, users generally find policy reviews and classroom training boring. Gamification and phishing simulations are designed to bring interactivity to the effort and make it more interesting and engaging for users.

---

## Question 58
**Correct Answer:** C

**Explanation:**
Certificates may only be added to a certificate revocation list by the certificate authority that created the digital certificate.

---

## Question 59
**Correct Answer:** D

**Explanation:**
Remote journaling transfers transaction logs to a remote site on a more frequent basis than electronic vaulting, typically hourly. Transaction logging is not a recovery technique alone; it is a process for generating the logs used in remote journaling. In an electronic vaulting approach, automated technology moves database backups from the primary database server to a remote site on a scheduled basis, typically daily. Remote mirroring maintains a live database server at the backup site and mirrors all transactions at the primary site on the server at the backup site.

---

## Question 60
**Correct Answer:** A, B, D

**Explanation:**
The specific data elements covered by state data breach notification laws vary from state to state, but most include Social Security numbers, drivers' license numbers, and bank account numbers when paired with a PIN. No state data breach notification laws include marital status as a covered element.

---

## Question 61
**Correct Answer:** B

**Explanation:**
Operational investigations are performed by internal teams to troubleshoot performance or other technical issues. They are not intended to produce evidence for use in court and, therefore, do not have the rigid collection standards of criminal, civil, or regulatory investigations.

---

## Question 62
**Correct Answer:** A

**Explanation:**
Nondisclosure agreements (NDAs) are designed to protect the confidentiality of an organization's data, including trade secrets during and after the person's employment. NDAs do not protect against deletion or availability issues, and noncompete agreements would be required to stop competition.

---

## Question 63
**Correct Answer:** C

**Explanation:**
Adding a second factor can ensure that users who might be incorrectly accepted are not given access due to a higher than desired false acceptance rate (FAR) from accessing a system. The CER is the crossover between the false acceptance and false rejection rate (FRR) and is used as a way to measure the accuracy of biometric systems. Changing the sensitivity to lower the FRR may actually increase the FAR, and replacing a biometric system can be expensive in terms of time and cost.

---

## Question 64
**Correct Answer:** D

**Explanation:**
Data custodians are typically responsible for the technical environment and procedures related to data management, which include the backup and recovery of systems to ensure data availability. While data owners are accountable for the data and may decide what needs to be backed up, they do not perform the actual backups. Business owners and data users are more focused on the operational and decision-making aspects of the data's business use and are generally not involved in the technical aspects of data maintenance such as system backups.

---

## Question 65
**Correct Answer:** D

**Explanation:**
Ron's company is a data processor in this instance, as it is receiving records from the European firm. The European firm is the data controller in this case, as they bear responsibility for the data. The individuals described in the records are the data subjects. Data owners are tasked with making decisions about data such as who receives access to it and how it is used.

---

## Question 66
**Correct Answer:** C

**Explanation:**
This is an example of two-person control, where two people must concur to perform a sensitive action. Separation of duties is a slightly different principle, where one individual is prevented from holding the privileges to perform two separate actions that, when combined, would result in excessive permissions. Least privilege says that an individual should have the minimum necessary set of permissions to carry out their job functions. There is no indication that least privilege is violated in this scenario. Multifactor authentication is an important security control, but the scenario does not mention whether the administrators use multifactor authentication to perform these activities.

---

## Question 67
**Correct Answer:** C

**Explanation:**
Salting adds random text to the password before hashing in an attempt to defeat automated password cracking attacks that use precomputed values. MD5 and SHA-1 are both common hashing algorithms, so using them does not add any security. Double-hashing would only be a minor inconvenience for an attacker and would not be as effective as the use of salting.

---

## Question 68
**Correct Answer:** A

**Explanation:**
Guidelines provide advice based on best practices developed throughout industry and organizations, but they are not compulsory. Compliance with guidelines is optional.

---

## Question 69
**Correct Answer:** A

**Explanation:**
The Bell–LaPadula model includes the simple security property, which says that no user should be

able to read information above their security clearance level. It also includes the star property, which says that a subject should not be able to write data to an object below their security clearance level, and the discretionary security property, which uses access matrices to control access. The Biba integrity model says that users should not be able to read data below their security clearance level.

---

## Question 70
**Correct Answer:** C

**Explanation:**
Regression testing ensures proper functionality of an application or system after it has been changed. Unit testing focuses on testing each module of a program instead of against its previous functional state. White- and black-box testing both describe the amount of knowledge about a system or application, rather than a specific type or intent for testing.

---

## Question 71
**Correct Answer:** C

**Explanation:**
Risk transference involves shifting the impact of a potential risk from the organization incurring the risk to another organization. Insurance is a common example of risk transference.

---

## Question 72
**Correct Answer:** A

**Explanation:**
The four canons of the ISC2 Code of Ethics are to protect society, the common good, the necessary public trust and confidence, and the infrastructure; act honorably, honestly, justly, responsibly, and legally; provide diligent and competent service to principals; and advance and protect the profession.

---

## Question 73
**Correct Answer:** C

**Explanation:**
A trust that allows one forest to access another's resources without the reverse being possible is an example of a one-way trust. Since Jim doesn't want the trust path to flow as the domain tree is formed, this trust has to be nontransitive.

---

## Question 74
**Correct Answer:** B

**Explanation:**
Susan's team is performing static analysis, which analyzes nonrunning code. Dynamic analysis uses running code, whereas gray-box assessments are a type

of assessment done without full knowledge. Fuzzing feeds unexpected inputs to a program as part of dynamic analysis.

---

## Question 75
**Correct Answer:** A, D

**Explanation:**
Kevin may choose to pay the ransom, and he may regain access to his data by doing so, but there is no guarantee that the attackers will deliver the decryption key after he makes payment. Additionally, the payment of the ransom may be illegal depending upon the circumstances. He cannot be sure that the attackers do not have access to his information, as the ransomware may have copied data for the attackers' use. Restoring from backup is a good method to regain access to information encrypted by ransomware.

---

## Question 76
**Correct Answer:** A

**Explanation:**
Remote attestation creates a hash value from the system configuration to confirm the integrity of the configuration. Binding and sealing are techniques used by the TPM to encrypt data. The random number generator (RNG) function of the TPM is used to support cryptographic operations.

---

## Question 77
**Correct Answer:** A, C

**Explanation:**
Situations where humidity is too high may result in the buildup of moisture and corrosion of equipment. If humidity falls too low, it may result in static electricity issues. Humidity issues generally do not contribute to fires or physical access control failures.

---

## Question 78
**Correct Answer:** A

**Explanation:**
Hot sites contain all of the hardware and data necessary to restore operations and may be activated very quickly. Warm sites contain the necessary hardware but not the data. Cold sites contain neither hardware nor data. Mobile sites are easily transportable, which is not mentioned in this scenario.

---

## Question 79
**Correct Answer:** B

**Explanation:**
Syslog uses UDP port 514. TCP-based implementations of syslog use TCP port 601 when unencrypted and use TCP port 6514 when encrypted

with TLS. The other ports may look familiar because they are commonly used TCP ports: 443 is HTTPS, 515 is the LPD print service, and 445 is used for Windows SMB.

---

## Question 80
**Correct Answer:** B

**Explanation:**
PSH is a TCP flag used to clear the buffer, resulting in immediately sending data, and URG is the TCP urgent flag. These flags are not present in UDP headers.

---

## Question 81
**Correct Answer:** B

**Explanation:**
Fagan inspection is a highly formalized review and testing process that uses planning, overview, preparation, inspection, rework, and follow-up steps. Static inspection looks at code without running it, dynamic inspection uses live programs, and interface testing tests where code modules interact.

---

## Question 82
**Correct Answer:** D

**Explanation:**
The system is set to overwrite the logs and will replace the oldest log entries with new log entries when the file reaches 20 MB. The system is not purging archived logs because it is not archiving logs. Since there can be only 20 MB of logs, this system will not have stored too much log data, and the question does not provide enough information to know if there will be an issue with not having the information needed.

---

## Question 83
**Correct Answer:** D

**Explanation:**
The image shown is from a network-connected web camera. This is likely an Internet of Things (IoT) botnet, much like the Mirai botnet that had a major impact on world Internet traffic in 2016.

---

## Question 84
**Correct Answer:** A

**Explanation:**
Alejandro is in the first stage of the incident response process, detection. During this stage, the intrusion detection system provides the initial alert, and Alejandro performs preliminary triaging to determine if an intrusion is actually taking place and whether the scenario fits the criteria for activating further steps of the incident response process (which

include response, mitigation, reporting, recovery, remediation, and lessons learned).

---

## Question 85
**Correct Answer:** C

**Explanation:**
After detection of a security incident, the next step in the process is response, which should follow the organization's formal incident response procedure. The first step of this procedure is activating the appropriate teams, including the organization's computer security incident response team (CSIRT).

---

## Question 86
**Correct Answer:** C

**Explanation:**
The root-cause analysis examines the incident to determine what allowed it to happen and provides critical information for repairing systems so that the incident does not recur. This is a component of the remediation step of the incident response process because the root-cause analysis output is necessary to fully remediate affected systems and processes.

---

## Question 87
**Correct Answer:** D

**Explanation:**
When using symmetric cryptography, the sender encrypts a message using a shared secret key, and the recipient then decrypts the message with that same key. Only asymmetric cryptography uses the concept of public and private key pairs.

---

## Question 88
**Correct Answer:** A

**Explanation:**
Business logic errors are most likely to be missed by automated functional testing. If a complete coverage code test was conducted, runtime, input validation, and error handling issues are likely to have been discovered by automated testing. Any automated system is more likely to miss business logic errors, because humans are typically necessary to understand business logic issues.

---

## Question 89
**Correct Answer:** A

**Explanation:**
During the lessons learned phase, analysts close out an incident by conducting a review of the entire incident response process. This may include making recommendations for improvements to the process that

will streamline the efficiency and effectiveness of future incident response efforts.

---

## Question 90
**Correct Answer:** B

**Explanation:**
The Digital Millennium Copyright Act (DMCA) prohibits attempts to circumvent copyright protection mechanisms placed on a protected work by the copyright holder. The Health Insurance Portability and Accountability Act (HIPAA) governs the security and privacy of protected health information. The Gramm- Leach-Bliley Act (GLBA) governs the security and privacy of financial information. The Electronic Communications Privacy Act (ECPA) restricts eavesdropping on private communications.

---

## Question 91
**Correct Answer:** B

**Explanation:**
Linda should choose a warm site. This approach balances cost and recovery time. Cold sites take a very long time to activate, measured in weeks or months. Hot sites activate immediately but are quite expensive. Mutual assistance agreements depend on the support of another organization.

---

## Question 92
**Correct Answer:** A

**Explanation:**
Purchasing insurance is a way to transfer risk to another entity. Risk avoidance actions change business processes to eliminate a risk. Risk mitigation activities reduce the likelihood or impact of a risk occurring. Risk acceptance takes no action to control the risk other than acknowledging its presence.

---

## Question 93
**Correct Answer:** D

**Explanation:**
Gray-box testing is a blend of crystal-box (or white- box) testing, which provides full information about a target, and black-box testing, which provides little or no knowledge about the target.

---

## Question 94
**Correct Answer:** A

**Explanation:**
The combination of an ID card (something you have) and a PIN (something you know) is a reasonable way to control access to a physical facility. The use of a password is not a user-friendly way to control access to a physical facility. The use of an ID card (something

you have) in conjunction with an access token (something you have) does not constitute multifactor authentication because both are something you have factors. The same is true for the use of a retinal scan (something you are) and a fingerprint (something you are).

---

## Question 95
**Correct Answer:** A

**Explanation:**
Ethernet networks in modern organizations use a star topology, where each device is directly connected to the switch and receives only traffic intended for that device. This reduces the possibility of eavesdropping on other devices.

---

## Question 96
**Correct Answer:** A

**Explanation:**
Proxy servers can act to anonymize web requests by hiding their true source IP addresses and removing identifying information. Content filters restrict the websites that users may access. Malware filters search for and block malicious code. Caching servers store local copies of frequently requested content to reduce loading time.

---

## Question 97
**Correct Answer:** A

**Explanation:**
U.S. export control laws contain special provisions around the use of encryption technology, and Evelyn should include details about the software used by her firm in the training. These regulations do not affect content filtering controls, firewall rules, or phishing simulations.

---

## Question 98
**Correct Answer:** A

**Explanation:**
Skip should use Secure Copy (SCP), which is a secure file transfer method. SSH is a secure command- line and login protocol, whereas HTTP is used for unencrypted web traffic. Telnet is an unencrypted command-line and login protocol.

---

## Question 99
**Correct Answer:** C

**Explanation:**
The California Online Privacy Protection Act requires that commercial websites that collect personal information from users in California conspicuously post a privacy policy. The act does not require compliance

with the EU GDPR, nor does it use the GDPR concepts of notice or choice, and it does not require encryption of all personal data.

---

## Question 100
**Correct Answer:** D

**Explanation:**
Modern recommendations from the National Institute of Standards and Technology (NIST) are that users should not be forced to change their passwords through the use of password expiration policies. More information on these recommendations can be found in NIST Special Publication (SP) 800-63B, “Digital Identity Guidelines.”

---

## Question 101
**Correct Answer:** A

**Explanation:**
This is an example of federation, where user credentials from one organization are accepted as proof of identity by another organization. The users are not creating new accounts, so there is no identity proofing, enrollment, or provisioning activity taking place.

---

## Question 102
**Correct Answer:** B

**Explanation:**
Iris scans have a longer useful life than many other types of biometric factors because they don't change throughout a person's life span (unless the eye itself is damaged). Iris scanners can be fooled in some cases by high-resolution images of an eye, and iris scanners are not significantly cheaper than other scanners.

---

## Question 103
**Correct Answer:** D

**Explanation:**
NIST 800-53 is the standard that describes the security controls mandatory for use on U.S. federal government systems. It provides a catalog of security and privacy controls for all U.S. federal information systems except those related to national security. PCI DSS is a proprietary information security standard for organizations that handle payment cards and is not specific to government systems. ISO 27001 is an international standard on how to manage information security and is not specific to U.S. federal systems. SABSA is a framework and methodology for enterprise security architecture and service management, again

not specific to the mandatory controls required by U.S. government systems.

---

## Question 104
**Correct Answer:** C

**Explanation:**
They need a key for every possible pair of users in the cryptosystem. The first key would allow communication between Matthew and Richard. The second key would allow communication between Richard and Christopher. The third key would allow communication between Christopher and Matthew.

---

## Question 105
**Correct Answer:** D

**Explanation:**
All of these controls involve the use of encryption, but only Transport Layer Security (TLS) provides a strong, effective means for protecting data in transit. Secure Sockets Layer (SSL) is an outdated method for protecting data in transit that should no longer be used. Full disk encryption (FDE) provides encryption for data at rest. The Trusted Platform Module (TPM) manages encryption keys for use in FDE.

---

## Question 106
**Correct Answer:** C

**Explanation:**
The SMTP protocol does not guarantee confidentiality between servers, making TLS or SSL between the client and server only a partial measure. Encrypting the email content can provide confidentiality; digital signatures can provide nonrepudiation.

---

## Question 107
**Correct Answer:** D

**Explanation:**
The single quotation mark in the input field is a telltale sign that this is a SQL injection attack. The quotation mark is used to escape outside the SQL code's input field, and the text following is used to directly manipulate the SQL command sent from the web application to the database.

---

## Question 108
**Correct Answer:** C

**Explanation:**
TLS provides message confidentiality and integrity, which can prevent eavesdropping. When paired with digital signatures, which provide integrity and authentication, forged assertions can also be defeated. SAML does not have a security mode and relies on TLS

and digital signatures to ensure security if needed. Message hashing without a signature would help prevent modification of the message but won't necessarily provide authentication.

---

## Question 109
**Correct Answer:** A

**Explanation:**
The goal of the business continuity planning process is to ensure that your recovery time objectives are all less than your maximum tolerable downtimes.

---

## Question 110
**Correct Answer:** C

**Explanation:**
The remediation phase of incident handling focuses on conducting a root-cause analysis to identify the factors contributing to an incident and implementing new security controls, as needed.

---

## Question 111
**Correct Answer:** A

**Explanation:**
The S/MIME secure email format uses the P7S format for encrypted email messages. If the recipient does not have a mail reader that supports S/MIME, the message will appear with an attachment named smime.p7s.

---

## Question 112
**Correct Answer:** A

**Explanation:**
Aggregation is a security issue that arises when a collection of facts has a higher classification than the classification of any of those facts standing alone. An inference problem occurs when an attacker can deduce information of greater sensitivity from a lower security level fact. SQL injection is a web application exploit. Multilevel security is a system control that allows the simultaneous processing of information at different classification levels.

---

## Question 113
**Correct Answer:** B

**Explanation:**
Polyinstantiation allows the storage of multiple different pieces of information in a database at different classification levels to prevent attackers from conducting aggregation or inference attacks. Kim could store incorrect location information in the database at lower classification levels to prevent the aggregation attack in this scenario. Input validation, server-side validation, and parameterization are all techniques

used to prevent web application attacks and are not effective against inference attacks.

---

## Question 114
**Correct Answer:** B

**Explanation:**
The tail number is a database field because it is stored in the database. It is also a primary key because the question states that the database uniquely identifies aircraft using this field. Any primary key is, by definition, also a candidate key. There is no information provided that the tail number is a foreign key used to reference a different database table.

---

## Question 115
**Correct Answer:** B

**Explanation:**
Foreign keys are used to create relationships between tables in a database. The database enforces referential integrity by ensuring that the foreign key used in a table has a corresponding record with that value as the primary key in the referenced table.

---

## Question 116
**Correct Answer:** B

**Explanation:**
The waterfall model uses an approach that develops software sequentially, spending quite a bit of time up front on the development and documentation of requirements and design. The spiral and Agile models focus on iterative development and are appropriate when requirements are not well understood or iterative development is preferred. DevOps is an approach to integrating development and operations activities and is not an SDLC model.

---

## Question 117
**Correct Answer:** A

**Explanation:**
The data owner is a senior manager who bears ultimate responsibility for data protection tasks. The data owner typically delegates this responsibility to one or more data custodians.

---

## Question 118
**Correct Answer:** D

**Explanation:**
Fuzz testing tools are designed to provide invalid or unexpected input to applications, testing for vulnerabilities like format string vulnerabilities, buffer overflow issues, and other problems. A static analysis relies on examining code without running the application or code and thus would not fill forms as part

of a web application. Brute-force tools attempt to bypass security by trying every possible combination for passwords or other values. A white box is a type of penetration test where the testers have full knowledge of the environment.

---

## Question 119
**Correct Answer:** B

**Explanation:**
Warren could use a survey or third-party assessment to evaluate the effectiveness of the campaign, but the best evidence would be provided by a phishing simulation where the organization measures user responses to simulated phishing attacks. Code reviews would not be useful in evaluating the effectiveness of antiphishing campaigns.

---

## Question 120
**Correct Answer:** B

**Explanation:**
Anomaly-based intrusion detection systems may identify a zero-day vulnerability because it deviates from normal patterns of activity. Signature-based detection methods would not be effective because there are no signatures for zero-day vulnerabilities. Strong patch management would not be helpful because, by definition, zero-day vulnerabilities do not have patches available. Full-disk encryption would not detect an attack because it is not a detective control.

---

## Question 121
**Correct Answer:** A

**Explanation:**
Whether Rob has standing to report this situation to ISC2 depends upon the canon(s) violated by the activity. This behavior violates canon II, “Act honorably, honestly, justly, responsibly, and legally.” Any member of the public may file a claim under canons I or II. Only an employer or someone with a contracting relationship with the individual may file a complaint under canon III. Anyone who is certified or licensed as a professional and subscribes to a code of ethics as part of that licensure or certification is eligible to file a canon IV complaint.

---

## Question 122
**Correct Answer:** A

**Explanation:**
The emergency response guidelines should include the immediate steps an organization should follow in

response to an emergency situation. These include immediate response procedures, a list of individuals who should be notified of the emergency, and secondary response procedures for incident responders. They do not include long-term actions such as activating business continuity protocols, ordering equipment, or activating disaster recovery sites.

---

## Question 123
**Correct Answer:** D

**Explanation:**
An access control vestibule (or mantrap) uses two sets of doors, only one of which can open at a time. An access control vestibule is a type of preventive access control, although its implementation is a physical control.

---

## Question 124
**Correct Answer:** B

**Explanation:**
RAID level 5 is also known as disk striping with parity. It uses three or more disks, with the equivalent of one disk containing parity information used to restore data to another disk in the event of failure. When used with three disks, RAID 5 is able to withstand the loss of a single disk.

---

## Question 125
**Correct Answer:** See Explanation

**Explanation:**
The SOC levels match the report descriptions as follows: 1. SOC 1, Type 1: D. A report that provides the auditor's opinions of financial statements about controls at the service organization and that includes a report on the opinion on the presentation of the service organization's system as well as suitability of the controls 2. SOC 1, Type 2: C. A report that provides an assessment of the risk of material misstatement of financial statement assertions affected by the service organization's processing and that includes a description of the service auditor's tests of the controls and the results of the tests and their effectiveness

3. SOC 2: B. A report that provides predefined, standard benchmarks for controls involving confidentiality, availability, integrity, and privacy of a system and the information it contains, generally for restricted use 4. SOC 3: A. A general use report that reports on the effectiveness of controls related to compliance and/or operations

---

