# Critical Business Services

| Document Information | Details |
|----------------------|---------|
| Document ID | ORG-005 |
| Version | 1.0 |
| Status | Approved |
| Prepared By | GRC Consulting Team |
| Client | FinSure Technologies Pvt. Ltd. |
| Module | Organization |
| Framework Alignment | ISO/IEC 27001:2022, NIST RMF Prepare, ISO 22301 |
| Classification | Internal |
| Last Updated | July 2026 |

---

# 1. Purpose

The purpose of this document is to identify the critical business services delivered by FinSure Technologies Pvt. Ltd. and establish their importance to business operations.

Identifying critical business services enables the organization to prioritize information security, risk management, business continuity, disaster recovery, and incident response activities based on business impact.

---

# 2. Scope

This document applies to all business services that are essential for delivering customer value, maintaining regulatory compliance, protecting organizational assets, and supporting operational resilience.

---

# 3. Definition

A **Critical Business Service (CBS)** is a service whose disruption would have a significant impact on customers, regulatory obligations, financial performance, or the organization's reputation.

Critical services receive the highest priority during:

- Risk Assessments
- Incident Response
- Business Continuity Planning
- Disaster Recovery
- Change Management
- Security Monitoring
- Third-Party Risk Management

---

# 4. Critical Business Services

## CBS-01 – Digital Payments Platform

### Description

The Digital Payments Platform enables customers to securely initiate, process, and monitor electronic payment transactions.

### Business Value

- Primary revenue-generating service.
- Core customer-facing platform.
- Supports payment processing and settlement.

### Business Impact if Unavailable

- Loss of revenue.
- Customer dissatisfaction.
- Transaction failures.
- Potential contractual breaches.
- Reputational damage.

### Service Owner

Head of Product

---

## CBS-02 – Merchant Portal

### Description

A secure web portal allowing merchants to manage accounts, monitor transactions, configure payment settings, and generate reports.

### Business Value

- Primary customer management interface.
- Supports daily merchant operations.

### Business Impact if Unavailable

- Reduced customer productivity.
- Increased support requests.
- Delayed business operations.

### Service Owner

Customer Success Manager

---

## CBS-03 – Financial Reporting Services

### Description

Provides automated reporting capabilities supporting financial operations, audit activities, and regulatory reporting.

### Business Value

- Supports financial decision-making.
- Enables compliance reporting.
- Facilitates audit readiness.

### Business Impact if Unavailable

- Delayed financial reporting.
- Compliance risks.
- Audit challenges.

### Service Owner

Chief Financial Officer (CFO)

---

## CBS-04 – Identity & Access Management Services

### Description

Provides centralized authentication and authorization for employees, administrators, and customers through Microsoft Entra ID.

### Business Value

- Enables secure system access.
- Protects organizational resources.
- Supports Zero Trust architecture.

### Business Impact if Unavailable

- Users unable to authenticate.
- Administrative access disruption.
- Increased operational downtime.

### Service Owner

IAM Lead

---

## CBS-05 – Customer Support Services

### Description

Provides technical assistance, incident reporting, and customer communication.

### Business Value

- Maintains customer satisfaction.
- Supports issue resolution.
- Enables business continuity during incidents.

### Business Impact if Unavailable

- Increased customer dissatisfaction.
- Delayed incident resolution.
- Reduced service quality.

### Service Owner

Customer Success Manager

---

# 5. Service Criticality Assessment

| Business Service | Criticality | Recovery Priority |
|------------------|------------|-------------------|
| Digital Payments Platform | Critical | Highest |
| Merchant Portal | High | High |
| Financial Reporting Services | High | High |
| Identity & Access Management | Critical | Highest |
| Customer Support Services | Medium | Medium |

---

# 6. Supporting Technology

The critical business services rely upon the following technology components:

- Microsoft Azure
- Azure Kubernetes Service (AKS)
- Microsoft Entra ID
- Microsoft Sentinel
- PostgreSQL
- Azure SQL Database
- React Web Application
- Node.js APIs
- .NET Backend Services
- GitHub Actions

Failure of these supporting technologies may directly impact service availability.

---

# 7. Third-Party Dependencies

Several critical services depend upon external providers.

| Service | Third-Party Dependency |
|---------|------------------------|
| Cloud Hosting | Microsoft Azure |
| Identity Services | Microsoft Entra ID |
| Source Code Platform | GitHub |
| Productivity Services | Microsoft 365 |

These dependencies are governed under the Third-Party Risk Management program.

---

# 8. Risk Considerations

The following risks have the potential to impact critical business services:

- Cloud infrastructure outage.
- Identity compromise.
- Application vulnerabilities.
- Database failure.
- Ransomware attacks.
- Distributed Denial-of-Service (DDoS) attacks.
- Third-party service disruption.
- Insider threats.

These risks are formally assessed within the Enterprise Risk Management process.

---

# 9. Relationship to the GRC Program

This document supports:

- Asset Identification
- Business Impact Analysis (BIA)
- Risk Assessment
- Risk Treatment
- Incident Response
- Business Continuity Planning
- Disaster Recovery Planning
- Third-Party Risk Management
- Executive Risk Reporting

---

# 10. Related Documents

| Document ID | Document |
|-------------|----------|
| ORG-001 | Company Profile |
| ORG-004 | Technology Architecture |
| AST-001 | Asset Inventory *(To Be Developed)* |
| RISK-001 | Risk Assessment Methodology *(To Be Developed)* |
| BCP-001 | Business Continuity Plan *(To Be Developed)* |

---

# 11. Approval

| Role | Status |
|------|--------|
| Chief Executive Officer | ✔ Approved |
| Chief Information Security Officer | ✔ Approved |
| GRC Program Manager | ✔ Approved |

---

**End of Document**