# Cyber Pros AI Governance Portfolio Project: Automated Loan Underwriting System - Lanchel Brutus

## Executive Summary

I served as the **AI Governance Lead** for a fictional high-risk AI governance assessment involving Meridian Financial Services, a mid-sized financial services company piloting an automated loan underwriting system.

The system uses a third-party AI model, **CrediSure Credit Decision Engine v2.3**, to evaluate small business loan applications and produce one of three outcomes:

- Auto-approve
- Auto-deny
- Route to manual review

Because approximately **94% of applications are processed automatically** and the system affects access to credit, I classified this as a **high-risk AI use case** requiring governance review before production deployment.

My final recommendation was:

> **Proceed with conditions. Meridian should not approve unrestricted production deployment until fairness testing, proxy-bias review, reason code validation, human oversight triggers, appeal procedures, vendor evidence review, monitoring thresholds, and governance committee approval are completed.**

The EU AI Act Assessment <img width="1433" height="753" alt="Screenshot 2026-10-07 at 19 54 33" src="https://github.com/user-attachments/assets/fc066bbb-d2dc-464d-8888-3f4533a5459a" />

> **Caption:** This screenshot shows the EU AI Act FRIA summary for the Meridian Automated Loan Underwriting System, including stakeholder consultation status, flagged rights, risk score, and conditional approval recommendation. 

## Frameworks Applied

| EU AI Act | NIST AI Risk Management Framework | ISO/IEC 42001 |
|---|---|---|
| High-risk AI classification | Governance roles and responsibilities | AI management system scope |
| Fundamental Rights Impact Assessment | System context and intended use | Organizational roles and responsibilities |
| Human oversight| Risk measurement and testing evidence | AI risk assessment |
| Logging | Risk prioritization and treatment | AI risk treatment |
| Explanation to affected persons | Human-AI oversight | Management review |
| Fundamental Rights Impact Assessment |  | AI system lifecycle management |
| Appeal and contestability|  | Third-party AI risk management |
| Deployment conditions |  | |


This portfolio demonstrates my ability to perform practical AI governance work for a high-risk AI system.

Specifically, this project shows that I can:

- Lead an AI governance review for a high-risk AI use case
- Document an AI system profile and governance intake record
- Identify and assess AI risks related to fairness, explainability, automation, vendor risk, and human oversight
- Apply EU AI Act, NIST AI RMF, and ISO/IEC 42001 concepts in a practical way
- Review third-party AI model and vendor governance concerns
- Design human oversight, exception review, and appeal procedures
- Prepare an executive-ready production readiness recommendation
- Use AI governance tooling to organize evidence, risks, policies, and framework assessments

---

## Central Governance Question

This portfolio answers one central question:

> **Should Meridian Financial Services approve production deployment of a 94% automated AI loan underwriting system?**

My answer:

> **Not for unrestricted production deployment. The system may proceed only with conditions because the current governance evidence does not fully support safe, fair, explainable, accountable, and well-monitored deployment.**

## Portfolio Artifacts

| Artifact | Purpose | Link |
|---|---|---|
| AI System Profile and Intake Record | Documents system purpose, users, affected groups, data, vendor, and risk classification. | [View Artifact](https://docs.google.com/document/d/1q2iMEMb-7Xek2lmECq1-DQT5rDRCi_MlFYTwL2Jb5Ig/edit?usp=drive_link) |
| AI Risk Register and Mitigation Summary | Documents key AI risks, severity, controls, residual risk, and recommendations. | [View Artifact](https://docs.google.com/document/d/1PPeg_nKr-xfuAuxdIFQvRu8r0F2wEdDUUjADJ7biQds/edit?usp=sharing) |
| Human Oversight and Appeal Procedure | Defines human review triggers, override authority, escalation, and applicant appeal process. | [View Artifact](https://docs.google.com/document/d/14L_cdmdn3WDQU4OAkmWXmSriK4wWIMFxztZ-IMBISiA/edit?usp=sharing) |
| Third-Party Vendor and Model Review | Evaluates CrediSure AI vendor risk, model limitations, and required evidence. | [View Artifact](https://docs.google.com/document/d/1ixeLcu3ZbLs1oRMVsZRcOhEaMFqoLRPLP9jZmIk2sNU/edit?usp=sharing) |
| Production Readiness Decision Memo | Provides final executive recommendation. | [View Artifact](https://docs.google.com/document/d/1n6fIW4xsy8nhBQPPLpI4zdDttjGDRojv0N6MzQdUku8/edit?usp=sharing) |
| Final VerifyWise Portfolio Report | Consolidated portfolio report generated from VerifyWise. | [View Report](https://drive.google.com/file/d/1eN26gCzbvlTUXNyT1W1nhECPlyotqaj9/view?usp=sharing) |

---

## Practical AI governance Skill Proof (Screenshots) 

### 1. Use Case Registration

<img width="980" height="817" alt="2  Create the New Use Case" src="https://github.com/user-attachments/assets/859be89b-3c21-4694-ab9b-0dbbe16abc34" />


> **Caption:** This screenshot shows the Meridian Automated Loan Underwriting System registered as a high-risk AI use case in VerifyWise.

**Skill demonstrated:** AI use case intake, risk classification, and governance workflow setup.

---

### 2. Model Inventory

<img width="824" height="746" alt="3  Add the Model to Model Inventory " src="https://github.com/user-attachments/assets/f07225c1-6cc8-4cea-bcd0-3c1bfe24ae93" />

> **Caption:** This screenshot shows the CrediSure Credit Decision Engine v2.3 documented in the model inventory.

**Skill demonstrated:** Model inventory documentation, model limitation tracking, and third-party AI model governance.

---

### 3. Dataset Record

<img width="827" height="817" alt="4  Datasets" src="https://github.com/user-attachments/assets/ac514020-1a62-43f5-8b8a-9860a1a03080" />

> **Caption:** This screenshot shows the Small Business Loan Underwriting Dataset documented with data purpose, source, PII status, known bias concerns, and mitigation approach.

**Skill demonstrated:** Dataset governance, PII awareness, data source documentation, and bias mitigation planning.

---

### 4. AI Risk Register

<img width="1522" height="865" alt="5  Risk register" src="https://github.com/user-attachments/assets/649f77f7-4d6d-4201-9219-7314a65b3954" /> 

> **Caption:** This screenshot shows the six priority AI risks documented for the Meridian Automated Loan Underwriting System.

**Skill demonstrated:** AI risk identification, risk rating, mitigation planning, residual risk analysis, and approval workflow documentation.

## Key Risks Identified

| Risk | Why It Matters |
|---|---|
| Discriminatory lending outcomes | The system may unfairly approve or deny applicants based on biased data, proxy variables, or historical lending patterns. |
| Proxy bias through credit and business variables | Variables such as geography, business age, industry, credit history, thin credit files, or cash-flow volatility may create unfair outcomes. |
| Weak explainability and incomplete reason codes | Meridian may be unable to explain automated denials, support appeals, or demonstrate compliance during review. |
| Accountability gaps in third-party AI deployment | Meridian remains responsible for deployment even if the vendor controls key model details. |
| Inaccurate automated denials | Qualified applicants may be incorrectly denied credit due to model error, incomplete data, or overly strict thresholds. |
| Lack of meaningful human oversight | Routing only 6% of applications to human review may be insufficient for a high-risk credit decision system. |

---

### 5. Vendor Record

<img width="799" height="714" alt="7  Vendor List " src="https://github.com/user-attachments/assets/0ffb06b0-6843-47c2-8dda-c6b992d03e3e" />

> **Caption:** This screenshot shows the CrediSure AI vendor record documenting the third-party provider responsible for the credit decisioning model.

**Skill demonstrated:** Third-party AI vendor risk management and vendor governance documentation.

---

### 6. Framework Assessments

<img width="1505" height="835" alt="ISO 42001 Part 1" src="https://github.com/user-attachments/assets/dc5ac0f7-da16-4fe9-ac50-e86fc03be3b5" /> 
<img width="1527" height="941" alt="ISO 42001 Part 2" src="https://github.com/user-attachments/assets/a6a6660a-df92-499f-9d10-b0a29d8da48b" />

> **Caption:** This screenshot shows selected framework assessment progress for NIST AI RMF, ISO/IEC 42001, and EU AI Act governance requirements.

**Skill demonstrated:** Practical framework application and evidence-based AI governance assessment.

---

### 7. Fundamental Rights Impact Assessment (FRIA) Summary

<img width="1531" height="823" alt="10  The EU AI Act Assessment" src="https://github.com/user-attachments/assets/03001655-4ef1-4ad8-a86a-5080bfc145fc" />

> **Caption:** This screenshot shows the EU AI Act Fundamental Rights Impact Assessment summary for the Meridian Automated Loan Underwriting System.

**Skill demonstrated:** Fundamental rights risk assessment, high-risk AI review, human oversight analysis, and conditional deployment recommendation.

---

### 8. Final Report

[Francois_Arthanas_AI_Governance_Portfolio_Report.pdf](https://github.com/user-attachments/files/28196322/Francois_Arthanas_AI_Governance_Portfolio_Report.pdf)

<img width="858" height="590" alt="image" src="https://github.com/user-attachments/assets/67c70b59-4f54-43f5-ade8-b6e73cf3780c" />

> **Caption:** This screenshot shows the final VerifyWise portfolio report generated for the Meridian Automated Loan Underwriting System.

**Skill demonstrated:** Governance evidence organization and final reporting.


## Final Recommendation

My final recommendation is:

> **Proceed with conditions.**

Meridian should not approve unrestricted production deployment at this time.

The system may move forward only if the following conditions are completed:

- Complete fairness testing and disparate impact analysis
- Complete proxy-bias review
- Validate denial reason codes
- Define mandatory human review triggers
- Establish appeal and reconsideration procedures
- Complete vendor documentation review
- Complete security and privacy review
- Define model and outcome monitoring thresholds
- Implement decision-level audit logging
- Establish incident escalation procedures
- Obtain governance committee approval

---

## Portfolio Conclusion

This project demonstrates my ability to evaluate a high-risk AI system from an AI governance, risk, and compliance perspective.

The Meridian Automated Loan Underwriting System offers business benefits, including faster decisions, improved consistency, and operational efficiency. However, because it affects access to credit and automates most decisions, it requires strong governance before deployment.

As AI Governance Lead, my assessment found that the system should not receive unrestricted production approval until Meridian completes required fairness, explainability, human oversight, vendor, monitoring, privacy, and governance controls.

This project reflects how I would support responsible AI deployment in a real organization.

---

## Disclaimer

This is a fictional educational portfolio project created for AI governance, risk, and compliance training. It does not represent legal advice, regulatory certification, credit decisioning advice, or an actual assessment of a real financial institution.

