---
layout: default
title: 11. Maintain Credential - Renew
collection: usecases
---

When an employee or contractor’s credential expires, they usually have the option to renew it, rather than go through the issuance process again. This use case describes the processes for renewing a credential.
For PIV cards, you can only renew if the card has not already expired.

---

![Actors and Systems Key for Images](../../img/usecases/clabelmaintain.png){:align="right"}
![Actors and Systems Key for Images](../../img/usecases/renewkey.png)

**Pre-condition:** An individual has a credential that has recently expired or will expire soon.

| ![1. Renewal Requested](../../img/usecases/renew1.png)  | An actor requests the individual’s credential be renewed. <br/><em> This actor could be the individual, their supervisor, or a credential manager.</em> |
| ![2. Request Reviewed](../../img/usecases/renew2.png)  | An approval authority reviews the request and verifies the individual qualifies to renew their credential. |
| ![3. New Credential Issued](../../img/usecases/renew3.png)  | If the request is approved, the old credential is revoked and a new one is issued. |
| ![4. New Credential Delivered](../../img/usecases/renew4.png)  | An issuing authority delivers the renewed token to the individual. |

**Post-condition:** Individual has a renewed crendential token ready for use.

[Click here](../../img/Renew.png) for a consolidated image of this use case.

