# Web Application VAPT – SaveDate.me

## Overview

This project presents a Vulnerability Assessment and Penetration Testing (VAPT) conducted on the **SaveDate.me** web application during my cybersecurity internship.

The assessment focused on identifying security vulnerabilities, validating findings through manual testing, and providing remediation recommendations to improve the application's security posture. The engagement identified Medium, Low, and Informational severity findings related to security misconfigurations, request handling, authentication, and information disclosure. :contentReference[oaicite:0]{index=0}

---

## Objectives

- Assess the security posture of the web application
- Identify security vulnerabilities and misconfigurations
- Validate vulnerabilities using manual testing
- Prepare a professional VAPT report
- Recommend appropriate remediation measures

---

## Scope

**Target:** SaveDate.me Web Application

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

The assessment followed a structured Vulnerability Assessment and Penetration Testing (VAPT) methodology:

- Information Gathering
- Reconnaissance
- Vulnerability Assessment
- Manual Verification
- Risk Analysis
- Documentation
- Remediation Recommendations

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
- Absence of Anti-CSRF Tokens
- WordPress User Enumeration
- Cookie Without SameSite Attribute
- Missing / Weak Security Headers
- Missing Subresource Integrity (SRI)
- Password Auto-Complete Enabled
- Server Information Disclosure
- Information Disclosure via URL Parameters

The assessment identified no Critical or High severity issues, but several Medium and Low severity findings that could increase the application's attack surface if left unaddressed. :contentReference[oaicite:1]{index=1}

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

- `report.pdf` – Redacted VAPT Report
- `screenshots/` – Evidence collected during testing

---

## Disclaimer

This project is shared for educational and portfolio purposes only. Any confidential or sensitive information has been removed from the published report and supporting materials.
