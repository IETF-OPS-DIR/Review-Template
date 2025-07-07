# ops-dir Review Template

Hello, 

I have been selected as the Operations Directorate (opsdir) reviewer for this draft. 

The Operations Directorate reviews all operational and management-related drafts to ensure alignment with operational best practices.

More "Guidelines for Considering Operations and Management in IETF Specifications" can be found at https://datatracker.ietf.org/doc/draft-opsarea-rfc5706bis/.

While these comments are primarily for the OPS ADs, the authors should consider them alongside other feedback and address them through updates or discussions. 


**Document**: [Draft Name and Version] 

**Reviewer**: [Your Name] 

**Review Date**: [Date] 

**IETF LC End Date**: [Date] 

**Intended Status**: [Proposed Status, e.g., Standards Track] 

 

---

 

## **Summary** 

Choose one: 

- **No issues found**. This document is ready for publication. 

- **Minor concerns/nits** that should be resolved before publication. 

- **Significant concerns** requiring discussion between authors and OPS ADs. 
 

## **General Operational Comments Alignment with RFC 5706bis** 

Provide an overview of the draft’s operational feasibility, readability, and alignment with RFC5706bis guidelines. Example: 

> *This document defines a mechanism for [X]. While the technical approach is sound, Section [X] lacks clarity on how the mechanism would deploy.

The Operational Considerations section (Section X) should be expanded to address [Z].* 



Explicitly evaluate compliance with operational guidelines (optional but recommended): 

for example the check list: 

- **Fault Management**: Are failure detection/recovery mechanisms specified? 

- **Configuration Management**: Are atomic changes and rollback procedures defined? 

- **Performance Monitoring**: Are metrics (e.g., latency, resource usage) exposed? 

| **Review Item**                | **RFC 5706 Considerations**                                                                               
|------------------------------- |-------------------------------------------------------------------------------------------------------
| Deployment                     | Does the document include a description of how this protocol or technology is going to be deployed and managed? 
| Installation and Initial Setup | Are configuration parameters clearly identified and do they have reasonable default values?           
| Migration Path                 | Are there any backward compatibility issues?                                                         
| Requirements on Other Protocols| What protocol operations are expected to be performed relative to the new protocol or technology?    
| Impact on Network Operation    | Will the new protocol significantly increase traffic load on existing networks?                       
| Verifying Correct Operation    | How can one test end-to-end connectivity and throughput?                                            

 

For routing protocols, example as 

[RFC 6123 – Inclusion of Manageability Sections in Path Computation Element (PCE) Working Group Drafts](https://www.rfc-editor.org/rfc/rfc6123.html)

  

## **Major Issues** 

List critical problems blocking publication (e.g., protocol flaws, missing operational safeguards, lack of manageability considerations). Include section/paragraph references. 

- **Example**: 

 > *Section 4.2 describes [feature] but does not specify how operators can monitor its performance (RFC 5706 Section 3.6). This omission could lead to undiagnosed failures in production networks.* 

- If none: 

 > *No major issues found.* 

 

---

## **Minor Issues** 

List non-blocking but important clarifications (e.g., ambiguous terminology, incomplete examples). 

- **Example**: 

 > *Section 2.1 uses "node" without defining its scope (physical/virtual). Add a reference to RFC 8345 for consistency.* 

- If none: 

 > *No minor issues found.* 

 

---

 

## **Nits** 

Optional editorial suggestions (e.g., acronym expansions, grammar fixes). 

- **Example**: 

 > *Abstract*: Expand "NFV" on first use. 

 > Section 3.1: "it’s" → "its".* 

 

---

 

 

 

---

 

Thank you for your work on this document. Please address these comments or contact me for clarification. 

 

Best regards, 

[Your Name] 
