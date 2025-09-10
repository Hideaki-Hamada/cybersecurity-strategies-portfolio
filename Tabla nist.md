# Current State Assessment Template
## NIST Cybersecurity Framework - FinSecure Bank

**Team Name:** ________________________  EZLN
**Team Members:** ________________________  Dana Gabriela López Chan, Fernando Ricardo Castillo Contreras, Luis Manuel Palacios Gutierrez, Julio David Vazquez Arjona, Emiliano Javier Urrea Mariño
**Date:** ________________________  09/08/2025

---

## **Assessment Instructions**

### **Scoring Guidelines (1-5 Scale):**

| **Score** | **Maturity Level** | **Description** |
|-----------|-------------------|-----------------|
| **1** | **Not Implemented** | No processes, controls, or awareness in place |
| **2** | **Partially Implemented** | Ad-hoc, informal processes; limited documentation |
| **3** | **Implemented** | Documented processes with basic monitoring |
| **4** | **Managed** | Measured, monitored, and regularly reviewed processes |
| **5** | **Optimized** | Continuously improved and automated where appropriate |

### **Evidence Types to Consider:**
- **Policies and procedures** documented and current
- **Technology implementations** and configurations
- **Training records** and awareness programs
- **Incident history** and response capabilities
- **Audit findings** and remediation status
- **Regulatory compliance** status and findings

---

## **IDENTIFY Function Assessment**

### **Asset Management (ID.AM)**

| **Subcategory** | **Description**                                                                                                                                   | **Current Score (1-5)** | **Evidence/Justification**                                                                                                                                                                                                    | **Confidence Level** |
| --------------- | ------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | -------------------- |
| **ID.AM-1**     | Physical devices and systems within the organization are inventoried                                                                              | 3                       | They have asset inventories as part of the resources available for cybersecurity analysis. This is mentioned on page 31 under the heading                                                                                     | Med                  |
| **ID.AM-2**     | Software platforms and applications within the organization are inventoried                                                                       | 3                       | They do have a software and application inventory system for their infrastructure, but the maturity level of the system is unknown.                                                                                           | Med                  |
| **ID.AM-3**     | Organizational communication and data flows are mapped                                                                                            | 2                       | It is mentioned that network diagrams are available, suggesting that some data flows may be represented, but there is no clear evidence that organizational communication flows are fully mapped, documented, and maintained. | Low                  |
| **ID.AM-4**     | External information systems are catalogued                                                                                                       | 3                       | There is no explicit mention of a formal catalog or external systems management tool, but it is understood that supplier audits are performed and that a cloud platform is available for testing.                             | Med                  |
| **ID.AM-5**     | Resources (hardware, devices, data, time, personnel, and software) are prioritized based on their classification, criticality, and business value | 2                       | There are indications of prioritization in terms of investment and strategy, but no mention is made of a formal process for classifying and prioritizing resources based on their value or criticality.                       | Low                  |
| **ID.AM-6**     | Cybersecurity roles and responsibilities for the entire workforce and third-party stakeholders are established                                    | 4                       | Roles are defined and assigned for both internal and external personnel. It is not explicitly stated whether all employees are aware of their cybersecurity responsibilities.                                                 | High                 |

**Asset Management Assessment Notes:**
- **Key Strengths:** Staff roles and software and hardware inventory systems.
- **Major Gaps:** Organizational communication and classification of asset criticality
- **Priority Actions:** Classification of asset criticality and Organizational communication

---

### **Business Environment (ID.BE)**

| **Subcategory** | **Description**                                                                                            | **Current Score (1-5)** | **Evidence/Justification**                                                                                                                                                                                                                                                                                                                                       | **Confidence Level** |
| --------------- | ---------------------------------------------------------------------------------------------------------- | ----------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | -------------------- |
| **ID.BE-1**     | The organization's role in the supply chain is identified and communicated                                 | 2                       | There is awareness of third-party risks and measures have been taken, there is no evidence that FinSecure's role in the supply chain has been formally identified or communicated to stakeholders.<br>There is no mention of whether there is a policy or documentation defining its position as a consumer, supplier, or intermediary in the chain.             | Low                  |
| **ID.BE-2**     | The organization's place in critical infrastructure and its industry sector is identified and communicated | 4                       | The organization recognizes its role in the financial sector as part of critical infrastructure. It complies with multiple sector-specific regulations.<br>There is awareness of the threat environment and regulatory pressure.<br>It is not explicitly mentioned whether this information is communicated in a structured manner to all employees or partners. | High                 |
| **ID.BE-3**     | Priorities for organizational mission, objectives, and activities are established and communicated         | 4                       | The objectives are clearly defined and aligned with the bank's mission. They are communicated in the context of the GAP analysis project.<br>There is no mention of whether these priorities are integrated at all operational levels or whether they are reviewed regularly.                                                                                    | High                 |
| **ID.BE-4**     | Dependencies and critical functions for delivery of critical services are established                      | 3                       | Critical functions are identified in practice (core banking, infrastructure, digital services).<br> There is no mention of whether there is formal documentation linking technological dependencies to critical business functions.<br>There is no indication of whether there is a dependency map or impact matrix.                                             | Med                  |
| **ID.BE-5**     | Resilience requirements to support delivery of critical services are established for all operating states  | 3                       | There are backup and recovery practices that work.<br>There is no evidence that requirements are documented for all operating states or formally communicated.                                                                                                                                                                                                   | Med                  |

**Business Environment Assessment Notes:**
- **Key Strengths:** There is a clear notion of the organization's role as critical infrastructure, also well-defined objectives and the presence of established recovery practices. 
- **Major Gaps:** There is no formal identification of the organization's role in the supply chain, not enough documentation of resilience requirements, dependencies and critical functions. 
- **Priority Actions:** Document and communicate correctly the role in the supply chain, as well a formal documentation mapping dependencies between technology, processes and critical functions.  

---

### **Governance (ID.GV)**

| **Subcategory** | **Description**                                                                                                | **Current Score (1-5)** | **Evidence/Justification**                                                                                                                                                                                                                                                                                                   | **Confidence Level** |
| --------------- | -------------------------------------------------------------------------------------------------------------- | ----------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | -------------------- |
| **ID.GV-1**     | Organizational cybersecurity policy is established and communicated                                            | 4                       | Policies exist and are available.<br>Actions are being taken to improve security posture.<br>There is no evidence of periodic review or structured communication at all levels.                                                                                                                                              | High                 |
| **ID.GV-2**     | Cybersecurity roles and responsibilities are coordinated and aligned with internal roles and external partners | 3                       | Roles are defined and there is collaboration with third parties.<br>There is no mention of formal coordination between internal and external roles (e.g., RACI matrices, shared responsibility agreements).<br>Nor is there any indication of processes to align security objectives between the bank and its suppliers.<br> | Med                  |
| **ID.GV-3**     | Legal and regulatory requirements regarding cybersecurity are understood and managed                           | 3                       | The bank complies with multiple relevant regulations.<br>It has processes in place to assess and respond to regulatory findings.<br>There is no mention of whether there is an automated or centralized system for managing compliance.                                                                                      | Med                  |
| **ID.GV-4**     | Governance and risk management processes address cybersecurity risks                                           | 4                       | There are established processes for addressing cybersecurity risks.<br>Corrective actions have been taken following audits.<br>There is no mention of whether there is a formal risk management methodology or whether it is reviewed periodically.                                                                          | High                 |

**Governance Assessment Notes:**
- **Key Strengths:** Accessible cyber security policy, established processes for addressing security risks and compliance with multiple regulations.
- **Major Gaps:** There is not a set timeline to review policies or consistently communicated, coordination roles with partners outside the organization in informal, compliance management is not centralized and there is not a established methodology for risk management.
- **Priority Actions:** Establish a regular review cycle for policies with structured and clear communication, formalize the role coordination with partners, implement a centralized system for compliance tracking and adopt a standardized risk management methodology.

---

### **Risk Assessment (ID.RA)**

| **Subcategory** | **Description**                                                                   | **Current Score (1-5)** | **Evidence/Justification**                                                                                                                                                                                                                                                                | **Confidence Level** |
| --------------- | --------------------------------------------------------------------------------- | ----------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | -------------------- |
| **ID.RA-1**     | Asset vulnerabilities are identified and documented                               | 2                       | There are mechanisms that could identify vulnerabilities (penetration tests, incidents).<br>There is no evidence of a formal, continuous, and documented process for identifying vulnerabilities in all technological assets.                                                             | Low                  |
| **ID.RA-2**     | Cyber threat intelligence is received from information sharing forums and sources | 2                       | There are external services that could provide intelligence, but there is no evidence of active participation in exchange forums or systematic reception of threat intelligence.<br>There is no mention of whether sources such as US-CERT, FS-ISAC, or commercial threat feeds are used. | Low                  |
| **ID.RA-3**     | Threats, both internal and external, are identified and documented                | 4                       | Threats are clearly identified and documented in real incidents.<br>The threat environment of the sector is recognized.<br>There is no mention of whether there is a formal repository or automated system to manage this information.                                                    | High                 |
| **ID.RA-4**     | Potential business impacts and likelihoods are identified                         | 3                       | Impacts and costs are identified in real incidents.<br>There is awareness of the threat environment.<br>There is no formal, ongoing process for assessing impacts and probabilities in a structured manner.                                                                               | Med                  |
| **ID.RA-5**     | Threats, vulnerabilities, likelihoods, and impacts are used to determine risk     | 3                       | Risk components are present and analyzed in real incidents<br>There is no evidence of a structured, repeatable, and documented process for proactively determining risk.                                                                                                                  | Med                  |
| **ID.RA-6**     | Risk responses are identified and prioritized                                     | 3                       | Responses to risks are in place and implemented.<br>There is no evidence of a formal framework for prioritizing and managing these responses in a structured and continuous manner.                                                                                                       | Med                  |

**Risk Assessment Notes:**
- **Key Strengths:** Threats are both well recognized and documented from real past incidents, with awareness of risks and established responses.
- **Major Gaps:** There is no formal documentation of both vulnerabilities and threat intelligence, no clear structure for impact and likelihood assessments and risk determinations and response prioritization are not based on a framework.
- **Priority Actions:** Create a formal vulnerability management process, adopt systematic threat intelligence sources, create well structured methods for how impact and likelihood are assessed, and implement a framework for risk and response prioritization.

---

### **Risk Management Strategy (ID.RM)**

| **Subcategory** | **Description**                                                                                                                         | **Current Score (1-5)** | **Evidence/Justification**                                                                                                                                                                   | **Confidence Level** |
| --------------- | --------------------------------------------------------------------------------------------------------------------------------------- | ----------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | -------------------- |
| **ID.RM-1**     | Risk management processes are established, managed, and agreed to by organizational stakeholders                                        | 3                       | There are active risk management processes.<br>There is no evidence of formal consensus or structured governance regarding these processes.                                                  | Med                  |
| **ID.RM-2**     | Organizational risk tolerance is determined and clearly expressed                                                                       | 2                       | There are signs of risk management and budgetary control.<br>There is a lack of formal definition and clear communication of organizational risk tolerance.                                  | Low                  |
| **ID.RM-3**     | The organization's determination of risk tolerance is informed by its role in critical infrastructure and sector specific risk analysis | 2                       | The bank is aware of its role in critical infrastructure and the threat environment.<br>There is no evidence that this information is used to formally inform organizational risk tolerance. | Low                  |

**Risk Management Strategy Notes:**
- **Key Strengths:** Active risk management is in place, there is a certain level of awareness of its critical infrastructure role and sector associated risks.
- **Major Gaps:** Lack of a formal agreement around risk management processes, organizational risk tolerance is not clearly defined or communicated and critical infrastructure considerations are not being used to guide risk tolerance
- **Priority Actions:** Create a stakeholder consensus for risk management processes, properly define and communicate organization risk tolerance, and align risk tolerance with the organization's role in critical infrastructure.

---

### **Supply Chain Risk Management (ID.SC)**

| **Subcategory** | **Description**                                                                                                                                                                  | **Current Score (1-5)** | **Evidence/Justification**                                                                                                                                                                                                                                                                                                                                | **Confidence Level** |
| --------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | -------------------- |
| **ID.SC-1**     | Cyber supply chain risk management processes are identified, established, assessed, managed, and agreed to by organizational stakeholders                                        | 2                       | There is awareness of the risk in the supply chain and actions have been initiated.<br>There is a lack of formalization, complete documentation, and organizational consensus on the processes for managing these risks.                                                                                                                                  | Low                  |
| **ID.SC-2**     | Suppliers and third party partners of information systems, components, and services are identified, prioritized, and assessed using a cyber supply chain risk assessment process | 2                       | There is awareness of third-party risk, and assessments have been initiated.<br>Formalization, structured prioritization, and organizational consensus on the process are lacking.<br>                                                                                                                                                                    | Low                  |
| **ID.SC-3**     | Contracts with suppliers and third-party partners are used to implement appropriate measures designed to meet the objectives of an organization's cybersecurity program          | 2                       | There is awareness of third-party risk, and assessments have been initiated.<br>There is a lack of evidence of systematic use of contracts as a tool to implement security measures aligned with the organizational program.                                                                                                                              | Low                  |
| **ID.SC-4**     | Suppliers and third-party partners are routinely assessed using audits, test results, or other forms of evaluations to confirm they are meeting their contractual obligations    | 1                       | There is no evidence of regular audits or formal reviews.<br>Third-party management is in its early stages.<br>Third-party risk was identified as a weakness in the current posture analysis.                                                                                                                                                             | Low                  |
| **ID.SC-5**     | Response and recovery planning and testing are conducted with suppliers and third-party providers                                                                                | 1                       | There is no evidence of joint drills, tabletop exercises, or recovery testing with third parties.<br>Third-party management is a recognized weakness.<br>Incident response is described as informal and with little automation.<br>Although there is an MSSP and external penetration testing, there is no indication of collaboration on recovery plans. | Low                  |

**Supply Chain Risk Management Notes:**
- **Key Strengths:** There is awareness of third-party and supply chain risks, and some initial assessments and external testing have been initiated.
- **Major Gaps:** Not a proper formalization for risk management processes in the supply chain, as well as in the documentation and stakeholder consensus. Not a proper structure for supplier prioritization, contracts are not systematically leveraged for security, a complete lack of routine assessments and no joint response nor recovery planning with third parties. 
- **Priority Actions:** Formalize and document supply chain risk management processes, establish structured supplier assessment and prioritization, integrate security requirements into contracts, implement regular third-party audits, and develop joint response and recovery testing with key suppliers and partners.

---

## **PROTECT Function Assessment**

### **Identity Management, Authentication and Access Control (PR.AC)**

| **Subcategory** | **Description**                                                                                                                      | **Current Score (1-5)** | **Evidence/Justification**                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         | **Confidence Level** |
| --------------- | ------------------------------------------------------------------------------------------------------------------------------------ | ----------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | -------------------- |
| **PR.AC-1**     | Identities and credentials are issued, managed, verified, revoked, and audited for authorized devices, users and processes           | 2                       | Identity system: Microsoft Active Directory (2016 version), which is functional but somewhat outdated.<br>MFA: RSA SecurID with limited deployment, indicating that not all users or processes are protected with multi-factor authentication.<br>Manual processes: Identity management is said to involve manual processes, limiting efficiency and auditability.<br>Not mentioned: Issuance, revocation, or systematic auditing of credentials for devices or processes.                                                         | Low                  |
| **PR.AC-2**     | Physical access to assets is managed and protected                                                                                   | 4                       | The document indicates that physical security at branches and data centers is a known strength.<br>Although specific controls (such as cameras, access cards, guards, etc.) are not detailed, it is explicitly acknowledged that physical measures are robust.<br>There is no mention of a formal audit or periodic review of these controls, which prevents a perfect rating from being awarded.                                                                                                                                  | High                 |
| **PR.AC-3**     | Remote access is managed                                                                                                             | 2                       | The document indicates that branch offices are connected via an MPLS network backed up by the internet, but does not detail how remote access by employees or third parties is managed.<br>MFA is implemented in a limited way, which is critical for protecting remote access.<br>There is no mention of the use of VPNs, session controls, remote access monitoring, or specific policies.<br>The security infrastructure is described as legacy and partially automated, suggesting weaknesses in this area.                    | Low                  |
| **PR.AC-4**     | Access permissions and authorizations are managed, incorporating the principles of least privilege and separation of duties          | 2                       | Microsoft Active Directory (2016) is used, which allows permissions to be managed, but there is no mention of an explicit implementation of least privilege or separation of duties.<br> Identity management is described as manual and limited, suggesting that accesses may not be optimized or reviewed regularly.<br>There is no evidence of access audits, automated provisioning tools, or periodic role reviews.                                                                                                            | Low                  |
| **PR.AC-5**     | Network integrity is protected (e.g., network segregation, network segmentation)                                                     | 3                       | The document indicates that there is basic segmentation between environments, which is positive but limited.<br>It does not specify whether VLANs, internal firewalls, DMZ zones, or microsegmentation are used.<br>The network infrastructure includes MPLS with internet backup and redundant data centers, which supports availability but not necessarily integrity.<br>The security infrastructure is legacy, which could limit advanced segmentation capabilities.                                                           | Low / Med / High     |
| **PR.AC-6**     | Identities are proofed and bound to credentials and asserted in interactions                                                         | 2                       | Active Directory (2016) is used, which allows for some identity management, but formal verification (e.g., identity validation before issuing credentials) is not mentioned.<br>MFA is implemented in a limited way, reducing the ability to robustly assert identities in interactions.<br>There is no evidence of secure provisioning, automated revocation, or credential auditing processes.<br>Identity management is described as manual, which limits traceability and security.<br>                                        | Low                  |
| **PR.AC-7**     | Users, devices, and other assets are authenticated (e.g., single-factor, multi-factor) commensurate with the risk of the transaction | 2                       | RSA SecurID is used for multi-factor authentication, but with limited deployment, indicating that not all users or critical processes are adequately protected.<br>There is no mention of adaptive authentication or segmentation by risk level.<br>The identity infrastructure is manual and based on Active Directory 2016, with no evidence of authentication for devices or automated processes.<br>There is no indication of policies that adjust the level of authentication based on the type of transaction or access.<br> | Low                  |

**Access Control Assessment Notes:**
- **Key Strengths:** Physical access controls at branches and data centers are robust, and basic network segmentation is in place to support availability and partial protection of assets.
- **Major Gaps:** Identity and access management relies on outdated infrastructure and manual processes, MFA deployment is limited, least privilege and separation of duties are not enforced, remote access lacks clear policies and controls, and device authentication and advanced segmentation are not implemented.
- **Priority Actions:** Modernize identity management with automated provisioning and auditing, expand MFA to all users and critical processes, formalize least privilege and role reviews, strengthen remote access with VPNs and monitoring, enhance network segmentation, and establish secure credential proofing and device authentication.

---

### **Awareness and Training (PR.AT)**

| **Subcategory** | **Description**                                                                  | **Current Score (1-5)** | **Evidence/Justification**                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           | **Confidence Level** |
| --------------- | -------------------------------------------------------------------------------- | ----------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | -------------------- |
| **PR.AT-1**     | All users are informed and trained                                               | 2                       | A phishing incident was reported in March 2024, where 12 employees fell victim due to a lack of awareness about email security.<br>The response included additional training, indicating that not all users were previously trained.<br>There is a security awareness coordinator (Jennifer Walsh), but she works part-time (0.5 FTE), which limits the scope.<br>An enhanced phishing simulation program has been initiated but is still in the implementation phase.<br>                                                                                                                                                           | Low                  |
| **PR.AT-2**     | Privileged users understand their roles and responsibilities                     | 2                       | The document mentions an IT structure with defined roles (CIO, IT Security Manager, etc.), but does not specify whether privileged users receive differentiated training or are assigned specific responsibilities.<br>Security awareness is limited and in the process of being improved, suggesting that specific training for privileged users is probably not formalized. There is no mention of acceptable use policies, liability agreements, or audits of privileged activities.<br>                                                                                                                                          | Low                  |
| **PR.AT-3**     | Third-party stakeholders understand their roles and responsibilities             | 1                       | Se indica que hay una nueva iniciativa de evaluación de riesgos de terceros, pero aún está en desarrollo.<br>No se menciona que los proveedores participen en simulacros, capacitaciones, ni revisiones de seguridad conjuntas.<br>No hay evidencia de acuerdos formales de seguridad, SLAs con cláusulas de ciberseguridad, ni de programas de concientización para terceros.<br>La gestión de terceros fue identificada como una debilidad clave en el análisis de postura actual.<br>                                                                                                                                             | Low                  |
| **PR.AT-4**     | Senior executives understand their roles and responsibilities                    | 2                       | The document mentions that the CIO (Sarah Mitchell) has experience in regional banking, suggesting some knowledge of the environment.<br>An IT Security Manager was hired following FDIC findings, indicating that there was an executive response to regulatory concerns.<br>However, there is no mention of specific training for executives, active participation in drills, policy reviews, or leadership in security initiatives.<br>The presentation of results to the Board Risk Committee is planned as part of the GAP Analysis, suggesting that executive awareness is developing but not yet consolidated.<br>            | Low                  |
| **PR.AT-5**     | Physical and cybersecurity personnel understand their roles and responsibilities | 3                       | El equipo de seguridad cibernética está compuesto por 4 FTE + 0.5 FTE en concientización, con roles definidos (analista, especialista de red, analista de cumplimiento, coordinadora de concientización).<br>El IT Security Manager fue contratado tras hallazgos del FDIC, lo que indica una intención de fortalecer la gobernanza.<br>No se menciona si el personal recibe capacitación formal y continua, ni si hay documentación clara de roles y responsabilidades.<br>La seguridad física se considera una fortaleza, pero no se detalla si el personal de seguridad física está alineado con políticas de ciberseguridad.<br> | Low                  |

**Awareness and Training Assessment Notes:**
- **Key Strengths:** Cybersecurity and physical security personnel have defined roles, and there are initial initiatives for phishing simulations and awareness programs.
- **Major Gaps:** General user training is incomplete, privileged users and executives lack formalized training, third-party stakeholders are not engaged, and awareness programs are limited in scope and resources.
- **Priority Actions:** Expand user and privileged user training, implement ongoing executive awareness programs, involve third parties in security education and exercises, and increase resources for structured, continuous awareness initiatives.

---

### **Data Security (PR.DS)**

| **Subcategory** | **Description**                                                                                | **Current Score (1-5)** | **Evidence/Justification**                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       | **Confidence Level** |
| --------------- | ---------------------------------------------------------------------------------------------- | ----------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | -------------------- |
| **PR.DS-1**     | Data-at-rest is protected                                                                      | 1                       | The document does not refer to disk, database, or storage encryption.<br>No specific access controls are mentioned to protect data at rest.<br>The technological infrastructure includes legacy systems (IBM DB2 on AIX, FIS Profile), which could limit modern data protection capabilities.<br>Data protection in transit is also not mentioned, reinforcing the lack of focus on information security.                                                                                                                        | Low                  |
| **PR.DS-2**     | Data-in-transit is protected                                                                   | 1                       | There is no mention of the use of TLS/SSL, VPNs, or encryption of communications between systems, users, or branches.<br>The infrastructure includes SOAP APIs with few REST endpoints, which may limit modern security in integrations.<br>Although there is MPLS connectivity and ISP redundancy, this favors availability but does not guarantee the protection of data in transit.<br>There is no evidence of specific policies or controls to protect information while it is being transmitted.<br>                        | Low                  |
| **PR.DS-3**     | Assets are formally managed throughout removal, transfers, and disposition                     | 1                       | The document does not mention policies or procedures for the secure disposal of assets, internal transfers, or equipment dismantling.<br>There is no evidence of updated inventories, asset tagging, or disposal audits.<br>Although it is indicated that there is access to asset inventories as part of the resources available for analysis, this does not imply that there is formal management of the entire cycle.                                                                                                         | Low                  |
| **PR.DS-4**     | Adequate capacity to ensure availability is maintained                                         | 3                       | The primary system has 99.2% availability, with a target of 99.5%, indicating active monitoring and management.<br>The infrastructure includes:<br>Primary data center in Austin.<br>Disaster recovery (DR) site in Dallas.<br>Redundant connectivity with dual ISPs.<br>There is no explicit mention of the use of capacity monitoring tools, proactive alerts, or scalability plans for peak demand.<br>The digital transformation and cloud migration strategy suggests that work is underway to improve this area.<br>       | Mid                  |
| **PR.DS-5**     | Protections against data leaks are implemented                                                 | 1                       | There is no mention of the use of DLP technologies, outbound traffic monitoring, or content-based access controls.<br>The data breach incident by a supplier in August 2024 exposed 8,500 records, highlighting a lack of effective protection against external leaks.<br>The security infrastructure is legacy and limited, suggesting that there are no modern data leak prevention mechanisms in place.<br>There is no evidence of data classification, sensitive information handling policies, or data transfer audits.<br> | Low                  |
| **PR.DS-6**     | Integrity checking mechanisms are used to verify software, firmware, and information integrity | 1                       | There is no evidence of the use of hashes, digital signatures, integrity scanning, or tools such as Tripwire, file integrity monitoring (FIM), or similar.<br>The infrastructure includes legacy systems (FIS Profile, IBM DB2 on AIX), which may limit the ability to implement modern integrity controls.<br>There is no mention of any post-update verification process or audit of changes to critical files.<br>                                                                                                            | Low                  |
| **PR.DS-7**     | The development and testing environment(s) are separate from the production environment        | 1                       | There is no reference to development, testing, or version control environments.<br>There is no mention of the use of isolated environments or secure deployment policies.<br>The technological infrastructure is based on legacy systems (FIS Profile, IBM DB2), which could hinder the implementation of separate environments.<br>The lack of automation in security processes also suggests that this practice is not formalized.<br>                                                                                         | Low                  |
| **PR.DS-8**     | Integrity checking mechanisms are used to verify hardware integrity                            | 1                       | There is no evidence of the use of technologies such as secure boot, TPM (Trusted Platform Module), or firmware signing.<br>The infrastructure includes legacy systems (AIX servers, FIS Profile), which may limit the ability to implement modern hardware integrity controls.<br>There is no mention of hardware audits or post-deployment validation processes.<br>                                                                                                                                                           | Low                  |

**Data Security Assessment Notes:**
- **Key Strengths:** System availability is actively managed with redundancy, a DR site, and dual ISP connectivity, providing baseline continuity.
- **Major Gaps:** Data-at-rest and in-transit are unprotected, asset lifecycle management is absent, data leak protections and integrity checks are missing, and development/testing environments are not separated from production. Legacy infrastructure limits modern security capabilities.
- **Priority Actions:** Implement encryption for data-at-rest and in-transit, establish formal asset management and secure disposal procedures, deploy data leak prevention and integrity verification mechanisms, separate development/testing from production, and modernize infrastructure to support these controls.

---

## *DETECT Function Assessment*

### *Anomalies and Events (DE.AE)*

| *Subcategory* | *Description*                                                                                           | *Current Score (1-5)* | *Evidence/Justification*                                                                                                                                                                                                        | *Confidence Level* |
| --------------- | --------------------------------------------------------------------------------------------------------- | ----------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | -------------------- |
| *DE.AE-1*     | A baseline of network operations and expected data flows for users and systems is established and managed | 1                       | The document does not indicate that FinSecure Bank has established or actively manages a baseline of network operations and expected data flows for users and systems.                                                            | Low                  |
| *DE.AE-2*     | Detected events are analyzed to understand attack targets and methods                                     | 2                       | The incident response process is informal, and SIEM deployment is limited, which restricts deeper analysis of attack methods and targets.                                                                                         | Low                  |
| *DE.AE-3*     | Event data are collected and correlated from multiple sources and sensors                                 | 1                       | It does not appear to collect and correlate event data from multiple sources and sensors in a comprehensive way. The document mentions a limited deployment of Splunk SIEM, which restricts centralized visibility.               | Low                  |
| *DE.AE-4*     | Impact of events is determined                                                                            | 3                       | FinSecure Bank does determine the impact of events, at least at a basic level. like the phishing incident included cost estimates and identification of root cause. However, these assessments appear to be manual and reactive.  | Med                  |
| *DE.AE-5*     | Incident alert thresholds are established                                                                 | 1                       | There is no mention the establishment of incident alert thresholds at FinSecure Bank. While incidents are reported and responded to, there is no evidence of predefined criteria or thresholds that trigger alerts automatically. | Low                  |

*Anomalies and Events Assessment Notes:*
- *Key Strengths:* Event impacts are assessed at a basic level, including cost estimates and root cause identification for incidents.
- *Major Gaps:* Network baselines are not established, event collection and correlation are limited, incident analysis is informal, and alert thresholds are not defined or automated.
- *Priority Actions:* Establish network baselines, deploy comprehensive event collection and correlation tools, formalize incident analysis processes, and define automated alert thresholds for timely detection.

---

### *Security Continuous Monitoring (DE.CM)*

| *Subcategory* | *Description*                                                                          | *Current Score (1-5)* | *Evidence/Justification*                                                                                                                                                                                                                                                                        | *Confidence Level* |
| --------------- | ---------------------------------------------------------------------------------------- | ----------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | -------------------- |
| *DE.CM-1*     | The network is monitored to detect potential cybersecurity events                        | 2                       | There is a SIEM splunk but its partially implemented FinSecure Bank performs limited network monitoring for cybersecurity events.                                                                                                                                                                 | Low                  |
| *DE.CM-2*     | The physical environment is monitored to detect potential cybersecurity events           | 2                       | There is strong physical security controls at branches and data centers, as noted in the document. However, it does not specify whether the physical environment is actively monitored for cybersecurity-related events.                                                                          | Low                  |
| *DE.CM-3*     | Personnel activity is monitored to detect potential cybersecurity events                 | 1                       | Monitoring of personnel activity to detect potential cybersecurity events is not clearly implemented at FinSecure Bank. Given the limited SIEM deployment and informal incident response processes, this area appears to be underdeveloped.                                                       | Low                  |
| *DE.CM-4*     | Malicious code is detected                                                               | 2                       | Malicious code is detected to some extent at FinSecure Bank. The bank uses Symantec Endpoint Protection, but it's a legacy version, which may lack modern detection capabilities. Additionally, Splunk SIEM is deployed, but only in a limited scope, reducing visibility across the environment. | Low                  |
| *DE.CM-5*     | Unauthorized mobile code is detected                                                     | 1                       | There is no specific controls or tools for detecting unauthorized mobile code. Endpoint protection is based on a legacy version of Symantec, and there is no indication of advanced threat detection or behavioral analysis capabilities.                                                         | Low                  |
| *DE.CM-6*     | External service provider activity is monitored to detect potential cybersecurity events | 2                       | There is limited monitoring of external service provider activity. The document mentions a regional MSP providing monitoring services, but with a limited scope.                                                                                                                                  | Low / Med / High     |
| *DE.CM-7*     | Monitoring for unauthorized personnel, connections, devices, and software is performed   | 1                       | Monitoring for unauthorized personnel, connections, devices, and software at FinSecure Bank is not clearly described.                                                                                                                                                                             | Low / Med / High     |
| *DE.CM-8*     | Vulnerability scans are performed                                                        | 1                       | While FinSecure Bank performs penetration testing annually through a third party, this is not the same as continuous or automated vulnerability scanning.                                                                                                                                         | Low / Med / High     |

*Security Continuous Monitoring Assessment Notes:*
- *Key Strengths:* Some monitoring exists via SIEM and legacy endpoint protection, and physical security controls are robust.
- *Major Gaps:* Network and personnel monitoring are limited, external service provider activity is only partially monitored, malicious and unauthorized code detection is weak, monitoring of connections and devices is minimal, and vulnerability scanning is not continuous or automated.
- *Priority Actions:* Fully deploy and integrate SIEM, enhance endpoint and mobile code detection, implement continuous vulnerability scanning, expand monitoring of personnel, devices, and external providers, and integrate physical and cybersecurity monitoring for centralized visibility.

---

## *RESPOND Function Assessment*

### *Response Planning (RS.RP)*

| *Subcategory* | *Description*                                       | *Current Score (1-5)* | *Evidence/Justification*                                                                                                 | *Confidence Level* |
| --------------- | ----------------------------------------------------- | ----------------------- | -------------------------------------------------------------------------------------------------------------------------- | -------------------- |
| *RS.RP-1*     | Response plan is executed during or after an incident | 2                       | FinSecure Bank does execute response plans during or after incidents, but the execution is informal and lacks automation.  | Low                  |

*Response Planning Assessment Notes:*
- *Key Strengths:* 
- *Major Gaps:* 
- *Priority Actions:* 

---

### *Communications (RS.CO)*

| *Subcategory* | *Description*                                                                                                        | *Current Score (1-5)* | *Evidence/Justification*                                                                                                                                                                                                                                                         | *Confidence Level* |
| --------------- | ---------------------------------------------------------------------------------------------------------------------- | ----------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | -------------------- |
| *RS.CO-1*     | Personnel know their roles and order of operations when a response is needed                                           | 2                       | Inconsistent employee training program but in recent there an implementation of an  Enhanced phishing simulation program                                                                                                                                                           | Low                  |
| *RS.CO-2*     | Incidents are reported consistent with established criteria                                                            | 1                       | Informal processes, limited automationVoluntary information sharing with external stakeholders to enhance broader cybersecurity situational awareness is minimal at FinSecure Bank.                                                                                                | Low                  |
| *RS.CO-3*     | Information is shared consistent with response plans                                                                   | 2                       | Information sharing at FinSecure Bank is partially aligned with response plans. While incidents are documented and regulatory notifications are performed, the response processes are informal, with limited automation and inconsistent employee training.                        | Low                  |
| *RS.CO-4*     | Coordination with stakeholders occurs consistent with response plans                                                   | 2                       | Coordination with stakeholders at FinSecure Bank is partially consistent with response plans. While there is evidence of communication with regulators and customers during incidents, the incident response processes are informal, and third-party coordination is limited.      | Low                  |
| *RS.CO-5*     | Voluntary information sharing occurs with external stakeholders to achieve broader cybersecurity situational awareness | 1                       | Voluntary information sharing with external stakeholders to enhance broader cybersecurity situational awareness is minimal at FinSecure Bank. The document does not mention participation in industry threat intelligence sharing, ISACs, or collaborative cybersecurity networks. | Low                  |

*Communications Assessment Notes:*
- *Key Strengths:* 
- *Major Gaps:* 
- *Priority Actions:* 

---

## *RECOVER Function Assessment*

### *Recovery Planning (RC.RP)*

| *Subcategory* | *Description*                                                    | *Current Score (1-5)* | *Evidence/Justification*                        | *Confidence Level* |
| --------------- | ------------------------------------------------------------------ | ----------------------- | ------------------------------------------------- | -------------------- |
| *RC.RP-1*     | Recovery plan is executed during or after a cybersecurity incident | 4                       | There is a Solid Backup procedures and DR testing | High                 |

*Recovery Planning Assessment Notes:*
- *Key Strengths:* Response plans are executed during or after incidents, showing awareness and reactive capability.
- *Major Gaps:* Execution is informal, lacks automation, and there is no evidence of structured procedures or rehearsed workflows.
- *Priority Actions:* Formalize response plans, automate key response steps where possible, and conduct regular drills to ensure consistent execution during incidents.

---

## *Current State Summary*

### *Function-Level Averages:*

| *Function* | *Average Score* | *Number of Subcategories* | *Confidence Level* |
|--------------|-------------------|------------------------------|----------------------|
| *IDENTIFY* | __ | 23 | __ |
| *PROTECT* | __ | 25 | __ |
| *DETECT* | __ | 13 | __ |
| *RESPOND* | __ | 16 | __ |
| *RECOVER* | __ | 5 | __ |
| *OVERALL* | __ | 82 | __ |

### *Key Findings:*

#### *Top 3 Strongest Areas:*
1. ___________
2. ___________
3. ___________

#### *Top 5 Weakest Areas (Biggest Gaps):*
1. ___________
2. ___________
3. ___________
4. ___________
5. ___________

#### *Most Critical Findings:*
- *Immediate Concerns (Score 1-2):* 
- *Regulatory Compliance Risks:* 
- *Business Impact Risks:* 

### *Assessment Confidence Notes:*
- *High Confidence Areas:* 
- *Low Confidence Areas (Need More Information):* 
- *Assumptions Made:* 

---

## *Next Steps*

1. *Review and validate* scores with team members
2. *Identify additional evidence* needed for low-confidence areas
3. *Proceed to Target State Definition* worksheet
4. *Prepare for GAP Analysis* phase

*Team Lead Signature:* ________  
*Date Completed:* ________