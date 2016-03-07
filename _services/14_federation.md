---
layout: page_collection
title: Federation
collection: services
permalink: services/federation/
---
![Federation Service Diagram - Overview of diagram follows in text below.]({{site.baseurl}}/img/Federation.png){:align="right"}

Federation is the ability of one organization to accept another
organization’s work. Federation is based on inter-organizational trust.
The trusting organization has to be comfortable that the trusted
organization has similar policies, and that those policies are being
followed:

* A credential issued by your local library will not likely be trusted
by the security staff at the White House.

* A credential issued by your bank may be trusted by your health
club.

* A PIV credential issued by the Federal Government may be trusted by your State to access a website

Federation can occur at different points within ICAM. Examples include:

* An organization can accept credentials issued by another organization,
but still authenticate and authorize the individual locally:
  * A passport issued by the U.S. Department of State is accepted as a
valid credential by a foreign country, but that country’s immigration
office still authenticates the holder and requires a visa
(authorization).

* An organization can accept specific characteristics (attributes) describing
an individual from another organization:
  * Your bank will request your credit score from one of the credit
bureaus, rather than maintaining that information itself.

* An organization can accept an authorization decision from another
organization:
  * A driver’s license authorizing you to drive in one state is accepted by
another.

### Federation Services
The Federation services in the Federal ICAM architecture include Policy Administration, Entitlement Management, Provisioning, Authentication, and Authorization.
![Federation Service Details Diagram - Service definitions follow in text below.]({{site.baseurl}}/img/federation_services_detailed.png){:align="center"}

**Attribute Exchange**  

> Discovering and sharing identity attributes between different systems to promote interoperability and simplify the process for establishing an identity.  
_Keywords_: Attribute Definition, ARS  

**Credential Translation**  

> Transforming a token or credential into an alternative format, potentially containing claims about the client, for acceptance at a relying party.
_Keywords_: Secure Token Service, Assertion Service  

**Credential Bridging**  

> Establishing a cross-certified, affiliated relationship to trust credentials at a level of assurance asserted by those credentials.  
_Keywords_: Federal PKI Bridge  

**Policy Alignment**  

> Establishing a mutual relationship between parties by deliberately establishing common standards and principles.  
_Keywords_: Trust Relationship  
