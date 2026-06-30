**🎯 The Objective:**

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

1. Created Two users called **“Raj.E”** & **“Anand Kumar”**

<img width="1412" height="481" alt="image" src="https://github.com/user-attachments/assets/65bf1888-9245-4dec-b633-3913a8610b69" />

I've created created 2 New Users by All Users -> New Users -> Adding Details -> Creating New users


2. Creating a **“Break Glass Admin”** user with Global Admin access and disabled MFA: 

<img width="1026" height="620" alt="image" src="https://github.com/user-attachments/assets/4882642b-c1a7-460a-9571-1db091573735" />

This Admin account was created with "Global Administartor" access to encounter **"complete lock out"** situation.

<img width="1374" height="752" alt="image" src="https://github.com/user-attachments/assets/cf971499-9979-4480-b363-98cc5c7b73e3" />
<img width="1294" height="711" alt="image" src="https://github.com/user-attachments/assets/b311fe7c-0973-4da7-81c2-0b9e4f02bf81" />



3. Performing Bulk Actions [Creatings users in bulk with **"CreateUsersTemplate.csv"**]

<img width="1345" height="422" alt="image" src="https://github.com/user-attachments/assets/ab608a71-e373-4032-9d13-c468c6afa1e8" />



