### (star) integrity property: **In the Biba model, this requires that a subject cannot write to an object at a higher security level (no "write down"** 
### (star) security property: **In the Bell-LaPadula model, this requires that a subject may not write information into an object that is at a lower sensitivity level (no "write-down")**

# A
### AAA : **Authentication, authorization, and accounting; the three essential functions of an access control and identity management system.**

### Accept (a risk): **In risk management terms, to choose to do nothing to reduce the estimated impact of a risk; being self-insuring, assuming that the safeguard values incurred over time will not be worth the avoided losses of the risk if it occurs. Recognize that a risk exists, and understand its potential impact, but choose to do nothing to deal with it.**

### Access control list (network): **Routers, firewalls, and intrusion protection systems have their own onboard control parameters that are used to enable or disable access for selected addresses, ports, services, periods of time, or other conditions as dictated by information security needs.**

### Access control list (system): **For a given access control system, the central repository of all the identities of subjects and objects, as well as the verification and validation information necessary to authenticate an identity and to authorize the access it has requested. In centralized access control systems, there is one access control list; decentralized systems would have one access control list in each access control server systems for each partition of the access control space.**

### Accounting: **In access control terms, this records information on all access attempts and the results of those attempts. Accounting provides the tools and processes that instrument the access control process, that monitor what subjects actually do with the objects they’ve been granted access to, and how the access session finally comes to a close (that is, does it end properly, abnormally, or with a system or app crash?). This provides the audit trail by which we address many key information security processes, each of which needs to ascertain (and maybe prove to legal standards) who did what to which information, using which information.**

### Address Resolution Protocol (ARP): **A discovery protocol by which a network device determines the corresponding IP address for a given MAC address by (quite literally) asking other network devices for it. On each device, ARP maintains in its cache a list of IP address and MAC address pairs. Failing to find the address there, ARP seeks to find either the DHCP that assigned that IP address, or some other network device whose ARP cache knows the desired address.**

### Advanced Persistent Threat (APT): **A threat actor who uses a protracted series of intrusions, reconnaissance efforts, and attempts to insert and establish command and control of a target’s information systems, as part of an effort to exploit the target for the attacker’s gain. APTs’ use of small, simple, and subtle techniques during the early phases of their attacks have been nicknamed “low and slow,” similar to smugglers flying in well under the radar as they attempt surreptitious entry.**

### Agent vs Agentless Access Control: **Describes whether the NAC system is relying on trusted agents within access-requesting endpoints to reliably report information needed to support authentication requests, or whether the NAC does its own scanning and network inventory or uses other tools to do this.**

### Annual Loss Expectency (ALE): **The estimate of the total loss or impact from a given risk, normalized to a one-year period.**

### Annual Rate of Occurrences (ARO): **An estimate or count of how many times each year a specific risk may occur.**

### Asset Management: **The process of identifying everything that could be a key or valuable asset and adding it to an inventory system that tracks information about its acquisition costs, its direct users, its physical (or logical) location, and any relevant licensing or contract details. Asset management also includes processes to periodically verify that “tagged property” (items that have been added to the formal inventory) are still in the company’s possession and have not disappeared, been lost, or been stolen. It also includes procedures to make changes to an asset’s location, use, or disposition.**

### Asset-based Risk Assessment: **Using tangible assets (such as datacenters, assembly lines, equipment, or people) or intangible assets (such as data sets, business records, or other information) as the focus of impact analysis, vulnerability assessment, and then risk mitigation and control decisions.**

### Assymmetric Encryption: **A cryptographic process that uses very different mathematical processes for encryption and decryption, and thus very different encryption and decryption keys. The algorithm should be chosen such that it is computationally infeasible (not practical) to take the ciphertext and back-compute the original plaintext from it, or compute the corresponding decryption key, even if the attacker has the encryption key itself.**

### Attack Surface: **The set of entities, information assets, features, and elements that are the focus of reconnaissance, intrusion, manipulation, and misuse, as part of an attack on an information system.**

### Attribute-based Access Control (ABAC): **These systems combine multiple characteristics (or attributes) about a subject, object, or the environment to authorize or restrict access. ABAC uses Boolean logic statements to build as complex a set of rules to cover each situation as the business logic and its information security needs dictate.**

### Authentication: **In communications systems, the verification that the sender or receiver is who they claim to be, and then the further validation that they have been granted permission to use that communications system.**

### Authentication (of an identity): **In identity management, the act of examining or testing the identity credentials provided by a subject that is requesting access, and, based on information in the access control list, either granting (accepts) access, denying it, or requesting additional credential information before making an access determination.**

### Authorization: **After authenticating the identity of a subject, the access control system must then determine whether the specifics of the access request are allowed by the permissions set in the access control tables.**

### Avoid (a risk): **In risk management terms, to change what you do, and how you do it, in such ways as to not be where your attacker is expecting you to be when they try to attack you. This can be a temporary change to your planned activities or a permanent change to your operations. Also referred to as eliminating a risk.**

# B

### Basis of Estimate: **The data, measurements, and logic used to establish an estimate of cost or value.**

### Bell-LaPadula access control model: **This model emphasizes protecting the confidentiality of information and enables the construction of systems handling multiple levels of classified information (such as Unclassified, Confidential, Secret, and Top Secret, in military terms). It places priority on preventing data classified at one level from leaking out or being exfiltrated to a process running at a lower security classification level.**

### Best-effort Basis: **The expectation that for services being requested and delivered, the server will do what is reasonable and prudent but will not go to extraordinary lengths or spend significantly greater resources attempting to make sure that the service is performed, regardless of errors, link failures, or other unforeseen problems. Nothing asserts that if a device’s firmware does things the “wrong” way that its errors will keep it from connecting, getting traffic sent and received correctly, or doing any other network function. Nothing also guarantees that the sender’s traffic will go where they want it to, and nowhere else, that it will not be seen by anybody else along the way, and that it will not suffer any corruption of content.**

### Biba Access Control Model: **Model that emphasizes data integrity over confidentiality by preventing unauthorized modification of information.**
### BLOBs: **Binary large objects; unit of measure by which cloud storage users can define and allocate storage independent of the actual disk drive or storage technology and its allocation units.**

### Block Ciphers: **An encryption system that encrypts the input plaintext by first breaking it into a series of blocks of individual symbols, typically of fixed block length, and then encrypting and decrypting the block as if it was a single symbol. A block of 64 bits (eight 8-bit bytes) can be thought of as a 64-digit binary number, which is what the encryption algorithm would then work on. Block ciphers typically have to pad the last block of a fixed-length plaintext message (such as a file or an email) so that each block has the required length.**

### Blockchain: **A series of messages, each with its own message digest, that taken together represent a transaction history about an item of interest; the message digest for the first block is computed normally, and then this is used as an input into the message digest for the next block, and so on. Thus, any attempt to make a change to the content of a block will invalidate all subsequent block-level message digests.**

### Bluetooth: **A short-range wireless radio interface standard, designed to support wireless mice, keyboards, and other devices, typically within 1 to 10 meters of the host computer they are being used with. Bluetooth is also used to support data synchronization between smart watches and fitness trackers with smartphones. Bluetooth has its own protocol stack, with one set of protocols for the controller (the time-critical radio elements) and another set for the host. There are 15 protocols altogether. Bluetooth does not operate over Internet Protocol networks.**

### Bring your own Cloud (BYOC): **The practice of individual employees using personal cloud storage systems, such as OneDrive or Dropbox, as part of the IT systems that they use  adddddddto perform their work-related tasks. BYOC calls attention to the potential information security, data integrity, and data quality issues that can arise if BYOC is not subject to adequate policy guidance and procedural control.**

### Bring your own Device (BYOD): **Policies and procedures for when organizational IT infrastructures have to deal with computing and communications equipment, software, security tools, and data that do not belong to the organization and are not under its legal span of control.**

### Bring your own infrastructure (BYOI): **A greatly expanded version of the BYOD problem set that calls attention to the potential security issues that arise when smartphones, laptops, or phablets, and even wearable computing devices bring hotspot connectivity, shared storage, and even shared or personally managed cryptographic resources to the workplace.**

### Broadcasting: **Sending of information to a wide audience, such that each audience member receives the same content**

### Bump-in-the-stack: **Nickname for IPSec implemented as a separate set of functions that sit (in effect) between the device drivers and the operating system’s IP stack.**

### Bump-in-the-wire: **Nickname for IPSec implementations using external cryptoprocessors (that is, cryptographic processors not under the direct control of the operating system).**

### Bus Topology: **A network topology that connects multiple nodes together, one after the other, in series. The bus provides the infrastructure for sending signals to all of the nodes, and for sending addressing information (sometimes called device select) that allows each node to know when to listen to the data and when to ignore it.**

### Business Continuity Plan (BCP): **Plans that are produced by business continuity planning, that are at the “high tactical” level: they use the strategic plans of the organization as context to take the prioritized core business processes (as defined by the BIA), specifying the tasks needed to recover from such a disruption. This includes all phases of incident response. BCPs do not normally go into the step-by-step operational details necessary to achieve effective preparation, response, or recovery; they rely on other, subordinate plans and procedures to do so.** 

### Business Continuity Planning: **Considers how to keep core business logic and processes operating safely and reliably in the face of disruptive incidents; it also looks at how to restore these core processes after they have been disrupted.**

### Business Impact Analysis (BIA): **A consolidated statement of how different risks could impact the prioritized goals and objectives of an organization.**

### Business Logic: **The set of ideas and knowledge that the owners and managers need to be able to set up the business and operate it effectively, along with the constraints, special conditions, or other limits that the business must operate within.**

### Business Plan: **A document that captures what the business owners want to achieve and how they intend to do that. Typically, a business plan shows planned activities over a span of time (perhaps several years), shows startup and ongoing costs of operating the business, and projects revenues from those operations.**

### Business Process: **A sequence of tasks that accomplishes a business function or objective, with steps assigned to people or organizational units, information flows, IT, physical equipment, or other business assets.**

# C

### Captive Portals: **An access control remediation approach that restricts access to a select set of webpages. These pages would instruct the endpoint’s user how to perform and validate the updates, after which they can retry the access request.**

### Catphishing: **Involves the creation of an entirely fictitious persona; this “person”   then strikes up what seems to be a legitimate personal or professional relationship with people within its operator’s target set. Catphishing originated within the online dating communities, but we’ve seen several notorious examples so far of its use in attack strategies that do not involve romance.**

### Casual Agent: **A software process, data object, hardware element, human-performed procedure, or any combination of those that perform the actions on the targeted systems that constitute an incident, attack, or disruption. Malware payloads, their control and parameter files, and their carriers are examples of causal agents. Bogus user IDs, hardware sniffer devices, or systems on your network that have already been suborned by an attacker are examples of causal agents.**

### Centralized Access Control: **Implemented using one system to provide all identity management and access control mechanisms. This system is the one-stop shopping point for all access control decisions; every request from every subject, throughout the organization, comes to this central system for authentication, authorization, and accounting.**

### Certificate:  **A digital assertion that the identity of the certificate holder and the public key associated with that certificate are linked or bound with each other.**

### Certificate Authority (CA): **The anchor node of a hierarchy of trust, issuing the certificates that bind individual identities with their corresponding public keys.**

### Chain of Custody: **(1) the sequence of each step taken to originally gather evidence, record or copy it, put it into storage, and then control and keep account of persons or processes that accessed that evidence; it further has to account for anything that was done to the evidence. Gaps in this chain of custody suggest that someone had the opportunity to tamper with the evidence, at which point, whether or not the tampering occurred, the evidence is worthless. (2) The detailed records that account for each piece of evidence, from the time it is first collected, through every use of that evidence by any person for any purpose. These records prove that a responsible person had custody of the evidence at all times, even when the evidence is transferred from one person’s possession and control to another. This prevents impeachment of the evidence (attempts to claim that the evidence had been tampered with and is not reliable).**

### Character Ciphers: **The use of individual symbols in the plaintext as the unit to encrypt and decrypt, much like the simple, classical substitution and transposition ciphers did. Also called symbol ciphers.**

### C-I-A: **Confidentiality, integrity, and availability, with respect to information or information systems. Also written as CIA.**

### CIANA: **Confidentiality, integrity, availability, nonrepudiation, authentication; an expanded and more demanding set of information security characteristics than CIA, by elevating nonrepudiation and authentication to equal importance.**

### CIDR: **Classless Inter-Domain Routing; introduced to help simplify both the notation and the calculation of subnets. CIDR appends the number of subnet address bits to the main   IP address. For example, 192.168.1.168/24 shows that 24 bits are assigned for the network address, and the remaining 8 bits are therefore available for the node-within-subnet address. (Caution: Don’t get those backward!)**

### Ciphertext: **The output of an encryption process applied to a plaintext input; an encrypted file, stream of symbols, or message content, with its meaning obscured.**

### Cleartext: **(1) The portion of text, data, or message content data that is never intended to be transmitted, stored, or used in anything but an unencrypted form with its meaning and value available to anyone to read, or (2) another term for plaintext, albeit subject to confusion.**

### Collisions (Cryptographic): **Flaws in encryption and decryption algorithms that allow for either (1) two different plaintext phrases mapping (encrypting) to the same ciphertext phrase, or (2) two different ciphertext phrases mapping (decrypting) to the same plaintext phrase. If either occurs, you lose the ability upon decryption to determine which was the correct and intended plaintext.**

### Common Vulnerabilities and Exploitations: **Databases that provide up-to-date information about vulnerabilities found in commonly available hardware, software, and firmware elements of IT systems, including operating systems, applications, and platforms; also includes information about known and reported exploitations that target these vulnerabilities.**

### Community of Practice: **An informal grouping of like-minded individuals who share in the study, practice, or use of a given set of procedural knowledge.**

### Company-owned Personally enabled (COPE): **Strategies in which the organization owns and exerts some configuration management, application whitelisting, and security feature enforcements on the device that it issues to an individual employee. The employee can then (within policy limits) install applications and data for work-related or purely personal use. Also known as corporate-owned personally enabled.**

### Competitive advantage: **The use of business logic, proprietary information, or techniques in ways that allows one business to enjoy greater success than its competitors do.**

### Computer Emergency response team (CERT): **A team of people with the primary responsibility to respond to potential information systems security incidents, systems failures, or degradation of performance that threatens to significantly disrupt the organization’s normal operations. Also called a computer security incident response team (CSIRT).**

### Computing Hygiene: **Commonsense, reasonable best practices to keep information systems safe from the threats of unauthorized use, malware infection, loss of data, or damage to the systems themselves.**

### Configuration Control: **The process of regulating changes so that only authorized changes to controlled systems baselines can be made. Configuration control implements what the configuration management process decides and prevents unauthorized changes. Configuration control also provides audit capabilities that can verify that the contents of the controlled baseline in use today are in fact what they should be.**

### Configuration Management: **The process by which the organization decides what changes in controlled systems baselines will be made, when to implement them, and the verification and acceptance needs that the change and business conditions dictate as necessary and prudent. Change management decisions are usually made by a configuration management board, and that board may require impact assessments as part of a proposed change.**

### Connectionless Communication: **Information flow that does not use preestablished routing; each packet carries its own sender and recipient address information and can be routed independently of any others.**

### Connection-oriented Communication: **Information flow between nodes using a preestablished set of information that identifies sender, recipient, and routing information. The connection is set up (via handshaking), used for communication, and then terminated (via additional handshaking or a timeout) at the end of communications.**

### Containment: **The process of identifying the affected or infected systems elements, whether hardware, software, communications systems, or data, and isolating them from the rest of your systems to prevent the disruption-causing agent and the disruption it is causing from affecting the rest of your systems or other systems external to your own.**

### Contingency Operations Planning: **Extends the business continuity planning process   into more detailed and specific subplans and procedures that may be necessary to get   the business back into operation, if perhaps in a limited way, after a disruption. This can embrace a variety of approaches, depending on the nature of the business logic in question, such as: alternate work locations for employees to use; alternate communications systems, internal and external, to keep employees, stakeholders, customers, or partners in touch, informed, and engaged; information backup, archive, and restore capabilities, whether for physical backup of information and key documents or digital backups; and even temporary staffing, financial, and other key considerations.**

### Continuity: **A characteristic of a system’s design that reflects the degree to which a system can produce correct, timely results when input errors, missing data, failed or failing subsystems, or other problems are impacting its operations.**

### Control Plane: **Provides all of the processes, functions, and protocols for switching, routing, address resolution, and related activities; this is both a design abstraction or concept, and a physical implementation at the circuit level in network and communications hardware and software.**

### Controlled Paths: **Pathways, channels, or connections of any kind, deliberately created by systems builders or managers, that allow subjects on one side of the threat surface to access objects on the other side. Such paths or portals should contain features that authenticate subjects prior to granting access.**

### Covert Path: **An unintended or unauthorized intra-system channel by which two cooperating entities can transfer information in ways that violate the system’s security and integrity policies but does exceed the entities’ current access privileges. The most prevalent covert path in all systems is the human one.**

### Critical Asset Protection Planning: **Looks at the protection required for strategic, high- value or high-risk assets, in order to prevent significant loss of value, utility, or availability of these assets to serve the organization’s needs. These can be people, intellectual property, databases, assembly lines, or almost anything that is hard to replace and almost impossible to carry on business without.**

### Critical Path: **In risk management terms, a sequence of tasks or steps in a business process, such that there are no easy, affordable, or practical alternative ways to achieve the same results or outcomes; thus, successful performance of each task or step is critical to success.**

### Cryptanalysis: **The study of vulnerabilities (theoretical or practical) in cryptographic algorithms and systems and the use of exploits against those vulnerabilities to break such systems.**

### Cryptographic Algorithm: **The formal definitions of the processes we use to encrypt plaintext into ciphertext and then decrypt ciphertext back to plaintext. It defines or specifies a series of steps—some mathematical, some logical, some grouping or ungrouping of symbols, or other kinds of operations—that must be being applied, in the specified sequence, to achieve the required operation of the system.**

### Cryptographic Algorithm Validation Program: **A NIST program that provides validation testing and certification of FIPS-approved and NIST-recommended cryptographic algorithms. The program also sets testing standards for use by cryptographic and security testing (CST) laboratories.**

### Cryptographic Engineering: **The science and engineering practice of building, optimizing, deploying, using, and strengthening cryptographic systems**

### Cryptographic module: **Any combination of hardware, firmware, or software that implements cryptographic functions (as per FIPS 140).**

### Cryptographic Module Validation Program (CMVP): **A joint American and Canadian security accreditation program for cryptographic modules, for use by these nations’ government agencies and regulated industries (healthcare, financial institutions, etc.)  that handle sensitive information not subject to higher government classification levels. Certification by the Cryptographic Algorithm Validation Program (CAVP) is a prerequisite for submission to the CMVP.**

### Cryptographic Primitives: **Mathematical or other elements that exhibit some kind of cryptographic property in ways that can relate to real cryptographic problems. Cryptographic research focuses on these.**

### Cryptographic Protocols: **(1) The use of cryptography itself in the operation of a cryptographic system, which typically can refer to key management and key distribution techniques, or (2) the use of cryptographic systems and techniques to solve a particular problem.**

### Cryptographic System: **All the elements we need to make a specific application of cryptography be part of our information systems. It includes the algorithm for encrypting and decrypting our information; the control parameters, keys, and procedural information necessary to use the algorithm correctly; and any other specialized support hardware, software, or procedures necessary to make a complete solution.**

### Cryptography: **The use and practice of cryptographic techniques to obscure and protect information at rest, in motion, and at use; this includes operations and functions for encryption decryption, cryptographic hash, and other uses.**

### Cryptolinguistics: **The translating between human languages to produce useful information, insight, or actionable intelligence (which has little to do with cryptography).** 

### Cryptology: **The combined study of cryptography (the secret writing) and cryptanalysis (trying to break other people’s secret writing systems or find weaknesses in your own).**

### Cybernetics: **The study of control systems.** 

# D

### Data: **The symbols and representations of observable facts, or the results of performing measurements and estimates.**

### Data cleaning: **Processing of data to remove errors and inconsistencies.**

### Data Encapsulation: **Wrapping a data payload using symmetric encryption, typically using a session key.**

### Data Loss: **The unauthorized movement of data from within an information system, by means of data theft, inadvertent disclosure, or the loss of an endpoint device that contained copies of the data in question.**

### Data Modeling: **A formal process that translates the business logic into named data elements. It formalizes the constraints for initialization of each data item; how new values are input, calculated, produced, and checked against logical constraints; and how to handle errors in data elements.**

### Data Plane: **The set of functions, processes, and protocols that move or forward frames and packets from one interface to another; this is both a design abstraction or concept, and a physical implementation at the circuit level in network and communications hardware and software.**

### Data Processing: **Applying logic and reasoning to make sure that all of the observations conform to an acceptable quality and consistency standard.**

### Data Quality Assurance: **Processes or procedures that look end-to-end at everything involved in the way the organization acquires external data, generate their own data internally, and specify what they do with it. Data quality assurance captures the business logic that is necessary to say that a given input is correct in content, in meaning, and in format. Then it enforces business logic that restricts the use of that data to valid, authorized processes and further specifies who in the organization can use those processes.**

### Data Remanence: **The data that remains on or in a device or system after it has been  shut down, powered off, or even physically removed from the larger information system   it is a part of. Data can and often does remain on devices that are no longer functional (such as hard disk drives that have suffered a head crash); without proper zeroization or randomization efforts, disposing of obsolete or nonfunctional devices or systems presents a very high risk of data exfiltration.**

### Data Semantics: **The use of metadata and usage data to attain greater insight into the meaning of data and the meanings behind or associated with its use and misuse.**

### Data Smoothing: **Removing data samples that are sufficiently out of normal, expected ranges or tolerances; they indicate a mistaken observation and should not be used in further processing.**

### Datagram: **The unit of information used by a protocol layer or a function within it. It’s the unit of measure of information in each individual transfer.**

### Decentralized Access Control: **Segments the organization’s total set of subjects and objects (its access control problem) into partitions, with an access control system and its servers  for each such partition. Partitioning of the access control space may reflect geographic, mission, product or market, or other characteristics of the organization and its systems. The individual access control systems (one per partition) have to coordinate with each other to ensure that changes are replicated globally across the organization.**

### Decision Assurance: **Increasing our confidence in our ability to make decisions by protecting the availability, reliability, and integrity of the four main components of the decision process: (1) The knowledge we already have (our memory and experience), including knowledge of our goals, objectives, and priorities; (2) new information we receive from others (the marketplace, customers, others in the organization, etc.); (3) our cognitive ability to think and reason with these two sets of information and to come to a decision; and (4) taking action to carry out that decision, or to communicate that decision to others, who will then be responsible for taking action.**

### Decode: **Translating an encoded message or idea from its representation as a set or stream of symbols back into a form where its meaning can be understood and used.**

### Decryption: **The process of un-obscuring or revealing the meaning of an encrypted message and restoring it so that its original meaning is intact and revealed.**

### Demilitarized Zone: **The subset of organizational systems that are not within the protected or “bastion” systems perimeter. Systems or servers within the DMZ are thus exposed to larger, untrusted networks, typically the entire Internet. Public-facing Web servers, for example, are outside of the DMZ and do not require each Web user to have their identity authenticated in order to access their content. Data flows between systems  in the DMZ and those within the protected bastion must be carefully constructed and managed to prevent covert paths (connections into the secure systems that are not detected or prevented by access controls), or the exfiltration of data that should not go out into the DMZ and beyond.**

### Design Pattern: **A recommended method, procedure, or definition of a way to accomplish a task. Experience and analysis have shown us that such design patterns can be built successfully and used safely to achieve correct results.**

### Detect: **In risk management terms, to notice or consciously observe that an event of interest is happening.**

### Deter: **In risk management terms, to discourage or dissuade someone from taking an action because of their fear or dislike of the possible consequences.**

### Deterministic: **A process that, given the same initial starting conditions and sequence of inputs, will produce the same sequence of outputs.**

### Diameter (Access Control): **An enhanced version of RADIUS that has inherent incompatibilities with the network structures that support RADIUS.**

### Digital Nomads: **Information workers of all kinds whose work and lifestyles no longer are centered around a fixed place of abode or work.**

### Disaster Recovery Plan (DRP): **Plan that looks to ways to prevent a disruption from turning into panic or hysteria, while at the same time meeting the organization’s due care and due diligence responsibilities to keep both stakeholders and the community informed.**

### Disaster Recovery Planning: **Strategic and tactical planning that must concern itself with significant loss of life, injury to people, damage to organizational assets (or the property or assets of others), and significant disruption to normal business operations.**

### Discretionary Access Control: **Allows the systems administrators to tailor the enforcement of these policies across their total population of subjects. Many operating systems, such as Microsoft Windows, come preconfigured with a discretionary access control model as the default.**

### Discretionary Security Property: **Requires that systems implementing Bell-LaPadula protections must use an access matrix to enforce discretionary access control.**

### Domain Name System (DNS): **Provides the translation of human-readable, meaningful addresses (such as www.wiley.com) into the IP address needed to route Internet traffic to. DNS consists of a set of servers that resolve domain names into IP addresses, registrars that assign and issue both IP addresses and the domain names associated with them to parties who want them, and the regulatory processes that administer those functions.**

### Due Care: **The responsibility to fully understand and accept a task or set of requirements, and then ensure that you have fully designed and implemented and are operating systems and processes to fulfill those requirements. This is both a legal and ethical responsibility.**

### Due Diligance: **The responsibility to ensure that the systems and processes you have implemented to fulfill a set of requirements are actually working correctly, completely, and effectively. This is both a legal and ethical responsibility.** 

### Due Process: **A process that defines the right and correct way to do a particular task; that process specifies all of the correct steps that must be taken, constraints you must stay within, and requirements you must meet in order to correctly perform this task. Although we normally think of this as due process of law—meaning that the government cannot do something unless all of the legal requirements have been met—due process is also a useful doctrine to apply to any complex or important task.**

### Dynamic Host Configuration Protocol (DHCP): **Assigns IPv4 (and IPv6) addresses to new devices as they join the network. This set of handshakes allows DHCP to accept or reject new devices based on a variety of rules and conditions that administrators can use to restrict a network. DHCP servers allow subscriber devices to lease an IP address for a specific period of time (or indefinitely); as the expiration time reaches its half-life, the subscribing device requests a renewal. DHCP is a cross-layer protocol.**

### Dynamic IP Address: **Assigned each time that device connects to the network. ISPs most often use dynamic assignment of IP addresses to subscriber equipment, since this allows them to manage a pool of addresses better. The end user’s subscriber equipment (modem, router, PC, or laptop) then needs a DHCP server to assign them each a LAN segment IP address.** 

# E

### Emergency Zeroization: **A process to ensure that no cryptologic materials can be recovered by an adversary if they are attempting to seize or take control of the system. In such circumstances, rapid physical destruction is often the last choice of methods but one that is often built into such systems just in case it is needed.**

### Encode: **Using protocols or rules of grammar and syntax to represent ideas as a stream or set of symbols, such as an alphabet.**

### Encryption: **The process of taking a message written in one set of symbols (and its syntax and semantics) and hiding or obscuring its meaning by changing the way the message is written.** 

### Endpoint: **Any device, such as a server, workstation, laptop computer, smartphone,  or an Internet of Things (IOT) device, at which the data that is inside the IT system is transformed into displays or action in the real world and the real world is transformed  into data to be put inside that IT system. All information systems have endpoints; all information-based processes either start with an endpoint to begin modeling the real world “out there,” end with an endpoint to influence that real world (usually through the actions of the endpoint’s human user, or a peripheral device attached to the endpoint), or both.**

### Eradication: **The process of identifying every instance of the causal agent and its associated files, executables, and so forth from all elements of your system.**

### Evidence: **Information created as a by-product of an information security incident that may provide knowledge of the identity of the attacker, the nature of their attack, and the damages incurred by the attack; used as part of forensic investigations in support of internal administrative action, litigation, or even criminal prosecution or defense actions.**

### Exfiltration: **The unauthorized movement by copying of data from within an information system, whether by an authorized user or an external, unauthorized attacker. Data exfiltration is legally defined as theft in many nations’ criminal law systems.**

### Existential Risk: **A risk that could end the existence of the organization, business, or company affected by it.**

### Exposed Cost: **The combination of the costs of all aspects of the impact of a risk, times the expected frequencies of occurrence, times their probabilities of occurrence.**

### Explicit Knowledge: **Knowledge that is recorded in some physical or electronic form and that can be read or used directly by others.**


# F

### False Negative Access Control Error: **Errors in which the system rejects a legitimate factor, thus erroneously denying access. Also known as Type 1 or false rejection errors.**

### False Positive Access Control Errors: **Errors in which the system accepts as genuine a presented factor that is not authentic, thus erroneously granting access. Also known as Type 2 or false acceptance errors.**

### Federated Identity and Access Control Management: **Provides mechanisms for sharing identity and access information, which makes identity and access portable, allowing properly authorized subjects to access otherwise separate and distinct security domains. Federated access uses open standards such as the OASIS Security Assertion Markup Language (SAML) and technologies such as OAuth, OpenID, various security token approaches, Web service specifications, Windows Identity Foundation, and others. Federated access systems typically use Web-based SSO for user access (which is not to be confused with SSO within an organization’s systems). Just as individual platform or system access is logically a subset of SSO, SSO is a subset of federated access.**

### Firewall: **A network device or system that selectively blocks some traffic from crossing the boundary protected by the firewall, while allowing other traffic to pass through. Firewalls can use a variety of techniques ranging from simple access control lists (such as by blocking some ports and authorizing or denying connections from certain IP or MAC addresses), or use deeper inspection of the packets, combined with heuristics, pattern recognition, or signature analysis as part of their filtering process. Firewalls can do either stateful or stateless inspection, based on whether they attempt to track and model a series or set of actions, or just packet by packet.**

### Forward Secrecy: **Sometimes called perfect forward secrecy, this is a characteristic of asymmetric cryptographic algorithms such that the session keys used to encrypt plaintext will not be compromised if the private key of the server is compromised. This protects other past encrypted sessions from being decrypted (assuming they were intercepted and recorded), provided the protocol used generates unique session keys for each session. Symmetric encryption alone cannot provide forward secrecy.**

### Functional Impact: **The degree to which an information systems security incident impacts the organization’s ability to perform its business processes, achieve its objectives or desired outcomes, or deliver goods and services to its external customers and internal users.**

### Functional Requirement: **A software engineering term that refers to a task, activity, or action that the system has to perform.**

# G

### Gap Analysis: **In information security risk assessment, gap analysis focuses on places where the functions performed by one element of the system do not quite meet the expectations or needs of the next element in line in a process chain, and thus may indicate an exploitable vulnerability or point of possible failure.**

### Gemba: **In quality management terms, the place where work that creates value actually gets done, typically by applying knowledge to input materials to produce products, services, or elements thereof.**

### Glueware: **Small programs, shell scripts, or even procedures for humans to perform that integrate parts of a larger system or process together. Glueware often escapes the notice of formal configuration management and control systems and may contain undetected, exploitable vulnerabilities if it is not also included in formal vulnerability assessments.**

### GovCloud: **Cloud hosting services tailored to meet the needs of the U.S. federal government and its support contractors, for either single-agency use or multiagency activities.**

### Graceful Degradation: **A design characteristic that attempts to keep a system operating safely, producing correct results but perhaps at decreased capacity, as elements fail or as input data errors occur.**

# H

### Handshake: **A sequence of small, simple communications that we send and receive, such as hello and goodbye, ask and reply, or acknowledge or not-acknowledge, which control and carry out the communications we need. Handshakes are defined in the protocols we agree to use.**

### Heuristics: **Rules generated by observing the behavior of a system or subsystem; often used in intrusion detection systems.**

### Hirarchies of Trust: **Collections of trust relationship in which one trust anchor provides the central authority for all chains of trust in the collection, via transitive trust relationships with other nodes. Provides for clearer ways to revoke trustworthiness of lower-level nodes.**

### Homomorphic Encryption: **An encryption process that allows for complex data analytics to be performed on many individually encrypted data items to produce a meaningful, aggregate answer—without needing to decrypt any of the input data and without revealing its plaintext or exposing it to attack. This relies on the mathematical properties of cyclic groups.**

### Honeypot: **A sacrificial system placed on the outward-facing areas of the organization’s network. It may use copies of production systems (such as webpages and Web-facing databases), new versions of such systems, or cut-down, limited-capability versions of production environments. The purpose of a honeypot is to allow an attacker limited, controlled access to the organization’s systems so that more can be learned about systems vulnerabilities by watching the attacker attempt to exploit vulnerabilities in those systems.**

### Host-based Intrusion Detection System (HIDS): **An IDS system that is installed as a software application that runs on a host computer, under the control of its operating system, such as a server, workstation, laptop, or smartphone or other mobile devices. HIDSs are installed so that they become part of the operating system boot sequence, much like antivirus systems are, and they typically work by focusing on attempts to violate access control policies and mechanisms.** 

### Human Security Behaviour: **The set of human activities, behaviors, and decision processes (conscious or subconscious) that enable users either to be effective elements of the organization’s security posture or to become part of its security problems.**

### Hybrid Cloud: **The set of human activities, behaviors, and decision processes (conscious or subconscious) that enable users either to be effective elements of the organization’s security posture or to become part of its security problems.**

### Hypervisor: **Software that manages the creation, use, and disposal of virtual machines. Type 1 hypervisors execute directly on the bare metal processor hardware; Type 2 hypervisors execute as special applications under the control of the host system’s operating system. Both types allow for the same computing hardware to run virtual machines that can provide users with almost any operating system and environment.**

# I

### Identity as a Service (IDaaS): **Cloud-based services for obtaining subscription-based identity management and access control capabilities.**

### Identity Management lifecycle: **Describes the series of steps in which a subject’s identity is initially created, initialized for use, modified as needs and circumstances change, and finally retired from authorized use in a particular information system. These steps are typically referred to as provisioning, review, and revocation of an identity.**

### Identity Plane: **Growing in popularity, this term, analogous to the data, control, or management plane view of networks, refers to how identity management and access control information are generated, routed, requested, used, and kept secure throughout an information system.**

### IEEE 802.1X: **A port-based standard for network access control protocols; it defines the the Extensible Authentication Protocol (EAPOL). Also known as “EAP over LAN,” it was initially created for use in Ethernet (wired) networks, but later extended and clarified to support wired and wireless device access control, as well as the Fiber Distributed Data Interface (ISO standard 9314-2). Further extensions provide for secure device identity and point-to-point encryption on local LAN segments.**

### Impact factor or Exposure factor: **The percentage of an asset’s or process’s value that is reduced by the impact of a risk event.**

### In-band: **Exchange of cryptographic keying material in the same communications channel that will be used for subsequent encrypted communication.**

### Incident of Intrest: **Identification and selection of an event that may be of significance in information security terms, either as a precursor or an indicator of a possible attack.**

### Incident Response Framework: **A formal plan or process for managing the organization’s response to a suspected information security incident. It consists of a series of steps that start with detection and run through response, mitigation, reporting, recovery, and remediation, ending with a “lessons learned” and onward preparation phase.**

### Indicator: **A sign, signal, or observable characteristic of the occurrence of an event that an information security incident may have occurred or may be occurring right now.**

### Indicator of Compromise: **An observable artifact that with high confidence signals that an information system has been compromised or is in the process of being compromised. Such artifacts might include recognizable malware signatures, attempts to access IP addresses  or URLs known or suspected to be of hostile or compromising intent, or domain names associated with known or suspected botnet control servers.**

### Infiltration: **The insertion of hostile code or data fragments into a target system; contrast with exfiltration, the unauthorized removal (typically by copying) of data from within an information system.**

### Information: **Created from data when we make conclusions or draw logical inferences about that data. We do this by combining it with the results of previously made decisions or with other data that we’ve collected.**

### Information Access Gates: **Datacenter access control systems, technologies, and strategies, typically using role-based access control.**

### Information Archtecture: **The information that people in an organization use and share as they work to accomplish the goals of the organization’s business logic.**

### Information Availability: **The condition that the information we require for a business process or decision is available for use, is complete, is correct, and in the required form or format, within the timeliness needs of that business process or decision. This includes retrieval, processing, transmission or movement, formatting, and presentation for use as necessary. Note that information that has been corrupted, is incomplete, or incorrect does not meet the availability requirement, even if it is delivered or presented on time.**

### Information Classification System: **Systematic approach to labeling categories or types of information based on the organization’s qualitative assessment of risks regarding that information.**

### Information Impact: **The degree to which an information security incident risks unauthorized disclosure, exfiltration, corruption, deletion, or other unauthorized changes to information assets, and the relative strategic, tactical, or operational value or sensitivity of that information asset to the organization.**

### Information Integrity: **Assures that the information is accurate, complete, and processed in accepted, understood, or authorized ways as required by the business logic that applies to it, and that no unauthorized or unknown processes have been allowed to tamper with the information or inject errors into it**

### Information Processing: **The first step in a series of actions where we apply business logic to the data to inform or enable the next step in a business process.**

### Information Quality: **(1) A systematic effort to ensure that all information used by an organization is (a) consistently meeting or exceeding all knowledge worker and end- customer expectations regarding that information, (b) so that knowledge workers can perform their work effectively and contribute to the enterprise mission, and (c) so that customers are successful in conducting business with you, and are delighted with the products, services, and communications (or information) they receive from you; or (2) a measure or assessment of how well a particular data set, database, or information asset meets criteria (a), (b), and (c) shown in the first definition.**

### Information Security Baseline: **Information that documents an organization’s information security risks, its chosen mitigation approaches, and its decisions about residual risk.**

### Infomation Security Incident Response Planning: **Planning to provide all personnel, systems, and assets necessary for promptly detecting IT and information systems events (or anomalies) that might be security incidents in the making; characterizing them; notifying appropriate organizational managers and leaders; and working through containment, eradication, and recovery tasks as we respond to such incidents.**

### Information Systems: **The collected sets of hardware, software, databases, and data sets; the communications, networking, and other technologies that connect all of those elements together into a cohesive, working whole; and the people who use them and depend on them to achieve their goals and objectives.**

### Information Systems Architecture: **The processes and procedures, and the information or data assets, that people in an organization use in systematic ways to achieve the goals of the organization’s business logic.**

### Information System Security: **Everything we need to do during design, implementation, operational use, and maintenance to keep all aspects of an information system protected against accidental or deliberate damage; it includes keeping its information free from unauthorized changes or viewing; and it keeps those systems up and running so that the information is there when people need it to get their jobs done.**

### Information Technology baseline: **An inventory or list of all IT hardware, software, connectivity, and data elements that make up an information system; usually detailed enough to show current versions or update levels on each device, system, or program.**

### Infrastructure as a Service (IaaS): **A cloud services model that provides CPU, storage, software-defined networking, and server capabilities on which users can host databases, compute-intensive applications, and other elements of their business logic. IaaS can be as simple as bare metal servers that require (and enable) the user to be in total control of defining, creating, dispatching, and using virtual machines, running on hypervisors selected by the user, or they can include a variety of system capabilities to make virtual machine creation, deployment, use, and retirement from use easier to manage.**

### Integrated Development Enviroment (IDE): **A set of software tools that can be used together to design, develop, test, integrate, and deploy software systems and applications.**

### Internet backbone: **A mesh of internetworking nodes and high-capacity, long-distance communications circuits that connect them to each other and to the many Internet service providers.**

### Internet of Things (IoT): **A general term for TCP/IP-capable devices that provide limited sets of functions; smart thermostats or smart home sensors and alarms, home entertainment systems elements, and devices for controlling or monitoring industrial, agricultural, or medical processes are just a part of the tasks we’re allocating to IoT devices. Many IoT devices do not have even the most rudimentary security precautions built into them or any means for users to update their onboard firmware or change control parameters (even usernames and passwords).**

### Internet Point of Presense: **A physical place at which a local Internet service provider (ISP) brings a physical connection from the Internet backbone to the user’s NIC. Contractually, the user owns and is responsible for maintaining their own equipment and connections to the point of presence, and the ISP owns and maintains from there to the Internet backbone.**

### Internet Segment: **Sometimes called “an internet” (lowercase), a network of devices that communicate using TCP/IP and thus support the OSI 7-layer reference model.**

### Intrusion Detection Systems (IDSs): **Systems that monitor attempts to access system resources to determine whether such attempts are legitimate or are potential hostile intrusions. May either be host-based or network-based.**

### Intrusion Prevention System (IPS): **A class of intrusion detection systems that can also be configured or programmed to shut down or block a suspect connection, route it instead to a quarantine area or honeypot, or take other actions to contain the impacts of the potential intrusion.**

### IPSec: **Internet Protocol Security for IPv4 providing an open and extensible architecture that consists of a number of protocols and features used to provide greater levels of message confidentiality, integrity, authentication, and nonrepudiation protection.**

# K

### Key Distribution: **The process of ensuring that authorized senders and recipients have appropriate copies of cryptographic keys to be used for their secure communications, along with any updates to the rules for their period of use and their safe disposal. Key distribution depends on all users being known to be trustworthy by the key originator and controller.**


### Key Encapsulation: **Wrapping an encryption key inside a data payload using some combination of symmetric and asymmetric encryption so as to provide for secure in-band key exchange; typically used to generate and exchange session keys.**

### Key Exchange: **Process and protocols by which two users generate and exchange session keys with each other. Key exchange systems start with the presumption that parties do not know each other and have no a priori reason to trust each other. They achieve this trust, and therefore can share in a secure, encrypted conversation, by generating their session key together and keeping that session key secret to themselves.**

### Key Generation: **The process of creating encryption keys.**

### Key Management: **Rules that govern time or usage constraints for cryptographic keys and keying materials, along with rules for disposing of expired keying materials and dealing with compromised keys.**

### Key Revocation: **The key management process of informing all users that a particular key is no longer valid and that it should not continue to be used.**

### Keying Material: **The physical media or electronic format of cryptographic keys and associated control parameters.**

### Kill Chain: **The sequence of steps, including alternate branches and sequels, that an attacker initiates and attempts to complete against a target. These steps broadly include reconnaissance, fingerprinting, entry, command and control, accomplishing their objective or intent, and exit.**

### Knowledge: **Created from data and information when broad general ideas (or hypotheses) are determined to be probably true and correct based on that data and information.**

### Knowledge Management: **The set of plans and processes to gather tacit and explicit knowledge in an organization, and organize and manage it to make it more immediately useful or exploitable by the organization and its people.**

# L

### Layers of Abstraction: **A design paradigm in information systems where complex systems are constructed with multiple layers of functions. Each layer depends on the capabilities of the layers beneath it while hiding the details of these lower layers from the higher layers.**

### Living Off the Land Attacks: **Malware-free attacks where the attacker leverages the built-in capabilities of a target system to achieve their objectives. Initial access is typically gained through social engineering or exploiting weak identity management and access control systems.**


# M

### Malware: **Software that is malicious in intent and effect. It is the general term for any type of software that enters your system without your full knowledge and consent, performs unauthorized functions, and diverts compute resources from your organization.**

### Management Plane: **Contains all of the processes, functions, and protocols that administrators use to manage, configure, and control the network. This concept is both a design abstraction and a physical implementation at the circuit level in network and communications hardware and software.**

### Mandatory Access Control: **Also known as nondiscretionary access control; it uniformly enforces policies that prohibit any subjects from attempting to change, circumvent, or bypass the constraints imposed by the access control system.**

### Maximum Allowable Outage (MAO): **The maximum time that a business process or task cannot be performed without causing intolerable disruption or damage to the business. Sometimes referred to as the Maximum Tolerable Outage (MTO) or the Maximum Tolerable Period of Disruption (MTPOD).**

### Mean Time to Repair or Restore (MTTR): **An estimate of the average time required to repair or replace a failed system, component, or process. MTTR includes the time needed to get suitable staff on-site, diagnose the failure, identify the correct repair or restoration needed, source parts or replacement components, effect repairs, and verify that the system works correctly post-repair.**

### Media Access Control (MAC) Address: **A unique number assigned to each network interface card or circuit, used in Layer 2 to provide unambiguous source and destination device addresses.**

### Mesh Topology: **A network design that provides multiple point-to-point connections between some or all of the nodes in the mesh. Mesh designs can be uniform (all nodes connected to all other nodes) or contain subsets of nodes with varying degrees of interconnection, supporting client-server, server-to-server, or peer-to-peer relationships.**

### Middleware: **Special-purpose software that bridges functional and interface gaps between different systems, applications, or platforms.**

### Mitigate (Fix, Remedy, Remediate) a Risk: **The process of making changes to systems, processes, or assets to reduce or eliminate vulnerabilities that could lead to impact and loss. This should not be confused with repairs and restoration required after a risk event has caused damage.**

### Mobile Device Management (MDM): **Application systems that provide device management, configuration control, security, and other services for organizations that utilize mobile endpoint devices of any kind.**

### Multicasting: **The process of sending a message to multiple devices both within a router domain and beyond it.**

### Multifactor Authentication: **An access control approach requiring that subjects prove their identity with more than one kind of information or factor. These factors are typically categorized as something the user has (e.g., smartcards, token fobs, smartphones), something the user knows (e.g., passwords, PINs, passphrases), and something the user is (e.g., biometric data).**

# N

### Narrowcasting: **The process of selectively generating and sending content to a subset of a larger audience, such that each subset may receive significantly different content.**

### Near-Field Communication (NFC): **A secure radio-frequency communications channel that works for devices within about 4 cm (1.6 inches) of each other. Designed for contactless, cardless payment and debit authorizations, NFC uses secure on-device data storage and existing radio frequency identification (RFID) standards to carry out data transfers, such as phone-to-phone file sharing or payment processing transactions.**

### Negative Security Control: **A means of providing security by explicitly identifying untrustworthy subjects, objects, software elements, or hardware elements; any attempts by these explicitly named subjects to connect to the system are denied. Also called blacklisting, it is often seen in the signature analysis techniques used by antimalware systems.**

### Network Access Control (NAC): **The set of services that give network administrators the ability to define and control what devices, processes, and persons can connect to the network or to individual subnetworks or segments of that network. It is usually a distributed function involving multiple servers within a network. NAC protocols define how network administrators translate business information security needs and policies into compliance filters and settings.**

### Network Address Translation (NAT): **Also known as Port Address Translation (PAT), IP masquerading, NAT overload, and many-to-one NAT; all provide methods for a routing function to edit a packet to change (translate) one set of IP addresses for another.**

### Network-Based Intrusion Detection Systems (NIDS): **Separate hardware and software platforms that sit between the protected, managed portions of your network and less secure zones, such as the Internet. Unlike Host-Based Intrusion Detection Systems (HIDS), NIDS monitor network traffic and alert when packets attempt to access ports, services, or addresses, or perform other actions that the NIDS is configured to detect.**

### Network Management Functions: **Services that allow user programs like ipconfig to instantiate, initiate, terminate, or monitor communications devices and activities. Simple Network Management Protocol (SNMP) is widely used in the TCP/IP community, while Common Management Information Protocol (CMIP) and its associated Common Management Information Service (CMIS) are more recognized in OSI communities.**

### Network Operating System: **The collection of software, firmware, parameters, control settings, and device-level operating systems that together form the network portion of an IT infrastructure.**

### Network Operations Center (NOC): **A physically or logically distinct set of resources, people, and tools that an organization uses to manage, monitor, maintain, and support its computer and communications network systems, infrastructures, and assets. Typically, the NOC focuses on ensuring the network works, keeping it operational, and modifying and maintaining it to meet changing organizational needs.**

### Nondiscretionary Access Control: **An access control method that allows the organization to determine when and how to make access control decisions based on a wide range of specific needs.**

### Nonfunctional Requirements: **A software engineering term referring to a general attribute of a system rather than a specific action it must perform. Traditionally, security requirements were viewed as nonfunctional, based on the belief that qualified programmers would naturally include features such as input data validation and user/subject authentication and authorization. Although this assumption has proven false in practice, the software industry still often considers security needs as largely nonfunctional.**

### Nonrepudiation: **A characteristic of a communications system that prevents a user from claiming they never sent or received a particular message. This feature sets limits on what senders or receivers can do by restricting or preventing any attempt to deny or repudiate a message, its content, or its meaning.**


# O

### Object-Based Access Control: **An access control method that uses the characteristics of each object or class of objects to determine what types of access requests will be granted.**

### Objects: **In access control terms, objects are the people, information assets, software processes, or hardware resources that subjects attempt to access. Objects can be collections of information or the processes, devices, or people that hold that information and act as gatekeepers to it.**

### One-Time Pads: **An encryption scheme where the key generator produces a sequence of key values, and this sequence is provided to both the sender and recipient. The first key in the sequence is used to encrypt and decrypt the first message, the second key for the second message, and so on.**

### One-Way Trust Relationship: **In communication systems, this refers to one node determining that it can trust another node, such as a certificate authority, as the verifiable source of authentic information, such as a certificate.**

### Operational Intelligence (OPINT): **The gathering of information and insights by observing how an organization operates at the fine-grained, step-by-step process or task level, and looking for patterns.**

### Operationalize: **The process of deconstructing a definition, concept, or idea into its components to apply that concept through a sequence of tasks.**

### Operational Testing and Evaluation (OT&E): **Formal systems testing to verify that a given system and the processes driven by people implementing the overall business logic and purpose function correctly and completely from the end users' or operators' perspective.**

### Organizational Culture: **The sum of all the ways, both written and unwritten, in which an organization makes decisions and carries them out. Organizational culture often reflects the personalities and preferences of its founders, stakeholders, leaders, or key investors.**

### Orphan: **A hardware device, application program, or other systems element for which the original vendor or manufacturer no longer provides updates, security patches, or migrations to new versions of operating systems.**

### OSI 7-Layer Reference Model: **The Open Systems Interconnection reference model, published by the International Organization for Standardization (ISO), provides a seven-layer protocol stack that adds session management, presentation services, and application interface functions to the four layers of the TCP/IP model and protocol stack.**

### Outcomes-Based Risk Assessment: **A risk assessment approach that uses a prioritized set of organizational or business outcomes, goals, or objectives as the focus for impact analysis, vulnerability assessment, and then risk mitigation and control decisions.**

### Out-of-Band: **The exchange of cryptographic keying material using a physically and logically separate communications channel from the one that will be used for subsequent encrypted communication.**

### Out-of-Band vs. Inline: **Refers to where Network Access Control (NAC) functions perform their monitoring and control tasks. Inline solutions position the NAC as a single (inline) point of connection and control between the protected side of the network and the unprotected side. Out-of-band solutions deploy NAC system elements, typically as agents, in many places within the network; these agents report to a central control system and monitoring console, which can then control access.**


# P

### Peer-to-Peer: **A logical connection between two nodes such that neither node has effective command or control over the other.**

### Penetration Testing: **Security testing focused on actively finding and exploiting vulnerabilities in an organization’s information security posture, processes, procedures, and systems. Often conducted by ethical hackers, penetration testing, or "pen-testing," aims to gain unauthorized access to protected and secure system elements.**

### Personally Identifying Information (PII): **Information about a specific individual that can be used in identity proofing or authentication processes.**

### Pervasive Encryption: **A concept developed by IBM and other companies to keep data fully encrypted throughout its lifecycle, including creation, quality control, transport, storage, retrieval, use, display, and disposal, while protecting against threats like covert paths or data aggregation.**

### Phishing: **Broadcast or shotgun-style attacks typically using email spam to lure recipients into exposing their systems to malware, hostile reconnaissance, or other threats. Often used for identity theft, phishing attacks entice targets to reveal personally identifying information (PII) for fraudulent purposes.**

### Physical Security and Safety Planning: **Planning that focuses on preventing unauthorized physical access to an organization’s premises, property, systems, and people, while also addressing hazards like fire or environmental risks that could cause injury, death, or property damage.**

### Plaintext: **Text, data, message, or file content that is in its original, unencrypted form, and is the input to an encryption process. Plaintext is readily understandable, whether it consists of human-readable characters or binary object code.**

### Platform as a Service (PaaS): **A large-scale, feature-rich applications platform provided on top of an Infrastructure as a Service (IaaS) foundation, typically integrating data modeling, management, backup, restore, and failover capabilities focused on application services delivered to users.**

### Point-to-Point Topology: **The simplest network topology, consisting of two nodes connected by a single link.**

### Policies (Administrative): **Administrative documents or statements that provide broad direction and intention, guiding what should be done, compliance standards, responsibilities, and rationales. Typically approved by senior leadership, administrative policies shape, direct, and evaluate the performance of the workforce.**

### Policies (Technical): **Software and data-driven tools that implement aspects of administrative policies by configuring access control, identity management, and resource management within an information system.**

### Positive Security Model: **A security approach that explicitly identifies trusted subjects, objects, software elements, or hardware elements, denying attempts by any not explicitly named. Also known as whitelisting, it can be applied to applications, MAC and IP addresses, email forms, and data files.**

### Preadmission vs. Postadmission: **An access control technique that determines whether authentication of an endpoint or user occurs before network access is granted (preadmission) or whether access is denied based on postconnection behavior (postadmission).**

### Precursor: **A sign, signal, or observable characteristic of an event that, while not an attack itself, could indicate a potential future attack.**

### Prevent: **In risk management, the act of stopping an attack or incident from occurring or halting it mid-progress to limit damage.**

### Privacy, Reasonable Expectation of: **The belief or legal authority to control who can enter or share a private space, assuming responsibility for what occurs within that space.**

### Private Browsing: **Using a web browser in a mode that keeps the user’s identity, browsing history, and entered data confidential.**

### Private Cloud: **Cloud systems that are dedicated solely to one organization, ensuring exclusive use and control.**

### Private Key: **One of two keys generated for asymmetric encryption, where the public key is freely available, and the private key is kept secret by the user it is issued to. Public key exchange protocols allow for establishing session keys and validating digital signatures.**

### Private Places: **Areas or spaces where the owner or responsible person has control over who can enter, observe, or participate in activities within that space.**

### Privilege Creep: **The accumulation and retention of access control privileges beyond what is necessary for a subject’s approved duties, increasing the risk of abuse.**

### Privilege Review: **The ongoing process in identity management that checks whether access privileges granted to a subject are still necessary or if they should be modified or removed.**

### Privileged Communication: **The passing of information between parties with the agreement that the contents will not be disclosed to others.**

### Privileged Information: **Information shared with another party under the agreement that it will not be disclosed without consent or legal process.**

### Procedures (Administrative): **Detailed step-by-step instructions derived from broad policy statements, directing individuals assigned to perform specific tasks.**

### Process-Based Risk Assessment: **Using critical business processes as the focus for impact analysis, vulnerability assessment, and risk mitigation decisions.**

### Processed Data: **Raw data that has been adjusted to remove biases or errors from the original measurement process.**

### Provisioning (Identity Management): **The process of creating, approving, and deploying identities in an organization, including validating identity claims, issuing credentials, and managing access to system objects.**

### Proximate Cause Analysis: **Efforts to identify the last action taken that directly led to an incident.**

### Pseudorandom Number: **A number generated by an algorithm that produces a set of outputs distributed across a coordinate space without easy-to-spot patterns, though it is not truly random.**

### Public Cloud: **Cloud systems where multiple, unrelated customers share hardware, systems, and software resources managed by the cloud services provider.**

### Public Key: **One of two keys generated for asymmetric encryption, where the public key is freely available, and the private key is kept secret. Public key exchange protocols enable trusted communication and digital signature validation.**

### Public Places: **Areas where anyone can observe the presence and activities of others with little to no control over who is in that space.**

# Q

### Qualitative Risk Assessment: **Risk assessment that focuses on the inherent qualities, aspects, or characteristics of a risk as it relates to the outcome(s) of a risk occurrence. It is used when there is no firm basis for quantitative risk assessment or in conjunction with it, often reflecting risk tolerance or intangible assessments of importance.**

### Quantitative Risk Assessment: **A set of techniques that estimates the frequencies and probabilities of risk occurrence, as well as the potential loss or impact, to determine an expected cost or impact of that risk.**

### Quantum Cryptography: **Cryptographic processes that use quantum computing techniques. Still in the basic research phase, quantum cryptography could provide advantages in encryption systems, key distribution, message integrity, cryptanalysis, and attack prevention.**

### Quantum Key Distribution: **A technique that uses the measurement effect to alert users if a third party attempts to observe a key. This method is ideal for one-time pad encryption systems and works well with AES and other symmetric encryption systems.**

### Quarantine (Malware Protection): **An antimalware approach that moves a file suspected of being infected into a secured area in file storage. Only trusted processes and users can then read, examine, or execute those files to determine if they are malware.**

### Quarantine Networks: **An access control remediation approach that provides a restricted IP subnetwork, allowing the endpoint in question to access only a select set of hosts, applications, and other information resources. For example, it might restrict the endpoint to a software patch and update management server; once the update is successfully installed and verified, the access attempt can be reprocessed.**


# R

### RADIUS (Remote Authentication Dial-In User Service): **Provides a central repository of access control information and protocols by which access control and management systems can authenticate, authorize, and account for access requests. RADIUS is widely supported and integrated into many network systems, providing roaming support for mobile users.**

### Raw Data: **Observations or measurements that come directly from a sensor, recorder, or measuring device, without any processing or analysis.**

### Recoverability: **An estimate of whether the impact of an information security incident can be eliminated or significantly reduced if the incident is promptly and thoroughly contained. For example, data that has been exfiltrated is generally considered a nonrecoverable impact.**

### Recovery Point Objective (RPO): **Estimates the amount of data loss that is tolerable to an organization, typically expressed in terms of how much data must be restored from backup to bring a system back to its required state.**

### Recovery Time Objective (RTO): **The amount of time within which system functionality or business processes must be restored after a disruption. The RTO should be less than or equal to the Maximum Allowable Outage (MAO).**

### Remediation (Access Control): **Measures taken to assist legitimate users who fail an access control attempt, helping them to correct the failure and gain authorization.**

### Residual Risk: **The level of risk that remains after risk controls have been implemented.**

### Resiliency: **A characteristic of a system’s design that reflects its ability to continue operating correctly under unanticipated errors or conditions, without crashing or causing unacceptable data loss or business process interruptions.**

### Responder’s Workbench: **A set of prepositioned software, hardware tools, and support data used by incident response team members. It can include data capture and analysis tools, logging functions, and tools to facilitate system, application, or data restoration efforts.**

### Revocation: **The formal process of terminating access privileges for a specific identity within a system.**

### Ring Topology: **A network topology in which each node is connected to two other nodes, forming a ring. Each node must function properly to pass data along to the next node. Ring topologies can provide either unidirectional or bidirectional data flow and can use signal conditioning to extend the total length of the network.**

### Risk: **The possibility that an event could disrupt or damage the organization’s activities, assets, or processes, potentially affecting its ability to achieve its goals and objectives. Risk involves a threat acting upon an asset's vulnerabilities to cause undesired results.**

### Risk Appetite: **Also known as risk tolerance, this is a subjective measure of how willing an organization’s senior leaders and managers are to accept certain risks.**

### Risk Controls (Countermeasures): **The actions taken to implement technologies, features, and procedures to prevent vulnerabilities from being exploited and causing harmful impacts.**

### Risk Management: **The organized process of identifying and assessing risks based on their potential impacts to the organization, making decisions on how to address these risks, and developing and implementing plans to control, mitigate, respond to, and recover from risk events.**

### Risk Management Framework: **A formalized set of management tools, procedures, standards, or techniques that guide organizations in making decisions about which risks are urgent and important, and how to address them.**

### Risk Mitigation: **The process of implementing decisions to contain, transfer, reduce, or eliminate risk to acceptable levels. This may include accepting a risk when no other practical options are available.**

### Risk Register: **A central repository or knowledge bank of the risks identified in a business and its processes.**

### Risk Treatment: **The application of methods to eliminate or reduce the likelihood and impact of a risk.**

### Risk Treatment Strategies: **Broad approaches to managing risk, including accepting, transferring, avoiding, or remediating (mitigating) the risk.**

### Role-Based Access Control (RBAC): **A method of granting access privileges to subjects based on their roles within an organization. Factors influencing role-based privileges include separation of duties, need to know, and the duration and scope of the role.**

### Root Cause Analysis: **Efforts to identify the underlying vulnerability or failure mechanism that led to an incident.**

### Rootkits: **A class of malware that uses privilege elevation techniques to insert itself into the lowest-level functions of the operating system. Rootkits load during bootup, often before most security systems, and can give attackers undetectable control over a system, making them a favorite tool in advanced persistent threats.**

### Rounds, Number of (Cryptographic Algorithms): **The stages of operations applied iteratively to input plaintext or blocks of it during the encryption process.**

### Routing: **The process of determining the path or set of paths to send data from one endpoint device through the network to another.**


# S

### Safeguard Value: **The estimated cost to implement and operate a chosen risk mitigation control.**

### Safety: **A characteristic of an information system that reflects whether its failure modes can cause harm, including injury or loss of life, to its users, other systems, or innocent bystanders. Safety is separate from security or privacy.**

### Sandbox: **An isolated, highly controlled software and hardware environment where software and data can be tested, inspected, and evaluated. Sandboxes are often used in software development and testing to evaluate new versions of software without affecting production data or environments. They are also used as quarantine areas to safely examine potentially malicious software or data.**

### Secure Browsing: **Using a web browser in a manner that actively helps keep the user’s system secure while assertively protecting the user's privacy, system data, and browsing history.**

### Security: **The set of plans, procedures, and actions that keep something safe from harm, damage, or loss, whether through accidents, acts of nature, or deliberate actions by people.**

### Security Evangelist: **A person who promotes better information security hygiene across an organization, encouraging a culture of security awareness. They also work externally with customers, partners, and stakeholders to communicate the importance of keeping the community safe and secure.**

### Security Information and Event Management (SIEM) System: **An application system that provides a centralized capability to collect, assess, monitor, and analyze information related to precursors, indicators, and information security events.**

### Security Operations Center (SOC): **A dedicated team and set of tools focused on deterring, preventing, detecting, and responding to network security events. The SOC integrates all network-security activities to make informed, timely, and effective decisions, ensuring ongoing system reliability, availability, and security.**

### Segmentation: **In networking, the process of dividing a large network into smaller, more manageable subnetworks.**

### Semantics: **The rules that define how ideas and meanings are represented in language through words, sentences, and expressions, and how these are interpreted. This applies to both natural (human) languages and artificial languages used in computer programming.**

### Service Fabric: **The set of processors, storage assets, communications, and network connections, along with the management functions that control synchronization, load leveling, and task management, all managed as a resource pool by a service fabric manager.**

### Service Level Agreement (SLA): **A contractual agreement between a service provider and consumer that specifies service quality, quantities, timeliness, responsiveness, and other performance and security standards.**

### Shadow IT Systems or Elements: **Systems and applications created by users outside the control of the IT department, often using tools like spreadsheets or database systems available in office productivity suites. These are often developed without the IT department’s knowledge or oversight.**

### Signature Recognition: **Antimalware and intrusion detection techniques that identify suspect malware or intrusion attempts by matching predetermined bit patterns or file characteristics.**

### Simple Integrity Property: **In the Biba model, this property requires that a subject cannot read from an object at a lower security sensitivity level (no “read-down”).**

### Simple Security Property: **In the Bell-LaPadula model, this property requires that a subject may not read information at a higher sensitivity level (no “read-up”).**

### Single Loss Expectancy (SLE): **The total monetary loss expected from a single occurrence of a risk, including immediate, delayed, direct, indirect, and lost opportunity costs.**

### Single Sign-On (SSO): **An access control approach that authenticates a subject upon initial access and then packages the credentials for use with other systems or applications in the environment.**

### Social Engineering: **Efforts to exploit weaknesses in people within an organization by learning about them and using that information to gain unauthorized access or information. This is also referred to as HUMINT (human intelligence) in espionage and national security contexts.**

### Sockets: **Software interfaces to services provided by a protocol stack, offering application developers well-defined ways to access each service. The term reflects early telephone systems where calls were connected by plugging cables into sockets.**

### Software as a Service (SaaS): **A layer of application software provided on top of an Infrastructure as a Service (IaaS) foundation, typically offered on a subscription basis. Examples include cloud-hosted productivity suites and software development tools.**

### Software Development Lifecycle (SDLC): **The sequence of steps necessary to understand the needs for a software-based system, design it, build it, test it, and deliver it to end users for business use. Various SDLC models exist, often tailored to the needs of specific development teams.**

### Software Quality Assurance: **An end-to-end process that ensures software meets all required functions as documented in the system functional requirements and that it does not perform any unintended actions.**

### Software-Defined Network (SDN): **A network management approach that uses virtualization tools to define the network entirely in software.**

### Spaghetti Code: **Poorly designed software that lacks proper separation of functions, making it difficult for maintenance programmers to understand or modify.**

### Spear Phishing: **Targeted phishing attacks focused on specific individuals or groups, often using social engineering techniques to suggest a pre-existing relationship in order to lower the target’s defenses.**

### Standalone Systems: **IT systems that are physically and logically disconnected from other systems or elements of the organization’s IT architecture.**

### Star Topology: **A network topology with one central node connected to multiple other nodes via point-to-point connections. The central node typically acts as a server, while the other nodes function as clients.**

### Stateful Communications Process: **A process in which the sender and receiver keep track of the sequence of steps in communication, requiring identification, error detection, and retransmission protocols.**

### Stateless Communication Process: **A process that does not require the sender and receiver to track the sequence of communication steps. It typically does not require a connection, retransmission, or validation of the recipients.**

### Static IP Address: **An IP address assigned to a device that remains unchanged, offering faster and more reliable connections due to persistent ARP and DNS caches.**

### Stream Ciphers: **Symmetric encryption processes that work on a single byte or bit of plaintext at a time, using a pseudorandom keystream to encrypt the data. Stream ciphers are fast and can handle any length of input plaintext.**

### Subject-Based Access Control: **An access control method that considers characteristics of the subject that are unlikely to change over time when establishing privileges.**

### Subjects (Access Control): **Entities (people, software processes, or hardware functions) that attempt to perform actions on objects, such as reading, changing, or executing them.**

### Subnetting: **An IPv4 network addressing method that allows for the logical and physical segmentation of a network by subdividing the host portion of an IP address. IPv6 supports subnetting more simply but with its larger address space, subnetting is often unnecessary.**

### Supervisory Control and Data Acquisition (SCADA): **A specialized class of network and systems devices used for data sharing, command, and control protocols in industrial process control, such as in electric power generation and transmission.**

### Switching: **The process of receiving data on one input port of a network device and selecting an output port to send the data to.**

### Symmetric Encryption: **A cryptographic process where the same key is used to both encrypt and decrypt a plaintext message. The decryption algorithm is the inverse of the encryption algorithm.**

### Syntax: **The rules that define the structure and grammar of words, sentences, and phrases in language. This applies to both natural (human) languages and artificial languages used in computer programming.**

### System: **A collection of interconnected and interacting elements that work together to fulfill or achieve a larger purpose or objective.**

# T

### TACACS: **Terminal Access Controller Access Control System; variations include TACACS+, and Extended TACACS (XTACACS). All versions provide authentication, authorization, and accounting functions for access control, with differing sets of capabilities.**

### Tacit Knowledge: **Knowledge that is not written down or recorded in any tangible form, existing solely within human memory.**

### TCP/IP: **Transmission Control Protocol over Internet Protocol; at Layer 4 of the Internet protocol stack, TCP provides a connection-oriented service and operates over the Layer 3 Internetworking (or Internet) protocol.**

### Telemetry: **Data generated by a system or subsystem that is used to monitor its performance or state of health.**

### Terms of Reference (TOR): **See service level agreement (SLA).**

### Terms of Service (TOS): **See service level agreement (SLA).**

### Threat Modeling: **The process of modeling an information system in terms of the physical, logical, and administrative threat surfaces or boundaries it presents to the outside world. This focuses security assessments on how each boundary can be crossed.**

### Threat Surface: **A boundary that encapsulates objects requiring protection to meet their information security needs.**

### Threat-Based Risk Assessment: **A risk assessment approach that identifies and prioritizes threats, using them as the focus for impact analysis, vulnerability assessment, and risk mitigation and control decisions. Also known as vulnerability-based risk assessment.**

### Timeline Analysis: **The process of reconstructing a sequence of events to focus analysis, raise questions, generate insights, and organize information discovered during incident response. It is a powerful tool for determining both proximate and root causes.**

### TLS Cipher Suite: **The set of cryptographic algorithms used within Transport Layer Security (TLS) across its four major operational phases: key exchange and agreement, authentication, block and stream encryption, and message authentication. The suite is updated as older algorithms become vulnerable and new ones are adopted by the Internet Engineering Task Force (IETF) and the Web community.**

### Topology: **In network design, the basic logical geometry by which different elements of a network connect together. Topologies consist of nodes and the links that connect them.**

### Trade Secrets: **Aspects of a company’s business logic believed to be unique, not widely known or understood in the marketplace, and not easily deduced or inferred from the products themselves.**

### Traffic Analysis (TA): **A cryptanalysis attack that attempts to deduce the meaning of encrypted communications by analyzing patterns in sender and recipient addresses, protocols or packet types, volumes, timing, and coincidences.**

### Transfer (a Risk): **Dealing with a risk by having another party be responsible for restoring business functions, making repairs, or covering other aspects of loss if the risk occurs, usually done through insurance contracts.**

### Transitive Trust Relationship: **Exists when one node (Node A) trusts another node (Node B), which in turn trusts a third node (Node C). As a result, Node A trusts Node C, making Node C the trust anchor of this three-node chain of trust.**

### Transport Layer Security (TLS): **A cross-layer protocol within both TCP/IP and OSI 7-layer reference model protocol stacks that provides secure connections. TLS has largely replaced Secure Socket Layer (SSL) due to SSL’s encryption vulnerabilities.**

### Trust Relationship: **In communications systems, this refers to one node trusting another for the purposes of protecting privileged information or as the authoritative source of information, such as a certificate. Trust relationships can be one-way, two-way (the aggregate of two one-way relationships), or transitive, and can be used to establish webs of trust or hierarchies of trust.**

### Trusted Platform Module (TPM): **Specialized hardware devices incorporated into the motherboard of a computer, phone, or tablet that provide enhanced cryptographic-based device and process security services. A TPM is sealed in a tamper-resistant hardware package and is embedded into the computer’s motherboard to be nonremovable, working with device drivers and other software to achieve greater security.**

### Trusted Supply Chain: **The set of suppliers, manufacturers, vendors, and maintainers that provide elements of an organization’s IT infrastructure, whose business processes and security postures can be trusted to prevent malware from being inserted or embedded during manufacture, testing, storage, shipment, and installation.**


# U

### Unicasting: **Sending a message to a specific IP address that does not end in .255; the message is directed only to that particular address.**

### Uniform Resource Locator (URL): **An address string that identifies a resource such as a file, webpage, or server. It consists of a protocol, a fully qualified domain name, and suffix fields that provide additional parameters to the server receiving and processing the URL.**

### Uniqueness:

1. **In access control and identity management, the property of an identifier such that it is linked to one and only one subject or object unambiguously. Typically, these identifiers are generated using cryptographic hash operations.**
2. **More generally, the property of a system of identities and their corresponding names (or identifiers) such that there is a one-to-one mapping between them.**

### User Behavioral Analytics: **Application of business intelligence (BI) and predictive intelligence (PI) methods to measurements, indicators, and patterns of user behaviors to potentially identify when a user's behavior is suspicious and warrants closer scrutiny.**

### Utility: **Making large sets of data more useful or applicable for other purposes through data compression, smoothing, reduction, or other statistical or mathematical means.**


# V

### Web of Trust: **Collections of trust relationships (chains of trust) where no single node acts as a designated or recognized authority, resulting in no central trust anchor for all chains in the web. Managing and scaling such a web can be challenging, particularly when a node becomes untrustworthy, as there is no clear-cut revocation process.**

### Whaling: **Attacks directed at specific, high-profile individuals within an organization, often using what appears to be a legitimate business transaction to request the immediate release or transfer of funds to a third party.**

### Wisdom: **Knowledge that enables drawing broad, insightful conclusions about future courses of action.**

# Z

### Zero-Day Exploit: **An attack that exploits a newly discovered vulnerability before it is known or reported to the developers, vendors, or users of the affected system. The term implies that defenders have no time to prepare for the attack since the vulnerability is unknown.**

### Zeroization: **Also known as randomization or clobbering, this is the process of clearing cryptologic systems of all keying materials, plaintext, ciphertext, control parameters, and sometimes even software and firmware. It restores the device to a clean initial state and removes any information that could potentially be used to compromise the encryption scheme.**

### Zero Trust Architectures: **Network design and access control approaches that focus on security within the organization’s information infrastructure rather than solely on perimeter defenses. Zero trust architectures emphasize micro-segmentation of the network and attribute-based access control to contain threats and limit potential damage or loss.**