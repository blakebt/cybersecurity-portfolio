# Botium Toys: Scope, goals, and risk assessment report

## Scope and goals of the audit

## Scope: The scope of this audit is defined as the entire security program at Botium Toys. This includes their assets like employee equipment and devices, their internal network, and their systems. You will need to review the assets Botium Toys has and the controls and compliance practices they have in place.

## Goals: Assess existing assets and complete the controls and compliance checklist to determine which controls and compliance best practices that need to be implemented to improve Botium Toys’ security posture.

## Current assets

Assets managed by the IT Department include: 

* On-premises equipment for in-office business needs    
* Employee equipment: end-user devices (desktops/laptops, smartphones), remote workstations, headsets, cables, keyboards, mice, docking stations, surveillance cameras, etc.  
* Storefront products available for retail sale on site and online; stored in the company’s adjoining warehouse  
* Management of systems, software, and services: accounting, telecommunication, database, security, ecommerce, and inventory management  
* Internet access  
* Internal network  
* Data retention and storage  
* Legacy system maintenance: end-of-life systems that require human monitoring 

## **Risk assessment**

### Risk description

Currently, there is inadequate management of assets. Additionally, Botium Toys does not have all of the proper controls in place and may not be fully compliant with U.S. and international regulations and standards. 

### Control best practices

The first of the five functions of the NIST CSF is Identify. Botium Toys will need to dedicate resources to identify assets so they can appropriately manage them. Additionally, they will need to classify existing assets and determine the impact of the loss of existing assets, including systems, on business continuity.

### Risk score

On a scale of 1 to 10, the risk score is 8, which is fairly high. This is due to a lack of controls and adherence to compliance best practices.

### Additional comments

The potential impact from the loss of an asset is rated as medium, because the IT department does not know which assets would be at risk. The risk to assets or fines from governing bodies is high because Botium Toys does not have all of the necessary controls in place and is not fully adhering to best practices related to compliance regulations that keep critical data private/secure. Review the following bullet points for specific details:

* Currently, all Botium Toys employees have access to internally stored data and may be able to access cardholder data and customers’ PII/SPII.  
* Encryption is not currently used to ensure confidentiality of customers’ credit card information that is accepted, processed, transmitted, and stored locally in the company’s internal database.   
* Access controls pertaining to least privilege and separation of duties have not been implemented.  
* The IT department has ensured availability and integrated controls to ensure data integrity.  
* The IT department has a firewall that blocks traffic based on an appropriately defined set of security rules.  
* Antivirus software is installed and monitored regularly by the IT department.   
* The IT department has not installed an intrusion detection system (IDS).  
* There are no disaster recovery plans currently in place, and the company does not have backups of critical data.   
* The IT department has established a plan to notify E.U. customers within 72 hours if there is a security breach. Additionally, privacy policies, procedures, and processes have been developed and are enforced among IT department members/other employees, to properly document and maintain data.  
* Although a password policy exists, its requirements are nominal and not in line with current minimum password complexity requirements (e.g., at least eight characters, a combination of letters and at least one number; special characters).   
* There is no centralized password management system that enforces the password policy’s minimum requirements, which sometimes affects productivity when employees/vendors submit a ticket to the IT department to recover or reset a password.  
* While legacy systems are monitored and maintained, there is no regular schedule in place for these tasks and intervention methods are unclear.  
* The store’s physical location, which includes Botium Toys’ main offices, store front, and warehouse of products, has sufficient locks, up-to-date closed-circuit television (CCTV) surveillance, as well as functioning fire detection and prevention systems.

## **Controls assessment**

| Administrative Controls |  |  |  |
| ----- | :---- | :---- | :---- |
| **Control name** | **Control type and explanation** | **Needs to be implemented (X)** | **Priority** |
| Least privilege | Preventative; bolster confidentiality by only allowing employees that need access to customer PII/SPII have access | X | High |
| Separation of duties | Preventative; Reduce risk by ensuring that all critical actions require multiple people. Helping keep employees accountable for important information | X | High |
| Disaster recovery plans | Corrective; Ensure business continuity by establish recovery plans in the event of breach | X | High |
| Password policies | Preventative; Establish effective password strength rules for improved security. Reduce the risk of account compromise from simple attacks like Brute force techniques | X | High |

|  Technical Controls |  |  |  |
| ----- | :---- | :---- | :---- |
| **Control name** | **Control type and explanation** | **Needs to be implemented (X)** | **Priority** |
| Encryption | Deterrent; Ensures confidential data is more secure | X | High/Medium |
| Intrusion Detection System (IDS) | Detective; allows IT to identify potential intrusions more quickly. | X | High |
| Backups | Corrective; In the event of a breach backups ensure that data can be restored/recovered. | X | High |
| Password management | Preventative; Help contribute to business continuity by establishing a system that will manage password resets while enforcing established password strength rules. | X | Medium |
| Manual monitoring, maintenance, and intervention | Preventative; Establish a schedule for legacy system maintenance and monitoring to ensure that these older systems do not pose a risk to security | X | High |

## 

## 

## **Compliance Checklist**

- [ ] **National Institute of Standards and Technology Cybersecurity Framework (NIST CSF)**

	  
	NIST CSF is a framework that provides standards, guidelines, and best practices     to manage risk. They  provide 5 core functions that help do this. Identify, Protect, Detect, Respond, and Recover. 

	**Explanation:** The organization expressed an interest in complying with the NIST CSF. In order to be in compliance we will need to address the lack of appropriate managed assets. We must classify all assets and determine the impact of loss of these assets to business continuity.

- [ ] **Payment Card Industry Data Security Standard (PCI DSS)**

	PCI DSS is an international security standard meant to ensure that organizations storing, accepting, processing, and transmitting credit card information do so in a secure environment.

	**Explanation:** The organization must adhere to PCI DSS because we accept, process, and store credit card information both in person and online.

- [ ] **General Data Protection Regulation (GDPR)**

	GDPR is a European Union (EU) general data regulation that protects the processing of EU citizens’ data and their right to privacy in and out of the EU. Citizens of the EU must be notified of a breach, if their data has been compromised, within 72 hours of the incident. 

	**Explanation:** As the organization is interested in supporting their online market worldwide and will collect personal information from people in the EU, we must adhere to GDPR.

## **Recommendations**

Many administrative and technical controls must be implemented to improve the organization’s security posture. These controls include: Least privilege, Separation of duties, Disaster recovery plans, Password policies, Encryption, Intrusion Detection System (IDS), backups, password management, and legacy system monitoring and maintenance. 

The organization is currently out of compliance with NIST CSF, PCI DSS, and GDPR. In order to be in compliance the organization must classify assets and identify the impacts of the loss of these assets on business continuity. The organization must also implement Least privilege, separation of duties, and encryption to protect sensitive personally identifiable information. 

## 