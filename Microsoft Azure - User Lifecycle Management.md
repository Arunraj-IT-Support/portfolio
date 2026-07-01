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

1. Creating and **Managing User Accounts**:

Created and configured new user accounts in the Entra ID directory. I set up these digital identities by navigating to **All Users > New User > Creating New users**, filling in the necessary profile details, and establishing their core accounts so new hires can log in securely.

<img width="1412" height="481" alt="image" src="https://github.com/user-attachments/assets/65bf1888-9245-4dec-b633-3913a8610b69" />


2. Setting Up Emergency **Break-Glass Accounts**:

Created a highly privileged emergency recovery account with the Global Administrator role to prevent a total tenant lockout scenario. This account is intentionally excluded from multi-factor authentication (MFA) policies to ensure IT can still access the environment if primary authentication services or cellular networks go down.

<img width="1026" height="620" alt="image" src="https://github.com/user-attachments/assets/4882642b-c1a7-460a-9571-1db091573735" />

This Admin account was created with "Global Administrator" access to encounter **"complete lock out"** situation.

<img width="1374" height="752" alt="image" src="https://github.com/user-attachments/assets/cf971499-9979-4480-b363-98cc5c7b73e3" />

<img width="1294" height="711" alt="image" src="https://github.com/user-attachments/assets/b311fe7c-0973-4da7-81c2-0b9e4f02bf81" />



3. Bulk User Provisioning using **CSV Automation**:

Onboarded multiple employee accounts simultaneously by importing a structured CSV file into Entra ID. This method reduces manual data entry, speeds up the provisioning process, and ensures all user profiles have consistent attributes from day one.

<img width="1345" height="422" alt="image" src="https://github.com/user-attachments/assets/ab608a71-e373-4032-9d13-c468c6afa1e8" />


4. Delegating **Role-Based Access (RBAC)** via Group Ownership:
   
Assigned specific users as Group Owners within the system. This delegates day-to-day management tasks to department heads or team leads, allowing them to manage their own group memberships without giving them full administrative roles over the entire directory.

<img width="1388" height="839" alt="image" src="https://github.com/user-attachments/assets/9ca511cc-05d0-4da6-b884-f4d1dc59c206" />


<img width="1387" height="866" alt="image" src="https://github.com/user-attachments/assets/f3b3f921-bb37-4a73-a6f0-1a4042e2f88c" />

5. Managing **Employee Offboarding and Account Deletion**:

Handled the secure departure of personnel by executing offboarding protocols. This involved removing the user's active cloud access and permanently deleting their profile from the directory to protect corporate data and prevent post-employment access risks.

<img width="1389" height="859" alt="image" src="https://github.com/user-attachments/assets/675334e3-d486-4cf7-ab38-1b20e4c2a1b8" />

6. **Revoking Active Sessions** for Security Incidents:

Demonstrated incident response by using the global sign-out feature to instantly revoke active login sessions. This action immediately invalidates all active browser cookies and token connections for an account, locking out unauthorized users in the event of credential theft or a hijacked session.

<img width="1393" height="486" alt="image" src="https://github.com/user-attachments/assets/5aae2041-1e70-4505-86c4-bf88a3c53a02" />

7. Executing **Post-Offboarding** Forensic Audits & User Log Analysis:

Processed formal organizational data requests to conduct security and compliance audits on deprovisioned corporate assets. Extracted and analyzed directory sign-in logs, audit trails, and data access events from the tenant repository to ensure absolute regulatory alignment and detect post-termination anomalies.

<img width="1392" height="839" alt="image" src="https://github.com/user-attachments/assets/489adfef-c13b-4435-a60c-a39972c48032" />

8. Enforcing **Multi-Factor Authentication (MFA)**:

Set up security safeguards across user profiles to prevent weak-password vulnerabilities. Configured targeted multi-factor authentication baselines in the admin panel to ensure that users must provide a secondary verification method before connecting to corporate cloud apps.

<img width="1346" height="670" alt="image" src="https://github.com/user-attachments/assets/58dec228-f066-4769-8488-ea09b48e7064" />



**📊 Result:**

1. Reduced employee account provisioning and onboarding times by automating identity ingestion loops.
2. Enforced a strict Least Privilege standard across all organizational departments, reducing internal data-exposure risks.
3. Established a resilient emergency disaster recovery protocol to ensure 100% tenant availability.
