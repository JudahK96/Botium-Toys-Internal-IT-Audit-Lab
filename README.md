# Botium Toys IT Audit Lab

## Objective
Assess existing assets and determine which controls and compliance best practices that need to be implemented to improve Botium Toys’ security posture.

The scope of this audit is defined as the entire security program at Botium Toys. This includes their assets like employee equipment and devices, their internal network, and their systems. You will need to review the assets Botium Toys has and the controls and compliance practices they have in place.

### Skills Learned

- Interal Security audit
- Control and compliance checklist.

### Tools Used

- (CSF) NIST Cybersecurity Framework
- (PCI DSS) Payment Card Industry Data Security Standard
- (GDPR) General Data Protection Regulation
- (SOC1/SOC2) System and Organizations Controls


## Botium Toys Overview
![Screenshot 2024-05-27 145515](https://github.com/JudahK96/Botium-Toys-Internal-IT-Audit-Lab/assets/170769994/2006f802-49d5-4890-99c9-c1bd3b109ff6)


## Audit Assessment
### Copmpliance Standards
| Y/N Compliance | Best practice | Explanation |
|----------------|---------------|-------------|
| N | Least Privilege | All employees have access to customer data; privileges need to be limited |
| N | Disaster recovery plans | Disaster recovery plan needs to be implamented for business continuity |
| N | Password policies | Minimal password requirements |
| N | Separation of duties | CEO runs payroll and operations; risk of fraud/acess to critical data |
| Y | Firewall | The existing firewall blocks traffic based on an appropriately defined set of security rules. |
| N | Intrusion detection system (IDS) | IT department needs an IDS in place to help identify possible intrusions |
| N | Backups | IT department needs tohave backups of critical data |
| Y | Antivirus software | Antivirus software is installed and monitored regularly |
| N | Manual monitoring, maintenance, and intervention for legacy systems  | Legacy systems aremonitored and maintained but no scheduale for this task and procedures/policies related to intervention are unclear, which could place these systems at risk of a breach |
| N | Encryption | Not in use |
| N | Password management system | No password management system in place |
| Y | Locks (offices, storefront, warehouse) | store’s physical location has locks |
| Y | Closed-circuit television (CCTV) surveillance | CCTV is installed/functioning at sotre's |
| Y | Fire detection/prevention (firealarm, sprinkler system, etc.) | Functioning fire detection and prevention system. |

### (PCI DSS) Payment Card Industry Data Security Standard
| Y/N Compliance | Best practice | Explanation |
|----------------|---------------|-------------|
| N | Only authorized users have access to customers’ credit card information | All employees have access to the company’s internal data |
| N | Credit card information is accepted, processed, transmitted, and stored internally, in a secure environment | Credit card information is not encrypted and all employees currently have access to internal data, including customers’ credit card information |
| N | Implement data encryption procedures to better secure credit card transaction touchpoints and data | The company does not currently use encryption to better ensure the confidentiality of customers’ financial information |
| N | Adopt secure password management policies | Password policies are nominal and no password management |

### (GDPR) General Data Protection Regulation
| Y/N Compliance | Best practice | Explanation |
|----------------|---------------|-------------|
| N | E.U. customers’ data is kept private/secured | Does not currently use encryption to better ensure the confidentiality of customers’ financial information |
| Y | There is a plan in place to notify E.U. customers within 72 hours if their data is compromised/there is a breach | Plan to notify E.U. customers within 72 hours of a data breach |
| N | Ensure data is properly classified and inventoried | Current assets have been inventoried/listed, but not classified |
| Y | Enforce privacy policies, procedures, and processes to properly document and maintain data | Privacy policies, procedures, and processes have been developed and enforced among IT team members and other employees |

### (SOC1/SOC2) System and Organizations Controls
| Y/N Compliance | Best practice | Explanation |
|----------------|---------------|-------------|
| N | User access policies are established | Controls of Least Privilege and separation of duties are not currently in place; all employees have access to internally stored data |
| N | Sensitive data (PII/SPII) is confidential/private | Encryption is not currently used to better ensure the confidentiality of PII/SPII |
| Y | Data integrity ensures the data is consistent, complete, accurate, and has been validated | Data integrity is in place |
| N | Data is available to individuals authorized to access it | data is available to all employees, authorization needs to be limited to only the individuals who need access to it |
