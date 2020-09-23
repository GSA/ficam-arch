---
layout: default
title: 8. Accept Federation Assertions
collection: usecases
---

![ICAM Practice Area]({{site.baseurl}}/img/usecases/Federation-AttributeExchange.png){:align="right"}

Federal employees and contractors often need to access protected services managed by other federal agencies. Federation is the means by which an agency can accept authentication assertions and associated identity attributes from systems within their agency and at other agencies. This allows federal employees and contractors from across agencies access protected resources and streamlines the user’s experience.
  
Agencies can pass assertions to share attributes about employees and contractors.

---

## Use Case

In this use case, an employee or contractor from Agency A attempts to access a federated service at Agency B. This use case assumes the employee or contractor already has an account or entitlements to access resources at Agency B, or that they will be provisioned.

For more information about granting access to protected resources, see [Grant Access](../7_grantaccess).

![Icon Key for Use Case Images]({{site.baseurl}}/img/usecases/8-IconKey.png)

| **1. Request access to federated service**<br/>![Request access to federated service]({{site.baseurl}}/img/usecases/8-1.png)  | An Agency A employee or contractor requests access to a federated service at Agency B.<br/>The employee or contractor selects the Agency A authentication service. |
| **2. Redirect to Agency A for authentication**<br/>![Redirect to Agency A for authentication]({{site.baseurl}}/img/usecases/8-2.png)  | The Agency B system redirects the employee or contractor to the Agency A authentication service.<br/>Agency A authenticates the employee or contractor. |
| **3. Perform transparent transaction**<br/>![Perform transparent transaction]({{site.baseurl}}/img/usecases/8-3.png)  | Agency A passes identity attributes and transaction data to Agency B via a signed assertion. |
| **4. Agency B grants access**<br/>![Agency B grants access]({{site.baseurl}}/img/usecases/8-4.png)  | Agency B consumes the assertion data, correlating it with an established account or local identity and makes an access control decision.<br/>The Agency B system redirects the employee or contractor to the federated service. |

## Examples

- I want to allow employees and contractors from other federal agencies, that meet specific requirements, to access some of my agency’s resources, to facilitate cross-government collaboration and information sharing.
- An employee or contractor from Agency A visits a shared service operated by Agency B to service all Federal government users. At the homepage, the employee/contractor selects their Agency A icon and is redirected to their Agency A SSO portal. They log in using their Agency A managed credentials and are redirected back to the Agency B shared service.

## Next Steps

[Authorize access to the protected resource](../7_grantaccess).
