# 8. Governance & Roles

## 8.1 Overview

Governance ensures that IT services are delivered in a controlled, consistent, and accountable manner. The NexaITSM platform defines clear roles, responsibilities, and accountability structures to support effective IT service management.

Governance also ensures:
- alignment with business goals
- compliance with policies and regulations
- effective decision-making
- accountability across teams

---

## 8.2 Key ITSM Roles

### Service Owner
Responsible for the overall performance, quality, and value of a service.

### Process Owner
Responsible for designing, maintaining, and improving ITSM processes.

### Service Desk Agent
First point of contact for users; handles incidents and service requests.

### Incident Manager
Oversees incident resolution and ensures minimal service disruption.

### Problem Manager
Manages root cause analysis and prevents recurring incidents.

### Change Manager
Controls and approves changes to minimize risk.

### Configuration Manager
Maintains the CMDB and ensures accurate asset data.

### Knowledge Manager
Ensures knowledge is captured, maintained, and reused.

### Continual Improvement Manager
Drives performance improvements using KPIs and feedback.

### DevOps Engineer
Implements CI/CD pipelines and automation.

### Site Reliability Engineer (SRE)
Ensures system reliability, monitors SLIs/SLOs, and reduces toil.

### Security Engineer
Implements security controls and DevSecOps practices.

### Supplier Manager
Manages external vendors and service providers.

### Platform Administrator
Maintains and configures the ITSM platform.

---

## 8.3 RACI Matrix

RACI defines:
- **R (Responsible):** Performs the work
- **A (Accountable):** Owns the outcome
- **C (Consulted):** Provides input
- **I (Informed):** Kept updated

### Key Activities RACI Table

| Activity | Service Desk | Incident Manager | Problem Manager | Change Manager | Service Owner | DevOps/SRE | Supplier |
|--------|--------------|-----------------|----------------|----------------|--------------|------------|----------|
| Incident Resolution | R | A | C | I | I | C | I |
| Problem Analysis | C | C | A | I | I | R | I |
| Change Approval | I | I | C | A | C | R | I |
| Service Request Fulfillment | R | I | I | I | A | C | I |
| CMDB Maintenance | I | I | I | C | A | R | C |
| Knowledge Management | R | C | C | I | A | C | I |
| KPI Monitoring | I | C | C | C | A | R | I |
| Supplier Escalation | I | C | I | I | A | C | R |

---

## 8.4 Supplier Management

The NexaITSM platform includes external vendors for:
- cloud services
- hardware procurement
- software licensing
- managed services

Supplier management ensures:
- clear contracts and SLAs
- performance monitoring
- escalation procedures
- accountability for service delivery

Integration with ITSM processes:
- incidents can be escalated to suppliers
- changes may involve vendor coordination
- supplier performance is tracked through KPIs

---

## 8.5 Governance Model

The governance model includes:

### Operational Level
- Service Desk
- Technical Support Teams
- DevOps and SRE teams

### Tactical Level
- Process Owners
- Change Advisory Board (CAB)
- Problem Review Meetings

### Strategic Level
- Service Owners
- IT Leadership
- Business Stakeholders

---

## 8.6 Decision-Making Structure

- Standard changes → automated approval  
- Normal changes → CAB approval  
- Emergency changes → ECAB approval  

Major incidents:
- escalated to Incident Manager
- involve cross-functional teams

---

## 8.7 Summary

The governance structure of the NexaITSM platform ensures that all ITSM activities are clearly defined, accountable, and aligned with business objectives.

By defining roles, responsibilities, and decision-making processes, the platform supports:
- efficient service delivery
- risk management
- compliance
- continuous improvement
