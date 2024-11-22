# Security Assessment of Ginandjuice.shop

## Graduation Project - DEPI  
**Team Name:** HACK TACTIX  
**Date of Assessment:** October 24, 2024  

---

## Project Overview

As part of our graduation project, **HACK TACTIX** conducted a security assessment of the internal corporate network of **ginandjuice.shop**. This penetration test simulated the actions of an external threat actor aiming to identify vulnerabilities and provide actionable recommendations to strengthen the security of the organization's systems.

---

## Key Findings  

During the assessment, **12 vulnerabilities** were identified and categorized as follows:

| **Severity**   | **Count** |
|----------------|-----------|
| Critical       | 0         |
| High           | 5         |
| Medium         | 2         |
| Low            | 3         |
| Informational  | 2         |

### Vulnerabilities Identified  

1. **SQL Injection** (CVSS: 8.8)  
   - **Severity:** High  
   - **Impact:** Unauthorized database manipulation and potential data exfiltration.  
   - **Instance:** Page 13  

2. **Cross-Site Scripting (Reflected)** (CVSS: 7.3)  
   - **Severity:** High  
   - **Impact:** Malicious script injection, session hijacking, or credential theft.  
   - **Instance:** Page 19  

3. **DOM-based Cross-Site Scripting (XSS)** (CVSS: 7.2)  
   - **Severity:** High  
   - **Impact:** Exploitation of dynamic client-side scripts to execute malicious payloads.  
   - **Instance:** Page 20  

4. **Client-Side Template Injection** (CVSS: 7.0)  
   - **Severity:** High  
   - **Impact:** Remote code execution or manipulation of client-side data.  
   - **Instance:** Page 21  

5. **XML External Entity (XXE) Injection** (CVSS: 8.5)  
   - **Severity:** High  
   - **Impact:** Access to internal files, denial-of-service (DoS), or sensitive data leaks.  
   - **Instance:** Page 24  

6. **Vulnerable JavaScript Libraries** (CVSS: 5.4)  
   - **Severity:** Medium  
   - **Impact:** Exploitation of outdated dependencies.  
   - **Instance:** Page 26  

7. **HTTP Response Header Injection** (CVSS: 6.5)  
   - **Severity:** Medium  
   - **Impact:** Manipulation of HTTP headers to compromise client-server communication.  
   - **Instance:** Page 27  

8. **Cookies Without HttpOnly Flag Set** (CVSS: 3.1)  
   - **Severity:** Low  
   - **Impact:** Increased risk of client-side attacks, such as XSS.  
   - **Instance:** Page 30  

9. **Cookies Without Secure Flag Set** (CVSS: 3.1)  
   - **Severity:** Low  
   - **Impact:** Risk of exposure in unsecured connections.  
   - **Instance:** Page 31  

10. **HTTP Strict Transport Security (HSTS) Not Implemented** (CVSS: 3.1)  
    - **Severity:** Low  
    - **Impact:** Risk of downgrade attacks and man-in-the-middle attacks.  
    - **Instance:** Page 32  

11. **Content Security Policy (CSP) Not Implemented** (CVSS: 0)  
    - **Severity:** Informational  
    - **Impact:** Lack of a CSP weakens defenses against XSS and code injection.  
    - **Instance:** Page 33  

12. **JavaScript Source Map Detected** (CVSS: 0)  
    - **Severity:** Informational  
    - **Impact:** Disclosure of source code and internal structure.  
    - **Instance:** Page 33  

---

## Team Members  

| **Name**             |
|-----------------------|
| Ahmed Hamada          |
| Mazen Khaled          |
| Ahmed Mahmoud         |
|Mariam Abdelrahman     |
|Safia Mohamed          |
---

## About HACK TACTIX  

We are **HACK TACTIX**, a passionate cybersecurity team from DEPI, specializing in ethical hacking and vulnerability assessments. Our mission is to identify risks and provide actionable solutions to protect systems from potential threats.  
