# Backup and Recovery Policy
## Project: Cyber Security Governance Framework for an Australian Insurance Brokerage

### Organisation: HarbourShield Insurance Brokers Pty Ltd
### Document Owner: Operations Manager
### Approved By: Managing Director
### Version: 1.0
### Document Status: Portfolio Project – Fictional Business Scenario

## 1. Purpose
The purpose of this Backup and Recovery Policy is to define how HarbourShield Insurance Brokers Pty Ltd protects important business information and systems from loss, corruption, accidental deletion, ransomware, system failure, supplier outage, or other disruption.

HarbourShield relies on cloud-based systems to manage customer information, insurance policy documents, claims information, financial records, email, and business operations. Backup and recovery controls help ensure that critical information can be restored when required and that business disruption is reduced during security incidents or technology failures.

This policy supports practical backup and recovery governance for a small-to-medium Australian insurance brokerage using cloud systems and outsourced IT support.

## 2. Policy Objectives
The objectives of this policy are to:
1. Identify critical systems and information requiring backup or recovery capability.
2. Define backup ownership and responsibilities.
3. Reduce business disruption caused by data loss, ransomware, accidental deletion, or system failure.
4. Support recovery of customer, insurance, finance, and operational information.
5. Ensure backup and recovery arrangements are reviewed and tested periodically.
6. Clarify expectations between HarbourShield, outsourced IT providers, and third-party vendors.
7. Support incident response and business continuity activities.

## 3. Scope
This policy applies to:
- All HarbourShield business systems and information assets that support operations.
- Microsoft 365, SharePoint, OneDrive, insurance CRM, Xero, WordPress, laptops, email, and approved business systems.
- Customer, employee, supplier, insurer, policy, claims, financial, and operational information.
- Backups managed by HarbourShield, outsourced IT providers, cloud providers, hosting providers, or other third-party vendors.
- Recovery activities following accidental deletion, ransomware, malware, account compromise, supplier outage, system failure, or data corruption.

## 4. Backup and Recovery Principles
HarbourShield’s backup and recovery approach is based on the following principles:

| Principle | Description |
| --- | --- |
| Business criticality | Backup and recovery priority should be based on business importance. |
| Clear ownership | Each critical system should have a business owner and technical support owner. |
| Recoverability | Backups are only useful if information can be restored when required. |
| Ransomware resilience | Backup arrangements should consider ransomware and account compromise scenarios. |
| Periodic testing | Critical recovery processes should be tested periodically. |
| Supplier awareness | Cloud and SaaS recovery responsibilities must be understood. |
| Least privilege | Backup administration access must be limited to authorised users. |
| Continuous improvement | Backup and recovery gaps should be tracked and improved over time. |

## 5. Critical Systems and Information
The following systems and information types are considered important to HarbourShield’s operations.

| System / Information Asset | Business Use | Backup / Recovery Importance |
| --- | --- | --- |
| Microsoft 365 Email | Customer, insurer, and supplier communication | High |
| SharePoint / OneDrive | Customer documents, policy files, internal documents | High |
| Insurance CRM | Customer records, policy records, renewals, notes | Critical |
| Xero | Invoices, payments, accounting records | High |
| WordPress Website | Public website and enquiry forms | Medium |
| Windows Laptops | User workstations and local working files | Medium |
| Insurer Portals | Policy submissions and insurer communication | High |
| Governance Documents | Policies, registers, risk records, incident documents | High |
| Backup Configuration Records | Recovery settings and vendor details | Restricted / High |

Business owners must ensure that critical information is stored in approved systems rather than only on local devices.

## 6. Backup Ownership
Backup and recovery responsibilities must be clearly assigned.

| Area | Business Owner | Technical / Supplier Support |
| --- | --- | --- |
| Microsoft 365 Email | Operations Manager | Outsourced IT Provider / Microsoft |
| SharePoint / OneDrive | Operations Manager | Outsourced IT Provider / Microsoft |
| Insurance CRM | Operations Manager | CRM Vendor / Outsourced IT Provider |
| Xero | Finance Manager | Xero / Outsourced IT Provider |
| WordPress Website | Marketing Coordinator | Web Hosting Provider / Outsourced IT Provider |
| Windows Laptops | Operations Manager | Outsourced IT Provider |
| Governance Documents | Operations Manager | Outsourced IT Provider |
| Backup and Recovery Process | Operations Manager | Outsourced IT Provider |

The Managing Director is accountable for approving major backup and recovery risk decisions.

## 7. Backup Requirements
HarbourShield must ensure that critical business information is backed up or recoverable through vendor-supported recovery options.

Backup requirements include:
- Critical business systems must have documented backup or recovery arrangements.
- Backup responsibilities must be agreed with the outsourced IT provider and relevant vendors.
- Customer, policy, claims, finance, and governance information should be stored in approved systems that support recovery.
- Backup frequency should reflect business criticality.
- Backup access must be limited to authorised users.
- Backup settings must not be changed without approval.
- Backup failures or unavailable recovery options must be investigated.
- Backup gaps should be recorded in the Cyber Risk Register or improvement plan.

## 8. Backup Frequency Guidance
Backup frequency should be based on business impact and operational need.

| System / Information Type | Recommended Backup / Recovery Frequency |
| --- | --- |
| Insurance CRM | Vendor-supported recovery or daily backup where available |
| Microsoft 365 Email | Retention and recovery configuration reviewed periodically |
| SharePoint / OneDrive | Retention, version history, and recovery configuration reviewed periodically |
| Xero | Vendor-supported recovery and export options reviewed periodically |
| WordPress Website | At least weekly, or before major changes |
| Governance Documents | Stored in SharePoint / OneDrive with version history enabled where available |
| Local Laptop Files | Avoid local-only storage; important files must be moved to approved cloud storage |
| Backup Configuration Records | Reviewed after major system or supplier changes |

Where systems are fully managed by SaaS providers, HarbourShield must understand what recovery is available and what additional backup controls may be required.

## 9. Recovery Objectives
HarbourShield should define practical recovery expectations for critical systems.

| System / Information Asset | Recovery Priority | Target Recovery Approach |
| --- | --- | --- |
| Insurance CRM | Critical | Restore access or vendor-supported recovery as soon as practical. |
| Microsoft 365 Email | High | Restore mailbox access, recover deleted emails where available, investigate compromise. |
| SharePoint / OneDrive | High | Recover deleted or corrupted files using retention, version history, or backup options.
| Xero | High | Restore access, review transactions, use vendor support where required. |
| WordPress Website | Medium | Restore website from hosting backup or clean rebuild if compromised. |
| Windows Laptop | Medium | Rebuild device and restore business files from approved cloud storage. |
| Governance Documents | High | Restore from SharePoint / OneDrive version history or backup. |

Formal recovery time objectives may be developed as the business matures.

## 10. Recovery Testing
Backups and recovery arrangements must be tested periodically.

Testing requirements include:
- Critical recovery processes should be tested at least annually.
- Website backup restoration should be tested after major website changes where practical.
- SharePoint / OneDrive file recovery should be tested periodically.
- Microsoft 365 recovery options should be reviewed with the outsourced IT provider.
- CRM and Xero recovery options should be confirmed with vendors.
- Recovery test results should be documented.
- Failed recovery tests must be investigated and remediated.

Example recovery test record:
| Field | Description |
| --- | --- |
| System Tested | System or data tested. |
| Test Date | Date of recovery test. |
| Test Type | File restore, mailbox recovery, website restore, vendor recovery confirmation. |
| Result | Successful, partially successful, or failed. |
| Issues Found | Problems identified during testing. |
| Action Required | Remediation or improvement required. |
| Owner | Person responsible for follow-up. |

## 11. Ransomware Recovery Considerations
Backup and recovery arrangements must consider ransomware risk.

Ransomware-related requirements include:
- Important files should not be stored only on individual laptops.
- Shared cloud folders should use version history or recovery options where available.
- Backup administration access must be protected with strong authentication.
- Backup settings must not be accessible to unnecessary users.
- Suspicious encryption, mass deletion, or unusual file changes must be reported immediately.
- During ransomware events, affected devices must be isolated where practical.
- Recovery must not begin until the incident is understood and containment steps are completed.
- The outsourced IT provider must assist with technical containment and recovery planning.

## 12. Accidental Deletion and Data Corruption
Accidental deletion or corruption of business information must be reported promptly.

Examples include:
- Deleted customer folders.
- Incorrectly overwritten policy documents.
- Corrupted spreadsheet or report.
- Deleted mailbox content.
- Removed SharePoint files.
- WordPress content accidentally changed or deleted.
- CRM records accidentally changed or removed.

Users must not attempt risky recovery actions without support where sensitive or critical information is involved.

## 13. Supplier and SaaS Recovery Responsibilities
HarbourShield uses third-party cloud and SaaS systems. The business must understand the recovery responsibilities of each supplier.

Supplier review should consider:
- Whether the supplier provides backup or recovery.
- Whether deleted records can be restored.
- How long deleted information is retained.
- Whether version history is available.
- Whether customer-managed backups are required.
- How restoration requests are submitted.
- Whether recovery is included in the service plan.
- Whether recovery support has additional costs.
- How supplier outages are communicated.

Critical supplier recovery capabilities should be reviewed at least annually.

## 14. Backup Security
Backups and recovery systems must be protected from unauthorised access.

Backup security requirements include:
- Backup administration access must be limited.
- MFA must be enabled for backup and administrator accounts where supported.
- Backup configuration details must be treated as Restricted information.
- Backup credentials must be stored securely.
- Backup settings must not be changed without approval.
- Backup access must be removed when no longer required.
- External IT provider backup access must be documented and reviewed.
- Backup logs or status alerts should be reviewed where available.

## 15. Local Storage and User Devices
Users must avoid storing important business information only on local devices.

Requirements include:
- Customer, policy, claims, and finance documents should be stored in approved business systems.
- Local files should be moved to SharePoint, OneDrive, CRM, or another approved repository.
- Important documents must not be stored only on a laptop desktop or downloads folder.
- Local-only files may not be recoverable if a device is lost, stolen, damaged, or infected.
- Lost or stolen devices must be reported immediately.
- Users must follow instructions from the outsourced IT provider during device recovery.

## 16. Incident Recovery Process
Recovery during a security incident must be coordinated.

Recovery process:
1. Identify the affected system, user, or data.
2. Report the issue to the Operations Manager.
3. Engage the outsourced IT provider or relevant vendor.
4. Determine whether the issue is accidental, technical, or malicious.
5. Contain the incident before restoration where required.
6. Confirm the safest recovery point.
7. Restore information or system access.
8. Validate that recovered information is accurate and usable.
9. Record the recovery action.
10. Conduct a post-incident review for significant incidents.

The Managing Director must be informed for significant incidents affecting customer information, critical systems, or business operations.

## 17. Backup and Recovery Records
HarbourShield should maintain records of important backup and recovery activities.

Records may include:
- Backup configuration summary.
- Critical system recovery options.
- Recovery test results.
- Backup failure investigations.
- Supplier recovery confirmations.
- Recovery actions after incidents.
- Backup-related risk register entries.
- Approval of backup exceptions.

These records should be stored in an approved restricted-access location.

## 18. Policy Exceptions
Exceptions to this policy must be documented and approved.

Examples include:
- A system does not support customer-managed backups.
- A SaaS provider only offers limited recovery.
- Backup testing cannot be completed due to supplier limitations.
- A legacy process stores information locally for a temporary period.
- Recovery options require additional supplier cost and business approval.

Exceptions must include:
- System or information affected.
- Business reason.
- Risk description.
- Compensating controls.
- Approval owner.
- Expiry or review date.

## 19. Roles and Responsibilities
| Role | Responsibility |
| --- | --- |
| Managing Director | Approves major backup and recovery risk decisions and high-risk exceptions. |
| Operations Manager | Owns this policy, coordinates backup reviews, recovery tests, and incident recovery activities. |
| Outsourced IT Provider | Supports backup configuration, recovery testing, device recovery, and technical restoration. |
| System Owners | Confirm business criticality and recovery needs for their systems. |
| Finance Manager | Confirms recovery requirements for Xero and finance information. |
| Marketing Coordinator | Coordinates WordPress website backup and recovery with hosting provider. |
| Employees | Store business information in approved systems and report deletion, corruption, or loss promptly. |
| Third-Party Vendors | Provide recovery support according to service agreements and platform capabilities. |

## 20. Related Documents
This policy should be read together with:
- Information Security Policy.
- Access Control Policy.
- Acceptable Use Policy.
- Password and MFA Policy.
- Data Classification Policy.
- Incident Response Plan.
- Third-Party Security Review Checklist.
- Information Asset Register.
- Cyber Risk Register.

## 21. Review Cycle
This policy should be reviewed:
- At least annually.
- After a ransomware incident.
- After a major backup or recovery failure.
- After a critical supplier outage.
- After a major system or supplier change.
- When business, legal, regulatory, or technology requirements change.
