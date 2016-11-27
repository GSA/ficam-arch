---
layout: default
title: 14. Manage Entitlements
collection: usecases
---

Entitlements management is the process of overseeing and adjusting the access privileges granted to individuals, roles, and groups within an organization. This process is sometimes known as ‘provisioning’ and applies mainly to the “static” model of access management (see the Authorize Access, Static use case).

Managing entitlements happens during design time, before an individual attempts to access protected resources, and an individual’s entitlements must be provisioned before they will be able to access protected resources.

---

![Actors and Systems Key for Images](../../img/usecases/entitlementslabel.png){:align="right"}
![Actors and Systems Key for Images](../../img/usecases/entitlementskey.png)

**Pre-condition:** Individual has an active credential.

| ![1. Request to Create Entitlements](../../img/usecases/entitlements1.png)  | An actor requests to create entitlements for an individual. <br/><em>This actor could be the individual, an administrator, or an automated system, depending on the organization. </em>  |
| ![2. Request Reviewed](../../img/usecases/entitlements2.png)  | The request change is reviewed. <br/><em>Reviewer could be a person or a system that evaluates the request against existing policy. They may be multiple layers of review.</em> |
| ![3. Request Approved](../../img/usecases/entitlements3.png)  | If the requested change is in accordance with policy and the individual has a mission need for access, the request is approved. |
| ![3. Maintain Entitlements](../../img/usecases/entitlements4.png)  | The individual is provisioned with updated access entitlements. Those entitlements are updated and maintained whenever their roles changes.  |

**Post-condition:** The individual has been provisioned entitlements that allow them access to the appropriate resources for their role.  

[Click here](../../img/Entitlements.png) for a consolidated image of this use case.

