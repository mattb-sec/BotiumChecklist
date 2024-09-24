Following up on the risk assessment I performed for Botium Toys, I will now take a look at their current controls and evaluate whether the necessary controls are implemented and whether they are compliant with payment processing and data policies.

# Security Controls Assessment Checklist

| Yes        | No         | Control |
|:-------------|:------------------|:------|
|  | X | Least Privilege  |
|  |  X| Disaster recovery plans  |
|  | X | Password policies   |
|  | X | Separation of duties  |
| X |  |  Firewall |
|  | X |  Intrusion Detection System (IDS) |
|  | X |  Backups |
| X |  | Antivirus software  |
|  | X | Manual monitoring, maintenance, and intervention for legacy systems  |
|  | X |  Encryption |
|  | X |  Password management system |
| X |  |  Locks (office, storefront, warehouse) |
| X |  | Closed-circuit television (CCTV) surveillance  |
| X |  |  Fire detection/prevention (fire alarm, sprinkler system, etc.) |

# Payment Card Industry Data Security Standard (PCI DSS)

| Yes        | No         | Best Practice |
|:-------------|:------------------|:------|
|  | X | Only authorized users have access to customer's credit card information.  |
|  | X |  Credit card information is stored, accepted, processed, and transmitted internally, in a secure environment. |
|  | X | Implement data encryption procedures to better secure credit card transaction touchpoints and data.  |
|  | X | Adopt secure password management policies.  |

# General Data Protection Regulation (GDPR)

| Yes        | No         | Best Practice |
|:-------------|:------------------|:------|
|  | X | E.U. customers' data is kept private/secured. |
| X |  | There is a plan in place to notify E.U. customers within 72 hours if their data is compromised/there is a breach. |
|  | X | Ensure data is properly classified and inventoried. |
| X |  | Enforce privacy policies, procedures, and processes to properly document and maintain data. |

# System and Organizations Controls (SOC type 1, SOC type 2)

| Yes        | No         | Best Practice |
|:-------------|:------------------|:------|
|  | X |  User access policies are established. |
|  | X |  Sensitive data (PII/SPII) is confidential/private. |
| X |  |  Data integrity ensures the data is consistent, complete, accurate, and has been validated. |
|  | X |  Data is available to individuals authorized to access it. |

# Recommendations

- Implement controls pertaining to least privilege and separation of duty. Customer PII should be stored on an as-needed basis and only be accessible to those who would need to review it.

- Implement data encryption so that stored data can remain secure, even if compromised.

- Employ an intrusion detection system to ensure only authorized connections are on the company network.

- Regularly backup critical data and employ a disaster recovery plan.
  
- Enforce stricter password policies and multi-factor authentication to ensure user accounts are secure. Also recommend instruction of proper password hygiene so users have a uniform and secure way to store their passwords, should they forget them.

- Lastly, employ a password management system so the IT team can efficiently address user password issues.

