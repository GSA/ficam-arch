---
layout: default
title: Access Management
collection: services
permalink: services/access/
---

![A blue box with the list of Access Management services defined later in the body text of this page.]({{site.baseurl}}/img/services/AccessManagementServices.png){:align="right" style="padding-left:30px"}

Access Management is how an agency authenticates enterprise identities and authorizes appropriate access to protected services.

Policy administration is a combination of laws, regulations, rules, and agency policies that secure access to agency services. Your agency determines the requirements for an individual to access each resource category, and they can be as simple or as complex as you need. The following are some examples of access requirements:

- “Grant access to anyone on this list of people.”
- “Grant access to any agency employee or contractor with an authenticated PIV card.”
- “Grant access to anyone who is a federal employee, GS-12 or higher, cleared Top Secret, trained in first aid, and certified as a project manager.”

<p style="font-size: 2rem; font-weight: 700;">Authentication</p>
 
Authentication is how you verify the claimed identity of someone trying to access an agency resource. Typically, you’ll verify an identity using an authenticator associated with a credential.

Authentication is generally a two-step process:

> *Step 1.* Authenticate the credential itself:
- Did a trusted organization issue the credential?
- Has the credential expired?
- Has the credential been revoked, voided, or tampered?

> *Step 2.* Use an authenticator mentioned in Credential Management to validate the credential holder.

### Authorization

Authorization is how you decide whether you should allow someone to access an agency resource. Access requirements usually dictate whether you’ll allow someone to:

- Read or modify a certain document.
- Access an agency website.
- Enter an agency facility or location.

Usually, authorization occurs immediately after authentication. When you log in to a service, you present your credentials, and the service confirms your credentials are valid (authentication) and grants or denies you access based on your assigned permissions (authorization).

Identity proofing is how you establish an identity. Authentication is how you confirm the identity. Authorization is how you use the identity.

## Access Management Services

The Access Management services in the Federal ICAM architecture include Policy Administration, Entitlements Management, Authentication, Authorization, and Privileged Access Management.

![A blue box with the Access Management service definitions, which are listed in the following body text.]({{site.baseurl}}/img/services/AccessManagementServiceDefinitions.png){:align="center"}

### Policy Administration

> Create and maintain the technical access requirements that govern access to protected agency services.

> *Keywords*: Policy Decision, Policy Enforcement

### Authentication

> Verify that a claimed identity is genuine based on valid credentials.

> *Keywords*: Validation, Two-Factor, Multi-Factor

### Authorization

> Grant or deny access requests to protected agency services based on access requirements, identity attributes, and entitlements.

> *Keywords*: Policy Decision, Policy Enforcement

### Privileged Access Management

> Protect access to accounts that have access permissions that can affect IT system configurations and data security (e.g., superusers, domain administrators, or global administrators). 

> *Keywords*: Privileged Identity Management, Privileged Account Management, Administration, Superuser
