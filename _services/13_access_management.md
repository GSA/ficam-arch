---
layout: page
title: Access Management
collection: services
permalink: services/access/
---
![Access Service Diagram - Overview of diagram follows in text below.]({{site.baseurl}}/img/Access.png){:align="right"}
Access Management is the set of practices that enables only
those permitted the ability to perform an action on a
particular resource.  The three most common Access Management services you encounter every day perhaps without realizing it are: Policy Administration, Authentication, and Authorization.

**POLICY ADMINISTRATION** is the process by which laws,
regulations, rules, and organizational/corporate access
policies are put into effect. These policies may be extremely
simple, extremely complicated, or anywhere in between.

For example:

* “Grant access to anyone who knows the secret
handshake.”

* “Grant access to anyone on this list of people.”

* “Grant access to anyone in Human Resources.”

* “Grant access to anyone who is a federal employee,
GS-12 or higher, cleared Top Secret, trained in first
aid, and certified as a project manager.”


**AUTHENTICATION** is the process by which a claimed identity is confirmed,
generally through the use of a credential:

* When going through airport security, you present your driver’s
license, confirming your identity as the ticketed passenger.

* When you attempt to withdraw cash at an ATM, you present your
ATM card and enter your personal identification number (PIN),
confirming your identity as the account holder.

* When you attempt to login to a US Government website, you present the digital certificate on your PIV credential,
and enter a personal identification number, and the website confirms your identity as the PIV credential holder.

Authentication is generally a two-step process:

**Step 1**. Authenticate the credential itself:

>  - Was the credential issued b>y a trusted organization?
  - Has the credential expired?
  - Has the credential been revoked, voided, or tampered?

**Step 2**. Ensure that the individual the credential was issued to is the
same individual that is presenting it:

>  - Does the photo and height/weight on the driver’s license match
the person who presented it?
  - Does the person know the PIN for the ATM card that was
presented?
  - Does the person have the private key on the PIV card for the certificate presented to the website?


Authentication is how you confirm who you are. Identity proofing is
performed to establish an identity, whereas authentication is performed
to _use_ an identity.


**AUTHORIZATION** is the adjudication of requests. Authorization is the decision portion of Access Management: the process
by which a request to perform an action on a resource is decided, typically based on a policy.
The range of possible requests is very broad:

• A request to read a certain document.

• A request to receive a benefit.

• A request to enter a facility or location.

In some cases, it is necessary to perform authentication in order to
perform authorization:

> When you present your driver’s license at a bar, you are
simultaneously authenticating (the bartender ensures the photo on
the license matches the person) and authorizing (the bartender
ensures you are old enough).  

In other cases, authorization can occur without authentication:  

> When you unlock your car, the car is authorizing you without
knowing who is holding your keys. If you give your keys to a friend,
he or she is just as able to unlock your car as you are, and the car
does not know the difference.  

Authorization is how your request for a resource is decided.  

## Access Management Services
The Access Management services in the Federal ICAM architecture include Policy Administration, Entitlement Management, Provisioning, Authentication, and Authorization.  

![Access Service Details Diagram - Service definitions follow in text below.]({{site.baseurl}}/img/access_services_detailed.png){:align="center"}

**Policy Administration**  

> Creating and maintaining the rule sets that govern access to protected resources.  
_Keywords_: Policy Decision, Policy Enforcement  

**Entitlement Management**  

> Establishing and maintaining the authoritative access permissions for a person or entity.  
_Keywords_: Privilege, Right, Access Recertification, Account Management  

**Provisioning**

> Linking and unlinking access permissions for a person or entity to a protected resource.  
_Keywords_: Workflow, Deprovisioning  

**Authentication**  

> Verifying that a claimed identity is genuine based on valid credentials.  
_Keywords_: Validation, Two-Factor, Multi-Factor  

**Authorization**  

> Granting or denying access requests to protected resources based on a policy determination.  
_Keywords_: Policy Decision, Policy Enforcement
