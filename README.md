# Phishing-Credential-Compromise-Risk-Assessment
# INFORMATION SECURITY RISK ASSESSMENT REPORT

## Phishing and Credential Compromise

---

### Organization: **ABC Finance Ltd (Fictional Organization)**

### Risk ID: **R002**

### Assessment Type: **Information Security Risk Assessment**

### Prepared By: **Sulaimon Aleem**

### Risk Status: **Open**

---

# 1. Executive Summary

This risk assessment was conducted following a phishing incident involving an employee of ABC Finance Ltd. The employee clicked a phishing link contained in a malicious email and entered their company username and password into a fraudulent login page.

Following the incident, attempts were made to use the compromised credentials to access the organization's internal systems.

The assessment identified a **High information security risk** relating to credential compromise and potential unauthorized access to company systems and sensitive information. Immediate containment actions and longer-term security improvements are recommended to reduce the likelihood of similar incidents.

---

# 2. Risk Assessment Details

| Risk Assessment Category | Details                                                                                                                                                |
| ------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------ |
| **Risk ID**              | R002                                                                                                                                                   |
| **Asset**                | Company email, customer data, company systems, company documents and user accounts                                                                     |
| **Threat**               | Cyber attacker using phishing to obtain employee credentials                                                                                           |
| **Vulnerability**        | Insufficient employee awareness and security controls allowed company credentials to be submitted to a fraudulent website                              |
| **Risk Statement**       | Attackers could gain unauthorized access to company systems and sensitive information using employee credentials compromised through a phishing attack |
| **Likelihood**           | High                                                                                                                                                   |
| **Impact**               | High                                                                                                                                                   |
| **Risk Rating**          | High                                                                                                                                                   |
| **Risk Treatment**       | Mitigate                                                                                                                                               |
| **Risk Owner**           | IT Manager                                                                                                                                             |
| **Risk Status**          | Open                                                                                                                                                   |

---

# 3. Business Impact

If the compromised credentials are successfully exploited, the organization may experience:

* Unauthorized access to company systems.
* Exposure of sensitive customer information.
* Compromise of company email accounts.
* Financial losses.
* Further phishing or social engineering attacks.
* Regulatory or compliance consequences.
* Damage to the organization's reputation.

---

# 4. Root Cause Analysis

The immediate cause of the incident was the employee clicking a phishing link and submitting company credentials to a malicious website.

The underlying root cause was insufficient employee awareness and inadequate security controls to prevent or reduce successful phishing attacks.

This allowed the employee to interact with a malicious link and provide company credentials to an unauthorized party.

---

# 5. Recommended Controls

## Preventive Controls

The following preventive controls are recommended:

### Multi-Factor Authentication

Multi-Factor Authentication (MFA) should be enabled for company accounts to reduce the risk of unauthorized access when passwords are compromised.

### Security Awareness Training

Employees should receive regular cybersecurity and phishing awareness training to improve their ability to identify malicious emails and fraudulent websites.

### Email Security and Phishing Filtering

Email filtering controls should be implemented or strengthened to detect and block malicious emails, links, and attachments.

### Account Security Controls

The organization should enforce appropriate authentication and account security requirements.

### Suspicious Email Reporting

Employees should have a clear process for reporting suspicious or potentially malicious emails to the appropriate IT or security team.

---

# 6. Detective Controls

The following detective controls are recommended:

* Monitor authentication and VPN login logs.
* Conduct periodic user access reviews.
* Monitor user accounts for unusual or suspicious activity.
* Implement security monitoring and alerts for suspicious authentication attempts.
* Review security events involving compromised or high-risk accounts.

---

# 7. Immediate Corrective Actions

The following actions should be completed immediately:

1. Isolate or disable the affected user account where necessary.
2. Reset the compromised password.
3. Revoke active user sessions where applicable.
4. Review authentication and VPN login logs.
5. Investigate whether unauthorized access to company systems occurred.
6. Block the malicious website or domain.
7. Monitor the affected account for suspicious activity.

### Corrective Action Deadline

**Immediate containment actions should be completed within 24 hours.**

---

# 8. Long-Term Corrective Actions

| Corrective Action                              | Responsible Owner         | Target Deadline   |
| ---------------------------------------------- | ------------------------- | ----------------- |
| Enable MFA for company accounts                | IT Manager                | Within 72 hours   |
| Review affected authentication and access logs | IT/Security Team          | Within 24 hours   |
| Complete security awareness training           | HR and IT Management      | Within 30 days    |
| Improve phishing and email security controls   | IT/Security Team          | Within 30 days    |
| Conduct phishing awareness testing             | Information Security Team | Within 30–60 days |
| Conduct a user access review                   | IT Manager                | Within 30 days    |

---

# 9. Audit Evidence

The following evidence should be collected to verify that recommended controls have been implemented and are operating effectively:

* Security awareness training certificates or training dashboard reports.
* MFA enrollment and configuration reports.
* User access review reports.
* Authentication and VPN login logs.
* Email filtering and security configuration records.
* Phishing awareness or simulation results.
* Incident investigation reports.
* Password reset and account containment records.
* Evidence of corrective action completion.

---

# 10. Risk Treatment

The recommended risk treatment is **Mitigation**.

The organization should reduce the likelihood and impact of credential compromise by strengthening authentication controls, improving employee awareness, implementing effective email security controls, monitoring suspicious activity, and conducting periodic access reviews.

---

# 11. Conclusion

This assessment identified a **High information security risk** resulting from employee credentials being compromised through a phishing attack.

Immediate containment actions are required to prevent further unauthorized access. The organization should also implement long-term improvements, including Multi-Factor Authentication, phishing awareness training, improved email security controls, authentication monitoring, and regular access reviews.

The risk should remain **Open** until corrective actions have been implemented, verified, and supported by appropriate evidence.

Once all corrective actions are completed, the risk should be reassessed to determine whether the residual risk is acceptable to the organization.

---

**Portfolio Project:** GRC Risk Assessment R002
**Project Title:** Phishing and Credential Compromise Risk Assessment
**Prepared By:** Sulaimon Aleem

