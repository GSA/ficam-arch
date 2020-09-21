---
layout: default
title: 6. Manage the Credential Lifecycle
collection: usecases
---

![ICAM Practice Area]({{site.baseurl}}/img/usecases/Credential-MaintenanceRevocation.png){:align="right"}

Active credentials require regular maintenance. This use case describes the most common credential maintenance activities:

- **Reset a credential** - An employee or contractor forgets the password or PIN associated with a credential, and requests a reset.a
- **Renew a credential** - An employee or contractor’s credential is expiring or their personal information changes, so they request a replacement credential. You must renew a credential prior to the expiration date, otherwise the employee or contractor must go through the issuance process again.
- **Revoke a credential** - An employee or contractor is no longer eligible for their credential (like separating from the issuing agency). The sponsor, supervisor, or administrator requests a revocation of all associated credentials and enterprise accounts.

You should periodically review your employee or contractors’ eligibility for credentials to identify potential orphans.

---

![Icon Key for Use Case Images Images]({{site.baseurl}}/img/usecases/6-IconKey.png)

## Reset a Credential

In this use case, an employee or contractor interacts with the agency services to register or request a derived credential.

| 1. Initiate the request ![Initiate the request]({{site.baseurl}}/img/usecases/6-Reset-1.png)  | An employee or contractor forgets their password or PIN, and requests a reset.<br/>If the request is valid, the identity management system approves the request. |
| 2. Issue a reset ![Issue a reset]({{site.baseurl}}/img/usecases/6-Reset-2.png)  | The system issues a password/PIN reset, which may be a temporary password or a link to a web-based reset form. |
| 3. Reset the credential ![Reset the credential]({{site.baseurl}}/img/usecases/6-Reset-3.png)  | The employee or contractor resets their password or PIN. |

## Renew a Credential

In this use case, an administrator needs to issue a new credential to replace one that will expire soon or has outdated identity information.

| 1. Initiate the request ![Initiate the request]({{site.baseurl}}/img/usecases/6-Renew-1.png)  | An individual requests a renewal for an employee or contractor’s credential.<br/>This individual may be the employee or contractor, their supervisor, or an administrator with approval authority.<br/>This could also be an automated process triggered by schedules or specific events. |
| 2. Review the request ![Issue a reset]({{site.baseurl}}/img/usecases/6-Renew-2.png)  | The identity management system reviews the request and verifies that the employee or contractor qualifies for a renewed credential. If so, approve the request. |
| 3. Replace the credential ![Reset the credential]({{site.baseurl}}/img/usecases/6-Renew-3.png)  | The system issues a new credential to the employee or contractor. |

## Revoke a Credential

In this use case, you are an administrator who needs to revoke an active credential.

| 1. Initiate the request ![Initiate the request]({{site.baseurl}}/img/usecases/6-Revoke-1.png)  | An individual sends a separation notification or a notice of a lost or compromised credential, requesting revocation.<br/>This individual may be the employee or contractor, their supervisor, HR, or a security team member. |
| 2. Disable the credential ![Disable the credential]({{site.baseurl}}/img/usecases/6-Revoke-2.png)  | The administrator invalidates the credential.<br/>Depending on your agency, an individual or a system may perform this task. |
| 3. Return the credential ![Return the credential]({{site.baseurl}}/img/usecases/6-Revoke-3.png)  | If the revoked credential is physical or hardware-based, the administrator returns the credential to the appropriate individual.<br/>This individual may be a supervisor, HR, or security team member. |

## Examples

- An employee or contractor may have attempted to use a credential and input the PIN information incorrectly several times up to an agency defined limit, and has locked their account or credential.  The employee or contractor requests a PIN reset.  The employee or contractor is directed to an unlock service; has to verify information again to prove they are the same person issued the original credential; and follows prompts to unlock their credential, generating a new PIN information in the process.
- *Reset* - I want to verify the identity of an employee or contractor that has already been issued a credential, and reset their PIN or password so that they can continue to access enterprise resources.
- *Renew* - I want to verify the identity and eligibility of an employee or contractor, with a previously issued credential that is near expiration, so that they may be issued a new enterprise credential to keep their ability to access enterprise resources.
- *Revoke* - I want to remove access to enterprise resources for an employee or contractor, so that they can no longer use the protected resource. 

## Next Steps

Manage the entitlements lifecycle of the credential.
