# Cyber Pros AI Governance Portfolio Project: Automated Loan Underwriting System (Francois B. Arthanas)

## Executive Summary

I served as the **AI Governance Lead** for a fictional high-risk AI governance assessment involving Meridian Financial Services, a mid-sized financial services company piloting an automated loan underwriting system.

The system uses a third-party AI model, **CrediSure Credit Decision Engine v2.3**, to evaluate small business loan applications and produce one of three outcomes:

- Auto-approve
- Auto-deny
- Route to manual review

Because approximately **94% of applications are processed automatically** and the system affects access to credit, I classified this as a **high-risk AI use case** requiring governance review before production deployment.

My final recommendation was:

> **Proceed with conditions. Meridian should not approve unrestricted production deployment until fairness testing, proxy-bias review, reason code validation, human oversight triggers, appeal procedures, vendor evidence review, monitoring thresholds, and governance committee approval are completed.**

<img width="1531" height="823" alt="10  The EU AI Act Assessment" src="https://github.com/user-attachments/assets/7ea423af-3db7-48bc-a618-10fd256f8c5d" />

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

## Business Context

Meridian Financial Services is a fictional mid-sized financial services company that provides financing products to small and medium-sized businesses, including:

- Small business loans
- Working capital loans
- Business lines of credit
- Equipment financing
- Merchant financing products

Meridian’s leadership team is under pressure to modernize the loan decision process. Traditional underwriting takes several business days, which may cause applicants to abandon the process, move to faster fintech lenders, or become frustrated by slow feedback.

To improve speed, consistency, and scalability, Meridian is piloting an AI-powered loan underwriting system.

However, the proposed system introduces significant AI governance risk because it:

- Affects access to credit
- Uses sensitive financial and credit-related data
- Relies on a third-party AI vendor
- Automates most loan decisions
- May create fairness, explainability, vendor, compliance, and human oversight risks

---

## Frameworks Applied

| EU AI Act | NIST AI Risk Management Framework | ISO/IEC 42001 |
|---|---|---|
| High-risk AI classification | For NIST AI RMF | Finally ISO |
| Fundamental Rights Impact Assessment | Another NIST | AND ISO |
| ISO/IEC 42001| AI management system scope | Sample |

| Human Review Rate | Approximately 6% routed to manual review |

The system evaluates small business loan applications using application data, cash-flow history, credit bureau data, business and guarantor credit information, requested loan amount, industry, geography, business age, fraud indicators, and historical repayment/default data.

The system produces one of three outcomes:

| Outcome | Description |
|---|---|
| Auto-approve | The application is approved without manual underwriting review. |
| Auto-deny | The application is denied without manual underwriting review. |
| Manual review | The application is routed to a human underwriter. |

---

## Central Governance Question

This portfolio answers one central question:

> **Should Meridian Financial Services approve production deployment of a 94% automated AI loan underwriting system?**

My answer:

> **Not for unrestricted production deployment. The system may proceed only with conditions because the current governance evidence does not fully support safe, fair, explainable, accountable, and well-monitored deployment.**

---

## Frameworks Applied

### EU AI Act

Used to assess:

- High-risk AI classification
- Fundamental Rights Impact Assessment
- Human oversight
- Logging
- Explanation to affected persons
- Appeal and contestability
- Deployment conditions

### NIST AI Risk Management Framework

Used to assess:

- Governance roles and responsibilities
- System context and intended use
- Risk measurement and testing evidence
- Risk prioritization and treatment
- Human-AI oversight

### ISO/IEC 42001

Used to assess:

- AI management system scope
- Organizational roles and responsibilities
- AI risk assessment
- AI risk treatment
- Management review
- AI system lifecycle management
- Third-party AI risk management

---

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

## Portfolio Artifacts

| Artifact | Purpose | Link |
|---|---|---|
| AI System Profile and Intake Record | Documents system purpose, users, affected groups, data, vendor, and risk classification. | [View Artifact](./artifacts/01-ai-system-profile-and-intake.md) |
| AI Risk Register and Mitigation Summary | Documents key AI risks, severity, controls, residual risk, and recommendations. | [View Artifact](./artifacts/02-ai-risk-register-and-mitigation-summary.md) |
| Human Oversight and Appeal Procedure | Defines human review triggers, override authority, escalation, and applicant appeal process. | [View Artifact](./artifacts/03-human-oversight-and-appeal-procedure.md) |
| Third-Party Vendor and Model Review | Evaluates CrediSure AI vendor risk, model limitations, and required evidence. | [View Artifact](./artifacts/04-third-party-vendor-and-model-review.md) |
| Framework Mapping | Maps the work to EU AI Act, NIST AI RMF, and ISO/IEC 42001. | [View Artifact](./artifacts/05-framework-mapping.md) |
| Production Readiness Decision Memo | Provides final executive recommendation. | [View Artifact](./artifacts/06-production-readiness-decision-memo.md) |
| Final VerifyWise Portfolio Report | Consolidated portfolio report generated from VerifyWise. | [View Report](./report/FirstName_LastName_AI_Governance_Portfolio_Report.pdf) |

---

## VerifyWise Screenshots

This repository includes selected screenshots from VerifyWise to demonstrate practical AI governance workflow experience.

> Replace each placeholder image with your actual screenshot. Use clear PNG files and avoid including private information, passwords, tokens, or personal email addresses.

### 1. Use Case Registration

![Use Case Registration](./screenshots/01-use-case-registration.png)

**Caption:** This screenshot shows the Meridian Automated Loan Underwriting System registered as a high-risk AI use case in VerifyWise.

**Skill demonstrated:** AI use case intake, risk classification, and governance workflow setup.

---

### 2. Model Inventory

![Model Inventory](./screenshots/02-model-inventory.png)

**Caption:** This screenshot shows the CrediSure Credit Decision Engine v2.3 documented in the model inventory.

**Skill demonstrated:** Model inventory documentation, model limitation tracking, and third-party AI model governance.

---

### 3. Dataset Record

![Dataset Record](./screenshots/03-dataset-record.png)

**Caption:** This screenshot shows the Small Business Loan Underwriting Dataset documented with data purpose, source, PII status, known bias concerns, and mitigation approach.

**Skill demonstrated:** Dataset governance, PII awareness, data source documentation, and bias mitigation planning.

---

### 4. AI Risk Register

![AI Risk Register](./screenshots/04-risk-register.png)

**Caption:** This screenshot shows the six priority AI risks documented for the Meridian Automated Loan Underwriting System.

**Skill demonstrated:** AI risk identification, risk rating, mitigation planning, residual risk analysis, and approval workflow documentation.

---

### 5. Vendor Record

![Vendor Record](./screenshots/05-vendor-record.png)

**Caption:** This screenshot shows the CrediSure AI vendor record documenting the third-party provider responsible for the credit decisioning model.

**Skill demonstrated:** Third-party AI vendor risk management and vendor governance documentation.

---

### 6. Framework Assessments

![Framework Assessments](./screenshots/06-framework-assessments.png)

**Caption:** This screenshot shows selected framework assessment progress for NIST AI RMF, ISO/IEC 42001, and EU AI Act governance requirements.

**Skill demonstrated:** Practical framework application and evidence-based AI governance assessment.

---

### 7. FRIA Summary

![FRIA Summary](./screenshots/07-fria-summary.png)

**Caption:** This screenshot shows the EU AI Act Fundamental Rights Impact Assessment summary for the Meridian Automated Loan Underwriting System.

**Skill demonstrated:** Fundamental rights risk assessment, high-risk AI review, human oversight analysis, and conditional deployment recommendation.

---

### 8. Final Report

![Final Report](./screenshots/08-final-report.png)

**Caption:** This screenshot shows the final VerifyWise portfolio report generated for the Meridian Automated Loan Underwriting System.

**Skill demonstrated:** Governance evidence organization and final reporting.

---

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

## Skills Demonstrated

| Skill | Evidence in This Portfolio |
|---|---|
| AI governance leadership | Led the end-to-end governance review as AI Governance Lead. |
| AI system intake | Documented system purpose, stakeholders, data, vendor, and risk classification. |
| AI risk assessment | Identified six priority AI risks and mitigation actions. |
| Framework application | Applied EU AI Act, NIST AI RMF, and ISO/IEC 42001 concepts. |
| Vendor AI risk management | Reviewed CrediSure AI and documented required vendor evidence. |
| Dataset governance | Documented PII, data sources, known bias, and mitigation approach. |
| Human oversight design | Defined manual review, escalation, override, and appeal procedures. |
| Executive communication | Prepared production readiness recommendation. |
| Evidence management | Organized governance evidence in VerifyWise. |
| Responsible AI decision-making | Recommended conditional approval instead of unrestricted deployment. |

---

## Portfolio Conclusion

This project demonstrates my ability to evaluate a high-risk AI system from an AI governance, risk, and compliance perspective.

The Meridian Automated Loan Underwriting System offers business benefits, including faster decisions, improved consistency, and operational efficiency. However, because it affects access to credit and automates most decisions, it requires strong governance before deployment.

As AI Governance Lead, my assessment found that the system should not receive unrestricted production approval until Meridian completes required fairness, explainability, human oversight, vendor, monitoring, privacy, and governance controls.

This project reflects how I would support responsible AI deployment in a real organization.

---

## Disclaimer

This is a fictional educational portfolio project created for AI governance, risk, and compliance training. It does not represent legal advice, regulatory certification, credit decisioning advice, or an actual assessment of a real financial institution.



