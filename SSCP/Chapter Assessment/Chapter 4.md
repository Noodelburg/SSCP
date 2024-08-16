
## 1. Which statement(s) about information architectures and IT architectures are most correct?

* A. Securing the IT architecture first provides the fastest path to a prudent security posture; once that is achieved, a vulnerability assessment of the information architecture can be done to reveal other residual risks.
* ### B. Business needs should drive administrative security policies based on the information architecture; the IT architecture then needs to have its administrative, logical, and physical controls driven to support the information architecture’s security needs.
* C. The IT architecture’s security is primarily dependent on technical or logical controls; these need to be determined first, and then they will inform policy writers as they create or update administrative security requirements for the information architecture.
* D. Without effective education and training of all members of the organization, the IT architecture cannot be made secure or kept secure.

## 2. An architecture assessment includes which of the following activities? (Choose all that apply.)

* A. Review of risk mitigation plans and risk countermeasure log files
* B. Ongoing monitoring of systems performance, event logs, and alert data
* ### C. Review of problem reports, change requests, and change management information
* ### D. Review of network and communications connectivity, diagrams, wiring closets, etc.

```
Options C and D focus on trying to discern the “as-built” current state of the systems; whether this goes down to the cable-by-cable verification of what’s plugged in where could depend on how thorough the baseline needs to be. Options A and B refer to ongoing operation of the system after mitigation steps have been taken to see if incidents of interest are happening or if there is a need for additional risk mitigation.
```

## 3. How are dashboards used as part of systems monitoring or incident response?

* A. Dashboards typically display highly summarized key performance indicators, which are suitable for long-term business planning; as such, they’re not useful in real-time systems monitoring or incident response.
* B. Dashboards can be useful in systems monitoring; they can flag IT staff when events are occurring that may indicate systems loading issues or even failures of systems components. But they are not usually suitable for detecting security incidents.
* C. By summarizing systems status, such as which elements are healthy and which are nonresponsive, dashboards can be helpful in incident response decisions. But the details below the level of the dashboard are what ongoing monitoring depends on.
* ### D. By combining highly summarized key performance parameters with ongoing and recent event data, systems managers can see at a glance whether systems are behaving within expected limits, detect whether subsystems have failed (or are under attack), and drill down to get further data to inform incident response decision making.

## 4. Why are shadow IT systems or elements a concern to information security specialists? (Choose all that apply.)

* A. These are exploits and malware found on the dark Web and, as such, must be considered hostile to your organization’s goals and objectives. They should be banned from the business and its systems by policy.
* ### B. Most are written by well-intended users and may be widely used by people in the organization, but quite often they are not subjected to even the most basic software quality assurance measures and are outside of configuration management and control. Hence, they pose potential risks to the IT architecture.
* ### C. The more complex and dynamic these shadow systems become, the less confidence management should have in the reliability, integrity, and confidentiality of the results they produce.
* D. As long as common vulnerabilities have been addressed (for example, by blocking the use of unsigned macros in Microsoft Office), shadow IT components are no more likely to introduce risks than other IT systems.

## 5. Which of the following most correctly address whether penetration testing is suitable for use during systems security verification or is best suited to ongoing monitoring and assessment? (Choose all that apply.)

* ### A. Penetration testing is most revealing when performed against a baseline already in use for some time, because the risks of people becoming complacent and mitigation controls becoming out of date increase with time.
* ### B. Penetration testing is not useful during verification testing or systems assessment, because by its nature penetration testing is a somewhat covert attempt to simulate a hostile attack, whereas verification testing is a formalized, planned, and monitored activity.
* C. Penetration testing has a valid and valuable contribution to make at any point in the lifecycle of a system, from initial systems analysis throughout its deployed operational use.
* ### D. Penetration testing is normally used during postdeployment systems assessment and starts with current knowledge of how threat actors attempt to reconnoiter, surveil, select, and penetrate a target; verification starts with a functional security requirements baseline and confirms (via audit, test, or inspection) that each requirement in that baseline still functions properly. Both techniques complement each other during ongoing operational assessment.

## 6. CVE data and your own vulnerability assessments indicate that many of your end-user systems do not include recent security patches released by the software vendors. You decide to bring these systems up to date by applying these patches. This is an example of which of the following?


* ### A. Remediating or mitigating a risk
* B. Transferring a risk
* C. Avoiding a risk
* D. Accepting a risk

## 7. Which statement correctly describes the usefulness of CVE data as part of your risk mitigation planning?

* A. It should provide most, if not all, of the vulnerability information you need to implement risk mitigation.
* B. Since hackers use CVE data to aid in planning their attacks, this should be the first place you look for insight as you do emergency hardening of your IT systems. Once these obvious vulnerabilities have been mitigated, a more complete vulnerability assessment should be done.
* ### C. It’s a great source of information for known systems elements and known vulnerabilities associated with them, but it does nothing for vulnerabilities that haven’t been reported yet or for company-developed IT elements.
* D. Since the vast majority of systems in use are based on Windows, if your business does not use Windows platforms you can probably avoid the expense of investigating CVE for vulnerability information.

```
Option B does correctly state the risk that attackers may know more about your systems than you do if you haven’t thoroughly checked CVE data as part of your vulnerabilities assessment. But it incorrectly goes on to suggest that you fix those first—they may not relate to your organization’s highest-priority impacts as spelled out by the business impact analysis (BIA). Option A is therefore false. Option D is also false, since even the most Linux-based of organizations will probably have non-Linux systems elements (such as network components) that common vulnerabilities and exploits (CVE) could have information about.
```


## 8. What is the role of incident response and management in risk mitigation and risk management?


* ### A. Incident response and management are vital to risk mitigation; they provide the timely detection, notification, and intervention capabilities that contain the impact of a risk event and manage efforts to recover from it and restore operations to normal.
* B. Although it comes after the risk assessment and mitigation planning, implementation, and verification, incident response is not part of risk mitigation or risk management.
* C. Incident management is a part of risk mitigation but not part of risk management.
* D. Incident management is a part of risk management, but not of risk mitigation.

## 9. Which of the following might be legitimate ways to transfer a risk?

* ### A. Recognize that government agencies have the responsibility to contain, control, or prevent this risk, which your taxes pay them to do.
* ### B. Pay insurance premiums for a policy that provides for payment of claims and liabilities in the event the risk does occur.
* ### C. Shift the affected business processes to a service provider, along with contractually making sure they are responsible for controlling that risk or have countermeasures in place to address it.
* D. Change the underlying business process to use more secure software and hardware systems.

## 10. How do we perform ongoing monitoring of our IT systems to ensure that all risk mitigation controls and countermeasures are still protecting us? (Choose all that apply.)

* ### A. Periodically, gather up all of the event logs and monitoring log files, collate them, and see if potential events of interest are apparent.
* ### B. Routinely poll or ask users if abnormal systems behaviors have been noted.
* ### C. Review systems performance parameters, such as throughputs, systems loading levels, resource utilization, etc., to see if they meet with expectations.
* D. Review current postings in CVE and NVD systems to determine if the vulnerability assessment is still effective.

## 11. What does it mean to accept a risk?


* A. Accepting a risk is when management has reviewed and approved the vulnerability assessment prior to authorizing mitigation to proceed.
* ### B. Accepting a risk means that management knows and understands the probability of occurrence, the possible impacts, and the possible costs of mitigation but chooses nonetheless to not make any changes to business processes or systems. This approach is, in effect, self-insuring against the risk.
* C. Accepting a risk means that management has decided to get insurance coverage that will compensate for loss or damages if the risk event actually occurs.
* D. Accepting a risk means the same thing as ignoring it.

```
Option A confuses accepting a risk with accepting the assessment of all risks as an actionable basis on which to proceed with mitigation efforts. Option C confuses accepting with transferring a risk. Option D confuses accepting with ignoring a risk. Acceptance requires knowing, informed consent; ignoring a risk is simply choosing not to investigate, assess, characterize, or even think about the risk.
```


## 12. What is the role of threat modeling in performing a vulnerability assessment?


* A. Threat modeling involves creating models of systems, their vulnerabilities, and possible exploits, as well as modeling or simulating attacks to determine which vulnerabilities are in fact most severe. This drives mitigation planning.
* ### B. Threat modeling focuses attention on boundaries between systems elements and the outside world, and this may help you discover poorly secured VPN or maintenance features or tunnels installed by malware.
* C. Threat modeling can be used to validate that your risk mitigation controls and countermeasures have been successfully implemented, and so it comes after the vulnerability assessment.
* D. Threat modeling is a useful first step when planning penetration testing.


## 13. How should the SSCP assess the human elements in a system as part of vulnerability assessments? (Choose all that apply.)

* A. Since the human user is the weakest element in any IT security system, the vulnerability assessment should start by examining all manual data entry, manipulation, or process interaction steps for possible vulnerabilities.
* B. The organizational culture and context should determine whether senior leaders and managers create a climate of trust and empowerment or one of rigidly enforced controls and constraints. This sets the bounds within which the SSCP can examine manual interaction with and use of the IT systems for possible vulnerabilities.
* ### C. Every step in every process, whether performed by people or machines, is a potential vulnerability and should be assessed in accordance with the BIA’s established priorities.
* ### D. If the vulnerability assessment indicates that no amount of user training or administrative controls can reduce the risk of an incorrect human action to accessible levels, then further physical or logical controls, or a process redesign, may be needed.


## 14. Which of the following activities are not part of information risk mitigation?


* A. Implementing new systems features or capabilities to enhance product quality
* B. Incident management and investigation after a suspected information security breach
* C. Installing and testing new firewall, switch, and router systems and settings
* ### D. Developing an information classification policy and process

```
Improving product quality is a laudable goal but in and of itself it is not related to information systems security; thus Option A is incorrect. Option B refers to activities after an incident; mitigation activities happen before an incident occurs, or result from lessons learned because of the incident. Option C is most likely being done to implement new or revised security policies. Option D is part of information risk management and should precede information risk mitigation.
```


## 15. What important role does systems monitoring perform in support of incident management?

* A. They are not related—monitoring is a routine task that uses trend analysis and data analytics to determine if past systems behavior and use have been within expected bounds.
* ### B. The role is essential; by bringing together alert and alarm indicators from systems and their associated security controls and countermeasures, monitoring is the watchdog capability that activates incident response capabilities and plans.
* C. Incident response includes its own monitoring and alarms capabilities, so systems monitoring provides a good backup or alternate path to determining whether an incident is occurring.
* D. Ongoing, continuous monitoring is used to adjust or fine-tune alarm threshold settings so that false alarm rates can be better managed.


## 16. What are some of the reasons you might recommend that risks be avoided? (Choose all that apply.)

* ### A. It might cost more to mitigate or control a risk than the business stands to gain by operating with the risk in place.
* ### B. Replacing a vulnerable set of processes with ones that are less vulnerable can be more effective and less costly than attempting to redesign or repair the vulnerable steps or elements.
* C. In most cases, very few risks can be avoided; you really end up accepting them, ignoring them, or fixing things so that the risks are far less likely to occur or are less damaging if they do.
* D. Avoidance means that you’re refusing to face the facts and trying to ignore what experience is showing you. This is much like ignoring a risk, which makes sense only for risks that are truly beyond the ordinary.

```
Option C makes it seem that businesses are helpless to choose their goals, objectives, and where or how they will operate; this statement exaggerates. Option D confuses psychological avoidance behavior with an informed choice to step out of the way of a risk; it confuses ignoring with avoiding.
```

## 17. What roles do testing and verification play in information security? (Choose all that apply.)

* ### A. Provide continued confidence in the security of the information systems under test and verification
* ### B. Highlight the need for further risk mitigation, controls, and countermeasures
* ### C. Confirm that countermeasures and controls are still achieving the required degree of protection
* D. Verify that penetration testing subcontractors have satisfactorily fulfilled their contract with the business

## 18. How might you keep a gap from becoming a blind spot in your information security defenses? (Choose all that apply.)


* A. Transfer this risk to insurers or other parties.
* ### B. Ensure that systems elements around the gap provide sufficient detection and reporting capabilities so that an event of interest occurring in the gap cannot spread without being detected.
* C. Ensure that other systems elements can either detect or report when an event of interest is happening within the gap.
* D. You can’t, as by definition the gap is where you have no appreciable security coverage, and this includes having no monitoring or detection capabilities.

## 19. How do physical, logical, and administrative controls interact with one another?


* A. Usually, the only way these controls can interact is via postevent analysis.
* ### B. Administrative controls should direct and inform people; logical controls implement those directions in the IT architecture; physical controls reinforce by preventing or deterring disruptions to the hardware, systems, and support infrastructures themselves.
* C. After determining the physical security and asset protection needs and controls, the administrative and logical controls can be tailored to eliminate or reduce gaps in risk mitigation coverage.
* D. It may seem like these should harmonize well, but in practice, that rarely happens since administrators seldom appreciate what IT security needs actually entail.

```
Option A misunderstands that controls are chosen and then implemented, and proper mitigation planning seeks to have controls or countermeasures mutually reinforce each other. Option C misstates the mitigation planning task. Option D suggests that if “administrators” are network or systems administrators, then we hope they _do_ understand something about IT security; if they are not, they are probably not the ones who have to work to ensure these controls are part of an interlocking system of information security.
```

## 20. How should IT services such as PaaS, IaaS, and SaaS be evaluated as part of a security assessment?


* A. Since terms-of-service agreements cover your business’s use of these services, this transfers all of the information security risk to the cloud service provider and makes the security assessment a lot easier.
* B. PaaS security needs should be adequately covered by the platform services provider, whereas IaaS may or may not provide strong enough security measures to meet your needs and thus should be avoided if possible.
* ### C. The BIA and the architectural baselines should make clear what risks are transferred to the cloud services provider either in whole or in part, or where their services are assumed to be parts of the mitigation strategy. The security assessment should clearly identify this to as great a detail as it can, particularly for the risks identified in the BIA as of greatest concern.
* D. Penetration testing, with the consent of the cloud services provider, would be the most reliable way of assessing the security of these services.

```
Option A seems to blindly assume that a contractual transfer of responsibility was necessary, sufficient, and agreed to, and this is normally not the case. Option B is false; platforms and infrastructures still require substantial effort by users (and their IT security team) to establish policies, implement them in controls, and monitor their ongoing correct operation. Option D seems to ignore BIA-driven risk assessment and is inherently misleading.
```

