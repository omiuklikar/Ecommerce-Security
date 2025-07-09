# Risk Controls and Mitigation 

This document outlines the proposed **Administrative**, **Physical**, and **Logical/Technical** controls to mitigate the risks identified in the earlier assessment for each asset category. The controls are also mapped to relevant compliance frameworks (ISO 27001, PCI DSS, DPDPA, IT Act 2000).

---

## 1. Physical Assets

| Asset            | Control Type   | Control Description                             | Compliance Mapping               |
| ---------------- | -------------- | ----------------------------------------------- | -------------------------------- |
| Desktop Firewall | Physical       | Place in secure server room with access control | ISO 27001 A.11.1.1               |
| Employee Laptops | Logical        | Full-disk encryption and endpoint protection    | PCI DSS Req. 3.4, ISO A.10.1     |
| Restricted Zones | Administrative | Implement role-based access policy and logging  | ISO 27001 A.9.1.2, IT Act Sec 72 |

---

## 2. Digital Assets

| Asset          | Control Type   | Control Description                                | Compliance Mapping            |
| -------------- | -------------- | -------------------------------------------------- | ----------------------------- |
| Wi-Fi Networks | Logical        | WPA3 encryption, MAC filtering, captive portal     | PCI DSS Req. 1.2.3            |
| Customer Data  | Logical        | Encrypt at rest and in transit using TLS and AES   | GDPR Art. 32, DPDPA Sec 8(5)  |
| System Logs    | Administrative | Retention policy (12 months), regular audit review | PCI DSS Req. 10, ISO A.12.4.1 |

---

## 3. People Assets

| Asset     | Control Type   | Control Description                    | Compliance Mapping                |
| --------- | -------------- | -------------------------------------- | --------------------------------- |
| Employees | Administrative | Mandatory training and NDA             | ISO 27001 A.7.2.2, DPDPA Sec 8(2) |
| DPO       | Administrative | Assign responsibility with clear roles | DPDPA Chap IV, ISO A.6.1.1        |

---

## 4. Paper Assets

| Asset            | Control Type   | Control Description                     | Compliance Mapping            |
| ---------------- | -------------- | --------------------------------------- | ----------------------------- |
| Risk Reports     | Physical       | Locked cabinets, fireproof storage      | ISO A.11.2.6                  |
| Employee Records | Administrative | Access logs and secure shredding policy | DPDPA Sec 8, PCI DSS Req. 9.6 |

---

## 5. Service Assets

| Asset            | Control Type | Control Description                   | Compliance Mapping             |
| ---------------- | ------------ | ------------------------------------- | ------------------------------ |
| Cloud Services   | Logical      | IAM policies, MFA, regular audit logs | ISO 27017, PCI DSS Req. 12.3   |
| Payment Gateways | Logical      | Use PCI-DSS certified vendors only    | PCI DSS 3.2.1 Scope definition |

---

## 6. Software Assets

| Asset              | Control Type | Control Description                          | Compliance Mapping            |
| ------------------ | ------------ | -------------------------------------------- | ----------------------------- |
| OpenCart           | Logical      | Patch management, WAF protection             | OWASP Top 10, ISO A.14.2.3    |
| Wazuh, Snort, etc. | Logical      | Monitor logs, detect intrusions, send alerts | ISO A.12.4.1, PCI DSS Req. 10 |
| Antivirus          | Logical      | Auto-update enabled, scan frequency weekly   | ISO 27001 A.12.2.1            |

---

**Next Step:** We will compile a summary GRC report of Phase 2, summarizing all documents created so far.

Proceed to: `5_GRC_Summary_Report.md`
