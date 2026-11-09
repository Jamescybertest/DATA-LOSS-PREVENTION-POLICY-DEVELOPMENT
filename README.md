
# Data Loss Prevention (DLP) Policy | MapleTrust Financial Services


### Project Overview

This policy establishes requirements to protect MapleTrust Financial Services' sensitive information from unauthorized disclosure, transfer, or loss.  The policy aims to reduce the risk of data breaches, protect customer financial information, and support compliance with applicable data protection requirements.  

### Project Objectives

- Establish security requirements for protecting sensitive information.
- Define roles and responsibilities for data protection.
- Align DLP policy requirements with ISO/IEC 27001:2022.
- Establish requirements for control testing and compliance monitoring.

### Framework and References

- **ISO/IEC 27001:2022:** Annex A.8.12 - Data leakage prevention.
- **SANS Institute:** Data Inventory Management Policy Template
- **Internal Policy:** MTFS-DLP-001.

### Project Deliverables

- **DLP Policy:** Nine safeguards covering data inventory, classification, data transfer protection, monitoring, access control, encryption, control testing, and policy exceptions.
- **ISO 27001 Control Mapping:** Policy safeguards mapped to relevant Annex A controls.

  
### Control Effectiveness Testing

To assess the effectiveness of DLP-03, three simulated tests were designed to verify whether DLP controls prevent unauthorized transfers of sensitive information.

| Test ID | Environment | Result |
|---|---|---|
| DLP-T01 | Email | Pass |
| DLP-T02 | Endpoint (USB) | Fail |
| DLP-T03 | Cloud Application | Pass |

### Findings and Remediation

**Finding ID:** DLP-T02

**Finding:** The endpoint DLP control failed to block an unauthorized USB transfer of sensitive information.

**Risk:** Sensitive customer information could be transferred to unauthorized devices.

**Risk Rating:** High (Initial)

**Corrective Action:** Review and update endpoint DLP configurations to prevent unauthorized transfers.

**Status:** Open - Pending Remediation and Retesting.

### Compliance Summary

- **Tests:** 3
- **Passed:** 2
- **Failed:** 1
- **Test Pass Rate:** 66.7%

### Conclusion

Developed a DLP policy with nine safeguards aligned with ISO/IEC 27001:2022 Annex A controls.  The simulated control assessment identified one deficiency affecting endpoint DLP protection. Remediation and retesting are required before the finding can be closed.

### **Note:** MapleTrust Financial Services is a fictional organization, Control testing results are simulated for portfolio purposes.

