---
layout: page_collection
title: Manage Entitlements
collection: usecases
---

Entitlements management is the process of overseeing and adjusting the access privileges granted to individuals, roles, and groups within an organization. This process is sometimes known as ‘provisioning’ and applies mainly to the “static” model of access management (see the Authorize Access, Static use case).

Managing entitlements happens during design time, before an individual attempts to access protected resources, and an individual’s entitlements must be provisioned before they will be able to access protected resources.

---

![Actors and Systems Key for Images](../../img/usecases/entitlementslabel.png){:align="right"}
![Actors and Systems Key for Images](../../img/usecases/entitlementskey.png)

**Pre-condition:** Individual has an active credential.

| ![1. Separation Notification](../../img/usecases/revoke1.png)  | An actor sends separation notification to the credential manager. <br/><em> Actor could range from the individual to their supervisor, HR, or security team member.</em> |
| ![2. Credential Disabled](../../img/usecases/revoke2.png)  | The credential manager invalidates the credential and disables its access provisions. <br/><em>The credential manager could be a person or a system.</em> |
| ![3. Credential Collected](../../img/usecases/revoke3.png)  | An actor collects the credential if it is a hardware token. <br/><em>Actor could be supervisor, HR, or a security team member. </em> |
| ![3. Credential Collected](../../img/usecases/revoke3.png)  | An actor collects the credential if it is a hardware token. <br/><em>Actor could be supervisor, HR, or a security team member. </em> |

**Post-condition:** Individual no longer has access via that credential.

[Click here](../../img/Entitlements.png) for a consolidated image of this use case.

