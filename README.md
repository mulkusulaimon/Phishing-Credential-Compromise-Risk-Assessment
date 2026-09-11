# Phishing-Credential-Compromise-Risk-Assessment
Company: ABC Finance Ltd (Fictional) 
Assessment Type: Information Security Risk Assessment 
Prepared By: Sulaimon Aleem 
Risk ID: R002 
Risk Status: Open
1. Executive Summary

During a security review, an employee clicked a phishing link and entered their company username and password into a fraudulent website. The compromised credentials were subsequently used in attempts to access company systems.

The assessment identified a High information security risk involving credential compromise and unauthorized access. Immediate containment and longer-term security improvements are recommended.

2. Risk Assessment
Field	Assessment
Risk ID	R002
Assets	Company email, customer data, company systems, company documents, user accounts
Threat	Cyber attacker using phishing to obtain employee credentials
Vulnerability	Insufficient employee awareness and controls allowed credentials to be submitted to a fraudulent website
Risk	Attackers could gain unauthorized access to company systems and sensitive information using compromised employee credentials
Likelihood	High
Impact	High
Risk Rating	High
Risk Treatment	Mitigate
Risk Owner	IT Manager
Status	Open
3. Business Impact

If the compromised credentials are successfully exploited, the organization could experience:

Unauthorized access to company systems
Customer data exposure
Email account compromise
Financial loss
Further phishing or social-engineering attacks
Regulatory or compliance consequences
Reputational damage
4. Root Cause

The immediate cause was an employee interacting with a phishing email and submitting company credentials to a malicious website.

The underlying control weakness was:

Insufficient employee awareness and phishing-resistant security controls allowed the employee to interact with a malicious link and submit company credentials to a fraudulent website.

5. Recommended Controls
Preventive Controls
Enable Multi-Factor Authentication (MFA) for company accounts.
Conduct regular security awareness and phishing-awareness training.
Implement email security and phishing-link filtering.
Strengthen authentication and account security controls.
Establish procedures for reporting suspicious emails.
Detective Controls
Monitor authentication and VPN logs.
Implement SIEM monitoring for suspicious login activity.
Conduct periodic user access reviews.
Monitor compromised accounts for unusual activity.
Alert on suspicious authentication patterns.
6. Immediate Corrective Actions

The organization should:

Isolate or disable the affected account.
Reset the compromised password.
Revoke active sessions and authentication tokens where applicable.
Review authentication and VPN logs.
Investigate whether unauthorized access occurred.
Block the malicious domain/link.
Monitor the affected account for suspicious activity.

Target: Immediate containment within 24 hours.

7. Long-Term Corrective Actions
Action	Owner	Target
Enable MFA for affected and remaining users	IT Manager	24–72 hours
Complete security awareness training	HR / IT	30 days
Improve email phishing protection	IT/Security	30 days
Review authentication logs	IT/Security	Immediate
Conduct phishing simulation	Information Security	30–60 days
Review access controls	IT Manager	30 days
8. Audit Evidence

An auditor or GRC analyst should request:

Security awareness training records
Training completion dashboard
MFA enrollment report
User access review reports
Authentication logs
VPN logs
Email security/filtering configuration
Phishing simulation results
Incident investigation report
Evidence of password reset/account containment

The objective is not merely to confirm that controls exist, but to determine whether they are implemented and operating effectively.

9. Risk Treatment

Treatment: Mitigate

The organization should reduce the likelihood and potential impact of credential compromise by implementing stronger authentication, employee awareness, email security, monitoring, and access controls.

10. Conclusion

The assessment identified a High risk resulting from compromised employee credentials obtained through a phishing attack. Immediate containment is required to prevent further unauthorized access.

Management should strengthen MFA, phishing protection, security awareness, authentication monitoring, and access-review processes. The corrective actions should be tracked to completion and supported by appropriate evidence before the risk is considered closed.

Portfolio Project: R002 — Phishing & Credential Compromise Risk Assessment
