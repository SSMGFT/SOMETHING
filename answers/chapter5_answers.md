# CISSP Practice Tests - Chapter 5: Identity and Access Management (Domain 5) Answer Key

## Question 1
**Correct Answer:** B

**Explanation:**
Single sign-on provides a single authentication process to allow authorization to multiple services. An access control list, or ACL, is a ruleset used to determine if a subject can gain access to a service or system. Multifactor requires multiple factors, and the specifics of how Henry logged in were not discussed in the question. Finally, role-based access control uses a subject's role(s) to determine if they can access a service or system, and no mention of roles was made.

---

## Question 2
**Correct Answer:** B

**Explanation:**
Since Jim's organization is using a cloud-based identity as a service solution, a third-party, on-premises identity service can provide the ability to integrate with the IDaaS solution, and the company's use of Active Directory is widely supported by third-party vendors. OAuth is used to log in to third-party websites using existing credentials and would not meet the needs described. SAML is a markup language and would not meet the full set of AAA needs. Since the organization is using Active Directory, a custom in-house solution is unlikely to be as effective as a preexisting third-party solution and may take far more time and expense to implement.

---

## Question 3
**Correct Answer:** D

**Explanation:**
A policy enforcement point in a zero trust environment receives authorization requests and then sends them to the policy decision point. They are used anywhere that authorization controls are needed. They do not make decisions for the policy engine, can exist beyond workstations and mobile devices, and use policies set at the zero trust control layer rather than just at the endpoint device.

---

## Question 4
**Correct Answer:** C

**Explanation:**
Voice pattern recognition is “something you are,” a biometric authentication factor, because it measures a physical characteristic of the individual authenticating.

---

## Question 5
**Correct Answer:** B

**Explanation:**
Susan has used two distinct types of factors: the PIN and password are both Type 1 factors, and the retina scan is a Type 3 factor. Her username is not a factor.

---

## Question 6
**Correct Answer:** C

**Explanation:**
Hardware Security Modules, or HSMs, are the most secure way to store keys associated with a CMS. They provide enhanced key management capabilities and are often required to be FIPS certified. In addition to these advantages, an HSM can improve cryptographic performance for the organization due to dedicated hardware designed for just that purpose. Long keys and using AES-256 are good practices, but an HSM provides greater security and will require appropriate cryptographic controls already. Changing passphrases can be challenging across an organization; instead, securing the passphrases and keys is more important and reasonable for most organizations.

---

## Question 7
**Correct Answer:** B

**Explanation:**
Brian's organization is using a federated identity management approach where multiple organizations allow identities to be used across the organizations. Each organization needs to conduct identity proofing of their own staff members' identities and provide them with rights and role information that will allow them to use resources within the federated identity environment.

---

## Question 8
**Correct Answer:** A

**Explanation:**
Authentication that takes attributes such as location, device, and time of day into account is context-aware authentication. This allows organizations to make choices about whether the authentication is appropriate and allowed in addition to the use of credentials. The decision is based on contextual information, not user knowledge or identity factors,

which are used only to authenticate. Zero trust may leverage context information, but context-aware authentication alone does not indicate zero trust.

---

## Question 9
**Correct Answer:** B

**Explanation:**
Decentralized access control can result in less consistency because the individuals tasked with control may interpret policies and requirements differently and may perform their roles in different ways. Access outages, overly granular control, and training costs may occur, depending on specific implementations, but they are not commonly identified issues with decentralized access control.

---

## Question 10
**Correct Answer:** B

**Explanation:**
A callback to a landline phone number is an example of a “somewhere you are” factor because of the fixed physical location of a wired phone. A callback to a mobile phone would be a “something you have” factor.

---

## Question 11
**Correct Answer:** B

**Explanation:**
The NIST recommendation to not expire passwords recognizes that users often make minimal changes to their passwords when they are required to change them. In addition, password changes drive significant support overhead as users forget their passwords or otherwise face challenges with them. Longer password lives do create the potential for attackers to have longer to compromise them, but modern password recommendations look for multifactor authentication, which means a compromised password is less of a threat. Hashing new passwords does require computation, but not a significant amount using modern hardware.

---

## Question 12
**Correct Answer:** C

**Explanation:**
AAA refers to a set of security protocols that are used to identify and authorize users and record their activities. The acronym stands for authentication, authorization, and accounting.

---

## Question 13
**Correct Answer:** A

**Explanation:**
Active Directory relies on the Lightweight Directory Access Protocol (LDAP) as part of its single sign-on (SSO) implementation. Zero trust is not a SSO implementation, and Shibboleth is an open-source identity management system. RADIUS is not a single sign-on implementation, although some vendors use it behind the scenes to provide authentication for proprietary SSO.

---

## Question 14
**Correct Answer:** B

**Explanation:**
Knowledge-based authentication relies on information that only the individual who wants to prove their identity is likely to know. This might include a mortgage payment amount, vehicle information, or driver's license number among many options. Cognitive passwords, or security questions, are created by users, which means they aren't suited to this type of identity proofing. Palm scans and USB tokens both require prior engagement with the user as well and thus aren't suited for identity proofing with users who are new customers.

---

## Question 15
**Correct Answer:** D

**Explanation:**
When the owner of a file makes the decisions about who has rights or access privileges to it, they are using discretionary access control. Role-based access controls would grant access based on a subject's role, while rule-based controls would base the decision on a set of rules or requirements. Nondiscretionary access controls apply a fixed set of rules to an environment to manage access. Nondiscretionary access controls include rule-, role-, and lattice-based access controls.

---

## Question 16
**Correct Answer:** D

**Explanation:**
Need to know is applied when subjects like Alex have access to only the data they need to accomplish their job. Separation of duties is used to limit fraud and abuse by having multiple employees perform parts of a task. Constrained interfaces restrict what a user can see or do and would be a reasonable answer if need to

know did not describe his access more completely in this scenario. Context-dependent control relies on the activity being performed to apply controls, and this question does not specify a workflow or process.

---

## Question 17
**Correct Answer:** D

**Explanation:**
Password history tracks what passwords have been set previously and will not allow reuse. A specific number of past passwords is typically set, and passwords themselves should not be retained. Instead, properly secured hashes are retained and compared to hashes of the new passwords. Length, maximum age, and MFA do not solve the issue of password reuse.

---

## Question 18
**Correct Answer:** C

**Explanation:**
Ifeoma knows that a minimum password age of one day will discourage users from resetting their passwords to attempt to return to their original password. Length and complexity do not prevent this if the original password met these requirements, and a maximum age is set in organizations that require password changes on a recurring basis.

---

## Question 19
**Correct Answer:** A

**Explanation:**
Requiring multifactor authentication (MFA) is a common security measure used to prevent unauthorized access to an account in case of password loss or exposure. SSO allows the use of an account throughout systems or services. Federation connects different organizations together, allowing the use of credentials between trusted partners, and password rotation can help, but lost passwords remain dangerous until the rotation happens allowing days, weeks, or even months of potential vulnerable time.

---

## Question 20
**Correct Answer:** A

**Explanation:**
Retina scans can reveal additional information, including high blood pressure and pregnancy, causing privacy concerns. Newer retina scans don't require a puff of air, and retina scanners are not the most expensive biometric factor. Their false positive rate can typically be adjusted in software, allowing

administrators to adjust their acceptance rate as needed to balance usability and security.

---

## Question 21
**Correct Answer:** C

**Explanation:**
Mandatory access control systems are based on a lattice-based model. Lattice-based models use a matrix of classification labels to compartmentalize data. Discretionary access models allow object owners to determine access to the objects they control, role-based access controls are often group-based, and rule-based access controls like firewall ACLs apply rules to all subjects they apply to.

---

## Question 22
**Correct Answer:** D

**Explanation:**
Using an enterprise authentication system like Active Directory that requires individuals to log in with their credentials provides the ability to determine who was logged in if a problem occurs and also allows Greg to quickly and easily remove users who are terminated or switch roles. Using a shared PIN provides no accountability, while unique PINs per user on specifically issued iPads mean that others will not be able to log in. OAuth alone does not provide the services and features Greg needs—it is an authorization service, not an authentication service.

---

## Question 23
**Correct Answer:** A

**Explanation:**
Logging systems can provide accountability for identity systems by tracking the actions, changes, and other activities a user or account performs. Authorization does not provide accountability because it validates that a person can perform an action, not who is using the identity. Digital signatures can be used to validate an identity, not to provide accountability by proving who is using it, and Type 1 authentication is something you know. Again, logging is the best way to provide accountability for the use of an identity.

---

## Question 24
**Correct Answer:** B

**Explanation:**
As an employee's role changes, they often experience privilege creep, which is the accumulation of old rights and roles. Account review is the process of

reviewing accounts and ensuring that their rights match their owners' role and job requirements. Account revocation removes accounts, while re-provisioning might occur if an employee was terminated and returned or took a leave of absence and returned.

---

## Question 25
**Correct Answer:** A

**Explanation:**
Biba uses a lattice to control access and is a form of the mandatory access control (MAC) model. It does not use rules, roles, or attributes, nor does it allow user discretion. Users can create content at their level or lower but cannot decide who gets access, levels are not roles, and attributes are not used to make decisions on access control.

---

## Question 26
**Correct Answer:** C

**Explanation:**
RADIUS is an AAA protocol used to provide authentication and authorization; it's often used for modems, wireless networks, and network devices. It uses network access servers to send access requests to central RADIUS servers. Kerberos is a ticket-based authentication protocol; OAuth is an open standard for authentication allowing the use of credentials from one site on third-party sites; and EAP is the Extensible Authentication Protocol, an authentication framework often used for wireless networks.

---

## Question 27
**Correct Answer:** A

**Explanation:**
Session identifiers should not be predictable to ensure that attackers can't simply guess or easily brute force session IDS. Web application development best practices currently recommend the use of long session IDs (128 bits or longer) that have sufficient entropy (randomness) to ensure that they will not be easily duplicated or brute-forced. It is also a best practice to make sure the session ID itself is meaningless to prevent information disclosure attacks. Session IDs should expire, however, because a session that never expires could eventually be brute-forced even if all of these recommendations were met.

---

## Question 28
**Correct Answer:** B

**Explanation:**
Passwordless authentication leverages applications and capabilities such as built-in biometric authentication mechanisms. Extended and alternative authentication are not terms used on the exam. The Fast Identity Online Alliance (FIDO) is an open industry association that provides frameworks for passwordless authentication, but SPOT is not a type of passwordless authentication.

---

## Question 29
**Correct Answer:** B

**Explanation:**
The posturing capability of network access control (NAC) determines if a system is sufficiently secure and compliant enough to connect to a network. This is a form of risk-based access control, as systems that are not compliant are considered higher risk and either are placed in a quarantine and remediation network or zone or are prohibited from connecting to the network until they are compliant.

---

## Question 30
**Correct Answer:** D

**Explanation:**
Authorization provides a user with capabilities or rights. Roles and group management are both methods that could be used to match users with rights. Logins are used to validate a user.

---

## Question 31
**Correct Answer:** C

**Explanation:**
Privilege creep occurs when users retain rights they do not need to accomplish their current job from roles they held previously. Unauthorized access occurs when an unauthorized user accesses files. Excessive provisioning is not a term used to describe permissions issues, and account review would help find issues like this.

---

## Question 32
**Correct Answer:** A

**Explanation:**
Multifactor authentication is most likely to limit horizontal privilege escalation by making it difficult to access user accounts and to authenticate to a compromised account. Limiting permissions for groups and accounts can also help, but disabling unused ports and services and sanitizing user inputs both address

threats that are most frequently associated with vertical privilege escalation attacks.

---

## Question 33
**Correct Answer:** C

**Explanation:**
Hybrid systems use both on-premises and cloud identity and services to provide resources and tools in both environments. While they can be complex, hybrid systems also provide a migration path to a full cloud deployment or for a fault-tolerant design that can handle on-premises or cloud outages while remaining functional.

---

## Question 34
**Correct Answer:** C

**Explanation:**
Mandatory access controls (MAC) use a lattice or matrix to describe how classification labels relate to each other. In this image, classification levels are set for each of the labels shown. A discretionary access control (DAC) system would show how the owner of the objects allows access. RBAC could be either rule- or role-based access control and would use either system- wide rules or roles. Task-based access control (TBAC) would list tasks for users.

---

## Question 35
**Correct Answer:** D

**Explanation:**
Copying existing rights to new groups that have different needs will often result in overly broad privileges. Michelle should create new groups, move all staff into the appropriate groups, and then ensure that they have the access and permissions they need.

---

## Question 36
**Correct Answer:** B

**Explanation:**
The process of a subject claiming or professing an identity is known as identification. Authorization verifies the identity of a subject by checking a factor like a password. Logins typically include both identification and authorization, and token presentation is a type of authentication.

---

## Question 37
**Correct Answer:** A

**Explanation:**
Service accounts are commonly set to not have expiring passwords to prevent service outages. Organizations may choose to rotate passwords on a regular basis using automation tools as part of their

password management strategy to help avoid issues with exposed or compromised service passwords. Disabling complexity requirements and setting a minimum password age are not commonly done for service accounts.

---

## Question 38
**Correct Answer:** B

**Explanation:**
Password complexity is driven by length, and a longer password will be more effective against brute- force attacks than a shorter password. Each character of additional length increases the difficulty by the size of the potential character set (for example, a single lowercase character makes the passwords 26 times more difficult to crack). While each of the other settings is useful for a strong password policy, they won't have the same impact on brute-force attacks.

---

## Question 39
**Correct Answer:** A

**Explanation:**
Interactive login for a service account is a critical warning sign, either of compromise or bad administrative practices. In either case, Alaina should immediately work to determine why the account logged in, what occurred, and if the interactive login was done remotely or locally. A remote interactive login for a service account in any professionally maintained environment is an almost guaranteed sign of compromise. Password changes for service accounts may be done as part of ongoing password expiration processes, limitations should always be placed on service accounts rights to ensure that they are only those required, and a local use of the service account as part of the service is a normal event.

---

## Question 40
**Correct Answer:** A

**Explanation:**
Organizations that have very strict security requirements that don't have a tolerance for false acceptance want to lower the false acceptance rate, or FAR, to be as near to zero as possible. That often means that the false rejection rate, or FRR, increases. Different biometric technologies or a better registration

method can help improve biometric performance, but false rejections due to data quality are not typically a concern with modern biometric systems. In this case, knowing the crossover error rate, or CER, or having a very high CER doesn't help the decision.

---

## Question 41
**Correct Answer:** C

**Explanation:**
The most efficient use of Derek's time would be to create a group that is populated with all maintenance staff and then to give that group login rights only to the designated PCs. While time-based constraints might help, in this case, it would continue to allow maintenance staff to log in to PCs that are not intended for use during business hours, leaving a gap in the control. Multifactor authentication, as described, does not meet the requirements of the scenario but may be a good idea overall for greater security for authentication across the organization. Geofencing is typically not accurate enough to rely on inside buildings for specific PCs.

---

## Question 42
**Correct Answer:** B, C

**Explanation:**
Common session management techniques include the use of cookies, hidden form fields, URL rewriting, and built-in frameworks like Java's HTTPS session. IP tracking may be included in session information but is not itself a complete session identifier, and TLS token binding is used to make TLS sessions more secure, not to provide session identification.

---

## Question 43
**Correct Answer:** C

**Explanation:**
TLS provides message confidentiality and integrity, which can prevent eavesdropping. When paired with digital signatures, which provide integrity and authentication, forged assertions can also be defeated. SAML does not have a security mode and relies on TLS and digital signatures to ensure security if needed. Message hashing without a signature would help prevent modification of the message but won't necessarily provide authentication.

---

## Question 44
**Correct Answer:** B

**Explanation:**
Integration with cloud-based third parties that rely on local authentication can fail if the local organization's Internet connectivity or servers are offline. Adopting a hybrid cloud and local authentication system can ensure that Internet or server outages are handled, allowing authentication to work regardless of where the user is or if their home organization is online. Using encrypted and signed communication does not address availability, redirects are a configuration issue with the third party, and a local gateway won't handle remote users. Also, host files don't help with availability issues with services other than DNS.

---

## Question 45
**Correct Answer:** A

**Explanation:**
While many solutions are technical, if a trusted third party redirects to an unexpected authentication site, awareness is often the best defense. Using TLS would keep the transaction confidential but would not prevent the redirect. Handling redirects locally works only for locally hosted sites, and using a third-party service requires off-site redirects. An IPS might detect an attacker's redirect, but tracking the multitude of load- balanced servers most large providers use can be challenging, if not impossible. In addition, an IPS relies on visibility into the traffic, and SAML integrations should be encrypted for security, which would require a man-in-the-middle type of IPS to be configured.

---

## Question 46
**Correct Answer:** B

**Explanation:**
Discretionary access control (DAC) can provide greater scalability by leveraging many administrators, and those administrators can add flexibility by making decisions about access to their objects without fitting into an inflexible mandatory access control system (MAC). MAC is more secure due to the strong set of controls it provides, but it does not scale as well as DAC and is relatively inflexible in comparison.

---

## Question 47
**Correct Answer:** C

**Explanation:**
While signature-based detection is used to detect attacks, review of provisioning processes typically involves checking logs, reviewing the audit trail, or performing a manual review of permissions granted during the provisioning process.

---

## Question 48
**Correct Answer:** A

**Explanation:**
SAML is an open, XML-based standard used to provide authorization, attribute information, and authentication data. SOAP, or Simple Object Access Protocol, is a messaging protocol and could be used for any XML messaging but is not a markup language itself. OAuth is an authorization framework that exchanges information using APIs, and OpenID Connect is an authentication layer using OAuth that provides both authentication and authorization, but not attribute information.

---

## Question 49
**Correct Answer:** C

**Explanation:**
Rainbow tables are databases of pre-hashed passwords paired with high-speed lookup functions. Since they can quickly compare known hashes against those in a file, using rainbow tables is the fastest way to quickly determine passwords from hashes. A brute- force attack may eventually succeed but will be very slow against most hashes. Pass-the-hash attacks rely on sniffed or otherwise acquired NTLM or LanMan hashes being sent to a system to avoid the need to know a user's password. Salts are data added to a hash to avoid the use of tools like rainbow tables. A salt added to a password means the hash won't match a rainbow table generated without the same salt.

---

## Question 50
**Correct Answer:** B

**Explanation:**
Google's federation with other applications and organizations allows single sign-on as well as management of their electronic identity and its related attributes. While this is an example of SSO, it goes beyond simple single sign-on. Provisioning provides

accounts and rights, and a public key infrastructure is used for certificate management.

---

## Question 51
**Correct Answer:** D

**Explanation:**
When users have more rights than they need to accomplish their job, they have excessive privileges. This is a violation of the concept of least privilege. Unlike privilege creep, this is a provisioning or rights management issue rather than a problem of retention of rights the user needed but no longer requires. Rights collision is a made-up term and thus is not an issue here.

---

## Question 52
**Correct Answer:** B

**Explanation:**
Registration is the process of adding a user to an identity management system. This includes creating their unique identifier and adding any attribute information that is associated with their identity. Proofing occurs when the user provides information to prove who they are. Directories are managed to maintain lists of users, services, and other items. Session management tracks application and user sessions.

---

## Question 53
**Correct Answer:** A, B

**Explanation:**
Audit logging when combined with user accounts that can reliably be expected to be accessible only to a specific user due to the use of multifactor authentication is frequently used to provide strong accountability for actions taken via systems and applications. A password can be shared, making it less reliable, and time and location requirements are useful security controls but do not impact accountability.

---

## Question 54
**Correct Answer:** D

**Explanation:**
OAuth is the most widely used open standard for authorization and delegation of rights for cloud services. OpenID is used for authentication, and TACACS+ and RADIUS are primarily used on-site for authentication and authorization for network devices.

---

## Question 55
**Correct Answer:** D

**Explanation:**
Cameron is using a just-in-time (JIT) system that provides the access needed when it is needed. A zero trust system requires authentication and authorization when actions are performed but does not necessarily require privileges to be granted and removed when they are needed.

---

## Question 56
**Correct Answer:** C

**Explanation:**
Identity proofing can be done by comparing user information that the organization already has, like account numbers or personal information. Requiring users to create unique questions can help with future support by providing a way for them to do password resets. Using a phone call only verifies that the individual who created the account has the phone that they registered and won't prove their identity. In- person verification would not fit the business needs of most websites.

---

## Question 57
**Correct Answer:** A

**Explanation:**
In federated systems, a user's access to services is authenticated through their own organization's identity provider (IDP). Service providers query those IDPs when the user attempts to authenticate to the service and, if the request is validated, allow access based on the rules and policies set for the service based on attributes that may be relevant that are provided by the IDP.

---

## Question 58
**Correct Answer:** C

**Explanation:**
Type 2 errors occur in biometric systems when an invalid subject is incorrectly authenticated as a valid user. In this case, nobody except the actual customer should be validated when fingerprints are scanned. Type 1 errors occur when a valid subject is not authenticated; if the existing customer is rejected, it is a Type 1 error. Registration is the process of adding users, but registration errors and time of use, method of use errors are not specific biometric authentication terms.

---

## Question 59
**Correct Answer:** B

**Explanation:**
Firewalls use rule-based access control, or Rule- BAC, in their access control lists and apply rules created by administrators to all traffic that passes through them. DAC, or discretionary access control, allows owners to determine who can access objects they control, while task-based access control lists tasks for users. MAC, or mandatory access control, uses classifications to determine access.

---

## Question 60
**Correct Answer:** C

**Explanation:**
When you input a username and password, you are authenticating yourself by providing a unique identifier and a verification that you are the person who should have that identifier (the password). Authorization is the process of determining what a user is allowed to do. Validation and login both describe elements of what is happening in the process; however, they aren't the most important identity and access management activity.

---

## Question 61
**Correct Answer:** C

**Explanation:**
Kathleen should implement a biometric factor. The cards and keys are an example of a Type 2 factor, or “something you have.” Using a smart card replaces this with another Type 2 factor, but the cards could still be loaned out or stolen. Adding a PIN would address the problem by adding a second authentication factor, but PINs may be written down and are prone to theft or even guessing for shorter PINs, so a biometric factor is preferable if it is available. Adding cameras doesn't prevent access to the facility and thus doesn't solve the immediate problem (but it is a good idea!).

---

## Question 62
**Correct Answer:** C

**Explanation:**
Enterprise credential management tools, often called password vaults, allow passwords to be securely generated, stored, and managed. They can provide logs of who uses passwords, when they were updated, and if they meet complexity and other requirements. Of course, this means the keys to your environment are all

in one place, so securing and managing the enterprise password manager is very important!

---

## Question 63
**Correct Answer:** B

**Explanation:**
The sudoers file can list the specific users who can use sudo as well as the commands or directories that are allowed for them.

---

## Question 64
**Correct Answer:** C

**Explanation:**
In a mandatory access control system, all subjects and objects have a label. Compartments may or may not be used, but there is not a specific requirement for either subjects or objects to be compartmentalized. The specific labels of Confidential, Secret, and Top Secret are not required by MAC.

---

## Question 65
**Correct Answer:** D

**Explanation:**
Passwords are never stored for web applications in a well-designed environment. Instead, salted hashes are stored and compared to passwords after they are salted and hashed. If the hashes match, the user is authenticated.

---

## Question 66
**Correct Answer:** C

**Explanation:**
When a third-party site integrates via OAuth 2.0, authentication is handled by the service provider's servers. In this case, Google is acting as the service provider for user authentication. Authentication for local users who create their own accounts would occur in the e-commerce application (or a related server), but that is not the question that is asked here.

---

## Question 67
**Correct Answer:** B

**Explanation:**
The anti-forgery state token exchanged during OAuth sessions is intended to prevent cross-site request forgery (CSRF). This makes sure that the unique session token with the authentication response from Google's OAuth service is available to verify that the user, not an attacker, is making a request. XSS attacks focus on scripting and would have script tags involved, SQL injection would have SQL code included, and XACML is the eXtensible Access Control Markup Language, not a type of attack.

---

## Question 68
**Correct Answer:** A

**Explanation:**
Knowledge-based authentication relies on preset questions such as “What is your pet's name?” and the answers. It can be susceptible to attacks because of the availability of the answers on social media or other sites. Dynamic knowledge-based authentication relies on facts or data that the user already knows that can be used to create questions they can answer on an as- needed basis (for example, a previous address or a school they attended). Out-of-band identity proofing relies on an alternate channel like a phone call or text message. Finally, Type 3 authentication factors are biometric, or “something you are,” rather than knowledge-based.

---

## Question 69
**Correct Answer:** C

**Explanation:**
An access control matrix is a table that lists objects, subjects, and their privileges. Access control lists focus on objects and which subjects can access them. Capability tables list subjects and what objects they can access. Subject/object rights management systems are not based on an access control model.

---

## Question 70
**Correct Answer:** C

**Explanation:**
Self-service password reset tools typically have a significant impact on the number of password reset contacts that a help desk has. Two-factor and biometric authentication both add complexity and may actually increase the number of contacts. Passphrases can be easier to remember than traditional complex passwords and may decrease calls, but they don't have the same impact that a self-service system does.

---

## Question 71
**Correct Answer:** C

**Explanation:**
RADIUS supports TLS over TCP. RADIUS does not have a supported TLS mode over UDP. AES pre-shared symmetric ciphers are not a supported solution and would be difficult to both implement and maintain in a large environment, and the built-in encryption in RADIUS only protects passwords.

---

## Question 72
**Correct Answer:** B

**Explanation:**
OAuth provides the ability to access resources from another service and would meet Jim's needs. OpenID would allow him to use an account from another service with his application, and Kerberos and LDAP are used more frequently for in-house services.

---

## Question 73
**Correct Answer:** B

**Explanation:**
Since physical access to the workstations is part of the problem, setting application timeouts and password-protected screensavers with relatively short inactivity timeouts can help prevent unauthorized access. Using session IDs for all applications and verifying system IP addresses would be helpful for online attacks against applications.

---

## Question 74
**Correct Answer:** A

**Explanation:**
This diagram shows an example of hybrid federation where authentication occurs on-premises and services are provided through a federated identity service in the cloud.

---

## Question 75
**Correct Answer:** B, C

**Explanation:**
The best answers in the scenario that Chris faces are either RFID or magstripe readers and PIN pads. Guards create ongoing expenses, and any solution without a PIN will allow a stolen or cloned badge to be used without validating that the person accessing the building is a legitimate user. While a guard can prevent a stolen badge and PIN combination, this is only used in environments where the cost is justifiable.

---

## Question 76
**Correct Answer:** A

**Explanation:**
Yubikeys, Titan Security Keys, and similar devices are examples of tokens. PIV stands for personal identity verification and is a full multifactor authentication solution, not a device. Biometric identifiers are something you are, and a smart card is a card with an embedded chip.

---

## Question 77
**Correct Answer:** C

**Explanation:**
OpenID Connect is a RESTful, JSON-based authentication protocol that, when paired with OAuth, can provide identity verification and basic profile

information. SAML is the Security Assertion Markup Language, Shibboleth is a federated identity solution designed to allow web-based SSO, and Higgins is an open-source project designed to provide users with control over the release of their identity information.

---

## Question 78
**Correct Answer:** C

**Explanation:**
In a mandatory access control system, the operating system enforces access control, and users cannot delegate rights. Discretionary access control allows users to delegate rights, and neither attribute nor role- based access control specifically meets these requirements.

---

## Question 79
**Correct Answer:** D

**Explanation:**
In a zero trust reference model-based design, subjects connect through a policy enforcement point. The policy engine makes policy decisions based on rules that are then acted on by the policy administrator, granting or denying access to enterprise resources. Constrained interfaces limit user actions but are not the component connected through to conduct transactions.

---

## Question 80
**Correct Answer:** C

**Explanation:**
Synchronous soft tokens, such as Google Authenticator, use a time-based algorithm that generates a constantly changing series of codes. Asynchronous tokens typically require a challenge to be entered on the token to allow it to calculate a response, which the server compares to the response it expects. Smartcards typically present a certificate but may have other token capabilities built-in. Static tokens are physical devices that can contain credentials and include smart cards and memory cards.

---

## Question 81
**Correct Answer:** B

**Explanation:**
Kerberos, RADIUS, and TACACS+ are all commonly used for internal networks. SENTRY was made up for this question.

---

## Question 82
**Correct Answer:** B

**Explanation:**
Knowledge-based authentication is used by some financial institutions to validate the identity of new users. It uses information from tax and financial records that is unlikely to be available to others, allowing new users to provide details like their last credit card payment, mortgage payment, or other information to validate their identity. A Social Security number is somewhat trivial to acquire via paid services or other means, and manually validating identities is neither quick nor automatic. A biometric factor would require a previous enrollment, making this unsuitable for new customers.

---

## Question 83
**Correct Answer:** B, C

**Explanation:**
Google accounts, like many cloud identity providers, rely on OpenID and OAuth. Kerberos is used for on-premises environments, and RADIUS is frequently used for authentication and authorization for network devices and services like VPN.

---

## Question 84
**Correct Answer:** C

**Explanation:**
Best practices for session management involve a long session ID (often 128 bits or longer) and enough randomness or entropy to make it hard to guess session IDs. This makes brute-force or algorithmic guessing attacks unlikely unless there is a flaw in the implementation. These do not prevent denial-of-service or man-in-the-middle attacks, and cookie attacks are focused on acquiring and reading or reusing cookies in most scenarios.

---

## Question 85
**Correct Answer:** D

**Explanation:**
Risk-based access control models risk using information that is available when the access request is created. Information about the request and the risk it may create is calculated based on risk values and compared to access policies. If the risk value is acceptable, access is granted. One of the most common examples of this in organizations is NAC, or network access control, where a system is profiled to determine

security risk and compliance before admission to a network. This can be seen as a more specific example of rule-based access control. Role-based access control bases its decisions on the roles of the individuals, whereas mandatory access control is enforced by the operating system.

---

## Question 86
**Correct Answer:** A

**Explanation:**
The most important step in securing service accounts is to ensure that they have only the rights that are absolutely needed to accomplish the task they are designed for. Disabling interactive logins is important as well and would be the next best answer. Limiting when accounts can log in and using randomized or meaningless account names can both be helpful in some circumstances but are far less important.

---

## Question 87
**Correct Answer:** B

**Explanation:**
The NIST zero trust reference design includes both the Policy Engine and the Policy Administrator as part of the policy decision point. The terms control plane module, enterprise management console, and zero trust engine are not used in this context.

---

## Question 88
**Correct Answer:** C

**Explanation:**
Federation does not necessarily guarantee that services will be shared or made accessible. Member organizations can choose which services they provide and can use more granular controls like role- or organization-based permissions to grant access to services. Payment may be part of a federation agreement or service access, but simply federating does not create or prevent a financial requirement.

---

## Question 89
**Correct Answer:** A

**Explanation:**
Attributes used for ABAC often fall into one of four categories: subject attributes such as department or title; action attributes such as the ability to view, edit, or delete; object attributes that describe the object that can be impacted; and contextual attributes such as location, time, or elements. Discretionary access control would place these decisions in the hands of

trusted subjects, MAC would enforce it at the operating system level, and role BAC would use only roles instead of the full set of criteria Kristen wants to apply.

---

## Question 90
**Correct Answer:** D

**Explanation:**
The Linux filesystem allows the owners of objects to determine the access rights that subjects have to them. This means that it is a discretionary access control. If the system enforced a role-based access control, Alex wouldn't set the controls; they would be set based on the roles assigned to each subject. A rule-based access control system would apply rules throughout the system, and a mandatory access control system uses classification labels.

---

## Question 91
**Correct Answer:** B

**Explanation:**
Privilege creep is a constant concern when staff change roles over time. Privileges from previous roles may be easy to forget or to retain during transition because staff may continue to help cover the tasks or processes the individual previously performed. Over time, these forgotten rights and privileges can stack, leaving the staff member with rights that their current role should not have. Registration is a concern for new staff, while de-provisioning is a concern for departing staff. Accountability is typically provided by IAM systems by authenticating and logging access and privilege usage.

---

## Question 92
**Correct Answer:** A

**Explanation:**
This is a role-based access control (RBAC) chart noting that each group has specific rights by roles. Attribute-based access control (ABAC) would use other attributes including things like location, mandatory access control (MAC) would be enforced by the operating system, and discretionary access control (DAC) allows subjects like users to set rights on objects they control.

---

## Question 93
**Correct Answer:** A

**Explanation:**
Ensure that users cannot bypass logging by switching to the root user using sudo su -. Instead,

users who need the ability to perform privileged actions should be added to the sudoers list and then logged as themselves performing the actions. Adding all users is likely an overly broad action, whereas removing all users would not allow individual logging under their accounts, nor would they have rights to take administrative actions. Disabling sudo doesn't allow administrative tasks except as root, which defeats this requirement as well.

---

## Question 94
**Correct Answer:** C

**Explanation:**
Single sign-on (SSO) is part of identity federation. It also means that account management is simpler since multiple accounts don't have to be maintained for users who need to access systems and resources across the federation. Productivity can increase because staff don't have to remember multiple logins and can use SSO to log in once instead of multiple times. It does not, however, do anything to prevent brute-force attacks, and in fact, a single account with broad access can make it easier for an attacker to gain that broader access unless solutions like multifactor authentication are put in place.

---

## Question 95
**Correct Answer:** A

**Explanation:**
A JIT, or just-in-time, provisioning mechanism creates accounts when they are needed rather than creating them in advance. This is an effective method to limit the number of accounts being maintained and can be useful if the number of accounts are part of a licensing agreement that may drive costs higher if users who don't need accounts or are not using them have them. OAuth, OpenID, and Kerberos are not mentioned in the question.

---

## Question 96
**Correct Answer:** B

**Explanation:**
Windows uses Kerberos for authentication. RADIUS is typically used for wireless networks, modems, and network devices, while OAuth is primarily used for web applications. TACACS+ is used for network devices.

---

## Question 97
**Correct Answer:** D

**Explanation:**
When very high levels of control are needed or when endpoint devices cannot be trusted, using a centralized environment with remote connectivity and enterprise authentication can provide appropriate security. 1.

---

## Question 98
**Correct Answer:** See Explanation

**Explanation:**
E 2. B 3. D 4. C 5. A

---

## Question 99
**Correct Answer:** See Explanation

**Explanation:**
The security controls match with the categories as follows: 1. Password: B. Something you know 2. ID card: A. Something you have 3. Retinal scan: C. Something you are 4. Smartphone token: A. Something you have 5. Fingerprint analysis: C. Something you are 1.

---

## Question 100
**Correct Answer:** See Explanation

**Explanation:**
A 2. E 3. D 4. B 5. C

---

