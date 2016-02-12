---
layout: page_collection
title: Create and Issue Derived PIV
collection: usecases
---
When a federal employee or contractor requires PIV authentication, but using their PIV card is not practical, using a derived PIV may be an option. A derived PIV is a secure, reliable, federally issued credential issued to a mobile device, generally a smartphone or tablet, that allows an individual to use their mobile device in place of their PIV card. An individual must first have been issued a PIV card in order to be eligible for a derived PIV.

A derived PIV can be either LOA3 or LOA4. An LOA3 derived PIV uses either software or hardware to connect with a mobile device, whereas an LOA4 derived PIV must be a hardware token.

![Actors and Systems Key for Images](../../img/usecases/clabelissuance.png){:align="right"}
![Actors and Systems Key for Images](../../img/usecases/derivedkey.png)

**Pre-condition:** An individual has a mobile device and an existing PIV credential.

| ![1. Request Issued](../../img/usecases/derived1.png)  | An individual requests a derived PIV from an approved authority. |
| ![2. Request Approved](../../img/usecases/derived2.png)  | The approval authority reviews the request. If valid, it is approved. |
| ![3. Authentication](../../img/usecases/derived3.png)  | The individual contacts a CSP that provides derived PIVs and is authenticated using their PIV card. <br/><em> Authentication may occur virtually (LOA3) or in person (LOA3 & LOA4).</em>  |
| ![4. Token Generated](../../img/usecases/derived4.png)  | The CSP generates the credential token and securely issues it to the individual. <em>The issuer could be a person or a system.</em> |
| ![5. Token Issued](../../img/usecases/derived5.png)  | The credential is securely issued to the individual’s mobile device.  |
| ![6. Token Activated](../../img/usecases/derived6.png)  | The individual is prompted to activate the token by establishing a shared secret.  |
| ![7. Functionality Verified](../../img/usecases/derived7.png)  | The individual verifies token functionality through a test system.  |

**Post-condition:** Individual has an activated derived PIV credential that is ready for use.

[Click here](../../img/Derived.png) for a consolidated image of this use case.

