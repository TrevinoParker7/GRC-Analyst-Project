# Corporate Cybersecurity Assessment utilizing NIST CyberSecurity Framework (CSF) 2.0

## Introduction

For this project I was tasked with analyzing an Organization's ('Oscorp') cybersecurity status and designing a comprehensive cybersecurity program utilizing the [NIST CSF 2.0](https://www.nist.gov/publications/nist-cybersecurity-framework-csf-20) to uplift its security posture. I was given a 'current status' report, much like one that would be compiled after initial investigations and interviews with employees and stakeholders. Using the NIST CSF, I conducted a pass/fail assesment and presented recommendations for improvement. I decided to start with a short presentation to stakeholders to explain the framework and roadmap and ended with presenting them with a comprehensive list of recomendations and procedures to be implemented.

![horizon_labs2](https://github.com/user-attachments/assets/6e1c3012-8e1f-4351-8bcc-3889bf7498a3)


## CSF Core Functions
The CSF Core Functions — GOVERN, IDENTIFY, PROTECT, DETECT, RESPOND, and RECOVER — organize cybersecurity outcomes at their highest level.

| Core Functions  | Description
| --------------- | -----
| ![Screenshot 2024-10-28 134244](https://github.com/user-attachments/assets/c536c78f-b8d2-4988-a1ad-ea1b0222bd41) | The organization’s cybersecurity risk management strategy, expectations, and policy are established, communicated, and monitored.
| ![Screenshot 2024-10-28 134430](https://github.com/user-attachments/assets/bd218bc5-9048-4d91-96fd-77aba367d87b) | The organization’s current cybersecurity risks are understood.
| ![Screenshot 2024-10-28 134438](https://github.com/user-attachments/assets/f6554061-0d01-49e9-91df-b102eb4b8ac7) | Safeguards to manage the organization’s cybersecurity risks are used.
| ![Screenshot 2024-10-28 134447](https://github.com/user-attachments/assets/26e591c9-9ee6-454f-9f5b-37062bec1d0c) | Possible cybersecurity attacks and compromises are found and analyzed.
| ![Screenshot 2024-10-28 134456](https://github.com/user-attachments/assets/bfdf2e21-ced1-4767-8ac6-4ec982b6f5e3) | Actions regarding a detected cybersecurity incident are taken.
| ![Screenshot 2024-10-28 134503](https://github.com/user-attachments/assets/10ef5d64-da8b-41df-a0fe-56acb244fd1c) | Assets and operations affected by a cybersecurity incident are restored.

------
<!-- GOVERN -->
![Screenshot 2024-10-28 135023](https://github.com/user-attachments/assets/a9b93ba7-a2a2-4cdc-954f-8016f3df6e58)

The rigor of an organization’s cybersecurity risk governance and management practices can be categorized according to a table of tiers as outlined in CSF 2.0 Profiles and Tiers. (See Fig. 1)

![image](https://github.com/user-attachments/assets/60704a33-4b7f-4925-8eef-4084d5fa484c)

A Current Profile specifies the Core outcomes that an organization is currently achieving (or attempting to achieve) and characterizes how or to what extent each outcome is being achieved. 

**Oscorp’s current profile is identified as Tier 1: Partial.**
|Tier           | Cybersecurity Risk Governance      | Cybersecurity Risk Management
|---------------|------------------------------------|------------------------------
|Tier 1: Partial | Application of the organizational cybersecurity risk strategy is managed in an ad hoc manner. Prioritization is ad hoc and not formally based on objectives or threat environment. | There is limited awareness of cybersecurity risks at the organizational level. The organization implements cybersecurity risk management on an irregular, case-by-case basis. The organization may not have processes that enable cybersecurity information to be shared within the organization. The organization is generally unaware of the cybersecurity risks associated with its suppliers and the products and services it acquires and uses. 
 
A Target Profile specifies the desired outcomes that an organization has selected and prioritized for achieving its cybersecurity risk management objectives. It considers anticipated changes to the organization’s cybersecurity posture, such as new requirements, new technology adoption, and threat intelligence trends. 

**Target profile for Oscorp: Tier 4:**

|Tier           | Cybersecurity Risk Governance                                                    | Cybersecurity Risk Management
|---------------|----------------------------------------------------------------------------------|------------------------------
|Tier 4: Adaptive | There is an organization-wide approach to managing cybersecurity risks that uses risk-informed policies, processes, and procedures to address potential cybersecurity events. The relationship between cybersecurity risks and organizational objectives is clearly understood and considered when making decisions. Executives monitor cybersecurity risks in the same context as financial and other organizational risks. The organizational budget is based on an understanding of the current and predicted risk environment and risk tolerance. Business units implement executive vision and analyze system-level risks in the context of the organizational risk tolerances. Cybersecurity risk management is part of the organizational culture. It evolves from an awareness of previous activities and continuous awareness of activities on organizational systems and networks. The organization can quickly and efficiently account for changes to business/mission objectives in how risk is approached and communicated. | The organization adapts its cybersecurity practices based on previous and current cybersecurity activities, including lessons learned and predictive indicators. Through a process of continuous improvement that incorporates advanced cybersecurity technologies and practices, the organization actively adapts to a changing technological landscape and responds in a timely and effective manner to evolving, sophisticated threats. The organization uses real-time or near real-time information to understand and consistently act upon the cybersecurity risks associated with its suppliers and the products and services it acquires and uses. Cybersecurity information is constantly shared throughout the organization and with authorized third parties.

At all times the question should be asked whether data is kept *Confidential*, its *Integrity* is upheld, and is readily *Available* and what risks and vulnerabilities present a danger to this ‘[CIA Triad](https://www.nccoe.nist.gov/publication/1800-26/VolA/index.html)’. 

![image](https://github.com/user-attachments/assets/5b8e35de-2c04-4de8-a82c-bb526a3f6f5c)
------
<details close> 
<summary> <h3> Oscorp's Current status report (Click here)</h3> </summary>

**Current Oscorp cybersecurity team:**
- Cyber security analyst: generalist, responds to cyber incidents as they come. Reports
to Oscorp’s IT manager.
- Network engineer: manages the firewalls. Reports to the Network Team Leader.
- Cyber Security Consultant: your new role at Oscorp. You will initially report to the IT
manager.

**Oscorp Current Cyber Security Controls:**
- Organisational governance:
  - CEO has a clear business strategy for the business. However, roles and
responsibilities for cybersecurity haven’t been defined. They’re assigned to
the IT team. There is no cybersecurity strategy.

- Asset Management:
  - The IT team has a spreadsheet with serial numbers of laptops.
  - The spreadsheet includes the model of each machine and details about the
warranty.
  - Oscorp uses Microsoft Office365 and relies exclusively on Software-as-a-
Service applications.
  - All data is in Microsoft Azure cloud
  - The IT team uses a Secure Operating Environment (SOE) to image all their
laptops with the latest Windows desktop version

- Business Continuity and Disaster Recovery:
  - The IT team conducts regular disaster recovery testing
  - The IT team has clear and documented business continuity plans
  - The IT team takes regular backups. Backups get tested periodically

- Vulnerability management:
  - Oscorp have purchased Qualys vulnerability scanner.
  - The IT team uses Qualys on an ad-hoc basis.
  - There is no formal vulnerability management program in place.
  - Large number of high and severe vulnerabilities reported by Qualys

- Risk management:
  - Oscorp has a risk team that performs financial risk activities.
  - There is no technology or cyber risk process at Oscorp.

- Third Party Risk Management:
  - Oscorp doesn’t perform any third-party risk management.
  - Contracts are reviewed by procurement and finance, not IT.

- Identity and Access Management:
  - Oscorp uses Microsoft Active Directory to manage users and groups
  - There is no privileged access management solution in place
  - Admin account password is shared with a few senior members of the IT team
  - Access to resources is granted upon request
  - The organisation does not use two-factor authentication for login
  - Complex login passwords are used
  - Employees use a VPN solution to login remotely when required

- Network security:
  - The organisation has Palo Alto Next Gen firewalls.
  - The firewalls have been configured by the network
  - The firewalls get audited every year by the network team
  - The firewalls get regular updates
  - The IT team have up to date network diagrams. The diagrams include the
cloud environment.
  - The network is segmented using VLANs.

- Physical Security:
  - Oscorp is a highly secure facility, with state-of-the-art CCTV cameras
everywhere
  - Oscorp takes physical very seriously
  - They do extensive vettng for all their employees
  - The have a 24/7 monitoring for their research labs and physical facilities

- Data Security:
  - Oscorp doesn’t have a DLP soluDon
  - All data resides in Microsoft Azure cloud and Microsoft Office 365
  - Key critical application is a SaaS service from Horizon Labs.

- Policy:
  - There is one generic IT policy in place
  - No formal information security policy
  - There is no data governance policies or information classificaDon

- Cyber Security detection and response:
  - There is no detection or response capability
  - The IT team responds to alerts from the anti-virus (Microsoft Defender)
  - No SIEM in place

- Security Education and Awareness:
  - All employees are required to do an induction web training module. The
module includes basic instructions about cyber security.

  </details>
------

Utilizing CSF Core functions as a guide, an assessment of Oscorp identified many deficiencies. Recommendations will be provided after each subcategory. 

<!--IDENTIFY-->
![Screenshot 2024-10-28 134831](https://github.com/user-attachments/assets/9dc5bda1-08f0-4d90-b806-34621a19553a)

<details close> 
<summary> <h3> Nist Cybersecurity Framework 2.0 Pass/Fail logs (Click here)</h3> </summary>

![Screenshot 2024-10-27 205100](https://github.com/user-attachments/assets/586dd539-f042-4bea-b9d2-290b8e445571)

![Screenshot 2024-10-27 205255](https://github.com/user-attachments/assets/c0c4e42a-7736-48b1-ac59-92604fef17ca)

  </details>

### Asset Management:
-	*Physical devices and systems within the organization ARE properly inventoried, HOWEVER no IP address identified.* No access agents identified. This prohibits a vulnerability scanner from authenticating and accessing the device and limits the scope of the scanner.
-	*External information systems are NOT properly catalogued.* Although third-party contracts are being tracked, there is no third-party risk management or IT involvement.
-	*Resources (e.g., hardware, devices, data and software) are NOT prioritized based on their classification, criticality and business value.* There is no asset classification process based in sensitivity and criticality.
-	*Cybersecurity roles and responsibilities for the entire workforce and third-party stakeholders (e.g., suppliers, customers, partners) are NOT established.*

A vulnerability management policy needs to be implemented. Vulnerabilities need to be classified and prioritized. It is recommended an access agent is installed on all permanent and non-permanent network connected devices in order to authenticate the scan. Utilizing an access agent in conjunction with a vulnerability scanner will greatly improve the scope of the scans. 
Third-party risk management policy needs to be implemented and IT department needs third-party service provider involvement.
Assets need to be labeled with a sensitivity or criticality classification determined by the Maximum Tolerable Outage matrix. See figure below for example.

![image](https://github.com/user-attachments/assets/0fd3f160-1f11-4da1-a781-d0837b1115c7)

`(RPO=recovery point objective, RTO=recovery time objective, WRT=working recovery time)`

Cybersecurity roles and responsibilities for the entire workforce and third-party stakeholders (e.g., suppliers, customers, partners) need to be established and implemented.

### Business Environment:
-	*The organization’s role in the supply chain is NOT identified and communicated.*

The organization needs clear documentation outlining their role within their own supply chain when it comes to cyber security. Mapping of third-party suppliers, classifying suppliers based on criticality and sensitivity. 

### Governance:
-	*Organizational information security policy is NOT established.*
-	*Information security roles and responsibilities are NOT coordinated and aligned with internal roles and external partners.* No security roles and policies have been documented and communicated.
-	*Legal and regulatory requirements regarding cybersecurity, including privacy and civil liberties obligations, are NOT understood and managed.* No legal and regulatory responsibilities have been documented.
-	*Governance and risk management processes DO NOT address cybersecurity risk.* There is no process or oversight implemented to manage cyber security risk.

A formal Cyber and Information Security policy needs to be established.
Information security, legal and regulatory roles and responsibilities need to be outlined, documented and communicated with internal and external stakeholders.
A comprehensive set of processes and procedures to manage cyber security risks need to be established with direct board member oversight of security issues.

### Risk Assessment and Risk Management Strategy:
-	*Asset vulnerabilities are NOT identified and documented.* Scans are merely conducted ad-hoc without regularity. No established procedures for analysis and documentation.
-	*Threat and vulnerability information is NOT received from information sharing forums and sources.*
-	*Threats, both internal and external, are NOT identified and documented.*
-	*Potential business impacts and likelihoods are NOT identified.*
-	*Threats, vulnerabilities, likelihoods and impacts are NOT used to determine risk.*
-	*Risk responses are NOT identified and prioritized.*
-	*Risk management processes are NOT established, managed and agreed to by organizational stakeholders.*
-	*Organizational risk tolerance is undetermined and NOT clearly expressed.*

A full-scale Cyber Security Risk Management policy needs to be implemented utilizing the **[OWASP](https://owasp.org/)** (Open Worldwide Application Security Project) secure design principles. Use of [NIST 800-53](https://csrc.nist.gov/pubs/sp/800/53/r5/upd1/final) implemented to test and verify the policy. Complete a document that outlines strategies for managing potential risks that could impact the organization. Utilizing a **Risk Matrix** to establish risk tolerance and priority. Tangible and non-tangible asset identification and categorization. 

![Screenshot 2024-09-06 155149](https://github.com/user-attachments/assets/88309da8-792e-4e3d-a6ed-d7c293cfc655)

------
<!--## PROTECT-->
![Screenshot 2024-10-28 134843](https://github.com/user-attachments/assets/eaa0f70b-acb1-43ba-9186-53f4c406875c)

<details close> 
<summary> <h3> Nist Cybersecurity Framework 2.0 Pass/Fail logs (Click here)</h3> </summary>

![Screenshot 2024-10-28 141833](https://github.com/user-attachments/assets/83ff0872-74e1-4969-a1f2-29a639abb176)

![Screenshot 2024-10-28 142000](https://github.com/user-attachments/assets/f36bc530-31e3-4425-a67d-2a70586aa605)

![Screenshot 2024-10-28 142028](https://github.com/user-attachments/assets/cac40a40-e19a-464c-a819-e8f1651e5231)


  </details>
  
### Access Controls:

-	*Identities and credentials are NOT adequately managed for authorized devices and users.* No use of Multi-Factor Authentication. No specified off-boarding procedures. No periodic access reviews established.
-	*Physical access to assets is NOT managed and protected.* No verified entry/exit logs. No biometrics implemented. No access management policy in place.
-	*Remote access is NOT adequately managed.* No Two-Factor Authentication for VPN. 
-	*Access permissions are NOT managed, incorporating the principles of least privilege and separation of duties.* No Access management policy in place. Least privilege and Separation of Duties implementation inadequate.

Identity and Access Management (IAM) policy needs to be established and implemented to determine access to resources and assets based on identity verification, validation, authentication and authorization of the subject (user, group, device, etc.) for a specific period of time.
Policy should cover Multi-Factor Authentication (MFA), Access control lists (ACL), Roll-based access control, On- and Off-boarding procedures, Remote access directives to include 2FA.

### Awareness Training:
-	*All users are NOT informed and trained.* No regular training. Insufficient onboarding training. No Third-Party Training protocol established. 
-	*Privileged users DO NOT understand roles and responsibilities.* No Privileged access management in place.
-	*Third-party stakeholders (e.g., suppliers, customers, partners) DO NOT understand roles and responsibilities.* No Third-Party Training protocol or Risk Management established.
-	*Senior executives DO NOT understand roles and responsibilities.* No dedicated executive security and board member awareness training established.
-	*Physical and information security personnel DO NOT understand roles and responsibilities.* No roles or responsibilities established.

Training and Education program needs established and implemented. Program needs to be ran periodically and kept up to date. Effectiveness needs to be verified. Training should be extended to Third-Party providers through the TPRM. Cyber Security roles and responsibilities need established and implemented. Establish dedicated training for executives and board members.

### Data Security:
-	*Data-at-rest is NOT adequately protected.* Although data is kept by Azure, the organization has not classified or labeled any data. No DLP strategy is implemented. 
-	*Data-in-transit is NOT adequately protected.* No USB data transfer limitations are established.
-	*Assets are NOT formally managed throughout removal, transfers and disposition.* No policies regarding asset offboarding or data disposal implemented.
-	*No protections against data leaks are implemented.* No DLP strategy implemented

A Data Loss Prevention method needs to be configured. Data needs to be classified and labeled for it to be effective. Movement and exfiltration of data (USB downloads) need to be monitored. Asset and data disposal policies need to be implemented.

### Information Protection Processes and Procedures:
-	*No configuration change control processes are in place.* No change management or documented policies in place.
-	*Policy and regulations regarding the physical operating environment for organizational assets are NOT met.* Physical protection protocols are in place, yet no policies are defined.
-	*Data is NOT destroyed according to policy.* No data disposal policy in place. 
-	*Effectiveness of protection technologies is NOT shared with appropriate parties.*
-	*Inadequate Cybersecurity in human resources practices. (e.g., deprovisioning, personnel screening).* No offboarding procedures in place.
-	*NO vulnerability management plan is developed or implemented.* No effective or formally managed Vulnerability Management program implemented.

Configuration change protocols need to be implemented and documented. Physical security policies need to be defined. Data disposal policy needs implemented. Data protection information sharing should be considered. Personnel offboarding procedures and policy needs implemented. Although vulnerability scans are occasionally performed, a formal and effective program and policy needs to be implemented.

### Protective Technology:
-	*Audit/log records are NOT determined, documented, implemented or reviewed in accordance with policy.* No event or log management is performed. No SIEM in place.
-	*Removable media is NOT protected and its use restricted according to policy.* No data exfiltration policy in place.
-	*Communications and control networks are NOT adequately protected.* Network traffic is not monitored adequately.

A Security Information and Event Management (SIEM) needs to be implemented and aligned with industry standard framework [MITRE ATT&CK](https://attack.mitre.org/). Policy needs to be established and personnel appointed for monitoring. 

------
<!--## DETECT-->
![Screenshot 2024-10-28 134853](https://github.com/user-attachments/assets/2a5d2bd2-ba9b-4cff-84c2-840f73c4633b)

<details close> 
<summary> <h3> Nist Cybersecurity Framework 2.0 Pass/Fail logs (Click here)</h3> </summary>

![Screenshot 2024-10-28 142453](https://github.com/user-attachments/assets/e8f4d360-6015-451c-8484-3fc6b868b63b)

![Screenshot 2024-10-28 142508](https://github.com/user-attachments/assets/7fc2cbd1-0dcd-4818-8413-c17ef30d0716)


  </details>

  
### Anomalies and Events:

Implement a SIEM to capture and monitor network traffic. Monitor logs and events, analyze threats, classify low/medium/high impact events based on criticality and establish escalation points.

### Security Continuous Monitoring:

Implement a SIEM to capture and monitor network traffic. Merely monitoring traffic and alerts through Microsoft Defender is critically inadequate. Scope of monitoring needs to be defined. Implement detection and response procedures and capabilities. Implement proper Third-Party Risk Management Policy. Implement a formal Vulnerability Management Policy and run scan periodically according to policy.

### Detection Processes:

Detection and response capabilities need to be established. Roles and responsibilities need to be defined and implemented. Separation of duties between IT department and Cyber security department need to be considered. Use periodic Penetration Test to verify robustness of security posture.

------
<!-- RESPOND-->
![Screenshot 2024-10-28 134902](https://github.com/user-attachments/assets/0e5fa430-0cea-4d22-be43-912381a82917)

<details close> 
<summary> <h3> Nist Cybersecurity Framework 2.0 Pass/Fail logs (Click here)</h3> </summary>


![Screenshot 2024-10-28 142705](https://github.com/user-attachments/assets/ef22e6a8-8635-47a4-abfc-80181246c01c)


  </details>


### Response Planning:

A Cybersecurity response process and policy needs to be established. 

### Communications:

Incident response activities need to be determined and communicated with internal and external stakeholders. Include all contact details and establish thresholds and escalation points. Communicate with proper authorities when necessary and share findings with industry peers

### Analysis:

Ensure analysis is conducted to determine adequate response and support recovery activities. Document criticality of incidents. Consider the ability for forensic investigations when needs. 

### Mitigation:

- Ensure Incident response plans follow a standard that ensure that incidents are contained and mitigated (SANS incident response plans).
- Establish Vulnerability Management Program to aid in identifying and categorizing new, known and unknown vulnerabilities.
- Establish a process for dealing with ‘Zero-day’ vulnerabilities.

### Improvements: 

Analyze, test and update incident response plans continuously. 

------
<!--## RECOVER-->
![Screenshot 2024-10-28 134912](https://github.com/user-attachments/assets/b595cac7-1881-4388-b3ac-4e5f59a099fc)

<details close> 
<summary> <h3> Nist Cybersecurity Framework 2.0 Pass/Fail logs (Click here)</h3> </summary>


![Screenshot 2024-10-28 142747](https://github.com/user-attachments/assets/92ba5adc-b78e-447e-bba8-c2d2103bdefc)



  </details>

### Communications:

Coordinate restoration activities with internal and external parties, such as coordinating centers, Internet Service Providers, owners of attacking systems, victims, other CSIRTs and vendors. Consider need for reputational damage mitigation policy.

------

## Conclusion

After investigating Oscorp's security posture, I analysed the findings and overlayed them with the NIST CSF 2.0. I utilized relevant security frameworks like MITRE ATT@CK, NIST 800-53, OWASP and others to compile a comprehensive roadmap towards a secure security infrastructure. 


