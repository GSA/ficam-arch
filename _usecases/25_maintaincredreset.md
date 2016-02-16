---
layout: page_collection
title: 10. Maintain Credential - Reset
collection: usecases
---

When an employee or contractor forgets the shared secret associated with their credential, usually a password or PIN, they can request a reset. This prevents them from having to request a new credential.  

---

![Actors and Systems Key for Images](../../img/usecases/clabelmaintain.png){:align="right"}
![Actors and Systems Key for Images](../../img/usecases/resetkey.png)

**Pre-condition:** An employee has an active, agency-issued credential.

| ![1. Reset Requested](../../img/usecases/reset1.png)  | The individual forgets their password or PIN. They contact their credential manager for a reset.  |
| ![2. Identity Verified](../../img/usecases/reset2.png)  | The credential manager verifies the requestor’s identity. <br/><em> The verification method will vary by agency.</em> |
| ![3. Reset Issued](../../img/usecases/reset3.png)  | The credential manager issues a reset. <br/><em> For example, this could be a temporary password or a security link to a web-based reset form.</em> |
| ![4. User Conducts Resets](../../img/usecases/reset.png)  | The individual resets their password or PIN. |

**Post-condition:** Shared secret is reset and the credential is again ready for use.  

[Click here](../../img/Reset.png) for a consolidated image of this use case.

