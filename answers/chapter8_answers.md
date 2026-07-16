# CISSP Practice Tests - Chapter 8: Software Development Security (Domain 8) Answer Key

## Question 1
**Correct Answer:** A

**Explanation:**
Limiting request rates can prevent abuse of APIs like this one. The other suggestions are all poor recommendations. In general, requests should require HTTPS, tokens are used for security using tools like JSON web tokens (JWT), and HTTP methods may be restricted, but GET, POST, and PUT are some of the most common methods used for API access and are far more typically whitelisted.

---

## Question 2
**Correct Answer:** A, B, C

**Explanation:**
Botnets are used for a wide variety of malicious purposes, including scanning the network for vulnerable systems, conducting brute-force attacks against other systems, mining cryptocurrency, and sending out spam messages. They are not commonly used to conduct man-in-the-middle attacks, which are normally waged through DNS poisoning or similar mechanisms.

---

## Question 3
**Correct Answer:** C

**Explanation:**
Code review takes place after code has been developed, which occurs after the design phase of the system's development life cycle (SDLC). Code review may use a combination of manual and automated techniques or rely solely on one or the other. It should be a peer-driven process that includes developers who did not write the code. Developers should expect to complete the review of around 300 lines per hour, on average.

---

## Question 4
**Correct Answer:** A

**Explanation:**
This code is an example of parameterization, which can help avoid SQL injection. Note that each parameter has a placeholder, which is then passed to the query.

---

## Question 5
**Correct Answer:** C

**Explanation:**
One of the responsibilities of the release control process is ensuring that acceptance testing is

performed, to ensure that any alterations to end-user tasks are understood and functional prior to code release. The request control, change control, and configuration control processes do not include acceptance testing.

---

## Question 6
**Correct Answer:** B

**Explanation:**
Cross-site request forgery (XSRF or CSRF) attacks exploit the trust that sites have in a user's browser by attempting to force the submission of authenticated requests to third-party sites. Session hijacking attacks attempt to steal previously authenticated sessions but do not force the browser to submit requests. A SQL injection directly attacks a database through a web application. Cross-site scripting uses reflected input to trick a user's browser into executing untrusted code from a trusted site.

---

## Question 7
**Correct Answer:** A

**Explanation:**
The OpenSSL package is a widely used implementation of TLS encryption that is available as an open-source package. It is not commercial off-the- shelf software (COTS). While it might be developed by third parties, it is more accurate to describe it as open source. The library is available as code for free use, but not as a managed service.

---

## Question 8
**Correct Answer:** D

**Explanation:**
The error message shown in the figure is the infamous “Blue Screen of Death” that occurs when a Windows system experiences a dangerous failure and enters a fail secure state. If the system had “failed open,” it would have continued operation. The error described is a memory fault that is likely recoverable by rebooting the system. There is no indication that the system has run out of usable memory.

---

## Question 9
**Correct Answer:** A, B, C

**Explanation:**
Software threat modeling is designed to reduce the number of security-related design and coding flaws as well as the severity of other flaws. The developer or evaluator of software has no control over

the threat environment, because it is external to the organization.

---

## Question 10
**Correct Answer:** C

**Explanation:**
In the diagram, Account is the name of the class. Owner and Balance are attributes of that class. AddFunds and RemoveFunds are methods of the class.

---

## Question 11
**Correct Answer:** D

**Explanation:**
Rapid Application Development, or RAD, focuses on fast development and the ability to quickly adjust to changing requirements. RAD uses four phases: requirements planning, user design, construction, and cutover.

---

## Question 12
**Correct Answer:** A

**Explanation:**
Dynamic testing of software typically occurs in a black-box environment where the tester does not have access to the source code. Static testing, white-box testing, and code review approaches all require access to the source code of the application.

---

## Question 13
**Correct Answer:** C

**Explanation:**
Given the list of options here, the root cause is most likely an issue with an authorization check that does not properly limit users to the authorization that they should have. Data validation issues are more likely to allow injection attacks or to allow bad data to be input, while session management issues would allow session hijacking or might actually cause them to be logged in as another user. Finally, error handling would show up as a problem when errors occurred, which this problem does not indicate.

---

## Question 14
**Correct Answer:** C

**Explanation:**
Aggregate functions summarize large amounts of data and provide only summary information as a result. When carefully crafted, aggregate functions may unintentionally reveal sensitive information.

---

## Question 15
**Correct Answer:** B

**Explanation:**
The best protection against buffer overflow attacks is server-side input validation. This technique limits user input to approved ranges of values that fit within allocated buffers. While firewalls and intrusion

prevention systems may contain controls that limit buffer overflows, it would be more effective to perform filtering on the application server. Encryption cannot protect against buffer overflow attacks.

---

## Question 16
**Correct Answer:** C

**Explanation:**
Each of these problems is caused by improper or missing input validation and can be resolved by handling inputs properly. In many cases, this can be done using libraries or methods already built into the language or framework that the developer is using.

---

## Question 17
**Correct Answer:** C

**Explanation:**
Acme Widgets is clearly in the initial stage of the SW-CMM. This stage is characterized by the absence of formal process. The company may still produce working code, but it does so in a disorganized fashion.

---

## Question 18
**Correct Answer:** B

**Explanation:**
The Repeatable stage is the second stage in the SW- CMM, following the Initial stage. It should be the next milestone goal for Acme Widgets. The Repeatable stage is characterized by basic life cycle management processes.

---

## Question 19
**Correct Answer:** A

**Explanation:**
The Defined stage of the SW-CMM is marked by the presence of basic life cycle management processes and reuse of code. It includes the use of requirements management, software project planning, quality assurance, and configuration management practices.

---

## Question 20
**Correct Answer:** D

**Explanation:**
The Managed stage is the fourth stage in the SW- CMM, following the Defined stage. It should be the next milestone goal for Beta Particles. The Managed stage is characterized by the use of quantitative software development measures.

---

## Question 21
**Correct Answer:** C

**Explanation:**
Referential integrity ensures that records exist in a secondary table when they are referenced with a foreign key from another table. Foreign keys are the mechanism used to enforce referential integrity.

---

## Question 22
**Correct Answer:** A

**Explanation:**
Macro viruses are most commonly found in office productivity documents, such as Microsoft Word documents that end in the .doc or .docx extension. They are not commonly found in executable files with the .com or .exe extension.

---

## Question 23
**Correct Answer:** C

**Explanation:**
The degree of a database table is the number of attributes in the table. Victor's table has six attributes: the employee's user ID, home telephone, office telephone, mobile telephone, office location, and job title.

---

## Question 24
**Correct Answer:** C

**Explanation:**
The string shown in the logs is characteristic of a directory traversal attack where the attacker attempts to force the web application to navigate up the file hierarchy and retrieve a file that should not normally be provided to a web user, such as the password file. The series of “double dots” is indicative of a directory traversal attack because it is the character string used to reference the directory one level up in a hierarchy.

---

## Question 25
**Correct Answer:** C

**Explanation:**
Design reviews should take place after the development of functional and control specifications but before the creation of code. The code review, unit testing, and functional testing all take place after the creation of code and, therefore, after the design review.

---

## Question 26
**Correct Answer:** C

**Explanation:**
Regression testing is software testing that runs a set of known inputs against an application and then compares the results to those produced by an earlier version of the software. It is designed to capture unanticipated consequences of deploying new code versions prior to introducing them into a production environment.

---

## Question 27
**Correct Answer:** D

**Explanation:**
Assurance, when it comes to software, is the level of confidence that software is free from vulnerabilities, either intentionally designed into the software or

accidentally inserted at any time during its life cycle, and that the software functions in the intended manner. It is a term typically used in military and defense environments.

---

## Question 28
**Correct Answer:** C

**Explanation:**
The change control process is responsible for providing an organized framework within which multiple developers can create and test a solution prior to rolling it out in a production environment. Request control provides a framework for user requests. Release control manages the deployment of code into production. Configuration control ensures that changes to software versions are made in accordance with the change and configuration management policies.

---

## Question 29
**Correct Answer:** D

**Explanation:**
Aggregation is a security issue that arises when a collection of facts has a higher classification than the classification of any of those facts standing alone. An inference problem occurs when an attacker can pull together pieces of less sensitive information and use them to derive information of greater sensitivity. SQL injection is a web application exploit. Multilevel security is a system control that allows the simultaneous processing of information at different classification levels.

---

## Question 30
**Correct Answer:** B

**Explanation:**
Code libraries are packages of reusable functions that may be incorporated into individual development projects. Ron could use libraries to easily share code among his team. Code repositories may be used to manage the distribution and updating of these libraries, but that is a second-order use case, making code libraries the best answer. Integrated development environments (IDEs) are tools used by developers to create software, while dynamic application security testing (DAST) is used to verify the correct implementation of code.

---

## Question 31
**Correct Answer:** A

**Explanation:**
Black-box testing begins with no prior knowledge of the system implementation, simulating a user's perspective. White-box and gray-box testing provide full and partial knowledge of the system, respectively, in advance of the test. Blue boxes are a phone hacking tool and are not used in software testing.

---

## Question 32
**Correct Answer:** B

**Explanation:**
In this example, the two SQL commands are indeed bundled in a transaction, but it is not an error to issue an update command that does not match any rows. Therefore, the first command would “succeed” in updating zero rows and not generate an error or cause the transaction to roll back. The second command would then execute, reducing the balance of the second account by $250.

---

## Question 33
**Correct Answer:** A

**Explanation:**
Software development kits (SDKs) are code libraries and other tools made available to assist developers in creating code. An integrated development environment (IDE) may be a component of an SDK, but it is not necessarily part of every SDK. An application programming interface (API) is a set of functions made available to external developers, but the code does not execute on the users' machine, as would a code library or other SDK tools. Data loss prevention (DLP) capabilities are not a component of software development toolsets.

---

## Question 34
**Correct Answer:** C

**Explanation:**
A fail open configuration may be appropriate in this case. In this configuration, the firewall would continue to pass traffic without inspection while it is restarting. This would minimize downtime, and the traffic would still be protected by the other security controls described in the scenario. Failover devices and high availability clusters would indeed increase availability, but at potentially significant expense. Redundant disks

would not help in this scenario because no disk failure is described.

---

## Question 35
**Correct Answer:** D

**Explanation:**
An inference problem occurs when an attacker can pull together pieces of less sensitive information and use them to derive information of greater sensitivity. SQL injection is a web application exploit. Multilevel security is a system control that allows the simultaneous processing of information at different classification levels. Parameterization is a security control used to reduce the likelihood of attacks that rely upon improper user input.

---

## Question 36
**Correct Answer:** B

**Explanation:**
Polymorphic viruses mutate each time they infect a system by making adjustments to their code that assists them in evading signature detection mechanisms. Encrypted viruses also mutate from infection to infection but do so by encrypting themselves with different keys on each device.

---

## Question 37
**Correct Answer:** A

**Explanation:**
The message forum is clearly susceptible to a cross- site scripting (XSS) attack. The code that Linda discovered in the message is a definitive example of an attempt to conduct cross-site scripting, and the alert box that she received demonstrates that the vulnerability exists. The website may also be vulnerable to cross-site request forgery, SQL injection, improper authentication, and other attacks, but there is no evidence of this provided in the scenario.

---

## Question 38
**Correct Answer:** A

**Explanation:**
The script that Linda discovered merely pops up a message on a user's screen and does not perform any more malicious action. This type of script, using an alert() call, is commonly used to probe websites for cross-site scripting vulnerabilities.

---

## Question 39
**Correct Answer:** B

**Explanation:**
Web application firewalls (WAFs) sit in front of web applications and watch for potentially malicious web

attacks, including cross-site scripting. They then block that traffic from reaching the web application. An intrusion detection system (IDS) may detect the attack but is unable to take action to prevent it. DLP and VPN solutions are unable to detect web application attacks.

---

## Question 40
**Correct Answer:** C

**Explanation:**
Input validation verifies that user-supplied input does not violate security conditions and is the most effective defense against cross-site scripting attacks. Bounds checking is a form of input validation, but it is typically used to ensure that numeric input falls within an acceptable range and is not applicable against cross- site scripting attacks. Peer review and OS patching are both good security practices but are unlikely to be effective against a cross-site scripting attack.

---

## Question 41
**Correct Answer:** B

**Explanation:**
RStudio is a tool used to assist in the creation of code, otherwise known as an integrated development environment (IDE). Software development kits (SDKs) are code libraries and other tools made available to assist developers in creating code. An application programming interface (API) is a set of functions made available to external developers, but the code does not execute on the users' machine, as would a code library or other SDK tools. Data loss prevention (DLP) capabilities are not a component of software development toolsets.

---

## Question 42
**Correct Answer:** D

**Explanation:**
Full SAFe is designed to support enterprises in building and maintaining large integrated solutions with the collaboration of hundreds of practitioners. It provides the most extensive level of guidance, with roles, responsibilities, and activities needed to sustainably deliver complex solutions. Essential SAFe focuses on the basic elements of the framework needed to be agile, Large Solution SAFe is for developing large and complex solutions that do not require the

constructs of the portfolio level, and Portfolio SAFe is for aligning enterprise strategy with execution but does not address the complexity of building large solutions that Full SAFe is designed for.

---

## Question 43
**Correct Answer:** C

**Explanation:**
The JVM is the runtime virtual machine that allows the execution of Java code on a device. The JVM implements the Java sandbox, but that is only one of its many functions. The JVM itself is not a change manager or code repository.

---

## Question 44
**Correct Answer:** C

**Explanation:**
User acceptance testing (UAT) is typically the last phase of the testing process. It verifies that the solution developed meets user requirements and validates it against use cases. Unit testing, integration testing, and system testing are all conducted earlier in the process leading up to UAT.

---

## Question 45
**Correct Answer:** D

**Explanation:**
When organizations adopt a continuous integration/continuous delivery (CI/CD) approach to software development, they may deploy code extremely rapidly. In fact, some organizations deploy new code to production hundreds or even thousands of times per day using this approach.

---

## Question 46
**Correct Answer:** C

**Explanation:**
The Open Worldwide Application Security Project (OWASP) is widely considered as the most authoritative source on web application security issues. They publish the OWASP Top Ten list that publicizes the most critical web application security issues.

---

## Question 47
**Correct Answer:** B

**Explanation:**
Chris is in an Agile sprint phase and is likely developing code based on user stories. Planning includes stakeholder stories, as well as design and test case preparation. Testing involves ensuring that the code works properly and meets requirements. Deployment includes the actual deployment of the

application, as well as additional verification and testing.

---

## Question 48
**Correct Answer:** D

**Explanation:**
Security information and event management (SIEM) systems do correlate information from multiple sources and perform analysis, but they stop short of providing automated playbook responses. That is the realm of security orchestration, automation, and response (SOAR) platforms. Intrusion prevention platforms have a more limited scope, allowing the blocking of traffic based upon analysis performed by the IPS itself. Log repositories simply collect log information and do not perform analysis.

---

## Question 49
**Correct Answer:** B

**Explanation:**
This is an example of a specific type of buffer overflow known as an off-by-one error. The first line of the code defines an array of 10 elements, which would be numbered 0 through 9. The second line of code tries to place a value in the 11th element of the array (remember, array counting begins at 0!), which would cause an overflow.

---

## Question 50
**Correct Answer:** C

**Explanation:**
Lost updates occur when one transaction writes a value to the database that overwrites a value needed by transactions that have earlier precedence, causing those transactions to read an incorrect value. Dirty reads occur when one transaction reads a value from a database that was written by another transaction that did not commit. Incorrect summaries occur when one transaction is using an aggregate function to summarize data stored in a database while a second transaction is making modifications to the database, causing the summary to include incorrect information. SQL injection is a web application security flaw, not a database concurrency problem.

---

## Question 51
**Correct Answer:** A

**Explanation:**
Transport Layer Security (TLS) provides the most effective defense against session hijacking because it

encrypts all traffic between the client and server, preventing the attacker from stealing session credentials. Secure Sockets Layer (SSL) also encrypts traffic, but it is vulnerable to attacks against its encryption technology. Complex and expiring cookies are a good idea, but they are not sufficient protection against session hijacking.

---

## Question 52
**Correct Answer:** C

**Explanation:**
The purpose of the change advisory board (CAB) is to review and then approve or reject proposed code changes. The CAB is not normally involved in the approval of developer credentials, the conduct of lessons learned sessions, or the prioritization of software development efforts.

---

## Question 53
**Correct Answer:** B

**Explanation:**
git is a version management tool that is very commonly used by developers to interact with code repositories, such as those hosted by GitHub. grep is a command-line tool used to search files for specific content. lsof is a command used to list the open files on a system. gcc is a C language compiler used to transform source code into executable code.

---

## Question 54
**Correct Answer:** C

**Explanation:**
The single quotation mark in the input field is a telltale sign that this is a SQL injection attack. The single quotation mark is used to escape outside the SQL code's input field, and the text following it is used to directly manipulate the SQL command sent from the web application to the database.

---

## Question 55
**Correct Answer:** B

**Explanation:**
Client-side input validation is not an effective control against any type of attack because the attacker can easily bypass the validation by altering the code on the client. Escaping restricted characters prevents them from being passed to the database, as does parameterization. Limiting database permissions prevents dangerous code from executing.

---

## Question 56
**Correct Answer:** B

**Explanation:**
PERT charts use nodes to represent milestones or deliverables and then show the estimated time to move between milestones. Gantt charts use a different format with a row for each task and lines showing the expected duration of the task. Work breakdown structures are an earlier deliverable that divides project work into achievable tasks. Wireframe diagrams are used in application UI design.

---

## Question 57
**Correct Answer:** D

**Explanation:**
Regression testing is performed after developers make changes to an application. It reruns a number of test cases and compares the results to baseline results. Orthogonal array testing is a method for generating test cases based on statistical analysis. Pattern testing uses records of past software bugs to inform the analysis. Matrix testing develops a matrix of all possible inputs and outputs to inform the test plan.

---

## Question 58
**Correct Answer:** B

**Explanation:**
Cross-site scripting (XSS) attacks may take advantage of the use of reflected input in a web application where input provided by one user is displayed to another user. Input validation is a control used to prevent XSS attacks. XSS does not require an unpatched server or any firewall rules beyond those permitting access to the web application.

---

## Question 59
**Correct Answer:** A

**Explanation:**
In a white-box test, the tester has access to full implementation details of the system, including source code, prior to beginning the test. In gray-box testing, the tester has partial knowledge. In black-box testing, the tester has no knowledge of the system and tests it from a user perspective. Blue boxes are a phone hacking tool and are not used in software testing.

---

## Question 60
**Correct Answer:** C

**Explanation:**
Heuristic-based antimalware software has a higher likelihood of detecting a zero-day exploit than signature-based methods. Heuristic-based software does not require frequent signature updates because it

does not rely upon monitoring systems for the presence of known malware. The trade-off with this approach is that it has a higher false positive rate than signature detection methods.

---

## Question 61
**Correct Answer:** D

**Explanation:**
One possibility for the clean scan results is that the virus is using stealth techniques, such as intercepting read requests from the antivirus software and returning a correct-looking version of the infected file. The system may also be the victim of a zero-day attack, using a virus that is not yet included in the signature definition files provided by the antivirus vendor.

---

## Question 62
**Correct Answer:** A

**Explanation:**
In URL encoding, the . character is replaced by %252E, and the / character is replaced by %252F. You can see this in the log entry, where the expected pattern of ../../ is replaced by %252E%252E%252F%252E%252E%252F.

---

## Question 63
**Correct Answer:** C

**Explanation:**
Attacks where the malicious user tricks the victim's web browser into executing a script through the use of a third-party site are known as cross-site scripting (XSS) attacks. This particular attack is a persistent XSS attack because it remains on the discussion forum until an administrator discovers and deletes it, giving it the ability to affect many users.

---

## Question 64
**Correct Answer:** C

**Explanation:**
The Agile Manifesto includes 12 principles for software development. Three of those are listed as answer choices: maximizing the amount of work not done is essential, build projects around motivated individuals, and welcome changing requirements throughout the development process. Agile does not, however, consider clear documentation the primary measure of progress. Instead, working software is the primary measure of progress.

---

## Question 65
**Correct Answer:** B

**Explanation:**
Each change should be the result of a reviewed and approved request for change (RFC). These RFCs may be approved by the change advisory board (CAB). The security information and event management (SIEM) and security orchestration, automation, and response (SOAR) platforms used by the organization would not normally contain information about the change management process.

---

## Question 66
**Correct Answer:** D

**Explanation:**
A key-value store is an example of a NoSQL database that does not follow a relational or hierarchical model like traditional databases. A graph database is another example of a NoSQL database, but it uses nodes and edges to store data rather than keys and values.

---

## Question 67
**Correct Answer:** C

**Explanation:**
A database failure in the middle of a transaction causes the rollback of the entire transaction. In this scenario, the database would not execute either command because doing so would violate the atomicity property of the transaction.

---

## Question 68
**Correct Answer:** B

**Explanation:**
When using commercial off-the-shelf (COTS) software, customers do not generally have access to the source code and must depend upon the vendor to release security patches that correct vulnerabilities. Other controls, such as intrusion prevention systems and firewalls, may be able to help mitigate the issue, depending upon the nature of the flaw, but they will not correct it.

---

## Question 69
**Correct Answer:** B

**Explanation:**
Static testing performs code analysis in an offline fashion, without actually executing the code. Dynamic testing evaluates code in a runtime environment. Both static and dynamic testing may use automated tools, and both are important security testing techniques.

---

## Question 70
**Correct Answer:** D

**Explanation:**
The chart shown in the figure is a Gantt chart, showing the proposed start and end dates for different activities. It is developed based on the work breakdown structure (WBS), which is developed based on functional requirements. Program Evaluation Review Technique (PERT) charts show the project schedule as a series of numbered nodes.

---

## Question 71
**Correct Answer:** D

**Explanation:**
In a gray-box test, the tester evaluates the software from a user perspective but has access to the source code as the test is conducted. White-box tests also have access to the source code but perform testing from a developer's perspective. Black-box tests work from a user's perspective but do not have access to source code. Blue boxes are a telephone hacking tool and not a software testing technique.

---

## Question 72
**Correct Answer:** D

**Explanation:**
The Time of Check to Time of Use (TOC/TOU) attack exploits timing differences between when a system verifies authorization and software uses that authorization to perform an action. It is an example of a race condition attack. The other three attacks mentioned do not depend on precise timing.

---

## Question 73
**Correct Answer:** D

**Explanation:**
Each of these input parameters makes up part of the attack surface of the application. Attackers may opt to target any of them to attack the code or its supporting infrastructure.

---

## Question 74
**Correct Answer:** B

**Explanation:**
Threat modeling commonly involves decomposing the application to understand it and how it interacts with other components or users. Next, identifying and ranking threats allows you to focus on the threats that should be prioritized. Finally, identifying how to mitigate those threats finishes the process. Once complete, an organization can take action to handle the threats that were identified with appropriate controls.

---

## Question 75
**Correct Answer:** D

**Explanation:**
The fail closed approach prevents any activity from taking place during a system security failure and is the most conservative approach to failure management. Fail open takes the opposite philosophy, allowing all activity in the event of a security control failure. Fail clear and fail mitigation are not failure management approaches.

---

## Question 76
**Correct Answer:** D

**Explanation:**
The illustration shows the spiral model of software development. In this approach, developers use multiple iterations of a waterfall-style software development process. This becomes a “loop” of iterations through similar processes. The original waterfall approach does not iterate through the entire process repeatedly. Some variants do allow iteration, but only by allowing movement backward and forward one stage. The Agile approach to software development focuses on iterative improvement and does not follow a rigorous SDLC model. Lean is a process improvement methodology and not a software development model.

---

## Question 77
**Correct Answer:** D

**Explanation:**
In a software-as-a-service solution, the vendor manages both the physical infrastructure and the complete application stack, providing the customer with access to a fully managed application.

---

## Question 78
**Correct Answer:** A

**Explanation:**
The request process begins with a user-initiated request for a feature. Change and release control are initiated by developers seeking to implement changes. Design review is a phase of the change approval process initiated by developers when they have a completed design.

---

## Question 79
**Correct Answer:** C

**Explanation:**
Polyinstantiation allows the storage of multiple different pieces of information in a database at different classification levels to prevent attackers from inferring anything about the absence of information. Input validation, server-side validation, and

parameterization are all techniques used to prevent web application attacks and are not effective against inference attacks.

---

## Question 80
**Correct Answer:** C

**Explanation:**
While Ursula may certainly use an object model, data dictionary, and primary key in her development effort, external developers cannot directly use them to access her code. An application programming interface (API) allows other developers to call Ursula's code from within their own without knowing the details of Ursula's implementation.

---

## Question 81
**Correct Answer:** C

**Explanation:**
This is an example of software-defined security (SDS), where security infrastructure may be easily manipulated by code. Answering this question is tricky because several of the other terms are closely related. Software-defined security is an example of infrastructure as code (IaC), but SDS is a more descriptive, and therefore better, answer. SDS is commonly used within an Agile development framework. The DevOps approach links together development and operations but is generally called DevSecOps when it also includes SDS.

---

## Question 82
**Correct Answer:** D

**Explanation:**
Messages similar to the one shown here are indicative of a ransomware attack. The attacker encrypts files on a user's hard drive and then demands a ransom, normally paid in Bitcoin, for the decryption key required to restore access to the original content. Encrypted viruses, on the other hand, use encryption to hide themselves from antivirus mechanisms and do not alter other contents on the system.

---

## Question 83
**Correct Answer:** D

**Explanation:**
Despite many organizations moving to Agile, DevOps, or other more responsive development methodologies, waterfall remains a strong contender when clear objectives and stable requirements are combined with a need to prevent flaws and to have a

high level of control over the development process and output.

---

## Question 84
**Correct Answer:** D

**Explanation:**
Neural networks attempt to use complex computational techniques to model the behavior of the human mind. Knowledge banks are a component of expert systems, which are designed to capture and reapply human knowledge. Decision support systems are designed to provide advice to those carrying out standard procedures and are often driven by expert systems.

---

## Question 85
**Correct Answer:** B

**Explanation:**
In level 2, the Repeatable level of the SW-CMM, an organization introduces basic life cycle management processes. Reuse of code in an organized fashion begins, and repeatable results are expected from similar projects. The key process areas for this level include Requirements Management, Software Project Planning, Software Project Tracking and Oversight, Software Subcontract Management, Software Quality Assurance, and Software Configuration Management.

---

## Question 86
**Correct Answer:** C

**Explanation:**
The critical fact in this question is that Lucas suspects the tampering took place before the employee departed. This is the signature of a logic bomb: malicious code that lies dormant until certain conditions are met. The other attack types listed here— privilege escalation, SQL injection, and remote code execution—would more likely take place in real time.

---

## Question 87
**Correct Answer:** A

**Explanation:**
The Agile approach to software development embraces four principles. It values individuals and interactions over processes and tools, working software over comprehensive documentation, customer collaboration over contract negotiation, and responding to change over following a plan.

---

## Question 88
**Correct Answer:** C

**Explanation:**
API developers commonly use API keys to limit access to authorized users and applications. Encryption provides for confidentiality of information exchanged using an API but does not provide authentication. Input validation is an application security technique used to protect against malicious input. IP filters may be used to limit access to an API, but they are not commonly used because it is difficult to deploy an API with IP filters since the filters require constant modification and maintenance as endpoints change.

---

## Question 89
**Correct Answer:** D

**Explanation:**
An audit kickoff meeting should clearly describe the scope and purpose of the audit as well as the expected time frame. Auditors should never approach an audit with any expectations about what they will discover because the findings should be developed based only upon the results of audit examinations.

---

## Question 90
**Correct Answer:** B

**Explanation:**
In the waterfall model, the software development process follows five sequential steps that are, in order, Requirements, Design, Coding, Testing, and Maintenance. Note that these phases may be further subdivided. The Requirements phase often begins with System Requirements and then moves on to Software Requirements. The Design phase often begins with Preliminary Design and then moves on to Detailed Design.

---

## Question 91
**Correct Answer:** C

**Explanation:**
In a platform-as-a-service solution, the customer supplies application code that the vendor then executes on its own infrastructure.

---

## Question 92
**Correct Answer:** D

**Explanation:**
Input validation ensures that the data provided to a program as input matches the expected parameters. Limit checks are a special form of input validation that ensure that the value remains within an expected range, but there was no range specified in this

scenario. Fail open and fail secure are options when planning for possible system failures.

---

## Question 93
**Correct Answer:** B, D

**Explanation:**
Dynamic application security tools conduct their testing by actually executing the code. This is the case for both fuzzing and web application vulnerability scanning. Code reviews and static analysis packages analyze the code itself but do not execute it, making them static application security testing (SAST) tools.

---

## Question 94
**Correct Answer:** C

**Explanation:**
The DevOps approach to technology management seeks to integrate software development, operations, and quality assurance in a seamless approach that builds collaboration between the three disciplines.

---

## Question 95
**Correct Answer:** A

**Explanation:**
Deploying a web application firewall (WAF) may reduce the likelihood or impact of a web application vulnerability and is, therefore, a good example of risk mitigation. Encryption is also a risk mitigation control, but it is less likely be effective against a web application security flaw. Purchasing an insurance policy is an example of risk transference, not risk mitigation. Discontinuing use of the software is an example of risk avoidance, not risk mitigation.

---

## Question 96
**Correct Answer:** D

**Explanation:**
Dirty reads occur when one transaction reads a value from a database that was written by another transaction that did not commit. Lost updates occur when one transaction writes a value to the database that overwrites a value needed by transactions that have earlier precedence, causing those transactions to read an incorrect value. Incorrect summaries occur when one transaction is using an aggregate function to summarize data stored in a database, while a second transaction is making modifications to the database, causing the summary to include incorrect information. SQL injection is a web application security flaw, not a database concurrency problem.

---

## Question 97
**Correct Answer:** A

**Explanation:**
The integrated product team (IPT) approach brought together cross-functional teams and was designed by the U.S. Department of Defense in 1995. It was a predecessor to the Agile methodology, which uses tools like the scrum approach and user stories to conduct software development work.

---

## Question 98
**Correct Answer:** B

**Explanation:**
Storage is an infrastructure component and, therefore, a block storage service is an example of an infrastructure-as-a-service (IaaS) cloud service. Software-as-a-service (SaaS) models provide full applications managed by the provider. Platform-as-a- service (PaaS) and function-as-a-service (FaaS) approaches allow developers to run their own code on an infrastructure platform managed by the provider.

---

## Question 99
**Correct Answer:** See Explanation

**Explanation:**
The code testing methods match to their definitions as follows: 1. Regression testing: C. A testing method that is used to verify that previously tested software performs the same way after changes are made 2. Integration testing: D. A testing method used to validate how software modules work together 3. Unit testing: B. A testing method that focuses on modules or smaller sections of code for testing 4. System testing: A. Testing on a complete integrated product

---

## Question 100
**Correct Answer:** See Explanation

**Explanation:**
The terms match to their definitions as follows: 1. Session hijacking: C. An exploitation method that often involves cookies or keys to gain unauthorized access to a computer or service 2. Cross-site scripting: A. An attack that injects a malicious script into otherwise trusted websites

3. Cross-site request forgery: D. An attack that forces a user to execute unwanted actions in a website or application they are currently logged into 4. SQL injection: B. An attack that is designed to execute commands against a database via an insecure web application

---

