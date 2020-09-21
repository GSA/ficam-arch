---
layout: default
title: 5. Issue a Derived Credential
collection: usecases
---

![ICAM Practice Area]({{site.baseurl}}/img/usecases/Credential-Maintenance.png){:align="right"}

A derived credential is a credential derived from an existing credential, with a different form factor (like on a mobile device). Derived credentials have the same IAL as the existing credential, and the same or lower AAL.

When an employee or contractor requires authentication, but cannot leverage an existing credential, they can use a derived credential. To be eligible for a derived credential, the employee or contractor must already have a valid credential with Authenticator Assurance Level (AAL) 2 or 3.

---

![Icon Key for Use Case Images]({{site.baseurl}}/img/usecases/5-IconKey.png)

## Procedure

In this use case, an employee or contractor interacts with the agency services to register or request a derived credential. 

| 1. Initiate the request ![Initiate the request]({{site.baseurl}}/img/usecases/5-1.png)  | A request for identity data is initiated to the identity manager. <br/><em> This identity manager could be a person or system, depending on the organization.</em>  |
| 2. Authenticate the existing credential ![Authenticate the existing credential]({{site.baseurl}}/img/usecases/5-2.png)  | The identity manager identifies relevant sources of data on the individual. <br/><em> Sources could include HR systems, security data, and personal databases.</em>  |
| 3. Generate the derived credential ![Generate the derived credential]({{site.baseurl}}/img/usecases/5-3.png)  | Aggregate identity data to create a complete identity profile.  |

## Examples

- I want to provide an employee or contractor, who has already been issued an enterprise credential, a derived credential so that they can authenticate to enterprise applications.
- An employee or contractor travels quite a bit as part of their job.  Accordingly, they are frequently limited to using a small tablet or their phone to stay connected while on the go. In this case, a derived credential is needed for purposes such as accessing secure agency websites or an agency VPN from their mobile device.

## Next Steps

Assign access entitlements and maintain the credential as necessary.
