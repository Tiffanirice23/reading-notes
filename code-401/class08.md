# Access Control (ACL)

## Reading

### [5 steps to RBAC](https://www.csoonline.com/article/3060780/security/5-steps-to-simple-role-based-access-control.html)

#### What is Role Based Access Control (RBAC) and why do we care?

> RBAC is a crucial component of modern access control and security strategies because it provides a structured and efficient way to manage and enforce access policies. It helps organizations protect their data, systems, and assets by ensuring that users have the right level of access

#### Describe a Role/Permission heirarchy that you might implement using RBAC.

For an online banking application, various roles with specific permissions are defined:

1. Roles:

Customer, Bank Teller, Account Manager

2. Permissions:

- Each role has a predefined set of permissions.

- Permissions become more extensive as roles progress from customers to system administrators.

#### What approach might you take to implement RBAC?

> To implement Role-Based Access Control (RBAC) effectively, organizations should begin by defining their access control objectives and requirements, identifying roles that correspond to job functions, and clearly defining fine-grained permissions for each role. A permission matrix mapping roles to their associated permissions serves as a reference. Users are then assigned roles based on their responsibilities, with the RBAC system integrated into IT systems and applications. Thorough testing, regular reviews, and maintenance are crucial, along with comprehensive training and documentation for users. Monitoring, logging, and incident response procedures help maintain security, and compliance and reporting are simplified through RBAC. Regular auditing and adaptation to organizational changes ensure the system remains robust, and user feedback can lead to continuous improvements. Following this step-by-step approach ensures a structured and effective RBAC implementation for access control and security.

### [wiki - RBAC](https://en.wikipedia.org/wiki/Role-based_access_control)

#### If Authentication is “you are who you say you are,” what is Authorization?

> Basically, “Are you allowed to do the thing you’re asking to do?” In other words, while authentication verifies your identity, authorization determines the actions and resources you are permitted to access or manipulate based on your authenticated identity.

#### Name three primary rules defined for RBAC.

> Three primary rules are defined for RBAC:

1. Role assignment: A subject can exercise a permission only if the subject has selected or been assigned a role.

2. Role authorization: A subject's active role must be authorized for the subject. With rule 1 above, this rule ensures that users can take on only roles for which they are authorized.

3. Permission authorization: A subject can exercise a permission only if the permission is authorized for the subject's active role. With rules 1 and 2, this rule ensures that users can exercise only permissions for which they are authorized.

#### Describe RBAC to a non-technical friend.

> RBAC is like a system that assigns roles such as visitors, librarians, managers, and maintenance workers to people in the library. Each role has its specific tasks and responsibilities. For instance, you wouldn't want a visitor to have the same level of access as a manager or a security guard. RBAC ensures that people in different roles have appropriate access and can do their jobs effectively, maintaining order and security within the library.

## Videos

### [RBAC tutorial](https://www.youtube.com/watch?v=C4NP8Eon3cA)

#### What Are access rights Associated with? The User? or The Role? Explain.

> The RBAC system is associated with the Role, not directly with the User. Users are assigned roles based on their job functions or responsibilities within an organization. Each role is associated with a predefined set of access rights or permissions that outline what actions can be performed and what resources can be accessed by individuals in that role.

#### Access Rights, or Authorization, is activated after a user successfully does what?

> Authorization is activated after the user has proven their identity through authentication. Once a user has successfully authenticated themselves by providing valid credentials (such as a username and password, a fingerprint scan, or a smart card), the system then checks their authorization or access rights to determine what actions they are allowed to perform and what resources they can access.

#### Explain how RBAC might benefit a business.

> RBAC is a valuable tool for businesses looking to improve security, streamline access management, and ensure compliance with regulatory requirements. It not only reduces security risks but also enhances operational efficiency and productivity, making it a crucial component of modern access control and cybersecurity strategies.

## Reflection

#### What are your learning goals after reading and reviewing the [class README?](https://codefellows.github.io/code-401-javascript-guide/curriculum/class-08/)

> I am mainly excited to begin creating front end interfaces! Please take me away from backend.
