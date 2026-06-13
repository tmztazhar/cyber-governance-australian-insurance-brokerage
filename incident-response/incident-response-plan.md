# Incident Response Plan

## Project: Cyber Security Governance Framework for an Australian Insurance Brokerage

### Organisation: HarbourShield Insurance Brokers Pty Ltd
### Document Owner: Operations Manager
### Approved By: Managing Director
### Version: 1.0
### Document Status: Portfolio Project – Fictional Business Scenario

## 1. Purpose
The purpose of this Incident Response Plan is to define how HarbourShield Insurance Brokers Pty Ltd identifies, reports, assesses, escalates, contains, recovers from, and reviews cyber security incidents.

HarbourShield handles customer personal information, insurance policy documents, claims information, financial records, insurer communications, and internal company documents. A cyber security incident could affect customer trust, business operations, legal or regulatory obligations, financial processes, and the company’s reputation.

This plan provides a practical incident response approach suitable for a small-to-medium Australian insurance brokerage that uses cloud-based systems and outsourced IT support.

## 2. Incident Response Objectives
The objectives of this plan are to:
1. Ensure suspected incidents are reported quickly.
2. Provide a clear escalation path for employees and management.
3. Reduce the impact of cyber security incidents on customers and business operations.
4. Support containment, recovery, and evidence preservation.
5. Clarify the roles of HarbourShield, outsourced IT providers, system owners, and external advisers.
6. Support appropriate assessment of customer, legal, regulatory, insurer, and supplier notification requirements.
7. Capture lessons learned and improve controls after incidents.

## 3. Scope
This plan applies to:
- All employees, contractors, temporary workers, and authorised third parties.
- All HarbourShield business systems and information assets.
- Microsoft 365, SharePoint, OneDrive, insurance CRM, Xero, WordPress, insurer portals, laptops, backups, and approved business systems.
- Customer, employee, supplier, insurer, policy, claims, financial, and operational information.
- Incidents involving outsourced IT providers, cloud platforms, SaaS vendors, website hosting providers, or other third-party suppliers.
- Suspected, confirmed, or attempted security events that may affect confidentiality, integrity, or availability.

## 4. Definition of a Cyber Security Incident
A cyber security incident is any suspected or confirmed event that may compromise the confidentiality, integrity, or availability of HarbourShield systems, information, accounts, devices, or business operations.

Examples include:
- Suspicious email or phishing attempt.
- Business email compromise.
- Suspected account compromise.
- Lost or stolen laptop.
- Malware or ransomware infection.
- Unauthorised access to customer information.
- Accidental email sent to the wrong recipient.
- Public exposure of confidential documents.
- Website compromise.
- Unusual CRM, Xero, Microsoft 365, or insurer portal activity.
- Supplier breach notification.
- Unauthorised change to payment or bank account details.
- Data deletion, corruption, or unauthorised file sharing.

## 5. Incident Response Principles
HarbourShield’s incident response approach is based on the following principles:

| Principle | Description |
| --- | --- |
| Report early | Employees must report suspicious activity quickly, even if they are unsure. |
| Contain first | The immediate priority is to limit further harm. |
| Preserve evidence | Relevant logs, emails, screenshots, and records should be preserved where possible. |
| Protect customers | Incidents involving customer information must be assessed carefully. |
| Business-led response | Cyber incidents are business risks, not only IT issues. |
| Clear escalation | Serious incidents must be escalated to the Managing Director. |
| Practical response | Response actions should be realistic for an SME environment. |
| Learn and improve | Lessons learned must be used to improve controls and awareness. |

## 6. Incident Response Roles
| Role | Responsibility |
| --- | --- |
| Managing Director | Accountable for major incident decisions, customer communication approval, regulatory escalation decisions, and risk acceptance. |
| Operations Manager | Coordinates incident response, triage, documentation, escalation, communication, and post-incident review. |
| Outsourced IT Provider | Provides technical investigation, containment, recovery, log review, account reset, malware removal, and system restoration support. |
| System Owner | Provides business context, confirms affected data or users, and supports access or process decisions. |
| Finance Manager | Supports incidents involving invoices, payment fraud, Xero, bank detail changes, or financial loss. |
| Broker Team Lead | Supports incidents involving customer policy documents, insurer portals, client communications, or broker access. |
| Marketing Coordinator | Supports incidents involving WordPress, website enquiry forms, public content, or website supplier coordination. |
| Employees | Report suspected incidents promptly and follow instructions during incident response. |
| External Compliance Consultant | Provides advice on privacy, breach notification, insurance, and regulatory considerations where required. |
| External Legal Adviser | Provides legal advice where customer impact, contractual issues, or formal notification obligations may exist. |

## 7. Incident Reporting
Employees must report suspected or confirmed incidents as soon as possible.

Incidents should be reported to:
`Operations Manager` ---> `Outsourced IT Provider` ---> `Managing Director, where required`

If the Operations Manager is unavailable, employees should contact the Managing Director or outsourced IT provider directly.

Employees should not ignore, hide, delete, or attempt to fix serious incidents without guidance.

## 8. Information to Include in an Incident Report
When reporting an incident, employees should provide as much of the following information as possible:

| Information Required | Example |
| --- | --- |
| Reporter name | Employee who noticed the issue |
| Date and time noticed | When the issue was first identified |
| System affected | Microsoft 365, CRM, Xero, laptop, WordPress |
| Description | What happened or what looks suspicious |
| People involved | User account, customer, supplier, or third party |
| Information involved | Customer records, policy documents, invoices |
| Actions already taken | Email reported, device disconnected, password changed |
| Screenshots or evidence | Suspicious email, error message, alert |
| Business impact | Unable to access system, possible data exposure |
| Urgency | Low, Medium, High, Critical |

## 9. Incident Severity Levels
HarbourShield uses four severity levels.

| Severity | Description | Example |
| --- | --- | --- |
| Low | Limited issue with little or no business or data impact. | Single phishing email reported and not clicked. |
| Medium | Localised issue requiring investigation but limited business impact. | User clicked suspicious link but no compromise confirmed. |
| High | Confirmed or likely compromise affecting sensitive information, business systems, or multiple users. | Mailbox compromise, customer data sent to wrong recipient, malware on company laptop. |
| Critical | Major incident affecting critical systems, customer information, business continuity, ransomware, fraud, or public exposure. | Ransomware, CRM compromise, large customer data exposure, major supplier breach. |

High and Critical incidents must be escalated to the Managing Director.

## 10. Incident Response Phases
HarbourShield follows seven incident response phases:
1. Prepare
2. Identify
3. Triage and Assess
4. Contain
5. Eradicate
6. Recover
7. Review and Improve

## 11. Phase 1: Prepare
Preparation activities reduce the likelihood and impact of incidents.

Preparation includes:
- Maintaining this Incident Response Plan.
- Maintaining the Cyber Risk Register.
- Maintaining the Information Asset Register.
- Ensuring MFA is enabled for critical systems where supported.
- Ensuring access reviews are performed periodically.
- Ensuring important business information is backed up or recoverable.
- Ensuring employees know how to report incidents.
- Maintaining outsourced IT provider contact details.
- Maintaining supplier support contact details.
- Keeping security policies available to employees.
- Conducting basic security awareness activities.

## 12. Phase 2: Identify
The purpose of this phase is to determine whether an unusual event may be a security incident.

Possible detection sources include:
- Employee reports.
- Suspicious email reports.
- Microsoft 365 alerts.
- Antivirus or endpoint protection alerts.
- Unusual login activity.
- CRM or Xero access alerts.
- Website alerts.
- Supplier notifications.
- Customer complaints.
- Finance irregularities.
- Unexpected MFA prompts.
- Unusual file sharing or deletion activity.

The Operations Manager should record the incident and involve the outsourced IT provider where technical investigation is required.

## 13. Phase 3: Triage and Assess
The purpose of triage is to understand the likely severity, impact, and required response.

Triage questions include:
1. What system, account, device, or information is affected?
2. Is customer information involved?
3. Is Confidential or Restricted information involved?
4. Is the incident still active?
5. Is there evidence of unauthorised access?
6. Is there evidence of data loss, disclosure, deletion, or corruption?
7. Are business operations disrupted?
8. Are finance systems, invoices, or payment details affected?
9. Is a third-party supplier involved?
10. Does the incident require escalation to the Managing Director?
11. Is external compliance or legal advice required?

The Operations Manager should assign an initial severity rating and update it as more information becomes available.

## 14. Phase 4: Contain
Containment aims to stop the incident from spreading or causing further harm.

Possible containment actions include:
| Incident Type | Possible Containment Action |
| --- | --- |
| Phishing email | Remove email, block sender, warn users. |
| Account compromise | Reset password, revoke sessions, enable or reset MFA, review mailbox rules. |
| Lost laptop | Disable account access, locate or wipe device where possible, assess data exposure. |
| Malware | Disconnect device, isolate from network, engage outsourced IT provider. |
| Ransomware | Isolate affected systems, stop file synchronisation where appropriate, preserve evidence. |
| Incorrect email recipient | Attempt recall where possible, contact recipient, request deletion, assess data involved. |
| Website compromise | Disable affected plugin or admin account, take site offline if needed, restore clean version. |
| Supplier breach | Confirm scope, affected data, supplier actions, and contractual notification details. |
| Finance fraud | Stop payment where possible, verify bank details, escalate to finance and management. |

Containment actions should be coordinated with the outsourced IT provider and relevant system owner.

## 15. Phase 5: Eradicate
Eradication removes the cause of the incident.

Possible eradication actions include:
- Remove malware from affected devices.
- Delete malicious mailbox rules.
- Remove unauthorised forwarding rules.
- Disable unauthorised accounts.
- Remove unauthorised access permissions.
- Patch vulnerable software.
- Remove unsafe browser extensions or plugins.
- Disable compromised WordPress plugins or themes.
- Reset compromised credentials.
- Remove unauthorised external sharing links.
- Work with suppliers to resolve platform-related issues.

The outsourced IT provider should confirm when the technical cause has been addressed.

## 16. Phase 6: Recover
Recovery restores normal business operations safely.

Recovery activities may include:
- Restore access to affected accounts.
- Restore deleted or corrupted files from available recovery options.
- Rebuild affected laptops.
- Restore WordPress from a clean backup.
- Validate CRM, Xero, SharePoint, or OneDrive records.
- Confirm affected users can work safely.
- Monitor for recurring suspicious activity.
- Confirm customer or business data integrity.
- Communicate recovery status to management and affected users.

Recovery should not begin until containment steps are complete and the risk of reinfection or repeated compromise is reduced.

## 17. Phase 7: Review and Improve
After High and Critical incidents, HarbourShield should complete a post-incident review.

The review should identify:
- What happened.
- How the incident was detected.
- What information, systems, or users were affected.
- What worked well.
- What did not work well.
- Root cause or likely cause.
- Business impact.
- Customer or supplier impact.
- Whether notifications were required.
- Control gaps.
- Lessons learned.
- Improvement actions.
- Action owners and due dates.

Improvement actions should be added to the Cyber Risk Register, Treatment Plan, or security improvement tracker.

## 18. Incident Escalation Criteria
The Operations Manager must escalate an incident to the Managing Director if any of the following apply:
- Customer personal information may be exposed.
- Insurance policy documents or claims information may be exposed.
- Finance systems, invoices, or payment details are affected.
- Ransomware, malware, or system-wide compromise is suspected.
- A privileged account may be compromised.
- A third-party supplier reports a breach affecting HarbourShield.
- Business operations are significantly disrupted.
- The incident may require customer, insurer, legal, regulatory, or public communication.
- The incident could cause reputational damage.
- The incident is rated High or Critical.

## 19. Communication Requirements
Incident communication must be controlled, accurate, and approved.

Communication principles:
- Do not speculate.
- Do not blame individuals during the initial response.
- Do not publicly discuss incidents without approval.
- Do not contact customers, insurers, regulators, or media without management approval.
- Keep internal communication factual and limited to those who need to know.
- Use approved communication channels where possible.
- Record major decisions and communications.

The Managing Director must approve external communications for serious incidents.

## 20. External Notification Assessment
Some incidents may require assessment for customer, supplier, insurer, regulatory, contractual, or legal notification.

Notification assessment should consider:
- Whether personal information was accessed, disclosed, lost, or misused.
- Whether Confidential or Restricted information was involved.
- Whether customer harm is possible.
- Whether identity documents were involved.
- Whether financial information or payment details were involved.
- Whether insurer, supplier, or contractual notification obligations apply.
- Whether external compliance or legal advice is required.
- Whether cyber insurance notification is required, if applicable.

The Managing Director should make notification decisions with support from the Operations Manager, external compliance consultant, legal adviser, and outsourced IT provider where required.

## 21. Evidence Handling
Incident evidence should be preserved where practical.

Examples of evidence include:
- Suspicious emails.
- Email headers.
- Screenshots.
- Login logs.
- Audit logs.
- User reports.
- File sharing records.
- Endpoint alerts.
- Website logs.
- Supplier breach notices.
- Copies of fraudulent invoices or payment requests.
- Timeline of actions taken.

Employees should not delete suspicious emails, files, or logs unless instructed by the Operations Manager or outsourced IT provider.
