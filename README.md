# Third-Party & Vendor Risk Management Toolkit

An open-source GRC portfolio project demonstrating a structured approach to third-party risk assessment, vendor due diligence, risk treatment, and AI vendor governance.

[![GRC](https://img.shields.io/badge/Domain-GRC-blue)]()
[![ISO 27001](https://img.shields.io/badge/Framework-ISO%2027001%3A2022-green)]()
[![ISO 42001](https://img.shields.io/badge/Framework-ISO%2042001-purple)]()
[![NIST CSF 2.0](https://img.shields.io/badge/Framework-NIST%20CSF%202.0-orange)]()
[![NIST AI RMF](https://img.shields.io/badge/Framework-NIST%20AI%20RMF-lightgrey)]()

## Overview

Organizations increasingly depend on third-party service providers, cloud platforms, SaaS applications, and AI vendors. These relationships can introduce information security, privacy, operational, regulatory, and AI-related risks.

This project demonstrates how a structured Third-Party Risk Management (TPRM) program can help organizations assess vendors, document risks, establish approval criteria, assign remediation actions, and monitor vendor risk throughout the relationship lifecycle.

The toolkit uses fictional organizations, vendors, and assessment data. It is intended for educational purposes and professional portfolio demonstration.

## Objectives

- Demonstrate practical GRC and third-party risk management concepts.
- Develop a repeatable vendor risk assessment process.
- Evaluate inherent risk and residual risk using documented scoring criteria.
- Incorporate AI-specific considerations into vendor due diligence.
- Establish risk-based vendor approval and monitoring procedures.
- Demonstrate control mapping to recognized security and AI risk frameworks.

## Toolkit Components

### 1. Vendor Risk Assessment Questionnaire

A 51-question questionnaire covering security, privacy, governance, operational resilience, and AI-related risks.

Includes eight AI-specific questions addressing topics such as:

- Use of customer data for AI model training.
- AI governance and accountability.
- AI risk assessment and impact assessment.
- Data protection and retention.
- Human oversight and monitoring.
- AI incident management.

### 2. Risk Scoring Methodology

A structured approach to evaluating vendor risk using:

- Inherent risk assessment.
- Weighted risk factors.
- Control effectiveness evaluation.
- Residual risk assessment.
- Risk acceptance and treatment criteria.
- Critical-control escalation rules.

**Key design principle:** A critical control failure can trigger a remediation requirement before approval, even when the calculated residual risk falls within the medium-risk category.

For example, an AI vendor that cannot provide adequate commitments concerning the use of customer data for model training may require further review and remediation before approval.

### 3. Vendor Due Diligence Checklist

A 34-item checklist designed to support vendor security reviews, including:

- Information security policies.
- Access control and authentication.
- Data protection and privacy.
- Incident response.
- Business continuity and disaster recovery.
- Cloud security.
- AI governance and risk management.

### 4. Vendor Risk Register

A centralized register for documenting:

- Vendor information and business purpose.
- Inherent risk ratings.
- Identified risks and control gaps.
- Existing controls.
- Residual risk ratings.
- Risk treatment plans.
- Responsible owners and review dates.

The example methodology uses a 5×5 likelihood-and-impact matrix.

### 5. Vendor Approval Workflow

A ten-stage vendor lifecycle workflow supported by an authority matrix.

The workflow is designed to cover vendor intake, risk classification, due diligence, assessment, remediation, approval, onboarding, monitoring, reassessment, and offboarding.

### 6. Continuous Monitoring

A risk-based monitoring approach that includes:

- Vendor risk tiers.
- Review frequency.
- Reassessment triggers.
- Security incident escalation.
- Remediation tracking.
- Risk dashboard and heat map.

## Framework References

The toolkit references the following frameworks and standards:

| Framework | Application |
|---|---|
| ISO/IEC 27001:2022 | Information security management and supplier-related security considerations |
| ISO/IEC 42001 | AI management systems and AI governance considerations |
| NIST Cybersecurity Framework 2.0 | Cybersecurity risk governance and management |
| NIST AI Risk Management Framework | AI risk identification, assessment, management, and monitoring |

Framework references are intended to support structured assessment and traceability. The presence of a reference does not mean every questionnaire item constitutes a formally verified control mapping.

## Repository Structure

```text
vendor-risk-assessment-toolkit/
├── README.md
├── questionnaire/
│   └── vendor-risk-questionnaire
├── risk-assessment/
│   └── risk-scoring-methodology
├── due-diligence/
│   └── vendor-due-diligence-checklist
├── risk-register/
│   └── vendor-risk-register
├── workflow/
│   └── vendor-approval-workflow
├── monitoring/
│   └── vendor-monitoring-plan
├── dashboard/
│   └── risk-dashboard
└── docs/
    └── methodology-and-limitations
```

*The directory structure above is a suggested organization. Update it to match the files actually included in the repository.*

## Example Use Case

A fictional healthcare technology organization plans to onboard an AI-enabled SaaS vendor that may process sensitive customer information.

The assessment process would:

1. Identify the vendor's business purpose and data access.
2. Determine the vendor's inherent risk tier.
3. Complete the security and AI risk questionnaire.
4. Review due diligence evidence.
5. Calculate residual risk based on documented criteria.
6. Identify critical control failures and remediation requirements.
7. Obtain the appropriate approval.
8. Establish ongoing monitoring and reassessment activities.

This scenario illustrates how vendor security reviews and AI governance considerations can be incorporated into one risk management workflow.

## Skills Demonstrated

- Governance, Risk and Compliance (GRC)
- Third-Party Risk Management (TPRM)
- Vendor Due Diligence
- Information Security Risk Assessment
- Inherent and Residual Risk Scoring
- ISO 27001 and ISO 42001 Framework Familiarity
- AI Governance and Risk Management
- Compliance Documentation
- Risk Treatment and Remediation Tracking
- Security Control Assessment

## Intended Audience

This portfolio project may be useful for:

- GRC and information security professionals.
- Third-party risk and vendor assurance teams.
- Organizations developing vendor assessment processes.
- Students and early-career professionals learning risk management.
- Consultants developing sample GRC documentation.

## Limitations and Disclaimer

This is an independent portfolio project using fictional data. It is not affiliated with or endorsed by ISO, NIST, or any employer.

The toolkit does not guarantee regulatory compliance, certification readiness, or vendor security. Organizations should adapt the materials to their business context, applicable legal obligations, risk appetite, and documented requirements.

Framework mappings and example scoring rules should be independently reviewed before operational use. The templates are not a substitute for professional judgment, legal advice, or an independent audit.

## Author

**Saad Ali**  
GRC Analyst | AI Governance | Information Security Risk Management

## Feedback and Contributions

Feedback, suggestions, and improvements are welcome. Contributions that improve the clarity of the assessment methodology, risk scoring, AI vendor due diligence, or monitoring workflow are especially valuable.

If you find this project useful, consider starring the repository.

