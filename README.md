# Botium Toys Internal Security Audit

# Table of contents

1. [Introduction](#introduction)
2. [Scenario](#scenario)
3. [Internal Security Audit Workflow](#workflow)
4. [Controls Assessment](#control-assessment)
5. [Compliance Checklist](#compliance-checklist)
6. [Stakeholder Memorandum](#stakeholder-memo)
7. [Conclusion](#conclusion)

-------

# Introduction <a name="introduction">

An internal security audit assessment done on Botium Toys, a fictitious toy company, completed as part of my cybersecurity portfolio and as part of Google's <a href='https://www.coursera.org/google-certificates/cybersecurity-certificate'>Cybersecurity Professional Certificate</a> on Coursera in the  <a href='https://www.coursera.org/learn/manage-security-risks?specialization=cybersecurity-certificate'> Play It Safe: Manage Security Risks </a> Course .
   
The goal of an audit can be to achieve compliance, to identify weaknesses or vulnerabilities within an
organization, and/or to understand failures in processes and procedures and correct
them. In this scenario, the IT manager set the goals. He is expecting a report of the
current security posture of the organization and recommendations for improving the
security posture of the organization, as well as justification to hire additional
cybersecurity personnel.

# Scenario  <a name="scenario">
This scenario is based on a fictional company:

Botium Toys is a small U.S. business that develops and sells toys. The business has a single physical location. However, its online presence has grown, attracting customers in the U.S. and abroad. Their information technology (IT) department is under increasing pressure to support their online market worldwide. 

The manager of the IT department has decided that an internal IT audit needs to be conducted. She expresses concerns about not having a solidified plan of action to ensure business continuity and compliance, as the business grows. She believes an internal audit can help better secure the company’s infrastructure and help them identify and mitigate potential risks, threats, or vulnerabilities to critical assets. The manager is also interested in ensuring that they comply with regulations related to accepting online payments and conducting business in the European Union (E.U.).   

The IT manager starts by implementing the National Institute of Standards and Technology Cybersecurity Framework (NIST CSF), establishing an audit scope and goals, and completing a risk assessment. The goal of the audit is to provide an overview of the risks the company might experience due to the current state of their security posture. The IT manager wants to use the audit findings as evidence to obtain approval to expand his department. 

The task is to review the IT manager's scope, goals, and risk assessment. Then, perform an internal audit to complete a controls assessment and compliance checklist. 
 
------------------------


The goals for Botium Toys’ internal IT audit are:
- To adhere to the National Institute of Standards and Technology Cybersecurity
Framework (NIST CSF)
- Establish a better process for their systems to ensure they are compliant
- Fortify system controls
- Implement the concept of least permissions when it comes to user credential
management
- Establish their policies and procedures, which includes their playbooks
- Ensure they are meeting compliance requirements

   
## Internal Security Audit Workflow  <a name="workflow">
The internal security audit can be broken down into two parts each with their own steps to follow.

### Part 1 (The Audit Planning Process)

1. Establish scope and goals of the audit.
2. Conducting a risk assessment of the Organizations assets
   
### Part 2 (Conduct The Audit)

1. Complete a Controls assessment
   - Select controls needing to be implemented.
   - Prioritize selected controls
2. Assess Compliance checklist
   - Explain why selected compliance regulations and standards need to be adhered to.
   - Review results
   - make note of findings
3. Communicate results to Stakeholders
   - Summarize recommendations to communicate properly 


Controls Assessment  <a name="control-assessment">
===================


Current Assets 
--------------

Assets managed by the IT Department include:

- On-premises equipment for in-office business needs 

- Employee equipment: end-user devices (desktops/laptops, smartphones), remote workstations, headsets, cables, keyboards, mice, docking stations, surveillance cameras, etc.

- Management of systems, software, and services: accounting, telecommunication, database, security, ecommerce, and inventory management

- Internet access

- Internal network

- Vendor access management

- Data center hosting services 

- Data retention and storage

- Badge readers

- Legacy system maintenance: end-of-life systems that require human monitoring

### Administrative Controls 
| Control Name | Control type and explanation | Needs to be implemented (X) | Priority |
| --- | --- | --- | --- |
| Least Privilege | Preventative; reduces risk by making sure vendors and non-authorized staff only have access to the assets/data they need to do their jobs | X | High |
| Disaster recovery plans | Corrective; business continuity to ensure systems are able to run in the event of an incident/there is limited to no loss of productivity downtime/impact to system components, including: computer room environment (air conditioning, power supply, etc.); hardware (servers, employee equipment); connectivity (internal network, wireless); applications (email, electronic data); data and restoration | X | High |
| Password policies | Preventative; establish password strength rules to improve security/reduce likelihood of account compromise through brute force or dictionary attack techniques | X | High |
| Access control policies | Preventative; increase confidentiality and integrity of data | X | High |
| Account management policies | Preventative; reduce attack surface and limit overall impact from disgruntled/former employees | X | High/Medium |
| Separation of duties | Preventative; ensure no one has so much access that they can abuse the system for personal gain | X | High |

### Technical Controls 
| Control Name | Control type and explanation | Needs to be implemented (X) | Priority |
| --- | --- | --- | --- |
| Firewall | Preventative; firewalls ***are already in place*** to filter unwanted/malicious traffic from entering internal network | NA | NA |
| Intrusion Detection System (IDS) | Detective; allows IT team to identify possible intrusions (e.g., anomalous traffic) quickly | X | High |
| Encryption | Deterrent; makes confidential information/data more secure (e.g., website payment transactions) | X | High/Medium |
| Backups | Corrective; supports ongoing productivity in the case of an event; aligns to the disaster recovery plan | X | High |
| Password management system | Corrective; password recovery, reset, lock out notifications | X | High/Medium |
| Antivirus (AV) software | Corrective; detect and quarantine known threats | X | High |
| Manual monitoring, maintenance, and intervention | Preventative/corrective; required for legacy systems to identify and mitigate potential threats, risks, and vulnerabilities | X | High |


### Physical Controls
| Control Name | Control type and explanation | Needs to be implemented (X) | Priority |
| --- | --- | --- | --- |
| Time-controlled safe | Deterrent; reduce attack surface/impact of physical threats | X | Medium/Low |
| Adequate lighting | Deterrent; limit “hiding” places to deter threats | X | Medium/Low |
| Closed-circuit television (CCTV) surveillance | Preventative/detective; can reduce risk of certain events; can be used after event for investigation | X | High/Medium |
| Locking cabinets (for network gear) | Preventative; increase integrity by preventing unauthorized personnel/individuals from physically accessing/modifying network infrastructure gear | X | Medium |
| Signage indicating alarm service provider | Deterrent; makes the likelihood of a successful attack seem low | X | Low |
| Locks | Preventative; physical and digital assets are more secure | X | High |
| Fire detection and prevention (fire alarm, sprinkler system, etc.) | Detective/Preventative; detect fire in the toy store’s physical location to prevent damage to inventory, servers, etc. | X | Medium/Low |

Compliance Checklist
====================

To review compliance regulations and standards, read the [controls, frameworks, and compliance](https://www.coursera.org/learn/foundations-of-cybersecurity/supplement/xu4pr/controls-frameworks-and-compliance) document.
   
Botium Toys will need to adhere to the following standards for the reasons listed:
     
-   General Data Protection Regulation (GDPR)
         - GDPR is a European Union (E.U.) general data regulation that protects the processing of E.U. citizens’ data and their right to privacy in and out of E.U. territory. Additionally, if a 
           breach occurs and a E.U. citizen’s data is compromised, they must be informed within 72 hours of the incident.
    
         - With the increase of Botium Toys online presence and increasing sales expanding overseas. Keeping this market segments right to privacy in place is vital. Handling E.U. citizens Pii and 
           Sii data differently to be compliant.
   

-   Payment Card Industry Data Security Standard (PCI DSS)

         - PCI DSS is an international security standard meant to ensure that organizations storing, accepting, processing, and transmitting credit card information do so in a secure environment. 

         - Botium Toys must adhere to PCI DSS, primarily based on where they conduct business and how they accept payments. The majority of their business is done online, and the majority of their 
           payments are done through Merchant Services and Payment Processing. PCI DSS provides best practices to stay in compliance with regulation in order to avoid fines and penalties. 


-   System and Organizations Controls (SOC type 1, SOC type 2)
   - The SOC1 and SOC2 are a series of reports that focus on an organization's user access policies at different organizational levels. They are used to assess an organization's financial compliance and levels of risk. They also cover confidentiality, privacy, integrity, availability, security, and overall data safety. Control failures in these areas can lead to fraud.

      - Botium Toys needs to establish and maintain appropriate user access for internal and external (third-party vendor) personnel to mitigate risk and ensure data safey.
      - Both of these standards evaluate the effectiveness of a company's internal controls. While SOC1 I focused on financial reporting controls, SOC2 is concerned with information security controls, including customer data safety. 
----------------
   

# Stakeholder memorandum <a name="stakeholder-memo">

TO: Stakeholders
CC: IT Manager

FROM: Michael Garcia\
DATE: 08/21/2023\
SUBJECT: Internal Security Audit Findings and Recommendations

Dear Colleagues,

Please review the following information regarding the Botium Toys internal audit scope, goals, critical findings, summary and recommendations.

**Scope:**

- The following systems are in scope: accounting, end point detection, firewalls, intrusion detection system, security information and event management (SIEM) tool. The systems will be evaluated for:

  - Current user permissions

  - Current implemented controls

  - Current procedures and protocols

- Ensuring current user permissions, controls, procedures, and protocols in place align with GDPR, PCI DSS, compliance requirements

- Ensure current technology and assets are accounted for both hardware and system access.

**Goals:**

- Adhere to the NIST CSF.

- Establish a better process for their systems to ensure they are compliant

- Fortify system controls

- Implement the concept of least permissions when it comes to user credential management

- Establish their policies and procedures, which includes their playbooks

**Critical findings** (must be addressed immediately):

 Multiple controls need to be developed and implemented to meet the audit goals, including:

- Principle of Least Privilege and Separation of duties

- Disaster recovery plans

- Password, Access control, and Account management policies

- Intrusion Detection System (IDS)

- Encryption (secure website transactions wand disk drive(s) containing sensitive information)

- Backups

- Implementation of a Password management system

- Antivirus (AV) software

- Manual monitoring, maintenance, and intervention for legacy systems

- Closed-circuit television (CCTV) surveillance

- Locks

- Locking cabinets (for network gear)

- Fire detection and prevention (fire alarm, sprinkler system, etc.)

- Policies need to be developed and implemented for the following:

  - To meet PCI DSS and GDPR compliance requirements.

  - To meet SOC1 and SOC2 guidance related to user access policies and overall data safety.

**Findings** (should be addressed, but no immediate need):

The following physical controls should be considered in the future once the critical findings have been resolved:

- Time-controlled safe

- Adequate lighting

- Signage indicating alarm service provider for restricted areas

**Summary/Recommendations:**

It is recommended that the critical findings relating to compliance with PCI and GDPR be promptly addressed as Botium Toys accepts online payments is expanding to offer services and handle the data of customers abroad including the European Union. SOC1 and SOC2 guidance related to user access policies should be used to align to the audit goal to adapt to the concept of least permissions to develop the policies and procedures needed to be compliant.

Disaster recovery plans and backups are recommended as they will support business continuity in the event of an incident occuring ranging from a physical disaster such as a fire, or worse case scenario of a cyber attack or technical issue impacting business productivity  as a part of a data and system resilience strategy. A method of fire detection and prevention systems is worth consideration for protecting against physical attacks.

Integrating an IDS and AV software into current systems will give the ability to assist with intrusion detection and spot and mitigate potential risks while taking into account the existing legacy systems that need manual monitoring and intervention. 

To secure assets at Botium Toys' phyiscal location, locks and CCTV should be used to secure physical assets and to monitor for potential threats. Having a time-controlled safe, adequate lighting, and signage indicating alarm service provider will further improve Botium Toys' security posture.
   
# Conclusion  <a name="conclusion">
 This concludes my mock security audit writeup, I hope you found it useful and enlightening as I have. If there is any constructive feedback or  suggestions to improve and include, just let me know. 

**Self-Evaluation**: I did mostly well in determining what controls are top priority and need implementation immediately in reducing risk and why Botium Toys would need to comply to the regulations and standards I initially picked on my first try. I really loved the challenge of this assignment and tested what I have learned in my studies and hands-on learning. 

**Lessons learned**: 
   
   The part I struggled with mostly was using much details in my findings in the stakeholder's memorandum. I learned and spent alot of time on this to be more concisely and to the point. I learned to use a list, have my writing proofread and ensure I didnt repeat anything and to filter out information.
   
   I also some trouble initially in explaining how the System and Organizations Controls standard relates to organizational user access policies, confidentiality, privacy, integrity, availability, security, and overall data safety and levels of risks, not just financial compliance while conducting the audit.
