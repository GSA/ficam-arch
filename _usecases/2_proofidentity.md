---
layout: default
title: 2. Proof an Identity
collection: usecases
---

![ICAM Practice Area]({{site.baseurl}}/img/usecases/Identity-IdentityProofing.png){:align="right"}

Before you can create a credential and assign it to an individual, that person must provide proof of their claimed identity. Identity proofing is the process by which a federal agency collects and verifies information about a person to establish an enterprise identity.

The location or information that a person needs to access informs the Identity Assurance Level (IAL), which informs the elements you should require from that person for identity proofing. There are three IALs; however, federal agencies require a minimum of IAL3 for employees or contractors with recurring access to government resources, so these use cases do not include IAL1.

This use case describes the high-level steps to proof an identity at IAL2 or IAL3. Depending on the required IAL, you may require increasingly more information from an employee or contractor or partner along with additional verification steps. The information provided by the employee or contractor is also known as identity evidence. Identity evidence may be physical, such as passports, driver’s licenses, and birth certificates.

- **IAL2** - first and last name, email address, and address of record, supported by appropriate identity documentation and verified as strong.
- **IAL3** - first and last name, email address, address of record, and fingerprints, supported by appropriate identity documentation and verified as superior.

For more information about identity proofing and IALs, see <a href="https://pages.nist.gov/800-63-3/">NIST SP 800-63-A</a> (Table 4-1).

---

![Icon Key for Use Case Images]({{site.baseurl}}/img/usecases/2-IconKey.png)

## Procedure

In this use case, an administrator needs to collect or manage identity data for an employee or contractor for the purpose of creating an enterprise identity record and maintaining it throughout its lifecycle.

| **1. Collect identity information**<br/>![Collect identity information]({{site.baseurl}}/img/usecases/2-1.png)  | **IAL2** *(In-person or remote)* - The employee or contractor presents identity information, like first name, last name, and address of record.<br/>**IAL3** *(In-person or supervised remote)* - The employee or contractor presents identity information, like first name, last name, and address of record, and biometric data like fingerprints. |
| **2. Verify the identity information**<br/>![Verify the identity information]({{site.baseurl}}/img/usecases/2-2.png)  | **IAL2** - The administrator confirms the information provided is valid and current by comparing photo identification to the individual, or confirming contact information, ensuring it matches the provided documentation.<br/>**IAL3** - The administrator verifies all information with the issuing organization.<br/>*Result:* The individual’s identity has been successfully proofed at IAL2, or IAL3. |

<style type="text/css">
.tg  {border-collapse:collapse;border-spacing:0;}
.tg td{border-color:black;border-style:solid;border-width:1px; overflow:hidden;padding:10px 5px;word-break:normal;}
.tg th{border-color:black;border-style:solid;border-width:1px; overflow:hidden;padding:10px 5px;word-break:normal;}
.tg .tg-yj5y{background-color:#efefef;border-color:inherit;text-align:center;vertical-align:middle}
.tg .tg-0pky{border-color:inherit;text-align:left;vertical-align:top}
</style>

<table class="tg">
  <tr>
    <td class="tg-0pky"><span style="font-weight:bold">1. Collect identity information</span><br><img src="../img/usecases/2-1.png" alt="Diagram displaying an employee/contractor presenting identity information to an administrator or user-facing application." width="280"></td>
    <td class="tg-0pky"><span style="font-weight:bold">IAL2</span> <span class="italic">(In-person or remote)</span> - The employee or contractor presents identity information, like first name, last name, and address of record.<br><span style="font-weight:bold">IAL3</span> <span class="italic">(In-person or supervised remote)</span> - The employee or contractor presents identity information, like first name, last name, and address of record, and biometric data like fingerprints.</td>
  </tr>
  <tr>
    <td class="tg-0pky"><span style="font-weight:bold">2. Verify the identity information</span><br><img src="../img/usecases/2-2.png" alt="Diagram displaying an administrator verifying identity information with the employee/contractor or issuing organization." width="280"></td>
    <td class="tg-0pky"><span style="font-weight:bold">IAL2</span> - The administrator confirms the information provided is valid and current by comparing photo identification to the individual, or confirming contact information, ensuring it matches the provided documentation.<br><span style="font-weight:bold">IAL3</span> - The administrator verifies all information with the issuing organization.<br><span class="italic">Result:</span> The individual’s identity has been successfully proofed at IAL2, or IAL3.</td>
  </tr>
</table>

## Examples

- I want to proof the identity of an employee or contractor to verify that the individual is who she says she is, so that she can be issued a unique enterprise credential.
- Prospective employee or contractor has filled out their information in an HR system and requires IAL3 proofing, and minimum background investigations. The prospective employee/contractor is then scheduled for in-person proofing. The prospective employee/contractor brings required identity documentation, where the information is verified using approved documentation and biometrics are captured.

## Next Steps

Create and issue a credential and assign access entitlements.
