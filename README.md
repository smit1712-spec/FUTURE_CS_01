# FUTURE_CS_01

## Internship Task 1 – OWASP ZAP Vulnerability Assessment

### Overview
This repository contains the work completed for Internship Task 1 under the Cyber Security track. The task focuses on performing a passive vulnerability assessment of a sample web application using OWASP ZAP.

---

## Objectives

- Create a basic website for security testing.
- Configure OWASP ZAP proxy.
- Perform a passive vulnerability assessment.
- Identify common web security issues.
- Document findings and recommendations.

---

## Tools Used

- OWASP ZAP v2.17.0
- Visual Studio Code
- Mozilla Firefox (Configured with OWASP ZAP Proxy)
- Google Chrome
- HTML
- GitHub

---

## Repository Structure

```
Website/
    index.html

Screenshots/
    Assessment screenshots

Zap Report/
    Generated OWASP ZAP HTML Report

2026-08-05-ZAP-Report-.html
    HTML vulnerability report

TASK 1 REPORT.pdf
    Final internship report
```

---

## Vulnerabilities Identified

- Content Security Policy (CSP) Header Not Set
- Missing Anti-clickjacking Header
- Strict-Transport-Security Header Not Set
- X-Content-Type-Options Header Missing
- Cache-Control Directive Observation

---

## Outcome

The assessment successfully identified multiple security-related HTTP header issues through passive scanning. Appropriate recommendations have been documented in the final report.

---

## Author

**Smit Borkhetaria**

Cyber Security Internship – Task 1
