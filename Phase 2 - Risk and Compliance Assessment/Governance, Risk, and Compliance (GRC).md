# Governance, Risk, and Compliance (GRC) Summary – Phase 2

This document summarizes the findings from the asset identification, risk analysis, and control implementation processes carried out as part of Phase 2 of the E-commerce Security Project.

---

## 🏛 Governance

The organization has initiated a cybersecurity governance framework that includes:

* **Defined Roles & Responsibilities**:

  * Security Lead
  * DPO (for DPDPA compliance)
  * IT Administrator

* **Security Policies Developed**:

  * Data Protection Policy
  * Acceptable Use Policy
  * Incident Response Policy

* **Awareness Training**: Ongoing training sessions are conducted for all personnel.

---

## ⚖ Compliance Summary

| Standard    | Key Areas Addressed                                        | Status              |
| ----------- | ---------------------------------------------------------- | ------------------- |
| ISO 27001   | Asset Management, Risk Treatment, Access Control           | Partially Compliant |
| PCI DSS     | Cardholder Data Protection, Log Retention, Access Controls | Partially Compliant |
| DPDPA       | Data Minimization, Consent, Privacy Notices                | Not Yet Compliant   |
| IT Act 2000 | Cybersecurity, Authentication, Electronic Records          | Partially Compliant |

**Note:** Controls are in place but require formal audits and documentation to become fully compliant.

---

## 📊 Risk Management Summary

| Asset Category  | Risk Level (Before Controls) | Risk Level (After Controls) |
| --------------- | ---------------------------- | --------------------------- |
| Physical Assets | High                         | Medium                      |
| Digital Assets  | High                         | Medium                      |
| People Assets   | Medium                       | Low                         |
| Paper Assets    | Medium                       | Low                         |
| Service Assets  | High                         | Medium                      |
| Software Assets | High                         | Medium                      |

---

## ✅ Control Effectiveness Overview

* **Administrative Controls**:

  * Implemented successfully for onboarding, training, and policy management.

* **Physical Controls**:

  * Mostly theoretical; mock access logs and restricted zone maps prepared.

* **Logical Controls**:

  * Configured tools like Snort, Wazuh, LDAP (if applicable) to manage access and detect threats.

---

## 📌 Next Steps for Compliance

1. Conduct a formal internal audit.
2. Implement centralized logging and real-time alerts.
3. Deploy encryption at rest and in transit.
4. Finalize data privacy documentation for DPDPA.

---

**Deliverable**: This concludes the Governance, Risk, and Compliance reporting for Phase 2.

Proceed to Phase 3: Identity and Access Security. ✅
