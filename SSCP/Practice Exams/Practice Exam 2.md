

## 1. Strong authentication requires which of the following?

* A. One-time password schemes
* B. Biometrics
* ### C. At least two of the three authentication factors
* D. Role-based access control

```
The three authentication factors are what the subject has, knows, and is.
```

## 3. When implementing a password-based access control solution, what function should be used to help avoid rainbow table collisions?

* A. Multistring concatenation
* B. Modular addition
* C. Message pad
* ### D. Salt

```
Salting involves injecting another randomly chosen value into the encryption process used to protect the password plain text.
```

## 4. Which of the following is one of the three primary rules in the Biba model?

* ### A. A subject cannot request services from an object that has a higher integrity level.
* B. A subject cannot modify an object that has a lower integrity level.
* C. A subject can read an object that has a lower integrity level.
* D. A subject cannot read or modify an object of either a lower or higher integrity level.

```
“Read-Up” is restricted in Biba’s simple integrity model.
```

## 5. A key employee reports that he left his personal smartphone on a train; he uses it with company systems and data extensively when he travels or commutes. What would you recommend that management do immediately, with respect to identity management and access control, for your federated access systems? Choose the most appropriate statement.

* A. Deprovision the employee’s identity.
* ### B. Use the mobile device management (MDM) system to lock or “brick” the device if it can, and attempt to track its location.
* C. Suspend all access privileges for the employee’s identity, and notify all federated systems partners to ensure that they take similar steps.
* ### D. Suspend all access privileges for devices normally used by the employee, such as their laptop, phablet, or phone (employee-owned, company-provided, or both). If possible, quickly establish a captive portal or quarantine subnet to route access attempts from these devices to.

```
Option A unnecessarily removes the identity from your systems and those of other systems in your federated access system; this would not be called for. Option C still allows devices that the employee had been known to use to access your systems; if the employee, these devices, or both are in hostile hands, this places your systems at risk. Option B correctly addresses trying to freeze or protect data on the device, and Option D prevents it from being used to attempt access to company systems.
```

## 6. Which of the following are behavioral traits in a biometric device?

* ### A. Voice pattern and keystroke dynamics
* B. Signature dynamics and iris scan
* C. Retina scan and hand geometry
* D. Fingerprint and facial recognition

```
The other options are not subject to conscious control or action by the subject.
```

## 7. Which statements about authentication, authorization, and accounting (AAA) in access control are correct? (Choose all that apply.)

* A. Accounting provides the authorization to access resources as part of chargeback systems.
* ### B. Analysis, auditing, and accounting are the services provided by an access control system’s server.
* ### C. Authorization checks to see if an identity has the right(s) to access a resource, whereas authentication validates that the identity is what it claims to be. Accounting tracks everything that is requested, approved, or denied.
* D. Authentication checks to see if an identity has been granted access privileges, using the access control tables in the central repository; authorization validates the identity is allowed to access the system. Accounting keeps track of all requests, approvals, and denials.

```
Access control is not involved with resource chargeback—that is, billing; thus A is not correct. Option D has confused the roles of authorization and authentication, which Option C states correctly. Option B is correct—this is the “triple A” of access control.
```

## 8. Which step in the identity management process is where privileges are removed?

* A. Proofing
* ### B. Provisioning
* C. Revocation
* D. Deletion

```
Privileges may be altered (including being removed) throughout the life cycle of an identity; deletion removes the identity completely from the system.
```

## 9. Access to organizational IT systems by remote users needs to address a number of information security concerns. Which of these concerns is addressed by mobile device management (MDM) solutions?

* A. Encryption of communications and data links to the user’s mobile endpoint device
* ### B. Data loss prevention due to lost or stolen mobile endpoint devices
* C. Physical security of the remote work location, devices, and data used or stored there
* D. Encryption of data while stored on the mobile endpoint device

```
MDM systems can lock or randomize content on a device declared as lost or missing. The other issues are handled by other aspects of IT security.
```

## 10. Identity and access management is an implementation of access control. Access control can be implemented in one of two broad ways. They are:

* ### A. Centralized and decentralized
* B. Mandatory and discretionary
* C. Role-based and identity-based
* D. Subject-based and object-based

```
Option A is correct; there is one system and one decision point for all subjects, objects, and rules, or multiple systems for subsets of those. Other options refer to aspects of implementing this broader choice, which can create hybrid approaches.
```

## 11. View-based access controls are an example of:

* A. Audit control
* ### B. Constrained user interface
* C. Temporal constraint
* D. Side channel

```
A view is a selected set of data items and relationships shown to a user; this limits or constrains the user’s ability to learn the presence or values of other items, and thus is a constrained interface (Option B is correct).
```

## 12. Which of the following implementations provides the most rigorous access control possible?

* A. Role-based
* B. Rule-based
* C. Temporal-based
* ### D. Attribute-based

```
Attribute-based systems use complex logical rule sets (Boolean logic) to check multiple sets of constraints such as roles, time, or other conditions.
```

## 13. Due diligence means:

* A. Pay your debts completely, on time
* B. Doing what you have to do to fulfill your responsibilities
* ### C. Making sure that actions you’ve taken to fulfill your responsibilities are working correctly and completely
* D. Reading and reviewing the reports from subordinates or from systems monitoring data

```
Options A and B are both examples of due care; due diligence is the verification that all is being done well and properly. Option D can be an important part of due diligence, but it is missing the potential for follow-up action.
```

## 14. Why is the preamble to (ISC)2’s Code of Ethics important to us as SSCPs?

* ### A. It is vital to understanding the code because it sets purpose and intention; it’s our mission statement as professionals.
* B. It sounds like it ought to be important, but it just states personal values; the canons tell us what to do and why that matters.
* C. It’s not that important, since it only provides a context for the canons, which are the real ethical responsibilities that we have.
* D. It sets the priorities for us to address, highest to lowest, starting with the profession, the organization, the people we work for or our customers, and then society as a whole.

```
Option A correctly interprets the words themselves of the preamble. Option B is incorrect. The preamble does not set personal values (such as “honesty”); these are in the canons and tied to actions we should take. Option C misses the point of the code.
```

## 15. Blacklisting is an example of:

* A. Positive security model
* B. Identity management
* C. Threat modeling
* ### D. Negative security model

```
Blacklisting involves eexcluding something based on what it is and is thus a negative security model.
```

## 16. Fred discovers that someone in the company’s payroll department has been modifying employee timecard data. If done without proper authorization, this would be what kind of violation?

* ### A. Integrity
* B. Confidentiality
* C. Availability
* D. Privacy

```
The taken-together correctness or wholeness of the data may have been violated, causing some employees to be paid more or less than they deserve. This violates the presumed integrity of the timecard and payroll data. Presumably, payroll staff have legitimate reasons to access the data, and even enter or change it, so it is not a confidentiality violation; since the systems are designed to store such data and make it available for authorized use, privacy has not been violated. Timecard data records have not been removed, so there are no availability issues.
```

## 17. Most attacks and compromises are the result of:

* A. Highly sophisticated advanced persistent threats
* B. Social engineering attacks
* ### C. Misconfiguration, default passwords, unpatched systems, and basic lack of adequate controls
* D. Failures by management to adequately fund, resource, and manage information systems security measures

```
Known vulnerabilities left unmitigated provide the easiest path for attackers to take; this includes obvious social engineering techniques. Many things, including lack of due care and due diligence by management, can contribute to this.
```

## 18. Protection of intellectual property (IP) is an example of what kind of information security need?

* A. Privacy
* ### B. Confidentiality
* C. Availability
* D. Integrity

```
Disclosure of intellectual property in unauthorized ways can end up giving away any competitive advantage that IP might have had for the business.
```

## 19. What is the core objective of an information security program?

* ### A. Support business mission
* B. Protect assets
* C. Ensure confidentiality
* D. Enforce least privilege

```
The other options are part of the how and the why, but the organization’s purpose and mission are what information security must support.
```

## 20. Whitelisting as a security approach:

* A. Requires effective, integrated identity management and access control
* ### B. Includes what is known to be trustworthy
* C. Excludes what is known to be untrustworthy
* D. Requires digitally signed software or data

```
Whitelisting may be implemented via integrated identity management and access control, or rely on digital signatures; it can also be done in other ways.
```

## 21. A thunderstorm knocks out the commercial electric power to your company’s datacenter, shutting everything down. This impacts which aspect of information security?

* A. Privacy
* B. Confidentiality
* C. Integrity
* ### D. Availability

```
If the equipment cannot run because there is no power, then no data stored in it can be displayed, printed, or shared with users—data is not available. Some transactions may have to be recovered and rerun once the power comes back up and everything is turned on again, but only if transactions were lost completely would there be a data integrity concern.
```

## 22. In general, what differentiates phishing from whaling attacks?

* ### A. Phishing attacks tend to be used to gain access to systems via malware payloads or by getting recipients to disclose information, whereas whaling attacks try to get responsible managers to authorize payments to the attacker’s accounts.
* B. Phishing attacks are focused on businesses; whaling attacks are focused on high-worth individuals.
* C. Whaling attacks tend to offer something that ought to sound “too good to be true,” whereas phishing attacks masquerade as routine business activities such as package delivery confirmations.
* D. Whaling attacks send out huge numbers of emails attempting to lure targeted individuals into responding or following a link; phishing attacks use telephone or other means of making personal contact with a selected target.

```
Option A is correct; phishing tends to seek information, whereas whaling (and spear phishing) seeks action, typically the release of funds to the attacker. Option B is incorrect; whaling is primarily aimed at senior business leaders, whereas phishing can be aimed at anybody, anywhere, if the attacker perceives there is something worthwhile to learn in doing so. Option C has these reversed; whaling attacks depend on credibility of the business transaction they request. Option D is incorrect, since it reverses key characteristics of whaling and phishing.
```

## 23. Which of the following statements about information security risks is most correct regarding the use of collaborative workspace tools and platforms?

* A. Because these tools encourage open, trusting sharing of information and collaboration on ideas, they cannot be used to securely work with proprietary or sensitive data.
* B. These tools require strong identity management and access control, as part of the infrastructure beneath them, to protect sensitive or proprietary information.
* C. Granting access to such collaboration environments should first be determined by legitimate business need to know and also upon trustworthiness.
* ### D. First, the organizations collaborating with them should agree on how sensitive data used by or created by the team members must be restricted, protected, or kept safe and secure. Then, the people using the tool need to be fully aware of those restrictions. Without this, the technical risk controls, such as access control systems, can do very little to keep information safe and secure.

```
Option A is false; appropriate administrative and technical controls can and should be used to reduce information security risks to acceptable levels. Option B is correct in part, but without the users of the tool being fully aware of the CIANA needs pertaining to the data, information, and knowledge that is being collaborated upon, the technical controls are meaningless. Option C is correct in part but does not address user awareness, education, or training. Option D covers the key elements of user awareness and education and support the CIANA requirements for this collaboration; thus, the technical controls can do their job more effectively.
```

## 24. Which statement best describes how does the separation of duties relate to education and training of end users, managers, and leaders in an organization?

* A. Separation of duties would dictate that general education and awareness training be done by different people than those who provide detailed skills-based training for the proper handling of sensitive information.
* B. Separation of duties should identify groups or teams that have little need for information security awareness, training, and education so that effort can be better focused on ones with greater needs.
* ### C. Separation of duties should segment the organization into teams focused on their job responsibilities, with clear interfaces to other teams. Effective awareness training and education can help each team, and each team member, see how successfully fulfilling their duties depends on keeping information safe, secure, and reliable.
* D. Separation of duties would dictate that workers outside of one team’s span of control or duties have no business need to know what that team works with; education and training would reinforce this.

```
Option A is incorrect; in general, the same core information security team members should actively shape and guide all information security awareness, education, and training efforts across the organization. Option B is incorrect; it shows a misunderstanding of separation of duties, which typically breaks a task for one trustworthy person or group into two or more sets of tasks for two (or more) trustworthy people or groups, so as to provide a check and balance arrangement. This would typically involve information at the same level of sensitivity or classification. Option C is correct, as it links the opportunities that separation of duties can suggest for focusing such education and training. Option D, like Option B, does not apply separation of duties correctly. It is not intended to produce “compartments” that others cannot know about; rather, it drives the design of access controls or administrative controls to prevent one person from taking incorrect action.
```

## 25. Your company uses computer-controlled machine tools on the factory floor as part of its assembly line. This morning, you’ve discovered that somebody erased a key set of machine control parameter files, and the backups you have will need to be updated and verified before you can use them. This may take most of the day to accomplish. What information security attribute is involved here?

* A. Confidentiality
* ### B. Integrity
* C. Availability
* D. Due care

```
Although it is clear that the necessary parameter files are not available, this seems to have been caused because somebody could violate the integrity requirements of those files—deleting them does not seem to have been an authorized change.
```

## 26. Which of the following best describes the capabilities of camera systems in physical security?

* A. Cameras provide deterrence and corrective capabilities.
* B. Cameras can provide a preventive type of control.
* C. Cameras can be effective without monitoring.
* ### D. Cameras provide surveillance, incident detection, and response capabilities.

```
Remote visual surveillance by itself cannot correct, contain, or respond to an incident. Their obvious or suspected presence can provide some deterrent value, whether or not the attacker can know they are monitored.
```

## 27. As a security flaw, buffer overflow is caused by:

* A. Lack of effective scanning or filtering of incoming packets
* B. Failure to configure the presentation layer properly
* ### C. Poorly designed and poorly tested code
* D. Improper user training

```
This classic security flaw is completely preventable, if only software developers and their managers enforced lessons learned regarding input data validation.
```


## 28. Source code escrow can be used to protect against:

* A. Vendor-placed backdoors
* B. Breaches of licensing agreements
* C. Lack of documentation
* ### D. Vendor bankruptcy

```
The other three options are difficult to impossible to evaluate until its vendor/creator goes out of business.
```

## 29. Which of the following statements is correct in regard to source code escrow?

* A. Allows organizations to meet contractual obligations in regards to software licensing
* ### B. Protects against software vendor bankruptcy
* C. Allows detection of vulnerabilities in software
* D. Allows backing up of critical software

```
Source code escrow can also be applied to reduce the risk of technology obsolescence, such as for device drivers, by paying a licensing (escrow) fee to the vendor.
```

## 30. A double blind test is:
* A. A strategy for operational test and evaluation to see if day-to-day business activities are still working correctly with a new or modified system
* B. A penetration test strategy without the knowledge of the incident response teams
* ### C. A penetration test strategy in which the test team has no insider knowledge of systems, procedures, or security posture, and the incident response teams have no knowledge of the upcoming or ongoing test
* D. A black box style of testing used during systems development

```
Double-blind testing requires that the bare minimum of senior leadership, IT, and operational managers and staff know of the test, and that test team “attackers” are realistically acting as naive outsiders, to make the test as realistic as possible.
```

## 31. Every control must be tested to ensure correct operation. Three questions should be addressed by control assessment. Which of the following is not a question that addresses this need?

* A. Was the control implement correctly?
* ### B. Was the control approved by audit?
* C. Is the control operating correctly?
* D. Is the control meeting its desired result?

```
Audits neither approve nor disapprove controls; they may assess whether your process for choosing, implementing, using, and monitoring the control meets audit standards, however.
```

## 32. Treating risk may include four options. They are avoiding risk, accepting risk, mitigating risk, and ______.

* A. Deterring risk
* B. Ignoring risk
* ### C. Transferring risk
* D. Insuring risk

```
Transferring involves making someone else responsible for the efforts and costs of recovery if the risk becomes an event. Usually this is done via insurance or other contracts.
```

## 33. What are the three broad types of risk mitigation controls or countermeasures?

* ### A. Physical, logical, and administrative
* B. Legal, regulatory, and ethical
* C. Role-based, rule-based, and attribute-based
* D. Deter, avoid, accept, and prevent

```
Types of controls indicate whether people, information technology parameters and settings, or walls, doors, locks, guards, and guns deliver the control or countermeasure effect.
```

## 34. What type of standards should be followed when conducting information security audits?

* A. The organization’s business plan, business impact analysis, and risk management plan
* ### B. Standards appropriate to the type and purpose of the audit
* C. COBIT 5 and ITIL
* D. ISO 27002

```
Audits may be done for many purposes; the right standard should be used to ensure that audit procedures, activity, and the auditors themselves produce audit findings that are credible and actionable.
```

## 35. Which statement about how different types of controls provide greater information security is most correct?

* A. Physical controls provide the greatest security, because they restrict physical movement into protected spaces or actual contact with hardware and systems.
* B. Administrative controls provide the greatest security, since they ensure that all company personnel follow the best procedures to keep information systems safe and secure.
* C. Logical controls provide the greatest security, because these implement management and policy decisions into features and settings in systems software and hardware.
* ### D. There is no real comparison between these types of controls, since they all address risks very differently.

```
Options A, B, and C are all false; the choice of the best risk control for a specific vulnerability in a particular situation must reflect a trade-off of risk, cost, ease of implementation, and residual risk, among other factors. Thus Option D is correct.
```

## 36. Which term refers to disabling unnecessary services, features, and accounts or identities on a system, as a way to reduce its potential attack surface?

* A. Mitigation
* ### B. Hardening
* C. Penetration testing
* D. Vulnerability assessment

```
Hardening is a subset of all possible mitigation approaches.
```

## 37. The proper way to manage and oversee change management in any organization is to:

* A. Delegate change management and control to the IT or systems departments responsible for particular systems, platforms, or apps.
* B. Require that change requests, implementation plans, and regression tests are reviewed and accepted by all affected elements of the organization.
* ### C. Adopt appropriate builds and controls technologies that help you control, manage, and track changes to software, hardware, and data configuration items, and establish formal management procedures to have all affected parties participate in such change decisions.
* D. Migrate your business into the cloud via platform as a service, and then delegate all configuration management problems to your cloud services provider via your service level agreement with them.

```
Informed management provides better decision making and gains more support from those affected by change.
```

## 38. What measures can be taken to reduce the information security risk of shadow IT systems?
* A. Implement dual-factor authentication and more stringent access controls
* B. Disable or lock features in applications suites that make shadow IT systems easy to write and spread through the organization
* C. Make greater use of Common Vulnerabilities and Exposures (CVE) data in designing and maintaining such systems
* ### D. Enforce standards for regular management review of all data produced by such systems before it is used in operational decision making

```
Option D puts the burden of verification and validation on the managers depending on the results of such shadow IT systems, which incentivizes them to better maintain and control their design and use. Option C is false, as CVE data is for systems and software in widespread use and not for customized one-of-a-kind programs. Option B is false, because this has proven unworkable in practice and denies the potential of significant payback to the organization if they make better, more well-managed use of these features (and the shadow IT they build using them). Option A is false, since identity management and access control have nothing to do with homegrown software being vulnerable or prone to exploitation.
```

## 39. Why should configuration management should be based on a foundation of policies, standards, and procedures?

* ### A. These provide the starting point to make configuration management and control reliable, repeatable, and verifiable, thus reducing risk.
* B. All organizations work better with written policies and procedures.
* C. Regulatory and legal needs for compliance dictate these.
* D. These form a valuable knowledge base for systems operation and maintenance.

```
The goal of configuration management is to reduce risk to systems and processes necessary to achieve organizational objectives. Reliability increases with well-defined, clear procedures and standards.
```

## 40. What is the role of users having good security awareness in dealing with the risk of social engineering?

* ### A. By itself, minimal; when coupled with focused task-based or role-based information security training, it can enable employees to better detect potential social engineering attacks, while providing guidance as to how they should respond.
* B. Unlimited; it can inform each employee’s reaction to small but not-quite-normal events, as they find the right best way to respond to people and situations.
* C. Minimal; awareness training is typically done when the employee first joins the organization and has little effectiveness without specific job-based training.
* D. Minimal; although it gets users to think about information security as a risk to the company, their jobs, and others, it doesn’t help them deal with new or novel situations, contacts by outsiders, and so forth.

```
Combining awareness of the constantly evolving threat landscape with practical ways to detect, characterize, and respond to something new is critical to effective defense against social engineering attacks.
```

## 41. The business impact analysis (BIA) is considered the most important component of business continuity planning because:

* ### A. It provides the foundation for understanding the criticality of the organization’s functions.
* B. It translates the prioritized results of the vulnerability assessment into a risk mitigation plan.
* C. It dictates day-to-day application of risk mitigation controls and countermeasures.
* D. It demonstrates the commitment of senior management and leadership to the information risk mitigation strategy.

```
The other options refer to other steps in the overall risk management process; the BIA puts risks in terms of bottom-line impacts to survival or accomplishing prioritized objectives.
```

## 42. he third step in risk management is:

* A. Frame risk
* B. Analyze risk
* ### C. Treat risk
* D. Quantify risk

```
Framing risk means to state it, in human language, in ways that communicate effectively to decision makers; this is important. Quantify is part of analysis and assessment; thus, frame, analyze, and treat.
```

## 43. Which of the following is true?

* A. Senior management’s attitude is not important in risk management.
* ### B. Risk management must always be conducted in alignment with the goals, mission, and culture of the organization.
* C. External factors should not be a consideration in risk management.
* D. All risk can and should be managed.

```
All aspects of risk management require balancing exposure to loss, opportunities to improve, and available resources against goals and objectives. Management and leadership make these decisions, in part based on their tolerance for ambiguity.
```

## 44. Who is ultimately accountable for risk management?

* A. Systems administrators
* B. Workgroup managers and supervisors
* ### C. Senior management and leadership
* D. End users

```
Others in the organization have responsibilities for what has been delegated to them, but senior leaders and managers own it all.
```

## 45. Determining whether a chosen safeguard is cost-effective means that:

* ### A. You must compare the total expected losses, over time, with the total costs to acquire, install, and use the safeguard.
* B. The single loss expectancy (SLE) is greater than the safeguard value.
* C. The total of replacement costs or values of the asset at risk, other related business losses including lost opportunity costs, is greater than the safeguard value.
* D. The annualized loss expectancy is less than the safeguard value.

```
We often simplify risk assessment by using annualized exposure, loss (which reflects fraction of asset value harmed, not total asset value), and safeguard costs; many safeguards have high initial costs and lower annual recurring operational costs. So the real comparison typically looks across a number of years.
```

## 46. It’s time for a compliance audit of your security systems and procedures. Your boss wants to save money and have an internal team do the audit. Which statement would be your best response to your boss?

* A. Our internal people may have the right skills and knowledge to do this audit, so this might be a good idea.
* B. We don’t really have anyone on our team who understands the audit standards, so we may need an external auditor anyway.
* C. We’ve got people who could do the audit, but their workloads and our priorities would mean the audit has to be delayed by several months.
* ### D. Compliance requirements and standards may dictate that the auditors be independent and certified, or the findings may not be acceptable.

```
In most cases, compliance audits must be done by trained and certified external auditors if the results are to be acceptable to legal, regulatory, insurance, or financial authorities.
```

## 47. SLE = \_\_\_\_ × exposure factor.
* A. Safeguard value
* ### B. Asset value
* C. (Asset value minus safeguard value)
* D. Asset value × annualized rate of occurrence

```
Exposure to loss by a single loss expectancy (SLE) considers all assets damaged by the event and the fraction of their value that is lost or compromised.
```

## 48. Which of the following is not true?

* A. The implementation of a control addresses a vulnerability.
* ### B. The implementation of effective controls will eliminate all quantified risks.
* C. A control that is proactive and tries to stop something before it happens is often called a safeguard.
* D. A control that is reactive and attempts to limit the effect of an attack is called a countermeasure.

```
Some risks cannot be quantified but can still be effectively controlled.
```

## 49. Which of the following statements is true?

* A. Business continuity planning (BCP) and disaster recovery planning (DRP) are the same.
* B. BCP is part of DRP.
* C. Both BCP and DRP are mutually exclusive.
* ### D. DRP is part of BC.P

```
The goal of all of this planning is to stay in business despite risk events large and small. Disasters are large events and thus a subset of the overall business continuity planning.
```

## 50. Why should a security practitioner be alert to identifying single points of failure in systems, processes, or business logic?

* A. Such points of failure usually indicate poorly performed systems maintenance and upgrades.
* B. Each such point may be a possible opportunity for product or process improvement and is worth investigating.
* ### C. Single points of failure can bring entire chains of business processes to a halt and thus represent a potentially critical vulnerability.
* D. During incident investigation, these should be checked to see if one or more of these had become the proximate cause.

```
Availability is put at great risk by such single points of failure, regardless of whether they are exploited by accident, other failures, or attackers. Prevention of such impacts should be prioritized and addressed properly.
```

## 51. What is the primary purpose of testing an intrusion prevention system (IPS)?

* ### A. To verify that the IPS is detecting and initiating an appropriate response to a suspicious activity
* B. To determine whether the IPS is capable of discarding suspect packets
* C. To analyze processor utilization to verify whether hardware upgrades are necessary
* D. To test whether the IPS can log every possible event on the network

```
IPSs are not limited to just discarding suspect packets; testing verifies that the IPS you’ve installed is giving you the right mix of protection at acceptable error levels.
```

## 52. Which of the following statements about social engineering attacks is incorrect?

* A. Most targeted individuals don’t see the harm in responding or in answering simple questions posed by the attacker.
* B. Most people believe they are too smart to fall for such obvious ploys, but they do anyway.
* ### C. Most targeted individuals and organizations have effective tools and procedures to filter out phishing and related scams, so they are now better protected from such attacks.
* D. Most people want to be trusting and helpful.

```
Options A, B, and D all demonstrate the hallmarks of social engineering attacks—they work (and have worked for thousands of years) because people are generally trusting, open, and willing to engage with strangers. Option C, the correct choice, is unfortunately not true; tools may help filter out some email-based social engineering attacks, but few organizations have truly been able to operate with a “loose lips sink ships” approach and deal openly with customers, clients, and many other outside stakeholders.
```

## 53. Which statement about the role of end users in detecting information security incidents is correct?

* A. Most end users may have significant experience with the routine operation of the business systems and applications that they use, but they cannot produce useful precursor or indicator information regarding possible information security incidents.
* ### B. Most end users and their first-level supervisors have the best, most current insight as to the normal business rhythm, flow, and therefore normal loads on the systems and their throughput. They will most likely see anything “abnormal” quickly as a result.
* C. Users think that they know a lot about “business normal,” but we need to rely more heavily on well-instrumented intrusion detection systems, access control, and other monitoring capabilities.
* D. Since most advanced persistent threat (APT) kill chains use low and slow attack methods to reconnoiter and gain access, by the time users see things behaving abnormally, it’s too late.

```
Option A is incorrect; it’s rather dismissive of the knowledge that most line workers have when it comes to how business actually gets done every day. Users may need better training as to what to do when they think they see a problem, but that’s not addressed by this option. Option C is incorrect, demonstrating a narrow vision that only sees the technological solutions as useful. Option D is incorrect, notably that it is never too late to sound an alarm. Option B correctly expresses the value of knowledge and experience. Harnessing this insight in real time as part of an intrusion or anomaly detection process, however, is another story.
```

## 54. Which set of plans and procedures should define how the organization makes backups of systems, applications, device settings, databases, and other data for use during the recovery phase of an information systems security incident response?

* A. Information security incident response plans and procedures
* B. Disaster recovery plans (DRPs) and procedures
* ### C. Business continuity plans (BCP) and procedures
* D. Information technology configuration management plans and procedures

```
Option A is false; the response team should need to know only how to find and use such backups and not be responsible for their initial generation or routine update. Option B is false; the DRP would address options spelled out in the BCP as to alternative processing locations, contingency plans, and so forth, all of which need the backups that the BCP directs be made. Option D is false; configuration management is the decision process that allows or prevents changes to hardware, software, or key data items or structures, but it doesn’t manage backups. Option C correctly links the purpose of backups—continuing to get business done in the face of accidents, systems failures, attacks, or natural disasters—with the need for a specific set of resources—that is, backups.
```

## 55. Creating incident response policies for an organization would be an example of which of the following?

* A. Technical control
* ### B. Administrative control
* C. Logical control
* D. Physical control

```
Note that many IT systems have software controls called “policies,” which should not be confused with documents that tell people what to do and why.
```

## 56. Which of the following is the most time-critical phase of activity in incident response?

* A. Eradication
* ### B. Detection
* C. Containment
* D. Preparation

```
The other phases cannot start until you’ve detected something that might need responding to.
```

## 57. Which of the following statements is the most correct in incident response?

* ### A. The goal of incident response is to minimize the damage and learn from the incident as to prevent it from happening again.
* B. The goal is to prevent incidents from happening.
* C. Incident response does not require a policy that provides its foundation.
* D. Incident response does not involve problem management.

```
ncidents will happen; 100 percent prevention is not a reality we can achieve. Thus, be prepared to detect, contain, and respond. This requires management and leadership commitment and prioritization, which usually requires written policy and direction.
```

## 58. You’re the only IT person at a small tool and die machine shop, which uses a local area network (LAN) and cloud-hosted platforms to run the business on. The previous IT person had told your boss not to worry about the business being the target of a cyberattack. Which statement best lets you explain the real risks the company might face?

* A. Since we don’t handle consumer-level payment cards, and we don’t have any proprietary information, we probably don’t have to worry about being a target.
* B. We do share an extranet connection with key customers and suppliers, but it should prevent an attack on our systems that could lead to an attack on theirs.
* C. Our cloud systems hosting company provides most of our security, and as long as we keep our systems on the factory floor and the workstations our staff use properly updated, we should be okay.
* ### D. Since we haven’t done even a basic vulnerabilities assessment, we don’t know what risks we could be facing. Let’s do that much at least, and let that tell us what the next step should be. Soon.

```
Although Option A may be true, it is naïve and incorrect; the air-conditioning company that serviced Target stores didn’t handle retail (credit card) sales either, yet attackers found it to be an ideal entry into Target’s payment processing systems. Option C is also incorrect; your cloud hosts will protect their systems, and their platforms, from malware attacks from your connections, but attackers who spoof bogus, privileged accounts into your systems can still destroy your business’s presence in those cloud systems. Option B is incorrect; without doing a detailed vulnerability assessment of that architecture, you are at risk making this assumption. Option D offers the boss a sensible first step.
```

## 59. Which of the following would be the first step to be conducted as an investigator arrives at a crime scene?

* A. Maintain chain of custody
* B. Prove the integrity of the scene
* ### C. Secure the scene
* D. Interview potential witnesses

```
Securing the scene limits the opportunity for evidence to be corrupted by other people or processes. It’s the first step in the chain of custody.
```


## 60. Which of the following is not a legal or regulatory issue that a computer security incident response team (CSIRT) would have to be concerned with?

* ### A. Incidents caused by employee negligence or accident
* B. Incidents caused by misuse of systems by an employee
* C. Incidents that may involve competitors attempting to access company proprietary information
* D. Incidents that disrupt normal business operations

```
Option A usually does not have a legal or regulatory obligation that the CSIRT must respond to (although there may be requirements for the organization to report statistics on such incidents to regulators or other authorities). Option B could lead to disciplinary actions or firing the employee involved, which could result in litigation. Option C may be criminal trespass or violation of other criminal laws. Option D may, depending on the nature of the business and its activities, require safety, security, or investor and consumer protection reporting and notification actions by the organization, regardless of cause.
```

## 61. What is the most important component of business continuity planning?

* ### A. Business impact analysis (BIA)
* B. Vulnerability assessment
* C. Disaster recovery plan
* D. Incident response plan

```
The BIA sets the priorities that all else follow from.
```

## 62. Which concept refers to the point in time to which data could be restored in the event of a business disruption?

* A. Recovery time objective (RTO)
* B. Business impact analysis (BIA)
* ### C. Recovery point objective (RPO)
* D. Maximum tolerable downtime (MTD)

```
The RTO and MTD express how quickly after an incident that services need to be restored. RPO looks at how far back in time before the incident you have to find and restore data, or re-accomplish transactions and updates.
```

## 63. What type of testing that should be performed when initially testing a disaster recovery plan?

* A. Simulation
* ### B. Structured walkthrough
* C. Parallel
* D. Full interruption

```
Structured walkthroughs are inexpensive ways to “desk-check” the recovery plan, while beginning to familiarize people with the roles they’ll need to perform during an actual recovery.
```

## 63. Which RAID level uses block-level striping with parity information distributed across multiple disks?

* A. RAID 0
* B. RAID 1
* C. RAID 4
* ### D. RAID 5

```
RAID 0 provides higher throughput but no redundancy. RAID 1 mirrors a whole disk. RAID 4 doesn’t exist.
```

## 64. Applied against a given block of data, what does a hash function create?

* A. A chunk of the original block used to ensure its confidentiality
* B. A block of new data used to ensure the original block’s confidentiality
* C. A chunk of the original block used to ensure its integrity
* ### D. A block of new data used to ensure the original block’s integrity

```
Be careful here; hashing does not change the contents of the original plain text but creates a unique new data block (the hash value) from the original, which can be used to verify the original has not been changed since the hash was generated.
```

## 65. In symmetric key cryptography, what should each party use?

* A. Key encrypting key
* ### B. Previously exchanged secret key
* C. Randomly generated value unknown to anyone
* D. Public key exchanged with the message

```
A random key value unknown to the recipient will not support decryption. The other options either refer to public/private key systems.
```

## 66. Steganography uses cryptographic means to:

* A. Corrupt the integrity of a message or file in ways not easily detectable
* B. Reduce the likelihood of key clustering
* ### C. Hide the plain text within another unencrypted data stream, message, or file
* D. Provide for nonrepudiation by watermarking

```
Watermarking is an example of using steganography to achieve a purpose such as nonrepudiation; it is not, however, what steganography is. It won’t help with key clustering, and a simple hash of the plain text will show that the plain text has been changed.
```

## 67. Symmetric cryptography is best characterized by:

* A. Using in-band communications for key distribution and management
* ### B. Using the same key for encryption and decryption
* C. Having much greater work factors than other forms of encryption
* D. Providing for very fast encryption and decryption only in streaming mode

```
Symmetric encryption must rely on out-of-band key management; it can be significantly easier to break (lower work factor) than asymmetric approaches for same key length.
```

## 68. What is the input that controls the operation of the cryptographic algorithm?

* A. Decoder Wheel
* B. Encoder
* ### C. Cryptovariable
* D. Cryptographic routine

```
Cryptovariables tend to specify block size, transposition, or substitution lengths; seeds for random number generators; or salt values. In some cryptosystems, they are fixed by the implementers; in others, they can be user specified.
```

## 69. Which of the following describes the Caesar Cipher?

* A. Substitution and transposition cipher
* B. Transposition by three characters
* C. Plaintext only cipher
* ### D. Substitution cipher by three characters

```
No transposition is involved.
```

## 70. Which of the following is not directly provided as a result of using cryptography?

* A. Authentication
* B. Confidentiality
* ### C. Availability
* D. Integrity

```
Cryptographic support of identity management, access control, file or system integrity checks, and so forth can contribute to availability, but encrypting files or messages without those other security measures alone will not.
```

## 71. All of the following address integrity except:

* A. Message Authentication Code (MAC)
* ### B. Data Encryption Standard (DES)
* C. Parity protection
* D. Message Digest 5 (MD5)

```
Integrity requires a way to verify that message or file plain text has not been altered over time; anything one could conceivably decrypt could lend itself to attacking the plain text’s integrity. Encryption, such as DES, may or may not be a part of a chosen integrity implementation.
```

## 72. Does the use of asymmetric algorithms have a scalability problem as more people require confidential communications?

* A. Yes, as indicated by the dramatic growth in Internet of Things (IoT) devices becoming part of the Internet.
* B. No, so long as full Internet Protocol Security (IPSec) implementations in IPv6 are used.
* C. No, as long as you’re using webs of trust as part of certificate/signature authentication.
* ### D. No, as long as you’re using hierarchies of trust as part of certificate/signature authentication.

```
Managing the expiration (or compromise) of certificates is problematic in webs of trust. IPSec doesn’t address this.
```

## 73. Advanced Encryption Standard (AES) is a block cipher with variable key lengths of?

* ### A. 128, 192, or 256 bits
* B. 32, 128, or 448 bits
* C. 8, 64, or 128 bits
* D. 128, 256, or 448 bits

```
This standard was set in 2001 by the U.S. National Institute of Standards and Technologies (NIST).
```

## 74. What kind of encryption is used in Wi-Fi Protected Access 2 (WPA2)?

* A. Data Encryption Standard (DES) in streaming mode
* B. Advanced Encryption Standard (AES) in cipher block chaining (CBC) mode
* ### C. AES in a combination of cipher block chaining (CBC) and counter (CTR) mode
* D. Public key infrastructure (PKI) using ElGamal and DES

```
Set as the standard in 2004 by the Wi-Fi Alliance; the other options are incomplete and incorrect.
```

## 75. A certificate authority (CA) provides which benefit to a user?

* A. Protection of private keys of all users
* B. History of symmetric keys
* C. Proof of nonrepudiation of origin
* ### D. Validation that a public key is associated with a particular user

```
CA authentication of a public key is the bedrock of public key infrastructure (PKI) systems. The other options do not relate to this or misapply public/private key concepts.
```

## 76. In its simplest form, how many parties are involved in a transitive trust relationship within a domain?

* A. One
* B. Two
* ### C. Three
* D. Four or more

```
or parties A, B, C, if Party B trusts C, and A trusts B, A can infer that C is trustworthy based on B’s endorsement or referral.
```

## 77. Which of the following algorithms supports asymmetric key cryptography?

* ### A. Diffie-Hellman
* B. Blowfish
* C. SHA-256
* D. Rijndael

```
Blowfish and Rijndael are symmetric algorithms; SHA-256 is a hash algorithm.
```

## 78. Which statement best compares transmission control protocol (TCP) and user datagram protocol (UDP)?

* ### A. UDP is a best-efforts protocol and thus provides high reliability.
* B. TCP provides retransmission and sequencing control, thus providing high reliability.
* C. TCP is a best-efforts protocol and thus provides high reliability.
* D. UDP provides retransmission and sequencing control, thus providing high reliability.

```
Both TCP and UDP are Layer 4 protocols. The difference between them is that TCP is connection-oriented and provides reliable transport services, whereas UDP in connectionless and provides best-effort transport services. The other options reverse the nature of TCP (connection) and UDP (connectionless).
```

## 79. How do circuit-switched networks work?

* A. They divide data into packets and transmit it over a virtual network
* B. They establish a dedicated circuit between endpoints.
* C. They divide data into packets and transmit it over a shared network
* ### D. They establish an on-demand circuit between endpoints.

```
Plain old telephone service (POTS) is the clearest example of a circuit-switched network, with each phone call on a logical connection or circuit for its duration.
```

## What ports are commonly used for a Transport Layer Security (TLS) connection?

* A. 53 and 25
* B. 21 and 22
* C. 53 and 88
* ### D. 443 and 80

```
The ports are defined in Internet Engineering Task Force requests for comments and can be reconfigured/reassigned by systems and network designers to meet specific needs.
```

## When establishing connections between hosts, which four identifiers are used to identify the specific connection?

* A. Source URL, source port, destination URL, destination port
* B. Source MAC, source port, destination MAC, destination port
* C. Source IP, destination IP
* ### D. Source IP, source port, destination IP, and destination port

```
Host connections are at the network layer and thus use IP addresses and port numbers.
```

## Which of the following are valid host addresses for network address translation (NAT) according to Request for Comments (RFC) 1918?

* A. 172.168.10.31
* ### B. 10.168.10.17
* C. 192.168.10.257
* D. 172.15.10.29

```
RFC 1918 defined private address ranges (pre–Classless Inter-Domain Routing [CIDR]), using host ID sizes of 24, 20, and 16 bits for classes A, B, C, respectively. Count the bits from the left.
```

## Which of the following does not apply to Secure Sockets Layer (SSL)/Transport Layer Security (TLS)?

* A. Supports secure e-commerce transactions
* B. Provides secure connections between client and server
* C. Authenticates both client and server
* ### D. Does not use asymmetric algorithms

```
HTTPS or other protocols using SSL or TLS may provide session key wrapping, but SSL/TLS themselves do not.
```


## Which of the following would not be a good choice for a secure email system for a typical small business?

* ### A. Providing end users with suites of encryption tools they can use as they need to, to protect content
* B. Using third-party secure email services
* C. Using browser email client plug-ins or extensions
* D. Deploying a private secure email server and configuring encryption services for email as needed

```
The other options provide capabilities to set policies to encourage, require, or enforce the use of secure email capabilities.
```

## Which statement has the protocol layers in the correct top-to-bottom order?

* A. Physical, Data Link, Network, Transport
* B. Transport, Data Link, Network, Physical
* C. Presentation, Application, Session, Transport
* D. Presentation, Session, Transport, Network

```
The layers from most abstract to least abstract are as follows: Application, Presentation, Session, Transport, Network, Data Link, and Physical.
```

## What is the biggest security issue associated with the use of a Multiprotocol Label Switching (MPLS) network?

* ### A. Lack of native encryption services
* B. Lack of native authentication services
* C. Use of Wired Equivalent Privacy (WEP) and Data Encryption Standard (DES) algorithms
* D. The need to establish peering relationships to cross Tier 1 carrier boundaries

```
Most MPLS implementations provide encryption at higher protocol layers as a way around this. The other options do not apply to MPLS.
```

## When setting up firewall rules, which is the best practice to follow?

* A. Allow all and then take away
* ### B. Allow none and then add specific rules
* C. Use a mix of allow-none and allow-all based on a segmented network and systems view
* D. Use your risk assessment findings to guide this decision for each business process

```
This approach forces you to systematically identify required services and connections, and constrain by date, time, or other attributes, one by one. It also precludes overlooking a factory-default connection that you may not need or want.
```

## A new installation requires a network in a heavy manufacturing area with substantial amounts of electromagnetic radiation and power fluctuations. Which media is best suited for this environment if little traffic degradation is tolerated?

* A. Shielded twisted pair
* B. Coax
* ### C. Fiber
* D. Wireless

```
Other physical technologies are more prone to electromagnetic interference.
```

## Which of the following is typically deployed as a screening proxy for web servers?

* A. Intrusion prevention system
* B. Kernel proxies
* C. Packet filters
* ### D. Reverse proxies

```
Kernel proxies can help accelerate Secure Sockets Layer (SSL) but do not provide screening of service or resource requests. The other options are not proxies.
```

## Which of the following should be part of a network’s perimeter defense?

* A. Virtual local area network (VLAN)
* B. Domain Name System (DNS) server
* C. Switch
* ### D. Firewall

```
The other options by themselves provide no security capabilities.
```

## Which statement best describes what security information and event management systems can do?

* A. Provide script-based management of incident response team actions, to help preserve chain of custody of evidence
* ### B. Collect data from multiple sources and bring it together for meaningful analysis
* C. Manage network and systems resources, devices, apps, and so forth to ensure policies are consistently enabled and monitored
* D. Provide predictive analytics as a means of identifying event precursors

```
The other options take some very smart people to accomplish.
```

## A security incident event management (SIEM) service performs which of the following function?

* A. Configures software for security policies and procedures
* ### B. Aggregates logs from security devices and application servers looking for suspicious activity
* C. Documents incident handling and communication
* D. Matches user system authorization with physical access permissions

```
Though the other options are useful, if not vital, security tactics, they’re not what SIEMs do.
```

## Which type of technology can examine network traffic at much deeper levels?

* A. Host-based firewalls
* ### B. Proxy firewalls
* C. Network-based intrusion detection systems
* D. Antimalware systems

```
The others do not aAllow for application-layer traffic inspection.
```

## Which of the following should be used to protect wireless local area network (WLAN) communications?

* A. Wired Equivalent Privacy (WEP)
* B. Wireless Application Protocol (WAP)
* ### C. Wireless Application Protocol 2 (WPA2)
* D. Temporal Key Integrity Protocol (TKIP)

```
WEP and WAP have been shown to be vulnerable; TKIP was a short-lived Band-Aid for WEP and should no longer be used.
```

## All of the following are examples of social engineering attacks, except:
* A. Phishing
* B. Whaling
* C. Spear phishing
* ### D. Ransom

```
Ransom attacks (whether by ransomware or not) may involve social engineering as part of gaining access, but they don’t use social engineering to implement the attack.
```

## Which of the following is not an example of malware?

* A. Ransomware
* B. Logic bomb
* C. Trojan horse
* ### D. Tailgating

```
Humans tailgate other humans through checkpoints.
```

## What is a type of device with limited local storage capacity known as?

* A. Thick client
* ### B. Thin client
* C. Endpoint
* D. Peer

```
Thick clients have extensive “local” files, often needing synchronization with servers or cloud backups. Peers, as in peer-to-peer, are part of service relationships.
```

## Which of the following should not be addressed as part of endpoint security
* ### A. Monitor network traffic across the demilitarized zone (DMZ)
* B. Physical security
* C. Antivirus protection
* D. Access control

```
Endpoints cannot (or should not) have such visibility across all segments of your networks.
```

## Which of the following is not an essential characteristic of cloud computing?

* A. On-demand self-service
* B. Broad network access
* C. Rapid elasticity
* ### D. Single tenancy

```
While one deployment model (private clouds) does support single tenants, that does not make “single tenant” a defining characteristic of cloud computing.
```

## Which of the following hypervisor types would be most attractive to an attacker to compromise?

* A. Type 1, because it runs on hardware and provides lower-layer attack capabilities
* ### B. Type 2, because it runs on an operating system and therefore provides more opportunities
* C. Neither, because they are almost impossible to compromise
* D. Both Types 1 and 2, since they both exist in all environments

```
Attacking the host operating system (or subverting built-in features in it, via illicit access) may provide greater opportunity to attack or subvert the hypervisor.
```

## Which of the following statements is the best description of the hypervisor?

* A. Allows multiple hosts to share a single operating system
* B. Allows multiple applications to share multiple operating systems
* C. Allows multiple tasks to share a single operating system
* ### D. Allows multiple operating systems to share a single host

```
The other options address other multiprocessing or software deployment strategies not involving virtualization.
```

