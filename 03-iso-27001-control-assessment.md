
# ISO/IEC 27001:2022 – Information Security Control Assessment

## 1. Assessment Overview

| Field | Details |
|---|---|
| Organization | ABC Technologies Ltd. (Fictional) |
| Industry | Technology / SaaS |
| Assessment Type | Internal Information Security Control Assessment |
| Framework | ISO/IEC 27001:2022 |
| Assessment Period | October 2026 |
| Assessment Team | Internal IT Audit Team |
| Environment | Microsoft Azure and Cloud-Based Business Applications |
| Document Status | Sample Portfolio Workpaper |

## 2. Assessment Objective

The objective of this assessment is to evaluate the design and operating effectiveness of selected information security controls against the applicable requirements of ISO/IEC 27001:2022.

The assessment aims to:

- Evaluate whether selected information security controls are appropriately designed.
- Verify whether controls are implemented and operating effectively.
- Review supporting documentation and audit evidence.
- Identify control gaps and potential security risks.
- Recommend corrective actions to strengthen the organization's Information Security Management System (ISMS).

## 3. Assessment Scope

The assessment covers selected information security controls relating to:

- User access management and access rights.
- Privileged access management.
- Cloud service security.
- Information backup and recovery.
- Security event logging and monitoring.

The assessment considers relevant policies, procedures, system configurations, access records, and other supporting evidence.

## 4. Assessment Methodology

The assessment will be performed through the following procedures:

1. Review relevant information security policies and procedures.
2. Understand the control objectives and associated risks.
3. Obtain supporting documentation and system-generated evidence.
4. Perform sample-based testing of selected controls.
5. Evaluate control design and operating effectiveness.
6. Document identified exceptions and control gaps.
7. Develop recommendations and corrective action plans.



## 5. ISO 27001 Annex A Control Assessment Matrix

The following six controls have been selected for this sample assessment based on their relevance to identity and access management, cloud security, backup management, and security monitoring.

| Control ID | Control Name | Assessment Focus | Key Risk |
|---|---|---|---|
| 5.15 | Access Control | Access control policies and rules | Unauthorized access |
| 5.18 | Access Rights | Provisioning, review, and removal of access rights | Excessive or inappropriate access |
| 5.23 | Information Security for Use of Cloud Services | Cloud service security governance | Cloud security misconfiguration |
| 8.2 | Privileged Access Rights | Allocation and management of privileged access | Privilege misuse |
| 8.13 | Information Backup | Backup procedures and restoration | Data loss |
| 8.15 | Logging | Generation, protection, and analysis of logs | Undetected security incidents |

### 5.1 Assessment Approach

Each selected control will be assessed using the following criteria:

| Assessment Criteria | Description |
|---|---|
| Control Design | Whether the control is appropriately designed to address the identified risk |
| Implementation | Whether the control has been implemented within the organization |
| Operating Effectiveness | Whether the control operates consistently throughout the assessment period |
| Evidence Sufficiency | Whether the evidence obtained is adequate and reliable |
| Exceptions | Any deviations from the expected control requirements |

### 5.2 Assessment Rating

The following rating scale will be used for this sample assessment:

| Rating | Definition |
|---|---|
| Effective | Control is appropriately designed and operating effectively |
| Partially Effective | Control is implemented but has identified weaknesses |
| Ineffective | Control is not adequately designed or is not operating effectively |
| Not Tested | Insufficient testing has been performed to reach a conclusion |

**Important:** Final ratings will be assigned only after reviewing the relevant evidence and completing the audit procedures. The ratings in this portfolio will be illustrative, not actual audit conclusions.

**Note:** This is a simulated portfolio assessment using fictional organizational information and illustrative audit evidence. It does not represent an actual ISO certification audit or independent assessment of a real organization.




## 6. Detailed Control Assessment

### 6.1 Control 5.15 – Access Control

**Control Reference:** ISO/IEC 27001:2022 Annex A 5.15

**Control Name:** Access Control

**Control Objective:**

To ensure that access to information and associated assets is restricted according to business requirements and information security policies.

**Risk Identified:**

Inadequate access control mechanisms may allow unauthorized individuals to access confidential company information, resulting in data breaches, unauthorized modifications, or information disclosure.

**Expected Control Activities:**

1. The organization maintains a documented access control policy.
2. Access to business applications and information systems is restricted based on business requirements.
3. Access permissions are approved by authorized personnel.
4. User access is assigned according to defined roles and responsibilities.
5. Access restrictions are communicated to relevant employees and system administrators.

**Audit Procedures:**

1. Obtain and review the organization's approved Access Control Policy.
2. Verify whether access control requirements are documented and communicated.
3. Review user access provisioning procedures.
4. Select a sample of user accounts from the organization's business applications.
5. Verify whether access permissions are appropriate to users' job responsibilities.
6. Inspect evidence of management approval for selected user access requests.

**Evidence Required:**

- Approved Access Control Policy.
- User access provisioning procedure.
- User access listing from business applications.
- Sample user access request forms.
- Management approval records.
- Role-based access control (RBAC) configuration, where applicable.

**Sample Testing Approach:**

Select 10 user accounts from the business application user listing and verify:

- Whether each user's access was formally approved.
- Whether assigned permissions are consistent with job responsibilities.
- Whether access is restricted according to the approved access control requirements.

**Assessment Considerations:**

Evaluate whether the documented policy is approved, communicated, and supported by implemented access restrictions.

The final control rating should be determined after reviewing the actual supporting evidence and completing sample testing.

**Preliminary Assessment Status:** Not Tested.



### 6.2 Control 5.18 – Access Rights

**Control Reference:** ISO/IEC 27001:2022 Annex A 5.18

**Control Name:** Access Rights

**Control Objective:**

To ensure that access rights to information and associated assets are provisioned, reviewed, modified, and removed in accordance with the organization's access control policy and business requirements.

**Risk Identified:**

Failure to appropriately manage user access rights may result in unauthorized system access, excessive privileges, unauthorized information disclosure, or continued access by former employees.

**Expected Control Activities:**

1. User access requests are formally initiated and approved by authorized personnel.
2. Access rights are assigned based on job responsibilities and the principle of least privilege.
3. User access rights are reviewed periodically by designated business or system owners.
4. Access rights are modified when employees change roles or responsibilities.
5. User access is revoked promptly upon employee termination or when access is no longer required.
6. Evidence of access reviews and access modifications is retained.

**Audit Procedures:**

1. Obtain the user access management policy and procedures.
2. Obtain the employee master list and user access listing from relevant business applications.
3. Review a sample of new employee access requests and verify management approval.
4. Select a sample of employees who changed roles and verify whether their access rights were appropriately modified.
5. Obtain a list of terminated employees and verify whether their system access was revoked.
6. Inspect periodic user access review records and verify evidence of review and approval.
7. Investigate any identified discrepancies between employee status and active system accounts.

**Evidence Required:**

- User Access Management Policy.
- Employee master list.
- Application user access listing.
- New user access request forms.
- Access modification and removal records.
- Employee termination records.
- Periodic user access review reports.
- Evidence of management review and approval.

**Sample Testing Approach:**

For this illustrative assessment, the following samples will be considered:

| Population | Sample Size | Testing Objective |
|---|---:|---|
| Newly created user accounts | 5 | Verify access approval |
| Employees with role changes | 3 | Verify access modification |
| Terminated employees | 3 | Verify timely access removal |
| Periodic access reviews | 1 review cycle | Verify review and approval |

The samples should be selected from complete and reliable populations. The sample sizes are illustrative and should be adjusted based on risk, population size, and audit methodology.

**Assessment Considerations:**

Evaluate whether access rights are properly approved, periodically reviewed, modified when job responsibilities change, and removed when no longer required.

Investigate discrepancies and obtain additional evidence before concluding whether a control exception exists.

**Preliminary Assessment Status:** Not Tested.



### 6.3 Control 5.23 – Information Security for Use of Cloud Services

**Control Reference:** ISO/IEC 27001:2022 Annex A 5.23

**Control Name:** Information Security for Use of Cloud Services

**Control Objective:**

To ensure that information security requirements are established and implemented throughout the acquisition, use, management, and exit processes of cloud services.

**Risk Identified:**

Inadequate governance and security management of cloud services may result in unauthorized access, data exposure, insecure configurations, regulatory non-compliance, or loss of business information.

**Expected Control Activities:**

1. The organization maintains an inventory of approved cloud services.
2. Cloud service providers undergo appropriate security and risk assessments before engagement.
3. Information security requirements are defined in cloud service agreements.
4. Responsibilities between the organization and cloud service providers are documented.
5. Cloud configurations and security settings are reviewed periodically.
6. Data protection, backup, and access management requirements are established.
7. Cloud service termination and data retrieval procedures are documented.

**Audit Procedures:**

1. Obtain the inventory of cloud services used by the organization.
2. Identify critical cloud platforms, including Microsoft Azure and relevant SaaS applications.
3. Review cloud service provider due diligence and security assessment documentation.
4. Inspect cloud service agreements for relevant information security requirements.
5. Review the documented shared responsibility matrix between the organization and cloud service providers.
6. Inspect evidence of periodic cloud security configuration reviews.
7. Verify whether cloud access is restricted to authorized personnel.
8. Review documented cloud service termination and data retrieval procedures.

**Evidence Required:**

- Cloud Service Management Policy.
- Approved cloud service inventory.
- Cloud service provider risk assessment reports.
- Cloud service agreements and contractual security clauses.
- Shared responsibility matrix.
- Microsoft Azure security configuration review reports.
- Cloud access review records.
- Cloud service termination and data retrieval procedures.

**Sample Testing Approach:**

For this illustrative assessment, select the following samples:

| Sample | Sample Size | Testing Objective |
|---|---:|---|
| Cloud service providers | 3 | Verify security assessment and approval |
| Critical cloud services | 2 | Review security requirements and responsibilities |
| Cloud configuration reviews | 2 review records | Verify periodic security reviews |
| Cloud service agreements | 2 | Verify contractual security requirements |

The sample sizes are illustrative and should be adjusted based on the cloud service population, risk assessment, and audit methodology.

**Assessment Considerations:**

Evaluate whether cloud services are formally approved, security risks are assessed, responsibilities are documented, and security requirements are monitored throughout the cloud service lifecycle.

Where technical configuration evidence is reviewed, validate the relevant settings against the organization's approved security baseline.

**Preliminary Assessment Status:** Not Tested.
