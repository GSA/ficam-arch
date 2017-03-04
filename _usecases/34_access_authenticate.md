---
layout: default
title: 16. Authenticate a User
collection: usecases
---

This use case describes, in detail, the steps for authenticating a user who has requested access to a protected resource. It stems from the ‘Grant access to a protected resource’ use case and expands on Step 3, ‘Verify authentication factors.’
Authentication is the process by which a system verifies the user’s claimed identity to a certain level of assurance (LOA).  LOA1 is the lowest level, and LOA4 is the highest.
There are three types of authentication factors: something you know (such as a password or PIN), something you have (such as a smartcard), and something you are (such as your fingerprint). At LOA3 and LOA4, at least two types of factors are required.

---

![Actors and Systems Key for Images]({{site.baseurl}}/img/usecases/authenticatelabel.png){:align="right"}
![Actors and Systems Key for Images]({{site.baseurl}}/img/usecases/authenticatekey.png)

**Pre-condition:** Individual has attempted to access a resource.  

| ![1. Prompt for Authentication]({{site.baseurl}}/img/usecases/authn1.png)  | The Access Control System (ACS) prompts the individual to provide authentication factor(s). |
| ![2. User Input]({{site.baseurl}}/img/usecases/authn2.png)  | For LOA 2, the individual provides a single authentication factor, usually a PIN or password. For LOA 3 and LOA 4, the individual provides at least two authentication factors.  |
| ![3. Input Verified]({{site.baseurl}}/img/usecases/authn3.png)  | The ACS verifies the user’s input against information about the user’s claimed identity. <br/><em>Each type of factor is authenticated in a different way. </em> |
| ![4. User Authenticated]({{site.baseurl}}/img/usecases/authn4.png)  | If the factors are verified, authentication is successful.  |

**Post-condition:** Individual is successfully or unsuccessfully authenticated. If successful, authorization is the next step. 

[Click here]({{site.baseurl}}/img/Authenticate.png) for a consolidated image of this use case.