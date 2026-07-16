# Android Application Security Assessment – Manappuram OGL

## Overview

This project presents a Mobile Application Vulnerability Assessment and Penetration Testing (VAPT) conducted on the **Manappuram OGL Android Application** during my cybersecurity internship.

The assessment focused on identifying security vulnerabilities through static analysis, reverse engineering, configuration review, and limited dynamic testing. The objective was to evaluate the application's security posture, identify potential risks, and recommend remediation measures to improve overall security.

---

## Objectives

- Perform Android application security assessment
- Identify security vulnerabilities and security misconfigurations
- Validate findings through manual analysis
- Prepare a professional Mobile Application VAPT report
- Recommend remediation strategies

---

## Scope

**Target:** Manappuram OGL Android Application

The assessment included:

- APK Static Analysis
- AndroidManifest.xml Review
- Permission Analysis
- Component Security Testing
- Network Security Configuration Review
- Reverse Engineering
- Limited Dynamic Analysis

---

## Methodology

This assessment followed the shared Android Application Security Testing methodology available in:

**Android-Application-VAPT/methodology.md**

---

## Tools Used

- MobSF
- JADX
- APKTool
- Android Debug Bridge (ADB)
- Burp Suite
- Genymotion

---

## Key Findings

| Severity | Findings |
|----------|---------:|
| Critical | 1 |
| High | 3 |
| Medium | 5 |
| Low | 4 |
| Informational | 3 |

### Major Findings

- Insecure Network Communication (Cleartext Traffic)
- Application Data Backup Enabled
- Exported Firebase Messaging Service Without Access Control
- Exported Firebase Instance ID Service Without Access Control
- Excessive Permission Usage (READ_CONTACTS)
- Insecure External Storage Usage
- Potential FileProvider Misconfiguration
- Missing Explicit Exported Attribute
- Exported Broadcast Receivers
- Advertising ID Privacy Exposure

---

## Skills Demonstrated

- Android Application Security Testing
- Mobile Application VAPT
- Static Analysis
- Reverse Engineering
- Android Manifest Analysis
- Permission Analysis
- Component Security Testing
- Network Security Review
- Security Reporting
- Risk Assessment

---

## Repository Contents

- `report.pdf` – Redacted Mobile Application VAPT Report
- `screenshots/` – Supporting screenshots collected during testing

---

## Disclaimer

This project is shared for educational and portfolio purposes only. Any confidential or sensitive information has been removed from the published report and supporting materials.
