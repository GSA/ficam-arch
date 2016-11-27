---
layout: default
title: 12. Maintain Credential - Revoke
collection: usecases
---

When an employee or contractor separates from an agency or no is eligible for their credential, their credential should be revoked. This use case describes the process for revoking a credential.

---

![Actors and Systems Key for Images](../../img/usecases/clabelmaintain.png){:align="right"}
![Actors and Systems Key for Images](../../img/usecases/renewkey.png)

**Pre-condition:** Individual has an active credential.

| ![1. Separation Notification](../../img/usecases/revoke1.png)  | An actor sends separation notification to the credential manager. <br/><em> Actor could range from the individual to their supervisor, HR, or security team member.</em> |
| ![2. Credential Disabled](../../img/usecases/revoke2.png)  | The credential manager invalidates the credential and disables its access provisions. <br/><em>The credential manager could be a person or a system.</em> |
| ![3. Credential Collected](../../img/usecases/revoke3.png)  | An actor collects the credential if it is a hardware token. <br/><em>Actor could be supervisor, HR, or a security team member. </em> |

**Post-condition:** Individual no longer has access via that credential.

[Click here](../../img/Revoke.png) for a consolidated image of this use case.

