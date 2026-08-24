# Darwin-GRC-HIPAA-Security-Risk-Assessment

## Project Overview

This project simulates a HIPAA Security Rule risk assessment for a fictional healthcare technology organization called **CloudNova Health Systems**.

The goal is to evaluate administrative, physical, and technical safeguards used to protect electronic protected health information (ePHI), identify compliance gaps, assess security risk, review business-associate controls, and develop remediation recommendations.

This project demonstrates practical GRC skills including:

- HIPAA Security Rule
- Security risk assessment
- Administrative safeguards
- Physical safeguards
- Technical safeguards
- ePHI protection
- Access control review
- Audit control review
- Business associate risk
- Gap analysis
- Risk registers
- Remediation planning
- Compliance documentation

## Business Scenario

CloudNova Health Systems is a fictional healthcare technology organization that stores and processes electronic protected health information.

The organization uses:

- Microsoft 365
- Microsoft Azure
- Cloud-hosted healthcare applications
- Role-based access control
- Multi-Factor Authentication
- Endpoint protection
- Centralized logging
- Security awareness training
- Backup and recovery systems
- Third-party service providers

Because ePHI is involved, the organization must maintain appropriate security safeguards to protect the confidentiality, integrity, and availability of sensitive healthcare information.

## Assessment Scope

The assessment focuses on HIPAA Security Rule safeguards including:

- Security Management Process
- Assigned Security Responsibility
- Workforce Security
- Information Access Management
- Security Awareness and Training
- Security Incident Procedures
- Contingency Planning
- Evaluation
- Business Associate Management
- Facility Access Controls
- Workstation Security
- Device and Media Controls
- Access Control
- Audit Controls
- Integrity
- Person or Entity Authentication
- Transmission Security

## Safeguard Categories

### Administrative Safeguards

Administrative safeguards include policies and procedures used to manage security risk and workforce responsibilities.

Examples include:

- Risk analysis
- Risk management
- Security responsibility
- Workforce access
- Security awareness
- Incident response
- Contingency planning
- Business associate oversight

### Physical Safeguards

Physical safeguards protect facilities, workstations, devices, and media.

Examples include:

- Facility access controls
- Workstation use
- Workstation security
- Device and media controls

### Technical Safeguards

Technical safeguards protect systems containing ePHI.

Examples include:

- Access control
- Unique user identification
- Emergency access
- Audit controls
- Authentication
- Integrity controls
- Transmission security

## Assessment Method

Each safeguard is evaluated using:

1. HIPAA Safeguard
2. Security Objective
3. Current State
4. Compliance Status
5. Risk Level
6. Evidence Expected
7. Gap Identified
8. Recommended Remediation

## Compliance Status Ratings

- Implemented
- Partial
- Missing
- Not Tested

## Key Findings

| Safeguard Area | Category | Status | Risk |
|---|---|---|---|
| Security Risk Analysis | Administrative | Partial | High |
| Risk Management Process | Administrative | Partial | High |
| Workforce Access Reviews | Administrative | Partial | High |
| Security Awareness Training | Administrative | Implemented | Low |
| Incident Response Testing | Administrative | Partial | High |
| Contingency Plan Testing | Administrative | Partial | Medium |
| Business Associate Review | Administrative | Partial | High |
| Workstation Security | Physical | Implemented | Low |
| Device and Media Disposal | Physical | Partial | Medium |
| Unique User Identification | Technical | Implemented | Low |
| MFA / Authentication | Technical | Partial | High |
| Audit Controls | Technical | Implemented | Low |
| Log Review | Technical | Partial | Medium |
| Transmission Security | Technical | Implemented | Low |

## Risk Assessment Method

Risk is calculated using:

Risk Score = Likelihood × Impact

### Risk Ratings

- 1–4 = Low
- 5–10 = Medium
- 11–15 = High
- 16–25 = Critical

## Example Risks

| Risk | Likelihood | Impact | Score | Rating |
|---|---:|---:|---:|---|
| Unauthorized access to ePHI | 3 | 5 | 15 | High |
| Former employee retains access | 3 | 5 | 15 | High |
| Business associate compromise | 3 | 5 | 15 | High |
| Incomplete incident response testing | 3 | 4 | 12 | High |
| Backup recovery failure | 2 | 5 | 10 | Medium |
| Incomplete audit-log review | 2 | 4 | 8 | Medium |
| Improper device disposal | 2 | 4 | 8 | Medium |

## Example Finding

### Workforce Access Review

**Current State:**  
Role-based access is implemented, but recurring workforce access reviews are inconsistent.

**Risk:**  
Employees may retain access to ePHI that is no longer required for their job responsibilities.

**Risk Level:**  
High

**Recommendation:**  
Perform quarterly access reviews, validate business need, remove unnecessary permissions, and retain review evidence.

## Business Associate Review

Third-party vendors that create, receive, maintain, or transmit ePHI should be evaluated for security risk.

The review focuses on:

- Security questionnaires
- Business Associate Agreements
- Access to ePHI
- Encryption
- Incident notification
- Security controls
- Subcontractor oversight
- Recurring reassessment

## Evidence Examples

Supporting evidence may include:

- Security risk analysis
- Risk register
- Access review reports
- MFA configuration screenshots
- Audit-log screenshots
- Security training reports
- Incident response plan
- Tabletop exercise reports
- Backup restoration reports
- Business Associate Agreements
- Vendor security questionnaires
- Device disposal records

## Remediation Priorities

1. Complete and document recurring HIPAA security risk analysis
2. Improve workforce access reviews
3. Enforce strong authentication for privileged and remote access
4. Strengthen business associate security reviews
5. Conduct annual incident response exercises
6. Test contingency and recovery procedures
7. Improve audit-log review documentation
8. Formalize device and media disposal controls

## Repository Structure

Darwin-GRC-HIPAA-Security-Risk-Assessment/
│
├── README.md
├── hipaa_safeguard_matrix.csv
├── hipaa_gap_assessment.csv
├── hipaa_risk_register.csv
├── business_associate_review.csv
├── security_findings.md
├── remediation_plan.md
└── evidence/

## Skills Demonstrated

- HIPAA Security Rule
- Governance, Risk, and Compliance
- Security Risk Assessment
- ePHI Protection
- Administrative Safeguards
- Physical Safeguards
- Technical Safeguards
- Access Control
- Audit Controls
- Business Associate Risk
- Incident Response
- Contingency Planning
- Gap Analysis
- Risk Registers
- Remediation Planning
- Compliance Documentation

## Project Goal

The goal of this project is to demonstrate practical HIPAA Security Rule GRC work by reviewing administrative, physical, and technical safeguards, identifying risks and compliance gaps, evaluating business-associate security, and developing remediation recommendations.
