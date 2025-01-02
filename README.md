<h1>Conduct A Security Audit</h1>


<h2>Description</h2>
	Project consists of conducting a security audit on a fictional toy company, Botium Toys.
<br />
<br />

**Scenario:**


Botium Toys is a small U.S. business that develops and sells toys. The business has a single physical location, which serves as their main office, a storefront, and warehouse for their products. However, Botium Toy’s online presence has grown, attracting customers in the U.S. and abroad. As a result, their information technology (IT) department is under increasing pressure to support their online market worldwide. 

The manager of the IT department has decided that an internal IT audit needs to be conducted. She's worried about maintaining compliance and business operations as the company grows without a clear plan. She believes an internal audit can help better secure the company’s infrastructure and help them identify and mitigate potential risks, threats, or vulnerabilities to critical assets. The manager is also interested in ensuring that they comply with regulations related to internally processing and accepting online payments and conducting business in the European Union (E.U.).   

The IT manager starts by implementing the National Institute of Standards and Technology Cybersecurity Framework (NIST CSF), establishing an audit scope and goals, listing assets currently managed by the IT department, and completing a risk assessment. The goal of the audit is to provide an overview of the risks and/or fines that the company might experience due to the current state of their security posture.

Your task is to review the IT manager’s scope, goals, and risk assessment report. Then, perform an internal audit by completing a controls and compliance checklist. </p>
<br />


<h2>Scope, Goals, and Risk Assessment Report:</h2>

### **Scope:** 
The scope of this audit is defined as the entire security program at Botium Toys. This includes their assets like employee equipment and devices, their internal network, and their systems. You will need to review the assets Botium Toys has and the controls and compliance practices they have in place.

### **Goals:**
Assess existing assets and complete the controls and compliance checklist to determine which controls and compliance best practices that need to be implemented to  improve Botium Toys’ security posture.

### **Current assets:**

Assets managed by the IT Department include: 

* On-premises equipment for in-office business needs  
* Employee equipment: end-user devices (desktops/laptops, smartphones), remote workstations, headsets, cables, keyboards, mice, docking stations, surveillance cameras, etc.
* Storefront products available for retail sale on site and online; stored in the company’s adjoining warehouse
* Management of systems, software, and services: accounting, telecommunication, database, security, ecommerce, and inventory management
* Internet access
* Internal network
* Data retention and storage
* Legacy system maintenance: end-of-life systems that require human monitoring 

### **Risk Assessment:**
Currently, there is inadequate management of assets. Additionally, Botium Toys does not have all of the proper controls in place and may not be fully compliant with U.S. and international regulations and standards. Botium Toys will need to dedicate resources to identify assets so they can appropriately manage them. Additionally, they will need to classify existing assets and determine the impact of the loss of existing assets, including systems, on business continuity. 

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

<h2>Controls and compliance checklist</h2>

Select “yes” or “no” to answer the question: Does Botium Toys currently have this control in place? 

![image](https://github.com/user-attachments/assets/ca414abe-322f-463b-96a7-2d12f570404a)


Select “yes” or “no” to answer the question: Does Botium Toys Does Botium Toys currently adhere to this compliance best practice?

![image](https://github.com/user-attachments/assets/8b6aacd4-f65e-4d09-b907-6d9639708673)
![image](https://github.com/user-attachments/assets/39a67061-cd15-4e81-8c03-fb4f67d4ee86)
![image](https://github.com/user-attachments/assets/fbe0a503-8913-4ecf-b59a-acc7b101afef)

<h2>Recommendations</h2>

Based on the assessment, here are my recommendations. 

_**Data Encryption:**_ Implement encryption for all sensitive customer data, including credit card information, both during transmission and when stored in the company's internal database. This ensures compliance with PCI-DSS and protects against data breaches.
<b />

_**Secure Data Storage:**_ Store all sensitive data in secure environments with access controls based on the principle of least privilege. Regularly review and classify assets to assess the impact of potential losses on business continuity.
<b />

_**Password Management:**_ Enforce a comprehensive password policy with higher complexity requirements (e.g., at least 8 characters, a combination of letters, numbers, and special characters). Implement a centralized password management system to reduce fatigue and ensure strong, unique passwords for all employees and vendors.
<b />

_**Access Control:**_ Implement strict access controls, including least privilege and separation of duties, to limit access to sensitive systems and data to authorized personnel only. Conduct periodic access reviews to ensure compliance.
<b />

_**Disaster Recovery Plan:**_ Develop and implement a disaster recovery and business continuity plan, including secure backups of critical data and procedures for restoring operations following a security incident. Regularly test backups to ensure reliability.
<b />

_**Intrusion Detection System (IDS):**_ Install and configure an intrusion detection system (IDS) to actively monitor the network for signs of malicious activity, integrated with a Security Information and Event Management (SIEM) system for real-time alerting.
<b />

_**Legacy System Management:**_ Establish a regular maintenance and monitoring schedule for legacy systems. Define clear intervention methods to ensure legacy systems do not present unnecessary risks.
<b />

_**Ongoing Security Audits:**_ Regularly conduct security audits, vulnerability assessments, and penetration testing to identify weaknesses in the network, systems, and processes. Implement proactive measures to address emerging threats.
<b />

_**Compliance with Regulations:**_ Review and update all security policies and procedures to align with U.S. and international regulations, such as GDPR and PCI-DSS, ensuring that privacy and security measures are in place to protect customer data.

