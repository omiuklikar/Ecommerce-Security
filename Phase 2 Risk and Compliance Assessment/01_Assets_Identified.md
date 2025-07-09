# Asset Identification 

This document outlines the asset inventory for the simulated e-commerce company. Assets are categorized into six groups as per industry-standard risk assessment models.

---

## 1. Physical Assets

| Asset                 | Description                                                              |
| --------------------- | ------------------------------------------------------------------------ |
| Desktop Firewall      | Physical desktop system running a Linux-based firewall                   |
| Employee Laptops      | 100 personal laptops used by employees and interns with virtual machines |
| Office Infrastructure | Servers, networking switches, routers, cables, physical storage drives   |
| Secure Storage        | Cabinets and shredders for storing/discarding sensitive paper records    |
| Restricted Zones      | Areas with access control for cardholder data / sensitive infrastructure |

---

## 2. Digital Assets

| Asset                  | Description                                                            |
| ---------------------- | ---------------------------------------------------------------------- |
| Wireless Networks      | Unsecured Wi-Fi requiring encryption and access control                |
| E-commerce Data        | Customer data, product data, transaction logs simulated using OpenCart |
| Cardholder Information | PCI-sensitive data if card processing simulated                        |
| Personal Data          | Employee and customer data under GDPR and DPDPA scope                  |
| System Logs & Backups  | Archived data for compliance (retention minimum 1 year as per PCI DSS) |

---

## 3. People Assets

| Asset                 | Description                                                |
| --------------------- | ---------------------------------------------------------- |
| Employees             | Including interns and staff (100 users with devices)       |
| Cybersecurity Team    | Responsible for implementing controls and risk assessments |
| DPO                   | Data Protection Officer (if applicable as per DPDPA)       |
| Training Participants | Individuals trained on ISO, GDPR, PCI DSS, etc.            |

---

## 4. Paper Assets

| Asset                   | Description                                                    |
| ----------------------- | -------------------------------------------------------------- |
| Risk Assessment Reports | Documentation of threats, vulnerabilities, and controls        |
| Compliance Records      | For ISO 27001, GDPR, PCI DSS, DPDPA, and IT Act 2000           |
| Employee Documents      | Training logs, agreements, HR files                            |
| Audit Trails            | Printed reports of audits and incidents (if stored physically) |
| Policies                | Printed security policies, SOPs, and guidelines                |

---

## 5. Service Assets

| Asset              | Description                                   |
| ------------------ | --------------------------------------------- |
| Google Cloud       | Free tier used for hosting/log processing     |
| Internet Provider  | ISP service for office and unsecured wireless |
| Payment Gateways   | Third-party (if payment simulation used)      |
| Compliance Support | Tools/services to support regulatory audits   |

---

## 6. Software Assets

| Asset          | Description                                          |
| -------------- | ---------------------------------------------------- |
| OpenCart       | E-commerce CMS platform deployed locally             |
| Ubuntu VM      | Guest OS used for simulation and security setup      |
| Security Tools | Snort, Wazuh, ZAP, etc., for scanning and monitoring |
| Antivirus      | Endpoint protection installed on VMs/laptops         |
| Access Control | LDAP/Active Directory simulation if applicable       |

---

**Next Step:** Identify threats and vulnerabilities against each asset type.

Proceed to: `2_Threats_and_Vulnerabilities.md`
