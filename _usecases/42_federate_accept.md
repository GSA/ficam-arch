---
layout: page_collection
title: 20. Accept Credentials in a Federation
collection: usecases
---

The term ‘federation’ describes an environment where an agency has established the tools and policies to accept identity and credential information from users at another organization, thus expanding secure access to individuals outside the organization.  Agencies might look to federate with other governmental bodies or private organizations in order to expand services, reduce costs, and improve overall efficiency.  
This use case shows the primary process for providing access to an outside individual in a federated environment.

---

![Actors and Systems Key for Images](../../img/usecases/federationlabel.png){:align="right"}
![Actors and Systems Key for Images](../../img/usecases/federationkey.png)

**Pre-condition:** Enterprise has set up the tools and policies to accept a federated credential

| ![1. Request Issued](../../img/usecases/fed1.png)  | An individual requests access to a resource at an outside organization <br/><em> In this case, an individual at a private sector organization is requesting access to a protected government resource.</em> |
| ![2A. Request Relayed (Directly)](../../img/usecases/fed2.png)  | The agency relays the request to the individual’s home organization. |
| ![2B. Request Relayed (Indirectly)](../../img/usecases/fed3.png)  | The agency directs the individual to their home organization to validate their identity. |
| ![3. Identity/Cred. Verified](../../img/usecases/fed4.png)  | The home organization verifies the individual’s identity. |
| ![4. Assertion Generated](../../img/usecases/fed5.png)  | The home organization generates a “verification assertion” to pass back to the requesting organization. |
| ![5A. Assertion Delivered (Directly)](../../img/usecases/fed6.png)  | The individual’s home organization passes the assertion to the requesting organization. |
| ![5B. Assertion Delivered (Indirectly)](../../img/usecases/fed7.png)  | The individual’s home organization passes the authentication assertion to the individual, who relays it to the requesting organization. |
| ![6. Access Decision](../../img/usecases/fed8.png)  | An access control decision is made by the organization. |


**Post-condition:** Individual is authenticated at the outside organization and proceeds to the authorization step.  

[Click here](../../img/FederatedCred.png) for a consolidated image of this use case.
