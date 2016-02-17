---
layout: page_collection
title: 5. Resolve an Identity Internal to an Agency
collection: usecases
---

Organizations often have multiple source systems that contain data relevant to an individual’s identity. This use case describes the approach for obtaining identity attributes from their originating, authoritative systems and aggregating it into a single record for presentation or evaluation.

---

![Actors and Systems Key for Images](../../img/usecases/ilabelresolve.png){:align="right"}
![Actors and Systems Key for Images](../../img/usecases/resolvekey.png)

**Pre-condition:** The user’s identity data exists in disparate systems across the organization.

| ![1. Identity Data Requested](../../img/usecases/resolve1.png)  | A request for identity data is initiated to the identity manager. <br/><em> This identity manager could be a person or system, depending on the organization.</em>  |
| ![2. Query Data Sources](../../img/usecases/resolve2.png)  | The identity manager identifies relevant sources of data on the individual. <br/><em> Sources could include HR systems, security data, and personal databases.</em>  |
| ![3. Aggregate Identity Data](../../img/usecases/resolve3.png)  | Aggregate identity data to create a complete identity profile.  |

**Post-condition:** The individual’s identity data has been resolved.

[Click here](../../img/ResolveID.png) for a consolidated image of this use case.
