# NIST CSF

This is a markdown friendly summary of the important parts of the [NIST CSF](https://www.nist.gov/cyberframework).

## Framework Core

### 🟦 Identify

Develop an organizational understanding to manage cybersecurity risk to systems, people, assets, data, and capabilities.

- **Asset Management (ID.AM)**: The data, personnel, devices, systems, and facilities that enable the organization to achieve business purposes are identified and managed consistent with their relative importance to organizational objectives and the organization’s risk strategy.
  - **ID.AM-1**: Physical devices and systems within the organization are inventoried
  - **ID.AM-2**: Software platforms and applications within the organization are inventoried
  - **ID.AM-3**: Organizational communication and data flows are mapped
  - **ID.AM-4**: External information systems are catalogued
  - **ID.AM-5**: Resources (e.g., hardware, devices, data, time, personnel, and software) are prioritized based on their classification, criticality, and business value
  - **ID.AM-6**: Cybersecurity roles and responsibilities for the entire workforce and third-party stakeholders (e.g., suppliers, customers, partners) are established
- **Business Environment (ID.BE)**: The organization’s mission, objectives, stakeholders, and activities are understood and prioritized; this information is used to inform cybersecurity roles, responsibilities, and risk management decisions.
  - **ID.BE-1**: The organization’s role in the supply chain is identified and communicated
  - **ID.BE-2**: The organization’s place in critical infrastructure and its industry sector is identified and communicated
  - **ID.BE-3**: Priorities for organizational mission, objectives, and activities are established and communicated
  - **ID.BE-4**: Dependencies and critical functions for delivery of critical services are established
  - **ID.BE-5**: Resilience requirements to support delivery of critical services are established for all operating states (e.g. under duress/attack, during recovery, normal operations)

- **Governance (ID.GV)**: The policies, procedures, and processes to manage and monitor the organization’s regulatory, legal, risk, environmental, and operational requirements are understood and inform the management of cybersecurity risk.
  - **ID.GV-1**: Organizational cybersecurity policy is established and communicated
  - **ID.GV-2**: Cybersecurity roles and responsibilities are coordinated and aligned with internal roles and external partners
  - **ID.GV-3**: Legal and regulatory requirements regarding cybersecurity, including privacy and civil liberties obligations, are understood and managed
  - **ID.GV-4**: Governance and risk management processes address cybersecurity risks

- **Risk Assessment (ID.RA)**: The organization understands the cybersecurity risk to organizational operations (including mission, functions, image, or reputation), organizational assets, and individuals.
  - **ID.RA-1**: Asset vulnerabilities are identified and documented
  - **ID.RA-2**: Cyber threat intelligence is received from information sharing forums and sources
  - **ID.RA-3**: Threats, both internal and external, are identified and documented
  - **ID.RA-4**: Potential business impacts and likelihoods are identified
  - **ID.RA-5**: Threats, vulnerabilities, likelihoods, and impacts are used to determine risk
  - **ID.RA-6**: Risk responses are identified and prioritized

- **Risk Management Strategy (ID.RM)**: The organization’s priorities, constraints, risk tolerances, and assumptions are established and used to support operational risk decisions.
  - **ID.RM-1**: Risk management processes are established, managed, and agreed to by organizational stakeholders
  - **ID.RM-2**: Organizational risk tolerance is determined and clearly expressed
  - **ID.RM-3**: The organization’s determination of risk tolerance is informed by its role in critical infrastructure and sector specific risk analysis

- **"Supply Chain Risk Management (ID.SC)**:
The organization’s priorities, constraints, risk tolerances, and assumptions are established and used to support risk decisions associated with managing supply chain risk. The organization has established and implemented the processes to identify, assess and manage supply chain risks."
  - **ID.SC-1**: Cyber supply chain risk management processes are identified, established, assessed, managed, and agreed to by organizational stakeholders
  - **ID.SC-2**: Suppliers and third party partners of information systems, components, and services are identified, prioritized, and assessed using a cyber supply chain risk assessment process
  - **ID.SC-3**: Contracts with suppliers and third-party partners are used to implement appropriate measures designed to meet the objectives of an organization’s cybersecurity program and Cyber Supply Chain Risk Management Plan.
  - **ID.SC-4**: Suppliers and third-party partners are routinely assessed using audits, test results, or other forms of evaluations to confirm they are meeting their contractual obligations.
  - **ID.SC-5**: Response and recovery planning and testing are conducted with suppliers and third-party providers

### 🟪 Protect

Develop and implement appropriate safeguards to ensure delivery of critical
services.

The Protect Function supports the ability to limit or contain the impact of a potential cybersecurity event.

- **Identity Management, Authentication and Access Control (PR.AC)**: Access to physical and logical assets and associated facilities is limited to authorized users, processes, and devices, and is managed consistent with the assessed risk of unauthorized access to authorized activities and transactions.
  - **PR.AC-1**: Identities and credentials are issued, managed, verified, revoked, and audited for authorized devices, users and processes
  - **PR.AC-2**: Physical access to assets is managed and protected
  - **PR.AC-3**: Remote access is managed
  - **PR.AC-4**: Access permissions and authorizations are managed, incorporating the principles of least privilege and separation of duties
  - **PR.AC-5**: Network integrity is protected (e.g., network segregation, network segmentation)
  - **PR.AC-6**: Identities are proofed and bound to credentials and asserted in interactions
  - **PR.AC-7**: Users, devices, and other assets are authenticated (e.g., single-factor, multi-factor) commensurate with the risk of the transaction (e.g., individuals’ security and privacy risks and other organizational risks)
  
- **Awareness and Training (PR.AT)**: The organization’s personnel and partners are provided cybersecurity awareness education and are trained to perform their cybersecurity-related duties and responsibilities consistent with related policies, procedures, and agreements.
  - **PR.AT-1**: All users are informed and trained
  - **PR.AT-2**: Privileged users understand their roles and responsibilities
  - **PR.AT-3**: Third-party stakeholders (e.g., suppliers, customers, partners) understand their roles and responsibilities
  - **PR.AT-4**: Senior executives understand their roles and responsibilities
  - **PR.AT-5**: Physical and cybersecurity personnel understand their roles and responsibilities

- **Data Security (PR.DS)**: Information and records (data) are managed consistent with the organization’s risk strategy to protect the confidentiality, integrity, and availability of information.
  - **PR.DS-1**: Data-at-rest is protected
  - **PR.DS-2**: Data-in-transit is protected
  - **PR.DS-3**: Assets are formally managed throughout removal, transfers, and disposition
  - **PR.DS-4**: Adequate capacity to ensure availability is maintained
  - **PR.DS-5**: Protections against data leaks are implemented
  - **PR.DS-6**: Integrity checking mechanisms are used to verify software, firmware, and information integrity
  - **PR.DS-7**: The development and testing environment(s) are separate from the production environment
  - **PR.DS-8**: Integrity checking mechanisms are used to verify hardware integrity

- **Information Protection Processes and Procedures (PR.IP)**: Security policies (that address purpose, scope, roles, responsibilities, management commitment, and coordination among organizational entities), processes, and procedures are maintained and used to manage protection of information systems and assets.
  - **PR.IP-1**: A baseline configuration of information technology/industrial control systems is created and maintained incorporating security principles (e.g. concept of least functionality)
  - **PR.IP-2**: A System Development Life Cycle to manage systems is implemented
  - **PR.IP-3**: Configuration change control processes are in place
  - **PR.IP-4**: Backups of information are conducted, maintained, and tested
  - **PR.IP-5**: Policy and regulations regarding the physical operating environment for organizational assets are met
  - **PR.IP-6**: Data is destroyed according to policy
  - **PR.IP-7**: Protection processes are improved
  - **PR.IP-8**: Effectiveness of protection technologies is shared
  - **PR.IP-9**: Response plans (Incident Response and Business Continuity) and recovery plans (Incident Recovery and Disaster Recovery) are in place and managed
  - **PR.IP-10**: Response and recovery plans are tested
  - **PR.IP-11**: Cybersecurity is included in human resources practices (e.g., deprovisioning, personnel screening)
  - **PR.IP-12**: A vulnerability management plan is developed and implemented

- **Maintenance (PR.MA)**: Maintenance and repairs of industrial control and information system components are performed consistent with policies and procedures.
  - **PR.MA-1**: Maintenance and repair of organizational assets are performed and logged, with approved and controlled tools
  - **PR.MA-2**: Remote maintenance of organizational assets is approved, logged, and performed in a manner that prevents unauthorized access

- **Protective Technology (PR.PT)**: Technical security solutions are managed to ensure the security and resilience of systems and assets, consistent with related policies, procedures, and agreements.
  - **PR.PT-1**: Audit/log records are determined, documented, implemented, and reviewed in accordance with policy
  - **PR.PT-2**: Removable media is protected and its use restricted according to policy
  - **PR.PT-3**: The principle of least functionality is incorporated by configuring systems to provide only essential capabilities
  - **PR.PT-4**: Communications and control networks are protected
  - **PR.PT-5**: Mechanisms (e.g., failsafe, load balancing, hot swap) are implemented to achieve resilience requirements in normal and adverse situations

### 🟨 Detect

Develop and implement appropriate activities to identify the occurrence of a
cybersecurity event.

The Detect Function enables timely discovery of cybersecurity events.

- **Anomalies and Events (DE.AE)**: Anomalous activity is detected and the potential impact of events is understood.
  - **DE.AE-1**: A baseline of network operations and expected data flows for users and systems is established and managed
  - **DE.AE-2**: Detected events are analyzed to understand attack targets and methods
  - **DE.AE-3**: Event data are collected and correlated from multiple sources and sensors
  - **DE.AE-4**: Impact of events is determined
  - **DE.AE-5**: Incident alert thresholds are established

- **Security Continuous Monitoring (DE.CM)**: The information system and assets are monitored to identify cybersecurity events and verify the effectiveness of protective measures.
  - **DE.CM-1**: The network is monitored to detect potential cybersecurity events
  - **DE.CM-2**: The physical environment is monitored to detect potential cybersecurity events
  - **DE.CM-3**: Personnel activity is monitored to detect potential cybersecurity events
  - **DE.CM-4**: Malicious code is detected
  - **DE.CM-5**: Unauthorized mobile code is detected
  - **DE.CM-6**: External service provider activity is monitored to detect potential cybersecurity events
  - **DE.CM-7**: Monitoring for unauthorized personnel, connections, devices, and software is performed
  - **DE.CM-8**: Vulnerability scans are performed

- **Detection Processes (DE.DP)**: Detection processes and procedures are maintained and tested to ensure awareness of anomalous events.
  - **DE.DP-1**: Roles and responsibilities for detection are well defined to ensure accountability
  - **DE.DP-2**: Detection activities comply with all applicable requirements
  - **DE.DP-3**: Detection processes are tested
  - **DE.DP-4**: Event detection information is communicated
  - **DE.DP-5**: Detection processes are continuously improved

### 🟥 Respond

Develop and implement appropriate activities to take action regarding a
detected cybersecurity incident.

The Respond Function supports the ability to contain the impact of a potential
cybersecurity incident.

- **Response Planning (RS.RP)**: Response processes and procedures are executed and maintained, to ensure response to detected cybersecurity incidents.
  - **RS.RP-1**: Response plan is executed during or after an incident

- **Communications (RS.CO)**: Response activities are coordinated with internal and external stakeholders (e.g. external support from law enforcement agencies).
  - **RS.CO-1**: Personnel know their roles and order of operations when a response is needed
  - **RS.CO-2**: Incidents are reported consistent with established criteria
  - **RS.CO-3**: Information is shared consistent with response plans
  - **RS.CO-4**: Coordination with stakeholders occurs consistent with response plans
  - **RS.CO-5**: Voluntary information sharing occurs with external stakeholders to achieve broader cybersecurity situational awareness

- **Analysis (RS.AN)**: Analysis is conducted to ensure effective response and support recovery activities.
  - **RS.AN-1**: Notifications from detection systems are investigated
  - **RS.AN-2**: The impact of the incident is understood
  - **RS.AN-3**: Forensics are performed
  - **RS.AN-4**: Incidents are categorized consistent with response plans
  - **RS.AN-5**: Processes are established to receive, analyze and respond to vulnerabilities disclosed to the organization from internal and external sources (e.g. internal testing, security bulletins, or security researchers)

- **Mitigation (RS.MI)**: Activities are performed to prevent expansion of an event, mitigate its effects, and resolve the incident.
  - **RS.MI-1**: Incidents are contained
  - **RS.MI-2**: Incidents are mitigated
  - **RS.MI-3**: Newly identified vulnerabilities are mitigated or documented as accepted risks

- **Improvements (RS.IM)**: Organizational response activities are improved by incorporating lessons learned from current and previous detection/response activities.
  - **RS.IM-1**: Response plans incorporate lessons learned
  - **RS.IM-2**: Response strategies are updated

### 🟩 Recover

Develop and implement appropriate activities to maintain plans for resilience
and to restore any capabilities or services that were impaired due to a  cybersecurity incident.

The Recover Function supports timely recovery to normal operations to reduce the impact from a cybersecurity incident.

- **Recovery Planning (RC.RP)**: Recovery processes and procedures are executed and maintained to ensure restoration of systems or assets affected by cybersecurity incidents.
  - **RC.RP-1**: Recovery plan is executed during or after a cybersecurity incident

- **Improvements (RC.IM)**: Recovery planning and processes are improved by incorporating lessons learned into future activities.
  - **RC.IM-1**: Recovery plans incorporate lessons learned
  - **RC.IM-2**: Recovery strategies are updated
- **Communications (RC.CO)**: Restoration activities are coordinated with internal and external parties (e.g.  coordinating centers, Internet Service Providers, owners of attacking systems, victims, other CSIRTs, and vendors).
  - **RC.CO-1**: Public relations are managed
  - **RC.CO-2**: Reputation is repaired after an incident
  - **RC.CO-3**: Recovery activities are communicated to internal and external stakeholders as well as executive and management teams

## Implementation Tiers

### Tier 1: Partial

- **Risk Management Process** – Organizational cybersecurity risk management practices are not formalized, and risk is managed in an ad hoc and sometimes reactive manner. Prioritization of cybersecurity activities may not be directly informed by organizational risk objectives, the threat environment, or business/mission requirements.

- **Integrated Risk Management Program** – There is limited awareness of cybersecurity risk at the organizational level. The organization implements cybersecurity risk management on an irregular, case-by-case basis due to varied experience or information gained from outside sources. The organization may not have processes that enable cybersecurity information to be shared within the organization.

- **External Participation** – The organization does not understand its role in the larger ecosystem with respect to either its dependencies or dependents. The organization does not collaborate with or receive information (e.g., threat intelligence, best practices, technologies) from other entities (e.g., buyers, suppliers, dependencies, dependents, ISAOs, researchers, governments), nor does it share information. The organization is generally unaware of the cyber supply chain risks of the products and services it provides and that it uses.

### Tier 2: Risk Informed

- **Risk Management Process** – Risk management practices are approved by management but may not be established as organizational-wide policy. Prioritization of cybersecurity activities and protection needs is directly informed by organizational risk objectives, the threat environment, or business/mission requirements.

- **Integrated Risk Management Program** – There is an awareness of cybersecurity risk at the organizational level, but an organization-wide approach to managing cybersecurity risk has not been established. Cybersecurity information is shared within the organization on an informal basis. Consideration of cybersecurity in organizational objectives and programs may occur at some but not all levels of the organization. Cyber risk assessment of organizational and external assets occurs, but is not typically repeatable or reoccurring.

- **External Participation** – Generally, the organization understands its role in the larger ecosystem with respect to either its own dependencies or dependents, but not both. The organization collaborates with and receives some information from other entities and generates some of its own information, but may not share information with others. Additionally, the organization is aware of the cyber supply chain risks associated with the products and services it provides and uses, but does not act consistently or formally upon those risks.

### Tier 3: Repeatable

- **Risk Management Process** – The organization’s risk management practices are formally approved and expressed as policy. Organizational cybersecurity practices are regularly updated based on the application of risk management processes to changes in business/mission requirements and a changing threat and technology landscape.

- **Integrated Risk Management Program** – There is an organization-wide approach to manage cybersecurity risk. Risk-informed policies, processes, and procedures are defined, implemented as intended, and reviewed. Consistent methods are in place to respond effectively to changes in risk. Personnel possess the knowledge and skills to perform their appointed roles and responsibilities. The organization consistently and accurately monitors cybersecurity risk of organizational assets. Senior cybersecurity and non-cybersecurity executives communicate regularly regarding cybersecurity risk. Senior executives ensure consideration of cybersecurity through all lines of operation in the organization.

- **External Participation** - The organization understands its role, dependencies, and dependents in the larger ecosystem and may contribute to the community’s broader understanding of risks. It collaborates with and receives information from other entities regularly that complements internally generated information, and shares information with other entities. The organization is aware of the cyber supply chain risks associated with the products and services it provides and that it uses. Additionally, it usually acts formally upon those risks, including mechanisms such as written agreements to communicate baseline requirements, governance structures (e.g., risk councils), and policy implementation and monitoring.

### Tier 4: Adaptive

- **Risk Management Process** – The organization adapts its cybersecurity practices based on previous and current cybersecurity activities, including lessons learned and predictive indicators. Through a process of continuous improvement incorporating advanced cybersecurity technologies and practices, the organization actively adapts to a changing threat and technology landscape and responds in a timely and effective manner to evolving, sophisticated threats.

- **Integrated Risk Management Program** – There is an organization-wide approach to managing cybersecurity risk that uses risk-informed policies, processes, and procedures to address potential cybersecurity events. The relationship between cybersecurity risk and organizational objectives is clearly understood and considered when making decisions. Senior executives monitor cybersecurity risk in the same context as financial risk and other organizational risks. The organizational budget is based on an understanding of the current and predicted risk environment and risk tolerance. Business units implement executive vision and analyze system-level risks in the context of the organizational risk tolerances. Cybersecurity risk management is part of the organizational culture and evolves from an awareness of previous activities and continuous awareness of activities on their systems and networks. The organization can quickly and efficiently account for changes to business/mission objectives in how risk is approached and communicated.

- **External Participation** - The organization understands its role, dependencies, and dependents in the larger ecosystem and contributes to the community’s broader understanding of risks. It receives, generates, and reviews prioritized information that informs continuous analysis of its risks as the threat and technology landscapes evolve. The organization shares that information internally and externally with other collaborators. The organization uses real-time or near real-time information to understand and consistently act upon cyber supply chain risks associated with the products and services it provides and that it uses. Additionally, it communicates proactively, using formal (e.g., agreements) and informal mechanisms to develop and maintain strong supply chain relationships.

## Establishing or Improving a Cybersecurity Program

The following steps illustrate how an organization could use the Framework to create a new cybersecurity program or improve an existing program. These steps should be repeated as necessary to continuously improve cybersecurity.

### Step 1: Prioritize and Scope

The organization identifies its business/mission objectives and high-level organizational priorities. With this information, the organization makes strategic decisions regarding cybersecurity implementations and determines the scope of systems and assets that support the selected business line or process. The Framework can be adapted to support the different business lines or processes within an organization, which may have different business needs and associated risk tolerance. Risk tolerances may be reflected in a target Implementation Tier.

### Step 2: Orient

Once the scope of the cybersecurity program has been determined for the business line or process, the organization identifies related systems and assets, regulatory requirements, and overall risk approach. The organization then consults sources to identify threats and vulnerabilities applicable to those systems and assets.

### Step 3: Create a Current Profile

The organization develops a Current Profile by indicating which Category and Subcategory outcomes from the Framework Core are currently being achieved. If an outcome is partially achieved, noting this fact will help support subsequent steps by providing baseline information.

### Step 4: Conduct a Risk Assessment

This assessment could be guided by the organization’s overall risk management process or previous risk assessment activities. The organization analyzes the operational environment in order to discern the likelihood of a cybersecurity event and the impact that the event could have on the organization. It is important that organizations identify emerging risks and use cyber threat information from internal and external sources to gain a better understanding of the likelihood and impact of cybersecurity events.

### Step 5: Create a Target Profile

The organization creates a Target Profile that focuses on the assessment of the Framework Categories and Subcategories describing the organization’s desired cybersecurity outcomes. Organizations also may develop their own additional Categories and Subcategories to account for unique organizational risks. The organization may also consider influences and requirements of external stakeholders such as sector entities, customers, and business partners when creating a Target Profile. The Target Profile should appropriately reflect criteria within the target Implementation Tier.

### Step 6: Determine, Analyze, and Prioritize Gaps

The organization compares the Current Profile and the Target Profile to determine gaps. Next, it creates a prioritized action plan to address gaps – reflecting mission drivers, costs and benefits, and risks – to achieve the outcomes in the Target Profile. The organization then determines resources, including funding and workforce, necessary to address the gaps. Using Profiles in this manner encourages the organization to make informed decisions about cybersecurity activities, supports risk management, and enables the organization to perform cost-effective, targeted improvements.

### Step 7: Implement Action Plan

The organization determines which actions to take to address the gaps, if any, identified in the previous step and then adjusts its current cybersecurity practices in order to achieve the Target Profile. For further guidance, the Framework identifies example Informative References regarding the Categories and Subcategories, but organizations should determine which standards, guidelines, and practices, including those that are sector specific, work best for their needs.

An organization repeats the steps as needed to continuously assess and improve its cybersecurity. For instance, organizations may find that more frequent repetition of the orient step improves the quality of risk assessments. Furthermore, organizations may monitor progress through iterative updates to the Current Profile, subsequently comparing the Current Profile to the Target Profile. Organizations may also use this process to align their cybersecurity program with their desired Framework Implementation Tier.
