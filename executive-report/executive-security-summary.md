# Executive Security Summary
## Organisation: HarbourShield Insurance Brokers Pty Ltd

### Document Owner: Operations Manager
### Reviewed By: Managing Director
### Version: 1.0
### Document Status: Portfolio Project – Fictional Business Scenario

## 1. Executive Overview
HarbourShield Insurance Brokers Pty Ltd is a fictional Australian insurance brokerage with approximately 25 employees. The business handles customer personal information, insurance policy documents, claims information, financial records, insurer communications, supplier information, and internal business documents.

The purpose of this cyber security governance project is to design a practical, business-focused security framework suitable for a small-to-medium insurance brokerage. The framework focuses on governance, risk management, information asset management, access control, password and multi-factor authentication, data classification, backup and recovery, incident response, and supplier security review.

The project does not assume a dedicated internal cyber security team or enterprise-level tooling. Instead, it reflects a realistic SME environment where the business relies on cloud-based systems, outsourced IT support, SaaS vendors, and practical governance documentation.

## 2. Business Security Context
HarbourShield’s operations depend on several important systems and information assets, including:

| Area | Example |
| --- | --- |
| Email and collaboration | Microsoft 365, Outlook, Teams |
| Document storage | SharePoint and OneDrive |
| Customer and policy management | Cloud-based insurance CRM |
| Finance and invoicing | Xero |
| Website and enquiries | WordPress website |
| Insurance operations | Insurer portals |
| User devices | Windows laptops |
| Technical support | Outsourced IT provider |

The business risk is significant because the organisation handles sensitive customer and insurance-related information. A cyber security incident could affect customer trust, business operations, privacy obligations, financial processes, supplier relationships, and reputation.

## 3. Key Security Risks Identified
The cyber risk assessment identified several realistic risks for an SME insurance brokerage.

| Key Risk | Business Impact |
| --- | --- |
| Business email compromise | Fraudulent payment requests, customer impersonation, unauthorised mailbox access. |
| Weak or inconsistent MFA | Increased risk of account compromise. |
| Unauthorised CRM access | Exposure of customer, policy, and renewal information. |
| Former employee access not removed | Unauthorised access to business systems after termination. |
| Accidental data disclosure | Customer documents sent to the wrong recipient. |
| Ransomware or malware | Disruption to business operations and potential file loss. |
| Supplier security failure | Exposure or disruption through CRM, IT provider, website host, or SaaS supplier. |
| Weak backup and recovery assurance | Difficulty recovering from deletion, ransomware, or supplier outage. |
| Poor access governance | Excessive permissions and limited accountability. |
| Website compromise | Public reputational impact and potential exposure of enquiry data. |

The highest-priority risks are account compromise, customer data exposure, supplier security weakness, and recovery readiness.

## 4. Current Security Maturity Assessment
The current security maturity is assessed as developing.

| Security Area | Security Position | Target Position |
| --- | --- | --- |
| Governance | Basic security ownership exists but requires formal documentation. | Clear governance charter, owners, review cycle, and reporting. |
| Asset management | Key systems are known but not formally documented. | Maintained information asset register. |
| Risk management | Risks are understood informally. | Formal cyber risk register with owners and treatment plans. |
| Access control | Access is role-based in some systems but inconsistently reviewed. | Six-monthly access reviews and clear joiner/mover/leaver process. |
| MFA | Enabled for some systems but not consistently enforced. | MFA required for all critical systems where supported. |
| Policy framework | Policies are incomplete or informal. | Practical SME security policy pack. |
| Incident response | Incident response is informal. | Documented incident response plan and severity matrix. |
| Supplier security | Suppliers are used but not consistently reviewed. | Supplier security checklist and annual critical supplier review. |
| Backup and recovery | Some recovery options exist but testing is limited. | Documented backup ownership and annual recovery testing. |

## 5. Governance Improvements Completed
The following governance artefacts were developed as part of this project:

| Artefact | Purpose |
| --- | --- |
| Business Security Context | Defines the company scenario, technology environment, data types, and project scope. |
| Information Security Governance Charter | Defines security ownership, decision-making, risk ownership, reporting, and review cycle. |
| Roles and Responsibilities Matrix | Defines RACI responsibilities for security governance activities. |
| Information Asset Register | Identifies key systems, data types, owners, classifications, and criticality. |
| Cyber Risk Register | Records key cyber risks, likelihood, impact, controls, treatment actions, and owners. |
| Information Security Policy | Establishes the parent security policy. |
| Access Control Policy | Defines user access, privileged access, access reviews, and joiner/mover/leaver process. |
| Acceptable Use Policy | Defines secure and acceptable use of systems, devices, email, internet, and cloud tools. |
| Password and MFA Policy | Defines authentication requirements for business and privileged accounts. |
| Data Classification Policy | Defines Public, Internal, Confidential, and Restricted data handling requirements. |
| Backup and Recovery Policy | Defines backup ownership, recovery expectations, testing, and ransomware considerations. |
| Incident Response Plan | Defines reporting, triage, containment, recovery, communication, and lessons learned. |
| Incident Severity Matrix | Supports consistent incident prioritisation and escalation. |
| Supplier Security Review Checklist | Supports review of outsourced IT, SaaS, CRM, website hosting, and other suppliers. |

These documents provide a practical foundation for security governance in a small insurance brokerage environment.

## 6. Priority Recommendations
The following recommendations should be prioritised.

### Priority 1: Enforce MFA on Critical Systems
MFA should be enabled for Microsoft 365, insurance CRM, Xero, WordPress administrator accounts, remote access, password managers, and privileged administrator accounts.

Expected benefit:
- Reduces likelihood of account compromise.
- Reduces business email compromise risk.
- Improves protection for customer, policy, and finance information.

### Priority 2: Complete Access Reviews
HarbourShield should perform six-monthly access reviews for key systems.

Systems to review:
- Microsoft 365.
- SharePoint and OneDrive.
- Insurance CRM.
- Xero.
- WordPress.
- Insurer portals.
- Password manager.
- Outsourced IT administrator access.

Expected benefit:
- Removes unnecessary access.
- Reduces former employee and excessive permission risks.
- Improves system owner accountability.

### Priority 3: Improve Backup and Recovery Assurance
Backup and recovery arrangements should be confirmed and tested for critical systems.

Focus areas:
- CRM recovery options.
- Microsoft 365 retention and recovery.
- SharePoint and OneDrive version history.
- Xero recovery and export options.
- WordPress backup restore.
- Recovery testing records.

Expected benefit:
- Improves resilience against ransomware, accidental deletion, and supplier outages.
- Reduces operational disruption.

### Priority 4: Formalise Incident Response
The Incident Response Plan and Incident Severity Matrix should be communicated to staff and tested using a simple tabletop exercise.

Suggested tabletop scenarios:
- Broker mailbox compromise.
- Customer document sent to wrong recipient.
- Ransomware affecting shared files.
- Supplier breach notification.
- Fraudulent bank detail change request.

Expected benefit:
- Improves response speed.
- Reduces confusion during incidents.
- Supports better decision-making and escalation.

### Priority 5: Review Critical Suppliers
Critical suppliers should be reviewed using the Supplier Security Review Checklist.

Priority suppliers:
- Outsourced IT provider.
- Insurance CRM vendor.
- Microsoft 365 environment.
- Xero.
- WordPress hosting provider.
- Insurer portals.

Expected benefit:
- Improves visibility of third-party risk.
- Clarifies supplier recovery and incident notification responsibilities.
- Reduces dependency risk.

## 7. Suggested 90-Day Security Improvement Roadmap

| Timeframe | Action | Owner |
| --- | --- | --- |
| Days 1-5 | Approve governance charter and policy pack. | Managing Director |
| Days 1-30 | Confirm MFA status for critical systems. | Operations Manager / Outsourced IT Provider |
| Days 1-30 | Complete initial access review for Microsoft 365, CRM, Xero, and WordPress. | Operations Manager / System Owners |
| Days 30-45 | Validate asset register and assign owners for all key systems. | Operations Manager |
| Days 30-60 | Review backup and recovery options for critical systems. | Operations Manager / Outsourced IT Provider |
| Days 45-60 | Conduct supplier security review for outsourced IT provider and CRM vendor. | Operations Manager |
| Days 60-75 | Run incident response tabletop exercise. | Operations Manager |
| Days 75-90 | Update cyber risk register and treatment plan based on findings. | Operations Manager |
| Days 75-90 | Present security progress update to Managing Director. | Operations Manager |

## 8. Suggested Security Metrics
The Managing Director should receive a quarterly security update using simple business-level metrics.

| Metric | Target |
| --- | --- |
| Critical systems with MFA enabled | 100% where supported |
| High and critical cyber risks open | Trending downward |
| Access reviews completed | Every six months |
| Critical suppliers reviewed | At least annually |
| Recovery tests completed | At least annually for critical systems |
| Security incidents recorded | 100% of reported incidents |
| High and critical incidents with post-incident review | 100% |
| Employees completing security awareness | 100% annually |
| Former employee access removed | Promptly after termination |

## 9. Business Benefits
The completed framework provides the following business benefits:

| Benefit| Explanation |
| --- | --- |
| Stronger customer trust | Better protection of customer, policy, and claims information. |
| Better accountability | Clear owners for security decisions, risks, assets, and incidents. |
| Reduced account compromise risk | Stronger access control, MFA, and password requirements. |
| Improved incident readiness | Clear response steps and escalation paths. |
| Better supplier visibility | Supplier checklist supports third-party risk review. |
| Improved resilience | Backup and recovery expectations reduce disruption. |
| Practical compliance support | Documentation supports privacy, governance, and cyber resilience expectations. |
| Scalable security foundation | The framework can mature as the business grows. |

## 10. Key Decisions Required
The following decisions should be made by business leadership:

| Decision | Recommended Direction |
| --- | --- |
| Security governance approval | Approve the governance charter and policy pack. |
| MFA enforcement | Require MFA for all critical systems where supported. |
| Access review schedule | Perform access reviews every six months. |
| Supplier review schedule | Review critical suppliers annually. |
| Backup recovery testing | Test key recovery processes at least annually. |
| Incident response testing | Run one tabletop exercise per year. |
| Risk reporting | Receive quarterly cyber security updates. |
| Risk acceptance | Managing Director to approve medium, high, and critical risk acceptance. |

## 11. Executive Conclusion
HarbourShield’s cyber security risks are manageable with practical governance, clear ownership, improved access control, stronger authentication, supplier review, backup assurance, and incident readiness.

The most important immediate improvements are MFA enforcement, access reviews, backup and recovery validation, supplier security review, and incident response testing.

This project provides a realistic SME cyber security governance framework that can be used as a foundation for ongoing improvement without requiring enterprise-level tools or a dedicated internal cyber security team.

## 12. Portfolio Note
This document is part of a fictional cyber security governance portfolio project. It demonstrates executive-level cyber security reporting, risk communication, governance planning, and SME security prioritisation for an Australian insurance brokerage scenario.

This document is not legal advice, compliance advice, or a complete ISO/IEC 27001 implementation.
