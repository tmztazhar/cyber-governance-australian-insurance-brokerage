# Password and Multi-Factor Authentication Policy

## Project: Cyber Security Governance Framework for an Australian Insurance Brokerage

### Organisation: HarbourShield Insurance Brokers Pty Ltd
### Document Owner : Operations Manager
### Approved By : Managing Director
### Version : 1.0
### Document Status : Portfolio Project – Fictional Business Scenario

## 1. Purpose
The purpose of this Password and Multi-Factor Authentication Policy is to define minimum requirements for password security and multi-factor authentication at HarbourShield Insurance Brokers Pty Ltd.

HarbourShield uses cloud-based systems to manage customer information, insurance policy documents, claims information, financial records, email, and business operations. Weak passwords, password reuse, shared credentials, and missing multi-factor authentication can increase the risk of account compromise, business email compromise, data exposure, fraud, and unauthorised access.

This policy supports stronger identity and access security for a small-to-medium Australian insurance brokerage.

## 2. Policy Objectives
The objectives of this policy are to:
1. Reduce the risk of unauthorised access to HarbourShield systems.
2. Require strong passwords or passphrases for business accounts.
3. Require multi-factor authentication for critical systems where supported.
4. Prevent password sharing and unsafe password storage.
5. Protect privileged and administrator accounts.
6. Support secure onboarding, offboarding, and access management.
7. Improve employee awareness of credential-based attacks.

## 3. Scope
This policy applies to:
- All employees, contractors, temporary workers, and authorised third parties.
- All HarbourShield business accounts and systems.
- Microsoft 365, SharePoint, OneDrive, insurance CRM, Xero, WordPress, insurer portals, password managers, remote access services, and other approved business applications.
- Privileged administrator accounts.
- Third-party and outsourced IT provider accounts used to access HarbourShield systems.
- Any system that stores, processes, transmits, or provides access to HarbourShield information.

## 4. Password Security Principles
HarbourShield’s password security approach is based on the following principles:

| Principle | Description |
| --- | --- |
| Strong authentication | Accounts must use strong passwords or passphrases. |
| Unique credentials | Business passwords must not be reused across personal or unrelated systems. |
| Confidentiality | Passwords and authentication codes must not be shared. |
| MFA first | Critical systems should use multi-factor authentication where supported. |
| Least privilege | Stronger authentication is required for privileged access. |
| Prompt reporting | Suspected password compromise must be reported immediately. |
| Practical usability | Password requirements should be secure but realistic for SME users. |

## 5. Password Requirements
Users must create strong passwords or passphrases for business systems.

Minimum password requirements include:
- Passwords must be difficult to guess.
- Passwords should be unique for each business system where single sign-on is not used.
- Passwords must not be reused from personal accounts.
- Passwords must not contain obvious information such as names, birthdays, company names, usernames, or common words.
- Passwords must not be shared with other people.
- Passwords must not be stored in unsecured documents, spreadsheets, browser notes, sticky notes, email drafts, or messaging apps.
- Passwords must be changed immediately if compromise is suspected.
- Default passwords must be changed before a system or account is used.

Where possible, users should use long passphrases instead of short complex passwords.

Example passphrase style:

`River-Policy-Coffee-Window-27`

The example above is for demonstration only and must not be used as a real password.

## 6. Password Length Guidance
Where the system allows configuration, HarbourShield should prefer longer passwords or passphrases.

Recommended minimums:
| Account Type | Recommended Minimum |
| --- | --- |
| Standard user account | At least 12 characters |
| Privileged or administrator account | At least 15 characters |
| Shared or service account, if unavoidable | At least 20 characters |
| Password manager master password | At least 15 characters |

Where a system does not support these settings, the strongest practical configuration should be used.

## 7. Multi-Factor Authentication Requirements
Multi-factor authentication must be enabled for critical systems where supported.

MFA should be required for:
- Microsoft 365.
- SharePoint and OneDrive access.
- Insurance CRM.
- Xero.
- WordPress administrator accounts.
- Remote access services.
- Password manager.
- Cloud storage platforms.
- Privileged administrator accounts.
- Outsourced IT provider access.
- Any system containing confidential or restricted information.

MFA should also be enabled for insurer portals where supported by the insurer.

## 8. MFA Methods
Approved or acceptable MFA methods may include:

| MFA Method | Usage Guidance |
| --- | --- |
| Authenticator app | Preferred where available. |
| Push notification | Acceptable if users are trained to deny unexpected prompts. |
| Hardware security key | Preferred for high-risk or privileged accounts where practical. |
| SMS code | Acceptable only where stronger methods are not available. |
| Email code | Acceptable only where stronger methods are not available and risk is low. |

Users must not approve MFA prompts they did not initiate.

Unexpected MFA prompts must be reported immediately because they may indicate a stolen password.

## 9. Privileged Account Authentication
Privileged accounts create higher risk because they can change security settings, access sensitive data, or manage other users.

Privileged account requirements include:
- Privileged accounts must use MFA where supported.
- Privileged passwords must be unique and strong.
- Privileged accounts must not be shared unless formally approved.
- Privileged access must be limited to authorised users only.
- Privileged accounts should not be used for normal daily work where separate standard accounts are available.
- External IT administrator accounts must be documented.
- Privileged access must be reviewed at least every six months.
- Privileged passwords must be changed immediately if compromise is suspected.

Examples of privileged accounts include:
- Microsoft 365 administrator.
- SharePoint administrator.
- CRM administrator.
- Xero administrator.
- WordPress administrator.
- Domain or hosting administrator.
- Backup administrator.
- Outsourced IT administrator.

## 10. Password Manager Use
Where practical, HarbourShield should use an approved password manager to reduce unsafe password storage and sharing.

Password manager requirements include:
- The password manager must use a strong master password.
- MFA must be enabled for the password manager where supported.
- Shared vaults should be limited to authorised users.
- Shared credentials should be avoided where individual accounts are available.
- Access to shared vaults must be removed when no longer required.
- Password manager access should be reviewed periodically.
- Passwords must not be exported or copied into unsecured files unless approved for a specific business reason.

If a password manager is not yet implemented, the risk should be recorded in the cyber risk register or improvement plan.

## 11. Password Sharing
Password sharing is not permitted unless formally approved as an exception.

Users must not:
- Share passwords with colleagues.
- Share passwords with managers.
- Share passwords with family members or friends.
- Send passwords through email, SMS, chat, or personal messaging apps.
- Store passwords in shared spreadsheets or unsecured documents.
- Ask another user for their password.

If a system requires shared access, the business should prefer one of the following options:
1. Create individual user accounts.
2. Use role-based access.
3. Use a password manager with controlled sharing.
4. Document and approve a temporary exception.

## 12. Service Accounts and Shared Accounts
Service accounts and shared accounts should be avoided where possible.

If they are required:
- A business reason must be documented.
- An account owner must be assigned.
- The account must use a strong password.
- MFA must be enabled where supported.
- Access must be limited to authorised users or systems.
- The password must be changed when authorised users leave or no longer require access.
- The account must be included in access reviews.
- The account must not be used for normal employee activity if individual accounts are available.

Examples include:
- Website service account.
- Backup service account.
- Legacy system account.
- Shared insurer portal account where individual accounts are not available.

## 13. Account Lockout and Failed Login Controls
Where supported, systems should be configured to reduce brute-force and password guessing attacks.

Recommended controls include:
- Account lockout after repeated failed login attempts.
- Login alerts for suspicious sign-in activity.
- Blocking or challenging risky sign-ins.
- Alerts for impossible travel or unusual locations where supported.
- Stronger controls for privileged accounts.
- Review of repeated failed login attempts during investigations.

The outsourced IT provider should support configuration of these controls where available.

## 14. Password Reset Process
Password resets must be handled securely.

Password reset requirements include:
- Users must verify their identity before a password is reset.
- Temporary passwords must be changed at first login where supported.
- Password reset links or codes must not be sent to unauthorised recipients.
- Suspicious password reset requests must be escalated.
- Password resets for privileged accounts require additional caution.
- The outsourced IT provider must not reset passwords based only on unverified email requests.

For high-risk systems, the Operations Manager or system owner should approve password reset requests.

## 15. Compromised Credentials
Users must report suspected credential compromise immediately.

Examples of possible compromise include:
- User entered a password into a suspicious website.
- User approved an MFA prompt they did not initiate.
- User receives unexpected MFA prompts.
- Unusual mailbox rules appear.
- Suspicious emails are sent from the user’s account.
- User receives password reset notifications they did not request.
- Login activity appears from an unusual location.
- The system alerts to suspicious sign-in activity.

Response actions may include:
- Resetting the password.
- Revoking active sessions.
- Reviewing mailbox rules.
- Reviewing recent login activity.
- Checking for suspicious forwarding rules.
- Reviewing access to CRM, SharePoint, OneDrive, Xero, and other systems.
- Notifying the Managing Director if customer information may be affected.
- Recording the incident in the incident register.

## 16. MFA Exceptions
Some systems may not support MFA or may only support weaker MFA options. MFA exceptions must be documented and approved.

The exception record should include:
- System name.
- Business owner.
- Reason MFA cannot be used.
- Risk rating.
- Compensating controls.
- Approval owner.
- Review date.

Possible compensating controls include:
- Stronger password requirements.
- Restricted administrator access.
- IP restrictions where available.
- Reduced user access.
- More frequent access reviews.
- Supplier security review.
- Monitoring for unusual activity.
- Migration to a system that supports MFA.

## 17. Joiner, Mover, Leaver Requirements
Password and MFA controls must be included in the user lifecycle process.

### 17.1 Joiners
New users must:
- Receive unique user accounts.
- Set strong passwords or passphrases.
- Enable MFA for required systems.
- Receive basic security guidance.
- Be warned not to share credentials.

### 17.2 Movers
When users change roles:
- Access rights must be reviewed.
- Privileged access must not be transferred automatically.
- Password manager vault access must be reviewed.
- Shared credential access must be reviewed.

### 17.3 Leavers
When users leave:
- Accounts must be disabled or removed promptly.
- Password manager access must be removed.
- Shared passwords must be changed if the user had access to them.
- MFA devices or methods linked to business systems must be removed where applicable.
- External or insurer portal access must be removed.

## 18. Employee Responsibilities
Employees are responsible for protecting their credentials.

Employees must:
- Use strong passwords or passphrases.
- Keep passwords confidential.
- Use MFA where required.
- Report suspicious login activity.
- Report unexpected MFA prompts.
- Avoid password reuse.
- Avoid storing passwords insecurely.
- Avoid sharing passwords with anyone.
- Follow password reset instructions securely.

## 19. Roles and Responsibilities
| Role | Responsibility |
| --- | --- |
| Managing Director | Approves this policy and accepts high-risk exceptions where required. |
| Operations Manager | Owns this policy, coordinates user awareness, access reviews, and exception tracking. |
| Outsourced IT Provider | Supports MFA configuration, password resets, account lockout settings, and investigation of suspicious logins. |
| System Owners | Confirm MFA and password requirements for systems they own. |
| Employees | Protect credentials, use MFA, and report suspicious activity. |
| Third Parties | Use strong authentication and follow HarbourShield access requirements. |

## 20. Related Documents
This policy should be read together with:
- Information Security Policy.
- Access Control Policy.
- Acceptable Use Policy.
- Data Classification Policy.
- Incident Response Plan.
- Cyber Risk Register.
- Information Asset Register.
- Roles and Responsibilities Matrix.

## 21. Review Cycle
This policy should be reviewed:
- At least annually.
- After a credential-related incident.
- After a business email compromise incident.
- After a major system or supplier change.
- When new authentication technology is introduced.
- When relevant legal, regulatory, or business requirements change.

