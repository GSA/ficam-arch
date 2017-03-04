---
layout: default
title: 6. Create and Issue Level of Assurance 2 Credential
collection: usecases
---

This use case describes the process for creating and issuing a credential at Level of Assurance 2 (LOA2).
A credential token meets LOA2 when it uses a single factor for authentication (See Authentication use case), mandates a strong PIN or password, and only transmits credential information using cryptographic protection.
LOA2 credentials are usually software tokens and are recognized as LOA2 strength only when paired with identity proofing at LOA2, LOA3, or LOA4.

---

![Actors and Systems Key for Images]({{site.baseurl}}/img/usecases/clabelissuance.png){:align="right"}
![Actors and Systems Key for Images]({{site.baseurl}}/img/usecases/createloa2key.png)

**Pre-condition:** An individual has the need for an LOA2 credential.

| ![1. Request Issued]({{site.baseurl}}/img/usecases/createloa2s1.png)  | The individual requests an LOA2 credential token from a Credential Service Provider (CSP).  |
| ![2. Request Approved]({{site.baseurl}}/img/usecases/createloa2s2.png)  | The CSP reviews the individual’s request. If the request is valid, it is approved.  |
| ![3. Token Established]({{site.baseurl}}/img/usecases/createloa2s3.png)  | The individual establishes a shared secret. <br/><em> This will later be used to authenticate the individual. It is commonly a PIN or password.</em>  |
| ![4. Functionality Verified]({{site.baseurl}}/img/usecases/createloa2s4.png)  | The individual verifies token functionality through a test system.  |

**Post-condition:** Individual has an activated LOA2 credential ready for use.

[Click here]({{site.baseurl}}/img/LOA2Cred.png) for a consolidated image of this use case.
