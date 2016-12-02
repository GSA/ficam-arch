---
layout: default
title: Credential Management
collection: services
permalink: services/credentials/
---
![Credential Service Diagram - Overview of diagram follows in text below.]({{site.baseurl}}/img/Credential.png){:align="right"}
Credential Management is the set of practices that an organization uses to issue, track, update, and revoke
credentials for identities within their context.

A **CREDENTIAL** is authoritative evidence of an individual’s claimed identity. Credentials come in many types, from
physical papers and cards (such as a passport or ATM card) to electronic items (such as a password or digital certificate),
and often incorporate anti-tamper features.  Within the US Federal Government, we have **PIV** as a credential.  

All credentials, no matter what type, associate an identity
with an individual (typically via an identifier) and identify the
organization that issued it:

* Your driver’s license includes a license number, your
name, and a state seal.

* An ATM card includes a card number, your name, and
a corporate symbol.

* A PIV credential contains a picture, the issuing agency logo, and cryptographic key pairs

Some credentials indicate authorizations granted to the
identity by the issuing organization. For example, a driver’s
license includes the authorization to drive a car.

Unlike identities, credentials generally expire. If an identity
continues past the expiration date of the credential, a new
credential is issued:

* Your driver’s license expires after so many years and
you receive a new one.

* Your ATM card expires after so many years and you
receive a new one.

* Your PIV credential expires after three to six years and you receive a new one.

A credential that is lost or compromised before it expires
may be revoked by the organization that issued it. Credentials can incorporate something you know (such as a
password or PIN), something you have (such as a card), or
something you are (such as a fingerprint or iris). Some
credentials incorporate more than one option, and are referred to
as two-factor or three-factor or multi-factor.

As with identity proofing, credentials have different Levels of
Assurance depending on the strength required. The
credential for accessing your bank account is likely stronger
than the credential for accessing your health club.

  
### Credential Management Services
The Credential Management services in the Federal ICAM architecture include Sponsorship, Registration, Issuance, Maintenance, and Revocation.

![Credential Service Details Diagram - Service definitions follow in text below.]({{site.baseurl}}/img/credential_services_detailed.png){:align="center"}

**Sponsorship**  

> Formally establishing that a person or entity requires a credential.   
_Keywords_: Sponsor, Authorizing Official, Affiliation, Request

**Registration**  

> Collecting the information needed from a person or entity to issue them a credential.   
_Keywords_: Enrollment  

**Issuance**  

> Transferring a credential to a person or entity.  
_Keywords_: Activation, Token  

**Maintenance**  

> Maintaining a credential over its life cycle.
_Keywords_: Renewal, Reset, Suspension, Blocking, Reissuance  

**Revocation**  

> Withdrawing a credential from a person or entity.  
_Keywords_: Termination  
