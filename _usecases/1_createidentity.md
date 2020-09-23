---
layout: default
title: 1. Create and Maintain an Identity
collection: usecases
---

![ICAM Practice Area]({{site.baseurl}}/img/usecases/Identity-Creation.png){:align="right" style="padding:15px"}

When you onboard an employee or contractor at your agency, you collect identity information from the individual, and store parts of that information as identity attributes. These attributes serve as a digital proxy for the individual’s identity, also known as an enterprise identity.

---

## Use Case

In this use case, an administrator needs to collect or manage identity data for an employee or contractor for the purpose of creating an enterprise identity record and maintaining it throughout its lifecycle.

![Icon Key for Use Case Images]({{site.baseurl}}/img/usecases/1-IconKey.png)

<table>
  <tr>
    <td style="width:250px;border:0px;vertical-align:top"><strong>1. Collect information</strong> <br> <img src="../../img/usecases/1-1.png" width="250"></td>
    <td style="border:0px;vertical-align:top">The administrator collects identity information from the employee or contractor, and adds this information to the authoritative source.<i>This identity information may come from the individual, onboarding documents, or HR systems.</i></td>
  </tr>
  <tr>
    <td style="width:250px;border:0px;vertical-align:top"><strong>2. Create an enterprise identity</strong> <br> <img src="../../img/usecases/1-2.png" width="250"></td>
    <td style="border:0px;vertical-align:top">The authoritative source sends the information to the system’s data repository. <br><br> Result: An enterprise identity in the authoritative source for the employee or contractor.</td>
  </tr>
  <tr>
    <td style="width:250px;border:0px;vertical-align:top"><strong>3. Maintain the enterprise identity</strong></td>
    <td style="border:0px;vertical-align:top">The following steps describe identity maintenance your agency should perform on a regular basis.</td>
  </tr>
  <tr>
    <td style="width:250px;border:0px;vertical-align:top"><strong>3a. Identify and aggregate identity data</strong> <br> <img src="../../img/usecases/1-3a.png" width="250"></td>
    <td style="border:0px;vertical-align:top">Query your data repositories for any existing identities for an individual. Aggregate these attributes as a single enterprise identity for the individual.</td>
  </tr>
  <tr>
    <td style="width:250px;border:0px;vertical-align:top"><strong>3b. Update the enterprise identity</strong> <br> <img src="../../img/usecases/1-3b.png" width="250"></td>
    <td style="border:0px;vertical-align:top">If an individual has updated personal information, there are two ways to update the enterprise identity: <ol> <li> The administrator updates the individual’s enterprise identity attributes directly in the authoritative sources.</li> <li>The individual uses an agency application to update their personal information, and the application updates the individual’s enterprise identity attributes in the authoritative sources.</li></ol></td>
  </tr>
  <tr>
    <td style="width:250px;border:0px;vertical-align:top"><strong>3c. Delete the enterprise identity</strong> <br> <img src="../../img/usecases/1-3c.png" width="250"></td>
    <td style="border:0px;vertical-align:top">When you need to delete an enterprise identity, delete the identity attributes in the authoritative source.</td>
  </tr>
</table>




## Example

I want to create a new enterprise identity, so that an individual may be established as a federal employee or contractor that will need to be identity proofed, credentialed, and granted access to agency services.

## Next Steps

[Proof the identity](../2_proofidentity) and [assign appropriate access entitlements](../3_manageentitlements).
