This project demonstrates the end-to-end implementation of identity and access management across a hybrid environment using Microsoft Entra ID.

It covers the complete administrative workflow, including user onboarding, access provisioning, group and policy management, password and security controls, and handling real-world scenarios such as account recovery, user offboarding, and data protection. The objective is to simulate how modern organizations manage users, enforce security, and maintain operational efficiency through centralized admin systems.

**To implement a centralized identity and access management system ensuring:**

1. Secure user onboarding
2. Role-based access control (RBAC)
3. Prevention of unauthorized access


**🛠️ Tools & Technologies**

1. Microsoft Azure Portal
2. Microsoft Entra ID (Azure Active Directory)
3. Role-Based Access Control (RBAC)


**🏢 Scenario**

A growing organization needed a secure and structured user management system to handle onboarding, access control, and role-based permissions for employees.

**⚙️ THE EXECUTION:**

This section covers real-world user lifecycle management scenarios commonly encountered in corporate environments, along with their handling from an IT Support perspective using **“Microsoft Entra ID”**. 

1. Provisioning **Enterprise Identities & Managing User** Lifecycles:

Initialized and deployed standard corporate user profiles within the centralized cloud directory to establish secure digital identities. This layout structures baseline account configurations, attributes management, and initial access logging for incoming organizational personnel.

<img width="1412" height="481" alt="image" src="https://github.com/user-attachments/assets/65bf1888-9245-4dec-b633-3913a8610b69" />

I've created created 2 New Users by All Users -> New Users -> Adding Details -> Creating New users


2. Deploying Emergency **Break-Glass Controls** for Infrastructure Redundancy:

Configured a highly privileged emergency recovery account assigned to the Global Administrator role to prevent total tenant lockout during primary system failures. This profile was strategically excluded from conditional multi-factor authentication (MFA) loops to maintain a resilient, secondary administrative access pathway during carrier network or cellular authentication outages. 

<img width="1026" height="620" alt="image" src="https://github.com/user-attachments/assets/4882642b-c1a7-460a-9571-1db091573735" />

This Admin account was created with "Global Administrator" access to encounter **"complete lock out"** situation.

<img width="1374" height="752" alt="image" src="https://github.com/user-attachments/assets/cf971499-9979-4480-b363-98cc5c7b73e3" />
<img width="1294" height="711" alt="image" src="https://github.com/user-attachments/assets/b311fe7c-0973-4da7-81c2-0b9e4f02bf81" />



3. Bulk User Provisioning using **CSV Automation**:

Created and onboarded multiple user accounts efficiently by importing structured CSV files into the directory infrastructure, enabling rapid deployment of employee identities with consistent attribute configuration and reduced manual effort.

<img width="1345" height="422" alt="image" src="https://github.com/user-attachments/assets/ab608a71-e373-4032-9d13-c468c6afa1e8" />


4. Enforcing **Role-Based Access Control (RBAC)** via Group Ownership Delegations:
   
Delegated administrative management permissions by assigning specific users as Group Owners, enabling decentralized policy management without violating the Principle of Least Privilege.

<img width="1388" height="839" alt="image" src="https://github.com/user-attachments/assets/9ca511cc-05d0-4da6-b884-f4d1dc59c206" />


<img width="1387" height="866" alt="image" src="https://github.com/user-attachments/assets/f3b3f921-bb37-4a73-a6f0-1a4042e2f88c" />

5. Executing User Offboarding Protocols & Lifecycle Deprovisioning:

Managed the secure exit of personnel by executing enterprise offboarding workflows, completely deprovisioning cloud identities, and deleting system profiles to prevent unauthorized post-employment access.

<img width="1389" height="859" alt="image" src="https://github.com/user-attachments/assets/675334e3-d486-4cf7-ab38-1b20e4c2a1b8" />

6. Mitigating Active Cyber Threats via **Global Session Revocation**:

Initiated immediate incident response protocols to counter active credential theft or session hijacking threats. Executed a global session revocation via the administrative console, instantly invalidating active browser cookies and OAuth tokens to lock out unauthorized actors while preserving system integrity.

<img width="1393" height="486" alt="image" src="https://github.com/user-attachments/assets/5aae2041-1e70-4505-86c4-bf88a3c53a02" />

7. Executing **Post-Offboarding** Forensic Audits & User Log Analysis:

Processed formal organizational data requests to conduct security and compliance audits on deprovisioned corporate assets. Extracted and analyzed directory sign-in logs, audit trails, and data access events from the tenant repository to ensure absolute regulatory alignment and detect post-termination anomalies.

<img width="1392" height="839" alt="image" src="https://github.com/user-attachments/assets/489adfef-c13b-4435-a60c-a39972c48032" />

8. Enforcing Targeted **Multi-Factor Authentication (MFA)**:

Deployed rigorous identity verification safeguards across target corporate profiles to eliminate perimeter credential vulnerabilities. Configured explicit per-user authentication baselines and conditional verification loops within the admin center to ensure only validated personnel can establish authorized cloud connections.

<img width="1346" height="670" alt="image" src="https://github.com/user-attachments/assets/58dec228-f066-4769-8488-ea09b48e7064" />



**📊 Result:**

1. Reduced employee account provisioning and onboarding times by automating identity ingestion loops.
2. Enforced a strict Least Privilege standard across all organizational departments, reducing internal data-exposure risks.
3. Established a resilient emergency disaster recovery protocol to ensure 100% tenant availability.
