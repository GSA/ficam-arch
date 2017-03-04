---
layout: default
title: 15. Grant Access to a Protected Resource
collection: usecases
---
This use case provides a high level overview of how an individual accesses a protected resource. It describes the process for accessing both logical resources, like systems and files, and physical resources, like facilities. In practice, the implementation of logical and physical access may differ.
For more information about:

* Authentication - please see Authenticate a User.
* Static and dynamic authorization - please see Authorize Access (Static) and Authorize Access (Dynamic).
* Access policy administration and entitlements management - please see Administer Digital Access Policies and Manage Entitlements.

![Actors and Systems Key for Images]({{site.baseurl}}/img/usecases/accesslabel.png){:align="right"}
![Actors and Systems Key for Images]({{site.baseurl}}/img/usecases/accesskey.png)

**Pre-condition:** Individual has a digital identity record and credential, and the individual has been associated with access entitlements.  

| ![1. Access Attempt]({{site.baseurl}}/img/usecases/grant1.png)  | Individual attempts to access a protected resource. |
| ![2. Present Credential]({{site.baseurl}}/img/usecases/grant2.png)  | Individual presents a credential that meets the minimum required level of assurance. |
| ![3. Verify Authentication Factors]({{site.baseurl}}/img/usecases/grant3.png)  | The Access Control System (ACS) authenticates the individual using necessary authentication factors. <br/><em>LOAs 1/2 - one factor required; LOAs 3/4 – at least two factors required.</em> |
| ![4. Authorization Check]({{site.baseurl}}/img/usecases/grant4.png)  | If authentication is successful, the ACS checks the individual against the resource’s access parameters.  <br/><em> This check might include gathering additional attributes about the individual to make an access decision.</em> |
| ![5. Access Decision]({{site.baseurl}}/img/usecases/grant5.png)  | If the individual matches the resource’s access parameters, the ACS grants access to the protected resource. |
| ![6. Log Access Activity]({{site.baseurl}}/img/usecases/grant6.png)  | The ACS creates a log of the access attempt, the user, and the decision for auditing and review purposes. |

**Post-condition:** Individual is granted or denied access to the resource.

[Click here]({{site.baseurl}}/img/GrantAccess.png) for a consolidated image of this use case.

