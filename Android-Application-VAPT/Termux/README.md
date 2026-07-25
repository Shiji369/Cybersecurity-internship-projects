# Android Application Security Assessment – Termux

## Overview

This project presents a Mobile Application Vulnerability Assessment and Penetration Testing (VAPT) conducted on the **Termux Android Application** during my cybersecurity internship.

The assessment focused on identifying security vulnerabilities through static and dynamic analysis, evaluating the application's security posture, and recommending remediation measures. Multiple High, Medium, Low, and Informational severity findings related to application configuration, exported components, permission management, and Android security best practices were identified during the assessment.

---

## Objectives

- Assess the security posture of the Android application.
- Identify security vulnerabilities and security misconfigurations.
- Validate findings through manual testing.
- Prepare a professional Mobile Application VAPT report.
- Recommend appropriate remediation measures.

---

## Scope

**Target Application:** Termux Android Application

The assessment included:

- APK Static Analysis
- AndroidManifest.xml Review
- Permission Analysis
- Component Security Testing
- Dynamic Analysis
- Runtime Behavior Analysis

---

## Methodology

This assessment followed the standard Android Application Vulnerability Assessment and Penetration Testing (VAPT) methodology used during the internship.

For the complete methodology, see:

**[Android Application VAPT Methodology](../methodology.md)**

---

## Tools Used

- MobSF
- JADX
- APKTool
- Android Debug Bridge (ADB)
- Genymotion
- Burp Suite

---

## Key Findings

| Severity | Findings |
|----------|---------:|
| High | 1 |
| Medium | 4 |
| Low | 3 |
| Informational | 2 |

### Major Findings

- Root Detection Not Implemented
- Application Running in Debug Mode
- Exported Content Provider Protected by Weak Permission
- Exported Command Execution Service Protected by Weak Permission
- Weak Protection Level for Command Execution Permission
- Use of SYSTEM_ALERT_WINDOW Permission
- Application Requests Permission to Install Packages
- Exported Settings Activity

The assessment identified several High, Medium, and Low severity vulnerabilities that could impact the application's security if left unaddressed. Appropriate remediation recommendations were provided to reduce the application's attack surface and improve overall security.

---

## Skills Demonstrated

- Android Application Security Testing
- Mobile Application Penetration Testing
- Vulnerability Assessment (VAPT)
- Static Analysis
- Dynamic Analysis
- Reverse Engineering
- Android Manifest Analysis
- Permission Analysis
- Security Reporting
- Risk Assessment

---

## Repository Contents

- `README.md` – Project overview and assessment summary.
- `Termux_Android_VAPT_Report.pdf` – Redacted Mobile Application VAPT report.
- `screenshots/` – Supporting screenshots collected during the security assessment.

---

## Disclaimer

This project is shared for educational and portfolio purposes only. Any confidential, sensitive, or personally identifiable information has been removed or redacted. The assessment was performed in an authorized environment during my cybersecurity internship.
