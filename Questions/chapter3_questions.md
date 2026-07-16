# CISSP Practice Tests - Chapter 3: Security Architecture and Engineering (Domain 3)

## Question 1
Matthew is the security administrator for a consulting firm and must enforce access controls that restrict users' access based upon their previous activity. For example, once a consultant accesses data belonging to Acme Cola, a consulting client, they may no longer access data belonging to any of Acme's competitors. What security model best fits Matthew's needs?

* [ ] **A.** Clark-Wilson
* [ ] **B.** Biba
* [ ] **C.** Bell-LaPadula
* [ ] **D.** Brewer-Nash

## Question 2
Referring to the figure shown here, what is the earliest stage of a fire where it is possible to use detection technology to identify it?

![Diagram](https://raw.githubusercontent.com/SSMGFT/SOMETHING/main/Assets/chapter3_images/img_page_103_1870.png)

* [ ] **A.** Incipient
* [ ] **B.** Smoke
* [ ] **C.** Flame
* [ ] **D.** Heat

## Question 3
Ralph is designing a physical security infrastructure for a new computing facility that will remain largely unstaffed. He plans to implement motion detectors in the facility but would also like to include a secondary verification control for physical presence. Which one of the following would best meet his needs?

* [ ] **A.** CCTV
* [ ] **B.** IPS
* [ ] **C.** Turnstiles
* [ ] **D.** Faraday cages

## Question 4
Harry would like to retrieve a lost encryption key from a database that uses m of n control, with m = 4 and n = 8. What is the minimum number of escrow agents required to retrieve the key?

* [ ] **A.** 2
* [ ] **B.** 4
* [ ] **C.** 8
* [ ] **D.** 12

## Question 5
Fran's company is considering purchasing a web-based email service from a vendor and eliminating its own email server environment as a cost-saving measure. What type of cloud computing environment is Fran's company considering?

* [ ] **A.** SaaS
* [ ] **B.** IaaS
* [ ] **C.** CaaS
* [ ] **D.** PaaS

## Question 6
Bob is a security administrator with the U.S. federal government and wants to choose a digital signature approach that is an approved part of the federal Digital Signature Standard under FIPS 186-5. Which one of the following encryption algorithms is not an acceptable choice for use in digital signatures?

* [ ] **A.** EdDSA
* [ ] **B.** HAVAL
* [ ] **C.** RSA
* [ ] **D.** ECDSA

## Question 7
Harry would like to access a document owned by Sally and stored on a file server. Applying the subject/object model to this scenario, who or what is the subject of the resource request?

* [ ] **A.** Harry
* [ ] **B.** Sally
* [ ] **C.** Server
* [ ] **D.** Document

## Question 8
Michael is responsible for forensic investigations and is investigating a medium-severity security incident that involved the defacement of a corporate website. The web server in question ran on a virtualization platform, and the marketing team would like to get the website up and running as quickly as possible. What would be the most reasonable next step for Michael to take?

* [ ] **A.** Keep the website offline until the investigation is complete.
* [ ] **B.** Take the virtualization platform offline as evidence.
* [ ] **C.** Take a snapshot of the compromised system and use that for the investigation.
* [ ] **D.** Ignore the incident and focus on quickly restoring the website.

## Question 9
Helen is a software engineer and is developing code that she would like to restrict to running within an isolated sandbox for security purposes. What software development technique is Helen using?

* [ ] **A.** Bounds
* [ ] **B.** Input validation
* [ ] **C.** Confinement
* [ ] **D.** TCB

## Question 10
What concept describes the degree of confidence that an organization has that its controls satisfy security requirements?

* [ ] **A.** Trust
* [ ] **B.** Credentialing
* [ ] **C.** Verification
* [ ] **D.** Assurance

## Question 11
What type of security vulnerability are developers most likely to introduce into code when they seek to facilitate their own access, for testing purposes, to software they developed?

* [ ] **A.** Maintenance hook
* [ ] **B.** Cross-site scripting
* [ ] **C.** SQL injection
* [ ] **D.** Buffer overflow

## Question 12
In the figure shown here, Sally is blocked from reading the file due to the Biba integrity model. Sally has a Secret security clearance, and the file has a Confidential classification. What principle of the Biba model is being enforced?

![Diagram](https://raw.githubusercontent.com/SSMGFT/SOMETHING/main/Assets/chapter3_images/img_page_106_1874.png)

* [ ] **A.** Simple Security Property
* [ ] **B.** Simple Integrity Property
* [ ] **C.** *-Security Property
* [ ] **D.** *-Integrity Property

## Question 13
Tom is responsible for maintaining the security of systems used to control industrial processes located within a power plant. What term is used to describe these systems?

* [ ] **A.** POWER
* [ ] **B.** SCADA
* [ ] **C.** HAVAL
* [ ] **D.** COBOL

## Question 14
Sonia recently removed an encrypted hard drive from a laptop and moved it to a new device because of a hardware failure. She is having difficulty accessing encrypted content on the drive despite that she knows the user's password. What hardware security feature is likely causing this problem?

* [ ] **A.** TCB
* [ ] **B.** TPM
* [ ] **C.** NIACAP
* [ ] **D.** RSA

## Question 15
Chris wants to verify that a software package that he downloaded matches the original version. What hashing tool should he use if he believes that technically sophisticated attackers may have replaced the software package with a version containing a backdoor?

* [ ] **A.** MD5
* [ ] **B.** 3DES
* [ ] **C.** SHA1
* [ ] **D.** SHA 256

### Scenario Context
> For questions 16–19, please refer to the following scenario: Alice and Bob would like to use an asymmetric cryptosystem to communicate with each other. They are located in different parts of the country but have exchanged encryption keys by using digital certificates signed by a mutually trusted certificate authority.

---

## Question 16
If Alice wants to send Bob a message that is encrypted for confidentiality, what key does she use to encrypt the message?

* [ ] **A.** Alice's public key
* [ ] **B.** Alice's private key
* [ ] **C.** Bob's public key
* [ ] **D.** Bob's private key

## Question 17
When Bob receives the encrypted message from Alice, what key does he use to decrypt the message's plaintext content?

* [ ] **A.** Alice's public key
* [ ] **B.** Alice's private key
* [ ] **C.** Bob's public key
* [ ] **D.** Bob's private key

## Question 18
Which one of the following keys would Bob not possess in this scenario?

* [ ] **A.** Alice's public key
* [ ] **B.** Alice's private key
* [ ] **C.** Bob's public key
* [ ] **D.** Bob's private key

## Question 19
Alice would also like to digitally sign the message that she sends to Bob. What key should she use to create the digital signature?

* [ ] **A.** Alice's public key
* [ ] **B.** Alice's private key
* [ ] **C.** Bob's public key
* [ ] **D.** Bob's private key

## Question 20
What name is given to the random value added to a password in an attempt to defeat rainbow table attacks?

* [ ] **A.** Hash
* [ ] **B.** Salt
* [ ] **C.** Extender
* [ ] **D.** Rebar

## Question 21
Which one of the following is not an attribute of a typical hashing algorithm?

* [ ] **A.** They require a cryptographic key.
* [ ] **B.** They are irreversible.
* [ ] **C.** It is very difficult to find two messages with the same hash value.
* [ ] **D.** They take variable-length input.

## Question 22
What type of fire suppression system fills with water after a valve opens when the initial stages of a fire are detected and then requires a sprinkler head heat activation before dispensing water?

* [ ] **A.** Wet pipe
* [ ] **B.** Dry pipe
* [ ] **C.** Deluge
* [ ] **D.** Preaction

## Question 23
Susan would like to configure IPsec in a manner that provides confidentiality for the content of packets. What component of IPsec provides this capability?

* [ ] **A.** AH
* [ ] **B.** ESP
* [ ] **C.** IKE
* [ ] **D.** ISAKMP

## Question 24
Which one of the following cryptographic goals protects against the risks posed when a device is lost or stolen?

* [ ] **A.** Nonrepudiation
* [ ] **B.** Authentication
* [ ] **C.** Integrity
* [ ] **D.** Confidentiality

## Question 25
Joanna wants to review the status of the industrial control systems her organization uses for building control. What type of systems should she inquire about access to?

* [ ] **A.** SCADA
* [ ] **B.** DSS
* [ ] **C.** BAS
* [ ] **D.** ICS-CSS

## Question 26
In the figure shown here, Harry's request to write to the data file is blocked. Harry has a Secret security clearance, and the data file has a Confidential classification. What principle of the Bell-LaPadula model blocked this request?

![Diagram](https://raw.githubusercontent.com/SSMGFT/SOMETHING/main/Assets/chapter3_images/img_page_111_1880.png)

* [ ] **A.** Simple Security Property
* [ ] **B.** Simple Integrity Property
* [ ] **C.** *-Security Property
* [ ] **D.** Discretionary Security Property

## Question 27
Florian and Tobias would like to begin communicating using a symmetric cryptosystem, but they have no prearranged secret and are not able to meet in person to exchange keys. What algorithm can they use to securely exchange the secret key?

* [ ] **A.** IDEA
* [ ] **B.** Diffie-Hellman
* [ ] **C.** RSA
* [ ] **D.** MD5

## Question 28
Carl's organization recently underwent a user access review. At the conclusion of the review, the auditors noted several cases of privilege creep. What security principle was violated?

* [ ] **A.** Fail securely
* [ ] **B.** Keep it simple and secure
* [ ] **C.** Trust but verify
* [ ] **D.** Least privilege

## Question 29
Matt's organization recently adopted a zero trust network architecture. Under this approach, which one of the following criteria would be LEAST appropriate to use when granting a subject access to resources?

* [ ] **A.** Password
* [ ] **B.** Two-factor authentication
* [ ] **C.** IP address
* [ ] **D.** Biometric scan

## Question 30
Colin is the chief privacy officer for a nonprofit organization and is assisting with the team's transition to a Privacy by Design approach. Under this approach, which is not one of the Privacy by Design principles?

* [ ] **A.** Proactive, not reactive
* [ ] **B.** Privacy as the default setting
* [ ] **C.** End-to-end security
* [ ] **D.** Defense in depth

## Question 31
What cryptographic principle stands behind the idea that cryptographic algorithms should be open to public inspection?

* [ ] **A.** Security through obscurity
* [ ] **B.** Kerckhoffs' principle
* [ ] **C.** Defense in depth
* [ ] **D.** Heisenburg principle

## Question 32
Ryan is developing a physical access plan for his organization's data center and wants to implement the security control indicated by the arrow in this diagram. What is the name of this control?

![Diagram](https://raw.githubusercontent.com/SSMGFT/SOMETHING/main/Assets/chapter3_images/img_page_113_1883.png)

* [ ] **A.** Access control vestibule
* [ ] **B.** Turnstile
* [ ] **C.** Intrusion prevention system
* [ ] **D.** Portal

## Question 33
Which one of the following does not describe a standard physical security requirement for wiring closets?

* [ ] **A.** Place only in areas monitored by security guards.
* [ ] **B.** Do not store flammable items in the closet.
* [ ] **C.** Use sensors on doors to log entries.
* [ ] **D.** Perform regular inspections of the closet.

## Question 34
In the figure shown here, Sally is blocked from writing to the data file by the Biba integrity model. Sally has a Secret security clearance, and the file is classified Top Secret. What principle is preventing her from writing to the file?

![Diagram](https://raw.githubusercontent.com/SSMGFT/SOMETHING/main/Assets/chapter3_images/img_page_114_1885.png)

* [ ] **A.** Simple Security Property
* [ ] **B.** Simple Integrity Property
* [ ] **C.** *-Security Property
* [ ] **D.** *-Integrity Property

## Question 35
Lana recently implemented a new process in her organization where managers who are responsible for granting users access to a system are not permitted to participate in access reviews. What principle is she enforcing?

* [ ] **A.** Two-person control
* [ ] **B.** Least privilege
* [ ] **C.** Privilege creep
* [ ] **D.** Segregation of duties

## Question 36
Which of the following statements about system development are correct? (Select all that apply.)

* [ ] **A.** Systems should be designed to operate in a secure manner if the user performs no other configuration.
* [ ] **B.** Systems should be designed to fall back to a secure state if they experience an error.
* [ ] **C.** Systems should be designed to incorporate security as a design feature.
* [ ] **D.** Systems should be designed in a manner that keeps their functionality as simple as possible.

## Question 37
Alan is reviewing a system that has been assigned the EAL1 evaluation assurance level under the Common Criteria. What is the degree of assurance that he may have about the system?

* [ ] **A.** It has been functionally tested.
* [ ] **B.** It has been structurally tested.
* [ ] **C.** It has been formally verified, designed, and tested.
* [ ] **D.** It has been methodically designed, tested, and reviewed.

## Question 38
Jake works for a research organization that is seeking to deploy a grid computing system that will perform cycle scavenging on user workstations to conduct research tasks that require high-performance computing. What is the most significant risk associated with this operation?

* [ ] **A.** Data confidentiality
* [ ] **B.** Isolation breach
* [ ] **C.** Data integrity
* [ ] **D.** Data availability

## Question 39
Eimear's software development team uses an approach that creates many discrete software objects and then binds them together using APIs. What term best describes this architecture?

* [ ] **A.** Microservices
* [ ] **B.** Function-as-a-service
* [ ] **C.** Containerization
* [ ] **D.** Virtualization

## Question 40
Adam recently configured permissions on an NTFS filesystem to describe the access that different users may have to a file by listing each user individually. What did Adam create?

* [ ] **A.** An access control list
* [ ] **B.** An access control entry
* [ ] **C.** Role-based access control
* [ ] **D.** Mandatory access control

## Question 41
Betty is concerned about the use of buffer overflow attacks against a custom application developed for use in her organization. What security control would provide the strongest defense against these attacks?

* [ ] **A.** Firewall
* [ ] **B.** Intrusion detection system
* [ ] **C.** Parameter checking
* [ ] **D.** Vulnerability scanning

## Question 42
Which one of the following combinations of controls best embodies the defense-in-depth principle?

* [ ] **A.** Encryption of email and network intrusion detection
* [ ] **B.** Cloud access security brokers (CASBs) and security awareness training
* [ ] **C.** Data loss prevention and multifactor authentication
* [ ] **D.** Network firewall and host firewall

## Question 43
James is working with a Department of Defense system that is authorized to simultaneously handle information classified at the Secret and Top Secret levels. What type of system is he using?

* [ ] **A.** Single state
* [ ] **B.** Unclassified
* [ ] **C.** Compartmented
* [ ] **D.** Multistate

## Question 44
Kyle is being granted access to a military computer system that uses System High mode. What is not true about Kyle's security clearance requirements?

* [ ] **A.** Kyle must have a clearance for the highest level of classification processed by the system, regardless of his access.
* [ ] **B.** Kyle must have access approval for all information processed by the system.
* [ ] **C.** Kyle must have a valid need to know for all information processed by the system.
* [ ] **D.** Kyle must have a valid security clearance.

## Question 45
Gary intercepts a communication between two individuals and suspects that they are exchanging secret messages. The content of the communication appears to be the image shown here. What type of technique may the individuals use to hide messages inside this image? Source: Matt65 / Wikimedia Commons / Public domain.

![Diagram](https://raw.githubusercontent.com/SSMGFT/SOMETHING/main/Assets/chapter3_images/img_page_118_1890.png)

* [ ] **A.** Visual cryptography
* [ ] **B.** Steganography
* [ ] **C.** Cryptographic hashing
* [ ] **D.** Transport layer security

## Question 46
Philip is developing a new security tool that will be used by individuals in many different subsidiaries of his organization. He chooses to use Docker to deploy the tool to simplify configuration. What term best describes this approach?

* [ ] **A.** Virtualization
* [ ] **B.** Abstraction
* [ ] **C.** Simplification
* [ ] **D.** Containerization

## Question 47
In the ring protection model shown here, what ring contains the operating system's kernel?

![Diagram](https://raw.githubusercontent.com/SSMGFT/SOMETHING/main/Assets/chapter3_images/img_page_119_1893.png)

* [ ] **A.** Ring 0
* [ ] **B.** Ring 1
* [ ] **C.** Ring 2
* [ ] **D.** Ring 3

## Question 48
In an infrastructure-as-a-service environment where a vendor supplies a customer with access to storage services, who is normally responsible for removing sensitive data from drives that are taken out of service?

* [ ] **A.** Customer's security team
* [ ] **B.** Customer's storage team
* [ ] **C.** Customer's vendor management team
* [ ] **D.** Vendor

## Question 49
During a system audit, Casey notices that the private key for her organization's web server has been stored in a public Amazon S3 storage bucket for more than a year. Which one of the following actions should she take first?

* [ ] **A.** Remove the key from the bucket.
* [ ] **B.** Notify all customers that their data may have been exposed.
* [ ] **C.** Request a new certificate using a new key.
* [ ] **D.** Nothing, because the private key should be accessible for validation.

## Question 50
Which one of the following systems assurance processes provides an independent third-party evaluation of a system's controls that may be trusted by many different organizations?

* [ ] **A.** Certification
* [ ] **B.** Definition
* [ ] **C.** Verification
* [ ] **D.** Accreditation

## Question 51
Darcy's organization is deploying serverless computing technology to better meet the needs of developers and users. In a serverless model, who is normally responsible for configuring operating system security controls?

* [ ] **A.** Software developer
* [ ] **B.** Cybersecurity professional
* [ ] **C.** Cloud architect
* [ ] **D.** Vendor

## Question 52
Harold is assessing the susceptibility of his environment to hardware failures and would like to identify the expected lifetime of a piece of hardware. What measure should he use for this?

* [ ] **A.** MTTR
* [ ] **B.** MTTF
* [ ] **C.** RTO
* [ ] **D.** MTO

## Question 53
Chris is designing a cryptographic system for use within his company. The company has 1,000 employees, and they plan to use an asymmetric encryption system. They would like the system to be set up so that any pair of arbitrary users may communicate privately. How many total keys will they need?

* [ ] **A.** 500
* [ ] **B.** 1,000
* [ ] **C.** 2,000
* [ ] **D.** 499,500

## Question 54
Gary is concerned about applying consistent security settings to the many mobile devices used throughout his organization. What technology would best assist with this challenge?

* [ ] **A.** MDM
* [ ] **B.** IPS
* [ ] **C.** IDS
* [ ] **D.** SIEM

## Question 55
Alice sent a message to Bob. Bob would like to demonstrate to Charlie that the message he received definitely came from Alice. What goal of cryptography is Bob attempting to achieve?

* [ ] **A.** Authentication
* [ ] **B.** Confidentiality
* [ ] **C.** Nonrepudiation
* [ ] **D.** Integrity

## Question 56
Rhonda is considering the use of new identification cards for physical access control in her organization. She comes across a military system that uses the card shown here. What type of card is this?

![Diagram](https://raw.githubusercontent.com/SSMGFT/SOMETHING/main/Assets/chapter3_images/img_page_123_1898.png)

* [ ] **A.** Smart card
* [ ] **B.** Proximity card
* [ ] **C.** Magnetic stripe card
* [ ] **D.** Phase three card

## Question 57
Gordon is concerned about the possibility that hackers may be able to use the Van Eck radiation phenomenon to remotely read the contents of computer monitors in a restricted work area within his facility. What technology would protect against this type of attack?

* [ ] **A.** TCSEC
* [ ] **B.** SCSI
* [ ] **C.** GHOST
* [ ] **D.** TEMPEST

## Question 58
Jorge believes that an attacker has obtained the hash of the Kerberos service account from one of his organization's Active Directory servers. What type of attack would this enable?

* [ ] **A.** Golden ticket
* [ ] **B.** Kerberoasting
* [ ] **C.** Pass the ticket
* [ ] **D.** Brute force

## Question 59
Sherry conducted an inventory of the cryptographic technologies in use within her organization and found the following algorithms and protocols in use. Which one of these technologies should she replace because it is no longer considered secure?

* [ ] **A.** MD5
* [ ] **B.** AES
* [ ] **C.** PGP
* [ ] **D.** WPA3

## Question 60
Robert is investigating a security breach and discovers the Mimikatz tool installed on a system in his environment. What type of attack has likely taken place?

* [ ] **A.** Password cracking
* [ ] **B.** Pass the hash
* [ ] **C.** MAC spoofing
* [ ] **D.** ARP poisoning

## Question 61
Tom is a cryptanalyst and is working on breaking a cryptographic algorithm's secret key. He has a copy of an intercepted message that is encrypted, and he also has a copy of the decrypted version of that message. He wants to use both the encrypted message and its decrypted plaintext to retrieve the secret key for use in decrypting other messages. What type of attack is Tom engaging in?

* [ ] **A.** Chosen ciphertext
* [ ] **B.** Chosen plaintext
* [ ] **C.** Known plaintext
* [ ] **D.** Brute force

## Question 62
A hacker recently violated the integrity of data in James's company by modifying a file using a precise timing attack. The attacker waited until James verified the integrity of a file's contents using a hash value and then modified the file between the time that James verified the integrity and read the contents of the file. What type of attack took place?

* [ ] **A.** Social engineering
* [ ] **B.** TOCTOU
* [ ] **C.** Data diddling
* [ ] **D.** Parameter checking

## Question 63
Carl is deploying a set of video sensors that will be placed in remote locations as part of a research project. Because of connectivity limitations, he would like to perform as much image processing and computation as possible on the device itself before sending results back to the cloud for further analysis. What computing model would best meet his needs?

* [ ] **A.** Serverless computing
* [ ] **B.** Edge computing
* [ ] **C.** IaaS computing
* [ ] **D.** SaaS computing

## Question 64
What action can you take to prevent accidental data disclosure due to wear leveling on an SSD device before reusing the drive?

* [ ] **A.** Reformatting
* [ ] **B.** Disk encryption
* [ ] **C.** Degaussing
* [ ] **D.** Physical destruction

## Question 65
Johnson Widgets strictly limits access to total sales volume information, classifying it as a competitive secret. However, shipping clerks have unrestricted access to order records to facilitate transaction completion. A shipping clerk recently pulled all of the individual sales records for a quarter from the database and totaled them up to determine the total sales volume. What type of attack occurred?

* [ ] **A.** Social engineering
* [ ] **B.** Inference
* [ ] **C.** Aggregation
* [ ] **D.** Data diddling

## Question 66
What physical security control broadcasts false emanations constantly to mask the presence of true electromagnetic emanations from computing equipment?

* [ ] **A.** Faraday cage
* [ ] **B.** Copper-infused windows
* [ ] **C.** Shielded cabling
* [ ] **D.** White noise

## Question 67
In a software-as-a-service cloud computing environment, who is normally responsible for ensuring that appropriate firewall controls are in place to protect the application?

* [ ] **A.** Customer's security team
* [ ] **B.** Vendor
* [ ] **C.** Customer's networking team
* [ ] **D.** Customer's infrastructure management team

## Question 68
Alice has read permissions on an object, and she would like Bob to have those same rights. Which one of the rules in the Take-Grant protection model would allow her to complete this operation?

* [ ] **A.** Create rule
* [ ] **B.** Remove rule
* [ ] **C.** Grant rule
* [ ] **D.** Take rule

## Question 69
As part of his incident response process, Charles securely wipes the drive of a compromised machine and reinstalls the operating system (OS) from original media. Once he is done, he patches the machine fully and applies his organization's security templates before reconnecting the system to the network. Almost immediately after the system is returned to service, he discovers that it has reconnected to the same botnet it was part of before. Where should Charles look for the malware that is causing this behavior?

* [ ] **A.** The operating system partition
* [ ] **B.** The system BIOS or firmware
* [ ] **C.** The system memory
* [ ] **D.** The installation media

## Question 70
Lauren implements ASLR to help prevent system compromises. What technique has she used to protect her system?

* [ ] **A.** Encryption
* [ ] **B.** Mandatory access control
* [ ] **C.** Memory address randomization
* [ ] **D.** Discretionary access control

## Question 71
Alan intercepts an encrypted message and wants to determine what type of algorithm was used to create the message. He first performs a frequency analysis and notes that the frequency of letters in the message closely matches the distribution of letters in the English language. What type of cipher was most likely used to create this message?

* [ ] **A.** Substitution cipher
* [ ] **B.** AES
* [ ] **C.** Transposition cipher
* [ ] **D.** 3DES

## Question 72
In a zero trust network architecture, what component is responsible for making policy decisions based upon rules and external data sources?

* [ ] **A.** Policy engine
* [ ] **B.** Policy administrator
* [ ] **C.** Policy enforcement point
* [ ] **D.** Subject

## Question 73
Grace would like to implement application control technology in her organization. Users often need to install new applications for research and testing purposes, and she does not want to interfere with that process. At the same time, she would like to block the use of known malicious software. What type of application control would be appropriate in this situation?

* [ ] **A.** Blacklisting
* [ ] **B.** Graylisting
* [ ] **C.** Whitelisting
* [ ] **D.** Bluelisting

## Question 74
Warren is designing a physical intrusion detection system for use in a sensitive media storage facility and wants to include technology that issues an alert if the communications lines for the alarm system are unexpectedly cut. What technology would meet this requirement?

* [ ] **A.** Heartbeat sensor
* [ ] **B.** Emanation security
* [ ] **C.** Motion detector
* [ ] **D.** Faraday cage

## Question 75
John and Gary are negotiating a business transaction, and John must demonstrate to Gary that he has access to a system. He engages in an electronic version of the “magic door” scenario shown here. What technique is John using?

![Diagram](https://raw.githubusercontent.com/SSMGFT/SOMETHING/main/Assets/chapter3_images/img_page_130_1906.png)

* [ ] **A.** Split-knowledge proof
* [ ] **B.** Zero-knowledge proof
* [ ] **C.** Logical proof
* [ ] **D.** Mathematical proof

## Question 76
After scanning all of the systems on his wireless network, Mike notices that one system is identified as an iOS device running a massively out-of-date version of Apple's mobile operating system. When he investigates further, he discovers that the device is an original iPad and that it cannot be updated to a current secure version of the operating system. What would be the best option for handling this device?

* [ ] **A.** Retire or replace the device.
* [ ] **B.** Isolate the device on a dedicated wireless network.
* [ ] **C.** Install a firewall on the tablet.
* [ ] **D.** Reinstall the OS.

## Question 77
Tonya believes that an attacker was able to eavesdrop on legitimate HTTPS communications between her users and remote web servers by engaging in a DNS poisoning attack. After conducting DNS poisoning, what technique would an attacker likely use to conduct this eavesdropping?

* [ ] **A.** Man-in-the-middle
* [ ] **B.** Brute-force
* [ ] **C.** Timing
* [ ] **D.** Meet-in-the-middle

## Question 78
Howard is choosing a cryptographic algorithm for his organization, and he would like to choose an algorithm that supports the creation of digital signatures. Which one of the following algorithms would meet his requirement?

* [ ] **A.** RSA
* [ ] **B.** 3DES
* [ ] **C.** AES
* [ ] **D.** Blowfish

## Question 79
Laura is responsible for securing her company's web- based applications and wants to conduct an educational program for developers on common web application security vulnerabilities. Where can she turn for a concise listing of the most common web application issues?

* [ ] **A.** CVE
* [ ] **B.** NSA
* [ ] **C.** OWASP
* [ ] **D.** CSA

## Question 80
The Bell-LaPadula and Biba models implement state machines in a fashion that uses what specific state machine model?

* [ ] **A.** Information flow
* [ ] **B.** Noninterference
* [ ] **C.** Cascading
* [ ] **D.** Feedback

## Question 81
During a third-party vulnerability scan and security test, Danielle's employer recently discovered that the embedded systems that were installed to manage her company's new buildings have a severe remote access vulnerability. The manufacturer has gone out of business, and there is no patch or update for the devices. What should Danielle recommend that her employer do about the hundreds of devices that are vulnerable?

* [ ] **A.** Identify a replacement device model and replace every device.
* [ ] **B.** Turn off all of the devices.
* [ ] **C.** Move the devices to a secure and isolated network segment.
* [ ] **D.** Reverse engineer the devices and build an in-house patch.

## Question 82
What type of motion detector senses changes in the electromagnetic fields in monitored areas?

* [ ] **A.** Infrared
* [ ] **B.** Wave pattern
* [ ] **C.** Capacitance
* [ ] **D.** Photoelectric

## Question 83
Mike has been tasked with preventing an outbreak of malware like Mirai, a botnet that targeted IP-based cameras and routers. What type of systems should be protected in his organization?

* [ ] **A.** Servers
* [ ] **B.** SCADA
* [ ] **C.** Mobile devices
* [ ] **D.** Internet of Things (IoT) devices

## Question 84
Which one of the following statements is correct about the Biba model of access control?

* [ ] **A.** It addresses confidentiality and integrity.
* [ ] **B.** It addresses integrity and availability.
* [ ] **C.** It prevents covert channel attacks.
* [ ] **D.** It focuses on protecting objects from integrity threats.

## Question 85
In Transport Layer Security, what type of key is used to encrypt the actual content of communications between a web server and a client?

* [ ] **A.** Ephemeral session key
* [ ] **B.** Client's public key
* [ ] **C.** Server's public key
* [ ] **D.** Server's private key

## Question 86
Beth would like to include technology in a secure area of her data center to protect against unwanted electromagnetic emanations. What technology would assist her with this goal?

* [ ] **A.** Heartbeat sensor
* [ ] **B.** Faraday cage
* [ ] **C.** Piggybacking
* [ ] **D.** WPA2

## Question 87
In a virtualized computing environment, what component is responsible for enforcing separation between guest machines?

* [ ] **A.** Guest operating system
* [ ] **B.** Hypervisor
* [ ] **C.** Kernel
* [ ] **D.** Protection manager

## Question 88
Rick is an application developer who works primarily in Python. He recently decided to evaluate a new service where he provides his Python code to a vendor who then executes it on their server environment. What type of cloud computing environment is this service?

* [ ] **A.** SaaS
* [ ] **B.** PaaS
* [ ] **C.** IaaS
* [ ] **D.** CaaS

## Question 89
A component failure in the primary HVAC system leads to a high temperature alarm in the data center that Kim manages. After resolving the issue, what should Kim consider to prevent future issues like this?

* [ ] **A.** A closed loop chiller
* [ ] **B.** Redundant cooling systems
* [ ] **C.** Swamp coolers
* [ ] **D.** Relocating the data center to a colder climate

## Question 90
Tommy is planning to implement a power conditioning UPS for a rack of servers in his data center. Which one of the following conditions will the UPS be unable to protect against if it persists for an extended period of time?

* [ ] **A.** Fault
* [ ] **B.** Blackout
* [ ] **C.** Sag
* [ ] **D.** Noise

## Question 91
Which one of the following humidity values is within the acceptable range for a data center operation?

* [ ] **A.** 0%
* [ ] **B.** 10%
* [ ] **C.** 15%
* [ ] **D.** 40%

## Question 92
Kristen's organization suffered a ransomware infection and has lost access to critical business data. She is considering paying the ransom to regain access to her data. Which of the following statements about this payment are correct? (Select all that apply.)

* [ ] **A.** Payment of the ransom may be illegal.
* [ ] **B.** Payment of the ransom may result in further demands for payments.
* [ ] **C.** Payment of the ransom guarantees access to the decryption key.
* [ ] **D.** Payment of the ransom may cause a data breach.

## Question 93
Alex's employer creates most of their work output as PDF files. Alex is concerned about limiting the audience for the PDF files to those individuals who have paid for them. What technology can he use to most effectively control the access to and distribution of these files?

* [ ] **A.** EDM
* [ ] **B.** Encryption
* [ ] **C.** Digital signatures
* [ ] **D.** DRM

## Question 94
As part of his team's forensic investigation process, Matt signs out drives and other evidence from an evidence storage facility before working with them. What type of documentation is he creating?

* [ ] **A.** Criminal
* [ ] **B.** Chain of custody
* [ ] **C.** Civil
* [ ] **D.** CYA

## Question 95
Todd believes that a digital certificate used by his organization has been compromised, and he wants to add it to the certificate revocation list (CRL). What element of the certificate goes on the CRL?

* [ ] **A.** Serial number
* [ ] **B.** Public key
* [ ] **C.** Digital signature
* [ ] **D.** Private key

## Question 96
Alison is examining a digital certificate presented to her by her bank's website. Which one of the following requirements is not necessary for her to trust the digital certificate?

* [ ] **A.** She knows that the server belongs to the bank.
* [ ] **B.** She trusts the certificate authority.
* [ ] **C.** She verifies that the certificate is not listed on a CRL.
* [ ] **D.** She verifies the digital signature on the certificate.

## Question 97
Which one of the following is an example of a covert timing channel when used to exfiltrate information from an organization?

* [ ] **A.** Sending an electronic mail message
* [ ] **B.** Posting a file on a peer-to-peer file sharing service
* [ ] **C.** Typing with the rhythm of Morse code
* [ ] **D.** Writing data to a shared memory space

## Question 98
Which one of the following would be a reasonable application for the use of self-signed digital certificates?

* [ ] **A.** Digital commerce website
* [ ] **B.** Banking application
* [ ] **C.** Internal scheduling application
* [ ] **D.** Customer portal

## Question 99
Ron is investigating a security incident that took place at a highly secure government facility. He believes that encryption keys were stolen during the attack and finds evidence that the attackers used dry ice to freeze an encryption component. What type of attack was likely attempted?

* [ ] **A.** Side channel attack
* [ ] **B.** Brute-force attack
* [ ] **C.** Timing attack
* [ ] **D.** Fault injection attack

## Question 100
Match the following numbered security models with the appropriate lettered security descriptions: Security models: 1. Clark-Wilson 2. Bell-LaPadula 3. Biba Descriptions:

* [ ] **A.** This model blocks lower-classified objects from accessing higher-classified objects, thus ensuring confidentiality.
* [ ] **B.** The * property of this model can be summarized as “no write-up.”
* [ ] **C.** This model uses security labels to grant access to objects via transformation procedures and a restricted interface model.

## Question 101
Match each of these following numbered architecture security concepts with the appropriate lettered description: Architectural security concepts: 1. Time of check 2. Covert channel 3. Time of use 4. Maintenance hooks 5. Parameter checking 6. Race condition Descriptions:

* [ ] **A.** A method used to pass information over a path not normally used for communication
* [ ] **B.** The exploitation of the reliance of a system's behavior on the sequence of events that occur externally
* [ ] **C.** The time at which the subject checks whether an object is available
* [ ] **D.** The time at which a subject can access an object E. An access method known only to the developer of the system F. A method that can help prevent buffer overflow attacks

