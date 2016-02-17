---
layout: page_collection
title: 2. Proof an Identity at Level of Assurance 2
collection: usecases
---

This use case describes the process for completing identity proofing at Level of Assurance 2 (LOA2), which allows an individual to receive an LOA2 credential. LOA2 requires an individual to submit basic documents to prove their claimed identity and may be completed in person or remotely.

---

![Actors and Systems Key for Images](../../img/usecases/ilabelproof.png){:align="right"}
![Actors and Systems Key for Images](../../img/usecases/proofloa2key.png)

**Pre-condition:** A need has been established for an individual to receive an LOA2 credential.

| ![1A. Identity Info Presented In-Person](../../img/usecases/proofloa21a.png)  | If in person, the individual presents a valid government ID.  |
| ![1B. Identity Info Presented Remotely](../../img/usecases/proofloa21b.png)  | If remote, the individual presents a utility company or bank account number and a government issued ID number.  |
| ![2. Information Verified](../../img/usecases/proofloa22.png)  | If in person, the approval authority matches the photo on the ID with the individual.<br/> If remote, the approval authority verifies either the government ID number or the account number.  |
| ![3. Confirmation](../../img/usecases/proofloa23.png)  | The approval authority confirms the individual’s contact information.  |

**Post-condition:** The individual’s identity is proofed at LOA2.

[Click here](../../img/ProofLOA2.png) for a consolidated image of this use case.

## Considerations
* Federal employees and contractors should be proofed at LOA3 or LOA4. Identity proofing at LOA2 may apply to other populations, such as citizens. The systems that these individuals access generally do not require the extensive identity proofing of LOA3 or LOA4, but the minimal identity proofing of LOA1 may not meet the standards needed to access certain government systems.

## Background & Key Revisions
* Identity proofing has been broken out by LOA because the process varies at each level.
* It was decided that these use cases will only depict activities that should be performed by the Federal Government. Therefore, a use case for LOA1 was not created, as the government should perform identity proofing at LOA2 or higher.
* At LOA2, identity proofing can be completed either in-person or remotely. These options have been depicted in this use case as two initial “branches” that lead to the same final step.
* The “approval authority” has not been further defined because that role likely will vary from agency to agency.
* The Precondition has been intentionally left vague because the circumstances under which a person would seek identity proofing at LOA2 may vary.

## External References
* <a href="http://nvlpubs.nist.gov/nistpubs/SpecialPublications/NIST.SP.800-63-2.pdf">NIST SP 800-63-2</a>
