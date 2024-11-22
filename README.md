# Graduation-project-DEPI
Here’s a complete **README.md** file that includes space for team member names and all the necessary project details:

---

# Security Assessment of Ginandjuice.shop

## Project Overview

As part of our graduation project at DEPI, **HACK TACTIX** conducted a comprehensive security assessment of the internal corporate network of **ginandjuice.shop**. This penetration test, performed on **October 24, 2024**, simulated the actions of an external threat actor to identify and exploit vulnerabilities, assess the organization's security posture, and provide actionable recommendations for remediation.

---

## Key Findings

During the assessment, a total of **12 vulnerabilities** were discovered, categorized as follows:

| Severity  | Count |
|-----------|-------|
| Critical  | 0     |
| High      | 5     |
| Medium    | 2     |
| Low       | 3     |

### Notable High-Severity Vulnerabilities:
- **SQL Injection** (CVSS: 8.8): Exploitable to manipulate the database, execute unauthorized queries, and exfiltrate sensitive data.
- **Cross-Site Scripting (XSS):** Includes reflected and DOM-based XSS, enabling session hijacking, credential theft, and malicious redirection.
- **XML External Entity (XXE) Injection:** Risk of internal file exposure and denial-of-service (DoS) attacks.
- **Client-Side Template Injection:** Potential for remote code execution and data manipulation.

### Medium and Low-Severity Vulnerabilities:
- Outdated or vulnerable JavaScript libraries.
- Missing security headers, such as HSTS and CSP.
- Misconfigured cookies.

---

## Recommendations

1. Address **high-severity vulnerabilities** immediately to mitigate critical risks.
2. Resolve **medium- and low-severity issues** to improve the overall security posture.
3. Implement ongoing security monitoring and regular penetration testing to ensure resilience.

---

## Team Members

| Name                     | Role                 |
|--------------------------|----------------------|
| _[Team Member Name]_     | _[Role/Responsibility]_ |
| _[Team Member Name]_     | _[Role/Responsibility]_ |
| _[Team Member Name]_     | _[Role/Responsibility]_ |

---

## About HACK TACTIX

**HACK TACTIX** is a cybersecurity team dedicated to identifying vulnerabilities and securing organizational infrastructure. Our expertise includes penetration testing, vulnerability analysis, and developing actionable security recommendations.

