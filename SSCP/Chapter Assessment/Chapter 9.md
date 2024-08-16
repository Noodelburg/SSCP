

## 1. Which statement about privacy and data protection is most correct?

* A. International standards and agreements specify that personally identifiable information (PII) and information about an individual’s healthcare, education, and work or credit history must be protected from unauthorized use or disclosure.
* B. Some countries, or regions like the EU, have laws and regulations that specify how personally identifiable information (PII) and information about an individual’s healthcare, education, and work or credit history must be protected from unauthorized use or disclosure. Other countries do not. It’s up to the organization that gathers, produces, uses, or disposes of such private data to determine what protection, if any, is needed.
* C. Storing backup or archive copies of privacy-related information in a datacenter in another country, without doing any processing there, does not subject you to that country’s data protection laws.
* ### D. Sometimes, it seems cheaper to run the risk of fines or loss of business from a data breach involving privacy-related data than to implement proper data protection to prevent such a loss. Although this might make financial sense, it is not legal or ethical to do so.

```
Option A is false; no such agreements apply worldwide. At best, regulations like the General Data Protection Regulation (GDPR) apply to EU member states. Option B is true as far as it goes, but with a catch: if the organization guesses wrong, it could end up in serious legal trouble in multiple jurisdictions. Option C is false; storage of data in a center in another country must involve movement of data from your jurisdiction into the one the datacenter is in and movement in the reverse direction when you need to use the backup. In almost all cases, data protection laws and regulations apply to data in use, at rest, and in motion.
```


## 2. Which of the following might be serious example(s) of “shadow IT” contributing to an information security problem? (Choose all that apply.)

* A. One user defines a format or style sheet for specific types of documents that other users will create and manage.
* B. An end user writes special-purpose database queries and reports used to forecast sales and project production and inventory needs, which are reviewed and used at weekly division meetings.
* ### C. Several users build scripts, flows, and other processing logic to implement a customer service help desk/trouble ticket system, using its own database on a shared use/collaboration platform that the company uses.
* ### D. Users post documents, spreadsheets, and many other types of information on a company-provided shared storage system, making the information more freely available throughout the company.

```
The key determiner of whether user-defined and user-maintained “stuff” is shadow IT is the amount of business logic that it embeds or implements; the more such business logic is built into uncontrolled or unmanaged apps or tools, the greater the risk of something going wrong in undetected ways. Thus, Option A is not a probable risk; Option B seems to have a lot of frequent, intensive review of the results of these queries, which would need to correlate or compare with what the production information systems would show. Option C implements customer relationship management and systems/product maintenance business logic; Option D seems to circumvent information classification, segregation of duties, and other access control principles. Both Options C and D bear close watching.
```

## 3. Which statements about the role(s) of archiving, backup, and restore in meeting information security needs are most correct? (Choose all that apply.)

* ### A. These each contribute to availability in similar ways.
* ### B. These each contribute to availability and nonrepudiation.
* ### C. As part of an incident response or disaster recovery plan, prompt restore to a known good data configuration may prevent other data from being compromised or breached, thus contributing to confidentiality.
* D. These have no role to play in achieving authentication needs.

```
Option D is incorrect. Authentication data, which defines user and process privileges, identity verification, and so forth, is as subject to being wiped out, corrupted, lost, or stolen as any other data on any information system.
```

## 4. In which phase or phases of a typical data exfiltration attack would a hacker be making use of phishing? (Choose all that apply.)

* A. Reconnaissance and characterization
* B. Data gathering, clumping, masking, and aggregating
* C. Installing and using covert command and control capabilities
* D. Initial access

```
Phishing and many other social engineering tactics have played a major role in over 60 percent of major data breaches in the past few years. Such tactics have high payoff to the attacker during their search for a possible target, gathering information about its systems and security, and then their initial entry into the target’s systems. Thus Options A and D are correct. Options B and C are almost exclusively done surreptitiously, exploiting information that social engineering may have revealed to the attacker; few if any signs of phishing in these activities have been noted.
```

## 5. Your coworkers don’t agree with you when you say that data quality is a fundamental part of information security. Which of the following lines of argument are true in the context of your discussion with them? (Choose all that apply.)

* ### A. If our business logic doesn’t establish the data quality rules and constraints, we have no idea if an input or a whole set of inputs makes valid business sense or is a spoof attack trying to subvert our systems.
* B. Since we don’t have a data quality program now, if we get served with a digital discovery order, who knows whether the data we surrender to the authorities is correct and complete? The attorneys might care, but that really has no effect on us.
* ### C. We have users who complain that when they try to test and evaluate backup data sets, the backup data makes no sense. If a real disruption or disaster strikes, and our backups don’t make any business sense, we could be out of business pretty quickly.
* D. We mitigate information risk to achieve the CIANA needs that the business impact analysis and the risk management plan called for; since those high-level plans didn’t conclude that we need a data quality program, then we probably don’t.

```
Option B is scary; it seems to assume that we can drown in data the government inspectors, auditors, or the attorneys who are suing us, and they’ll never figure out it is meaningless. Very risky business! Option D suggests that perhaps senior leadership just did not realize the potential impacts that bad data (or a lack of data quality) can have on maintaining confidentiality, integrity, availability, nonrepudiation, and authentication of all information-based business processes. Options A and C are real risks that many organizations face each day.
```

## 6. Sandi has suggested to her boss that their small company should be using a cloud-based shared storage service, such as OneDrive, Dropbox, or Google Drive. Her boss believes these are inherently insecure. Which of the following statements would not help Sandi make her case?

* A. Check the reputation and business model of the shared storage providers; check what national/legal jurisdiction they operate in, compared to the one her business operates in.
* B. Examine their stated, posted privacy and security policies; ask for a sample contract, terms of reference, or service level agreement, and see if they claim to provide what her company needs.
* C. Sandi can always encrypt her files before moving them into storage; that way, even if another user, a hacker, or the provider themselves try to read the file, they can’t.
* ### D. Sandi can take advantage of a free trial offer and see if her information security staff can hack into other users’ storage or into system logs and account information on the provider. If her “white hats” can’t break in and peek, the system is safe enough for her.

```
Option D is probably illegal in most of the jurisdictions in question; even where it is not, it is certainly unethical to attempt to evaluate a storage provider’s security by trying to hack into other customers’ data without their express written consent and the consent of the provider. The rest are reasonable and prudent parts of due care and due diligence checks on a candidate third-party provider of this type.
```

## 7. Which statements about continuity and resilience are correct? (Choose all that apply.)

* A. Continuity measures a system’s ability to deal with events the designers didn’t anticipate.
* B. Continuity and resilience are basically the same idea, since they both deal with how systems handle errors, component or subsystem failures, or abnormal operational commands from users or other system elements.
* ### C. Resilience measures a system’s ability to tolerate events or conditions not anticipated by the designers.
* ### D. Continuity measures a system’s ability to deal with out-of-limits conditions, component or subsystems failures, or abnormal operating commands from users or other system elements, by means of designed-in redundancy, load shedding, or other strategies.

```
Continuity is about planning for alternative modes of action—having a stack of “just in case” options already laid out in plans, procedures, software, or other IT elements. Thus, Option D is correct and Option A is false. Resilience is the ability to bend, adapt, tolerate, or even ignore unanticipated disruptions, without completely breaking down. Thus, Option B is incorrect, and Option C is correct.
```

## 8. What is the role of threat modeling when an organization is planning to migrate its business processes into a cloud-hosted environment? Choose the most correct statement.

* A. Private cloud deployments should see no change in threat modeling or threat surfaces.
* ### B. Migrating to the cloud may not change the logical relationship between information assets and subjects requesting to use them, or the way privileges are set based on roles, needs, and trust, but the connection path to them may change; this probably changes the threat surface.
* C. This really depends on the choice of IaaS, SaaS, or PaaS service models.
* D. Shared responsibility models will transfer much of the organization’s needs for information security services to the cloud-hosting provider, and they will apply their standard threat models to the chosen service and deployment models

```
Option A is false; it effectively assumes that private clouds are as secure as private datacenters or LANs and desktops. Option C is correct as far as it goes, since PaaS (for example) may provide platform-based controls while introducing additional boundaries (or threat surfaces). Option D is false and misstates the shared responsibility concept. Option B focuses on where to start thinking about the proposed migration and the role of threat modeling in planning for information security in the chosen cloud.
```

## 9. The “garbage-in, garbage-out” (GIGO) problem means:

* A. Noise on power supplies or signal cables can corrupt data in motion, which if processed can result in abnormal or incorrect “garbage” results.
* ### B. Most information processes involve a set of related data items that represent or model a real person, activity, or part of the world. When that set of data is mutually inconsistent, or inconsistent with other data on hand about that real entity, each field may be within range but the overall meaning of the data set is corrupt. This “garbage,” when processed (as input) by apps, produces equally meaningless but valid-looking outputs.
* C. Organizations that just throw away damaged storage devices; printed copies of their data, application source code, design notes; and so forth are putting this “garbage” right where a “dumpster diver” hacker attack can collect it, examine it, and possibly find exploitable vulnerabilities.
* D. Data input attacks can cause some applications to abort or execute abnormally, sometimes in ways that allow the garbage data that was input to be executed as if it is command strings or machine language instructions.

```
Option A is a real risk but not what GIGO is about. Option C may involve throwing things in the “garbage” that should have been destroyed or zeroized first, but it’s also incorrect. Option D is a very common attack attempt against many apps, but it usually does not lead to the application producing what looks like correctly formed outputs with distorted meanings. GIGO processing, as in Option B, can result in incorrect transactions being posted to an account, such as when a patient billing record has too many copies of the same lab procedure billed incorrectly to it.
```

## 10. Why is endpoint security so important to an organization?

* A. Users, who interact with organizational IT infrastructures and information at the endpoints, are notoriously difficult to control; if we can better control and secure the endpoints themselves, then we can prevent most end user–introduced security problems.
* ### B. Endpoints are where information turns into action, and that action produces value; on the way into the system, it is where action produces valuable information. This is where business actually gets done and work accomplished. Without the endpoints, the system is meaningless.
* C. Endpoints are what most users and customers see, and if endpoints are not secure, users and customers will not engage with our security programs and help us keep the system safe.
* D. While endpoints are where many users do information work, organizational managers and leaders draw their decision support at the systems level, and not from an endpoint device such as a smartphone. Data quality and software quality processes need to ensure that once data enters the system from an endpoint, it is then protected to meet CIANA needs throughout its life.

```
Option A is true insofar as it describes a common malware vector, but it misses the key point. Option C may be true in a very limited sense (police call this the “broken window” theory of urban crime control), but it misunderstands the role of the endpoints in an IT system. Option D is false; all output that humans can use is done at an endpoint, be that a laptop, a phone, an annunciator, a process control status board, or even a printer. Option B correctly captures the value proposition of information work and the high-leverage role of action that happens at endpoints.
```

## 11. Many issues are involved when planning for a third party to perform services involving data storage, backup and restore, and destruction or processing services for your company. Which of the following statements is not correct with regard to such planning or to your actual conduct of operations with that third party? (Choose all that apply.)

* A. Your data protection responsibilities remain with you; you need to be able to actively verify that such third parties are doing what you’ve contracted with them to do. Otherwise, you are blindly trusting them.
* ### B. Your contracts with these third parties should use a shared responsibility model to clearly delineate which party has which responsibilities; this will, in most cases, hold you harmless when the third party goes outside of the contract
* ### C. Since third parties are by definition on a contract with you, as your subcontractor, you are not liable or responsible for mistakes they make in performing their duties.
* D. What your third party providers, subcontractors, or employees (for that matter) do in your name and in your service, you are ultimately responsible for.

```
Option D most correctly states the bottom line to most organizations in terms of how stakeholders, investors, legal and regulatory authorities, customers, and others will judge responsibility when things go wrong. Option A is a specific example; due care requires that you have the contractual, technical, and administrative ways to do such verifications, while due diligence requires that you actually _do_ such verifications and hold the third party to task. Option B can only set day-to-day expectations; when a major data breach happens, Option D suggests that even if the service provider failed to fulfill their contract, your stakeholders will still hold you responsible. Option C is false.
```

## 12. Jayne’s company is considering the use of IoT devices as part of its buildings, grounds, and facilities maintenance tasks. Which statements give Jayne sound advice to consider for this project?

* A. Since IoT devices can easily be configured, updated, or patched, they are just as capable of being secure as are laptops, desktops, or smartphones.
* B. Functions that change frequently are well suited to IoT devices.
* C. Typical IoT devices are best suited to use where security or human safety are a primary concern.
* ### D. It may be better to consider industrial process control modules, rather than IoT devices, to interact with machinery, such as pumps and landscaping equipment.

```
Currently, most Internet of Things (IoT) devices are limited to performing only a few related functions; it is also as difficult if not impossible to configure their access control or other security features (if they have any), or update or patch their onboard firmware. This means that Options A and B are probably not correct. Option C is also doubtful for this same reason—would Jayne’s bosses want her to specify a human safety function be managed by an IoT device that anyone could hack into and subvert? Option D provides a sound alternative; the process control marketplace has many solutions available, all highly modularized.
```

## 13. Why is whitelisting a better approach to applications security than blacklisting? Choose the most correct statement.

* A. Whitelisting depends on government-certified lists of trusted software providers, whereas blacklisting needs to recognize patterns of malicious code behavior, or malware signatures, to block the malware from being installed and executed.
* B. For most organizations, the list of applications they have chosen to trust is far smaller and easier to administer than huge lists of malware signatures and behavioral models.
* ### C. Administering a whitelisting system can require a lot of effort, but when an unknown program is trying to execute (or be installed), you know it is not yet trusted and can prevent harm.
* D. With blacklisting only, new malware may not be recognized as such before it installs, executes, and begins to harm your systems and information.

```
Option C is correct in terms of the major benefit of whitelisting; Option D, its logical opposite, addresses the zero day risks of blacklisting approaches without saying why any other approach (such as whitelisting) is better. Option A is false on its face; no such program (thankfully!) exists to “trust-mark” applications. However, digitally signed installation kits do give some assurance that the software came from the vendor you thought provided it. Option B is true on its face but does not say why one approach provides better security than the other.
```

## 14. What steps can you take to limit or prevent attacks on your systems that attempt to spoof, corrupt, or tamper with data? (Choose all that apply.)

* A. Ensure that firewalls, routers, and other network infrastructures filter for and block attempts to access network storage without authorization.
* ### B. Develop and use an organizational data model and data dictionary that contain all data-focused business logic; use them to build and validate business processes and the apps that support them.
* ### C. Implement data quality processes that ensure all data is fit for all purposes, in accordance with approved business logic.
* ### D. Implement information classification, and use access control and identity management to enforce it.

```
Option A by itself won’t do what is needed; at a minimum, Option D and its implementation of rigorous access control and identity management is necessary to protect network storage resources from being corrupted, tampered with, and so on. The others are all valuable parts of a data governance and data security/data protection plan.
```

## 15. Which statements best explains why applications programs have exploitable vulnerabilities in them?

* A. Commercial software companies rush their products to market and pay little attention to designing or testing for security.
* ### B. In-house developers often do not rigorously use design frameworks and coding standards that promote or enforce secure programming.
* C. End users write most of the real applications that businesses use, but without configuration management, they’re impossible to update and keep secure.
* D. Most users do not keep their software updated, so they are missing out on security patches.

```
While many people feel that Option A is true, it’s an overgeneralization; most commercial apps go through rigorous design and testing, and include information security requirements. Option C exaggerates how much shadow IT exists, while ignoring the widespread use of platforms and services, productivity suites, etc. Option D addresses why apps already installed still have known vulnerabilities in them, but it does not address how those vulnerabilities got there in the first place. Option B is the number one reason we see the same kinds of errors, decade after decade, baked into new programs as they are written.
```

## 16. “Maintaining or improving information security while migrating to the clouds is more of a contractual than technical problem to solve.” Which statement best shows why this is either true or false?

* A. It is false. The contractual side is similar to any other service provider relationship and is done once; the technical challenge of mastering a whole new set of features and capabilities is far larger and is always ongoing.
* B. It is true. Cloud service models are constantly changing, and this means that the contracts, terms of service, or service level agreements are continually being updated. The underlying software technologies, however, don’t change as much or as frequently.
* C. It is false. The contractual agreements do change quite frequently as the underlying technologies, threats, and business case for both the cloud host and the customer change with time. These changes cause about equal amounts of work on both administrative and technical elements of the customer organization.
* ### D. It is false. The contractual agreements do change quite frequently as the underlying technologies, threats, and business case for both the cloud host and the customer change with time. However, even these changes cause less work, less frequently, for the administrative elements and more for the technical elements of the typical customer organization.

```
Option A is incorrect by oversimplifying the ongoing need to understand changing conditions and how these affect the business relationship between host and customer. Option B is false; cloud systems technologies, whether Azure, Google Cloud, or Amazon Web Services, are updated virtually every week, with changes impacting customer-migrated systems utility and security. Option C overemphasizes the administrative/contractual burden of change. Option D better reflects the need to thoroughly understand both the contractual and the technical up front and how the effort spent on both will likely change over time.
```

## 17. What are some effective, practical strategies to detect data exfiltration attacks? (Choose all that apply.)

* ### A. Analyze of access control and resource usage log data to alert when abnormal patterns of behavior are noted.
* ### B. Alert when failed attempts to access a resource (whether it is protected by encryption or not) exceed a specified limit.
* C. Use digital rights management in addition to other identity management and access control capabilities.
* D. Set filters and rules on network traffic, inspecting suspicious packets, streams, or addresses to check for data being exfiltrated.

```
Option C makes it harder for an unauthorized user to use a resource, whether it’s in its original form or it’s been copied and exfiltrated; this does not help detect an ongoing attack beyond what proper access control should do. Option D is easily thwarted by attackers when they restructure, clump, aggregate, encrypt, or disguise the data; the rules and filters don’t know what to look for as a result. Option A can reveal an attack in the early stages, but it is analysis intensive. Option B might usefully warn of attacks against data that is encrypted at rest but for which access control is not sensing a violation of privilege.
```

## 18. How does securing a virtual machine differ from securing a physical computer system?

* ### A. The basic tasks of defining the needs, configuring system capabilities in support of those needs, and then operationally deploying the VM are conceptually the same as when deploying the same OS and apps on a desktop or laptop. You use many of the same tools, OS features, and utilities.
* B. VMs cannot run without some kind of software-defined network and a hypervisor, which bring many more complex security concerns that administrators need to deal with to achieve required information security performance.
* C. VMs can access any resource on the bare metal machine that is hosting them through the hypervisor, which requires administrators to take many extra precautions to prevent security breaches.
* D. The bare metal server, host OS (if used), and hypervisor provide none of the security features you’ll need to configure to keep other system users, processes, and data, and those in each VM, safe, secure, and protected from each other.

```
Option B is partly correct but exaggerates the effort to set up an SDN or hypervisor. Option C is false, as it requires explicit actions by administrators to allow access to other system resources, devices, and so forth. Option D is also false, as the hardware, hypervisor, and host OS if used are where you start to define and configure VM images and the parameters that control their being dispatched to run and then retired.
```

## 19. Your boss tells you that securing the endpoints should consider all of the measures you would use to secure the information infrastructures themselves. Is she correct? Which statement best confirms or refutes her statement?

* A. False. Many of the things we do to secure operating systems and networks, for example, just don’t apply to an endpoint device, the apps on it, and the user’s interactions with it.
* ### B. True. After all, each endpoint is (by definition) embedded in or part of one or more threat surfaces; from there, the same threat modeling and assessment processes will lead us through the same risk management and mitigation processes, with choices tailored as needed.
* C. True. All of the same risk management, vulnerability assessment, risk mitigation, and operational risk management processes apply to each node of our system and to the system as a whole, tailored to the specific risks, vulnerabilities, technologies, and operational needs.
* D. False. What happens at the endpoints is a special case of information security and needs special attention that is very different than how we assess risk to servers, networks, or applications platforms.

```
Option A glosses over the growing “BYOx,” where x can be infrastructure, device, or most any service; you might argue that Option A also ignores the blurring of the boundary between an endpoint and the information system itself. Option B reminds us to do integrated, coherent threat modeling and analysis across our total systems environment. Option C just echoes what the boss said, although it does add a minor bit about tailoring; overall, it doesn’t contribute much to the conversation with the boss. Option D offers no support for this rather unusual viewpoint.
```

## 20. Fred is on the IT team migrating his company’s business systems into a public cloud provider, which will host the company’s processes and data on its datacenters in three different countries to provide load balancing, failover/restart, and backup and restore capabilities. Which statement or statements best addresses key legal and regulatory concerns about this plan? (Choose all that apply.)

* A. Because Fred’s company does not have a business office or presence in the countries where the cloud host’s datacenters are, those countries do not have legal or regulatory jurisdiction over company data.
* ### B. The countries where the cloud host’s datacenters are located, plus all of the countries in which Fred’s company has a business presence, office, or other facility, have jurisdiction over company data.
* ### C. In addition to staying compliant with all of those different countries’ laws and regulations, Fred’s company must also ensure that it does not violate cultural, religious, or political taboos in any of those countries.
* D. These jurisdictional arguments only apply to data stored on servers or systems within a given country, or that is being used in that country; nations do not control the movement of data across their borders.

```
Option A is false; the laws of the host nation apply to the cloud datacenter operator in that country, and that means they apply to all of the data and processing performed on that cloud datacenter. Option D is false, as nearly all countries claim the right to control the import and export of information, particularly (as in Option C) where that information violates, attacks, or ridicules a strong cultural, religious, or political value in that country. Options B and C are true.
```

