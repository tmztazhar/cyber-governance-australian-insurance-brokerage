## **1. Project Overview**

HarbourShield Insurance Brokers Pty Ltd is a fictional Australian Insurance Brokerage used for a cyber security governance portfolio project. The purpose of this project is to design a practical cyber security governance framework suitable or a small-to-medium insurance brokerage that handles sensitive customer, policy, claim, and business information.

The project focuses on governance, risk management, policy development, incident response planning, asset clarification, and third-party security review. It is designed to demonstrate practical GRC capability for a cyber security analyst, GRC analyst, or junior security consultant.

## **2. Business Scenario**

HarbourShield provides insurance brokerage services to small businesses and individual customers in Australia. The company helps customers compare insurance options, submit applications, manage policy renewals, and communicate with insurers.

The business operates with approximately 25 employees and uses a hybrid working model. Most business systems are cloud-based, including email, document storage, CRM, accounting, and customer communications.

Because the brokerage handles personal information, insurance records, policy documents, claims information, and customer communications, cyber security governance is required to reduce the likelihood and impact of data breaches, unauthorised access, ransomware, business email compromise, and third-party failures.

## **3. Business Objectives**

The security governance framework supports the following business objectives:

| Business Objective | Security Relevance |
| --- | --- |
| Protect customer trust | Reduce risk of personal data exposure |
| Maintain business operation | Improve resilience against ransomware and system outages |
| Support compliance expectations | Align with privacy, cyber resilience, and industry expectations |
| Improve staff accountability | Define clear responsibilities for security decisions |
| Manage supplier risk | Review cloud, CRM, IT support, and insurer portal dependencies |
| Enable scalable growth | Create repeatable governance processes as the business grows |

## **4. Technology Environment**

| System /Platform | Business Use | Security Concern |
| --- | --- | --- |
| Microsoft 365 | Email, documents, collaboration | MFA, Phishing, mailbox compromise |
| SharePoint / OneDrive | File storage | Access permissions, data leakage |
| Insurance CRM | Customer and policy records | Sensitive data access, third-party risk |
| Xero | Accounting and invoicing | Finance fraud, account compromise |
| Wordpress website | Marketing and customer enquiries | Plugin vulnerabilities, spam, unauthorised admin access |
| Windows laptops | Staff workstations | Malware, patching, endpoint protection |
| Remote access | Hybrid work | Weak passwords, unmanaged devices |
| Outsourced IT provider | IT administration and support | Privileged access, supplier dependency |

## **5. Sensitive Information Handled**

| Data Type | Example | Risk if Compromised |
| --- | --- | --- |
| Personal information | Name, address, phone, email | Privacy breach, phishing |
| Identity information | Date of birth, licence/passport details | Identity theft |
| Insurance policy data | Policy numbers, coverage details | Customer harm, reputational damage |
| Claims information | Incident reports, supporting documents | Sensitive exposure |
| Financial information | Premiums, invoices, payment records | Fraud, financial loss |
| Business customer information | Revenue, assets, operations | Commercial confidentiality breach |

## **6. Key Cyber Security Concerns**

The key cyber security concerns for HarbourShield are:

| Risk Area | Example Scenario |
| --- | --- |
| Business email compromise | Broker email account compromised and used to redirect customer payments |
| Ransomeware | Staff laptop infected, leading to encrypted shared files |
| Weak access control | Former employee retains access to CRM or email |
| Lack of MFA | Attacker accesses cloud systems using stolen passwords |
| Poor data handling | Sensitive policy documents shared with the wrong recipient |
| Third-party failure | CRM or outsourced IT provider suffers a breach |
| Inadequate incident response | Business does not know who to notify or what steps to take during a breach |
| Weak governance | No clear owner for cyber risk decisions |

## **7. Applicable Frameworks and References**

The framework is aligned with ISO/IEC 27001:2022 at a practical SME level. ISO describes ISO/IEC 27001 as a standard for establishing an information security management system and applying a risk management process adapted to the organisation’s size and needs.

ASIC cyber resilience guidance is also relevant because insurance brokers and financial services businesses need to consider cyber and operational resilience as part of maintaining trust and protecting customers.

APRA CPS 234 is not treated as a direct compliance requirement for this fictional brokerage unless it is APRA-regulated. However, it is useful as a financial-sector reference because APRA describes CPS 234 as focused on resilience against information security incidents and protection of confidentiality, integrity, and availability.

## **8. Project Scope**

The project includes:

| In Scope |
| --- |
| Governance charter |
| Roles and responsibilities |
| Information asset register |
| Cyber risk register |
| SME security policy pack |
| Incident response plan |
| Third-party risk checklist |
| Executive security summary |

## **9. Out of Scope**

The project does not include:

| Out of Scope | Reason |
| --- | --- |
| Full ISO/IEC 27001 certification | Too large for a portfolio project |
| Penetration Testing | Separate technical project |
| SIEM deployment | Not realistic for this SME scenario |
| Enterprise GRC tooling | Not required for a small brokerage |
| Full legal compliance advice | Portfolio project only, not legal advice |
| APRA-regulated entity compliance audit | Brokerage is treated as SME, not APRA-regulated insurer |

## **10. Assumptions**

The project assumes:

| Assumption |
| --- |
| The company has 25 employees |
| IT support is outsourced |
| Most systems are cloud-based |
| The company has no formal cyber security team |
| MFA is partially implemented but not consistently enforced |
| Security policies are incomplete or outdated |
| There is no formal risk register |
| Incident response is informal |
| Supplier security reviews are not consistently performed |
