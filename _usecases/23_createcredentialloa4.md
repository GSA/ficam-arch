---
layout: page_collection
title: Create and Issue Level of Assurance 4 Credential
collection: usecases
---

This use case describes the process for creating and issuing a credential at Level of Assurance 4 (LOA4).  
A credential token meets LOA4 when it uses multiple factors for authentication (see Authentication Use Case), includes regular online checks that the credential is still valid, and includes a strong cryptographic module.  
LOA4 tokens are exclusively hardware-based and are recognized as LOA4 strength only when paired with identity proofing at LOA4.  

---

![Actors and Systems Key for Images](../../img/usecases/clabelissuance.png){:align="right"}
![Actors and Systems Key for Images](../../img/usecases/createloa4key.png)

**Pre-condition:** An individual has the need for an LOA4 credential.

| ![1. Request Issued](../../img/usecases/createloa4s1.png)  | A sponsor requests a credential for the individual. <br/><em> Sponsor should be an official who can verify the individual's need for a credential.</em> |
| ![2. Request Approved](../../img/usecases/createloa4s2.png)  | The approval authority reviews the sponsor’s request. If the request is valid, it is approved. <br/><em> Review and approval could require a background investigation.</em> |
| ![3. Token Generated](../../img/usecases/createloa4s3.png)  | The CSP generates the credential token and digitally assigns it to the requested individual.  |
| ![4. Token Delivered](../../img/usecases/createloa4s4.png)  | The registrar verifies the individual's identity using biometric data, then delivers the token.  |
| ![5. Token Activated](../../img/usecases/createloa4s5.png)  | The registrar prompts the individual to activate the token and establish a memorized secret.  |
| ![6. Functionality Verified](../../img/usecases/createloa4s6.png)  | The individual verifies token functionality through a test system.  |

**Post-condition:** Individual has an activated LOA4 credential ready for use.

[Click here](../../img/LOA4Cred.png) for a consolidated image of this use case.

