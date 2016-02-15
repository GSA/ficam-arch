---
layout: page_collection
title: Exchange Attributes in a Federation
collection: usecases
---

When an individual requests access to a resource at an outside organization, that organization usually needs the individual’s attributes to make an access decision. Rather than creating a new identity record, the organization can query a metadata service to determine where a record of that individual’s attributes already exists. This can also be used to support design time identity maintenance.
This use case demonstrates both a brokered (a) and non-brokered (b) approach for obtaining attributes. It also applies to situations where attributes are being sought from another division within the same organization.

---

![Actors and Systems Key for Images](../../img/usecases/exchangelabel.png){:align="right"}
![Actors and Systems Key for Images](../../img/usecases/exchangekey.png)

**Pre-condition:** The requesting user is authenticated and belongs to an organization other than the one that owns the protected resource.

| ![1. Access Request](../../img/usecases/exchange1.png)  | An individual from Organization A attempts to access a resource at Organization B. |
| ![2A-1. Metadata Service Queried (Brokered)](../../img/usecases/exchange2.png)  | Organization B asks the metadata service where to go to obtain more details about the individual. |
| ![2A-2. Metadata Service Response (Brokered)](../../img/usecases/exchange3.png)  | The metadata service tells Organization B that Organization A has the individual’s information on record. |
| ![2A-3. Broker Queried (Brokered)](../../img/usecases/exchange4.png)  | Organization A’s attribute broker obtains the relevant identity data from its data sources. |
| ![2A-4. Attribute Query (Brokered)](../../img/usecases/exchange5.png)  | Organization A’s attribute broker obtains the relevant identity data from its data sources. |
| ![2A-5. Attributes Passed (Brokered)](../../img/usecases/exchange6.png)  | Organization A’s attribute broker responds to organization B’s attribute broker with the relevant data. |
| ![2B-1. Attribute Query (Non-Brokered)](../../img/usecases/exchange7.png)  | Organization B queries Organization A for the individual’s attributes. |
| ![2B-2. Attributes Passed (Non-Brokered)](../../img/usecases/exchange8.png)  | Organization A responds to Organization B with the individual’s relevant attributes. |
| ![3. Access Decision](../../img/usecases/exchange9.png)  | Organization B uses the individual’s attributes to make an authorization decision.  |

**Post-condition:** The individual’s attribute data was provided to the requesting organization.

[Click here](../../img/ExchangeAttributes.png) for a consolidated image of this use case.
