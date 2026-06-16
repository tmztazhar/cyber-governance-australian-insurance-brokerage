# Incident Severity Matrix
## Project: Cyber Security Governance Framework for an Australian Insurance Brokerage

### Organisation: HarbourShield Insurance Brokers Pty Ltd
### Document Owner: Operations Manager
### Approved By: Managing Director
### Version: 1.0
### Document Status: Portfolio Project – Fictional Business Scenario

## 1. Purpose
The purpose of this Incident Severity Matrix is to help HarbourShield Insurance Brokers Pty Ltd assess and prioritise cyber security incidents based on business impact, information sensitivity, operational disruption, customer impact, financial risk, and likelihood of escalation.

This matrix supports consistent decision-making during incident response and helps determine when incidents must be escalated to the Managing Director, outsourced IT provider, external compliance consultant, legal adviser, supplier, insurer, or other external parties.

## 2. Scope
This matrix applies to cyber security incidents involving:
- Microsoft 365, SharePoint, OneDrive, insurance CRM, Xero, WordPress, insurer portals, laptops, and approved business systems.
- Customer, employee, insurer, supplier, policy, claims, financial, and operational information.
- Employees, contractors, temporary workers, authorised third parties, outsourced IT providers, and suppliers.
- Suspected or confirmed incidents affecting confidentiality, integrity, or availability.

## 3. Severity Levels
HarbourShield uses four severity levels:

| Severity | Description | Management Attention |
| --- | --- | --- |
| Low | Minor event with little or no confirmed impact. | Managed by Operations Manager. |
| Medium | Localised issue requiring investigation and corrective action. | Managed by Operations Manager with outsourced IT support where required. |
| High | Confirmed or likely compromise affecting sensitive information, business systems, or multiple users. | Escalate to Managing Director. |
| Critical | Major incident affecting critical systems, customer information, business continuity, fraud, ransomware, or public exposure. | Immediate Managing Director escalation. |

## 4. Severity Assessment Criteria
Incident severity should be assessed using the following criteria.

| Criteria | Low | Medium | High | Critical |
| --- | --- | --- | --- | --- |
| Data sensitivity | Public or Internal information only. | Limited Confidential information may be involved. | Confidential information confirmed or likely involved. | Restricted information, identity documents, large customer data set, or serious claims information involved. |
| Number of people affected | Single user or no affected user. | One user or small internal group. | Multiple users, customers, or business functions. | Many customers, business-wide impact, or unknown large scope. |
| Business impact | No disruption or minor inconvenience. | Limited disruption to one user or process. | Disruption to important business process. | Major disruption to critical systems or business operations. |
| System criticality | Non-critical system. | Important but non-critical system. | Critical business system affected. | Multiple critical systems or core customer/finance systems affected. |
| Account compromise | No compromise confirmed. | Suspicious activity but compromise unconfirmed. | Confirmed compromise of standard user account. | Privileged account, finance account, or multiple accounts compromised. |
| Financial risk | No financial impact. | Possible low-value financial risk. | Confirmed fraud attempt or material financial exposure. | Successful fraud, payment redirection, or major financial loss. |
| Legal / regulatory concern | No likely concern. | Unclear; requires internal review. | External compliance or legal advice may be required. | Customer, regulator, insurer, or legal notification likely needs assessment. |
| Reputational impact | No expected impact. | Limited internal concern. | Customer trust may be affected. | Public, customer, insurer, or media impact possible. |
| Supplier involvement | No supplier impact. | Supplier support needed. | Supplier incident may affect HarbourShield data or access. | Critical supplier breach or outage affecting customer information or operations. |

## 5. Severity Decision Guide
Use the highest applicable severity level. If unsure between two levels, select the higher level until more information is available.

| Severity | Example Incident |
| --- | --- |
| Low | Phishing email received but not clicked. |
| Low | Spam email blocked by email filter. |
| Low | Non-sensitive internal file deleted but easily restored. |
| Medium | User clicked suspicious link but no compromise confirmed yet. |
| Medium | Laptop temporarily misplaced but recovered quickly with no evidence of access. |
| Medium | Small number of internal files accidentally shared with another employee. |
| High | Confirmed mailbox compromise of an insurance broker. |
| High | Customer policy document sent to the wrong external recipient. |
| High | Malware detected on company laptop used for customer work. |
| High | Suspicious Xero activity or attempted invoice fraud. |
| Critical | Ransomware affecting shared files or multiple laptops. |
| Critical | Insurance CRM compromise or unauthorised access to customer records. |
| Critical | Large customer data exposure. |
| Critical | Compromise of Microsoft 365 administrator account. |
| Critical | Supplier breach involving customer identity documents or policy records. |

## 6. Escalation Requirements by Severity
| Severity | Escalation Requirement | Response Owner |
| --- | --- | --- |
| Low | Record if useful. No formal escalation unless trend is observed. | Operations Manager |
| Medium | Record incident and engage outsourced IT provider where technical review is needed. | Operations Manager |
| High | Escalate to Managing Director and outsourced IT provider. Consider external compliance or legal advice. | Operations Manager and Managing Director |
| Critical | Immediate escalation to Managing Director, outsourced IT provider, and relevant external advisers or suppliers. | Managing Director |

## 7. Response Time Guidance
The response times below are guidance for prioritisation, not strict legal or contractual deadlines.

| Severity | Initial Review Target | Containment Priority |
| --- | --- | --- |
| Low | Within 2 business days | As required |
| Medium | Within 1 business day | Same day where practical |
| High | Same business day | Urgent containment required |
| Critical | Immediate | Immediate containment required |

## 8. Notification Assessment Triggers
The Operations Manager must escalate to the Managing Director if any of the following are suspected or confirmed:
- Customer personal information may have been accessed, disclosed, lost, or misused.
- Insurance policy documents or claims information may be exposed.
- Identity documents may be involved.
- A privileged account may be compromised.
- Finance systems, invoices, payment instructions, or bank details are affected.
- Ransomware, malware, or system-wide compromise is suspected.
- A supplier reports a breach affecting HarbourShield.
- A critical system is unavailable for a material period.
- Public website compromise may expose customer enquiry information.
- The incident may require customer, insurer, supplier, legal, regulatory, or cyber insurance notification assessment.

## 9. Incident Type Severity Examples
### 9.1 Phishing

| Scenario | Severity |
| --- | --- |
| Phishing email received, not clicked, no credentials entered. | Low |
| User clicked suspicious link but did not enter credentials. | Medium |
| User entered credentials but no confirmed misuse yet. | High |
| User credentials used to access mailbox or customer systems. | High or Critical |

### 9.2 Business Email Compromise

| Scenario | Severity |
| --- | --- |
| Suspicious login blocked. | Medium |
| Broker mailbox compromised with no customer data confirmed exposed. | High |
| Broker mailbox used to send fraudulent emails to customers or insurers. | High |
| Finance mailbox compromised and bank detail change fraud attempted. | High or Critical |
| Multiple mailboxes compromised. | Critical |

### 9.3 Data Disclosure

| Scenario | Severity |
| --- | --- |
| Internal document sent to wrong internal recipient. | Low or Medium |
| Customer document sent to wrong internal team member. | Medium |
| Customer policy document sent to wrong external recipient. | High |
| Identity documents or claims files sent to wrong external recipient. | High or Critical |
| Large set of customer records exposed publicly. | Critical |

### 9.4 Malware and Ransomware

| Scenario | Severity |
| --- | --- |
| Malware blocked with no infection. | Low |
| Malware detected on one laptop with limited impact. | Medium or High |
| Malware infection affects customer documents or cloud sync. | High |
| Ransomware affects shared files or multiple devices. | Critical |
| Ransomware affects CRM, SharePoint, or finance operations. | Critical |

### 9.5 Lost or Stolen Device

| Scenario | Severity |
| --- | --- |
| Supplier outage with no data impact and short downtime. | Medium |
| Supplier reports security incident but HarbourShield data not affected. | Medium |
| Supplier breach may involve HarbourShield customer data. | High |
| Supplier breach confirmed involving customer records or identity documents. | Critical |

### 9.7 Website Compromise

| Scenario | Severity |
| --- | --- |
| Minor website defacement with no customer data impact. | Medium |
| WordPress admin account compromised. | High |
| Website enquiry form data accessed or exposed. | High |
| Website used to distribute malware or collect customer details fraudulently. | Critical |

## 10. Severity Reassessment
Incident severity may change as more information becomes available.

Severity should be reassessed when:
- New evidence is discovered.
- More systems or users are found to be affected.
- Customer information is confirmed involved.
- A supplier provides updated breach information.
- Business disruption increases.
- Fraud or financial loss is confirmed.
- External notification assessment becomes necessary.

The Operations Manager should update the incident log when severity changes.

## 11. Closure Requirements by Severity
| Scenario | Closure Requirement |
| --- | --- |
| Low | Confirm issue resolved or no further action required. |
| Medium | Record actions taken and any improvement required. |
| High | Complete incident record, management update, lessons learned, and improvement actions. |
| Critical | Complete formal post-incident review, management approval for closure, and tracked improvement plan. |

High and Critical incidents should not be closed until containment, recovery, notification assessment, and lessons learned are completed.

## 12. Roles and Responsibilities
| Role | Responsibility |
| --- | --- |
| Managing Director | Owns major incident decisions and approves closure of High and Critical incidents. |
| Operations Manager | Assigns initial severity, maintains incident log, coordinates escalation and response. |
| Outsourced IT Provider | Provides technical assessment, containment, recovery, and evidence support. |
| System Owner | Provides business impact and data sensitivity information. |
| Finance Manager | Assesses finance fraud, payment, Xero, and invoice-related impact. |
| Broker Team Lead | Assesses customer, policy, claims, insurer portal, and broker communication impact. |
| Marketing Coordinator | Assesses website, enquiry form, and public content impact. |
| External Compliance Consultant | Advises on privacy, breach notification, and regulatory considerations. |
| External Legal Adviser | Advises on legal, contractual, customer, or external notification issues where required. |

## 13. Related Documents
This matrix should be read together with:
- Incident Response Plan.
- Information Security Policy.
- Data Classification Policy.
- Access Control Policy.
- Password and MFA Policy.
- Backup and Recovery Policy.
- Cyber Risk Register.
- Information Asset Register.
- Third-Party Security Review Checklist.

## 14. Review Cycle
This matrix should be reviewed:
- At least annually.
- After a High or Critical incident.
- After an incident response tabletop exercise.
- After a major system or supplier change.
- When business, legal, regulatory, or technology requirements change.
