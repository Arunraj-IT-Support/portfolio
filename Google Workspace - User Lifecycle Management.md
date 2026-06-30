This project demonstrates the end-to-end implementation of identity and access management across a hybrid environment using Google Workspace.

It covers the complete administrative workflow, including user onboarding, access provisioning, group and policy management, password and security controls, and handling real-world scenarios such as account recovery, user offboarding, and data protection. The objective is to simulate how modern organizations manage users, enforce security, and maintain operational efficiency through centralized admin systems.

**To implement a centralized identity and access management system ensuring:**

Secure user onboarding
Role-based access control (RBAC)
Prevention of unauthorized access

**🛠️ Tools**

Google Admin Console

**🏢 Scenario**

A growing organization needed a secure and structured user management system to handle onboarding, access control, and role-based permissions for employees.

**⚙️ THE EXECUTION:**

This section covers real-world user lifecycle management scenarios commonly encountered in corporate environments, along with their handling from an IT Support perspective using **“Google Workspace Admin Console”**. 

1. Provisioning **Enterprise Identities & Managing User** Lifecycles:

Initialized and deployed standard corporate user profiles within the centralized cloud directory to establish secure digital identities. This layout structures baseline account configurations, attributes management, and initial access logging for incoming organizational personnel.

<img width="819" height="609" alt="image" src="https://github.com/user-attachments/assets/3753aa8d-7b6a-49bf-a674-a7b01c837d56" />

2. **Constructing Directory Trees** for Functional Isolation:

Engineered segmented Parent and Child Organizational Units (OUs) within the Google Workspace directory layout. This deployment systematically isolates corporate teams (e.g., segregating the Sales Team from the Poster Design Team) to restrict lateral data-exposure perimeters.

<img width="1636" height="734" alt="image" src="https://github.com/user-attachments/assets/0e03baed-9cc8-4a2c-83a4-23f0db624473" />

3. Structuring Organizational Unit (OU) Hierarchies & Directory Segmentation:

Provisioned and aligned diverse corporate user profiles into distinct, nested Organizational Units (OUs) based on functional department mandates. This structural segregation enables targeted policy deployment, automates group inherits, and prevents cross-departmental data sprawl by isolating team assets.

<img width="1401" height="584" alt="image" src="https://github.com/user-attachments/assets/18535397-a6be-445c-8c0e-451467d719ac" />

<img width="1389" height="557" alt="image" src="https://github.com/user-attachments/assets/bb9570f1-c7c6-4c6d-8b7e-9bde5f53c82c" />

4. Enforcing Governance via Application Service Overrides:

Regulated corporate asset exposures by enforcing strict domain-wide application blocks. Applied targeted administrative service overrides to disable unapproved or high-risk modules (such as completely turning off Google AI Studio) across restricted organizational units.

<img width="1675" height="732" alt="image" src="https://github.com/user-attachments/assets/31b3d78c-2926-48a9-a9e2-fab435e5719a" />

Granting AI studio access only to design team:

<img width="1670" height="791" alt="image" src="https://github.com/user-attachments/assets/7ac4bdb8-2015-4f4d-9912-80df150795e4" />



