---
layout: default
title: Code 401 | Class 08
parent: Code 401 Notes
---

## Reading: Access Control (ACL)

[5 steps to RBAC](https://www.csoonline.com/article/3060780/security/5-steps-to-simple-role-based-access-control.html)

### What is Role Based Access Control (RBAC) and why do we care?

RBAC is used to manage access and is important that the correct information is displayed correctly to the authorized user
Describe a Role/Permission heirarchy that you might implement using RBAC.

One role that you could implement would be a user vs an administrator role. The user role would be limited in regards to authorization when compared to the administrator

### What approach might you take to implement RBAC?

I would analyze the need for access to certain app features and then would develop roles based off of those needs.

[wiki - RBAC](https://en.wikipedia.org/wiki/Role-based_access_control)

### If Authentication is “you are who you say you are,” what is Authorization?

Authorization allows you to view, manage or interact with curated data based off of your allowed access.

### Name three primary rules defined for RBAC

* Role assignment: A subject can exercise a permission only if the subject has selected or been assigned a role.

* Role authorization: A subject's active role must be authorized for the subject. With rule 1 above, this rule ensures that users can take on only roles for which they are authorized.

* Permission authorization: A subject can exercise a permission only if the permission is authorized for the subject's active role. With rules 1 and 2, this rule ensures that users can exercise only permissions for which they are authorized.

### Describe RBAC to a non-technical friend

RBAC is used throughout our daily lives. An easy example would be employees at some facility that contains secured areas that require the proper authentication and authorization in order to access.  

Videos [RBAC tutorial](https://www.youtube.com/watch?v=C4NP8Eon3cA)

### What Are access rights Associated with? The User? or The Role? Explain

Access rights are associated with the role. The system administrator will breakdown the system and decide what rolls require specific access rights.

### Access Rights, or Authorization, is activated after a user successfully does what?

This is what happens after a user successfully authenticates themselves within the specific system

### Explain how RBAC might benefit a business

RBAC can increase security by implementing some type of vetting process that is required in order to gain access to more sensitive information. This also allows new employees to come into the business and fall immediately into the designated roll for their employment type.
