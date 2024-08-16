## Which wireless security protocols should no longer be used?

* Wired Equivalency Protocol (WEP), Wi-Fi Protected Access (WPA)

## What is * (star) integrity?

* Biba model, which prohibits “write up” from a lower to a higher security level

## Can streaming video or audio introduce malware to your system?

* Using an add-on player from a trusted provider in your browser should protect you; however, there’s a high risk that hidden buttons on the server page could initiate other actions that bring malware to your system.

## How do digital signatures work?

* The sender (or author) hashes the message or file to produce a message digest and applies the chosen decryption algorithm and their private key to that hash. This is the signature. The recipient uses the sender’s public key and applies the corresponding encryption algorithm to the signature, which will produce a matching message digest (hash) only if the message or file is authentically from the sender.

## What is subnetting in IPv4 and IPv6?

* Subnetting provides the network designer a way to logically group hosts on a network segment by treating the host address field as two sets of bits: one for subnetwork number, the other for host number. Both IPv4 and IPv6 provide for subnetting, but the much larger IPv6 address field makes this a lot simpler to design and manage.

## What is centralized access control?

* All identity management and access control decisions for an organization are handled by one server system.

## What kind of subjects should be authenticated before being granted access?

* All types—devices, people, software processes

## Your email address can be hijacked; what about your public key?

* No, because you need to use your private key when you generate digital signatures when producing files or messages to send to others. As long as you never disclose your private key, it cannot be compromised by known attack methods. Just don’t put it on a yellow stickie under your keyboard!

## What is mandatory access control (MAC) address whitelisting?

* Access control restricted to devices with matching MAC addresses; typically done by routers or firewalls

## How would you use CVE data?

* Common Vulnerabilities and Exploitation (CVE) data is the information security communities’ best, most current knowledge of vulnerabilities in commercial software, firmware and hardware systems, and about known exploits. Use this as part of your own systems vulnerability assessment and to guide hardening efforts.

## What does nonrepudiation use cryptography to do?

* Validate that the certificate, public key, or both associated with the sender or author match what is associated with the file or message

## What are the Open Systems Interconnection (OSI) layers, bottom to top?

* Physical, Data Link, Network, Transport, Session, Presentation, and Application

## What is SLE?

* Single loss expectancy, the damages or loss anticipated by a single occurrence of a risk event; (asset value) × exposure factor

## What is an orphan?

* A device or software program no longer supported by its vendor or manufacturer; no more upgrades, updates, or support to migrate to a new operating system is available.

## What are hierarchies of trust?

* Collections of trust relationship in which one trust anchor provides the central authority for all chains of trust in the collection via transitive trust relationships with other nodes. Provides for clear ways to revoke trustworthiness of lower-level nodes.

## What is IPv4?

* Internet Protocol version 4

## Describe the difference between confidentiality and privacy.

* Confidentiality is about keeping information secret so that we retain advantage or do not come to harm; privacy is about choosing who can enter into one’s life or property.

## What are BLOBs?

* Binary large objects; a way of defining and allocating data storage that is independent of the actual storage technology used

## What is a Type 2 access control error?

* False negative, prohibiting an authorized user from gaining access

## Why use a honeypot?

* To allow an attacker a limited, controlled access to the organization’s systems so that more can be learned about systems vulnerabilities by watching the attacker attempt to exploit vulnerabilities in those systems

## What is transitive trust?

* If node A trusts Node B, and node B trusts node C, then node A trusts node C. This is how chains of trust form (in this case, node C is the anchor).

## What is Institute of Electrical and Electronics Engineers (IEEE) 802.1X?

Access control standard that defines the Extensible Authentication Protocol

## What is eradication?

* Finding and eliminating all copies of causal agents such as malware files or unauthorized user/subject IDs

## What does “garbage in, garbage out” mean?

* Most information processes involve a set of related data items that represent or model a real person, activity, or part of the world. When that set of data is mutually inconsistent, or inconsistent with other data on hand about that real entity, each field may be within range but the overall meaning of the data set is corrupt. This “garbage,” when processed (as input) by apps, produces equally meaningless but valid-looking outputs.

## What are the steps in identity management?

* Provisioning, review, revocation, deletion

## What is a zero day exploit?

* Exploitation of an unreported vulnerability in commercial or widely available software or firmware

## What is cache poisoning?

* Almost every device on a network, from a smartphone or laptop on up, has an address and Domain Name System (DNS) cache on it; these can be poisoned in a variety of ways, exposing the user and the network to various attacks.

## What are the encryption benefits across time?

* Encrypting a file for storage ensures that it cannot be read or tampered with by unauthorized users or processes (ones who do not have the key); later, authorized users with the key can read the file.

## Fill in the blank: What you have, what you know, and

* What you are: a physical characteristic of you as a user, subject to biometric confirmation

## What are the phases of incident response?

* Detection, characterization, containment, eradication, restoration, after-action reporting/debriefing to produce lessons learned. Preparation, of course, precedes first detection.

## Email typically uses which ports and protocols?

* Simple Mail Transfer Protocol (SMTP), transmission control protocol (TCP) 25; post office protocol 3 (POP3, via TCP 110.

## What is due care?

* Taking steps to ensure that all of your responsibilities can be accomplished satisfactorily

## What is symmetric encryption?

* Fast! It uses the same key for encryption and decryption, which requires some kind of key distribution or public key exchange process to protect keys from compromise

## What are controlled paths?

* Deliberately designed and created ways for subjects on one side of the threat surface to cross over and access objects inside it

## What are HTTP and HTTPS, and what ports do they typically use?

* HyperText Transfer Protocol (HTTP) uses Transmission Control Protocol (TCP) port 80. Secure HTTP (HTTPS) uses TCP port 443.

## What is ARP, what layer does it run at, and what does it use for addressing?

* Address Resolution Protocol (ARP) provides a way to query other network devices so as to resolve a device’s media access control (MAC) address into its corresponding Internet Protocol (IP) address. It is a cross-layer protocol and can work across Layers 2, 3, and 4.

## What is forward secrecy?

* Session keys used to encrypt plaintext will not be compromised if the private key of the server is compromised. Requires use of asymmetric encryption, of course (“private key”).

## Describe the difference between Transmission Control Protocol (TCP) and User Datagram Protocol (UDP).

* TCP: reliable, connection-oriented, segment retransmission and sequencing; segments acknowledged. UDP: unreliable, connectionless, no windowing, retransmission, sequencing or acknowledgment.

## Which layer does IPSec operate at?

* Layer 3, the internetworking (or network) layer

## What is nonrepudiation?

* Prevents a sender of a message from later denying that they sent it

## What is clock synchronization?

* Makes analysis of system event logs much easier; can also keep system anomalies from occurring, as some protocols will not tolerate too large a clock difference between client and server.

## What are POP, SNMP, and IMAP, and what ports do they use?

* Different email protocols. Post Office Protocol (POP), version 3 (POP3,) uses TCP port 110, or via Secure Socket Layer (SSL) or Transport Layer Security (TLS) over port 995. Internet Mail Protocol (IMAP), version 4 (IMAP4) uses TCP port 143, via SSL or TLS using port 993. Simple Mail Transfer Protocol (SMTP) uses port 25, port 465 using SSL or TLS. TCP is Transmission Control Protocol. All email ports can be changed if both server and client agree.

## What is decentralized access control?

* An organization’s total access control needs (all subjects and objects, all locations) is partitioned, with each partition having its own access control servers

## Domain Name System (DNS) uses which port and protocol?

* UDP port 53 for name queries; TCP port 53 for zone transfers

## What is privilege creep?

* Continued accumulation of privileges by a subject or user, despite changes in job, role, functions, or conditions

## What is annualized rate of occurrence (ARO)?

* Number of times a risk event is anticipated to occur within a calendar year. ARO = 0.1 indicates a once-every-ten-year event.

## What are man-in-the-middle (MITM) attacks?

* MITM attacks can occur at any layer, and against connectionless or connection-oriented protocols

## Describe the difference between secure browsing and private browsing.

* Secure browsing attempts to restrict server (or other) access to private information identifying you, your system, or browsing history; private browsing merely attempts to protect your browsing history but offers little to protect your own identity.

## Can standard port numbers be changed?

* Yes, but doing so requires a cooperative effort on the part of all clients using the server that is making the change in port assignment. This happens quite frequently with Internet service provided (ISP)-hosted email systems.

## What is access control based on job functions or duties?

* Role-based access control

## What are host-based firewalls?

* Very similar to antimalware systems in that they scan files or packets coming into and out of the host system for possible malware

## What is the most common attack on business or private sector use of encryption?

* Social engineering

## What is * (star) security?

* Bell-LaPadula model, which prohibits writing down to a process at a lower security level

## What ways can you assess risk?

* Base it on the impacts or anticipated losses to organizational outcomes or goals, business processes, and key assets, or that can be caused by a particular class of threats or vulnerabilities.

## What is a separation of duties?

* Policies that allocate parts of sensitive or critical job functions to different people so that no one single person performs all tasks and can see or modify all data

## What is an attack surface?

* The set of applications, systems, hardware, features, or elements of your IT architecture, which can be the focus of an attacker’s attention

## What is MPLS, what layer does it run at, and what does it use for addressing?

* MultiProtocol Label Switching (MPLS) provides routing based on shortest paths within a network, and is often used in virtual private network (VPN) implementations. It uses Internet Protocol (IP) addresses, and thus runs at Layer 3

## What is the positive security model?

* Explicitly names those subjects that are allowed to have access; all others are therefore denied. Also known as whitelisting.

## Describe the difference between safety and reliability.

* Safety requires that when systems fail, they do no harm or injury to other systems, people, or property. Reliability requires them to produce accurate, on-time answers as and when required.

## What is confidentiality?

* Keeping sensitive, private, or proprietary data from being revealed to or accessed by an unauthorized subject

## How can you protect the integrity of a file, but have its contents remain as plaintext?

* a) digitally sign the file; or (b) use an encrypting hash to produce a message digest when creating the file, and again when reading it

## What is an acceptable use policy?

* Administrative statement of what company-provided IT systems can be used for, and what uses are prohibited

## What is existential risk?

*  risk of such impact that it can put the business out of business (cause it to cease to exist as a legal, functioning entity)

## What is the difference between decentralized and centralized access control?

* Centralized: harder to set up, easier to make global changes and updates. Decentralized: easier to set up, harder to maintain or make global changes.

## What are three uses of hashing?

* (1) creating pointers or indexes into data tables and databases; (2) producing secure message digests; (3) providing integrity checking for file or message content

## What kind of things might be an indicator of compromise?

* Recognizable malware signatures, attempts to access IP addresses or URLs known or suspected to be of hostile or compromising intent, or domain names associated with known or suspected botnet control servers

## What is IPSec, what layer does it run at, and what does it use for addressing?

* Internet Protocol Security (IPSec) is a set of security protocols added to Internet Protocol version 4, and built into the design of Internet Protocol version 6. It uses Internet Protocol (IP) addresses, and thus runs at Layer 3.

## What is data remanence?

* Data that remains in a system after power is removed; even failed disk or flash drives have data remaining in them, which can be extracted.

## What are subjects and objects?

* Subjects are people, processes, tasks, or devices that are trying to do things to objects, such as read, copy, modify, and run them (load and execute); objects can be people, devices, datasets or files, or processes.

## What are attacks against device-level firmware?

* (a) Remote or onsite device management (or mismanagement) attacks that allow a hacker to initiate a firmware update using a hacked firmware file; (b) phishing or misdirection attacks that fool operators or users into initiating an upload of a hacked firmware file

## Should security be a nonfunctional requirement?

* Yes; security needs tend to be broad sets of performance criteria.

## Why are hashes one-way?

* An effective hash algorithm has no mathematical inverse; you cannot take the resulting hash value and unencrypt it to reproduce the original plaintext.

## What is a salt, and why is it used?

* A pseudorandom value added to the plaintext during encryption, or during hashing. It effectively increases the key space by the number of bits to represent the salt, thus increasing security and reducing the chance of collision.

## What are phishing attacks most often used to do?

* Establish initial access to the target system

## What is a reference monitor?

* The functionality that checks every access attempt to see if it should be authorized or denied

## Security for collaboration environments most depends on what?

* Education and training of the users so that they know how, why, and when to protect what should not be shared

## Security for collaboration environments most depends on what?

* Education and training of the users so that they know how, why, and when to protect what should not be shared

## What is the best protection if a mobile endpoint device is lost or stolen?

* Mobile device management (MDM) systems can be used to configure and control the device and to lock or zeroize it if it is reported lost or stolen

## What are the Layer 2 protocols and addressing?

* Ethernet, 802.1X, Point-to-Point Protocol (PPP), Fibre Channel; mandatory access control (MAC) address

## What is a Type 1 access control error?

* False positive, allowing an unauthorized subject or user to gain access

## What is the difference between key exchange and key distribution?

* Key exchange involves using asymmetric encryption to generate and exchange session keys with someone you might not know. Key distribution is used to transmit symmetric encryption keys to authorized users.

## What is IPv6,?

* Internet Protocol version 6

## What is does a business continuity plan do?

* Provides strategic planning and direction to protect the business’s ability to function after a disruption

## Can antimalware systems provide network quarantine?

* No; malware quarantine is about isolating files suspected of being contaminated with malware, whereas network quarantine blocks access to the network by systems not meeting standards, such as having updated malware definition files.

## What are cryptographic primitives?

* Mathematical or logical elements, studied by researchers as part of basic research about cryptography

## What is Institute of Electrical and Electronics Engineers (IEEE) 802.1X?

* Public standard for access control systems; Terminal Access Controller Access-Control System Plus ( TACACS+ ), for example, complies with it.

## What is due diligence?

* Checking to make sure that all of your due care tasks are actually getting the job done correctly and completely

## What is PII?

* Personally identifiable information; information about a specific person which if disclosed to the wrong parties could allow for fraudulent misuse of the person’s identity

## Can Common Vulnerabilities and Exposures (CVE) data provide everything you need to secure your systems?

* No, because it will not contain information about customized software, processes, or procedures that you use

## How do you protect email from introducing malware into your system?

* Email scanning (message content and attachments), along with application whitelisting

## What is ICMP, what layer does it run at, and what does it use for addressing?

* Internet Control Message Protocol is used to communicate control information between network devices, and can perform some network and device management functions. It uses Internet Protocol (IP) addresses, and thus runs at Layer 3.

## What is identity proofing?

* Establishes the truthfulness of documents or other information that attest to a person’s claim to be that person, and is used during the identity provisioning process

## What are cryptographic protocols?

* (1) The use of cryptography itself in the operation of a cryptographic system, which typically can refer to key management and key distribution techniques; (2) the use of cryptographic systems and techniques to solve a particular problem

## Describe the difference between cleartext and plaintext.

* Cleartext is never meant to be encrypted. Plaintext is the original file, message content, or meaning that needs to be protected by means of encryption.

## Is IPv6 backward compatible with IPv4?

* No, because the differences in addressing, packet header structure, and other features would not allow an IPv4 packet to successfully travel on an IPv6 network

## How do you provide incident response support to forensics investigations? 

* Secure the scene, protect evidence, establish and maintain chain of custody of evidence

## What are SSL and TLS, and what layers to they run at??

* Secure Sockets Layer (SSL) and its replacement Transport Layer Security (TLS) provide the means to secure payload datagrams via encryption, and thus run at Layer 6 of the Open Systems Interconnection (OSI) model, and above the four-layer Transmission Control Protocol over Internet Protocol (TCP/IP) stack.

## What is ARP?

* Address Resolution Protocol, which discovers the corresponding IP address for a given mandatory access control (MAC) address by asking other devices for it. Failing to find it, it will seek it from a Dynamic Host Configuration Protocol (DHCP) server.

## What are covert paths? 

* Unintended and unauthorized channels, within a system, for the transfer of information in ways that violates security policies.

## What are HIDSs and HIPSs?

* Host-based intrusion detection or prevention systems

## What are TCP and UDP, what layer to they run at, and what do they use for addressing?

* Transmission Control Protocol (TCP) is a connection-oriented protocol that provides a degree of error correction, lost packet retransmission, and other quality services. It uses sender and recipient port numbers as addresses. User Datagram Protocol (UDP) is a connectionless protocol, and uses sender and recipient port numbers as addresses. These both run at Layer 4.

## What is the AAA of access control?

* Authentication (validate a subject is legitimate); authorization (validate that the access request itself is permitted for that subject, object, and conditions); accounting (keep records of every attempt and what it resulted in)

## What is discretionary access control?

* Allows subjects (users) to modify access control system constraints, rules, or policies

## Define middleware and glueware.

* Middleware: special software that interfaces systems and platforms together. Glueware: small, sometimes ad hoc bits of code or shell scripts used to integrate, patch, or address problems in a software system or application

## What are MAO, MTO, and MTPOD?

* Maximum allowable outage; maximum tolerable outage; and maximum tolerable period of disruption (which is the longest time that systems can be inoperable before intolerable disruption or damage is done to the busin

## What is datagram encapsulation?

* Makes resulting datagrams longer by adding header and footer information (and possibly by encrypting the original datagram as payload)

## What are IPv4 address classes?

* Class A: First octet 0–126 (first bit 0); Class B: first octet 128–191 (first two bits always 10); Class C, first octet 192–223 (first three bits always 110); Class D, first octet 224–239 (first 4 bits always 1110)

## What are mantraps?

* Physical security controls that can restrict entry to a protected area; can also detain a potential intruder between their entry and exit doors

