
## 1. Stream ciphers are normally selected over block ciphers because of?

* A. The high degree of strength behind the encryption algorithms
* ### B. The high degree of speed behind the encryption algorithms
* C. Their ability to use large amounts of padding in encryption functions
* D. Their ability to encrypt large chunks of data at a time

```
Stream ciphers are typically used for highly variable length plain-text inputs, such a streaming multimedia, digitized voice, and so forth.
```


## 2. What is the difference between a synchronous and asynchronous password token?

* A. Asynchronous tokens contain a password that is physically hidden and then transmitted for each authentication whereas synchronous tokens do not.
* ### B. Synchronous tokens are generated with the use of a timer whereas asynchronous tokens do not use a clock for generation.
* C. Synchronous tokens contain a password that is physically hidden and then transmitted for each authentication whereas asynchronous tokens do not.
* D. Asynchronous tokens are generated with the use of a timer whereas synchronous tokens do not use a clock for generation.

```
Option B correctly demonstrates synchronous (same time); Option D has this backward. Once the password is validated, the token is passed to subsequent processes that need to authenticate that subject’s access, such as in single sign-on systems. Thus Options A and C are incorrect.
```

## 3. This data backup strategy allows data backup to an offsite location via a WAN or Internet connection:

* A. Remote journaling
* ### B. Electronic vaulting
* C. RAID
* D. Clustering

```
Journaling makes note of changes (transactional). Vaulting provides full dataset backup. Other options address storage technologies.
```


## 4. RADIUS uses what kind of security model?

* A. Centralized
* B. Token-based
* ### C. Decentralized
* D. Whitelisting

```
Note that _centralized_ and _decentralized_ can be used to refer either to one vs. several servers, working in collaboration, to implement a single access control system, which is what RADIUS does, as well as refer to the strategy choice about one versus many places that decisions can be made across larger systems.
```


## 5. You are a member of your IT department’s incident response team, but you are not a trained forensics investigator. Which statement is most correct, regarding how your duties and tasks during or after an incident should consider the chain of custody?

* A. It has no real effect on your duties or tasks.
* ### B. It should dictate how thoroughly you make log entries or journal notes about each step you perform.
* C. It only affects your tasks if you have to zeroize, randomize, or cold start and restore a system or its memory.
* D. It limits what you can do without a forensics investigator’s approval or help.

```
Every action you take, whether on a computer or with papers and other objects at the scene, can change or corrupt evidence. The other options may, by themselves, put you at risk of corrupting evidence.
```


## 6. Which of the following is a principal component of an access control system?

* ### A. Objects
* B. Biometrics
* C. Crossover error rate
* D. Auditing/accounting

```
Access control defines a set of rules that constrain or allow access to objects.
```

## 7. As an SSCP, which statement bests describes your involvement with physical security?

* A. Little or no involvement; building or facilities management and any security guards should handle this.
* B. You ensure that key systems elements, such as server rooms and wiring closets, are kept locked at all times.
* C. You’re only involved with physical security of information assets and systems elements during security audits or penetration testing.
* ### D. You plan, help implement, review, and assess the physical security of IT systems and information assets, based on your organization’s prioritized risk mitigation strategy.

```
As an SSCP, all that you do should (moral imperative) be driven by the organization’s mission needs, including its risk management and mitigation strategies.
```

## 8. The process of identifying and evaluating risk based on level of importance is referred to as:

* A. Risk management
* B. Risk acceptance
* C. Risk transference
* ### D. Risk assessment

## 9. Which of the following does a digital signature not provide?

* A. Authentication
* ### B. Confidentiality
* C. Nonrepudiation
* D. Integrity

```
If confidentiality is required, encrypt the content after generating its digital signature.
```


## 10. The correct choice for encrypting the entire original data packet in a tunneled mode for an IPSec solution is?

* A. Generic Routing Encapsulation (GRE)
* B. Authentication Header (AH)
* ### C. Encapsulating Security Payload (ESP)
* D. Point-to-Point Tunneling Protocol (PPTP)

## 11. Intrusion detection systems (IDSs) and intrusion prevention system (IPSs) use analysis engines to make decisions. Which types of algorithms do many of these analysis engines use?

* A. Pattern and anomaly
* B. Blacklisting and anomaly
* ### C. Signature and protocol
* D. Anomaly and signature

```
“Anomaly detection” suggests detecting something not quite normal, which current analysis engines don’t support. Blacklisting is more of an access control or software installation and execution control.
```

## 12. Mobile device management (MDM) solutions are a good way for organizations to manage the requirements for protecting the use of mobile devices in accessing the network and its services. Which of the following is not supported by MDM solutions?

* A. Remote device locking
* B. Remote wiping capabilities
* ### C. Protection of the pin access to the device
* D. Virtual private network (VPN) configuration

```
Ultimately, endpoint security will rely on what the user knows, even if other factors are used as well.
```

## 13. Which of the following cloud deployment models would be best suited for state and local governments to use with businesses and individuals in their service areas?

* ### A. Public cloud
* B. Community cloud
* C. Hybrid cloud
* D. GovCloud

```
GovCloud is used for highly secure government activities. Community cloud is shared infrastructure, probably raising costs to each sponsoring organization, and potentially adds complexity to delivering public-facing information and services.
```

## 14. Which statement about phishing attacks is most correct?

* A. Phishing attacks are rarely successful, and so they pose very low risk to organizations.
* B. Spear phishing attacks are easy to detect with scanners or filters.
* C. You can safely reply to an email you don’t recognize and ask to be removed from their mailing list; this is not part of a phishing attack.
* ### D. Phishing attacks of all kinds are still in use, because they can be effective social engineering tools when trying to do reconnaissance or gain illicit entry into an organization or its systems.

```
Option A is false; even if thousands of phishing emails are sent as part of a low and slow attack, one response can generate exploitable information for the attacker. Option C is false; in doing so, you confirm that your email address connects to a real (and somewhat under-informed) person. Expect more. Option B is false; attackers work hard to mimic the style, format, expression, and construction of their phishing emails and continually attempt to spoof email addresses, domain names, and so forth. Tools may filter a lot of such junk email for you, but it won’t catch it all. Option D is most correct.
```

## 15. Which of the following describes a bus topology?

* ### A. Each node is connected to a single backbone cable.
* B. Each node is connected to a device such as a switch.
* C. Each node requires a physical connection to a bridge.
* D. Each node is separated using a dividing router.

```
A bus does not require any one node to be functioning or to pass information and control along to the next node, unlike a ring.
```

## 16. Audit reports usually contain which of the following sets of sections?

### A. Executive summary, detailed report
B. Scope, summary report
C. Executive summary, audit recommendations
D. Management response, audit findings

```
Management responds to the audit report after reading it; findings need to be reported before making recommendations.
```

## 17. Which of these is a characteristic of cryptosystems using symmetric encryption?

* A. Efficient and secure key distribution
* ### B. Fast encryption rates
* C. Very high work factors
* D. Well suited to user selection of keys and seeds

```
Key management is difficult to scale to large numbers of users; symmetric algorithms can be broken faster than asymmetric ones can. Thus, all that symmetric has going for it as an approach is its speed (which is why we use it in hybrid systems).
```

## 18. Which of the following penetration testing strategies best models what a real attacker might be able to achieve in an attack against an organization’s information systems?

### A. Double-blind
B. Blind
C. Internal
D. Targeted

```
Double-blind testing requires that the bare minimum of senior leadership, IT, and operational managers and staff know of the test, and that test team “attackers” are realistically acting as naïve outsiders, to make the test as realistic as possible.
```

## 19. Which of the following is the last step in any change control process?

A. Implementation of change
B. Monitoring of the change
### C. Notification of the completion
D. Testing of the change

```
The correct order for change control is to plan, assess, decide/direct, implement, test/verify, and notify upon completion. Monitoring throughout, as well as informed user involvement, is vital to informed consent and control.
```

## 20. Baselines are:

A. Collection of hardware and software
### B. Minimum levels of security
C. Step-by-step instructions
D. Suggestions

```
Baselines are both the sets of hardware, software, connections, and procedures, and the inventory listings of everything in a baseline and what its current version is.
```


## 21. A key escrow service is intended to allow for which of the following?

* ### A. Recovery of private keys
* B. Recovery of compromised public keys
* C. Transfer of private keys between users
* D. Storage of public keys

```
Note that any protocol supporting key escrow is only as secure as the escrow agent is trustworthy. So far, very few such proposals have won widespread trust and confidence in the market, and for good reason.
```


## 22. What is the first phase of an incident response process once the incident response team has been activated?

* A. Preparation
* B. Notification and escalation
* C. Containment and analysis
* ### D. Triage

```
First, identify the most critical potential impact or aspects of the incident, and work to contain and remediate those. The other options happen either before detection, or during all phases of response.
```

## 23. Which of the following penetration testing strategies best models what a real attacker might be able to achieve in an attack against an organization’s information systems?

* ### A. Double-blind
* B. Blind
* C. Internal
* D. Targeted

```
Double-blind testing requires that the bare minimum of senior leadership, IT, and operational managers and staff know of the test, and that test team “attackers” are realistically acting as naïve outsiders, to make the test as realistic as possible.
```

## 24. The type of data backup that only backs up files that have been changed since the last full backup is called?

* A. Full backup
* B. Incremental backup
* C. Partial backup
* ### D. Differential backup

```
Incremental backs up subsets of files regardless of the last update date but works through all files eventually. Partial just does a selected set of files—for example, for one user.
```

## 25. Which of the following statements about information risk management is true?

* A. Risk management is a major investment of time, effort, and money, and should only be done when major changes outside of the organization are happening.
* ### B. Risk management should be an ongoing, cyclic set of tasks, as part of maintaining constant awareness to a changing business and threat landscape.
* C. Risk management should be no more than an annual review activity, resulting in few actions to perform, for most small to medium-sized organizations.
* D. Risk management, like risk itself, is often best transferred to outside experts.

```
The people who own and run a business have ultimate responsibility for success or failure; if they choose to ignore risk by under-managing it, at best, they are gambling on bad things not happening.
```

## 26. Security requirements should be considered as what type of requirements?

* ### A. Functional requirements
* B. Nonfunctional requirements
* C. Unallocated requirements
* D. Allocated requirements

```
With today’s greater (and wiser) emphasis on security, nearly every security need can and should be linked to a verifiable, testable aspect or feature of the information architecture and the hardware, software, data, and procedures used with it.
```

## 27. Which statement correctly places layers of the Open Systems Interconnection (OSI) model in the correct order from highest to lowest?

* A. Transport, Application, Presentation
* ### B. Application, Presentation, Data Link
* C. Physical, Presentation, Session
* D. Session, Network, Transport

```
The layers from most abstract to least abstract are Application, Presentation, Session, Transport, Network, Data Link, and Physical.
```

## 28. Which of the following supports secure transmission of HTTP traffic?

* A. Kerberos
* ### B. Transport Layer Security (TLS)
* C. Secure Remote Password (SRP)
* D. Layer 2 Tunneling Protocol (L2TP)

```
TLS works at Layer 4 and above, which is where HTTPS operates.
```

## 29. The process of identifying and evaluating risk based on level of importance is referred to as:

* A. Risk management
* B. Risk acceptance
* C. Risk transference
* D. Risk assessment

```
Risk management includes multiple activities, such as risk assessment. Transference and acceptance are choices about how to deal with risks.
```

## 30. What is an authorization table?

* ### A. A matrix of access control objects, access control subjects, and their respective rights
* B. A service or program where access control information is stored and where access control decisions are made
* C. A listing of access control objects, policies, and procedures and their respective rights
* D. A record of all denied and permitted access control attempts

```
The table contains the information for making access control decisions; it does not make them, nor track the instances of results of such decisions. Thus Options B and D are incorrect. Policies and procedures are not part of this table.
```

## 31. During an incident response, what’s the most important set of limitations to keep in mind when searching or scanning systems, storage media, or an incident scene?

* A. Having the right connectivity to those systems or elements
* ### B. Legal limits regarding search or entry
* C. Company policies regarding access privileges
* D. Having the right tools and procedures to make the search meaningful during the incident response

```
Violating legal limits, such as searching a suspected attacker’s system, could put you in jeopardy of committing a computer crime yourself!
```

## 32. Which of the following is an example of a network device that uses context-based access control?

* A. Static packet filter
* B. Network intrusion detection system
* ### C. Stateful inspection firewall
* D. Virtual local area network

```
The correct option is C, which involves keeping track of how the client and server move through activities in a session, and looking for the abnormal, using a state table to define allowable transitions.
```

## 33. Which of these tasks would be part of managing information assets or IT assets?

* A. Implementing an acceptable use policy
* ### B. Reviewing your IT team’s approach to configuration management and control of software, hardware, and data
* C. Letting users decide when and how to perform software updates on endpoint devices they use
* D. Ensuring that all sensitive information, of any kind, is covered by nondisclosure agreements

```
Asset management involves knowing what systems, hardware, software, and other elements are used by the organization and ensuring that they are maintained and changed in authorized and controlled ways. Thus Option B is most correct. Option C suggests no management of endpoint software, which is very risky. Options A and D have nothing to do directly with managing IT or information assets, although they are important elements of an information security posture and program.
```

## 34. Most attacks today are happening at which layers of the Open Systems Interconnection (OSI) protocol stack?

* ### A. Presentation, Session, and Application
* B. Physical
* C. Data Link and Network
* D. Transport

```
The vast majority of attacks focus on web apps, which require protocols above the Transport layer.
```

## 35. Which of the following is not a Bluetooth-related attack?

* A. Bluesnarfing
* B. Bluebugging
* C. Bluejacking
* ### D. Bluetapping

```
The others involve unsolicited messaging (possibly leading to denial of service), data exfiltration by fraudulent access, and taking remote control of the Bluetooth device.
```

## 36. When you compare safety to security for information systems, which of the following statements is correct?

* ### A. When information security measures fail to keep critical data available and correct, the resulting system malfunctions could lead to loss of revenue, property damage, injury, or death.
* B. Operating a system in an unsafe manner could be introducing information that further corrupts the system, violating its integrity or leading to it crashing, which violates availability needs.
* C. Keeping a system safe also means “safe from harm,” and thus means much the same as keeping it secure.
* D. Safe system operation is the responsibility of its designers, builders, and operators; the information security people have no role in that, and thus safety and security are unrelated concepts.

```
“Safety” for information systems can mean keeping the system causing injury to others or damage to their property—to customers, users, or bystanders. Thus Option A is most correct. Option B is true as stated, but it reverses cause and effect and is thus incorrect. Option C makes no distinction between safety and security, which is incorrect. Option D is incorrect in that it tries to separate safety and security when they are in fact related to each other.
```

## 37. Which of the following would not be included as part of “hardening”?

* A. Disabling certain functionality
* B. Changing default passwords
* ### C. Initial information security training for all newly hired employees
* D. Physical security

```
While a well-trained work force with a strongly held security consciousness or culture is vital to safety and security, it takes far more than typical initial orientation training to achieve this. The rest are (or should be) part of normal computer security hygiene measures to the degree required by the risk assessment.
```

## 38. Cryptographic implementation attacks include:

* A. Random number generators
* ### B. Side channel
* C. Fault analysis
* D. Probing

```
Side-channel attacks rely on trying to infer internal behavior of the cryptosystem by externally observable signatures, such as noise or ripple on power lines and timing variations. Probing is a reconnaissance technique against web apps. The others are not related to cryptoattacks.
```

## 39. In the measurement of biometric accuracy, which of the following is commonly referred to as a “Type 2 error”?

* A. Cross-over error rate (CER)
* B. Rate of false rejection—false rejection rate (FRR)
* C. Input/output per second (IOPS)
* ### D. Rate of false acceptance—false acceptance rate (FAR)

```
Type 1 errors are false rejections.
```

## 40. Which statement regarding Recovery Point Objective (RPO) and Recovery Time Objective (RTO) is correct?

* A. RTO is always greater than RPO.
* ### B. RPO is about data recovery; RTO is about lost time from business activities.
* C. RTO refers to time before the disruption occurs, whereas RPO refers to a time after the disruption’s occurrence.
* D. RPO and RTO are always equal periods of time.

```
RPO is about how far back in time you fall back to re-accomplish transactions or other data changes; RTO is about how long you can afford to spend in incident response and recovery before lost business or other mission needs become too costly.
```

## 41. Which statement about precursors and indicators is most correct?

* A. Precursors are events that prepare the way for an attack, such as an intrusion, to take place.
* ### B. Precursors are the observable signals from an event, which may suggest that an information systems security event may happen later.
* C. Indicators are the observable signals from an event, which may suggest that an information systems security event may happen later.
* D. Indicators are events which are part of an information security incident kill chain; warnings are the observable effects that we can detect, that tell us of the occurrence of the indicator.

```
When it comes to incident detection, a precursor is an observable signal or result of an event, which may suggest to us that an event of interest—that is, a security-related event—may happen in the near future. Precursors do not, in themselves, suggest that the incident is currently happening. Thus A is false. Option C mistakes indicators for precursors. Option D confuses events with the observable signals from them—that is, the changes they make to target systems, which we can observe. “Warnings” in this context has no meaning—that is, our intrusion detection system (IDS) or intrusion prevention system (IPS) technologies detect indicators and issue alarms. Thus, B is most correct.
```

## 42. Everyone is responsible for following information policies, but who is ultimately responsible for information security?

* ### A. Senior management
* B. Information security team
* C. Users
* D. Auditors

```
Managing directors and even board of directors members are, legally, the ones with total responsibility for the organization, its assets, liabilities, and decisions. This does not and cannot change by delegating decisions and authority downward to subordinates.
```

## 43. Business logic is:

* A. A set of tasks that must be performed to achieve and objective within cost and schedule constraints
* B. The set of rules and constraints that drive a business to design a process that gets business done correctly and effectively
* C. Software and data used to process transactions and maintain accounts or inventories correctly
* ### D. The design of processes to achieve an objective within the rules and constraints the business must operate within

```
The logic is the set of steps and decisions necessary to achieve the objective; some of those decisions may compare intermediate results with constraints and then branch to alternate steps in the logic to make corrections, for example. The rules and constraints by themselves are not the business logic. Processes (software or people procedures) are not the business logic, but they should accurately and effectively implement that logic.
```

## 44. The ALE (annualized loss expectancy) calculation is an example of which of the following?

* A. Threat identification
* B. Qualitative risk analysis
* ### C. Quantitative risk analysis
* D. Vulnerability management

```
Identify the threat and the corresponding vulnerabilities; if you can, estimate the numbers for frequency of occurrence, single loss exposure, and so forth. If you cannot reasonably estimate, you can characterize as high/medium/low (qualitative analysis). Vulnerability management, not a normal term that we use, would refer to mitigation efforts.
```

## 45. Which types of networks are not prone to sniffing or eavesdropping?

* A. Wi-Fi
* B. IP over fiber
* ### C. Virtual private networks (VPNs)
* D. IPv6

```
Packet sniffing or eavesdropping is not confined to the physical layer. VPNs, with their bulk encryption of routing and payload data, all but exclude packet sniffing type of attacks.
```

## 46. An access control implementation where access permissions are allocated based on several subjects performing identical or similar functions is referred to as:

* A. Rule-based access control
* B. Discretionary access control
* ### C. Role-based access control
* D. Temporal access control

```
One subject (person or process) may be capable of performing many functions (roles), each of which may require different access control constraints or conditions.
```

## 47. Your boss says that since everything the company does with its information is all in the cloud platforms they use, the company have no need for physical security. How might you best respond?

* A. That’s correct, since the cloud services provider and our ISP handle physical security for their systems and everything using them.
* ### B. Actually, we still rely on our endpoint devices and our local area networks and connectivity; plus, we still have a lot of paper-based business processes and records that we keep.
* C. That’s a good point, and since our office spaces are secured and alarmed by the building’s owners and managers, they’ve provided for the rest.
* D. We could simplify the physical IT security situation even more, or eliminate it as a worry completely, if we shifted over to a bring-your-own-device strategy for everything.

```
Endpoint security and noncomputerized information still need physical protection, including paying due care and due diligence to back up, restore, archive, and other needs. No amount of bring-your-own (be it device, cloud, or infrastructure) will make that part of your threat surface go away.
```

## 48. Why is escalation part of the detection and analysis phase of an incident response?

* A. It will require additional resources, such as IT staff, to begin carrying out the next phases of the response plan, and this would require management approval and action.
* ### B. Management and leadership need to know that an information security incident may have occurred, and that investigation continues. Depending on the nature of the incident as understood thus far, management may need to take additional action.
* C. Most organizations are unwilling to delegate authority to an incident response team leader, and thus need to control every action, in order to exercise due diligence.
* D. This is required by NIST SP 800-61 Rev. 2, and in regulations that apply to the particular business or organization.

```
Option A is incorrect; this may be a consequence of the way that the team’s detection, response, and recovery responsibilities are defined and supported, but it’s not generally the case. Option C is incorrect; though this might be true in some organizations, it is not related to due diligence and misstates that concept. Option D is incorrect; NIST publications provide guidance, while federal regulations can make them obligatory on federal and other government activities, they do not in general dictate what the private sector must do. Option B is correct; management and leadership may have legal, regulatory, or business reasons for knowing immediately that an incident might have occurred or might be occurring, but they cannot fulfill those obligations if no one on the response team tells them about it.
```

## 49. Which document documents the steps that should be performed to restore IT functions after a business disruption event?

* A. Critical business functions
* B. Business continuity plan
* ### C. Disaster recovery plan
* D. Crisis communications plan

```
The disaster recovery plan (DRP) lays out the step-by-step activation of more detailed response procedures. The other plans provide framework, context, or specific support (communications to public and staff alike).
```

## 50. Which of the following social engineering attacks do not attempt to masquerade as legitimate business or social correspondence?

* A. Phishing
* B. Whaling
* C. Spear phishing
* ### D. Scareware

```
Scareware attempts to masquerade as warnings from antimalware or other security software.
```

## 51. One of the most common types of vulnerabilities in web-based applications is related to:

* A. Hard coding of encryption or other security control parameters in HTML or other web page source code
* ### B. Failure to properly validate all input data
* C. Allowing users to run unsigned macros or scripts as part of using the application’s features and logic
* D. Inadequately protecting or securing built-in test or diagnostic capabilities in the application itself

```
This classic security flaw is completely preventable, if only software developers and their managers enforced lessons learned regarding input data validation.
```

## 52. Which of the following is a major problem associated with cryptography?

* ### A. Key management
* B. Education
* C. Out-of-band communications
* D. Permutations and transpositions

```
If your keys are not kept secret, you have no security. All else are details of building, using, and managing cryptosystems.
```

## 53. Which canon of the (ISC)2 Code of Ethics would best apply in the following scenario? You work on the IT team at a medical insurance claims processing company that handles over a million patient claims per year. A recent vulnerabilities assessment indicates that patient data of all types is not encrypted, at all, and that the systems could easily be breached and the data exfiltrated from the company. Rather than spend the money and effort to harden the system, management has chosen to transfer this risk in part to liability insurance for its managing directors, and in part to the patients themselves in case a breach and data loss does occur.

* A. Act honorably, honestly, justly, responsibly, and legally.
* B. Provide diligent and competent service to your principals.
* C. Advance and protect the profession.
* ### D. Protect society, the common good, necessary public trust and confidence, and the infrastructure.

```
The greater potential for harm is to the individual patients, who have implicitly trusted your company to protect their data, their money, and their lives as you handle their claims.
```

## 54. How is the data plane used in digital networks?

* A. It is used to pass control parameters to network devices such as routers, switches, and firewalls.
* B. It separates the flow of user data from the flow of network management information, thus providing additional security.
* C. It describes how payload data flows between and within network elements.
* ### D. It is both the circuits and mechanisms by which data flows through the network, and the logical description of data flows within a network.

```
The “planes” provide both a logical perspective on networks, as well as very effective circuit-level design and implementation.
```

## 55. What might be the most important things that an audit report should communicate to senior management?

* A. Specific details of systems, data, and files audited
* B. Identify missing or out-of-date procedures and documentation
* C. Specific details of errors discovered by the auditors
* ### D. Recommendations for reducing risks, increasing compliance to required levels, or other recommendations for process and product improvement

## 56. Which of the following is not an example of data packet switching technologies?

* A. X25
* B. ATM
* C. Frame relay
* ### D. Peer-to-peer

```
Peer-to-peer normally applies to services provided by one system to another without a server, thus at higher than the network layer.
```

## 57. Which of the following is not a standard service model in cloud computing?

* A. Software as a service
* B. Platform as a service
* ### C. Private cloud as a service
* D. Application as a service

```
“Private” refers to a single organizational tenant or user of the cloud, while the other options define how that cloud’s services will be provisioned, managed and used. Thus a “cloud” is not a “service.”
```


## 58. What is an authorization table?

* ### A. A matrix of access control objects, access control subjects, and their respective rights
* B. A service or program where access control information is stored and where access control decisions are made
* C. A listing of access control objects, policies, and procedures and their respective rights
* D. A record of all denied and permitted access control attempts

```
The table contains the information for making access control decisions; it does not make them, nor track the instances of results of such decisions. Thus Options B and D are incorrect. Policies and procedures are not part of this table.
```

## 59. Which step in the identity management process is where credentials or other attestations are confirmed or validated?

* A. Proofing
* ### B. Provisioning
* C. Revocation
* D. Deletion

```
The other options address how an identity is established, managed, or terminated once the subject’s claims to that identity have been ascertained to be true.
```

## 60. You work with a small start-up company that depends on dynamic collaboration with many outside agencies, companies, and academic organizations, as well as with its potential customers and investors, to turn ideas into products and marketing strategies. These ideas and strategies are the intellectual property of your employer and need to be protected, while at the same time they depend on collaboration to produce in the first place. Which of the following would you recommend be the first that the company invest in and make use of?

* A. More rigorous access control systems, using multifactor authentication
* B. More secure, compartmented collaboration software suites, tools, and procedures
* ### C. Better, more focused education and open dialogue with company staff about the risks of too much open collaboration
* D. Better work on our information risk management efforts, to include an information security classification process which our teammates can use effectively

```
Options A and B are incorrect; tempting as they are to the geek in us, they are not the first place that effort needs to be spent. Option D is a necessary and vital task, but given the dynamics of this organization, it sounds like Option C is the most immediate need. Getting this small group of people totally focused on protecting their own future while collaborating with many others in building that future is going to be key to success; thus, more dialogue (C) can lead to a better, more informed, and effective information risk management and classification approach (D).
```

## 61. Which statement highlights the major security benefit when comparing webs of trust with hierarchies of trust?

* A. Individual user decisions in webs of trust provide greater end-user confidence based on reputation.
* B. Hierarchies of trust systems are often implemented with open source solutions, free from vendor bias or manipulation.
* C. Both web and hierarchy systems provide comparable levels of security.
* ### D. The use of recognized and accepted authorities gives hierarchies of trust greater scalability and trustworthiness over time.

```
Certificate revocation (that is, publishing distrust of a user or trust provider) can be problematic in web of trust systems.
```

## 62. Which statement about containment and eradication is most correct?

* A. Containment and eradication are separate and distinct tasks; once containment is complete, the incident response team moves on to eradication of the causal agent(s).
* B. Containment and eradication usually involve the same tools and procedures, and so they often are performed simultaneously.
* C. Malware quarantine operations are an example of containment and eradication achieved with the same task.
* ### D. Containment primarily addresses shutting down connectivity between networks, subnets, systems, and servers. Eradication addresses locating the causal agents (malware, bogus user IDs, etc.) and removing them from each system.

```
Option A is incorrect; containment may occur system by system or host by host as the networks are segmented and isolated, and thus the eradication specialists can start cleaning systems as they are isolated (or the causal agents on them are contained). Option B is incorrect, because different tools are needed to disable network connections than you’d use to scan systems for malware, as an example. Option C is incorrect; malware quarantine is more an example of eradication combined with recovery. Option D correctly explains isolating systems and then cleaning them.
```

## 63. You are a member of your IT department’s incident response team, but you are not a trained forensics investigator. Which statement is most correct, regarding how your duties and tasks during or after an incident should consider the chain of custody?

* A. It has no real effect on your duties or tasks.
* ### B. It should dictate how thoroughly you make log entries or journal notes about each step you perform.
* C. It only affects your tasks if you have to zeroize, randomize, or cold start and restore a system or its memory.
* D. It limits what you can do without a forensics investigator’s approval or help.

```
Every action you take, whether on a computer or with papers and other objects at the scene, can change or corrupt evidence. The other options may, by themselves, put you at risk of corrupting evidence.
```

## 64. Which of the following is not an element of key management?

* A. Key storage
* ### B. Key space
* C. Key creation
* D. Key distribution

```
The key space is fixed by the choice of algorithm and the size (number of bits) of the key. The other options talk directly to what key management has to accomplish across a user population.
```


## 65. A Hashed Message Authentication Code (HMAC) works by?

* A. Adding a non-secret key value to the input function along with the source message
* B. Adding a secret key value to the output function along with the source message
* ### C. Adding a secret key value to the input function along with the source message
* D. Adding a non-secret key value to the output function along with the source message

## 66. Does a security awareness program need to be reinforced by policy?

* A. No, because specific constraints, such as acceptable use, address details necessary for effective security.
* B. Yes, to avoid users from being lulled into complacency and thinking that information security is someone else’s job.
* ### C. Yes, because the policies would carry the constraints and incentives for correct security behavior, while providing directives as to required tasks to perform.
* D. No; policies in general are not related to user training and education.

```
Policies are the best vehicle to communicate broad and enduring direction to the organization’s workforce or constituents; as such, they should reinforce and be reinforced by education, training, and on the job procedures.
```

## 67. In penetration testing, which of the following equates to zero, partial, and full knowledge testing?

* A. Blind, double blind, and white
* B. Reconnaissance, foot-printing, gathering
* ### C. Black, gray, white
* D. Black, full, double blind

```
A “black box” test is one in which you know nothing about what’s inside the box; you only know what you can learn by watching how it interacts with the outside world. A blind test is the test team having zero (insider) knowledge of the system being pen tested.
```

## 68. Due care means:

* A. Auditing your systems and procedures for compliance
* ### B. Doing what you have to do to fulfill your responsibilities
* C. Making sure that actions you’ve taken to fulfill your responsibilities are working correctly and completely
* D. Reading and reviewing the reports from subordinates or from systems monitoring data

```
Options A and C are both examples of due care; due diligence is the verification that all is being done well and that nothing is not done properly. Option D can be an important part of due diligence but is missing the potential for follow-up action. Option B is a correct example of due care.
```

## 69. Where would you find Address Resolution Protocol (ARP) being used?

* A. At the Transport layer
* B. At the Application layer
* C. At the Physical layer
* ### D. At the Data Link layer

```
ARP resolves IP to MAC addresses at the Data Link layer.
```

## 70. Selecting this type of alternate processing site would be appropriate when an organization needs a low-cost recovery strategy and does not have immediate system recovery requirements:

* A. Mirror site
* ### B. Warm site
* C. Hot site
* D. Mobile site

```
Hot site and mirror site mean the same thing (mirror all ongoing operations, as if in parallel).
```

## 71. A customer wants to keep cost to a minimum and has only ordered a single static IP address from an Internet service provider (ISP). Which of the following must be configured on the router to allow for all the computers to share the same public IP address?

* A. Virtual private network (VPN)
* ### B. Port Address Translation (PAT)
* C. Virtual local area network (VLAN)
* D. Power over Ethernet (PoE)

```
Dynamic Host Configuration Protocol (DHCP) will also be required, but if the router cannot map addresses and ports WAN-to-LAN, this won’t work.
```

## 72. Having a voice conversation over the Internet is referred to as:

* A. Multicasting
* B. Virtual collaboration
* ### C. VOIP
* D. Streaming

```
VoIP is defined as voice over Internet Protocol.
```

## 73. Key clustering represents the significant failure of an algorithm because?

* A. A single key should not generate different ciphertext from the same plain text, using the same cipher algorithm.
* ### B. Two different keys should not generate the same ciphertext from the same plain text, using the same cipher algorithm.
* C. Two different keys should not generate different ciphertext from the same plain text, using the same cipher algorithm.
* D. A single key should not generate the same ciphertext from the same plain text, using the same cipher algorithm.

```
If this were to happen, it becomes much easier to decrypt ciphertext without knowledge of the original key. The other options show a misunderstanding of how keys map plain text to ciphertext.
```

## 74. A security audit is best defined as?

* A. A covert series of tests designed to test network authentication, hosts, and perimeter security
* ### B. A technical assessment that measures how well an organization uses security policies and controls to protect its information assets
* C. The use of intrusion detection systems (IDSs) to monitor anomalous traffic on a network segment and logging attempted break-ins
* D. The hardening of systems before deploying them on the corporate network

```
Audits in general compare how well you understand, implement, and follow standards, practices, policies, and procedures.
```


## 75. Your organization is considering adding a series of penetration tests as part of its ongoing security assessments. It’s never done penetration testing before. What kind of tests would probably not be the best to start with?

* A. Double-blind testing against live production systems and environments
* ### B. Full knowledge testing against test and development environments
* C. Internal testing
* D. Targeted testing

```
Growing your organizational abilities to make good use of penetration testing should (as in all things) start small and work your way up and out. Starting on test and development systems, which are not (normally) externally visible, is prudent.
```

## 76. A key employee seems to have gone missing while on an overseas holiday trip. What would you recommend that management do immediately, with respect to identity management and access control, for your federated access systems? (Choose all that apply.)

* * A. De-provision the employee’s identity.
* B. Suspend all access privileges for the employee’s identity, except for email, in case the employee tries to use it to contact the company for help.
* ### C. Suspend all access privileges for the employee’s identity, and notify all federated systems partners to ensure that they take similar steps.
* ### D. Suspend all access privileges for devices normally used by the employee, such as their laptop, phablet, or phone (employee-owned, company-provided, or both). If possible, quickly establish a captive portal or quarantine subnet to route access attempts from these devices to.


## 77. Does each layer of security need to have preventive, detective, and corrective capabilities?

* A. No, only the highest-priority vulnerabilities in your threat surface need all three control types.
* B. Yes, because you’ll need to be able to detect, isolate, contain, and correct even threats that are not layer dependent.
* ### C. Yes, but there will be situations in which elements at higher levels of security in your architecture will have to manage, direct, or perform these functions for elements at lower levels.
* D. Yes, but oftentimes, other elements in other layers of your security architecture will need to reach further in, in order to be able to detect, isolate, or correct.

```
Risk mitigation by means of countermeasures (to detect, prevent, correct) must be cost-effective; trade-offs will have to be made. When this happens, the “reach” should be from higher levels of security down to detect, prevent, or correct.
```

## 78. What is the most often-overlooked weakness in the way that layered defenses are built and operated?

* A. Integrated, automated systems status, state, and health checks that can validate proper update and patch levels, malware definition files, etc., are installed correctly
* B. Synchronizing the clocks on all devices throughout the organization’s systems and networks
* C. Monitoring and analysis of data from all security sensor devices
* ### D. Having seamless, integrated communications with all elements, at all layers, of the defense, as part of integrated command and control of the total security architecture

```
While the other options are vital components of a strong, layered security architecture, without the communications, command, and control ability to integrate it and operate it seamlessly, the systems are still at significant risk.
```


## 79. Which of the following technologies provides a means to evaluate network traffic flows and, based on a range of configurable rules, alert of possible compromise or rule anomalies?

* A. Terminal Access Controller Access Control System (TACACS)
* ### B. Network Intrusion Prevention (NIPS) or Detection (NIDS) Systems
* C. Server-based firewalls
* D. Security information and event management (SIEM)

```
None of the other options examine network traffic flows.
```

## 80. What is the process of using a key encrypting key (KEK) to protect session keys called?

* A. Key storage
* B. Key escrow
* C. Key generation
* ### D. Key wrapping

```
The other options reflect different aspects of key generation, management and recovery, but do not address session key encapsulation (wrapping).
```

## 81. The primary concerns of the information security practitioner are:

* A. That network and systems access controls prevent any unauthorized access or penetration into the organization’s systems
* B. That all security plans, procedures, and policies issued by senior organizational management and leadership are implemented effectively
* C. The security and availability of the hardware, software, communications, and data that make up the IT infrastructure the organization depends on
* ### D. That all information systems, assets, processes, and data are kept secure, safe, reliable and available, in accordance with the organization’s overall risk management posture and plan

```
All risks pertaining to the information the organization needs in order to survive and conduct its business are what the information security professional must focus on. That includes all of the other options and more.
```

## 82. Which of the following is true regarding computer intrusions?

* A. Covert attacks such as a distributed denial-of-service (DDoS) attack harm public opinion of an organization.
* B. Overt attacks are easier to defend against because they can be readily identified.
* ### C. Network intrusion detection systems (NIDSs) help mitigate computer intrusions by notifying personnel in real time.
* D. Social engineering attacks are less effective than technical attacks.

```
DDoSs are not typically done via intrusions. Just because you know the attack is coming or is happening may not make defending against it any easier. Social engineering is a fundamental part of most advanced persistent threat kill chains for one reason; it gains the attacker information and access.
```

## 83. Nonrepudiation of a message ensures that a message:

* ### A. Can be attributed to a particular author
* B. Is always sent to the intended recipient
* C. Can be attributed to a particular recipient
* D. Is always received by the intended recipient

## 84. Why are shadow IT systems an issue for information security?

* A. These are exploits and malware found on the dark web and, as such, must be considered hostile to your organization’s goals and objectives. They should be banned from the business and its systems by policy.
* ### B. Most are written by well-intended users and may be widely used by people in the organization, but quite often they are not subjected to even the most basic software quality assurance measures and are outside of configuration management and control. Hence, they pose potential risks to the IT architecture.
* C. Organizations routinely spend more time double-checking the results of such systems, which is effort that could be spent on other problems.
* D. As long as common vulnerabilities have been addressed (for example, by blocking the use of unsigned macros in Microsoft Office), shadow IT components are no more likely to introduce risks than other IT systems.

```
Option B correctly describes what shadow IT systems are; thus Option A is false. Option C demonstrates that in many cases, it cannot be shown that shadow IT systems taken as a whole correctly perform business logic or that they attain the C-I-A levels commensurate with the impacts if they fail. Option D is false; custom software systems such as these are normally not reported to common vulnerability channels.
```

## 85. As part of your organization’s IT security team, how would you expect to be involved in changes or updates to the system?

* A. Reviewing every proposed change to the software, hardware, communications, or data
* ### B. Participating during audits of the configuration management and systems build logs and records
* C. Testing major changes or updates to operating systems or applications
* D. No involvement; the IT staff of developers, testers, and the configuration management technicians should be the only ones involved with systems changes.

```
Most organizations do not need IT security staff involved in reviewing every patch, update, or change being applied to a system; thus, A and C are incorrect. Option B identifies a key due diligence role that IT security can perform and directly contradicts Option D, which is incorrect.
```

## 86. Accountability for protecting information rests with whom?

* ### A. Owner
* B. User(s)
* C. Data custodian
* D. Systems administrators

```
Owners may depend on these or other persons as part of achieving required levels of information security, but they cannot delegate their ultimate responsibilities.
```

## 87. Which statement best explains whether cryptography can protect data in use?

* A. Yes, provided asymmetric encryption is used.
* B. Yes, provided that endpoint device security using Mobile Device Management (MDM) systems are installed and working properly.
* ### C. No, because most use of data, by people or other systems, requires data to be decrypted for use to be meaningful.
* D. No, because homomorphic encryption is not in widespread use as part of the infrastructure.

```
MDM approaches to device security help but do not keep data encrypted while it is being used. Choice of algorithm has no bearing on this. And while some analytics processing may be possible on data encrypted homomorphically, actual transaction processing of encrypted data seems unlikely.
```

## 88. Which of the following provides a security benefit of using fiber-optic cabling over any other cabling technology?

* A. Faster data rates and throughput
* B. Less data remanence possibilities
* ### C. Harder to tap into
* D. Less attenuation

```
None of the physical media themselves have much of a data remanence vulnerability; the other options do not affect security.
```

## 89. What term is associated with criticality?

* ### A. Availability
* B. Reliability
* C. Integrity
* D. Resiliency

```
Availability embraces concepts such as maximum allowable outage or time to restore, all based on mission needs; this is what “critical” means.
```

## 90. A university records database application is used by academic advisers to access records about course enrollment, financial aid, and other information. If a record contains information about a special needs accommodation, the adviser may be denied access to the existence of the student’s request for such accommodations or information such as doctors’ statements that attest to the need. Only specific university staff would have the necessary access control rights to view records that contain any information about medical or other justifications for special accommodation. In this scenario, what would be the most appropriate access control model to deploy?

* A. Discretionary access control
* B. Context-based access control
* ### C. Content-dependent access control
* D. Role-based access control

```
Option D is incorrect, since same employee can access all fields of other records. Option B is incorrect, since there are no constraints set for time of day and so forth. Option A is incorrect, because nothing in the scenario addresses changes to security policies or attributes. Option C is correct: content-dependent means presence or absence of data that meets constraint conditions.
```

## 91. Asymmetric key cryptography is used for which of the following?

* A. Steganography, access control, nonrepudiation
* ### B. Encryption of data, nonrepudiation, access control
* C. Nonrepudiation, steganography, encryption of data
* D. Encryption of data, access control, steganography

```
Steganography, so far, has not shown utility or need to use encryption algorithms on top of its watermarking application.
```

## 92. Social engineering attacks still present a threat to organizations and individuals for all of the following reasons, except:

* A. Most targeted individuals don’t see the harm in responding or in answering simple questions posed by the attacker.
* B. Most people believe they are too smart to fall for such obvious ploys, but they do anyway.
* ### C. Most targeted individuals and organizations have effective tools and procedures to filter out phishing and related scams, so they are now better protected from such attacks.
* D. Most people want to be trusting and helpful.

```
Options A, B, and D all demonstrate the hallmarks of social engineering attacks—they work (and have worked for thousands of years) because people are generally trusting, open, and willing to engage with strangers. Option C, the correct choice, is unfortunately not true; tools may help filter out some email-based social engineering attacks, but few organizations have truly been able to operate with a “loose lips sink ships” approach and deal openly with customers, clients, and many other outside stakeholders.
```


## 93. A botnet can be characterized as which of the following?

* A. Type of virus
* ### B. Group of dispersed, compromised machines controlled remotely for illicit reasons
* C. Group of dispersed machines controlled remotely
* D. Network used solely for internal communications

```
Botnets do need networks to run on, and while viruses may be part of the ways that attackers capture (take control) of a system, the tools to take such control are not part of the network of bots (or zombies, as they are also known). By definition, conversion of a system to a zombie or element of a botnet is an attack.
```

## 94. Access control is based on which set of elements?

* ### A. Objects, subjects, and rules
* B. Multifactor authentication and access tokens
* C. Attributes and roles
* D. Hierarchies of trust

## 94. Why is effective incident management dependent on a well-written and communicated policy?

* A. Because it gives senior leaders and managers the tools they need to manage the incident responders.
* B. If things go wrong during incident response, such policies can provide proof of prior due care and due diligence.
* ### C. Personal stress levels can be high during incident response; written, well-understood policy and procedures form a solid base for training, which can contribute to minimizing overreaction or impulsivity.
* D. The absence of such policies, and demonstrated efforts to communicate them to staff, can jeopardize postincident forensics investigation.

## 95. Under what circumstances can an information systems security audit be conducted without relying on certified, qualified external auditors?

* A. There are no such circumstances in which this could be legal or advisable.
* ### B. As part of informal or in-house efforts to assess risk or identify management challenges
* C. As part of the response to a serious information security incident
* D. As a way to reduce costs and complexity involved in preparing compliance reports

```
Informal audits can be great ways to familiarize staff with compliance requirements and controls used by the organization, or to illuminate possible risks or the absence of controls. They should never be used in circumstances involving legal or regulatory compliance concerns, or possible litigation.
```

## 96. Which of the following statements about virtualization is correct?

* A. A Type 2 hypervisor runs directly on the bare metal.
* B. Virtualization provides a way to reduce software licensing costs, since only one copy of an operating system or applications platform is needed.
* C. Only a Type 1 hypervisor can support using the same bare-metal processor to host multiple, different operating systems.
* ### D. Individual virtual machines can communicate with each other via networks, passing files in shared storage areas, but not by direct memory-to-memory transfer of data.

```
It’s important to appreciate that virtual machines (VMs) need to communicate to what’s outside of them, and in doing so, they’re as much a part of the threat surface as real central processing units (CPUs) are.
```

## 97. Which of the following is not true of policies?

* A. Policies are what are called “directive” controls.
* B. Policies direct or mandate the behavior of the employees of the organization.
* C. Policies prescribe how an organization manages, protects, and distributes information.
* ### D. Policies are often a collection of ideas.

```
Policies state, assert, or direct required behavior.
```

## 98. There are many good reasons why even the smallest business or organizations should worry about configuration management and patch management, including all of the following except:

* A. Uncontrolled and unmanaged “push” updates to operating systems and critical applications can disrupt your business activities.
* B. Your employees can make changes to their endpoints, or to systems they access with those endpoint devices, in ways that can disrupt your business.
* C. Change management, including access control systems, are your first line of defense against attackers.
* ### D. Change management and control processes can help your users be better informed so that they can do their jobs better.

```
User knowledge and awareness of changes is a vital part of change management and control, but it is part of the process, not the goal. The other options all address aspects of risks and vulnerabilities, and the role of change management in reducing those risks.
```

## 99. Which statement about subjects and objects is not correct?

* ### A. Subjects are what users or processes require access to in order to accomplish their assigned duties.
* B. Objects can be people, information (stored in any fashion), devices, processes, or servers.
* C. Objects are the data that subjects want to access in order to read it, write to it, or otherwise use it.
* D. Subjects are people, devices, or processes.

```
Subjects, by definition, want to do something that involves an object. Thus, Option A has these roles reversed. Subjects can be any kind of entity that can take action. Objects contain information, but also can provide requested services (i.e., take action upon request), so B and C are correct.
```

## 100. The amount of time or effort required to break an encryption algorithm is referred to as the:

* A. Key strength
* B. Computational infeasibility
* C. Measure of merit
* ### D. Work factor

```
Computational infeasibility means it’s just not practical or possible to invert (logically reverse) some encryption algorithms; hence, they are asymmetric. Key strength is related to key length for a given algorithm. Measure of merit generally means how well suited the chosen algorithm is, all around, to the needs of the users.
```

## 101. When comparing Transmission Control Protocol (TCP) and User Datagram Protocol (UDP), which statement is most correct?

* A. As a connectionless protocol, UDP provides greater reliability than TCP.
* ### B. As a connectionless protocol, UDP is well suited to multicasting of streaming media.
* C. As a connection protocol, UDP provides greater reliability and error correction.
* D. TCP lacks the ability to handle error detection and retransmission, so is more of a best-efforts protocol.

```
Best-efforts basis with no handshake for retransmit request means UDP is connectionless and suited for uses that are tolerant of packet dropout.
```

