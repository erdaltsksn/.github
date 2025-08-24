# 🔒 Security Policy

We take the security of our software and services seriously. This document
contains a set of guidelines and discusses how to safely deal with a security
vulnerability.

## 🔐 Reporting a Vulnerability

If you believe you have found a security vulnerability in this project, please
report it to us as described below. We will investigate all legitimate reports
and do our best to quickly fix the problem.

> [!CAUTION]
> **Please DO NOT report security vulnerabilities through public GitHub issues.**

Instead, please use one of these secure channels:

### 1. GitHub Security Advisories (Recommended)

1. Go to the **Security** Advisories tab of the repository
2. Click **"Report a vulnerability"**
3. Fill out the private vulnerability report form
4. Submit your report

### 2. Private Email

To report a security issue, email [security@erdaltaskesen.com](mailto:security@erdaltaskesen.com)
and include the project name in the subject line.

## 📝 What to Include in Your Report

Please include the following information along with your report (as much as you
can provide) to help us better understand the possible issue:

### **Vulnerability Details**

- **Type of vulnerability** (e.g., XSS, SQL injection, authentication bypass)
- **Affected component(s)** (specific repository, file, or feature)
- **Severity assessment** (Critical, High, Medium, Low)
- **Description** of the vulnerability and its potential impact

### **Reproduction Information**

- **Steps to reproduce** the vulnerability
- **Proof of concept** code or screenshots
- **Environment details** (OS, browser, version, etc.)
- **Configuration** required to reproduce

### **Impact Assessment**

- **What can an attacker achieve?**
- **What data could be compromised?**
- **Are user accounts at risk?**
- **Could this lead to system compromise?**

### **Suggested Fix** (Optional)

- **Proposed solution** or mitigation
- **Code changes** you'd recommend
- **Alternative approaches** considered

### Severity Classification

| Severity.      | CVSS Range | Examples                          | Response Time |
|----------------|------------|-----------------------------------|---------------|
| 🔴 **Critical** | 9.0 – 10.0 | - Remote code execution           | **24 hours**  |
|                |            | - SQL injection with data access  |               |
|                |            | - Authentication bypass           |               |
| 🟠 **High**     | 7.0 – 8.9  | - Cross-site scripting (XSS)      | **48 hours**  |
|                |            | - Privilege escalation            |               |
|                |            | - Information disclosure          |               |
| 🟡 **Medium**   | 4.0 – 6.9  | - CSRF vulnerabilities            | **5 days**    |
|                |            | - Denial of Service               |               |
|                |            | - Insecure default configurations |               |
| 🟢 **Low**      | 0.1 – 3.9  | - Information leakage             | **10 days**   |
|                |            | - Minor security issues           |               |
|                |            | - Best-practice deviations        |               |

## 🚔 Security Response Process

1. **📥 Report Received**
   - Vulnerability report is received and acknowledged
   - Initial severity assessment performed
   - Unique tracking ID assigned

2. **🔍 Investigation**
   - Security team reproduces the issue
   - Impact assessment conducted
   - Severity confirmed or adjusted

3. **🛠️ Fix Development**
   - Security fix developed and tested
   - Internal security review performed
   - Fix validated against the vulnerability

4. **📢 Disclosure Coordination**
   - Reporter notified of fix timeline
   - Public disclosure coordinated
   - Security advisory prepared

5. **🚀 Release & Disclosure**
   - Security fix released
   - Public security advisory published
   - Reporter credited (if desired)

### Response Timeline

| Stage                | Timeline    | Description                             |
|----------------------|-------------|-----------------------------------------|
| **Initial Response** | 24-48 hours | Acknowledge receipt and assign severity |
| **Investigation**    | 3-5 days    | Reproduce and analyze the vulnerability |
| **Fix Development**  | 1-2 weeks   | Develop and test the security fix       |
| **Disclosure**       | 30-90 days  | Coordinate public disclosure            |

## 📋 Vulnerability Disclosure Policy

### 🤝 Coordinated Disclosure

We follow responsible disclosure practices:

1. **🔒 Private Reporting**: Security issues are reported privately
2. **⏰ Reasonable Timeline**: We commit to fixing issues promptly
3. **📢 Public Disclosure**: Coordinated public disclosure after fixes
4. **🏆 Credit**: Security researchers receive appropriate credit

### 📅 Disclosure Timeline

- **0-7 days**: Initial response and severity assessment
- **7-30 days**: Investigation and fix development
- **30-90 days**: Testing, release preparation, and disclosure
- **90+ days**: Public disclosure (may occur sooner if fix is ready)

### 🚫 What We Ask

- **No Public Disclosure** before coordinated release
- **No Data Destruction** or privacy violations during testing
- **Minimal Impact** testing that doesn't harm users or services
- **Legal Compliance** with applicable laws and regulations

### 🎁 Recognition

We appreciate security researchers and offer:

- **🏆 Public Credit** in security advisories (if desired)
- **📝 Hall of Fame** listing for significant findings
- **🎯 Direct Communication** with our security team
- **📧 Updates** on fix progress and release timeline

## 🙏🏼 Thanks

Thank you for improving the security of this project. Your efforts are greatly
appreciated and will be acknowledged.
