# Ops-Dir Review Template

Hi,


I have been selected as the Operational Directorate (opsdir) reviewer for this Internet-Draft. 

The Operations Directorate reviews Internet-Drafts to ensure alignment with operational best practices and that adequate operational considerations are covered.

A complete set of _"Guidelines for Considering Operations and Management in IETF Specifications"_ can be found at https://datatracker.ietf.org/doc/draft-opsarea-rfc5706bis/.

**Document**: [Internet-Draft Name and Revision]

**Reviewer**: [Your Name]

**Review Date**: [Date]

**Intended Status**: [Proposed Status, e.g., Standards Track] 

 
---

## **Summary** 

Choose one: 

- **Ready**: No issues found. This document is ready for publication. 

- **Has Nits**: This document is basically ready for publication but has nits that should be considered prior to publication.

- **Has Issues**: I have some minor concerns about this document that I think should be resolved before publication.
 
- **Has Major Issues**: I have significant concerns about this document and recommend that the OPS ADs discuss these issues further with the authors.


## **General Operational Comments Alignment with RFC 5706bis** 

Provide an overview of the draft’s operational feasibility, readability, and alignment with RFC5706bis guidelines. Example: 

> *This document defines a mechanism for [X]. While the technical approach is sound, Section [X] lacks clarity on how the mechanism would deploy.*

> *The Operational Considerations section (Section X) should be expanded to address [Z].* 



Explicitly evaluate compliance with operational guidelines (optional but recommended): 

For example the check list: 

- **Fault Management**: Are failure detection/recovery mechanisms specified? 

- **Configuration Management**: Are configuration changes to enable/disable the feature clearly defined? 

- **Performance Monitoring**: Are metrics (e.g., latency, resource usage) clearly identified? 

| **Review Item**                | **RFC 5706 Considerations**                                                                               
|------------------------------- |-------------------------------------------------------------------------------------------------------
| Deployment                     | Does the document include a description of how this protocol or technology is going to be deployed and managed? 
| Installation and Initial Setup | Are configuration parameters clearly identified and do they have reasonable default values?           
| Migration Path                 | Is a path to migrate existing configuration clearly articulated? Are there any backward compatibility issues?                        
| Requirements on Other Protocols| What other protocol operations are expected to be performed relative to the new protocol or technology?    
| Impact on Network Operation    | Will the new protocol significantly increase traffic load on existing networks or affect the control plane?                       
| Verifying Correct Operation    | For example, how can one test end-to-end connectivity and throughput?                                            

 
For routing protocols, an example is: 

[RFC 6123 – Inclusion of Manageability Sections in Path Computation Element (PCE) Working Group Drafts](https://www.rfc-editor.org/rfc/rfc6123.html)

  

## **Major Issues** 

List critical problems blocking publication (e.g., protocol flaws, missing operational safeguards, or lack of manageability considerations). Include section/paragraph references. 

- **Example**: 

 > *Section 4.2 describes [feature] but does not specify how operators can monitor its performance (RFC 5706 Section 3.6). This omission could lead to undiagnosed failures in production networks.* 

- If none: 

 > *No major issues found.* 

 

---

## **Minor Issues** 

List non-blocking but important clarifications (e.g., ambiguous terminology or incomplete examples). 

- **Example**: 

 > *Section 2.1 uses "node" without defining its scope (physical/virtual). Add a reference to RFC 8345 for consistency.* 

- If none: 

 > *No minor issues found.* 

 
---

## **Nits** 

Optional editorial suggestions (e.g., acronym expansions or grammar fixes). 

- **Example**: 

 > *Abstract*: Expand "NFV" on first use. 

 > Section 3.1: "it’s" -> "its".* 


---
 

---


Thank you for your work on this document. Please address these comments or feel free to contact me for clarification and/or discussion.


Best regards, 

[Your Name] 
