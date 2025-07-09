# Threats and Vulnerabilities 

This document outlines the potential threats and vulnerabilities associated with each asset category identified in the previous step.

---

## 1. Physical Assets

| Asset                 | Threats                        | Vulnerabilities                         |
| --------------------- | ------------------------------ | --------------------------------------- |
| Desktop Firewall      | Theft, Power failure           | No physical security, No UPS backup     |
| Employee Laptops      | Theft, Unauthorized access     | No disk encryption, Weak user passwords |
| Office Infrastructure | Fire, Hardware failure         | No fire suppression, Aging hardware     |
| Secure Storage        | Unauthorized access            | No biometric/pin access                 |
| Restricted Zones      | Tailgating, Unauthorized entry | No access control enforcement           |

---

## 2. Digital Assets

| Asset                  | Threats                       | Vulnerabilities                                |
| ---------------------- | ----------------------------- | ---------------------------------------------- |
| Wireless Networks      | Sniffing, Unauthorized access | Unsecured Wi-Fi (no WPA2), Default credentials |
| E-commerce Data        | Data breach, SQL injection    | Unpatched OpenCart, Weak DB credentials        |
| Cardholder Information | Skimming, Data leakage        | No encryption, Stored without tokenization     |
| Personal Data          | Data misuse, Identity theft   | No data classification or access restrictions  |
| System Logs & Backups  | Tampering, Ransomware         | No offsite backup, No integrity check          |

---

## 3. People Assets

| Asset                 | Threats                      | Vulnerabilities                            |
| --------------------- | ---------------------------- | ------------------------------------------ |
| Employees             | Social engineering           | Lack of training, No awareness sessions    |
| Cybersecurity Team    | Insider threats              | Overprivileged access, No activity logging |
| DPO                   | Mismanagement of data rights | Not formally appointed or trained          |
| Training Participants | Information leaks            | No NDA, Loose access controls              |

---

## 4. Paper Assets

| Asset              | Threats             | Vulnerabilities                  |
| ------------------ | ------------------- | -------------------------------- |
| Risk Reports       | Information theft   | No lockable storage              |
| Compliance Records | Fraud, Misuse       | No retention/disposal policy     |
| Employee Documents | Data leaks          | No redaction, Physical theft     |
| Audit Trails       | Tampering           | No chain of custody              |
| Policies           | Unauthorized access | Printed without control measures |

---

## 5. Service Assets

| Asset              | Threats                 | Vulnerabilities                           |
| ------------------ | ----------------------- | ----------------------------------------- |
| Google Cloud       | Misconfigurations       | Public access settings, No firewall rules |
| Internet Provider  | DoS, Traffic monitoring | No redundancy, No encrypted DNS           |
| Payment Gateways   | MITM, Phishing          | No 2FA, No fraud monitoring               |
| Compliance Support | Inaccurate assessments  | Outdated tools, Manual inputs             |

---

## 6. Software Assets

| Asset          | Threats              | Vulnerabilities                      |
| -------------- | -------------------- | ------------------------------------ |
| OpenCart       | XSS, SQLi, CSRF      | No WAF, Default settings             |
| Ubuntu VM      | Rootkit, Exploits    | No hardening, No auto-updates        |
| Security Tools | Bypass, Spoofing     | Misconfigurations, Default passwords |
| Antivirus      | Inadequate detection | No real-time protection, Not updated |
| Access Control | Privilege escalation | Misconfigured permissions            |

---

