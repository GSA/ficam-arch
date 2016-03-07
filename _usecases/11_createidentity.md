---
layout: page_collection
title: 1. Create and Maintain an Identity
collection: usecases
---

When an employee or contractor on-boards at an agency, their identity information is collected and stored to act as their digital proxy in IT systems. This information is stored within an identity record, which may be modified or deleted as needed.
Once this digital identity record is established, it may be pushed to other systems from an authoritative source and provisioned access permissions (see Manage Entitlements).

---

![Actors and Systems Key for Images](../../img/usecases/ilabel.png){:align="right"}
![Actors and Systems Key for Images](../../img/usecases/createidkey.png)

**Pre-condition:** Identity information on the individual has been collected.

| ![1. Information Populated](../../img/usecases/createid1.png)  | Personnel information is populated into the authoritative source.<br/>*Sources for this information could include onboarding documents or HR systems.*  |
| ![2. New Identity Record Created](../../img/usecases/createid2.png)  | The authoritative source sends the information to the system’s data repository.  |
| ![3B. Modify Record](../../img/usecases/createid3a.png)  | The administrator receives a change request and updates personnel information in the authoritative source.  |
| ![3B-1. Modify Record](../../img/usecases/createid3b1.png)  | The individual uses an agency application to update their personal information.  |
| ![3B-2. Actors and Systems Key](../../img/usecases/createid3b2.png)  | The agency application updates the individual’s identity record within the authoritative source.  |
| ![3C. Delete Record](../../img/usecases/createid3c.png)  | The administrator deletes the identity record within the authoritative source when notified that deletion is required.  |
| ![4. Data Repository Updated](../../img/usecases/createid4.png)  | The authoritative source updates the available identity information to the repository.  |

**Post-condition:** The identity record of an individual is created, updated, or deleted, as appropriate.  

[Click here](../../img/CreateID.png) for a consolidated image of this use case.
