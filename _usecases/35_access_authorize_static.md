---
layout: default
title: 17. Authorize Access - Static
collection: usecases
---

This use case provides, in detail, the steps for the static method of authorizing access to a protected resource. It stems from the ‘Grant access to a protected resource’ use case and expands on Step 4, ‘Authorization Check.’
Under the static model, an organization provisions users to a set of access entitlements.  Whenever they attempt to access a protected resource, the access control system (ACS) checks their permissions against the resource’s access rules.
This model is typical of Access Control Lists (ACL) and RBAC (role-based access control) systems.

![Actors and Systems Key for Images](../../img/usecases/authorizationlabel.png){:align="right"}
![Actors and Systems Key for Images](../../img/usecases/statickey.png)

**Pre-condition:** Individual’s credential has been authenticated and meets the minimum required level of assurance.   

| ![1. Obtain Identifier](../../img/usecases/static1.png)  | Obtain user’s identifier from user’s authenticated context. |
| ![2. Lookup Access Permissions](../../img/usecases/static2.png)  | Lookup user’s relevant access permissions associated with the resource. |
| ![3. Obtain Access Rules](../../img/usecases/static3.png)  | Obtain resource’s access control rules. |
| ![4. Process Authorization](../../img/usecases/static4.png)  | Evaluate individual’s access permissions against resource’s access control rules. |
| ![5. Access Decision](../../img/usecases/static5.png)  | If the individual has the appropriate access permissions, the ACS grants the individual access to the protected resource. Otherwise, access is denied. |

**Post-condition:** Individual is granted or denied access to the resource.

[Click here](../../img/AuthorizeStatic.png) for a consolidated image of this use case.