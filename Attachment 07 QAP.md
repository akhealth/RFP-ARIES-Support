# PERFORMANCE BASED QUALITY ASSURANCE PLAN (QAP) 
# ARIES SUPPORT 
## INTRODUCTION
This Quality Assurance Plan (QAP) has been developed to evaluate contractor actions while implementing [the Scope of Work (SOW)](TBD SCOPE LINK). It is designed to provide an effective method of monitoring contractor performance for each listed objective on the Performance Requirements Matrix. It also provides a systematic method to evaluate the services the contractor is required to furnish.

## STANDARD
The contractor is responsible for management and quality control actions to meet the terms of the contract. The role of the Procurement Officer (PO) and ARIES Technical Support Team is quality assurance to ensure contract standards are achieved. The contractor shall perform all work required in a satisfactory manner in accordance with the requirements of the RFP. The Contractor shall notify the Product Manager for appropriate action if it is likely that the contractor will not achieve successful delivery of the software code or support activities in accordance with the performance objectives and acceptable quality levels (AQLs) identified below.

## PERFORMANCE REQUIREMENTS MATRIX
The Technical Support Team and PO will evaluate the performance objectives reflected below by reviews and acceptance of work products and services. As indicated, the Product Team and PO will assess progress towards the final delivered software code. Note that the performance requirements listed below are required for the final deliverables. However, the sprints and incremental delivery of code will be assessed by the Department of Health and Social Services to ensure that the contractor is on a path to successful final delivery.
Deliverable or Required Services Performance Standard(s):

**Deliverable or Required Services** | **Performance Standard(s)** | **Acceptable Quality Level (AQL)** | **Method of Review**
--- | --- | --- | ---
Tested Code | Code delivered under the contract must have substantial test code coverage and a clean code base. | Minimum of 90% test coverage of all relevant code. | Combination of manual review and automated testing, using tools that integrate with Microsoft TFS and AzureDevOps. 
Accessible | Client-side rendering must conform with WCAG 2.0, level AA. | 0 errors reported for 508 Standards using an automated scanner and 0 errors reported in manual testing. | Testing method TBD
Deployed | Code must successfully build and deploy into testing environments. | Successful build DHSS managed automated continuous integration processes. | Combination of manual review and agreed upon automated testing.
Documented | All dependencies (and licenses for dependencies) are listed and all major functions are documented. | All dependencies are listed and the licenses are documented. Software/source code is documented. System diagram is provided. | Combination of manual review and automated testing
Available | Code must be stored in a version-controlled open-source repository. | All code produced under the contract must be available | DHSS will assess code availability
User research | Design research and usability testing activities must be conducted at regular intervals throughout the development process (not just at the beginning or end) to ensure the user needs are well understood and that design solutions work well for users. | During the first sprint, vendor shall establish a design research plan in collaboration with the technical support team. This plan must account for the availability of resources, articulation of research methods, and delivery of research-related records. In subsequent sprints, research-related records will be delivered in accordance with the aforementioned design research plan. | DHSS will cross-reference research-related records with other project documentation to ensure that research is properly accounted for and communicated.
Secure | Code must be free of medium- and high-level static and dynamic security vulnerabilities. | Clean automated tests from a static testing SaaS, Veracode, and/or documentation explaining any false positives. | Architecture must conform to DHSS IT Standards and project standards 

## PROCEDURES
The ARIES Technical Support Team and PO, along with the product owner, will inspect all tasks required by the contract to ensure contractor compliance with the contract requirements at the conclusion of each sprint, which shall have a length of two weeks or less, unless agreed upon by the vendor and Technical Support team.
The Support Team will create/identify the repositor(y/ies) needed for executing the contract and provide brief documentation on their purpose.  If the contractor identifies a need for a change in the repositories, they will submit a request to the Support team.  The Support team will review, discuss as needed, and resolve the request, as agreed. 

Delivery of all software assets will occur by pull request from the contractor’s repository to the appropriate Alaska repository. If inspection results are satisfactory, the pull request will be merged; otherwise, deficiencies will be noted in the pull request or through issues as described below. The Product Team and PO may find the delivery satisfactory even though further work is required, provided that the specific requirements of the sprint are met.
 
Unless otherwise agreed upon in writing, the contractor shall deliver research-related records to DHSS in accordance with the previously agreed upon design research plan. The design research plan shall be delivered during the first sprint.

At the conclusion of each sprint, the PO (or their designee) and Product Team will review the completed user stories and related functionality to ensure compliance with acceptance criteria and requirements. Incomplete or inadequate code and user stories will be noted in a mutually agreed-upon issue tracker with links to each issue shared with the PO. The contractor may respond in that tracker as appropriate, addressing the accuracy and validity of the defect as well as any planned corrective action (if not already noted). All clarifications and changes to the scope agreed upon in the issue tracker will be updated as revised acceptance criteria in the incomplete backlog items as part of the backlog grooming process.  The contractor team will discuss and document actions to prevent recurrence in the sprint retrospectives.

At the conclusion of the period of performance, a similar procedure will be followed to document discrepancies and to assess overall performance.

If any of the services do not conform to the contract requirements, the PO may require the contractor to perform the services again in conformity with contract requirements. Any user stories that are not accepted must be completed in the next sprint, unless the product owner and product manager agree to move it to a later sprint. The PO shall not certify satisfactory performance for the contract until all defects have been corrected. When the defects in services cannot be corrected by re-performance, the State may:

1. Require the contractor to take necessary action to ensure that future performance conforms to contract requirements; and,

2. Reduce the contract price to reflect the reduced value of the services performed. The Product Manager and PO will maintain a complete quality assurance file. The file will contain copies of all reports, evaluations, recommendations, and any actions relating to the State’s performance of the quality assurance function, including originals of all quality monitoring checklists. All such records will be retained for the life of the contract. 

## ACCEPTANCE OF SERVICES
Acceptance of services shall be based upon compliance with performance standards described in the performace requirements matrix and monitoring procedures described in this QAP. Before approving/certifying any contractor invoices, the PO will verify that all invoiced services have been performed in compliance with contract requirements. The PO shall not certify satisfactory performance for the contract until all defects have been corrected.
