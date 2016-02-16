---
layout: page_collection
title: 7. Create and Issue Level of Assurance 3 Credential
collection: usecases
---

This use case describes the process for creating and issuing a credential at Level of Assurance 3 (LOA3).
A credential token meets LOA3 when it uses multiple factors for authentication (see Authentication Use Case), includes regular online checks that the credential is still valid, and includes strong cryptography.  
LOA3 credentials can be either hardware or software tokens and are recognized as LOA3 strength when paired with identity proofing at LOA3 or LOA4.

---

![Actors and Systems Key for Images](../../img/usecases/clabelissuance.png){:align="right"}
![Actors and Systems Key for Images](../../img/usecases/createloa3key.png)

**Pre-condition:** An individual has the need for an LOA3 credential.

| ![1. Request Issued](../../img/usecases/createloa3s1.png)  | A sponsor requests a credential for the individual. <br/><em> Sponsor should be an official who can verify the individual's need for a credential.</em> |
| ![2. Request Approved](../../img/usecases/createloa3s2.png)  | The approval authority reviews the sponsor’s request. If the request is valid, it is approved.  |
| ![3. Token Generated](../../img/usecases/createloa3s3.png)  | The CSP generates the credential token and assigns it to the individual. <br/><em> Issuer could be a person or a system.</em>  |
| ![4. Token Delivered](../../img/usecases/createloa3s4.png)  | The CSP securely issues token to the individual. <br/><em> Delivery could occur through encrypted email, secure mail, or an authorized in-person issuer.</em> |
| ![5. Token Activated](../../img/usecases/createloa3s5.png)  | The individual is prompted to activate the token and establish a memorized secret. <br/><em> This will later be used to authenticate the individual. It is commonly a PIN or password.</em>  |
| ![6. Functionality Verified](../../img/usecases/createloa3s6.png)  | The individual verifies token functionality through a test system.  |

**Post-condition:** Individual has an activated LOA3 credential ready for use.

[Click here](../../img/LOA3Cred.png) for a consolidated image of this use case.

