---
layout: page_collection
title: Authorize Access - Dynamic
collection: usecases
---

This use case provides, in detail, the steps for the dynamic method of authorizing access to a protected resource. It stems from the ‘Grant access to a protected resource’ use case and expands on Step 4, ‘Authorization Check.’
Under the dynamic model, an organization establishes a set of access policies.  Whenever a user attempts to access a protected resource, the access control system (ACS) evaluates their attributes against those policies. When a user’s attributes change, their access entitlements change dynamically.
This model is typical of ABAC (attribute-based access control) systems.

---

![Actors and Systems Key for Images](../../img/usecases/authorizationlabel.png){:align="right"}
![Actors and Systems Key for Images](../../img/usecases/dynamickey.png)

**Pre-condition:** Individual’s credential has been authenticated and meets the minimum required level of assurance.   

| ![1. Obtain Identifier](../../img/usecases/dynamic1.png)  | Obtain user’s identifier from user’s authenticated context. |
| ![2. Obtain Access Policies](../../img/usecases/dynamic2.png)  | Obtain resource’s access control policies. |
| ![3. Obtain Relevant Attributes](../../img/usecases/dynamic3.png)  | Obtain the attributes needed for the access decision. <br/><em>The attributes needed could be about the individual, the resource, or the environment. </em> |
| ![4. Evaluate Policies](../../img/usecases/dynamic4.png)  | Evaluate collected attribute data against the access control policies. |
| ![5. Access Decision](../../img/usecases/dynamic5.png)  | If the request meets the conditions of the access policies, the ACS grants the individual access to the protected resource. Otherwise, access is denied. |

**Post-condition:** Individual is granted or denied access to the resource.

[Click here](../../img/AuthorizeDynamic.png) for a consolidated image of this use case.
