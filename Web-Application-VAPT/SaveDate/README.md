# Web Application VAPT – SaveDate.me

## Overview

This project presents a Vulnerability Assessment and Penetration Testing (VAPT) conducted on the **SaveDate.me** web application during my cybersecurity internship.

The assessment focused on identifying security vulnerabilities, validating findings through manual testing, and providing remediation recommendations to improve the application's security posture. Multiple Medium, Low, and Informational severity findings related to security misconfigurations, authentication, request handling, and information disclosure were identified during the assessment.

---

## Objectives

- Assess the security posture of the web application.
- Identify security vulnerabilities and security misconfigurations.
- Validate findings through manual testing.
- Prepare a professional Web Application VAPT report.
- Recommend appropriate remediation measures.

---

## Scope

**Target Application:** SaveDate.me

The assessment included:

- Web Application Security Testing
- HTTP Request & Response Analysis
- Authentication Testing
- Session Management Review
- Security Header Analysis
- Cookie Security Analysis
- Information Disclosure Testing

---

## Methodology

This assessment followed the standard Web Application Vulnerability Assessment and Penetration Testing (VAPT) methodology used during the internship.

For the complete methodology, see:

**[Web Application VAPT Methodology](../methodology.md)**

---

## Tools Used

- Burp Suite Professional
- OWASP ZAP
- WPScan
- cURL
- Browser Developer Tools

---

## Key Findings

| Severity | Findings |
|----------|---------:|
| Medium | 3 |
| Low | 4 |
| Informational | 3 |

### Major Findings

- CORS Misconfiguration
- Missing Anti-CSRF Tokens
- WordPress User Enumeration
- Cookie Without SameSite Attribute
- Missing or Weak Security Headers
- Missing Subresource Integrity (SRI)
- Password Auto-Complete Enabled
- Server Information Disclosure
- Information Disclosure via URL Parameters

No Critical or High severity vulnerabilities were identified during the assessment. However, several Medium and Low severity findings were discovered that could increase the application's attack surface if left unaddressed.

---

## Skills Demonstrated

- Web Application Penetration Testing
- Vulnerability Assessment (VAPT)
- OWASP Top 10 Testing
- HTTP Security Analysis
- Authentication & Session Security Testing
- Security Misconfiguration Analysis
- WordPress Security Testing
- Security Reporting
- Risk Assessment

---

## Repository Contents

- `README.md` – Project overview and assessment summary.
- `Shijimol_S_Savedate_PentestReport.pdf` – Redacted Web Application VAPT report.
- `screenshots/` – Evidence collected during the security assessment.

---

## Disclaimer

This project is shared for educational and portfolio purposes only. Any confidential, sensitive, or personally identifiable information has been removed or redacted. The assessment was performed in an authorized environment during my cybersecurity internship.
